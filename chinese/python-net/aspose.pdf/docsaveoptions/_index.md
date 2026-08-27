---
title: "DocSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "导出为 Doc 格式的保存选项"
type: docs
weight: 220
url: /zh/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

导出为 Doc 格式的保存选项

DocSaveOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| DocSaveOptions() | 初始化 DocSaveOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调用于处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。 <br/>            Continue 是默认操作，保存操作将继续，但用户也可以返回 Abort，此时保存操作应停止。 |
| save_format | 数据保存的格式。 |
| close_response | 获取或设置布尔值，指示在文档保存到响应后是否关闭 Response 对象。 |
| extract_ocr_sublayer_only | 此属性启用了提取图像或文本的功能 <br/>            用于带有 OCR 子层的 PDF 文档。 |
| try_merge_adjacent_same_background_images | 有时 PDF 包含背景图像（页面或表格单元格的）<br/>              这些图像由多个相同的平铺背景图像相邻放置构成。<br/>              在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会生成<br/>              背景图像各部分之间可见的边界，<br/>              因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。<br/>               如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置来消除<br/>              这种不需要的效果。 <br/>                注意！此质量优化通常会显著减慢转换速度，<br/>              因此，请仅在确实必要时使用此选项。 |
| mode | 识别模式。 |
| relative_horizontal_proximity | 在 PDF 中，单词可能通过内部运算符表示，这些运算符会逐字母或音节独立打印单词<br/>              因此，为了检测单词，有时需要检测实际上是单词的独立字符组<br/>              本设置定义文本元素（字母、音节）之间的空间宽度 <br/>              在源 PDF 的单词识别过程中，这个宽度将被视为单词之间的距离<br/>              （如果字母之间的空白至少达到此宽度，则表示文本元素属于不同的单词）。<br/>              它相对于字体大小进行归一化 - 1.0 表示相当于预期单词字体大小的 100%。<br/>             注意！仅在源 PDF 包含特定罕用字体且无法从字体计算最佳值的情况下使用<br/>             因此，在绝大多数情况下，此参数对结果文档没有任何影响。 |
| max_distance_between_text_lines | 此参数用于将文本行分组为段落。<br/>            确定两个相对文本行之间可以相隔多远。以文本行高度的百分之几百为单位。 |
| recognize_bullets | 开启项目符号识别 |
| add_return_to_line_end | 使用段落或换行符 |
| image_resolution_x | 转换后图像的 X 分辨率。 |
| image_resolution_y | 转换后图像的 Y 分辨率。 |
| format | 输出格式 |
| batch_size | 定义批处理大小，如果批量转换适用于源和目标格式对。<br/>             |
| memory_save_mode_path | 定义在内存保存模式下转换时用于保存<br/>            临时数据的路径（文件名或目录名）。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

