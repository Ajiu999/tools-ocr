## 树洞 OCR 文字识别
一款跨平台的 OCR 小工具

百度网盘：[https://pan.baidu.com/s/1gVVQ58fZ8ori-O7rWKpRPQ](https://pan.baidu.com/s/1gVVQ58fZ8ori-O7rWKpRPQ)
提取码：m6d8 

> - `xxx-with-jre.xx` 是完整版，带运行环境；如果精简版不能正常工作，请下载完整版使用；
> - 文字识别使用了各云平台开发的识别接口，因此需要联网才能正常使用；
> - 本程序使用 JavaFX 开发，使用前请务必安装 **Java8** 运行环境（完整版无需安装 Java8）。

![截图](http://img.luooqi.com/FqzQ_arDyqsYOXcRoFNQ_Hezyoqo)

![识别结果](http://img.luooqi.com/FrQngY0WsMZP-f6NBze14n0SSKkB)

## 程序使用
### 启动截图
- 方法一：在程序主界面点击截图按钮；
- 方法二：点击截图快捷键 F4。

### 圈选区域
进入截图界面后，按下鼠标左键，然后拖动即可圈选所要截取的区域；
圈选结束后，可以对圈选的区域进行微调：
- 使用 **方向键**，可以对所选区域的右边界和上边界进行微调；
- 使用 **Shift+方向键**，可以对所选区域的左边界和下边界进行微调；
- 使用 **Ctrl+A**，可以全选整个屏幕。

### 确定圈选
圈选完成后，点击 `Enter` 或者 `Space` 键，或者鼠标左键双击即可确认圈选；确认圈选后，会自动对所选区域进行 OCR 文字识别。

## 注意事项
### MAC权限设置
由于监控了截图快捷键，因此MAC需要开启相应的权限，请见下图：

![MAC权限设置](http://img.luooqi.com/Fo31NZQIhPNF6m7gOorRGDuKvaZ_)

## TODO
- [x] 图片文字识别
  - [x] 识别结果文本对齐（暂未实现多分栏）
  - [x] 全屏模式下截图
  - [x] 添加正在识别动画
- [ ] 文本翻译
- [ ] 公式识别
- [ ] 表格识别
- [ ] 软件设置

