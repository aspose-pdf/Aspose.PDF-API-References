---
title: "LaTeXSaveOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "导出为 TeX 格式的保存选项。"
type: docs
weight: 800
url: /zh/python-net/aspose.pdf/latexsaveoptions/
---

## LaTeXSaveOptions class

导出为 TeX 格式的保存选项。

LaTeXSaveOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| LaTeXSaveOptions() | 初始化 LaTeXSaveOptions 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| warning_handler | None |
| save_format | None |
| close_response | None |
| extract_ocr_sublayer_only | 此属性启用了提取图像或文本的功能 <br/>            用于带有 OCR 子层的 PDF 文档。 |
| try_merge_adjacent_same_background_images | 有时 PDF 包含背景图像（页面或表格单元格的）<br/>              这些图像由多个相同的平铺背景图像相邻放置构成。<br/>              在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会生成<br/>              背景图像各部分之间可见的边界，<br/>              因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。<br/>               如果导出的文档看起来在相同背景图像的各部分之间出现了可见的边界，请尝试使用此设置来消除<br/>              这种不需要的效果。 <br/>                注意！此质量优化通常会显著减慢转换速度，<br/>              因此，请仅在确实必要时使用此选项。 |
| out_directory_path | 属性用于 |
| pages_count | 返回转换后的页数。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| add_font_encs(font_encs) | 向字体编码列表添加字体编码 |
| clear_font_encs() | 清除字体编码列表 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

