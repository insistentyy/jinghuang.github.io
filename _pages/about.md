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

<font face="Times New Roman">
<div style="text-align: center; margin-bottom: 30px;">
    <h1 style="font-family: Georgia, serif; font-size: 2.5em; color: #2a4d69;">刘一澎</h1>
    <p style="font-size: 1.25em; color: #4b86b4;">兰州大学信息科学与工程学院 · 计算机科学与技术专业 · 本科三年级</p>
    <hr style="width: 100%; border: 1px solid #4b86b4;">
</div>

<p style="text-align: justify; font-size: 1.15em; margin-bottom: 30px;">
    大家好！我是 <b>刘一澎</b>，目前是本科三年级学生，专注于人工智能和计算机科学的交叉研究领域。
    自入学以来，我积极参与各类科研项目和学术竞赛，并获得了多项荣誉与奖项。我特别关注
    <b>图神经网络</b>、<b>计算机视觉</b>、<b>大语言模型</b>、以及<b>人工智能安全</b>等领域的前沿研究。
</p>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🎓 教育背景</h2>
<ul style="font-size: 1.15em; margin-bottom: 30px;">
    <li><b>排名：</b> GPA排名：<b>2/108 (1.8%)</b>、加权平均分排名：<b>2/108 (1.8%)</b></li>
    <li><b>成绩均分：</b> GPA：4.03/5.0、加权平均分：90.11/100</li>
    <li><b>语言能力：</b> 通过 CET4 和 CET6，独立撰写并发表两篇全英学术论文（均已被录用）</li>
    <li><b>核心课程：</b> 高等数学 (93)、线性代数 (97)、商务统计（即: 概率论与数理统计） (94)、数据结构 (97, 95)、计算机编程 (理论) (94, 100)、计算机编程 (实践) (97, 100)、数据管理 (99, 96)、信息可视化 (97)</li>
    <li><b>编程能力：</b> 精通 C/C++ 和 Python，熟悉算法与数据结构；精通深度学习模型的实现，长期担任数学建模编程手</li>
    <li><b>开发工具：</b> VS Code, PyCharm, Jupyter Notebook, LaTeX (Overleaf), Git</li>
    <li><b>在校荣誉：</b> 国家奖学金获得者 
        <a href="https://samer-hue.github.io/docs/guojiang.pdf" style="font-size: 0.8em; color: #4b86b4;">[国奖证书]</a>，
        兰州大学优秀学生一等奖学金，兰州大学学生标兵称号
    </li>
</ul>



<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🧠 科研经历 - 图神经网络</h2>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">DicTED - 基于预训练嵌入蒸馏的字典图神经网络</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://samer-hue.github.io/DicTED/README.html" style="color: #4b86b4;">[项目主页]</a> | <a href="https://github.com/Samer-hue/DicTED" style="color: #4b86b4;">[项目代码]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2023.3 - 2024.3</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 图神经网络，知识蒸馏</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 独立第一作者</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>时序图学习通过引入时间维度来扩展传统图学习的能力，但现有方法在获取多源信息时复杂度较高。</li>
        <li>字典时序图网络虽然通过存储邻域信息优化了性能，但对初始特征的依赖可能导致冷启动问题，并且频繁更新会引发灾难性遗忘。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li><b>预训练嵌入蒸馏：</b> 构建基于预训练嵌入蒸馏的字典时序图网络，通过聚合多个预训练教师模型生成嵌入，解决冷启动和灾难性遗忘问题。</li>
        <li><b>优化策略：</b> 将先验特征与原始特征结合，增强模型初始化效果；通过对齐嵌入损失和预测分数损失提高模型性能。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>成果：</b></p>
    <ul style="font-size: 1.15em;">
        <li>在多个真实数据集上，DicTED展示了优于现有SOTA方法的性能表现。</li>
        <li>作为独立第一作者的论文已被ICIC 2024 (CCF-C) 录用并发表。<a href="https://link.springer.com/chapter/10.1007/978-981-97-5678-0_29" style="color: #4b86b4;">[论文全文]</a></li>
    </ul>
