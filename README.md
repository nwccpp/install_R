### How to Install R Studio
##### Installation Steps **it is very important to install it in order, first R, then R Studio**:
1. Install R from the download [link](https://cran.r-project.org/mirrors.html). You can pick which one to choose, for example I chose the Duke Mirror <https://archive.linux.duke.edu/cran/>
2. Install R Studio (free desktop version) **AFTER** you installed R, from the [link](https://www.rstudio.com/products/rstudio/download/) <https://www.rstudio.com/products/rstudio/download/>. You will only use R Studio but need to have both on your computer.  

##### How to use R Studio
###### Installing Packages
1. Open R Studio from applications folder\
![R Studio Layout](https://github.com/nwccpp/install_R/blob/images/Presentation1.jpg?raw=true)

2. Create a new project\
![Steps](https://github.com/nwccpp/install_R/blob/images/Presentation2.jpg?raw=true)

3. Click on “File/New File/R script”:\
![New Script](https://github.com/nwccpp/install_R/blob/main/R_Script_1.png?raw=true)

4. Commands in R Studio can be written directly into the console area (bottom left), or in the script. To run a completed command press *Control + Enter*. 

5. Install packages by typing the code in the script and *run* the code
```{r}
install.packages("tidyverse") #data wrangling
install.packages("tidyr") #data wrangling
install.packages("tidytext") #text analysis
install.packages("dplyr") #data wrangling
install.packages("tm") #topic modeling
install.packages("topicmodels") #topic modeling
install.packages("quanteda") #text analysis
install.packages("lubridate") #dates
install.packages("ggplot2") #visualizations
install.packages("ggthemes") #visualizations
install.packages("scales") #visualizations
install.packages("wesanderson") #visualizations
```
4. Load installed packages into library
```{r}
library(tidyverse)
library(tidytext)
library(tidyr)
library(dplyr)
library(tm)
library(topicmodels)
library(quanteda)
library(lubridate)
library(ggplot2)
library(ggthemes)
library(scales)
library(wesanderson)
````
6.For help type ? followed by the *command* and *run*. For shortcuts in R Studio, please see the following [document](https://support.rstudio.com/hc/en-us/articles/200711853-Keyboard-Shortcuts-in-the-RStudio-IDE)
```{r}
?merge
```
7. Now you are ready to work in R Studio! 
