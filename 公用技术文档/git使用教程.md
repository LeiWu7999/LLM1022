# Git使用教程
## 首先管理员需要将协作人员拉入项目协作中：

进入要协作的项目，打开设置，添加成员
<div align="center">
<img src="./图片池/git图片1.png" alt="综述图1">
</div>
<div align="center">
<img src="./图片池/git图片2.png" alt="综述图1">
</div>
<div align="center">
<img src="./图片池/git图片3.png" alt="综述图1">
</div>

## Git成员操作：
### 安装与拉取仓库
首先，先按照教程在本地电脑安装Git：[Git安装教程](https://zhuanlan.zhihu.com/p/13401552684)


安装好后，在桌面新建文件夹，并用cursor打开文件夹


---
在cursor中新建git bash终端
</div>
<div align="center">
<img src="./图片池/git5.png" alt="综述图1">
</div>

---
终端里输入以下命令：
```bash
git clone https://github.com/LeiWu7999/LLM1022.git
```

---
完成后就可以看到项目文件了:


</div>
<div align="center">
<img src="./图片池/git6.png" alt="综述图1">
</div>

---
Git插件若显示这个界面说明Git启动成功了:

</div>
<div align="center">
<img src="./图片池/git7.png" alt="综述图1">
</div>

---
Git代理配置

先找到自己代理软件走的端口，例如V2ray：
</div>
<div align="center">
<img src="./图片池/git8.png" alt="综述图1">
</div>

---

在Git Bash中输入以下命令即可：
```
git config --global http.proxy http://127.0.0.1:(代理端口号)
```

---

### Git协作功能的使用

#### 同步功能
接下来就可以在仓库中进行添加和修改操作了，操作完成后，可以在Git插件中查看更改

</div>
<div align="center">
<img src="./图片池/git9.png" alt="综述图1">
</div>

在消息框中填入更改说明，例如：更改了XXX文件，即可点提交，提交后点击同步即可完成修改的上传同步。

#### 注意事项

上传同步前，请确保本地仓库进度和云端仓库是一样的

</div>
<div align="center">
<img src="./图片池/git10.png" alt="综述图1">
</div>

①代表本地仓库进度，②代表云端仓库进度，若进度不统一①会在②后面，这时更新本地仓库即可：

</div>
<div align="center">
<img src="./图片池/git11.png" alt="综述图1">
</div>