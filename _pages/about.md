---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

大家好！我是 **刘一澎**，目前是本科三年级，就读于[兰州大学信息科学与工程学院](https://xxxy.lzu.edu.cn/)计算机科学与技术专业。

我对人工智能充满热情，自入学以来，积极参与各类科研项目和学术竞赛，曾获得雷军计算机奖学金和多项校内外奖项。在科研方面，我参与并主导了多个项目，包括但不限于**图神经网络**、**计算机视觉**、**大语言模型**、**人工智能安全**等领域。

# 🎓 Education Background

- **排名：** GPA排名：**2/108 (1.8%)**、加权平均分排名：**2/108 (1.8%)**  
- **成绩均分：** GPA：4.03/5.0、加权平均分：90.11/100  
- **语言能力：** 已通过 CET4 和 CET6，有独立撰写并发表全英文学术论文（2篇，均已录用）的经历  
- **核心课程：** 高等数学 (93)、线性代数 (97)、概率论与数理统计 (94)、数据结构 (97, 95)、计算机编程 (理论) (94, 100)、计算机编程 (实践) (97, 100)、数据管理 (99, 96)、信息可视化 (97)  
- **编程能力：** 熟练掌握 C/C++ 和 Python，熟悉算法与数据结构，具备强大的抽象能力和良好的代码风格；熟练使用 PyTorch、Numpy、Pandas，熟悉各种深度学习模型及其实现；长期担任数学建模的编程手，并多次获得数模国赛和“华数杯”等高水平数学建模竞赛一等奖  
- **开发工具：** VS Code, PyCharm, Jupyter Notebook, LaTeX (Overleaf), Git  
- **在校荣誉：** 曾获**2021-2022年度国家奖学金**（该年度年级成绩排名为：1/108），兰州大学优秀学生一等奖学金（3%）、兰州大学学生标兵称号，以及多项竞赛奖金，在校累计获奖金额超过30000元  

# 🔥 News

# 🧪 Research Experience

## **💡💡FuzzLLM - 主动发现LLM中越狱漏洞的新型通用模糊测试框架** <sub> &nbsp;&nbsp;[[项目主页]](https://mumuyeye.github.io/FuzzLLM_demo/) | [[项目代码]](https://github.com/mumuyeye/FuzzLLM/tree/muye)</sub>

- **时间：** 2023.6 - 2023.11
- **领域：** **大语言模型**，**人工智能安全**
- **角色：** 团队(主力成员)
- **针对痛点**：
  1. LLMs的普及引入了安全风险，特别是越狱漏洞问题。
  2. 尽管LLM提供者如OpenAI努力通过更新模型版本和加强防御机制来修补这些漏洞，但这场攻防之间的猫鼠游戏显示出模型所有者往往处于被动防御的位置，只有在攻击被证明有效后才能开发出缓解措施。
  3. 安全微调机制的有效性受到高质量标记数据稀缺的限制，而且现有的工作往往未能全面公开其测试数据集，导致开发者无法针对整个越狱类别进行防御，只能对已知的个别提示及其变体进行防护。

* **我们的方法**：
  1. **引入FuzzLLM**：采用黑盒模糊测试方法，通过自动生成大量随机但结构化的输入提示来测试模型，无需访问或了解模型的内部结构。
  2. **模板、约束和问题集**：FuzzLLM通过将越狱提示分解为这些元素，基于现有研究成果，自动构造新的越狱提示。
  3. **提高测试全面性**：这种方法不仅增加了测试的广度和深度，还帮助模型提供者提前识别和修复潜在的安全漏洞。
* **项目成果**：
  * 已与复旦团队研发的统一越狱框架EasyJailbreak取得联系并加入其开源框架。

## **💡DtFormer - 基于自训练范式的恶劣天气场景鲁棒语义分割** <sub> &nbsp;&nbsp;[[项目主页]](https://mumuyeye.github.io/DtFormer/README.html) | [[项目代码]](https://github.com/mumuyeye/DtFormer)</sub>

- **时间：** 2023.8 - 2024.1
- **领域：** **计算机视觉**，**域适应**
- **角色：** 第二作者 / 团队(主力成员)
- **针对痛点**：
  1. 当今语义分割模型大多数基于清晰场景下的图片进行训练，极少考虑到恶劣天气影响，这导致其在恶劣天气下的表现往往不佳。这其中尤以雾天场景语义分割最甚。
  2. 目前，许多方法使用领域自适应来将分割知识从清晰的场景转移到模糊的场景。但由于雾导致的图像质量下降以及不同城市风格之间存在的较大域差距，这些方法均效果不佳。
  3. 最新的研究试图引入一个中间域来解耦域间隙，并逐步完成雾场景的语义分割，但这种方法对中间域信息的探索仍然不足。

* **我们的方法**：
  1. **观察和反应**：基于对语义分割模型在恶劣天气视觉场景中局限性的观察，我们选择了基于多层次教师自训练的方法。
  2. **逐步解决域差距**：通过将大的域差距拆解为若干小的域差距，分配给对应的不同任务，控制模型在自训练过程中的域差距。
  3. **交替训练策略**：结合交替训练的策略，使模型能够充分利用来自源域的参考信息，并逐步展示出从源域迁移到目标域的分割能力，特别是在抗雾干扰性方面表现良好。
* **项目成果**：
  * 相关工作已经完成，论文正处于写作阶段，预计完稿后投稿于ICASSP 2024

# 🏆 Competition Awards

- **“华数杯”全国大学生数学建模竞赛：一等奖** *国家级* 2023 &nbsp;&nbsp;[[证明]](https://mumuyeye.github.io/docs/2024jishe.pdf)  
- **全国大学生数据统计与分析竞赛：一等奖** *国家级* 2023 &nbsp;&nbsp;[[证明]](http://www.hzbmmc.com/views/award/award-item.html?id=1663113745191030785&navigate=inform)  
- **“英语世界”杯全国大学生英语语法大赛：一等奖** *国家级* 2023 &nbsp;&nbsp;[[证明]](https://x-static.lanqiao.cn/upload/202405/courseimg/86b0fcef-64d9-4bc3-ac81-b5f776a44c00.pdf)  
- **全国大学生数学竞赛：二等奖** *国家级* 2023 &nbsp;&nbsp;[[证明]](https://mumuyeye.github.io/docs/shujingguoer.png)  
- **“互联网＋”大学生创新创业大赛：金奖** *省部级* 2023 &nbsp;&nbsp;[[证明]](https://mumuyeye.github.io/docs/2024CCCCASTxuanbasai.pdf)  
- **全国大学生数学建模竞赛：一等奖** *省部级* 2023 &nbsp;&nbsp;[[证明]](https://mumuyeye.github.io/docs/2024CRAIChubei.pdf)  
- **全国大学生数学建模竞赛：一等奖** *省部级* 2022 &nbsp;&nbsp;[[证明]](https://mp.weixin.qq.com/s/HNQI1J82cJGcGI2ybIIoXg)  

# 🥇 Scholarships and Honors

- *2021-2022* **国家奖学金** (该年度年级成绩排名：1/108) *兰州大学* &nbsp;&nbsp;[[证明]](..\docs\national_scholarship_2021_2022.pdf)  
- *2021-2022* **兰州大学优秀学生一等奖学金** (获奖率：3%) *兰州大学* &nbsp;&nbsp;[[证明]](..\docs\excellent_student_scholarship.pdf)  
- *2021-2022* **兰州大学学生标兵** *兰州大学* &nbsp;&nbsp;[[证明]](..\docs\student_pacesetter.pdf)  

# 📖 Educations

- *2021.9 -*, 本科生, 兰兰州大学信息科学与工程学院  专业：计算机科学与技术.
