# 🚀 部署指南

## GitHub 上传步骤

### 1. 创建新仓库
1. 访问 https://github.com
2. 登录您的账户
3. 点击右上角的 "+" 号，选择 "New repository"
4. 仓库名称建议：`shenye-materials-website`
5. 描述：`燊业国际新材料 - 专业数码印刷材料供应商网站`
6. 选择 "Public"（公开）或 "Private"（私有）
7. 不要勾选 "Add a README file"（因为我们已经有了）
8. 点击 "Create repository"

### 2. 上传文件
1. 在新建的仓库页面，点击 "uploading an existing file"
2. 将以下文件拖拽到上传区域：
   - `index.html` - 主页面文件
   - `dtf-lion-dance.jpg` - DTF产品图片
   - `README.md` - 项目说明
   - `PROJECT_SUMMARY.md` - 详细文档
   - `DEPLOYMENT_GUIDE.md` - 本部署指南

### 3. 提交更改
1. 在页面底部填写提交信息：
   ```
   完成网站优化：中英文切换、图片清晰化、DTF产品展示
   ```
2. 点击 "Commit changes"

### 4. 启用 GitHub Pages（可选）
1. 在仓库页面，点击 "Settings" 标签
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 下选择 "Deploy from a branch"
4. 选择 "main" 分支和 "/ (root)" 文件夹
5. 点击 "Save"
6. 等待几分钟，您的网站将在以下地址可用：
   ```
   https://您的用户名.github.io/shenye-materials-website
   ```

## 本地测试
1. 下载所有文件到本地文件夹
2. 双击 `index.html` 用浏览器打开
3. 测试所有功能：
   - 中英文切换（点击按钮或按 Ctrl+L）
   - 图片清晰度
   - 响应式设计
   - 悬停效果

## 文件说明
- **index.html**: 主页面，包含所有功能和样式
- **dtf-lion-dance.jpg**: DTF打印膜产品展示图片
- **README.md**: 项目基本说明
- **PROJECT_SUMMARY.md**: 详细的技术文档
- **DEPLOYMENT_GUIDE.md**: 本部署指南

## 注意事项
- 确保所有文件都在同一个文件夹中
- 图片文件名不要更改
- 上传时保持文件结构不变
- 建议使用现代浏览器（Chrome、Firefox、Safari、Edge）

## 技术支持
如有问题，请检查：
1. 文件是否完整上传
2. 图片路径是否正确
3. 浏览器控制台是否有错误信息
