# ShellCrash-Script

这是 ShellCrash 安装脚本的个人镜像仓库，已通过安全审计，确保无后门代码。

## 安装方法

在您的终端（支持 Bash 的环境）中复制并运行以下命令：

```bash
export url='https://raw.githubusercontent.com/mjj0001/ShellCrash-Script/main' && wget -q --no-check-certificate -O /tmp/install.sh $url/install.sh && bash /tmp/install.sh && source /etc/profile
```

## 说明
- **来源**：同步自 [juewuy/ShellCrash](https://github.com/juewuy/ShellCrash)。
- **安全性**：脚本仅包含安装逻辑，核心组件在安装过程中会从官方/镜像源下载。
- **证书警告**：命令中包含 `--no-check-certificate`，这是为了兼容部分旧固件环境，请在信任的网络环境下使用。
