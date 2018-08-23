### Sublime 3 配置文件

我使用的操作系统是 Ubuntu (目前是 15.10 64-bit) 和 windows 10 64-bit，不同的操作系统，在 sublime 配置上会有微小的差别。

我使用 [Package Control](https://packagecontrol.io/installation)，所有我安装的包在 [Package Control.sublime-settings 文件](https://github.com/kayzhang/sublime-config/blob/master/Package%20Control.sublime-settings) 中都列出了。



### 安装步骤

－ 在新系统上 sublime 3 安装好之后

```console
cd /home/username/.config/sublime-text-3/Packages/User
git clone https://github.com/kayzhang/sublime-config.git
mv sublime-config/*(D) .
rm -rf sublime-config
```

- 到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的包会自动安装上。（ ctrl 跟 导引号 来呼叫出 command console ）
