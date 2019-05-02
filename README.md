
# CoolCar

**CoolCar**是一款基于安卓开发的智能车载APP，主要包括**健康信息**和**环境信息**两大板块，兼有地图定位、车友讨论和介绍指南等小功能。通过集成在方向盘上的硬件设备，系统能够采集到驾驶员的体温、心率、血压等生理指标以及车内环境的温度、湿度、紫外线强度等指标。APP巧妙地将车内环境和车主健康状况监测融合到一起，使车主能及时掌握自身健康指标以及车内环境，避免因健康状况而引发的安全事故。此外，系统能够通过APP向驾驶者**推送**健康信息，并进行语音播报，可在紧急时刻**自动**拨打求救电话并向呼救目标发送自己的位置信息。
	
|Author|Perfwxc|
|---|---
|E-mail|bigwxc@gmail.com
|WebSite|www.perfwxc.cn


------

# 目录

* [项目背景](#项目背景)
    * 社会背景
    * 竞品分析
* [项目简介](#项目简介)
* [文本](#文本)
    * 普通文本
    * 单行文本
    * 多行文本
    * 文字高亮
    * 换行
    * 斜体
    * 粗体
    * 删除线
* [图片](#图片)
    * 来源于网络的图片
    * GitHub仓库中的图片
* [链接](#链接) 
    * 文字超链接
        *  链接外部URL
        *  链接本仓库里的URL
    *  锚点
    * [图片链接](#图片链接)

------

### 社会背景

如今随着互联网技术的深度发展，大数据、云计算、人工智能等前沿技术逐渐深入到人类生活的方方面面。

伴随着汽车行业的发展，汽车智能化、网联化已成为大势所趋。

与此同时，**驾车安全性**也成为驾驶员驾车出行时的重要因素。

------

### 竞品分析

|#|手机应用|核心功能|特点分析|
|---|---|----|----
|1|`奔驰智能互联手机应用`<br>`666`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")|`baidu`
|2|`乐蜂窝`<br>`666`|![](https://github.com/perfwxc/CoolCar/raw/master/release/pics/编辑信息.png)|`baidu`
|3|`车载精灵`<br>`666`|![](https://github.com/perfwxc/CoolCar/raw/master/release/pics/编辑信息.png)|`baidu`

------

### 项目简介

本系统主要包括**健康信息**和**环境信息**两大板块，兼有地图定位、车友讨论和介绍指南等小功能。通过集成在方向盘上的硬件设备，系统能够采集到驾驶员的体温、心率、血压等生理指标以及车内环境的温度、湿度、紫外线强度等指标。APP巧妙地将车内环境和车主健康状况监测融合到一起，使车主能及时掌握自身健康指标以及车内环境，避免因健康状况而引发的安全事故。此外，系统能够通过APP向驾驶者**推送**健康信息，并进行语音播报，可在紧急时刻**自动**拨打求救电话并向呼救目标发送自己的位置信息。


------
# 一级标题  
## 二级标题  
### 三级标题  
#### 四级标题  
##### 五级标题  
###### 六级标题  


文本
------
### 普通文本
这是一段普通的文本
### 单行文本
    Hello,大家好，我是果冻虾仁。
在一行开头加入1个Tab或者4个空格。
### 文本块
#### 语法1
在连续几行的文本开头加入1个Tab或者4个空格。

    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安

#### 语法2
使用一对各三个的反引号：
```
欢迎到访
我是C++码农
你可以在知乎、CSDN、简书搜索【果冻虾仁】找到我
```
该语法也可以实现代码高亮，见[代码高亮](#代码高亮)
### 文字高亮
文字高亮功能能使行内部分文字高亮，使用一对反引号。
语法：
```
`linux` `网络编程` `socket` `epoll` 
```
效果：`linux` `网络编程` `socket` `epoll`

也适合做一篇文章的tag
#### 换行
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。

或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大。
#### 斜体、粗体、删除线

|语法|效果|
|----|-----|
|`*斜体1*`|*斜体1*|
|`_斜体2_`| _斜体2_|
|`**粗体1**`|**粗体1**|
|`__粗体2__`|__粗体2__|
|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|
|`***斜粗体1***`|***斜粗体1***|
|`___斜粗体2___`|___斜粗体2___|
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
|`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~|

    斜体、粗体、删除线可混合使用

图片
------
基本格式：
```
![alt](URL title)
```
alt和title即对应HTML中的alt和title属性（都可省略）：
- alt表示图片显示失败时的替换文本
- title表示鼠标悬停在图片时的显示文本（注意这里要加引号）

URL即图片的url地址，如果引用本仓库中的图片，直接使用**相对路径**就可了，如果引用其他github仓库中的图片要注意格式，即：`仓库地址/raw/分支名/图片路径`，如：
```
https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
```

|#|语法|效果|
|---|---|----
|1|`baidu`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
|2|`jieshao`|![](https://github.com/perfwxc/CoolCar/raw/master/release/pics/编辑信息.png)

注意例2的写法使用了**URL标识符**的形式，在[链接](#链接)一节有介绍。
>在文末有foryou的定义：


链接
------
### 链接外部URL

|#|语法|效果|
|---|----|-----|
|1|`[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")`|[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")|
|2|`[我的知乎][zhihu] `|[我的知乎][zhihu] |

语法2由两部分组成：
- 第一部分使用两个中括号，[ ]里的标识符（本例中zhihu），可以是数字，字母等的组合，标识符上下对应就行了（**姑且称之为URL标识符**）
- 第二部分标记实际URL。

>使用URL标识符能达到复用的目的，一般把全文所有的URL标识符统一放在文章末尾，这样看起来比较干净。
>>URL标识符是我起的名字，不知道是否准确。囧。。

### 链接本仓库里的URL

|语法|效果|
|----|-----|
|`[我的简介](/example/profile.md)`|[我的简介](/example/profile.md)|
|`[example](./example)`|[example](./example)|

### 图片链接
给图片加链接的本质是混合图片显示语法和普通的链接语法。普通的链接中[ ]内部是链接要显示的文本，而图片链接[ ]里面则是要显示的图片。  
直接混合两种语法当然可以，但是十分啰嗦，为此我们可以使用URL标识符的形式。

|#|语法|效果|
|---|----|:---:|
|1|`[![weibo-logo]](http://weibo.com/linpiaochen)`|[![weibo-logo]](http://weibo.com/linpiaochen)|
|2|`[![](/img/zhihu.png "我的知乎，欢迎关注")][zhihu]`|[![](/img/zhihu.png "我的知乎，欢迎关注")][zhihu]|
|3|`[![csdn-logo]][csdn]`|[![csdn-logo]][csdn]|

因为图片本身和链接本身都支持URL标识符的形式，所以图片链接也可以很简洁（见例3）。  
注意，此时鼠标悬停时显示的文字是图片的title，而非链接本身的title了。
> 本文URL标识符都放置于文末

### 锚点
其实呢，每一个标题都是一个锚点，和HTML的锚点（`#`）类似，比如我们 

|语法|效果|
|---|---|
|`[回到顶部](#readme)`|[回到顶部](#readme)|

不过要注意，标题中的英文字母都被转化为**小写字母**了。
> 以前GitHub对中文支持的不好，所以中文标题不能正确识别为锚点，但是现在已经没问题啦！

