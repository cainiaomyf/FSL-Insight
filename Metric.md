## [Met](#content)

1. 【NIPS‘17】**Prototypical networks for few-shot learning**
<br>*Snell J, Swersky K, Zemel R*
<br>[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/cb8da6767461f2812ae4290eac7cbc42-Paper.pdf)
[code](https://github.com/jakesnell/prototypical-networks)

|*Prototypical Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|49.42±0.78<br>[48.85±0.42]|68.20±0.66<br>[66.87±0.25]|53.31±0.89|72.69±0.74|55.50±0.70<br>[55.49±0.21]|72.00±0.60<br>[72.10±0.13]|56.64±0.23<br>[51.31±0.48]|73.66±0.17<br>[70.14±0.19]|-|-|35.30±0.60<br>[35.90±0.24]|48.60±0.60<br>[49.26±0.25]|98.8<br>[98.27±0.13]|99.7<br>[99.37±0.05]|
|ResNet10|51.98±0.84|72.64±0.64|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|60.37±0.83|78.02±0.57|65.65±0.92|83.40±0.65|72.20±0.70|83.50±0.50|66.09±0.92|82.50±0.58|41.54±0.76|57.08±0.76|-|-|-|-|
|ResNet18|-|-|-|-|-|-|72.99±0.88|86.64±0.51|-|-|-|-|-|-|


2. 【NIPS‘16】**Matching networks for one shot learning**
<br>*Vinyals O, Blundell C, Lillicrap T, Wierstra D*
<br>[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/cb8da6767461f2812ae4290eac7cbc42-Paper.pdf)
[code]()

|*Matching Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|43.56±0.84<br>[48.10±0.81]|55.31±0.73<br>[61.24±0.73]|-|-|-|-|51.45±0.22|75.46±0.18|-|-|-|-|-|-|
|ResNet10|54.49±0.81|68.82±0.65|-|-|-|-|51.45±0.22|75.46±0.18|-|-|-|-|-|-|
|ResNet12|63.08±0.80|75.99±0.60|68.50±0.92|80.60±0.71|-|-|71.87±0.85|85.08±0.57|43.88±0.75|57.05±0.71|-|-|-|-|
|ResNet18|-|-|-|-|-|-|73.49±0.89|84.45±0.58|-|-|-|-|-|-|


3. 【CVPR‘18】**Learning to compare: Relation network for few-shot learning**
<br>*Sung F, Yang Y, Zhang L, Xiang T, Torr P H, Hospedales T M*
<br>[paper](https://proceedings.neurips.cc/paper/2016/file/90e1357833654983612fb05e3ec9148c-Paper.pdf)
[code]()

|*Relation Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|49.31±0.85<br>[50.18±0.46]|66.60±0.69<br>[65.34±0.41]|54.48±0.93|71.32±0.78|55.00±1.00<br>[55.84±0.37]|69.30±0.80<br>[69.57±0.30|58.81±0.24<br>[57.40±0.36]|75.23±0.18<br>[72.09±0.31]|-|-|[35.80±0.18]|[47.80±0.24]|[98.02±0.09]|[99.25±0.05]|
|ResNet10|52.19±0.83|70.20±0.66|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|52.19±0.83|70.20±0.66|64.42±0.36|81.74±0.61|-|-|70.47±0.99|83.70±0.55|42.41±0.21|57.23±0.62|-|-|-|-|
|ResNet18|-|-|-|-|-|-|68.58±0.94|84.05±0.56|-|-|-|-|-|-|


4. 【CVPR‘18】**Learning to compare: Relation network for few-shot learning**
<br>*Sung F, Yang Y, Zhang L, Xiang T, Torr P H, Hospedales T M*
<br>[paper](https://proceedings.neurips.cc/paper/2016/file/90e1357833654983612fb05e3ec9148c-Paper.pdf)
[code]()

|*Relation Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|49.31±0.85<br>[50.18±0.46]|66.60±0.69<br>[65.34±0.41]|54.48±0.93|71.32±0.78|55.00±1.00<br>[55.84±0.37]|69.30±0.80<br>[69.57±0.30|58.81±0.24<br>[57.40±0.36]|75.23±0.18<br>[72.09±0.31]|-|-|[35.80±0.18]|[47.80±0.24]|[98.02±0.09]|[99.25±0.05]|
|ResNet10|52.19±0.83|70.20±0.66|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|52.19±0.83|70.20±0.66|64.42±0.36|81.74±0.61|-|-|70.47±0.99|83.70±0.55|42.41±0.21|57.23±0.62|-|-|-|-|
|ResNet18|-|-|-|-|-|-|68.58±0.94|84.05±0.56|-|-|-|-|-|-|


5. 【ICML‘15】**Siamese neural networks for one-shot image recognition**
<br>*Koch G, Zemel R, Salakhutdinov R*
<br>[paper](https://www.cs.utoronto.ca/~rsalakhu/papers/oneshot1.pdf)
[code]()

|*Siamese Nets*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet10|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet12|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet18|-|-|-|-|-|-|-|-|-|-|-|-|-|-|


6. 【ICCV‘21】**Meta-baseline: Exploring simple meta-learning for few-shot learning**
<br>*Yinbo Chen, Zhuang Liu, Huijuan Xu, Trevor Darrell, Xiaolong Wang*
<br>[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Meta-Baseline_Exploring_Simple_Meta-Learning_for_Few-Shot_Learning_ICCV_2021_paper.pdf)
[code](https://github.com/yinboc/few-shot-meta-baseline)

|*Classifier-Baseline*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|
|ResNet12|58.91±0.23|77.76±0.17|68.07±0.26|83.74±0.18|
|*Classifier-Baseline*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|ConvNet4|-|-|-|-|
|ResNet12|63.17±0.23|79.26±0.17|68.62±0.27| 83.74±0.18|


6. 【NIPS‘21】**Multi-instance attention network for few-shot learning**
<br>*YXu Luo, Longhui Wei, Liangjian Wen, Jinrong Yang, Lingxi Xie, Zenglin Xu, Qi Tian*
<br>[paper](https://proceedings.neurips.cc/paper/2021/file/6cfe0e6127fa25df2a0ef2ae1067d915-Paper.pdf)
[code](https://github.com/Frankluox/FewShotCodeBase)

|*COSOC*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|-|-|-|-|
|ResNet12|69.28±0.49|85.16±0.42|73.57 ± 0.43|87.57 ± 0.10|




