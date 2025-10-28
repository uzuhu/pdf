# PDF转图片工具

一个简单易用的在线PDF转图片工具，支持高清晰度转换，所有处理均在浏览器中完成，保护您的文件安全。

## 功能特点

- **高质量转换**：支持最高600 DPI的分辨率，确保转换后的图片清晰锐利
- **安全可靠**：所有文件处理均在浏览器中完成，不会上传到服务器，保护您的隐私
- **快速高效**：使用Web Workers进行后台处理，不阻塞主线程，转换速度快
- **批量下载**：支持将多张图片打包成ZIP文件，方便批量下载和分享
- **PDF预览**：上传后可预览PDF内容，方便确认转换前的文件
- **响应式设计**：适配各种设备屏幕，在电脑、平板和手机上均可使用

## 技术栈

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript
- PDF.js (用于PDF处理)
- JSZip (用于打包下载)
- FileSaver.js (用于文件下载)

## 如何使用

1. 打开[PDF转图片工具](https://yourusername.github.io/pdf-to-image-converter/)
2. 拖放PDF文件到上传区域，或点击"浏览文件"按钮选择文件
3. 预览PDF文件（可选）
4. 设置转换选项（图片格式、分辨率、页面范围）
5. 点击"开始转换"按钮
6. 转换完成后，下载单张图片或打包下载所有图片

## 如何部署到GitHub Pages

这个项目可以直接部署到GitHub Pages，因为它是一个纯前端应用，没有服务器端代码。

### 部署步骤

1. **创建GitHub仓库**
   - 在GitHub上创建一个新的仓库，命名为`pdf-to-image-converter`（或任何您喜欢的名称）

2. **克隆仓库到本地**
   ```bash
   git clone https://github.com/yourusername/pdf-to-image-converter.git
   cd pdf-to-image-converter
   ```

3. **添加项目文件**
   - 将`index.html`文件复制到仓库目录中

4. **提交并推送代码**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

5. **启用GitHub Pages**
   - 在GitHub仓库页面，点击"Settings"选项卡
   - 滚动到"GitHub Pages"部分
   - 在"Source"下拉菜单中，选择"main"分支
   - 点击"Save"按钮
   - 等待几分钟，您的网站将在`https://yourusername.github.io/pdf-to-image-converter/`上可用

## 本地运行

如果您想在本地运行这个项目，只需在浏览器中打开`index.html`文件即可，无需任何额外的依赖或服务器。

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 注意事项

- 由于浏览器内存限制，建议转换不超过50MB的PDF文件
- 不支持转换加密或受保护的PDF文件
- 转换时间取决于PDF文件的大小和页数

## 许可证

MIT License
