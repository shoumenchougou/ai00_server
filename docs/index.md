---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Ai00 server"
  text: "Just for RWKV"
  tagline: 支持 Vulkan/Dx12/openGL 的并发推理服务器
  actions:
    - theme: brand
      text: 快速上手！
      link: /markdown-examples
    - theme: alt
      text: 下载安装  
      link: https://github.com/Ai00-X/ai00_server/releases

  image:
    src: /logo.gif
    alt: AI00 Server
features:
  - icon: ❤
    title: 容易使用
    details: 
      -  Ai00 server 支持 Vulkan/Dx12/openGL 作为推理后端，支持 INT8/NF4 量化，所以可以在绝大部分的个人电脑上快速的运行！支持大部分 NVIDIA、AMD、Inter 的显卡，包括集成显卡。7B 的 RWKV 模型 NF4 量化时仅占用 5.5G 显存。
  - icon: ✨
    title: 免费开源
    details:
      - Ai00 server 使用 MIT/Apache2.0 协议，免费开源商用。您可以把 Ai00 server 集成在您的系统或软件中。社区保持活跃开发中！
  - icon: 👽
    title: 能力出众
    details: 兼容 ChatGPT 的 API 接口，使用强大的 RWKV 模型。RWKV 是将会吊打所有基于 Transformer 的模型的，在端侧 LLM 部署的王者模型。并且正在快速迭代中，功能和性能越来越强悍。
---

