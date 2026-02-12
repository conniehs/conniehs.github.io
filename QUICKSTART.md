# 🚀 快速开始指南

## 立即使用（本地测试）

### 方式1: 直接打开
1. 双击 `index.html` 文件
2. 文件将在默认浏览器中打开
3. 开始使用！

### 方式2: 使用Live Server（推荐）
1. 如果你使用VS Code，安装"Live Server"扩展
2. 右键点击 `index.html`
3. 选择"Open with Live Server"
4. 自动刷新，开发更方便

## 📝 第一次使用教程

### Step 1: 准备对话脚本
使用提供的 `example-script.txt` 或创建自己的脚本：

```
Student A: Hello! How are you?
Student B: I'm fine, thank you!
```

### Step 2: 上传脚本
1. 点击首页的 **"Start New Conversation"** 按钮
2. 填写表单：
   - **Script Title**: "My First Practice"
   - **Difficulty**: Beginner
   - **Speaker Roles**: "Student A, Student B"
3. 选择上传方式：
   - **上传文件**: 点击上传区，选择 `example-script.txt`
   - **或粘贴文本**: 直接复制粘贴对话内容
4. 点击 **"Save Script & Continue"**

### Step 3: 允许麦克风权限
- 浏览器会弹出麦克风权限请求
- 点击 **"允许"** 或 **"Allow"**
- 看到 "Ready to record!" 消息

### Step 4: 开始录音
1. 点击大型 **麦克风按钮**
2. 开始说话，朗读脚本内容
3. 观察波形动画和计时器
4. 完成后再次点击按钮停止

### Step 5: 播放回听
1. 点击 **播放按钮** ▶️ 听回放
2. 使用 **停止按钮** ⏹️ 重置
3. 拖动进度条跳转

### Step 6: 分析发音
1. 点击 **"Analyze Pronunciation"** 按钮
2. 等待分析完成（5-10秒）
3. 查看结果：
   - Student A 的分数
   - Student B 的分数
   - 综合得分
   - 错误单词列表

### Step 7: 听正确发音
1. 在错误单词列表中
2. **点击任意单词**
3. 听取正确的英式发音
4. 重复练习

### Step 8: 查看历史记录
1. 点击 **"View My Recordings"**
2. 查看所有练习历史
3. 比较不同时期的进步

## 🎯 使用技巧

### 最佳实践
- ✅ 在安静的环境中录音
- ✅ 使用耳机以获得更好的音质
- ✅ 清晰缓慢地说话
- ✅ 每次练习完整的对话

### 录音建议
- 📱 手机：确保麦克风权限已授予
- 💻 电脑：使用内置或外接麦克风
- 🎧 耳麦：获得最佳音质
- 🔇 静音：避免背景噪音

### 浏览器选择
推荐使用：
- ✅ **Google Chrome** (最佳支持)
- ✅ **Microsoft Edge** (最佳支持)
- ⚠️ Safari (部分功能可能受限)
- ⚠️ Firefox (语音识别可能不可用)

## 🎬 示例对话脚本

### 初学者 (Beginner)
```
Student A: Good morning!
Student B: Good morning! How are you?
Student A: I'm fine, thank you. And you?
Student B: I'm very well, thanks.
```

### 中级 (Intermediate)
```
Student A: Have you finished your homework?
Student B: Yes, I completed it last night. It was challenging.
Student A: I agree. The math problems were difficult.
Student B: Would you like to study together?
```

### 高级 (Advanced)
```
Student A: What do you think about climate change?
Student B: It's a serious issue that requires immediate action.
Student A: I completely agree. We should reduce our carbon footprint.
Student B: Absolutely. Small changes can make a big difference.
```

## ⚙️ 故障排除

### 问题1: 麦克风不工作
**原因**: 浏览器权限未授予
**解决**: 
- 检查浏览器地址栏的麦克风图标
- 点击图标，选择"允许"
- 刷新页面重试

### 问题2: 语音识别不准确
**原因**: 环境噪音、口音、网络
**解决**:
- 在安静环境录音
- 说话清晰缓慢
- 使用Chrome或Edge浏览器
- 多次练习提高准确度

### 问题3: 无法听到TTS发音
**原因**: 浏览器语音库未加载
**解决**:
- 等待几秒后重试
- 刷新页面
- 检查系统音量

### 问题4: 录音无法下载
**原因**: 浏览器安全限制
**解决**:
- 确认已允许下载权限
- 检查浏览器的下载设置
- 尝试不同浏览器

## 📊 数据存储说明

### 本地存储
- 所有数据保存在浏览器的 `localStorage`
- 数据不会上传到任何服务器
- 清除浏览器数据会删除所有记录

### 存储内容
- ✅ 脚本信息
- ✅ 录音元数据（时长、分数）
- ❌ 录音音频文件（无法存储到localStorage）

### 数据导出
- 点击"Download"按钮下载录音文件
- 保存到本地磁盘永久保存

## 🎓 教学建议

### 课堂使用
1. **课前准备**: 准备对话脚本
2. **分组练习**: 2人一组录音
3. **立即反馈**: 查看分析结果
4. **针对改进**: 重点练习错误单词
5. **进度追踪**: 记录每次分数

### 自主学习
1. 每天练习10-15分钟
2. 选择不同难度的脚本
3. 重复练习直到高分
4. 记录进步过程

### 评估方式
- 观察分数提升趋势
- 检查错误单词减少情况
- 鼓励持续练习

## 💡 高级用法

### 自定义脚本创作
1. 根据教学目标编写对话
2. 包含目标词汇和语法
3. 控制难度和长度
4. 提供情景背景

### 批量练习
1. 准备多个脚本文件
2. 按顺序练习
3. 比较不同主题的表现
4. 建立个人档案

## 📞 技术支持

### 获取帮助
- 查看 `README.md` 了解项目概况
- 阅读 `FEATURES.md` 了解详细功能
- 参考 `DEPLOYMENT.md` 部署到GitHub

### 报告问题
- 描述具体问题
- 提供浏览器版本
- 截图错误信息

## 🎉 开始使用！

现在你已经了解了所有内容，开始你的发音练习之旅吧！

1. 打开 `index.html`
2. 点击 "Start New Conversation"
3. 开始录音练习！

**祝你学习愉快！** 🚀📚✨
