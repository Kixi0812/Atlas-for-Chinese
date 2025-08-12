<h1 align="center">
  <a href="http://atlasos.net" target="_blank"><img src="https://gcore.jsdelivr.net/gh/Atlas-OS/branding@main/banners/banner-v3.png" alt="Atlas" width="800"></a>
</h1>
  <p align="center">
    <a href="https://github.com/Atlas-OS/Atlas/blob/main/LICENSE"><img alt="许可证" src="https://img.shields.io/github/license/atlas-os/atlas?style=for-the-badge&logo=github&color=1A91FF"/></a>
    <a href="https://github.com/Atlas-OS/Atlas/graphs/contributors"><img alt="贡献者" src="https://img.shields.io/github/contributors/atlas-os/atlas?style=for-the-badge&color=1A91FF" /></a>
    <a href="https://github.com/Atlas-OS/Atlas/releases/latest"><img alt="版本" src="https://img.shields.io/github/release/atlas-os/atlas?style=for-the-badge&color=1A91FF" /></a>
    <a href="https://github.com/Atlas-OS/.github/blob/main/profile/CODE_OF_CONDUCT.md"><img alt="行为准则" src="https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=for-the-badge&color=1A91FF" /></a>
  </p>
<p align="center">一款针对Windows的透明化轻量级修改工具，旨在优化性能、隐私与易用性。</p>

<p align="center">
  <a href="https://atlasos.net" target="_blank">🌐 官网</a>
  •
  <a href="https://docs.atlasos.net" target="_blank">📚 文档</a>
  •
  <a href="https://discord.atlasos.net" target="_blank">☎️ Discord</a>
  •
  <a href="https://github.com/Atlas-OS/Atlas/discussions" target="_blank">💬 讨论区</a>
</p>

## 📚 **重要文档**
- [安装指南](https://docs.atlasos.net/getting-started/installation/)
- [常见问题与故障排除](https://docs.atlasos.net/faq-and-troubleshooting/removed-features/)
- [贡献指南](https://docs.atlasos.net/contributions/)
- [品牌规范](https://docs.atlasos.net/branding/)

## 📕 项目介绍
本项目对AtlasOS存储库中的Readme文件进行了汉化，除此之外无其他内容。

## 🤔 什么是Atlas？

AtlasOS（简称Atlas）是一个开源项目，通过便捷地应用隐私保护、易用性优化和性能提升设置来增强Windows功能，同时保持系统的功能完整性与[可定制性](https://docs.atlasos.net/getting-started/post-installation/atlas-folder/general-configuration/)。

## 👀 为什么选择Atlas？
### 🔒 强化隐私保护
Atlas移除了Windows中大部分内置遥测功能，并应用多项组策略以减少数据收集。但需要注意，它无法保障Windows之外的隐私安全（如浏览器及其他第三方应用）。

### 📈 优化性能表现
Atlas在性能与兼容性之间取得平衡。它通过多项切实有效的改动提升Windows的性能和响应速度，同时不破坏核心功能。Atlas不会为追求安慰剂效应或微小提升而进行无关调整，因此更稳定、兼容性更佳。

### 🛡️ 安全功能
大多数Windows修改工具会移除用户维持系统安全所需的关键安全功能。与之不同的是，Atlas允许用户自行定制安全设置（风险自担），同时向用户说明每个选项的[利弊](https://docs.atlasos.net/getting-started/post-installation/atlas-folder/security/)。

部分可选安全功能包括：
- Windows Defender与SmartScreen
- Windows更新（自动更新可切换开启/关闭）
- CPU缓解措施
- 用户账户控制（UAC）
- 核心隔离功能

### ✅ 提升易用性
Atlas通过多项修改和默认设置优化Windows的使用体验，包括移除通常无需使用的应用（可重新安装）、配置界面的多个方面、禁用广告等。

### 🔍 开源且透明
与自定义Windows镜像不同，Atlas因使用[AME Wizard](https://ameliorated.io)而更易于审计。AME Wizard由Playbook（一种可定制的类脚本系统）控制，可执行多种任务。

Playbook实为重命名的**.zip**压缩包，密码为[`malte`](https://docs.ameliorated.io/developers/getting-started/creation.html)。由于其主要由纯文本构成，Playbook确保了透明度——这与存在诸多恶意活动切入点的自定义Windows镜像形成鲜明对比。Playbook中少量的二进制文件在我们的[`utilities`仓库](https://github.com/Atlas-OS/utilities)中开源，其哈希值列于[此处](https://github.com/Atlas-OS/Atlas/blob/main/src/playbook/Executables/AtlasModules/README.md)。

尽管AME Wizard的图形界面并非开源，但其整个后端（名为[TrustedUninstaller](https://github.com/Ameliorated-LLC/trusted-uninstaller-cli)）基于MIT许可证开源，包含运行Atlas所需的各项操作。Atlas Playbook则基于[GPLv3许可证](https://github.com/Atlas-OS/Atlas/blob/main/LICENSE)开源。

### 🔒 合规性
由于Atlas不重新分发修改后的Windows镜像，因此符合[《Windows使用条款》](https://www.microsoft.com/en-us/useterms/#areaheading-uid6738235)。此外，Atlas不会更改Windows的激活状态。

## 🎨 品牌素材包
想要设计原创Atlas壁纸吗？查看我们文档中的[品牌素材包](https://docs.atlasos.net/branding/)，并在[GitHub讨论区](https://github.com/Atlas-OS/Atlas/discussions/categories/community-artwork)分享你的作品！

## 💙 贡献者
<a href="https://github.com/Atlas-OS/Atlas/graphs/contributors" target="_blank"><img src="https://contrib.rocks/image?repo=Atlas-OS/Atlas&columns=18" alt="所有贡献者的头像"></a>
