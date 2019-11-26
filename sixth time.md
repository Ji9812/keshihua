## 一
![刑法](https://github.com/Ji9812/keshihua/blob/master/刑法.jpg)
![keyi](https://github.com/Ji9812/keshihua/blob/master/keyi.jpeg)
## 二
![性犯罪](https://github.com/Ji9812/keshihua/blob/master/性犯罪.jpg)
![keyi2](https://github.com/Ji9812/keshihua/blob/master/keyi2.jpeg)
# 实现用的代码
> setwd("C:/Users/16687/Desktop/keshihuahua")
> install.packages("gcookbook")
> install.packages("readxl")
> library(gcookbook)
> library(readxl)
> hanzaihi <- read_excel("hanzaihi.xlsx")
> View(hanzaihi)
> ggplot(hanzaihi,aes(x = year,y = percent,fill = crowd)) + geom_col(position="dodge")

> haizaihi2 <- read_excel("haizaihi2.xlsx")
> View(haizaihi)
> ggplot(haizaihi2, aes(x = year, y = percent, colour = crowd)) + geom_line()
