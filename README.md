# EdgeDI

This is the source code for our paper: **Joint Architecture Design and Workload Partitioning for DNN Inference on Industrial IoT Clusters**. A brief introduction of this work is as follows:

> The advent of Deep Neural Networks (DNNs) has empowered numerous computer-vision applications. Due to the high computational intensity of DNN models, as well as the resource constrained nature of Industrial Internet-of-Things (IIoT) devices, it is generally very challenging to deploy and execute DNNs efficiently in the industrial scenarios. Substantial research has focused on model compression or edge-cloud offloading, which trades off accuracy for efficiency or depends on high-quality infrastructure support, respectively. In this article, we present EdgeDI, a framework for executing DNN inference in a partitioned, distributed manner on a cluster of IIoT devices. To improve the inference performance, EdgeDI exploits two key optimization knobs, including: (1) Model compression based on deep architecture design, which transforms the target DNN model into a compact one that reduces the resource requirements for IIoT devices without sacrificing accuracy; (2) Distributed inference based on adaptive workload partitioning, which achieves high parallelism by adaptively balancing the workload distribution among IIoT devices under heterogeneous resource conditions. We have implemented EdgeDI based on PyTorch, and evaluated its performance with the NEU-CLS defect classification task and two typical DNN models (i.e., VGG and ResNet) on a cluster of heterogeneous Raspberry Pi devices. The results indicate that the proposed two optimization approaches significantly outperform the existing solutions in their specific domains. When they are well combined, EdgeDI can provide scalable DNN inference speedups that are very close to or even much higher than the theoretical speedup bounds, while still maintaining the desired accuracy.

> 深度神经网络（DNN）的出现推动了众多计算机视觉应用的发展。由于DNN模型的高计算强度以及工业物联网（IIoT）设备资源受限的特性，在工业场景中高效部署和执行DNN通常面临巨大挑战。现有研究主要聚焦模型压缩或边缘-云端卸载方案，前者以精度换取效率，后者则依赖于高质量的基础设施支持。本文提出EdgeDI框架，可在IIoT设备集群上以分区分布式方式执行DNN推理。为提升推理性能，EdgeDI采用两个关键优化维度：（1）基于深度架构设计的模型压缩技术，将目标DNN模型转换为紧凑版本，在保持精度的同时降低IIoT设备资源需求；（2）基于自适应工作负载划分的分布式推理机制，通过在异构资源条件下动态平衡IIoT设备间的工作负载分配来实现高度并行化。我们基于PyTorch实现了EdgeDI，并采用NEU-CLS缺陷分类任务和两种典型DNN模型（VGG与ResNet）在异构树莓派设备集群上评估其性能。结果表明：所提出的两种优化方法在各自领域显著优于现有方案。当二者协同工作时，EdgeDI可提供接近甚至远超理论加速上限的可扩展推理加速，同时保持预期精度。

It is published by ACM Transactions on Internet Technology (ACM ToIT). You can also refer to another relevant work [EdgeLD](https://github.com/fangvv/EdgeLD) from our team.

## Required software

PyTorch

## Citation

    @article{fang2023joint,
        title={Joint Architecture Design and Workload Partitioning for DNN Inference on Industrial IoT Clusters},
        author={Fang, Weiwei and Xu, Wenyuan and Yu, Chongchong and Xiong, Neal N},
        journal={ACM Transactions on Internet Technology},
        volume={23},
        number={1},
        pages={1--21},
        year={2023},
        publisher={ACM New York, NY}
    }

## Contact

Wenyuan Xu (19120419@bjtu.edu.cn)

> Please note that the open source code in this repository was mainly completed by the graduate student author during his master's degree study. Since the author did not continue to engage in scientific research work after graduation, it is difficult to continue to maintain and update these codes. We sincerely apologize that these codes are for reference only.
