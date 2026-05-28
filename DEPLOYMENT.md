# GitHub Pages 部署说明

## 已完成的步骤

✅ 1. 创建了完整的静态网站文件
   - index.html - 主页，展示4张游戏截图
   - privacy-policy.html - 隐私政策页面（符合Google Play要求）
   - style.css - 响应式样式文件
   - README.md - 项目说明

✅ 2. 代码已推送到GitHub
   - 仓库地址: https://github.com/youyileng/chickenmerge.github.io.git
   - 分支: main

## 接下来需要在GitHub上配置

请按照以下步骤在GitHub上启用GitHub Pages：

### 步骤1: 访问仓库设置
1. 打开浏览器，访问: https://github.com/youyileng/chickenmerge.github.io
2. 点击仓库页面右上角的 **Settings** (设置)

### 步骤2: 配置GitHub Pages
1. 在左侧菜单中找到 **Pages** 选项
2. 在 **Source** (源) 部分:
   - Branch: 选择 **main**
   - Folder: 选择 **/ (root)**
3. 点击 **Save** (保存)

### 步骤3: 等待部署
- GitHub会自动部署网站，通常需要1-3分钟
- 部署完成后，页面顶部会显示网站地址
- 网站地址应该是: **https://youyileng.github.io/chickenmerge.github.io/**

### 步骤4: 验证网站
访问以下页面确认部署成功：
- 主页: https://youyileng.github.io/chickenmerge.github.io/
- 隐私政策: https://youyileng.github.io/chickenmerge.github.io/privacy-policy.html

## 用于Google Play的链接

在Google Play Console中填写以下链接：

**隐私政策URL:**
```
https://youyileng.github.io/chickenmerge.github.io/privacy-policy.html
```

**应用网站URL (可选):**
```
https://youyileng.github.io/chickenmerge.github.io/
```

## 更新网站内容

如果需要更新网站内容：

```bash
# 1. 修改文件后，提交更改
cd D:\ChickenMerge\Github_Pages
git add .
git commit -m "更新说明"

# 2. 推送到GitHub
git push origin main

# 3. GitHub会自动重新部署（1-3分钟）
```

## 自定义域名（可选）

如果你有自己的域名，可以在GitHub Pages设置中配置：
1. 在 Settings > Pages 中找到 **Custom domain**
2. 输入你的域名（例如: www.chickenmerge.com）
3. 在域名DNS设置中添加CNAME记录指向: youyileng.github.io

## 注意事项

- ✅ 网站已包含完整的隐私政策，符合Google Play要求
- ✅ 响应式设计，支持手机和电脑访问
- ✅ 展示了4张游戏截图
- ⚠️ 记得在Google Play Console中填写正确的隐私政策URL
- ⚠️ 如果需要修改联系邮箱，请编辑 index.html 和 privacy-policy.html 中的 support@chickenmerge.com

## 故障排除

**问题1: 网站显示404**
- 确认GitHub Pages已在Settings > Pages中启用
- 确认选择了正确的分支(main)和文件夹(root)
- 等待3-5分钟让GitHub完成部署

**问题2: 图片不显示**
- 确认图片文件已正确推送到GitHub
- 检查图片文件名是否正确（区分大小写）

**问题3: 样式不正常**
- 清除浏览器缓存后重新访问
- 确认style.css文件已正确推送

## 联系支持

如有问题，请查看GitHub Pages文档:
https://docs.github.com/en/pages
