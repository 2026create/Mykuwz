# 乡村英语小老师 📚

一个为乡村小学生（3-6年级）设计的英语学习聊天界面，基于阿里云百炼智能体应用。

## 功能

- 📖 **背单词** - 自然拼读法、联想记忆法教记单词
- ✏️ **听写单词** - 互动式听写测试
- 🌍 **文化小课堂** - 了解英语国家的有趣文化
- 💬 **自由提问** - 随时问任何英语问题

## 本地使用

直接在浏览器中打开 `index.html` 即可使用。

## 部署到 GitHub Pages（免费获取访问链接）

### 第一步：创建 GitHub 仓库

1. 注册/登录 [GitHub](https://github.com)
2. 点击右上角 **+** → **New repository**
3. 仓库名填 `english-teacher`（或任意名字）
4. 选择 **Public**（公开）
5. 勾选 **Add a README file**
6. 点击 **Create repository**

### 第二步：上传 index.html

1. 在仓库页面点击 **Add file** → **Upload files**
2. 将 `index.html` 拖拽到上传区域
3. 点击 **Commit changes**

### 第三步：开启 GitHub Pages

1. 进入仓库页面，点击 **Settings**
2. 左侧菜单找到 **Pages**
3. **Source** 选择 **Deploy from a branch**
4. **Branch** 选择 `main`，文件夹选择 `/ (root)`
5. 点击 **Save**

### 第四步：获取访问链接

等待 1-2 分钟后，刷新 Pages 页面，顶部会显示：

```
https://你的用户名.github.io/english-teacher/
```

这就是你的访问链接，可以在手机和电脑浏览器中打开！

## 技术说明

- 调用阿里云百炼 DashScope API（v1）
- 支持多轮对话（session_id）
- 支持 Markdown 格式渲染
- 内置 CORS 代理回退机制
- 响应式设计，适配手机和电脑

## 安全提醒

> ⚠️ API Key 嵌入在前端代码中，任何访问者都能看到。
> 建议在阿里云百炼后台设置 API Key 的用量限制，防止滥用。
