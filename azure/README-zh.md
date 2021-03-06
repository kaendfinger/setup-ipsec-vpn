﻿# 在 Microsoft Azure 上部署

*其他语言版本: [English](README.md), [简体中文](README-zh.md).*

使用这个模板，你可以在 Microsoft Azure Cloud 上快速搭建一个 VPN 服务器 （<a href="https://azure.microsoft.com/zh-cn/pricing/details/virtual-machines/" target="_blank">定价细节</a>）。

根据你的偏好设置以下选项：

 - VPN Username （用户名）
 - VPN Password （密码）
 - IPsec Pre-Shared Key （预共享密钥）
 - Operating System Image （操作系统镜像，Debian 8 或 Ubuntu 16.04 LTS）
 - Virtual Machine Size （虚拟机大小，默认值： Standard_A0）

请点击以下按钮开始：

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhwdsl2%2Fsetup-ipsec-vpn%2Fmaster%2Fazure%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" alt="Deploy to Azure" />
</a>

屏幕截图：

![Azure Custom Deployment](custom_deployment_screenshot.png)

## 作者

- Daniel Falkner (https://github.com/derdanu)
