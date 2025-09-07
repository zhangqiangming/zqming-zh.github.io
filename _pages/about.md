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

# 👨‍🎓 个人简介

#### 我将于2026年5月博士毕业于湖北武汉的华中科技大学, 计算机科学与技术学院, 信息存储及应用实验室, 冯丹教授团队。我的博士导师是胡燏翀教授, 专业为计算机体系结构。硕士毕业于四川成都的四川大学, 计算机学院, 专业为计算机技术。包括合著，我已经发表12+篇学术论文, 其中以第一作者或通讯作者发表论文6篇, 包括: ICDE2026, HPDC2025, HPDC2024, CADCG2021, ICV2022等.
 <!-- <a href='https://scholar.google.com/citations?user=pGBngNMAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a> -->


<!-- 💻 -->
<!-- ### 我的研究领域包括： -->
# ⌛	 研究领域
- 计算机系统结构
- 大规模高性能分布式训练/推理
- Storage4AI, System4AI
- 大模型系统/存储
- 计算机视觉
- 行人重识别 



<style>
.container {
  position: relative;
  height: 200px;   /* 父容器高度 */
  border: 1px solid #ccc;
}
.container a {
  position: absolute;
  bottom: 0;       /* 紧贴底部 */
  left: 50%;
  transform: translateX(-50%); /* 居中 */
}
</style>

<span class='anchor' id='-xl'></span>

# 🎓 教育经历
<!-- <a href="https://www.hust.edu.cn/"><img class="svg" src="https://zhangqiangming.github.io/zqming-zh.github.io/images/HUST_logo.svg" width="23pt"></a> -->
- *2022.09 - 2026.06*, &nbsp; &nbsp;  华中科技大学&nbsp; &nbsp;计算机科学与技术专业&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 博士研究生

<!-- <a href="https://www.scu.edu.cn/"><img class="svg" src="https://zhangqiangming.github.io/zqming-zh.github.io/images/SCU_logo.svg" width="20pt"></a> -->
- *2019.09 - 2022.06*, &nbsp; &nbsp;  四川大学&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp;&nbsp;&nbsp;  计算机技术专业 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 硕士研究生


<!-- - *2014.09 - 2018.06*, &nbsp;  <a href="https://www.yangtzeu.edu.cn/"><img class="svg" src="https://zhangqiangming.github.io/zqming-zh.github.io/images/cjdx_logo.png" width="20pt"></a> 长江大学&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 计算机科学与技术学院 &nbsp; &nbsp;  计算机科学与技术专业 &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;  本科生 -->



<span class='anchor' id='-lwzl'></span>

# 📝 论文专利