</div>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">基于拓扑能量的联邦图后门攻击防御策略</h3>
    <p style="font-size: 1.15em;"><b>时间：</b> 2024.3 - 2024.8</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 图神经网络，联邦学习，后门攻击防御</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 共同第一作者</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>联邦图学习通过协同训练保护数据隐私，但其分布式特性引入了后门攻击的安全风险。</li>
        <li>现有防御方法在联邦图学习环境下效果不佳，尤其在大规模恶意客户端场景中。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li><b>拓扑能量客户端聚类：</b> 通过量化客户端数据分布的差异，识别潜在的恶意客户端。</li>
        <li><b>拓扑能量相似性传播：</b> 构建能量图，解耦恶意和良性客户端的能量元素，提升防御效果。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>成果：</b></p>
    <ul style="font-size: 1.15em;">
        <li>在多个场景下的实验表明，我们的方法优于当前的SOTA方法。</li>
        <li>论文正在撰写中，预计投稿至ICLR 2025。</li>
    </ul>
</div>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🖼️ 科研经历 - 计算机视觉</h2>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">FreeMRISeg - 磁共振图像分割</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://samer-hue.github.io/MRI-Segmentation/README.html" style="color: #4b86b4;">[项目主页]</a> | <a href="https://github.com/Samer-hue/MRI-Segmentation" style="color: #4b86b4;">[项目代码]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2022.9 - 2022.12</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 计算机视觉，医工交叉</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 团队负责人</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>深度学习在医学图像处理中的应用广泛，但训练分割模型需要大量标注数据，获取成本高。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li><b>弱监督语义分割：</b> 设计一个利用图像级标签作为监督的弱监督语义分割模型，减少对手动标注的依赖。</li>
        <li><b>分类与分割结合：</b> 通过分类生成像素级标签，并将其用于分割任务。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>成果：</b></p>
    <ul style="font-size: 1.15em;">
        <li>该项目成功申请为“中央高校基本科研业务专项资金”本科生项目。</li>
    </ul>
</div>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">PDGPSeg - 基于渐进式域间隙解耦的大雾场景语义分割</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://samer-hue.github.io/PDGPSeg/README.html" style="color: #4b86b4;">[项目主页]</a> | <a href="https://github.com/Samer-hue/PDGPSeg" style="color: #4b86b4;">[项目代码]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2023.12 - 2024.8</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 计算机视觉，域适应</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 团队主力成员 / 第三作者</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>大多数语义分割模型在清晰场景下训练，但在雾天等恶劣天气条件下表现较差。</li>
        <li>现有的领域自适应技术效果有限，特别是在不同城市风格的图像之间。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li><b>多层次教师自训练：</b> 通过将大的域间隙拆解为多个小的域间隙，控制模型的自训练过程。</li>
        <li><b>交替训练策略：</b> 结合源域参考信息，逐步掌握从源域到目标域的分割能力。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>成果：</b></p>
    <ul style="font-size: 1.15em;">
        <li>获得了中国机器人及人工智能大赛全国一等奖。<a href="https://samer-hue.github.io/docs/AWARDCRAICguo.pdf" style="color: #4b86b4;">[获奖证书]</a></li>
        <li>论文正在写作中，预计投稿至 IEEE TCSVT。</li>
    </ul>
</div>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🧠 科研经历 - 大语言模型、可视化</h2>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">面向高效多租户LoRA服务的动态算子优化</h3>
    <p style="font-size: 1.15em;"><b>时间：</b> 2024.7 - 2024.8</p>
    <p style="font-size: 1.15em;"><b>领域：</b> Efficient AI、高效微调</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 第三作者</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>低秩自适应(LoRA)已经成为在资源和数据受限的条件下，有效微调LLM的关键技术传统。</li>
        <li>传统上，我们需要独立处理每个LoRA模型，这会导致冗余的存储和计算，特别是当多个模型共享相同的预训练主干时，因为源自相同预训练模型的一些LoRA模型之间的存在潜在的权重相关性。</li>
        <li>当今的方法如vLLM和FastTransformer无法同时处理多个LoRA模型因为它们不能有效地批量处理不同模型的GPU操作。</li>
        <li>Punica通过引入了名为分段聚合矩阵向量乘法(SGMV)的新颖算子，做到了为不同的LoRA模型进行批量GPU操作，但其核心算子的实现不具备灵活性和多样性，往往使用通用方法实现，这可能不是特定任务和硬件架构的最佳选择。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>我们的方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li>引入动态算子优化来解决上述问题:其旨在基于特定场景动态优化SGMV算子。</li>
        <li>具体实现上，其利用搜索空间构造器创建分层搜索空间，将程序空间划分为高维的结构草图和低维的实现细节，确保了操作符实现的多样性和灵活性。</li>
        <li>优化引擎将在估算程序性能的成本模型指导下，使用进化搜索改进算子的实现，这种迭代优化过程确保SGMV的实现可以动态适应不同的场景，以保持高性能。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>研究成果：</b> 目前实验效果较为良好: 将我们的方法应用于最先进的服务系统可以实现1.30-1.46倍的吞吐量提高。</p>
