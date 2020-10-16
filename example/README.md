<h1>
  <span>杨芷江</span>
  <ul>
    <li><span font-weight="bold"><img align="left" alt="Kotori's Telegram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.11.0/icons/apple.svg" />电话</span>176 4981 9235</li>
    <li><span><img align="left" alt="Kotori's Telegram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.11.0/icons/tencentqq.svg" />QQ</span>1223821976</li>
    <li><span><img align="left" alt="Kotori's Telegram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.11.0/icons/gmail.svg" />邮箱</span><a href="mailto:kotori@cbdd.me">kotori@cbdd.me</a></li>
    <li><span><img align="left" alt="Kotori's Telegram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.11.0/icons/github.svg" />Github</span><a href="https://github.com/kotori-y">github.com/kotori-y</a></li>
  </ul>
  <img src="https://github.com/kotori-y/vuepress-theme-resume/blob/master/imgs/biograph.jpg?raw=true" width=100>
</h1>

## 教育经历

硕士 中南大学 药物化学 *计算机辅助药物设计* <span class="right">2018.09 - 2021.06</span><br>
本科 长春中医药大学大学 药学 <span class="right">2014.09 - 2018.06</span>

## 获奖经历

- **2019年第15届全国计算（机）化学学术会议优秀墙报** （13/150）

## 项目经验

### >>> 负向设计工具：**Scopy**<span class="right">开发者</span>

- 项目地址：https://github.com/kotori-y/Scopy
- 项目简介: 高通量筛选（HTS）和虚拟筛选（VS）广泛应用于化合物筛选和潜在先导化合物的发现。但是，筛选数据库中频繁出现的药物样差、选择性差和潜在毒性等化合物等，大大削弱了HTS和VS的效率。我们基于Python开发了一个负向设计工具Scopy, 旨在过滤药物早期发现中的不良化合物，减少先导化合物的损耗率。
- 项目发表: Yang, Z. Y., Yang, Z. J., et al.,Lu, A. P., Hou, T. J., & Cao, D. S. (2020). *Briefings in Bioinformatics* <br />(doi: 10.1093/bib/bbaa194, IF=8.99).
- 专利公开：基于python语言的高通量负向设计虚拟筛选系统

---

### >>> 自动搜寻警示结构工具：**pySmash**<span class="right">开发者</span>

- 项目地址：https://github.com/kotori-y/pySmash
- 项目简介：显著子结构被广泛应用于毒性、频繁命中化合物及生物活性等性质的初步筛选。pySmash为显著子结构的提取及应用提供了便利。pySmash提供三种子结构推导算法：环形指纹算法、路径算法和官能团算法。此外，pySmash还提供实现子结构应用的接口，同时提供有可视化界面的软件和Python软件包，既实现了灵活性又简化了流程。 
- 项目发表：*Briefings in Bioinformatics. (manuscript)*

---

### >>> 分子翻译及优化平台：ChemMort<span class="right">底层模型开发者</span>

- 项目地址：http://chemmort.scbdd.com/
- 项目简介：ChemMort是一个结合分子翻译及性质优化的平台，可用于改善目标化合物的ADME/T性质，减少临床药物由于药物动力学性质产生的损耗。ChemMort使用当前先进的LSTM神经网络建立了一个分子翻译模型来实现从SMILES到512维的描述符的映射，该描述符经翻译模型还能返回至原始的SMILES，实现“逆向QSAR”。此外，ChemMort还包含了一个优化模型，该模型通过PSO优化算法及加权算法，实现对分子的多目标优化。通过限制相似性等条件，可以得到与目标活性化合物相比，生物活性几乎不变，但ADME/T性质得到大大改善的化合物。
- 项目发表：*Nucleic Acid Research (in progress)*

---

### >>> 量子化学描述符提取工具：QUANTUM<span class="right">开发者</span>

- 项目简介：QUANTUM是一个方便的/Python环境无依赖的量子化学描述符提取软件，为广大研究人员提供了便利。量子化学描述符具有不依赖实验，无统计误差，物理意义明确，可解释性强，描述分子结构、电子结构及反应性精确的独特优势，可用于包括毒理学在内的QSAR模型的建立。然而，对于大多数药物化学家来说，从Gaussian等计算量子化学特征的软件输出的结果文件中，提取位于模型技术底层的量子化学描述符是一项非常困难且耗时的任务。我们通过Python语言，采取字符串匹配的技术进行特征提取，然后将整个程序打包成可执行文件，实现了界面化，即QUANTUM软件，可对Gaussian软件计算输出文件的17个局部和39个全局量子化学描述符进行自动提取。

---

### >>> 其他项目

- 频繁命中化合物预测系列平台：[ChemAgg](http://admet.scbdd.com/ChemAGG/index/)等.<span class="right">机器学习模型建立</span>
- 集成靶点预测分析平台：[metaTarFisher](https://metatarget.scbdd.com/).<span class="right">底层爬虫编写及平台维护</span>
- 基本分子描述符在线计算平台：[BDes](https://bdes.scbdd.com/).<span class="right">描述符算法编写</span>
- etc.

## 技能描述

- **掌握 Python编程语言及相关项目开发；**
- **掌握RDKit, OpenBabel及MOE等化学信息学工具；**
- 熟悉TensorFlow, pyTorch和Scikit-learn等主流人工智能学习框架及主流机器学习算法；
- 熟悉HTML, JavaScript及CSS前端工具；
- 了解C++, Go, R等主流编程语言。

## 自我评价

本人学习能力强，在没有任何计算机背景下，自学了Python, Javascript等编程语言及各种机器学习算法；本人还对计算机和计算化学充满热情，在闲暇时间学习了RDKit化学信息学工具及网络爬虫；此外，本人乐于合作，经常对同门提供代码支持。