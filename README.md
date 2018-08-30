# 看我写的怎么辛苦，点个星星或者打赏下呗
![clipboard image](https://user-images.githubusercontent.com/31888710/43787183-0402c67a-9a9d-11e8-8d44-1e8a02899d39.jpg)
### 前言
因为webstorm 注册码频频失效后，又在工作 产品准备上线的时候，时间本来就不充裕的情况下，webStorm 不能用，搞得我心烦意乱，尝试非常多webstorm 注册码 有的虽然能用，但是还是不太稳定，经常过几天就失效了
#### 尝试过
* 自己搭建IntelliJ IDEA授权服务器
* 利用补丁破解webStorm
* 用过四五十个webstorm注册码，现在已经非常不稳定了

#### 下面就来说下利用补丁破解webStorm，虽然麻烦的一点点，不过也挺稳定，暂时还能出现过问题。
#### 第一步:将补丁复制到安装目录的bin目录下
#### 第二步：修改同目录下WebStorm.exe.vmoptions 和WebStorm64.exe.vmoptions
![image.png](https://upload-images.jianshu.io/upload_images/6206911-b1d48408a635eb9b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

可以使用编辑器，记事本等的工具打开文件，然后添加这行代码
##### -javaagent:安装路径、破解补丁名称（安装路径不同，自行修改）

```
-javaagent:D:\Program Files\JetBrains\WebStorm\bin\JetbrainsCrack-3.1-release-enc.jar
```
#### 修改完成页面成这样
![image.png](https://upload-images.jianshu.io/upload_images/6206911-29cbef5fd6d2d733.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##### 第三步：修改后，保存文件。在此再次启动WebStorm，选择activation code，随便输入文字，数字就行
<hr>

#### 汉化
#### 将resources_cn.jar文件复制到安装目录的lib目录下

![image.png](https://upload-images.jianshu.io/upload_images/6206911-2bf7cc36dfdffba2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 重新打开软件， OK
<hr>

#### 引入我的配置文件settings.jar
![image.png](https://upload-images.jianshu.io/upload_images/6206911-c20e04d7550fecb4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

####  排除node-modules
![image.png](https://upload-images.jianshu.io/upload_images/6206911-38beb0a60e2cbd20.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 鼠标快速格式化代码（点击鼠标滚轮键）
![image.png](https://upload-images.jianshu.io/upload_images/6206911-60d80c5f86620578.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)






