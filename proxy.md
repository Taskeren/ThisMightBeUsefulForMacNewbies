# 代理相关内容

## 代理软件

目前来讲 Clash 是非常好的选择，Clash 在 MacOS 上免费的软件主要有 ClashXPro 和 Clash for Windows（没错，他就叫这个名字）。

ClashXPro 安装比较简单，就非常的正常，但是 CfW 安装时会出现“软件损坏”的情况，你需要执行下面的指令。

```
sudo xattr -r -d com.apple.quarantine [CfW 安装位置]

# 一般安装在应用软件里
sudo xattr -r -d com.apple.quarantine /Applications/Clash\ for\ Windows.app
```

这是因为 MacOS 的软件隔离机制。

## 配置代理

你可以参考 [FuckGFW](https://github.com/Taskeren/ForK-GFW)[*](https://fuck-gfw.taske.ren/)。
