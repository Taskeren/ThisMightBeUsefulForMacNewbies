# Windows

好吧，其实我发现 Windows 的有些配置部分也是依托答辩。

## 配置环境

### 移除 PowerShell 别名

```powershell
Remove-Item Alias:<alias>
```

移除 Windows 自带的 Curl：

```powershell
Remove-Item Alias:Curl
```

顺便带上用 Chocolatey 安装 Curl：

```powershell
choco install curl -y
```

### Java 多版本管理

你可以复制一份 `java.exe` 改成你想要的名字，例如 `java17.exe`。当使用 Java17 时就可以使用类似下面的指令：`java17 -jar the_program.jar`。
