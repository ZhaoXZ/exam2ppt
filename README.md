# exam2ppt：Word 试卷转讲评 PPT

把包含参考答案与解析的 Word 试卷，转换为可编辑的讲评课件。题目、图片、答案和解析在浏览器中处理，减少老师重复整理材料的工作。

**[在线使用](https://zhaoxz.github.io/exam2ppt/)** · [问题反馈](https://github.com/ZhaoXZ/exam2ppt/issues)

## 能做什么

- 读取支持的 `.docx` 与旧版 `.doc` 试卷。
- 识别题目、选项、材料、图片与参考答案。
- 生成答案高亮的讲评页，将解析放入演讲者备注。
- 根据内容选择支持的版式，必要时自动分页。
- 导出 `.pptx`，供老师检查和继续编辑。

## 使用方法

1. 打开[网页工具](https://zhaoxz.github.io/exam2ppt/)。
2. 选择包含参考答案与解析的 Word 试卷。
3. 检查识别结果，选择页面提供的输出设置。
4. 生成课件，在 PowerPoint 中检查答案和排版后使用。

试卷在浏览器本地转换，不上传处理。首次打开在线网页需要联网；保存完整的单文件网页后，可在本地离线使用。

## 为什么做这个工具

老师讲评试卷前，常需要将同一份材料重新整理为课件。我围绕这项具体工作设计工具，并根据中学地理教研组的试用反馈迭代。

产品重点是简短、可完成的操作路径：打开一个页面，选择试卷，得到可编辑的课件。

## 实现要点

- 自定义旧版 Word 二进制解析，处理文档结构、编号与图片。
- 识别题目和答案关系，支持布局选择与分页兜底。
- 通过 OOXML 调整字体与答案显示效果。

当前公开仓库分发打包后的网页应用，模块化开发源码及本地测试材料暂未放入此仓库。

## 使用限制

- 识别效果受试卷结构和答案格式影响，部分文档需要人工调整。
- 当前工具不提供扫描图片的 OCR 识别。
- 密集表格、特殊格式和复杂图片可能需要在导出后编辑。
- 课堂使用前，请核对答案、解析与版面。

## 反馈问题

请通过 [Issues](https://github.com/ZhaoXZ/exam2ppt/issues) 提供工具版本、预期结果和实际结果。推荐用少量自写的示例题复现解析问题。

## English overview

Convert Word exam papers into editable PowerPoint review slides, with questions, images, highlighted answers and explanations. Document conversion runs locally in the browser. The interface is in Chinese.

[Try the tool](https://zhaoxz.github.io/exam2ppt/). Review the generated answers and layout before classroom use.
