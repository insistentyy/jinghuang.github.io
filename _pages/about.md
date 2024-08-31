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
    <hr style="width: 50%; border: 1px solid #4b86b4;">
</div>

<p style="text-align: justify; font-size: 1.15em; margin-bottom: 30px;">
    大家好！我是 <b>刘一澎</b>，目前是本科三年级学生，专注于人工智能和计算机科学的交叉研究领域。
    自入学以来，我积极参与各类科研项目和学术竞赛，并获得了多项荣誉与奖项。我特别关注
    <b>图神经网络</b>、<b>计算机视觉</b>、<b>大语言模型</b>、以及<b>人工智能安全</b>等领域的前沿研究。
</p>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🎓 教育背景</h2>
<ul style="font-size: 1.15em; margin-bottom: 30px;">
    <li><b>排名：</b> GPA排名：<b>2/108 (1.8%)</b>、加权平均分排名：<b>2/108 (1.8%)</b> <span style="font-size: 15px;">[[排名证明]](https://samer-hue.github.io/docs/paimingzhengming.pdf)</span></li>
    <li><b>成绩均分：</b> GPA：4.03/5.0、加权平均分：90.11/100</li>
    <li><b>语言能力：</b> 通过 CET4 和 CET6，独立撰写并发表两篇全英学术论文（均已被录用）</li>
    <li><b>核心课程：</b> 高等数学 (93)、线性代数 (97)、商务统计（即: 概率论与数理统计） (94)、数据结构 (97, 95)、计算机编程 (理论) (94, 100)、计算机编程 (实践) (97, 100)、数据管理 (99, 96)、信息可视化 (97)</li>
    <li><b>编程能力：</b> 精通 C/C++ 和 Python，熟悉算法与数据结构；精通深度学习模型的实现，长期担任数学建模编程手</li>
    <li><b>开发工具：</b> VS Code, PyCharm, Jupyter Notebook, LaTeX (Overleaf), Git</li>
    <li><b>在校荣誉：</b> 国家奖学金获得者 <span style="font-size: 15px;">[[国奖证书]](https://samer-hue.github.io/docs/guojiang.pdf)</span>，兰州大学优秀学生一等奖学金，兰州大学学生标兵称号</li>
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
    <li><b>Kaggle: Chatbot Arena Human Preference Predictions：铜牌</b> *国家级* 2024 &nbsp;&nbsp;[[Leaderboard]](https://www.kaggle.com/competitions/lmsys-chatbot-arena/leaderboard)</li>
    <li><b>中国机器人及人工智能大赛(全国总决赛)：一等奖</b> *国家级* 2024 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDCRAICguo.pdf)</li>
    <li><b>“华数杯”全国大学生数学建模竞赛：一等奖</b> *国家级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDhuashubei.pdf)</li>
    <li><b>全国大学生数据统计与分析竞赛：一等奖</b> *国家级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDshujutongjifenxi.pdf)</li>
    <li><b>“英语世界”杯全国大学生英语语法大赛：一等奖</b> *国家级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDenglishgrammar.pdf)</li>
    <li><b>“互联网＋”大学生创新创业大赛：金奖</b> *省部级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDhulianwang+.pdf)</li>
    <li><b>全国大学生数学建模竞赛：一等奖</b> *省部级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDshumoguosai23.pdf)</li>
    <li><b>全国大学生数学建模竞赛：一等奖</b> *省部级* 2022 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDshumoguosai22.pdf)</li>
</ul>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">🥇 奖学金与荣誉</h2>

<ul style="font-size: 1.15em;">
    <li><b>2021-2022</b> <b>国家奖学金</b> (该年度年级成绩排名：1/108) *兰州大学* &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/guojiang.pdf)</li>
    <li><b>2021-2022</b> <b>兰州大学优秀学生一等奖学金</b> (获奖率：3%) *兰州大学*</li>
    <li><b>2021-2022</b> <b>兰州大学学生标兵</b> *兰州大学*</li>
</ul>

<h2 style="font-family: Georgia, serif; color: #2a4d69; border-bottom: 2px solid #4b86b4; padding-bottom: 5px;">📖 教育经历</h2>

<ul style="font-size: 1.15em;">
    <li><b>2021.9 -</b>, 本科生, 兰州大学信息科学与工程学院 · 专业：计算机科学与技术</li>
</ul>
</font>
