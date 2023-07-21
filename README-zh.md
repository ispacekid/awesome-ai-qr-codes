# Awesome AI QR Codes [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**收录 AI 二维码工具和资源的精选列表。**

🇬🇧 [English](README.md)｜🇨🇳 [中文](README-zh.md)

## 目录

- [教程](#教程)
- [生成工具](#生成工具)
- [Stable Diffusion 模型与扩展](#stable-diffusion-模型与扩展)
- [社区](#社区)

## 教程

### 文章

###### 精选

- [Stable Diffusion QR Code 101](https://antfu.me/posts/ai-qrcode-101) by [Anthony Fu](https://antfu.me/) - 一份值得所有初学者阅读的 AI 二维码制作上手指南。
- [Refining AI Generated QR Code](https://antfu.me/posts/ai-qrcode-refine) by [Anthony Fu](https://antfu.me/) - 关于如何完善 AI 生成的二维码。
- [Stylistic QR Code with Stable Diffusion](https://antfu.me/posts/ai-qrcode) by [Anthony Fu](https://antfu.me/)
- [AI 生成可扫码图像 — 新 ControlNet 模型展示](https://mp.weixin.qq.com/s/i4WR5ULH1ZZYl8Watf3EPw) (Chinese) by [nhciao (ciaochaos)](https://github.com/ciaochaos) - 最早基于 Stable Diffusion AI 二维码的原创研究，讲述项目的缘起、训练过程，并附带了许多生图结果。

###### 其他

- [How to generate a QR code with Stable Diffusion](https://stable-diffusion-art.com/qr-code/) by [Andrew](https://stable-diffusion-art.com/author/andrewon2/)
- [How to Create QR Code Art using Stable Diffusion](https://ihsavru.medium.com/how-to-create-qr-code-art-using-stable-diffusion-58c5e7e55fcb) by [Urvashi](https://ihsavru.medium.com/)
- [如何制作一个漂亮的二维码](https://mp.weixin.qq.com/s/_Oy9I9FqPXhfwN9IUhf6_g) by [nhciao (ciaochaos)](https://github.com/ciaochaos)

### 视频

- [二维码融合技术 2.0](https://www.bilibili.com/video/BV1zF411R7xg/) by [赛博迪克朗](https://space.bilibili.com/339984)

## 生成工具

### AI 二维码生成器

###### 网页

- [QRBTF.AI](https://qrbtf.com/ai) by [nhciao (ciaochaos)](https://github.com/ciaochaos) - Beta 测试中，URL 不可更改。
- [Quick QR Art](https://beta.quickqr.art/generate)
- [QRCode Monster](https://qrcode.monster/) by [Monster labs](https://huggingface.co/monster-labs) - Monster Labs 官方 AI 二维码生成器。
- [Artistic AI QR Code Generator](https://openart.ai/apps/ai_qrcode)

###### Discord 机器人

- [QRBTF Bot](https://discord.gg/V9CNuqYfte)
- [Quick QR Art Bot](https://top.gg/bot/1117660105962438706)

### 二维码编辑工具

###### AI 二维码编辑工具

- [Anthony Fu's QR Toolkit](https://qrcode.antfu.me/) by [Anthony Fu](https://antfu.me/) - 专为 AI 二维码设计，具备强大的定制设计能力，更新频率较高。
- [Quick QR Art](https://quickqr.art/)

###### 经典二维码编辑工具

- [QRBTF Classic](https://classic.qrbtf.com/) by [nhciao (ciaochaos)](https://github.com/ciaochaos) - 具备丰富的参数化样式、基于 SVG 的二维码生成能力。

## Stable Diffusion 模型与扩展

### ControlNet 模型

###### 精选

- [QR Code Monster v2 (CivitAI)](https://civitai.com/models/111006?modelVersionId=122143) by [Monster labs](https://huggingface.co/monster-labs) - 相比 QR Code Monster V1，提升了二维码可被成功扫描的概率。
- [QR Code Monster v1 (CivitAI)](https://civitai.com/models/111006?modelVersionId=119698) by [Monster labs](https://huggingface.co/monster-labs) - 目前使用量最大、效果相对更好的 AI 二维码 ControlNet 模型。
- [QR Code Monster v1 (Hugging Face)](https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster) by [Monster labs](https://huggingface.co/monster-labs)
- [IoC Lab ControlNet Brightness Model (Hugging Face)](https://huggingface.co/ioclab/ioc-controlnet/tree/main/models) by [IoC Lab](https://huggingface.co/ioclab) - 经常作为辅助 ControlNet 模型来提高局部对比度。

###### 其他

- [QR Pattern (CivitAI)](https://civitai.com/models/90940/controlnet-qr-pattern-qr-codes) by [Nacholmo](https://civitai.com/user/Nacholmo)
- [QR Code Conditioned ControlNet (Hugging Face)](https://huggingface.co/DionTimmer/controlnet_qrcode-control_v1p_sd15) by [Dion Timmer](https://huggingface.co/DionTimmer)
- [Tile (Hugging Face)](https://huggingface.co/lllyasviel/ControlNet-v1-1/blob/main/control_v11f1e_sd15_tile.pth) by [Kakigōri Maker](https://github.com/Mikubill)

### 扩展

- [sd-webui-controlnet](https://github.com/Mikubill/sd-webui-controlnet) by [Kakigōri Maker](https://github.com/Mikubill) - ControlNet 和其他基于注入的 Stable Diffusion WebUI 扩展。
- [sd-webui-qrcode-toolkit](https://github.com/antfu/sd-webui-qrcode-toolkit) by [Anthony Fu](https://antfu.me/) - Stable Diffusion WebUI 的扩展，集成网页版 Anthony Fu's QR Toolkit，以便于轻松发送图像。

## 社区

- [QRBTF’s Discord server](https://discord.gg/V9CNuqYfte) by [nhciao (ciaochaos)](https://github.com/ciaochaos)
- [Anthony’s Discord server](https://chat.antfu.me/) by [Anthony Fu](https://antfu.me/)
- [Quick QR Art Discord server](https://discord.com/invite/quickqrart)

## 协议

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
