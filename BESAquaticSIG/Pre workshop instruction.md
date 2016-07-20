## BES Aquatic SIG ECR workshop

Natalie Cooper (NHM) and David Orme (Imperial College London)

### General and generalised linear models

This day long workshop will focus on the mechanics of  [general linear models](https://en.wikipedia.org/wiki/General_linear_model) and [generalized linear models](https://en.wikipedia.org/wiki/Generalized_linear_model).

These two classes of model are functionally very similar and both support a wide range of different explanatory models. However, the way in which the models are fitted have some fundamental differences that can be very confusing. In ths workshop, we will cover the following:

* Morning session: (09:30 to 12:30, with coffee at 10:45)
  __General linear models in R__: Good practice for working in R and fitting regression, ANOVA and ANCOVA models (general linear models).
* Afternoon session 1: (13:15 - 15:00)
  __Theory of generalized linear models__: The key differences between a general and a generalized linear model and how the models function under the hood.
* Afternoon session 2: (15:15 - 17:00)
  __Generalized linear models in practice__: Using R to fit and assess generalized linear models.

#### Please download the following before the workshop.

* R (the latest version)
* R packages glm
* Data files from: https://github.com/nhcooper123/TeachingMaterials/tree/master/BESAquaticSIG/Data OR https://drive.google.com/folderview?id=0B6WKgRBJw5LOQXJ4WXBPSks2V3M&usp=sharing

#### Before the workshop please ensure you can do the following. 
*If you can't don't panic, but please alert Natalie at the start of the workshop so we can help.*

1. Open R on your computer.
2. Open a script in the R Editor OR script editor of your choice.
  * File > New Document
3. Get help for a particular function.
  * ?nameoffunction
  * Google!
4. Install and load packages in R.
  * install.packages("nameofpackage")
  * library(nameofpackage)
5. Load data into R using read.csv
  * mydata <- read.csv("PATH/dataset.csv")
6. Look at data you have loaded into R.
  * str(mydata)
7. Make simple boxplots and scatter plots
  * boxplot(Y ~ X, data = mydata)
  * plot(Y ~ X, data = mydata)
