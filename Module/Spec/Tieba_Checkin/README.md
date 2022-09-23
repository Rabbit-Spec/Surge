<h1 align="center">贴吧签到</h1>

<h4 align="center">百度贴吧每日自动签到</h4>

<p align="center">
<img src="https://raw.githubusercontent.com/Rabbit-Spec/Surge/Master/Module/Spec/Tieba_Checkin/img/1.PNG" width="300"></img>
</p>

## 功能
1.每日上午9:30自动签到，显示签到贴吧总数、成功数量、失败数量。<br>
2.针对签到失败的贴吧，进行10次，每次间隔2秒的重试，可以极大提高签到成功率。

## 注意事项
Surge在获取Cookie时，需要在MITM中设置h2=false，即关闭 MITM over HTTP/2，否则会提示获取Cookie出现异常。

需要用MITM over HTTP/2的话，建议在获取Cookie时临时关闭，获取成功后再开启，或者等待客户端修复。

## How to use
### 1. 安装环境
**需要有网络调试工具 Surge**<br>
最低支持版本 :<br>
>**AppStore 版 4.9.3 或更新版本**<br>
>**TestFlight 版 4.11.0 (2014) 或更新版本**

### 2. 模块安装链接
> **公开版 :** https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/tieba/tieba_signin.sgmodule<br>
> **备用版 :** https://raw.githubusercontent.com/Voldeemort/Surge/main/module/tieba/tieba_checkin.sgmodule<br>

### 3. 安装方式
打开 Surge -> 模块 -> 安装新模块... -> 复制粘贴上方的安装链接 -> 完成!
#### 需要开启MitM并信任证书，需要开启脚本

### 4. 更新模块方式
**请按照以下步骤更新**<br>
#### 更新模块本身 : 
>Surge -> 模块 -> 找到本模块 -> 左滑后点击更新<br>
#### 更新外部资源 : 
>点击首页最上方打开 Profile 页面 -> 更新外部资源 <br>

**两次更新之间建议 _ 间隔 5 分钟以上_，否则又几率页面缓存文档尚未更新导致更新失败<br>

#### 若贴吧签到模块失效可以联系作者
- [@blackmatrix7](https://github.com/blackmatrix7)
- [@Voldeemort](https://github.com/Voldeemort)

## 我用的机场
**我用着好用不代表你用着也好用，如果想要入手的话，建议先买一个月体验一下。**<br>
[「Nexitally」佩奇家主站，一家全线中转线路的高端机场。](https://naixii.com/signupbyemail.aspx?MemberCode=0b532ff85dda43e595fb1ae17843ae6d20211110231626) <br>
