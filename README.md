# OnePlus 8T (kebab) SukiSU Ultra Kernel Builder

> ⚠️ **项目状态：已停止维护 (No longer maintained)**
> 本仓库已停止更新与维护，代码仅供存档与参考。

本项目 Fork 自 [Chinohana/oneplus-8t-kebab-sukisu-ultra-actions](https://github.com/Chinohana/oneplus-8t-kebab-sukisu-ultra-actions)。

## 📝 本 Fork 的主要修改与特性

在原项目的基础上，本仓库添加了以下功能和修改：

### 1. Droidspaces 与容器支持
添加了 Droidspaces 所需的内核配置（如 Cgroups, Namespaces, SYSVIPC 等），这些配置可能同样适用于 Docker、LXC 等容器环境。

### 2. ACA 模式支持
添加了 ACA（Accessory Charger Adapter）模式的支持。
*   **注意**：关于该功能的具体工作原理和使用方式，请直接查看补丁文件：
    [`patches/ACA_mode_support/0001-Add-ACA-mode-support-for-OnePlus-8T.patch`](patches/ACA_mode_support/0001-Add-ACA-mode-support-for-OnePlus-8T.patch)

### 3. Kali NetHunter 补丁
集成了部分 Kali NetHunter 的内核补丁，并在构建工作流中增加了开关以支持 NetHunter 相关的内核特性。

---
*免责声明：刷机有风险，使用本仓库构建的内核造成的任何设备损坏，由使用者自行承担。*
