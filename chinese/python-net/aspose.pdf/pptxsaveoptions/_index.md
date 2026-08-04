---
title: "PptxSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "导出为 SVG 格式的保存选项。"
type: docs
weight: 1290
url: /zh/python-net/aspose.pdf/pptxsaveoptions/
---

## PptxSaveOptions class

导出为 SVG 格式的保存选项。

PptxSaveOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PptxSaveOptions() | 初始化 PptxSaveOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | 回调用于处理生成的任何警告。 <br/>            WarningHandler 返回 ReturnAction 枚举项，指定为 Continue 或 Abort。 <br/>            Continue 是默认操作，保存操作将继续，但用户也可以返回 Abort，此时保存操作应停止。 |
| save_format | 数据保存的格式。 |
| close_response | 获取或设置布尔值，指示在文档保存到响应后是否关闭 Response 对象。 |
| extract_ocr_sublayer_only | 此属性启用了提取图像或文本的功能 <br/>            用于带有 OCR 子层的 PDF 文档。 |
| try_merge_adjacent_same_background_images | 有时 PDF 包含背景图像（页面或表格单元格的）<br/>              这些图像由多个相同的平铺背景图像相邻放置构成。<br/>              在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会生成<br/>              背景图像各部分之间可见的边界，<br/>              因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。<br/>               如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置来消除<br/>              这种不需要的效果。 <br/>                注意！此质量优化通常会显著减慢转换速度，<br/>              因此，请仅在确实必要时使用此选项。 |
| slides_as_images | 如果设置为 true，则所有内容都被识别为图像（每页一个） |
| image_resolution | 获取或设置图像分辨率（dpi）。默认值为 192 dpi。 |
| separate_images | 如果设置为 true，则图像会与所有其他图形分离 |
| optimize_text_boxes | 切换文本列识别 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

