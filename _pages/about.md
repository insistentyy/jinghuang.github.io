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
大家好！我是 <b>刘一澎</b>，目前是本科三年级，就读于<a href="https://xxxy.lzu.edu.cn/">兰州大学信息科学与工程学院</a>计算机科学与技术专业。

我对人工智能充满热情，自入学以来，积极参与各类科研项目和学术竞赛，曾获得<b>国家奖学金</b>和多项校内外奖项。在科研方面，我参与并主导了多个项目，包括但不限于<b>图神经网络</b>、<b>计算机视觉</b>、<b>大语言模型</b>、<b>人工智能安全</b>等领域。

<h2>🎓 <font face="Georgia">Education Background</font></h2>

<ul>
    <li><b>排名：</b> GPA排名：<b>2/108 (1.8%)</b>、加权平均分排名：<b>2/108 (1.8%)</b> <span style="font-size: 15px;">[[排名证明]](https://samer-hue.github.io/docs/paimingzhengming.pdf)</span></li>
    <li><b>成绩均分：</b> GPA：4.03/5.0、加权平均分：90.11/100</li>
    <li><b>语言能力：</b> 已通过 CET4 和 CET6，有独立写作并发表全英学术论文（2篇，均已被录用）的经历</li>
    <li><b>核心课程：</b> 高等数学 (93)、线性代数 (97)、商务统计（即: 概率论与数理统计） (94)、数据结构 (97, 95)、计算机编程 (理论) (94, 100)、计算机编程 (实践) (97, 100)、数据管理 (99, 96)、信息可视化 (97)</li>
    <li><b>编程能力：</b> 熟练掌握 C/C++ 和 Python，熟悉算法与数据结构，具备强大的抽象能力和良好的代码风格；熟练使用 PyTorch、Numpy、Pandas，熟悉各种深度学习模型及其实现；长期担任数学建模的编程手，并多次获得数模国赛和“华数杯”等高水平数学建模竞赛一等奖</li>
    <li><b>开发工具：</b> VS Code, PyCharm, Jupyter Notebook, LaTeX (Overleaf), Git</li>
    <li><b>在校荣誉：</b> 曾获<b>2021-2022年度国家奖学金</b> <span style="font-size: 15px;">[[国奖证书]](https://samer-hue.github.io/docs/guojiang.pdf)</span>（该年度年级成绩排名为：1/108），兰州大学优秀学生一等奖学金（3%）、兰州大学学生标兵称号，以及多项竞赛奖金，在校累计获奖金额超过30000元</li>
</ul>

<h2>🔥 <font face="Georgia">News</font></h2>

<h2>🧠 <font face="Georgia">Research Experience-Graph Neural Networks</font></h2>

<h3>**💡💡💡 DicTED - 基于预训练嵌入蒸馏的字典图神经网络** <sub> &nbsp;&nbsp;[[项目主页]](https://samer-hue.github.io/DicTED/README.html) | [[项目代码]](https://github.com/Samer-hue/DicTED)</sub></h3>

<ul>
    <li><b>时间：</b> 2023.3 - 2024.3</li>
    <li><b>领域：</b> <b>图神经网络</b>，<b>知识蒸馏</b></li>
    <li><b>角色：</b> 独立第一作者</li>
    <li><b>研究背景：</b>
        <ol>
            <li>时序图学习通过将时间维度纳入分析来扩展传统图学习方法的能力，但由于数据结构的复杂性，现有方法在获取多源信息时具有很高的复杂性，且频繁的更新和训练导致了记忆问题。</li>
            <li>字典时序图网络通过存储和灵活匹配邻域信息来优化性能，但在初始化时对特征集的依赖性可能导致冷启动问题，同时嵌入信息的频繁更新也可能导致灾难性遗忘问题。</li>
        </ol>
    </li>
    <li><b>我们的方法：</b>
        <ol>
            <li><b>引入预训练嵌入蒸馏：</b> 我们构建了基于预训练嵌入蒸馏的字典时序图网络（DicTED），通过聚合多个预训练教师模型生成的嵌入作为先验特征，成功应对冷启动和灾难性遗忘问题。</li>
            <li><b>优化策略：</b> 在输入端，将先验特征与原始特征结合以增强模型的初始化效果；在优化过程中，通过对齐嵌入损失和预测分数损失，保留原始信息，提高模型性能。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>在多个真实数据集上，DicTED展示了优于现有SOTA方法的性能表现。</li>
            <li>作为独立第一作者的论文已被ICIC 2024 (CCF-C) 录用并发表。<a href="https://link.springer.com/chapter/10.1007/978-981-97-5678-0_29">[论文全文]</a></li>
        </ul>
    </li>
</ul>

<h3>**💡💡💡 基于拓扑能量的联邦图后门攻击防御策略**</h3>

<ul>
    <li><b>时间：</b> 2024.3 - 2024.8</li>
    <li><b>领域：</b> <b>图神经网络</b>，<b>联邦学习</b>，<b>后门攻击防御</b></li>
    <li><b>角色：</b> 共同第一作者</li>
    <li><b>研究背景：</b>
        <ol>
            <li>联邦图学习（FGL）通过协同训练共享的全局模型，同时保护敏感数据隐私，为分布式图数据建模提供了新范式，但其分布式特性也引入了新的安全漏洞，特别是恶意参与者的后门攻击。</li>
            <li>现有的防御方法在联邦图学习环境下效果不佳，主要由于图数据的非IID特性和复杂拓扑结构，这些方法在应对大规模恶意客户端或收集验证数据集困难的场景中，其有效性大打折扣。</li>
            <li>一些防御方法尝试计算客户端之间的相似性，但忽略了触发器可以被巧妙注入而不引起显著扰动的可能性，这在数据异质性环境下尤其挑战。</li>
        </ol>
    </li>
    <li><b>我们的方法：</b>
        <ol>
            <li><b>拓扑能量客户端聚类（TNC）：</b> 在微观层面，引入拓扑能量客户端聚类来应对复杂拓扑触发器问题，通过量化客户端数据分布的差异，将分布感知注入局部模型，解耦良性和恶意样本的能量分布，以此识别潜在的恶意客户端。</li>
            <li><b>拓扑能量相似性传播（TSP）：</b> 在宏观层面，构建基于能量分布相似性的能量图，进一步解耦恶意和良性客户端的能量元素。通过消息传递过程中的权重调整，更细粒度地识别异常能量元素，提升防御效果。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>在IID/非IID场景下的五个主流数据集上的实验结果表明，我们的方法优于当前的SOTA方法。</li>
            <li>相关研究工作已基本完成，论文正在实验收尾和写作阶段，预计完稿后投稿至ICLR 2025（共同第一作者）。</li>
        </ul>
    </li>
</ul>

<h2>🖼️ <font face="Georgia">Research Experience-Computer Vision</font></h2>

<h3>**💡💡 FreeMRISeg - 磁共振图像分割** <sub> &nbsp;&nbsp;[[项目主页]](https://samer-hue.github.io/MRI-Segmentation/README.html) | [[项目代码]](https://github.com/Samer-hue/MRI-Segmentation)</sub></h3>

<ul>
    <li><b>时间：</b> 2022.9 - 2022.12</li>
    <li><b>领域：</b> <b>计算机视觉</b>，<b>医工交叉</b></li>
    <li><b>角色：</b> 团队（负责人）</li>
    <li><b>研究背景：</b>
        <ol>
            <li>深度学习技术近年来在医学图像处理方面展现出了卓越的能力，特别是在磁共振成像（MRI）或计算机断层扫描（CT）中对病变的定位和分割。然而，训练这些分割模型需要大量由专业医生手动标注的像素级标签，这与更易获取的图像级标签相比更加耗时且费力。</li>
        </ol>
    </li>
    <li><b>我们的方法：</b>
        <ol>
            <li><b>弱监督语义分割模型设计：</b> 我们提出了一个利用图像级标签作为监督的弱监督语义分割模型，以解决标注数据不足的问题。该模型主要分为分类和分割两个部分。</li>
            <li><b>分类任务部分：</b> 选择ResNet作为卷积神经网络模型，对已有的图像级标签数据集（如RSNA2019）进行分类训练；使用类激活映射（CAM）推理分类网络的关注区域，并利用条件随机场（CRF）优化生成的掩码（Mask），从而获取更精准的像素级标签。</li>
            <li><b>分割任务部分：</b> 使用分类任务生成的像素级标签来训练分割网络（选用Deeplabv3、Trans-Unet、Swin-Unet、MT-Unet作为backbone），完成整个弱监督分割的工作流。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>该科研课题成功申请为“中央高校基本科研业务专项资金”本科生项目。</li>
        </ul>
    </li>
</ul>

<h3>**💡💡 PDGPSeg - 基于渐进式域间隙解耦的大雾场景语义分割** <sub> &nbsp;&nbsp;[[项目主页]](https://samer-hue.github.io/PDGPSeg/README.html) | [[项目代码]](https://github.com/Samer-hue/PDGPSeg)</sub></h3>

<ul>
    <li><b>时间：</b> 2023.12 - 2024.8</li>
    <li><b>领域：</b> <b>计算机视觉</b>，<b>域适应</b></li>
    <li><b>角色：</b> 团队（主力成员） / 第三作者</li>
    <li><b>研究背景：</b>
        <ol>
            <li>目前的语义分割模型大多基于清晰场景的图片进行训练，通常忽视了恶劣天气的影响，尤其是在雾天场景下，其分割性能较差。</li>
            <li>尽管现有的方法尝试使用领域自适应技术将分割知识从清晰场景迁移到模糊场景，但由于雾霾导致的图像质量下降及不同城市风格之间的域差异，这些方法的效果仍不理想。</li>
            <li>最新研究尝试通过引入中间域来解耦域间隙，逐步完成雾天场景的语义分割，但在中间域信息的探索上仍然存在不足。</li>
        </ol>
    </li>
    <li><b>我们的方法：</b>
        <ol>
            <li><b>多层次教师自训练：</b> 针对恶劣天气下语义分割模型的局限性，采用多层次教师自训练方法，将大的域间隙拆解为多个小的域间隙，每个小的域间隙对应一个任务，以此来控制模型在自训练过程中的域间隙。</li>
            <li><b>交替训练策略：</b> 结合交替训练策略，使模型能够充分利用来自源域的参考信息，逐步掌握从源域迁移到目标域的分割能力，在雾霾干扰下表现出良好的鲁棒性。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>获得了第二十六届中国机器人及人工智能大赛全国一等奖。&nbsp;<span style="font-size: 16px;"><a href="https://samer-hue.github.io/docs/AWARDCRAICguo.pdf">[获奖证书]</a></span></li>
            <li>论文正处于写作阶段，预计完稿后投稿至 <b>IEEE TCSVT (CCF-B / 中科院一区Top)</b>（第三作者）。</li>
        </ul>
    </li>
</ul>

<h2>🧩 <font face="Georgia">Research Experience-Large Language Models</font></h2>

<h3>**💡 面向高效多租户LoRA服务的动态算子优化**</h3>

<ul>
    <li><b>时间：</b> 2024.5 - 2024.8</li>
    <li><b>领域：</b> <b>大语言模型</b>，<b>大语言模型高效微调</b></li>
    <li><b>角色：</b> 第三作者</li>
    <li><b>研究背景：</b>
        <ol>
            <li>低秩自适应(LoRA)已成为在资源和数据受限条件下有效微调大型语言模型(LLM)的关键技术。然而，传统上需要独立处理每个LoRA模型，导致冗余的存储和计算，特别是当多个模型共享相同的预训练主干时，因为来自相同预训练模型的一些LoRA模型之间存在潜在的权重相关性。</li>
            <li>当前的方法，如vLLM和FastTransformer，无法同时处理多个LoRA模型，因为它们无法有效地批量处理不同模型的GPU操作。Punica通过引入分段聚合矩阵向量乘法(SGMV)的新算子，实现了对不同LoRA模型的批量GPU操作，但其核心算子的实现缺乏灵活性和多样性，通常使用通用方法实现，可能不是特定任务和硬件架构的最佳选择。</li>
        </ol>
    </li>
    <li><b>我们的方法：</b>
        <ol>
            <li><b>引入动态算子优化：</b> 通过动态优化SGMV算子来解决现有问题，方法基于特定场景动态优化算子，实现高性能。具体实现上，通过搜索空间构造器创建分层搜索空间，将程序空间划分为高维的结构草图和低维的实现细节，确保操作符实现的多样性和灵活性。</li>
            <li><b>优化引擎：</b> 优化引擎在估算程序性能的成本模型指导下，使用进化搜索改进算子的实现。这种迭代优化过程确保SGMV的实现可以动态适应不同的场景，以保持高性能。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>实验结果显示，应用我们的方法于最先进的服务系统可以实现1.30-1.46倍的吞吐量提高。</li>
        </ul>
    </li>
</ul>

<h3>**💡 Kaggle: LMSYS-Chatbot Arena Human Preference Predictions** <sub> &nbsp;&nbsp;[[比赛介绍]](https://www.kaggle.com/competitions/lmsys-chatbot-arena) | [[Leaderboard]](https://www.kaggle.com/competitions/lmsys-chatbot-arena/leaderboard)</sub></h3>

<ul>
    <li><b>时间：</b> 2024.5 - 2024.8</li>
    <li><b>领域：</b> <b>大语言模型</b>，<b>大语言模型微调</b></li>
    <li><b>角色：</b> 团队（主力成员）</li>
    <li><b>研究背景：</b>
        <ul>
            <li>本次比赛的目标是预测用户在与两个由大语言模型（LLM）驱动的聊天机器人之间的交谈中更偏爱哪些回答。参赛者将获得一组来自Chatbot Arena的对话数据，这些数据包含由不同LLM生成的回答。参赛者需开发一个机器学习模型，帮助改进聊天机器人与人类互动的方式，确保它们更好地符合人类的偏好。</li>
        </ul>
    </li>
    <li><b>我们的方法：</b>
        <ol>
            <li><b>初步模型测试：</b> 先后测试了Deberta base、Deberta v2、Xlarge、Deberta v3 large等“小语言”模型，但效果不佳。</li>
            <li><b>选择大模型策略：</b> 参考公开方案和讨论区的观点后，选择了使用“大语言”模型。尝试了Gemma2 9b，Gemma2 27b，Llama3 8b模型，其中Gemma2 27b在本地测试表现最好，但由于超出比赛环境的GPU显存限制，最终选择了Gemma2 9b和Llama3 8b模型。</li>
            <li><b>模型微调与集成：</b> 使用QLoRA对两个模型进行微调，并尝试了两种方案：（1）对Gemma2 9b设置较高的Rank（32,64）进行微调，并作为单模型；（2）对Gemma2 9b和Llama3 8b均设置较低的Rank（16）进行微调，并最终进行Ensemble。最终选择了效果更好的第二种方案。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>获得了0.9985的Final Score，最终摘得本次竞赛的铜牌（Top 10%）。</li>
        </ul>
    </li>
</ul>

<h2>📊 <font face="Georgia">Experience in Mathematical Modeling</font></h2>

<h3>**💡 母亲身心健康对婴儿睡眠质量的影响分析** <sub> &nbsp;&nbsp;[[项目报告]](https://samer-hue.github.io/docs/huashubei23C.pdf)</sub></h3>

<ul>
    <li><b>时间：</b> 2023.7 - 2023.8</li>
    <li><b>领域：</b> <b>数学建模</b>，<b>关联分析</b>，<b>多目标优化</b></li>
    <li><b>角色：</b> 团队（队长）</li>
    <li><b>研究背景：</b>
        <ul>
            <li>母亲的心理健康状况对婴儿的认知和情感等方面有重要影响，分析和建模母亲身体和心理指标与婴儿睡眠质量之间的关系，能够促进母婴健康发展。</li>
        </ul>
    </li>
    <li><b>我们的论文：</b>
        <ol>
            <li>建立SEM模型，将母亲的身体和心理指标作为自变量，婴儿行为和睡眠质量作为因变量，分析路径系数，揭示母亲因素对婴儿的影响。</li>
            <li>使用基于熵权法的TOPSIS模型量化身体和心理指标，并结合Adaboost、GBDT和随机森林构建Soft Voting分类器，模型准确率达95%以上。</li>
            <li>构建MIMO神经网络模型，输入母亲特征预测CBTS、EPDS和HADS得分，模型拟合优度达96.4%。</li>
            <li>将婴儿睡眠质量的四分类任务视为无监督学习问题，采用K-means算法聚类，并通过TOPSIS模型和Soft Voting模型验证分类结果的合理性，模型准确率达91.6%。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>作为队长组织团队参加2023年“华数杯”全国大学生数学建模竞赛，并获全国一等奖。</li>
        </ul>
    </li>
</ul>

<h3>**💡 基于计算几何和遗传算法的多波束测深和测线布设模型** <sub> &nbsp;&nbsp;[[项目报告]](https://samer-hue.github.io/docs/shumoguosai23B.pdf)</sub></h3>

<ul>
    <li><b>时间：</b> 2023.8 - 2023.9</li>
    <li><b>领域：</b> <b>数学建模</b>，<b>计算几何</b>，<b>多目标优化</b></li>
    <li><b>角色：</b> 团队（队长）</li>
    <li><b>研究背景：</b>
        <ul>
            <li>传统海洋测绘采用单波束测深系统效率低、要求高，而多波束测深系统更适合现代高效、高精度、全覆盖测量，需要合理设计测线以提高测量精度。</li>
        </ul>
    </li>
    <li><b>我们的论文：</b>
        <ol>
            <li>应用平面几何定理计算测深覆盖宽度和重叠率，并依数据求出真实值。</li>
            <li>将测量船与海底坡面的位置关系抽象为三棱锥体，分析不同测线夹角下的测深覆盖宽度与船距中心点的关系。</li>
            <li>设计两种测线布设方案，通过几何公式和Bisinhopping算法求出最优解。</li>
            <li>根据数据生成海底地形仿真图。</li>
            <li>使用贪心算法将三个目标函数归一化，建立加权目标函数。</li>
            <li>通过遗传算法多次迭代，得到最终解。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>作为队长组织团队参加2023年“高教社杯”全国大学生数学建模竞赛，并获省级一等奖。</li>
        </ul>
    </li>
</ul>

<h3>**💡 基于仿真模拟的三角形纯方位无源定位模型** <sub> &nbsp;&nbsp;[[项目报告]](https://samer-hue.github.io/docs/shumoguosai22B.pdf)</sub></h3>

<ul>
    <li><b>时间：</b> 2022.8 - 2022.9</li>
    <li><b>领域：</b> <b>数学建模</b>，<b>仿真模拟</b></li>
    <li><b>角色：</b> 团队（队长）</li>
    <li><b>研究背景：</b>
        <ul>
            <li>无人机在军用中常以编队形式执行任务，为避免外界干扰和雷达探测，需要通过无源探测定位有效调整无人机位置。</li>
        </ul>
    </li>
    <li><b>我们的论文：</b>
        <ol>
            <li>建立三角形纯方位无源定位模型，假设角度测量呈正态分布，通过仿真生成正态分布点，计算其与重心和内心的平均距离，最终选用内心代表测量点位置。</li>
            <li>建立四点定位模型，四架无人机发射信号形成4个定位三角形，测量点处于4个三角形相交的公共区域内，通过计算4个三角形内心坐标的平均值有效定位无人机位置。</li>
        </ol>
    </li>
    <li><b>项目成果：</b>
        <ul>
            <li>作为队长组织团队参加2022年“高教社杯”全国大学生数学建模竞赛，并获省级一等奖。</li>
        </ul>
    </li>
</ul>

<h2>🏆 <font face="Georgia">Competition Awards</font></h2>

<ul>
    <li><b>Kaggle: Chatbot Arena Human Preference Predictions：铜牌</b> *国家级* 2024 &nbsp;&nbsp;[[Leaderboard]](https://www.kaggle.com/competitions/lmsys-chatbot-arena/leaderboard)</li>
    <li><b>中国机器人及人工智能大赛(全国总决赛)：一等奖</b> *国家级* 2024 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDCRAICguo.pdf)</li>
    <li><b>“华数杯”全国大学生数学建模竞赛：一等奖</b> *国家级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDhuashubei.pdf)</li>
    <li><b>全国大学生数据统计与分析竞赛：一等奖</b> *国家级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDshujutongjifenxi.pdf)</li>
    <li><b>“英语世界”杯全国大学生英语语法大赛：一等奖</b> *国家级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDenglishgrammar.pdf)</li>
    <li><b>“互联网＋”大学生创新创业大赛：金奖</b> *省部级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDhulianwang+.pdf)</li>
    <li><b>全国大学生数学建模竞赛：一等奖</b> *省部级* 2023 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDshumoguosai23.pdf)</li>
    <li><b>全国大学生数学建模竞赛：一等奖</b> *省部级* 2022 &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/AWARDshumoguosai22.pdf)</li>
</ul>

<h2>🥇 <font face="Georgia">Scholarships and Honors</font></h2>

<ul>
    <li><b>2021-2022</b> <b>国家奖学金</b> (该年度年级成绩排名：1/108) *兰州大学* &nbsp;&nbsp;[[证明]](https://samer-hue.github.io/docs/guojiang.pdf)</li>
    <li><b>2021-2022</b> <b>兰州大学优秀学生一等奖学金</b> (获奖率：3%) *兰州大学*</li>
    <li><b>2021-2022</b> <b>兰州大学学生标兵</b> *兰州大学*</li>
</ul>

<h2>📖 <font face="Georgia">Educations</font></h2>

<ul>
    <li><b>2021.9 -</b>, 本科生, 兰州大学信息科学与工程学院  专业：计算机科学与技术.</li>
</ul>
</font>