</div>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">Kaggle: LMSYS-Chatbot Arena Human Preference Predictions</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://www.kaggle.com/competitions/lmsys-chatbot-arena" style="color: #4b86b4;">[比赛介绍]</a> | <a href="https://www.kaggle.com/competitions/lmsys-chatbot-arena/leaderboard" style="color: #4b86b4;">[Leaderboard]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2024.5 - 2024.8</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 大语言模型、模型微调</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 团队主力成员</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>本次比赛中，参赛者将被挑战去预测用户在与两个由大语言模型(LLM)驱动的聊天机器人之间的交谈中更喜欢哪些回答。</li>
        <li>参赛者将获得一组来自Chatbot Arena的对话数据，这些对话由不同的LLM生成回答。通过开发一个满足任务要求机器学习模型，帮助改进聊天机器人与人类互动的方式，确保它们更好地符合人类的偏好。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>我们的方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li>先后测试了Deberta base、Deberta v2、Xlarge、Deberta v3 large等“小语言”模型，发现效果不尽如人意。</li>
        <li>查阅了一些公开方案和讨论区的观点，发现这场比赛使用“大语言”模型可能更合适。因此在而后又尝试了Gemma2 9b，Gemma2 27b，Llama3 8b模型。</li>
        <li>Gemma2 27b在本地进行测试时的表现最好，但是会超出比赛环境的GPU显存，所以最终选择了Gemma2 9b和Llama3 8b模型。</li>
        <li>在确定模型后，使用QLoRA对这两个模型进行微调，并尝试了两种方案: [对Gemma2 9b设置较高的Rank（32,64）进行微调，并作为单模型] / [对Gemma2 9b和Llama3 8b均设置较低的Rank（16）进行微调，最终进行Ensemble]，最终根据结果选取后一种方案。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>研究成果：</b> 摘得本次竞赛的银牌（Top 5%）。</p>
</div>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">从“堆盒子”到动态规划</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://www.bilibili.com/video/BV1ojKvehEuq" style="color: #4b86b4;">[Bilibili页面]</a> | <a href="https://github.com/mumuyeye/From-Stacking-Boxes-to-Dynamic-Programming" style="color: #4b86b4;">[Code]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2023.9 - 2023.12</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 算法可视化、算法教学</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 团队主力成员</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>算法学习一直是很多投身于算法竞赛的高中生和计算机相关专业大学生的一块“心病”。</li>
        <li>算法教学领域存在诸多通病——有些课程要么浅尝辄止，难以让同学们从本质上掌握并能熟练运用算法知识，要么过于专业和晦涩，让同学们听的一头雾水。</li>
        <li>“化抽象为具象”的最佳方法便是对算法进行“可视化”。</li>
        <li>Manim是一款基于python的数学动画制作引擎，由斯坦福大学的数学系学生Grant Sanderson创建，并用于YouTube频道3Blue1Brown，来解说高等数学。</li>
        <li>Manim可以快速构建非常精彩而又形象的动画，例如数学证明可视化、数学运算可视化、二/三维模型可视化、机械原理可视化，Manim都可以精彩完成。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>我们的作品：</b></p>
    <ul style="font-size: 1.15em;">
        <li>采用了与著名博主3Blue1Brown所同源的基于Python的数学动画制作引擎Manim来制作，自主编写3000余行代码，配合后期大量的代码微调、剪辑、AI处理搭配工作，最终得以完成本次作品。</li>
        <li>其以更完整的教学结构、更通俗易懂的讲解、更专业的可视化（使用专业的Manim引擎而非传统的动画制作软件）、更友好的教学模式以及更具创新性的教学理念，在Coding for Education领域真正走到了前沿。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>研究成果：</b> 将视频发布到了Manim爱好者的交流社群中，在本院同学之间进行测试反馈和迭代，再到各高中乃至高校进行应用推广，均收到了良好反馈。</p>
</div>


