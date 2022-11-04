---
title: "alcohol related death in Australia from 1997 to 2020"
author: ''
date: "2022-11-04"
slug: "alcohol-related-death-in-australia-from-1997-to-2020"
categories: []
tags: []
---
![](images/Rplot01.png)
as this figure shows, although the amount came down a little for recent years, the whole number of alcohol related death has risen steadily for decades for 20 years. 
```{r, plot, echo=FALSE}
library(readxl)
w7aw <- read_excel("C:/Users/jingc/Desktop/w7aw.csv")
x<- w7aw$`All alcohol-related deaths`
plot(w7aw$Year, x, xlab = "years", ylab = "number of death", type = "l", col="red", ylim = c(0,5000), main = "alcohol related death from 1997-2020")
```

![](images/Aug22_ALCOHOL2.png)
but drinking status was essentially flat except weekly status.
