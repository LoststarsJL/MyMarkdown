# vscode 无法识别GitBash

记录于：2022年8月22日23:30:37

在重装VScode和Git后以及将Git添加到PATH后，VScode依然不能识别到GitBash

尝试在VScode的setting.json文件中添加配置手动添加GitBash

![图 1](https://cdn.jsdelivr.net/gh/LoststarsJL/MyImage/markdown-image/vscode%E6%97%A0%E6%B3%95%E8%AF%86%E5%88%ABGitBash-2022-08-22-23-25-07.png)  

```json
  "terminal.integrated.profiles.windows": {
    "GitBash": {
      "path": ["D:\\Program Files\\Git\\bin\\bash.exe"],
      "args": []
    }
  }
```

亲测可行

![图 2](https://cdn.jsdelivr.net/gh/LoststarsJL/MyImage/markdown-image/vscode%E6%97%A0%E6%B3%95%E8%AF%86%E5%88%ABGitBash-2022-08-22-23-27-50.png)  
