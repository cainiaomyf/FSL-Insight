## [Opt](#content)

1. 【ICML‘17】**Model-agnostic meta-learning for fast adaptation of deep networks**
*Finn C, Abbeel P, Levine S*
[paper](http://proceedings.mlr.press/v70/finn17a/finn17a.pdf)
[code](http://github.com/cbfinn/maml)

|*MAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) | Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |CIFARFS<br>(5w,1s) | CIFARFS<br>(5w,5s) | CUB<br>(5w,1s) | CUB<br>(5w,5s) |CIFAR100<br>(5w,1s) | CIFAR100<br>(5w,5s) |FC100<br>(5w,1s) | FC100<br>(5w,5s) | Omn<br>(5w,1s) | Omn<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|ConvNet4|48.70±1.84<br>[49.81±1.78]|63.11±0.92<br>[64.21±1.33]|51.67±1.81<br>[49.00±3.26]|70.30±0.08<br>[67.56±1.80]|58.90±1.90<br>[57.06±3.83]|71.50±1.00<br>[72.24±1.71]|47.85±0.22<br>[53.31±1.77]|64.77±0.20<br>[69.88±1.47]|-|-|37.63±2.23]|[49.14±1.58]|98.70±0.40<br>[97.13±1.25]|99.90±0.10<br>[99.23±0.40]|
|ResNet12|50.96±0.50|68.35±0.47|-|-|-|-|-|-|-|-|-|-|-|-|
|ResNet10|51.98±0.84|66.62±0.83|-|-|-|-|-|-|-|-|-|-|-|-|


2. 【ICLR‘19】**HOW TO TRAIN YOUR MAML**
*Antreas Antoniou, Harrison Edwards, Amos Storkey*
[paper](https://openreview.net/pdf?id=HJGven05Y7)
[code](https://github.com/AntreasAntoniou/HowToTrainYourMAMLPytorch)

|*MAML++*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |
|:------:|:------:|:------:|
|ConvNet4|52.15±0.26|68.32±0.44|



3. 【ICLR‘19】**Meta-learning with latent embedding optimization**
*Andrei A. Rusu, Dushyant Rao, Jakub Sygnowski, Oriol Vinyals*
[paper](https://arxiv.org/pdf/1807.05960)
[code](https://github.com/deepmind/leo)

|*LEO*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|WRN28|61.76 ± 0.08|77.59 ± 0.12|66.33 ± 0.05|81.44 ± 0.09|


4. 【ICLR‘19】**Meta-Learning with Implicit Gradients**
*Aravind Rajeswaran, , Jakub Sygnowski, Sham M. Kakade, Sergey Levine*
[paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/072b030ba126b2f4b2374f342be9ed44-Paper.pdf)
[code](https://github.com/aravindr93/imaml_dev)

|*iMAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|49.30±1.88|59.77±0.73|38.54±1.37|60.24±0.76|

5. 【ArXir‘18】**Recasting gradient-based meta-learning as hierarchical bayes**
*Erin Grant, Chelsea Finn, Sergey Levine, Trevor Darrell, Thomas Griffiths*
[paper](https://arxiv.org/pdf/1801.08930)

|*LMAML*| Mini<br>(5w,1s) | Mini<br>(5w,5s) |Tiered<br>(5w,1s) | Tiered<br>(5w,5s) |
|:------:|:------:|:------:|:------:|:------:|
|ConvNet-4|49.40±1.83|-|-|-|
