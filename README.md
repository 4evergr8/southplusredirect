# 🌐 SouthPlus 域名统一跳转脚本 简单 有效  

一个简单高效的 **Tampermonkey 用户脚本**，用于自动将多个 SouthPlus 系列分站（魂+、北+、白+、Lv+、夏+、春+、雪+、东+、蓝+ 等）**自动跳转到统一域名**，从而避免频繁登录、解决 Cookie 不通用的问题。

> 🛠 作者：4evergr8  
> 📦 当前版本：v1.0  
> ⚙️ 适用于：Tampermonkey / Violentmonkey / ScriptCat 等用户脚本管理器

---

## ✨ 功能介绍

- ✅ 自动检测并跳转所有 SouthPlus 系列分站域名  
- 🔁 自动跳转到统一主域名（默认：`www.south-plus.net`）  
- 🔐 避免重复登录，解决 Cookie 不通用问题  
- ⚙️ 支持自定义目标主域名（例如：`bbs.south-plus.org`）  
- 💾 自动保存设置，刷新后生效  

---

## 📦 安装方法

### 方法一：从 GreasyFork 安装（推荐） 
[👉 点击这里安装脚本](https://greasyfork.org/zh-CN/scripts/554316-southplus-%E5%8D%97%E5%8A%A0%E5%9F%9F%E5%90%8D%E8%B7%B3%E8%BD%AC-%E7%AE%80%E5%8D%95-%E6%9C%89%E6%95%88)

### 方法二：手动安装
1. 安装脚本管理器：
   - [Tampermonkey (Chrome)](https://tampermonkey.net/?ext=dhdg&browser=chrome)
   - [Tampermonkey (Firefox)](https://tampermonkey.net/?ext=dhdg&browser=firefox)
   - [Violentmonkey](https://violentmonkey.github.io/)
2. 在 Tampermonkey 中**新建一个用户脚本**
3. 打开本项目中的 [`main.js`](./main.js) 文件  
4. **复制全部代码内容**，粘贴到新脚本中  
5. 保存并启用脚本即可  

---

## ⚙️ 自定义主域名

1. 点击浏览器右上角的 **Tampermonkey 图标**  
2. 选择脚本：**SouthPlus 域名统一跳转**  
3. 点击菜单项 **「设置统一域名」**  
4. 输入新的主域名（例如：`bbs.south-plus.org`）  
5. 刷新页面即可生效  

---

## 📜 更新日志

### v1.0（首个正式版本）
- 🎉 初次发布  
- 🧩 实现多域名统一跳转功能  
- 🚫 解决分站 Cookie 不共享、需重复登录的问题  

---

## 🧑‍💻 作者信息

- 作者：**4evergr8**  
- 版本：**1.0**  
- 协议：MIT License  
- 反馈建议：[Issues](../../issues) / [Pull Requests](../../pulls)

---

⭐ 如果这个脚本帮你避免了频繁登录，请点个 Star 支持一下！
