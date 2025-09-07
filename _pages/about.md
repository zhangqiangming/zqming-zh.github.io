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


我将于2026年5月博士毕业于湖北武汉的华中科技大学, 计算机科学与技术学院, 信息存储及应用实验室, 冯丹教授团队。我的博士导师是胡燏翀教授, 专业为计算机体系结构。硕士毕业于四川成都的四川大学, 计算机学院, 专业为计算机技术。包括合著，我已经发表20+篇学术论文。
 <a href='https://scholar.google.com/citations?user=pGBngNMAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>


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
- *2022.09 - 2026.06*, &nbsp;&nbsp;  <a href="https://www.hust.edu.cn/"><img class="svg" src="https://zhangqiangming.github.io/zqming-zh.github.io/images/HUST_logo.svg" width="23pt"></a>华中科技大学&nbsp; &nbsp; &nbsp; 计算机科学与技术学院 &nbsp; &nbsp;  计算机科学与技术专业, &nbsp; &nbsp; 博士研究生


- *2019.09 - 2022.06*, &nbsp;&nbsp;  <a href="https://www.scu.edu.cn/"><img class="svg" src="https://zhangqiangming.github.io/zqming-zh.github.io/images/SCU_logo.svg" width="20pt"></a> 四川大学&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;  计算机学院 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  计算机技术专业 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  硕士研究生


<!-- - *2014.09 - 2018.06*, &nbsp;&nbsp;  <a href="https://www.yangtzeu.edu.cn/"><img class="svg" src="https://zhangqiangming.github.io/zqming-zh.github.io/images/cjdx_logo.png" width="20pt"></a> 长江大学&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 计算机科学与技术学院 &nbsp; &nbsp;  计算机科学与技术专业 &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;  本科生 -->



<span class='anchor' id='-lwzl'></span>
# 📝 论文专利


