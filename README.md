# SteamCMD Linux 文件仓库
![Banner](http://114.66.27.10:3000/assets/cs2.jpg)
通过 GitHub Actions 自动构建和更新的 SteamCMD Linux 版本，提供稳定的下载源和加速服务。
原仓库apples1949/SteamCmdLinuxFile

## 🚀 快速开始

### 方法一：使用预构建版本（推荐）

#### 完整安装 SteamCMD

```bash
# 创建并进入目录
mkdir steamcmd && cd steamcmd

# 下载 SteamCMD（使用 gh-proxy 加速）
wget "https://gh-proxy.com/github.com/evanfu08/SteamCmdLinuxFile/releases/download/steamcmd-latest/steamcmd_linux.tar.gz"

# 解压文件
tar -xzf steamcmd_linux.tar.gz

# 运行 SteamCMD
./steamcmd.sh
