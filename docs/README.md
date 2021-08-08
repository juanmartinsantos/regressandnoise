<br>

This web-page contains complementary material to the research paper:

| <a href="#img1"><img src="bannercolor.jpg" width="100" height="10"></a>| <a href="#img1"><img src="bannercolor.jpg" width="750" height="10"></a>|
|:---|:---|
|<a href="#img1"><img src="icon-research.jpg" width="150"></a>|Juan Martín, José A. Sáez, Emilio Corchado. **On the regressand noise problem: model robustness and synergy with regression-adapted noise filters**. [IEEE Access](https://ieeeaccess.ieee.org/), 2021 (submitted).|
| <a href="#img1"><img src="bannercolor.jpg" width="100" height="10"></a>| <a href="#img1"><img src="bannercolor.jpg" width="750" height="10"></a>|

<br>

The web is organized according to the following summary:

1. [Abstract](#Abstract)
2. [Real-world datasets](#Datasets)
3. [Performance results](#Performance)

<br>
 
## <a name="Abstract"></a> 1. Abstract
This research focuses on analyzing the robustness of different regression paradigms under regressand noise, which has not been examined in depth in the specialized literature. Furthermore, their synergy with fourteen noise preprocessing techniques adapted from the field of classification, known as noise filters, is studied. In order to do this, several noise levels are injected into the output variable of 20 real-world datasets. They are used to evaluate the performance of each regression algorithm with and without the employment of noise filters. The results obtained allow building a robustness ranking of the regression methods to regressand noise. This provides interesting findings, such as some learning paradigms change their well-know behaviour with noise in classification problems when they are applied to regression data. On the other hand, the usage of noise filters improves the performance of regression methods, showing different synergies depending on the regression paradigm and filter employed. 



<br>
 
## <a name="Datasets"></a> 2. Real-world datasets
This research considers 20 different regression datasets taken from the *UCI machine learning* and *KEEL-dataset* repositories. Different noise levels (ranging from x = 5% to x = 30%, by increments of 5%) are introduced into them. These datasets are shown in the following figure, along with the number of attributes (#at) and samples (#sa) for each one.

<center>
<a href="#img2"><img src="sb-datasets.png" width="600"></a>
</center>

These datasets can be downloaded from the web-pages:

[https://archive.ics.uci.edu/ml/datasets.php](https://archive.ics.uci.edu/)

[http://www.keel.es/](http://www.keel.es/)

<br>

## <a name="Performance"></a> 3. Performance results

|<a href="#img1"><img src="bannercolor.jpg" width="750" height="10"></a>|<a href="#img1"><img src="bannercolor.jpg" width="100" height="10"></a>|
|:---|:---:|
|&nbsp;&nbsp;&nbsp;**-** *Performance results of RPART.* | [<img src="icon-excel.png" width="50">](https://github.com/juanmartinsantos/regressandnoise/blob/main/docs/RMSE_RPART_git.xlsx?raw=true)|
|&nbsp;&nbsp;&nbsp;**-** *Performance results of NN.* | [<img src="icon-excel.png" width="50">](https://github.com/juanmartinsantos/regressandnoise/blob/main/docs/RMSE_NN_git.xlsx?raw=true)|
|&nbsp;&nbsp;&nbsp;**-** *Performance results of SVM.* | [<img src="icon-excel.png" width="50">](https://github.com/juanmartinsantos/regressandnoise/blob/main/docs/RMSE_SVM_git.xlsx?raw=true)|
|&nbsp;&nbsp;&nbsp;**-** *Performance results of ELM.* | [<img src="icon-excel.png" width="50">](https://github.com/juanmartinsantos/regressandnoise/blob/main/docs/RMSE_ELM_git.xlsx?raw=true)|
|&nbsp;&nbsp;&nbsp;**-** *Performance results of XGBoost.* | [<img src="icon-excel.png" width="50">](https://github.com/juanmartinsantos/regressandnoise/blob/main/docs/RMSE_XGBoost_git.xlsx?raw=true)|
|<a href="#img1"><img src="bannercolor.jpg" width="750" height="10"></a>|<a href="#img1"><img src="bannercolor.jpg" width="100" height="10"></a>|
