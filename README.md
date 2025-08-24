<h1 align="center">Cordys CRM</h1>
<h3 align="center">集信息化、数字化、智能化于一体的开源 AI CRM 系统</h3>
<p align="center">
  <a href="https://github.com/1Panel-dev/CordysCRM/releases/latest"><img src="https://img.shields.io/github/v/release/1Panel/CordysCRM" alt="Latest release"></a>
  <a href="https://github.com/1Panel-dev/CordysCRM"><img src="https://img.shields.io/github/stars/1Panel-dev/CordysCRM?color=%231890FF&style=flat-square" alt="Stars"></a>    
  <a href="https://hub.docker.com/r/1panel/cordys"><img src="https://img.shields.io/docker/pulls/1panel/cordys?label=downloads" alt="Download"></a><br/>
</p>

<hr/>

Cordys CRM 是飞致云出品的中国首个开源 AI CRM，集信息化、数字化和智能化于一体。Cordys CRM 预计在2025年底正式开源并发布，现已开启公测。

<img alt="Cordys CRM Overview" src="https://github.com/user-attachments/assets/f202f3ae-25c4-45de-8034-cce3225a9537" />

Cordys CRM 的核心优势是： 

- **灵活易用**：现代化的使用体验，灵活可配置的表单、流程和权限，轻松助力企业实现销售自动化;
- **BI 加持**：借助 DataEase 强大的嵌入式能力和 SQLBot 的智能问数能力，轻松助力企业实现高效的数据分析和可视化;
- **AI 加持**：借助 MaxKB 强大的智能体开发能力，轻松助力企业实现各类销售智能体。

## 快速开始

```
# Linux 机器
docker run -d --name=cordys --restart=always -p 8080:8080 -v ~/.cordys:/opt/cordys 1panel/cordys

# 用户名: admin
# 密码: Cordys@123..
```

你也可以通过 [1Panel 应用商店](https://1panel.cn/) 快速部署 Cordys CRM。

安装完成后，可以参考此 [快速入门指南](https://jlx18gc3up.feishu.cn/docx/VMJzdCipnoj5fYxcbakcWQSAnCh)。

在公测期间，欢迎大家参与并反馈宝贵意见。你可以通过以下微信交流群与Cordys CRM 开源项目组进行交流和反馈。

<image height="150px" width="150px" alt="Cordys CRM QRCode" src="https://github.com/user-attachments/assets/944b8331-f15e-448a-9876-a77ed45d982f" />

## UI 展示

  <tr>
    <img alt="Cordys CRM UI" src="https://github.com/user-attachments/assets/fb7ef62f-2d65-48da-bf38-2538a664edbb"   />
  </tr>

## 飞致云旗下的其他明星项目

- [DataEase](https://github.com/dataease/dataease/) - 人人可用的开源 BI 工具
- [1Panel](https://github.com/1panel-dev/1panel/) - 现代化、开源的 Linux 服务器运维管理面板
- [MaxKB](https://github.com/1panel-dev/MaxKB/) - 强大易用的企业级智能体平台
- [JumpServer](https://github.com/jumpserver/jumpserver/) - 广受欢迎的开源堡垒机
- [Halo](https://github.com/halo-dev/halo/) - 强大易用的开源建站工具
- [MeterSphere](https://github.com/metersphere/metersphere/) - 新一代的开源持续测试工具

## License

本仓库遵循 [FIT2CLOUD Open Source License](LICENSE) 开源协议，该许可证本质上是 GPLv3，但有一些额外的限制。

