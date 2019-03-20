# KUAKUA_ChatRobot

最近夸夸群很是流行，在公众号看到一则推送，手把手教你定制一款专属夸夸机器人。

<br/>

参考资料：
https://mp.weixin.qq.com/s/EssVIqNXLDWn_HubHzJ8Mw

<br/>

### 前期准备：

- 这份代码用到了python的itchat包，小伙伴需要提前安装一下。

```shell
pip install itchat pillow
```

<br/>

### 具体步骤：

- 运行源代码

- 扫码登录

- 触发关键字即可

<br/>

### 更新日志：

2019/03/18

- 上传源代码

2019/03/19

- 更新说明

<br/>

### 注意事项：

- 此回复是使用了微信网页端，如果设置了自动回复，电脑端微信自动退出。

- 想要在设置哪个群为夸夸群，需要更改代码 if msg['User']['NickName'] == '群名称' ，即将'群名称'改成相应的群名字。

- 语料可以自行添加扩充。

<br/>

### 说明：

用来扫码的那个微信号就自动变成夸夸群机器人，要想体验被夸，需要夸夸群里别的微信号来触发。

用python开发的这款可以在微信群里实现自动夸人的机器人，是不是很简单呢：）

<br/>
