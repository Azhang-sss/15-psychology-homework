# R语言习题集[^1]
[^1]:说明：所有命令，在github文档中，应当放在``（数字1左边的键）符号中

## 一、数据输入（10分）
### 请将下表在R中输入成data frame的格式，命名为prac01。

|*ID*|*Major*|*mid*|*final*|*total*|*Male*|
|:---:|:---:|:---:|:---:|:---:|:---:|
|1|英语|83|85|84|TRUE|
|2|法语|88|84|86|TRUE|
|3|社会工作|82|86|84|FALSE|
|4|应用心理学|89|88|88|FALSE|
|5|应用心理学|86|86|86|TRUE|
### 答案：
★(1511105 商美）




## 二、命令练习（20分）
###  (一)在#号后面解释前述命令的功能

`seq(1, 20, by = 2) #`  

`LETTERS[1:5] #`  

`letters[5:1] #`  

`rep(LETTERS[1:3], each = 3) #`  

`rep(LETTERS[1:3], times = 3) #`  

`dnorm(-2, 10, 2) #`  

`pnorm(-2, 10, 2) #`  

`pnorm(2.5)-pnorm(2) #`  

`rnorm(10, 20, 5) #`  

`qnorm(0.25, 10, 2) #`  

`cbind(dataA, dataB) #`  

`rbind(data, dataB) #`  

`quantile(x, probs = c(0.1, 0.6, 0.9) #`  

`scale(x, center = T, scale = T) #`  

`min(x) #`  

`max(x) #`  

`mean(x) #`  

`sd(x) #`  

`median(x) #`  

`cor(x, y) #`  

`IQR(x) #`  

`choose(n, k) #`  

`summary(x) #`  

`factorial(n) #`  

`fivenum(x) #`  

`options(digits = 5) #`  

`var(x) #`  

`round(x) #`  

`choose(10, 6) * factorial(6) #`
(1512894 尚灵)

## 三、数据操纵（30分）  
***
### &emsp;&emsp;（二）数据*PDSurveyBasic.xlsx*是南开大学汪新建教授主持的《医患信任建设的社会心理机制研究》这一项目中《医患社会心态问卷：患方卷》的部分试调查数据，该数据使用问卷星平台获得，下载*Excel*格式后我们将部分基础信息提取保存，并将变量名改为英文。部分数据显示如下：  
|*ID*|*Time1*|*Time2*|*IP*|*Relationship*|*Student*|
|:---:|:---:|:---:|:---:|:---:|:---:|
|8|2017/4/30 17:47:48|42秒|36.111.130.24(内蒙古-呼和浩特)|3|1|
|9|2017/4/30 18:41:02|3130秒|36.111.130.24(内蒙古-呼和浩特)|4|2|
|10|2017/4/30 20:08:23|1559秒|124.31.6.128(西藏-拉萨)|5|2|
|11|2017/4/30 20:08:49|1540秒|124.31.6.128(西藏-拉萨)|5|2|
|12|2017/4/30 20:09:12|926秒|106.57.158.22(云南-丽江)|3|2|
|13|2017/4/30 20:19:47|30秒|220.115.23.8(天津-天津)|5|1|
|14|2017/4/30 20:20:56|65秒|220.115.23.8(天津-天津)|5|1|
|15|2017/4/30 20:32:17|965秒|106.57.158.22(云南-丽江)|2|2|
|16|2017/4/30 20:37:46|2955秒|123.54.168.84(河南-信阳)|2|	2|
 
  
★(1512898张雪丽)
***

