# 🚀 GitHub部署指南

## 方法1: 通过GitHub网页界面上传

1. **登录GitHub**
   - 访问 https://github.com
   - 登录你的账号

2. **创建新仓库**
   - 点击右上角的 "+" 按钮
   - 选择 "New repository"
   - 仓库名称: `roleplayconvo` (或你喜欢的名字)
   - 选择 "Public" (公开)
   - 不要勾选 "Initialize with README" (因为我们已经有了)
   - 点击 "Create repository"

3. **上传文件**
   - 在新创建的仓库页面，点击 "uploading an existing file"
   - 将以下文件拖拽到上传区域：
     - `index.html`
     - `README.md`
     - `example-script.txt`
     - `.gitignore`
   - 填写commit信息: "Initial commit: RolePlayConvo platform"
   - 点击 "Commit changes"

4. **启用GitHub Pages**
   - 进入仓库的 "Settings" 标签
   - 在左侧菜单找到 "Pages"
   - Source选择 "Deploy from a branch"
   - Branch选择 "main" 或 "master"
   - Folder选择 "/ (root)"
   - 点击 "Save"
   - 等待几分钟后，页面会显示网站地址

## 方法2: 使用Git命令行 (推荐)

### 前置条件
在代码沙箱中，首先需要设置GitHub授权：
- 点击界面上的 **#github** 标签
- 完成GitHub授权流程
- 返回后等待授权完成

### 推送命令

```bash
cd /home/user/webapp

# 添加远程仓库 (替换YOUR_USERNAME和YOUR_REPO)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# 推送到GitHub
git push -u origin main
```

### 如果遇到main/master分支问题

```bash
# 检查当前分支名
git branch

# 如果是master，重命名为main
git branch -M main

# 推送
git push -u origin main
```

## 方法3: 下载ZIP后手动上传

1. **下载项目文件**
   - 从沙箱下载以下文件到本地
   - 或者使用浏览器保存 `index.html`

2. **上传到GitHub**
   - 按照方法1的步骤创建仓库
   - 使用 "Add file" > "Upload files" 上传所有文件

## 🌐 访问你的网站

部署到GitHub Pages后，你的网站将在以下地址可用：

```
https://YOUR_USERNAME.github.io/YOUR_REPO/
```

例如：
- 用户名: `john`
- 仓库名: `roleplayconvo`
- 网站地址: `https://john.github.io/roleplayconvo/`

## ✅ 验证部署

1. 访问GitHub Pages提供的URL
2. 检查页面是否正常加载
3. 测试以下功能：
   - 上传脚本
   - 允许麦克风权限
   - 录音功能
   - 播放功能
   - 发音分析
   - 录音库

## 🔧 故障排除

### 问题1: GitHub Pages未启用
**解决方案**: 进入 Settings > Pages，确保选择了正确的分支

### 问题2: 404错误
**解决方案**: 
- 确保 `index.html` 在仓库根目录
- 等待3-5分钟让GitHub Pages构建完成
- 清除浏览器缓存后重试

### 问题3: 麦克风不工作
**解决方案**: 
- GitHub Pages必须使用HTTPS（自动提供）
- 检查浏览器的麦克风权限设置
- 某些浏览器可能需要用户手动允许

### 问题4: 语音识别不工作
**解决方案**:
- 使用Chrome或Edge浏览器（最佳支持）
- 确保在安静的环境中测试
- 某些浏览器可能不支持Web Speech API

## 📱 移动设备测试

在手机上测试你的网站：
1. 使用手机浏览器访问GitHub Pages URL
2. 允许麦克风权限
3. 测试触摸交互
4. 检查响应式布局

## 🎉 完成！

现在你的RolePlayConvo平台已经上线，可以分享给学生使用了！

---

**提示**: 如果需要更新网站，只需：
1. 修改本地文件
2. 使用 `git add .` 和 `git commit -m "更新说明"`
3. 使用 `git push` 推送到GitHub
4. GitHub Pages会自动更新
