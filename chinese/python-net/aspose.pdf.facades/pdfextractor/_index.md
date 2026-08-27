---
title: "PdfExtractor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "用于从 PDF 文档中提取图像和文本的类。"
type: docs
weight: 210
url: /zh/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

用于从 PDF 文档中提取图像和文本的类。

PdfExtractor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfExtractor() | 初始化新的 [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) 对象。 |
| PdfExtractor(document) | 初始化 PdfExtractor 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| start_page | 获取或设置将在其执行提取操作的页面范围的起始页。 |
| end_page | 获取或设置将在其执行提取操作的页面范围的结束页。 |
| extract_text_mode | 设置提取文本结果的模式。 |
| text_search_options | 获取或设置文本搜索选项。 |
| extract_image_mode | 设置提取图像过程的模式。 |
| is_bidi | 当文本包含希伯来或阿拉伯符号时为 true。必须特别考虑这种情况，因为<br/>            字符串函数会改变其行为，并从右向左处理文本（数字除外 <br/>            以及其他非文本字符）。 |
| resolution | 设置或获取提取图像的分辨率。<br/>            默认值为 150。<br/>            分辨率更高的图像更清晰。<br/>            但是提高分辨率会导致提取图像所需的时间和内存增加。<br/>            通常，要获得清晰的图像，只需将分辨率设置为 150 或 300。 |
| password | 获取或设置输入文件的密码。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(input_file) | 绑定输入 PDF 文件。 |
| bind_pdf(input_stream) | 从流绑定 PDF 文档。 |
| bind_pdf(src_doc) | 初始化外观。 |
| extract_text() | 使用 Unicode 编码从 PDF 文档中提取文本。 |
| extract_text(encoding) | 使用指定编码从 PDF 文档中提取文本。 |
| get_text(output_file) | 将文本保存到文件。另请参见:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | 将文本保存到流。另请参见:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | 将文本保存到流。另请参见:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | 检索 PDF 文档中的下一张图像。注意：在使用此方法之前必须调用 ExtractImage。 |
| get_next_image(output_file, format) | 检索 PDF 文档中具有给定图像格式的下一张图像。注意：在使用此方法之前必须调用 ExtractImage。 |
| get_next_image(output_stream, format) | 检索 PDF 文件中的下一张图像，并以给定的图像格式存储到流中。 |
| get_next_image(output_stream) | 检索 PDF 文件中的下一张图像，并以给定的图像格式存储到流中。 |
| extract_attachment() | 从 PDF 文档中提取附件。 |
| extract_attachment(attachment_file_name) | 按附件名称将附件提取到 PDF 文件。 |
| get_next_page_text(output_file) | 将单页文本保存到文件。 |
| get_next_page_text(output_stream) | 将单页文本保存到流。 |
| close() | 释放与外观绑定的 Aspose.Pdf.Document。 |
| extract_image() | 从 PDF 文件中提取图像。 |
| has_next_image() | 检查 PDF 文档中是否还有可访问的图像。注意：在使用此方法之前必须调用 ExtractImage。 |
| get_attach_names() | 返回 PDF 文件中附件的列表。注意：在使用此方法之前必须调用 ExtractAttachments。 |
| get_attachment(output_path) | 将附件存储到文件中。 |
| has_next_page_text() | 指示是否可以获取更多文本。 |
| get_attachment_info() | 获取附件列表。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

