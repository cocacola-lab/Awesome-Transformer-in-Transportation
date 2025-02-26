# <p align=center>Transformer在交通运输中的应用 🚦 🚗 🚕 🛣️ 🚆 🛩️ ⛵️</p>

<div align=center>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
<!-- ![GitHub stars](https://img.shields.io/github/stars/cocacola-lab/Awesome-Transformer-for-Transportation.svg?color=red&style=for-the-badge) 
![GitHub forks](https://img.shields.io/github/forks/cocacola-lab/Awesome-Transformer-for-Transportation.svg?color=yellow&style=for-the-badge) 
![GitHub activity](https://img.shields.io/github/last-commit/cocacola-lab/Awesome-Transformer-for-Transportation?style=for-the-badge) 
![visitors](https://visitor-badge.glitch.me/badge?page_id=cocacola-lab/Awesome-Transformer-for-Transportation)  -->

这是一个关于 Transformer 在交通运输领域中应用的资源合集。

<h4 align="left">
    <p>
        <b>中文</b> |
        <a href="https://github.com/cocacola-lab/Awesome-Transformer-in-Transportation/README.md">English</a>
    <p>
</h4>

</div>
  
## <span id="head-content"> *目录* </span>
* - [ ] [1. 描述](#head1)
* - [ ] [2. 带代码的论文](#head2)
  * - [ ] [交通流预测](#head-Traffic-Forecasting)
  * - [ ] [交通控制](#head-Traffic-Controls)
  * - [ ] [公共交通管理](#head-Public-Transit-Management)
  * - [ ] [公众反馈分析](#head-Analysis-of-Public-Feedback)
  * - [ ] [实时信息发布](#head-Dissemination-of-Real-Time-Information)
  * - [ ] [驾驶员辅助](#head-Co-pilot-for-Drivers)
  * - [ ] [自动驾驶车辆控制](#head-Autonomous-Vehicle-Control)
  * - [ ] [运动规划与执行](#head-Motion-Planning-and-Execution)
  * - [ ] [鸟瞰视角（BEV）感知](#head-Bird's-Eye-View-(BEV)-Perception)
  * - [ ] [路径优化](#head-Route-Optimization)
  * - [ ] [事故预测](#head-Accident-Prediction)
  * - [ ] [安全关键事件检测](#head-Safety-Critical-Event-Detection)
  * - [ ] [交通场景识别](#head-Traffic-Scenario-Identification)
  * - [ ] [其他应用](#head-Other-Applications)
* - [ ] [3. 调研论文](#head3)
* [*联系我*](#head4)

## <span id="head1"> *1. 描述* </span>
>🐌 Markdown 格式:
>
> * (会议/期刊 年份) **标题**, 第一作者等. [[论文](URL)] [[代码](URL)] [[项目](URL)] <br/>
> * (会议/期刊 年份) [💬主题] **标题**, 第一作者等. [[论文](URL)] [[代码](URL)] [[项目](URL)]
>     * (可选) ```🌱``` 或 ```📌```
>     * (可选) 🚀 或 👑 或 📚
>
* 🌱：新颖思想idea
* 📌：有首创性...
* 🚀：效果最好的方法
* 👑：学术界/工业界广泛使用的模型
* 📚：新开源的任务/数据集/基准

## <span id="head2"> *2. 带代码的论文* </span>
    
   * <span id="head-Traffic-Forecasting"> **交通流预测** </span> **[       «🎯返回顶部»       ](#)**
        
       ```准确的交通流预测是智慧交通系统的基石。通过预测交通状况，交通管理部门可以优化交通流、减少拥堵并提升整体效率。Transformer在分析历史交通数据和预测未来交通模式方面表现出色。这一交通流预测任务支持动态交通管理、路线优化以及实时旅客信息发布等前瞻性措施。```

       * (2025 SENSORS) **基于预训练语言模型的时空Transformer网络用于交通流预测**, J Ma 等. [[论文](https://www.mdpi.com/1424-8220/24/17/5502)]
          * ```本工作能够捕捉交通数据中的复杂时空依赖关系，考虑了道路网络、天气状况和历史趋势，从而实现更准确可靠的预测。```
        * (2024 《Communications in Transportation Research》) **基于大语言模型的可解释交通流预测**, Xusen Guo 等. [[论文](https://www.sciencedirect.com/science/article/pii/S2772424724000337)] [[代码](https://github.com/Guoxs/xTP-LLM)]
          * ```MLLMs可以分析包括时间序列、图像及视频在内的多模态交通数据，生成具有可解释性的交通流预测。```      
        * (2024) **TransGPT: 用于交通领域的多模态生成预训练Transformer**, 未指定. [[论文](https://arxiv.org/pdf/2402.07233)] [[代码](未找到)]
            * ```提出了一种整合文本、图像和传感器数据流的多模态Transformer框架，用于交通数据分析。```
        * (2023) **基于深度学习的Transformer模型构建全面实时创伤观测平台：开发与验证研究**, 未指定. [[论文](https://pmc.ncbi.nlm.nih.gov/articles/PMC11041521/)] [[代码](未找到)]
          * ```开发了基于Transformer的模型，用于实时创伤监测系统的构建，并经过临床验证。```

   * <span id="head-Traffic-Control"> **交通控制** </span> **[       «🎯返回顶部»       ](#)**

        ```LLMs可以作为智能交通控制器，通过分析实时数据为驾驶者、基础设施和自动驾驶车辆提供情境感知的决策，从而优化交通流。```

        * (2025) **大语言模型（LLMs）作为城市路口交通控制系统：一种全新范式**, 未指定. [[论文](https://www.mdpi.com/2624-8921/7/1/11)] [[代码](未找到)]
          * ```首创性研究通过多模态数据处理实现了利用LLMs进行实时城市路口管理。```

   * <span id="head-Public-Transit-Management"> **公共交通管理** </span> **[       «🎯返回顶部»       ](#)**

        ```LLMs可以通过优化路线规划、缩短等待时间并提供个性化出行建议，提升公共交通系统的效率。```
        
        * (2025) **探索大语言模型在公共交通中的应用潜力：圣安东尼奥案例研究**, 未指定. [[论文](https://arxiv.org/abs/2501.03904)] [[代码](未找到)]
          * ```本案例研究展示了LLMs在公共交通调度和需求预测中的应用。```

   * <span id="head-Analysis-of-Public-Feedback"> **公众反馈分析** </span> **[       «🎯返回顶部»       ](#)**

        ```LLMs可以分析与交通系统相关的公众投诉和建议，帮助机构根据公众需求和安全要求调整服务。```

        * (2023) **利用大语言模型改进交通服务**, 未指定. [[论文](https://www.morgan.edu/national-transportation-center/the-smarter-center-(2023-2029)/research/use-of-large-language-models-to-improve-transportation-services)] [[代码](未找到)]
          * ```该研究从机构层面探讨了部署LLMs以优化交通服务的策略。```

   * <span id="head-Dissemination-of-Real-Time-Information"> **实时信息发布** </span> **[       «🎯返回顶部»       ](#)**

        ```LLMs能够自动更新社交媒体上的公交系统警报，提供个性化行程推荐，并对政策相关的用户咨询给出清晰且定制化的回复。```

      * (2024) **利用大语言模型提升公共交通服务**, 未指定. [[论文](https://arxiv.org/html/2410.14147v1)] [[代码](未找到)]
        * ```提出了一种基于LLM的框架，通过乘客反馈分析实现公交服务的实时调整。```

   * <span id="head-Co-pilot-for-Drivers"> **驾驶员辅助** </span> **[       «🎯返回顶部»       ](#)** 

        ```大语言模型可以作为驾驶员的助手，提供实时指导、警告和指令，以强化良好的驾驶行为并提高安全性。```
        * (2024) **融合预训练的LLM和LGM与驾驶数据以提高道路安全**, Forbes Tech Council. [[论文](https://www.forbes.com/councils/forbestechcouncil/2024/11/08/fusing-pretrained-llms-and-lgms-with-driving-data-to-improve-road-safety/)] [[代码](Not found)]  
            * ```从行业角度探讨将语言模型和几何模型整合到先进驾驶辅助系统中的方法。```

   * <span id="head-Autonomous-Vehicle-Control"> **自动驾驶车辆控制** </span> **[       «🎯返回顶部»       ](#)**

        ```像特斯拉和Waymo这样的公司在自动驾驶汽车中使用Transformer算法来实现目标检测、路径优化和决策制定。```
        * (2025) **Transformer算法革新AI：从自然语言到自动驾驶汽车**, James Santana. [[论文](https://medium.com/@jamesasantana/transformer-algorithms-revolutionize-ai-from-natural-language-to-self-driving-cars-cd0da43eff25)] [[代码](Not found)]  
            * ```探索在自动驾驶中利用Transformer架构的多模态融合策略，并提出了一种动态注意力分配机制。```
        * (2025) **顶级LLM开发公司**, SoluLab. [[论文](https://www.solulab.com/top-llm-development-companies/)] [[代码](Not found)]  
            * ```行业分析报告：2025年交通运输领域LLM开发公司的技术路线图比较。多模态语言模型通过整合文本分析与实时视频和音频输入，可以增强自动驾驶车辆的控制系统。```
        * (2024) **自动驾驶中的Vision Transformer综述**, 未指定. [[论文](https://arxiv.org/html/2403.07542v1)] [[代码](Not found)]  
            * ```对车道检测任务中ViT与Swin Transformer架构进行了系统比较。```

   * <span id="head-Motion-Planning-and-Execution"> **运动规划与执行** </span> **[       «🎯返回顶部»       ](#)**

        ```在自动驾驶车辆中，Transformer被用于运动规划，将传感器数据转化为精确决策，从而指导车辆控制器规划出最优行驶轨迹。```
        * (2024) **Transformers：自动驾驶的秘密武器**, EE Times Editorial Team. [[论文](https://www.eetimes.eu/transformers-autopilots-secret-weapon/)] [[代码](Not found)]  
            * ```行业报告，分析了在汽车系统芯片设计中为Transformer提供硬件加速的解决方案。```

   * <span id="head-Bird's-Eye-View-(BEV)-Perception"> **鸟瞰视角（BEV）感知** </span> **[       «🎯返回顶部»       ](#)**
            
        ```在自动驾驶中，Transformer被用于实现“鸟瞰视角”（BEV）感知，其中也包括车道检测等任务。```
        * (2023) **加速Transformer神经网络用于自动驾驶**, Ambarella Research. [[论文](https://www.ambarella.com.tw/blog/accelerating-transformer-neural-networks-for-autonomous-driving/)] [[代码](Not found)]  
            * ```提出了一种基于FPGA的Transformer模型压缩方案，以实现车载系统上的实时推理。```
        * (2023 WACV) **Bevsegformer：基于任意摄像装置的鸟瞰视角语义分割**, Peng, Lang, 等. [[论文](https://openaccess.thecvf.com/content/WACV2023/papers/Peng_BEVSegFormer_Birds_Eye_View_Semantic_Segmentation_From_Arbitrary_Camera_Rigs_WACV_2023_paper.pdf)] [[代码](https://)]  
            * ```BEVSegFormer结合Transformer、交叉注意力机制与CNN，以准确检测车道标记并增强调鸟瞰视角特征，从而实现更安全、更可靠的自动导航。```
        * (2022 ECCV) **Persformer：通过透视Transformer与openlane基准进行3D车道检测**, Chen, Li, 等. [[论文](https://link.springer.com/chapter/10.1007/978-3-031-19839-7_32)] [[代码](https://)]  
            * ```PersFormer结合交叉注意力机制、CNN及Transformer，实现车道标记的精确检测并提升鸟瞰视角特征，从而提升自动导航的安全性和可靠性。```

   * <span id="head-Route-Optimization"> **路径优化** </span> **[       «🎯返回顶部»       ](#)**
            
        ```在智能物流中，Transformer被整合用于机器人路径优化。```
        * (2025) **多模态语言模型用于智能交通系统**, 未指定. [[论文](https://arxiv.org/html/2412.11683v1)] [[代码](Not found)]  
            ```提出了一种跨模态对齐损失函数，以弥合文本、图像与传感器数据之间的语义差距。```
        * (2023) **TrafFormer：用于预测长期交通流的Transformer模型**, 未指定. [[论文](https://arxiv.org/abs/2302.12388)] [[代码](Not found)]  
            * ```构建了一个涵盖72小时城市路网交通流预测的框架，融入了时空注意力机制。```
        * (2023) **用于轨迹优化的Transformer及其在航天器会合任务中的应用**, 未指定. [[论文](https://arxiv.org/html/2310.13831v3)] [[代码](Not found)]  
            * ```扩展了Transformer架构以优化航天器轨迹，展示了其在轨道力学中的鲁棒性。```
        * (2025) **Transformer算法革新AI：从自然语言到自动驾驶汽车**, James Santana. [[论文](https://medium.com/@jamesasantana/transformer-algorithms-revolutionize-ai-from-natural-language-to-self-driving-cars-cd0da43eff25)] [[代码](Not found)]  
            * ```讨论了Transformer在自动驾驶系统中多模态融合策略。```

   * <span id="head-Accident-Prediction"> **事故预测** </span> **[       «🎯返回顶部»       ](#)**
            
        ```通过分析天气状况、时间及驾驶员行为等多种因素来预测事故。```
        * (2024) **基于LLM的多模态交通事故预测**, 未指定. [[论文](https://www.mdpi.com/1424-8220/23/22/9225)] [[代码](Not found)]  
            * ```构建了一个整合天气数据与交通摄像头信息的多模态事故预测系统。```
        * (2024) **基于数据驱动的LLM交通管理**, RapidCanvas Team. [[论文](https://www.rapidcanvas.ai/blogs/data-driven-traffic-management-leveraging-llms-for-real-time-decision-making)] [[代码](Not found)]  
            * ```商业案例研究：LLM在优化纽约市交通信号中的部署效果。```

   * <span id="head-Safety-Critical-Event-Detection"> **安全关键事件检测** </span> **[       «🎯返回顶部»       ](#)**
            
        ```多模态语言模型可以分析真实驾驶视频，以识别和理解安全关键事件，如交通模式的突然变化、意外障碍和潜在碰撞。```

   <!-- * <span id="head-Traffic-Condition-Monitoring"> **交通状况监控** </span> **[       «🎯返回顶部»       ](#)**

        ```对交通状态（例如拥堵、事故）进行分类。``` -->

   * <span id="head-Traffic-Scenario-Identification"> **交通场景识别** </span> **[       «🎯返回顶部»       ](#)**
            
        ```识别并定义相关场景。```
        * (2021 IEEE Intelligent Vehicles Symposium) **基于视觉Transformer三元组自编码器潜在空间中的交通场景基础设施新颖性检测与分析**, Jonas Wurst 等. [[论文](https://ieeexplore.ieee.org/abstract/document/9575730)] [[代码](https://github.com/JWTHI/ViTAL-SCENE)]  
               * ```📚 该论文提供了一种使用视觉Transformer作为编码器的三元组自编码器结构。```

  <!-- * <span id="head-Beyond-Transformer"> **Beyond Transformer**  </span> **[       «🎯Back To Top»       ](#)**
      * (arXiv preprint 2021) **Container: Context Aggregation Network**, Peng Gao et al. [[Paper](https://arxiv.org/pdf/2106.01401.pdf)]
        * ```🌱  A unified view of popular architectures for visual inputs – CNN, Transformer and MLP-mixer. ```
        * ```🌱  A novel network block – CONTAINER, which uses a mix of static and dynamic affinity matrices via learnable parameters. ```
        * 📚  Image Classification, Object Detection, Instance Segmentation,  Self-Supervised Representation Learning -->
      



## <span id="head3"> *3. [调研论文](https://github.com/Yutong-Zhou-cv/Awesome-Survey-Papers)* </span> **[       «🎯返回顶部»       ](#)**

[**交通运输中的Transformer：一项调研**](https://arxiv.org) 
<!-- (IJCAI'23 调研专题) -->

<!-- [Q](https://), [Jun](https://) 和 [Liang Sun](https://). -->

#### 如果您觉得这个仓库对您的工作有帮助，请引用我们的调研论文。

```bibtex
内容即将推出

当前正在积极开发中。敬请期待更多激动人心的更新和详细信息。
```

**其他相关调研与综述：**

*  **关于Transformer在深度学习任务中应用的综合调研** [[v1](https://arxiv.org/abs/2306.07303)](2023.06.11)
*  [🧩分割] **基于Transformer的视觉分割调研** [[Awesome Repo](https://github.com/lxtGH/Awesome-Segmenation-With-Transformer)] [[v1](https://arxiv.org/abs/2304.09854)](2023.04.19)
*  [🖊GNN] **计算机视觉中图神经网络和图Transformer的任务导向调研** [[v1](https://arxiv.org/abs/2209.13232)](2022.09.27)
*  [🏃‍动作识别] **用于动作识别的视觉Transformer调研** [[v1](https://arxiv.org/abs/2209.05700)](2022.09.13)
*  [🌌遥感] **遥感中的Transformer调研** [[v1](https://arxiv.org/abs/2209.01206)](2022.09.02)

  
<!--## Stargazers over time
[![Stargazers over time](https://starchart.cc/Yutong-Zhou-cv/Awesome-Transformer-in-CV.svg)](https://starchart.cc/Yutong-Zhou-cv/Awesome-Transformer-in-CV)-->

<!--#comments * (arXiv预印本 2021) **标题**, 第一作者等. [[论文]()] [[代码]()] * ```🌱 提示 ```-->

<!--#comments 折叠内容: <details><summary> <b>名称</b> </summary> ... </details> -->

## <span id="head4"> *联系我* </span>

* [北京交通大学CoLa实验室](https://github.com/cocacola-lab)

* 欢迎随时联系 (💌: <wjhan@@bjtu.edu.cn>)。
* 感谢 [YutongZhou的Github模板](https://github.com/Yutong-Zhou-cv/Awesome-Transformer-in-CV.git) 的支持。
