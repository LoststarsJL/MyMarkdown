# 【已解决】Git Bash运行git status中文文件名乱码

当运行git status只显示数字串，显示不出中文文件名

![Git Bash乱码-20220829203935](https://raw.githubusercontent.com/LoststarsJL/MyImage/main/markdown-image/Git%20Bash%E4%B9%B1%E7%A0%81-20220829203935.png)

git bash终端输入命令：

```bash
git config --global core.quotepath false
```

![Git Bash乱码-20220829204259](https://raw.githubusercontent.com/LoststarsJL/MyImage/main/markdown-image/Git%20Bash%E4%B9%B1%E7%A0%81-20220829204259.png)