### 学术论文
<!-- --- -->
-	`Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "ADTopk: All-Dimension Top-k Compression for High-Performance Data-Parallel DNN Training." 2024. In Proceedings of the 33rd International Symposium on High-Performance Parallel and Distributed Computing. (__HPDC'24__, Acceptance Rate=17.1%, 高性能顶会, CSRanking) [[Code]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)



-	`Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "SAFusion: Efficient Tensor Fusion with Sparsification Ahead for High-Performance Distributed DNN Training." 2025. In Proceedings of the 34th ACM International Symposium on High-Performance Parallel and Distributed Computing. (__HPDC'25__, Acceptance Rate=18.7%, 高性能顶会, CSRanking) [[Code]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)



-	`Zhangqiang Ming`, Rui, Wang, Yuchong Hu, Yuanhao Shu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "SSFusion: Tensor Fusion with Selective Sparsification for Efficient Distributed DNN Training." 2026. In Proceedings of the 42st IEEE International Conference on Data Engineering (__ICDE'26__, CCF-A, CSRanking) [[Code]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)



-	`Zhangqiang Ming`, Yuchong Hu, Patrick P. C. Lee, Xinjue Zheng, Wenxiang Zhou, and Dan Feng. "AsymCheck: Asymmetric Partitioned Checkpointing for Efficient Large Language Model Training." 2026. In Proceedings of the International Conference on Architectural Support for Programming Languages and Operating Systems (__ASPLOS'26__, CCF-A, CSRanking) [[Code]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)



-	Xinjue Zheng, `Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, and Dan Feng. "Saving Memory via Residual Reduction for DNN Training with Compressed Communication." 2025. In Proceedings of the European Conference on Parallel Processing (__EuroPar'26__, CCF-B, CSRanking) [[Code]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)



-	`Zhangqiang Ming`, Min Zhu, Xiangkun Wang, Jiamin Zhu, Junlong Cheng, Chengrui Gao, Yong Yang, and Xiaoyong Wei. "Deep learning-based person re-identification methods: A survey and outlook of recent works." Image and Vision Computing 119 (2022): 104394. (__ICV2022__, CCF-C; IF:3.291) [[Code]](https://www.sciencedirect.com/science/article/pii/S0262885622000233) [[预览]](https://www.sciencedirect.com/science/article/pii/S0262885622000233) [[下载]](https://www.sciencedirect.com/science/article/pii/S0262885622000233)



-	`Zhangqiang Ming`, Min Zhu, Jianrong Yan, Yong Yang, and Jiamin Zhu. "A survey on generative adversarial network based person re-identification method." Journal of Computer-Aided Design & Computer Graphics 34, no. 2 (2022): 163-179. (__CAD&CG__, CCF-A) 
[[Code]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[预览]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[下载]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852)



-	`Zhangqiang Ming`, Yong Yang, Xiaoyong Wei, Jianrong Yan, Xiangkun Wang, Fengjie Wang, and Min Zhu. "Global-local dynamic feature alignment network for person re-identification." arXiv preprint arXiv:2109.05759 (2021). [[Code]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[预览]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[下载]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852)


- `Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "Gradient Compression Techniques in Distributed DNNs Training Systems: A Survey and Outlooks." arXiv preprint arXiv:2310.14484 (2023).
[[Code]](https://dx.doi.org/10.3390/ma15207362) [[预览]]() [[下载]]()


- Yong Yang, Chengrui Gao, `Zhangqiang Ming`, Jixiang Guo, Edou Leopold, Junlong Cheng, Jie Zuo, and Min Zhu. "LatLRR-CNN: An infrared and visible image fusion method combining latent low-rank representation and CNN." Multimedia Tools and Applications 82, no. 23 (2023): 36303-36323. (JCR:Q1; IF:3.748) [[Code]](https://dx.doi.org/10.3390/ma15207362) [[预览]]() [[下载]]()


- Junlong Cheng,  Chengrui Gao, Changlin Li, `Zhangqiang Ming`, Yong Yang, Fengjie Wang, and Min Zhu. "F2RNET: A Full-Resolution Representation Network for Biomedical Image Segmentation." In 2022 IEEE International Conference on Image Processing (ICIP), pp. 2406-2410. IEEE, 2022.
[[Code]](https://dx.doi.org/10.3390/app12199703) [[预览]]() [[下载]]()


- Cheng, Junlong, Chengrui Gao, Hongchun Lu, `Zhangqiang Ming`, Yong Yang, and Min Zhu. "PL-Net: progressive learning network for medical image segmentation[J]." Frontiers in Bioengineering and Biotechnology, 2024, 12: 1414605. (2024).
[[Code]](https://dx.doi.org/10.3390/w14172736) [[预览]]() [[下载]]()




<!-- 
### 中文
---

- `明章强`，王荣彪，康宜华. 大提离漏磁无损检测方法. *无损检测*. 2022,44(4): 67. (核心期刊)  
[[Code]](https://dx.doi.org/10.11973/wsjc202204000) [[预览]]() [[下载]]()  

- 刘伯承, `明章强*`, 王荣彪, 叶文超, 康宜华. 基于TMR的轴承滚子微细裂纹漏磁检测方法. *仪表技术与传感器*. 2021(12): 111-114+118.  (通讯作者; 核心期刊)  
[[Code]](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDAUTO&filename=YBJS202112021) [[预览]]() [[下载]]()  

- 汪圣涵, `明章强*`, 刘军, 陈文宇, 康宜华. 双机械手操作的轴承阵列漏磁检测方法与系统. *轴承*. 2021(01): 54-58+65. (通讯作者; 核心期刊)  
[[Code]](https://dx.doi.org/10.19533/j.issn1000-3762.2021.01.011) [[预览]]() [[下载]]()  
 -->


### 发明专利
<!-- --- -->
- 胡燏翀, `明章强`, 周文翔, 郑欣觉, 罗致远, 冯丹.&nbsp;&nbsp;一种面向高性能数据并行DNN训练的全维度Top-k稀疏化压缩方法和系统, 2024, 202411182560.3. [[实审]]() 
- 胡燏翀, `明章强`, 王锐, 郑欣觉, 周文翔, 冯丹.&nbsp;&nbsp;面向高性能分布式DNN训练的高效稀疏提前张量融合方法及装置, 2025, 202510575871.4. [[实审]]() 
- 胡燏翀, `明章强`, 周文翔, 郑欣觉, 王锐, 冯丹.&nbsp;&nbsp;一种用于提升分布式训练系统中稀疏通信的弹性梯度合并方法和系统, 2025, 202510575871.4. [[实审]]() 
- 胡燏翀, 郑欣觉, `明章强`, 周文翔, 王锐, 冯丹.&nbsp;&nbsp;一种面向分布式训练的残差显存优化方法, 2025, CN20250503. [[实审]]() 
- 朱敏, `明章强`, 魏骁勇, 李龙兴, 杨勇, 李长林.&nbsp;&nbsp;一种基于全局-局部特征动态对齐的行人重识别方法, 2022, CN113408492B. [[授权]]() 
- 朱敏, `明章强`, 闫建荣, 张万利, 赵志龙.&nbsp;&nbsp;一种基于深度学习的多因素用电负荷预测方法, 2023, CN113962364B. [[授权]]()
- 朱敏, `明章强`, 杨勇, 程俊龙, 高承睿, 李龙兴.&nbsp;&nbsp;一种基于深度神经网络的开集目标检测与识别方法, 2023, CN114241260B. [[授权]]()
- 朱敏, 杨勇, `明章强`, 高承睿, 程俊龙, 李长林, 李龙兴.&nbsp;&nbsp;结合潜在低秩表示和卷积神经网络的红外和可见光图像融合方法, 2023, CN114004775B . [[授权]]() 
- 朱敏, 闫建荣, `明章强`, 王心翌.&nbsp;&nbsp;一种基于深度学习的RBP结合位点预测算法, 2022, CN113035280B. [[授权]]() 
- 朱敏, 高承睿, 程俊龙, 杨勇, `明章强`.&nbsp;&nbsp;一种基于全分辨率表示网络的医学图像分割方法, 2023, CN114898110B. [[授权]]() 



<span class='anchor' id='-ryjx'></span>


# 🏅 荣誉奖项
### 奖学金
- 2022-2023 学年华中科技大学研究生博士一等学业奖学金
- 2023-2024 学年华中科技大学研究生博士一等学业奖学金
- 2024-2025 学年华中科技大学研究生博士三等学业奖学金
- 2024 年华中科技大学优秀研究生奖学金
- 2023-2024 学年工程博士培养改革专项试点奖学金
- 2024-2025 学年华中科技大学华为奖学金
- 2020-2021 学年硕士国家奖学金
- 2019-2022 学年四川大学研究生一等学业奖学金
- 2016-2017 学年本科一等奖学金
- 2015-2016 学年本科国家奖学金

### 竞赛及获奖
- HPDC2024国际学术会议旅行奖(850美元)
- HPDC2025国际学术会议旅行奖(1600美元)
- 2024 年第二届全国大学生信息存储技术竞赛一等奖
- 2024 年计算机学院第三届学术年会最佳论文奖
- 2023 年华中科技大学优秀研究生干部
- 2022 年四川省优秀毕业生
- 2022 年四川大学优秀毕业生干部
- 2019-2020 学年四川大学优秀研究生干部 


### 学生工作
- 2022 - 2026 华中科技大学计算机学院博 2201 团支书
- 2020 - 2021 年第九届 CCF 四川大学学生分会主席


<span class='anchor' id='-xshy'></span>

# 📑 学术会议
<!-- # ![alt text](学术会议.png){: width="25" height="20"} 学术会议 -->
-  明章强, 第 34 届 ACM 高性能并行与分布式计算国际研讨会 HPDC2025, 圣母大学 美国,  Oral.
-  明章强, 第 33 届 ACM 高性能并行与分布式计算国际研讨会 HPDC2024, 比萨大学 意大利, Oral.
-  明章强, 2025 年第二届 CCF 中国存储大会 CCF ChinaStorage2025, 武汉 中国, Poster.
-  明章强, 2024 年第一届 CCF 中国存储大会 CCF ChinaStorage2024, 广州 中国, Poster.
-  明章强, 2024 年华中科技大学计算机学院第三届学术年会, 武汉 中国, Oral.
-  明章强, 2021 年第十一届信息科学与技术国际会议ICIST2021, 成都 中国, 线下.
-  明章强, 2021 年第四届中国模式识别与计算机视觉大会 PRCV2021, 北京 中国, 线下.


<span class='anchor' id='-gzsx'></span>


# 🏭 项目实习

### 科研项目
- 华中科技大学-新华三科技有限公司联合实验室, 智算中心存储建设项目 (2023.06 – 2027.06)
- 深圳市自然科学基金面上项目, 面向分布式 DNN 训练系统的关键存储技术研究 (2023.08 – 2026.08)
- 国家重点研发计划青年科学家项目, 大规模并行计算系统的可靠性编码理论和技术研究 (2021.09– 2024.09)
- 深圳自然科学基金面上项目, 面向低冗余成本的大规模全闪集群下大比例纠删码技术研究 (2020.09– 2023.09)
- 国家重点研发计划项目, 目标跟踪与重定位关键技术研究及应用 (2019.09 – 2022.04)


### 工作实习
<!-- # ![alt text](工作台_1.png){: width="25" height="20"} 工作实习 -->
- 2025.05 - 2026.02,  中电海康集团,  智能算法研究院,    浙江杭州
- 2021.06 - 2021.09,  海康威视研究院, 智能算法应用部,   四川成都
- 2017.06 - 2018.01,  武汉天喻软件有限公司, 产品开发部, 湖北武汉


