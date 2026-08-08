# Agent++




> 基于 Codex 工作流开发的 Windows AI 编码工作台，把真实项目理解、文件修改、命令执行、结果检查和对话协作放在同一个桌面流程里。




Agent++ 面向需要“能做事”的 AI 编码场景：不只是聊天问答，而是围绕真实项目持续完成任务。它通过 TKEN 账户服务连接已授权 GPT，同时开放兼容接口，让国产模型、自有模型和外部渠道都能进入同一个模型选择器。




## 核心优势




- **开放外接模型接口**：在“设置 -> 个人 -> 模型连接”中填写兼容服务的 Base URL 和 API Key，获取模型列表，筛选、测试所选模型后保存。
- **多渠道共存**：MiniMax、阿里云、百度千帆以及其他 OpenAI 兼容渠道可以同时配置；外接模型与内置模型统一选择。
- **国产模型支持**：可使用 DeepSeek、GLM、通义千问、MiniMax、百度文心/千帆等服务目录中的可用模型。
- **中国大陆网络环境下使用已授权 GPT**：通过 TKEN 账户服务使用服务端已开放的 GPT 模型，用户不需要自行配置科学上网。实际可用性取决于账户授权、服务状态、网络和上游政策，不承诺绕过第三方地区限制。
- **Codex 式项目执行**：理解项目上下文、修改文件、运行命令、检查结果，并在过程中保留可追踪的任务状态。
- **文本、图片和语音工作流**：支持文字对话、图片理解/翻译和语音转写等场景，具体能力以所选模型和渠道声明为准。
- **微信远程协作与插件工作区**：在支持的账户和客户端能力范围内查看任务状态，并接入浏览器、设计、文档和开发工具。
- **可靠更新与数据边界**：安装包经过签名和 SHA-256 校验；外接 API Key 不写入 TKEN 账户凭据或发布包。




## V133.0.0


> 客户端品牌名：Agent++。GitHub Release 安装包使用 Agent++ 文件名；官方下载镜像保留兼容旧技术路径。




- [GitHub Release](https://github.com/449323370/agent-plus-plus/releases/tag/v133.0.0)
- [官方下载镜像](https://download.tken.shop/agentpp/agentpp-V133-Final-Windows-Setup-20260806.exe)
- [官方下载别名（版本化）](https://download.tken.shop/agentpp/agent++.exe?v=133.0.0)
- GitHub Release 文件：agent++-V133-Final-Windows-Setup-20260806.exe
- 大小：645,080,788 bytes
- SHA-256：d0c367b8e861079d99050045bf1b5d47baeed2187113f2894c03bf06506ec292




下载后建议先核对 SHA-256，再运行安装程序。




## 界面预览




![模型连接：同时配置多个外部渠道](https://github.com/449323370/agent-plus-plus/releases/download/v133.0.0/model-connections.png)




![模型选择器：内置与外接模型统一选择](https://github.com/449323370/agent-plus-plus/releases/download/v133.0.0/model-picker.png)




![国产模型与多模型切换](https://github.com/449323370/agent-plus-plus/releases/download/v133.0.0/model-catalog.png)




## 首次使用




1. 安装并启动 Agent++。
2. 首次使用选择“领取免费体验”，已有账户选择“连接已有密钥”。
3. 在“分组与密钥”中保存已开通服务的 Key，选择模型并发送一条短消息。
4. 如需外部模型，进入“设置 -> 个人 -> 模型连接”，添加渠道、获取模型、测试所选模型，再保存。
5. 按需完成微信连接或安装插件。




完整教程：[Agent++ 使用帮助](https://www.tken.shop/agentpp-help)




## 安全边界




不要分享 Key、Cookie、验证码或支付信息。只把 API Key 输入到你信任的渠道；模型、能力、价格、余额和微信远程能力以当前账户授权与服务目录为准。




本仓库用于发布 Windows 安装包和版本说明，核心客户端源码不包含在仓库中。问题请提交到 [Issues](https://github.com/449323370/agent-plus-plus/issues)，只提供版本号、复现步骤和不含隐私的错误现象。