### 学术论文
<!-- --- -->
<div class='paper-box'>
<div class='paper-box-image'>
<div>
<!-- <div class="badge">HPDC 2024</div> -->
<!-- <img src='images/papers/hpdc2024.png' alt="sym" width="110%">-->
</div>
</div> 
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "ADTopk: All-Dimension Top-k Compression for High-Performance Data-Parallel DNN Training." 2024. In Proceedings of the 33rd International Symposium on High-Performance Parallel and Distributed Computing. (HPDC'24, Acceptance Rate=17.1%, 高性能顶会, CSRanking) [[网页]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)
</div>
</div>



<div class='paper-box'>
<div class='paper-box-image'>
<div>
<!-- <div class="badge">HPDC 2025</div> -->
<!-- <img src='images/papers/hpdc2024.png' alt="sym" width="110%">-->
</div>
</div> 
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "SAFusion: Efficient Tensor Fusion with Sparsification Ahead for High-Performance Distributed DNN Training." 2025. In Proceedings of the 34th ACM International Symposium on High-Performance Parallel and Distributed Computing. (HPDC'25, Acceptance Rate=18.7%, 高性能顶会, CSRanking) [[网页]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">ICDE 2026</div> -->
<!-- <img src='images/papers/hpdc2024.png' alt="sym" width="110%">--></div></div> 
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Rui, Wang, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "SSFusion: Tensor Fusion with Selective Sparsification for Efficient Distributed DNN Training." 2026. In Proceedings of the 42st IEEE International Conference on Data Engineering (ICDE'26, CCF-A, CSRanking) [[网页]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">ASPLOS 2026</div> -->
<!-- <img src='images/papers/hpdc2024.png' alt="sym" width="110%">--></div></div> 
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Yuchong Hu, Patrick P. C. Lee, Xinjue Zheng, Wenxiang Zhou, and Dan Feng. "AsymCheck: Asymmetric Partitioned Checkpointing for Efficient Large Language Model Training." 2026. In Proceedings of the International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS'26, CCF-A, CSRanking) [[网页]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">EuroPar 2025</div> -->
<!-- <img src='images/papers/hpdc2024.png' alt="sym" width="110%">--></div></div> 
<div class='paper-box-text' markdown="1">

-	Xinjue Zheng, `Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, and Dan Feng. "Saving Memory via Residual Reduction for DNN Training with Compressed Communication." 2025. In Proceedings of the European Conference on Parallel Processing (EuroPar'26, CCF-B, CSRanking) [[网页]](https://dl.acm.org/doi/abs/10.1145/3625549.3658678) [[预览]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678) [[下载]](https://dl.acm.org/doi/pdf/10.1145/3625549.3658678)
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">IVC 2026</div> -->
<!-- <img src='images/papers/reid.png' alt="sym" width="110%"> -->
</div>
</div>
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Min Zhu, Xiangkun Wang, Jiamin Zhu, Junlong Cheng, Chengrui Gao, Yong Yang, and Xiaoyong Wei. "Deep learning-based person re-identification methods: A survey and outlook of recent works." Image and Vision Computing 119 (2022): 104394. (CCF-C; IF:3.291) [[网页]](https://www.sciencedirect.com/science/article/pii/S0262885622000233) [[预览]](https://www.sciencedirect.com/science/article/pii/S0262885622000233) [[下载]](https://www.sciencedirect.com/science/article/pii/S0262885622000233)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">HPDC 2024</div>
<img src='images/papers/gan.png' alt="sym" width="110%"> -->
</div></div>
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Min Zhu, Jianrong Yan, Yong Yang, and Jiamin Zhu. "A survey on generative adversarial network based person re-identification method." Journal of Computer-Aided Design & Computer Graphics 34, no. 2 (2022): 163-179. (JCR:Q4; IF:0.536) 
[[网页]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[预览]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[下载]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div>
<!-- <div class="badge">HPDC 2024</div>
<img src='images/papers/glnet2021.png' alt="sym" width="110%" > -->
</div></div>
<div class='paper-box-text' markdown="1">

-	`Zhangqiang Ming`, Yong Yang, Xiaoyong Wei, Jianrong Yan, Xiangkun Wang, Fengjie Wang, and Min Zhu. "Global-local dynamic feature alignment network for person re-identification." arXiv preprint arXiv:2109.05759 (2021). [[网页]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[预览]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852) [[下载]](https://www.jcad.cn/en/article/doi/10.3724/SP.J.1089.2022.18852)
</div>
</div>


- `Zhangqiang Ming`, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "Gradient Compression Techniques in Distributed DNNs Training Systems: A Survey and Outlooks." arXiv preprint arXiv:2310.14484 (2023).
[[网页]](https://dx.doi.org/10.3390/ma15207362) [[预览]]() [[下载]]()


- Yong Yang, Chengrui Gao, `Zhangqiang Ming`, Jixiang Guo, Edou Leopold, Junlong Cheng, Jie Zuo, and Min Zhu. "LatLRR-CNN: An infrared and visible image fusion method combining latent low-rank representation and CNN." Multimedia Tools and Applications 82, no. 23 (2023): 36303-36323. (JCR:Q1; IF:3.748)  
[[网页]](https://dx.doi.org/10.3390/ma15207362) [[预览]]() [[下载]]()


- Junlong Cheng,  Chengrui Gao, Changlin Li, `Zhangqiang Ming`, Yong Yang, Fengjie Wang, and Min Zhu. "F2RNET: A Full-Resolution Representation Network for Biomedical Image Segmentation." In 2022 IEEE International Conference on Image Processing (ICIP), pp. 2406-2410. IEEE, 2022.
[[网页]](https://dx.doi.org/10.3390/app12199703) [[预览]]() [[下载]]()


- Cheng, Junlong, Chengrui Gao, Hongchun Lu, `Zhangqiang Ming`, Yong Yang, and Min Zhu. "PL-Net: progressive learning network for medical image segmentation[J]." Frontiers in Bioengineering and Biotechnology, 2024, 12: 1414605. (2024).
[[网页]](https://dx.doi.org/10.3390/w14172736) [[预览]]() [[下载]]()




<!-- 
### 中文
---

- `明章强`，王荣彪，康宜华. 大提离漏磁无损检测方法. *无损检测*. 2022,44(4): 67. (核心期刊)  
[[网页]](https://dx.doi.org/10.11973/wsjc202204000) [[预览]]() [[下载]]()  

- 刘伯承, `明章强*`, 王荣彪, 叶文超, 康宜华. 基于TMR的轴承滚子微细裂纹漏磁检测方法. *仪表技术与传感器*. 2021(12): 111-114+118.  (通讯作者; 核心期刊)  
[[网页]](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDAUTO&filename=YBJS202112021) [[预览]]() [[下载]]()  

- 汪圣涵, `明章强*`, 刘军, 陈文宇, 康宜华. 双机械手操作的轴承阵列漏磁检测方法与系统. *轴承*. 2021(01): 54-58+65. (通讯作者; 核心期刊)  
[[网页]](https://dx.doi.org/10.19533/j.issn1000-3762.2021.01.011) [[预览]]() [[下载]]()  
 -->


### 发明专利
<!-- --- -->
- 胡燏翀, `明章强`, 周文翔, 郑欣觉, 罗致远, 冯丹.&nbsp;&nbsp;一种面向高性能数据并行DNN训练的全维度Top-k稀疏化压缩方法和系统, 2024, 202411182560.3. [[实审]]() 
- 胡燏翀, `明章强`, 周文翔, 郑欣觉, 罗致远, 冯丹.&nbsp;&nbsp;面向高性能分布式DNN训练的高效稀疏提前张量融合方法及装置, 2025, 202510575871.4. [[实审]]() 
- 胡燏翀, `明章强`, 周文翔, 郑欣觉, 罗致远, 冯丹.&nbsp;&nbsp;一种用于提升分布式训练系统中稀疏通信的弹性梯度合并方法和系统, 2025, 202510575871.4. [[实审]]() 
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
- *2015.11* 获得 第十四届“挑战杯”全国大学生课外学术科技作品竞赛 `一等奖`  
- *2015.06* 获得 第十三届“挑战杯”四川大学生课外学术科技作品竞赛 `一等奖` [[新闻]](https://www.sc.gov.cn/10462/10778/10876/2015/7/1/10341562.shtml)  
- *2014.12* 获得 华中科技大学博士学业一定奖学金 `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  


### 竞赛获奖
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  


### 荣誉称号
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  
- *2014.12* 获得 第四届全国大学生工程训练综合能力竞赛（四川赛区） `一等奖`  



<span class='anchor' id='-xshy'></span>

# 📑 学术会议
<!-- # ![alt text](学术会议.png){: width="25" height="20"} 学术会议 -->
- *2025.06*, 第十九届国际应用电磁学与力学会议 (ISEM 2019), 江苏南京, 海报
- *2025.06*, 第十九届国际应用电磁学与力学会议 (ISEM 2019), 江苏南京, 海报
- *2024.12*, 2024CCF中国计算机存储大会, 广东广州, Poster
- *2024.06*, 第十九届国际应用电磁学与力学会议 (ISEM 2019), 意大利比萨, Oral
- *2023.10*, 第六届中国国际管道会议 (CIPC 2017), 广东广州, Poster
- *2019.10*, 第二届中国计算机视觉大会 (CVPR 2017), 陕西西安

<span class='anchor' id='-gzsx'></span>


# 🏭 工作实习
<!-- # ![alt text](工作台_1.png){: width="25" height="20"} 工作实习 -->
- *2018.05 - 2020.02*, 中电海康集团, 智能算法研究院, 浙江杭州
- *2020.11.25 - 2020.12.02*, 海康威视研究院, 智能算法应用部, 四川成都
- *2017.6 - 2021.1*, 武汉天喻软件, 湖北武汉





