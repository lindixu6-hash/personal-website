# 个人网站部署指南

## 🌐 如何访问你的网站

### 方式1：本地查看
1. 找到文件：`/Users/xulindi/Downloads/code·代码们/ai pm/website/index.html`
2. 双击用浏览器打开即可

---

## 🚀 部署到GitHub Pages（推荐）

### 第1步：创建GitHub仓库

在GitHub上创建一个新仓库，命名为 `website` 或 `personal-website`

---

### 第2步：上传文件到GitHub

**方法A：通过命令行上传（推荐）**

```bash
cd /Users/xulindi/Downloads/code·代码们/ai pm/website

# 添加远程仓库（替换YOUR_USERNAME为你的GitHub用户名）
git remote add origin https://github.com/YOUR_USERNAME/website.git

# 推送到GitHub
git branch -M main
git push -u origin main
```

**方法B：通过GitHub网页上传**

1. 打开 https://github.com/new
2. 创建一个新仓库（命名为 `website`）
3. 上传 `index.html` 文件

---

### 第3步：启用GitHub Pages

1. 打开你的GitHub仓库页面
2. 点击 **Settings**（设置）
3. 左侧菜单点击 **Pages**
4. 在 **Source** 下，选择：
   - Branch: `main`
   - Folder: `/ (root)`
5. 点击 **Save**

---

### 第4步：等待部署

- GitHub会自动部署你的网站（通常需要1-5分钟）
- 部署完成后，你会看到一个绿色的勾
- 你的网站地址：`https://YOUR_USERNAME.github.io/website/`

---

## 📱 如何使用网站链接

### 在简历中添加链接

在简历的联系方式部分加上：

```markdown
**个人网站**：https://YOUR_USERNAME.github.io/website/
```

或者：

```
🌐 个人网站：lindixu.github.io/website/
```

---

## 🎨 网站内容说明

### 已包含的内容
- ✅ 个人简介和联系方式
- ✅ 核心技能（AI技术、数据分析、语言能力）
- ✅ 项目经历（3个核心项目）
- ✅ 教育背景
- ✅ GitHub链接

### 如何修改内容

1. **修改文字**：
   - 用文本编辑器打开 `index.html`
   - 找到你想修改的文字
   - 修改后保存

2. **修改颜色**：
   - 在 `<style>` 标签中找到颜色代码
   - 例如：`#667eea` 可以改成其他颜色

3. **添加新项目**：
   - 复制一个 `.project-card` 块
   - 修改里面的内容

---

## 💡 提示

### 优点
- ✅ 免费
- ✅ 快速（1-5分钟部署）
- ✅ 专业（看起来很正式）
- ✅ 易分享（直接发链接）
- ✅ 可以随时更新

### 面试官看到网站的好处
- ✅ 体现你的技术能力（会做网站）
- ✅ 体现你的审美（设计好看）
- ✅ 体现你的执行力（说做就做）
- ✅ 方便了解你（比简历更直观）

---

## 🆘 需要帮助？

如果遇到问题，可以：
1. 查看GitHub Pages官方文档
2. 搜索"GitHub Pages 教程"
3. 或者告诉我，我帮你解决！

---

**祝你面试顺利！💪**
