# Ech0 - 开源、自托管、专注思想流动的轻量级发布平台



Ech0 是一款专为轻量级分享而设计的开源自托管平台，支持快速发布与分享你的想法、文字与链接。简单直观的操作界面，轻松管理你的内容，让分享变得更加自由，确保数据完全掌控，随时随地与世界连接。

![screenshot](https://github.com/user-attachments/assets/0c2d36eb-114d-426c-beaa-690d92a5b2cd)


## 核心优势

☁️ **原子级轻量**：内存占用仅**约11MB**，整个镜像大小不到**45MB**，单SQLite文件存储架构  
🚀 **极速部署**：无需配置，从安装到使用只需1条命令  
✍️ **零干扰写作**：纯净的在线Markdown编辑器，**所见即所得**  
📦 **数据主权**：所有内容存储于本地SQLite文件，支持RSS订阅  
🎉 **永久免费**：MIT协议开源，无追踪/无订阅/无服务依赖  
🌍 **跨端适配**：完美兼容桌面/移动浏览器  

> 📍 首次使用注册的账号会被设置为管理员（目前仅管理员支持发布内容）  
> 🎈 数据存储data下  


# ❓ 常见问题

1. **Ech0是什么？**
Ech0 是一款轻量级的开源自托管平台，专为快速发布与分享个人想法、文字和链接而设计。它提供简洁的界面，支持零干扰的写作体验，所有数据存储于本地，确保用户对内容的完全控制。

2. **Ech0 是免费的吗？**
是的，Ech0 完全免费且开源，遵循 MIT 协议。它没有广告、追踪、订阅或服务依赖。

3. **如何进行备份和恢复数据？**
由于所有内容都存储在本地 SQLite 文件中，您只需备份/opt/ech0/data目录中的文件即可（具体选择部署时的映射路径）。在需要恢复时，直接将备份文件还原即可。

4. **Ech0 支持 RSS 吗？**
是的，Ech0 支持 RSS 订阅，您可以通过 RSS 阅读器订阅您的内容更新。

5. **为什么每次留言只能上传一张图片？**
为了优化性能并减少页面加载时间，Ech0 限制每次留言仅支持上传一张图片。设计之初，Ech0 更侧重于简短的文字内容分享，而不是长篇文章发布。

6. **为什么发布失败，提示联系管理员？**
当前版本设计上，只有管理员可以发布内容。部署后，首个注册的用户会自动被设置为系统管理员，其他用户无法发布内容。

7. **为什么没有明确的权限划分？**
Ech0 旨在保持简洁和轻量，因此在设计时没有复杂的权限系统。我们希望用户能够专注于分享内容，而不是被复杂的权限管理所困扰。为了保持流畅的使用体验，Ech0 尽量精简了功能，避免不必要的复杂性。（因此目前只有管理员与非管理员之分，所以请谨慎分配你的权限）

---