<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">📊 科研经历 - 数学建模</h2>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">母亲身心健康对婴儿睡眠质量的影响分析</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://samer-hue.github.io/docs/huashubei23C.pdf" style="color: #4b86b4;">[项目报告]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2023.7 - 2023.8</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 数学建模，关联分析，多目标优化</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 团队队长</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>母亲的心理健康对婴儿认知和情感发展有重要影响，研究两者关系对母婴健康至关重要。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li><b>SEM模型：</b> 建立结构方程模型，分析母亲的身体和心理指标对婴儿行为和睡眠质量的影响。</li>
        <li><b>TOPSIS模型：</b> 使用TOPSIS模型量化母亲的身体和心理指标，并结合机器学习模型进行预测。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>成果：</b></p>
    <ul style="font-size: 1.15em;">
        <li>组织团队参加“华数杯”全国大学生数学建模竞赛，获得全国一等奖。</li>
    </ul>
</div>

<div style="margin-bottom: 30px;">
    <h3 style="font-family: Georgia, serif; font-size: 1.75em; color: #2a4d69;">基于计算几何和遗传算法的多波束测深和测线布设模型</h3>
    <p style="font-size: 1.15em;"><sub><a href="https://samer-hue.github.io/docs/shumoguosai23B.pdf" style="color: #4b86b4;">[项目报告]</a></sub></p>
    <p style="font-size: 1.15em;"><b>时间：</b> 2023.8 - 2023.9</p>
    <p style="font-size: 1.15em;"><b>领域：</b> 数学建模，计算几何，多目标优化</p>
    <p style="font-size: 1.15em;"><b>角色：</b> 团队队长</p>
    <p style="font-size: 1.15em;"><b>研究背景：</b></p>
    <ul style="font-size: 1.15em;">
        <li>传统海洋测绘效率低，多波束测深系统适合高效测量，但需要合理设计测线。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>方法：</b></p>
    <ul style="font-size: 1.15em;">
        <li><b>几何计算：</b> 应用平面几何定理计算测深覆盖宽度和重叠率，并求出真实值。</li>
        <li><b>优化算法：</b> 设计两种测线布设方案，并通过几何公式和遗传算法求解。</li>
    </ul>
    <p style="font-size: 1.15em;"><b>成果：</b></p>
    <ul style="font-size: 1.15em;">
        <li>参加“高教社杯”全国大学生数学建模竞赛，获省级一等奖。</li>
    </ul>
</div>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🏆 竞赛奖项</h2>

<ul style="font-size: 1.15em;">
    <li><b>Kaggle: Chatbot Arena Human Preference Predictions：铜牌</b> <b>国家级</b> 2024 &nbsp;&nbsp;</li>
    <li><b>中国机器人及人工智能大赛(全国总决赛)：一等奖</b> <b>国家级</b> 2024 &nbsp;&nbsp;</li>
    <li><b>“华数杯”全国大学生数学建模竞赛：一等奖</b> <b>国家级</b> 2023 &nbsp;&nbsp;</li>
    <li><b>全国大学生数据统计与分析竞赛：一等奖</b> <b>国家级</b> 2023 &nbsp;&nbsp;</li>
    <li><b>“英语世界”杯全国大学生英语语法大赛：一等奖</b> <b>国家级</b> 2023 &nbsp;&nbsp;</li>
    <li><b>“互联网＋”大学生创新创业大赛：金奖</b> <b>省部级</b> 2023 &nbsp;&nbsp;</li>
    <li><b>全国大学生数学建模竞赛：一等奖</b> <b>省部级</b> 2023 &nbsp;&nbsp;</li>
    <li><b>全国大学生数学建模竞赛：一等奖</b> <b>省部级</b> 2022 &nbsp;&nbsp;</li>
</ul>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🥇 奖学金与荣誉</h2>

<ul style="font-size: 1.15em;">
    <li><b>2021-2022</b> <b>国家奖学金</b> (该年度年级成绩排名：1/108) <b>兰州大学</b> &nbsp;&nbsp;</li>
    <li><b>2021-2022</b> <b>兰州大学优秀学生一等奖学金</b> (获奖率：3%) <b>兰州大学</b> </li>
    <li><b>2021-2022</b> <b>兰州大学学生标兵</b> <b>兰州大学</b> </li>
</ul>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">📖 教育经历</h2>

<ul style="font-size: 1.15em;">
    <li><b>2021.9 -</b>, 本科生, 兰州大学信息科学与工程学院 · 专业：计算机科学与技术</li>
</ul>
</font>
