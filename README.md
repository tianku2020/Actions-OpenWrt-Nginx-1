# Actions OpenWrt Snapshot

刚接触openwrt的新手勿用.

openwrt官方master分支版本,Kernel 5.4,包含了主流插件以及针对国内环境做了必要的优化,只针对X86_64,其他设备请自行调整与编译,包含PHP,uhttpd换成了nginx,大大增加了可玩性,比如kodexplorer,webdav,反向代理等,可作为NAS使用.

在[Releases](https://github.com/garypang13/Actions-OpenWrt-Snapshot/releases)下载已编译好的固件,周更.

后台默认地址 10.0.0.1
默认密码 root

自己编译需要[在此](https://github.com/settings/tokens)创建个token,然后在此仓库Settings->Secrets中添加个名字为REPO_TOKEN的Secret,填入token值,否者无法release

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars)](https://github.com/P3TERX/Actions-OpenWrt/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks)](https://github.com/P3TERX/Actions-OpenWrt/fork)

Build OpenWrt using GitHub Actions

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

[GitHub Actions Group](https://t.me/GitHub_Actions) | [GitHub Actions Channel](https://t.me/GitHub_Actions_Channel)

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/P3TERX/Actions-OpenWrt)
- Generate `.config` files using [OpenWrt](https://github.com/openwrt/openwrt/tree/openwrt-19.07) source code.
- Push `.config` file to the GitHub repository, and the build starts automatically.Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

## Acknowledgments

- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE) © P3TERX
