---
title: "PdfFileStamp"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "用于向 PDF 文件添加印章（水印或背景）的类。"
type: docs
weight: 320
url: /zh/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

用于向 PDF 文件添加印章（水印或背景）的类。

PdfFileStamp 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileStamp(input_file, output_file) | 初始化 PdfFileStamp 类的一个新实例 |
| PdfFileStamp(input_stream, output_stream) | 初始化 PdfFileStamp 类的一个新实例 |
| PdfFileStamp(input_file, output_file, keep_security) | 初始化 PdfFileStamp 类的一个新实例 |
| PdfFileStamp(input_stream, output_stream, keep_security) | 初始化 PdfFileStamp 类的一个新实例 |
| PdfFileStamp() | PdfFileStamp 的构造函数。<br/>            输入文件和输出文件可以通过相应的属性指定。 |
| PdfFileStamp(document) | 初始化 PdfFileStamp 类的一个新实例 |
| PdfFileStamp(document, output_file) | 初始化 PdfFileStamp 类的一个新实例 |
| PdfFileStamp(document, output_stream) | 初始化 PdfFileStamp 类的一个新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| optimize_size | 获取或设置优化标志。如果设置此标志，结果文件中相等的资源流将合并为一个 PDF 对象。<br/>            这可以减小结果文件的大小，但可能导致执行速度变慢和更高的内存需求。<br/>            默认值：false。 |
| keep_security | 如果为 true，则保持安全性。（此功能将在后续版本中实现。） |
| input_file | 获取或设置输入文件的名称和路径。 |
| input_stream | 获取或设置输入流。 |
| output_file | 获取或设置输出文件的名称和路径。 |
| output_stream | 获取或设置输出流。 |
| page_number_rotation | 获取或设置页码的旋转角度。旋转角度以度为单位。默认值为 0。 |
| page_height | 获取源文件中第一页的高度。 |
| page_width | 获取输入文件中第一页的宽度。 |
| starting_number | 获取或设置输入文件中第一页的起始编号。后续页面将从该值开始编号。<br/>            例如，如果 StartingNumber 设置为 100，文档页面的编号将为 100、101、102…… |
| numbering_style | 获取或设置页面编号样式。可能的取值：NumeralsArabic、NumeralsRomanUppercase、NumeralsRomanLowercase、LettersAppercase、LettersLowercase |
| stamp_id | 下一个添加的印章的 Stamp ID（包括页眉/页脚/页码）。 |
| POS_BOTTOM_MIDDLE | 底部中间位置。 |
| POS_BOTTOM_RIGHT | 底部右侧位置。 |
| POS_UPPER_RIGHT | 右上位置。 |
| POS_SIDES_RIGHT | 右侧位置。 |
| POS_UPPER_MIDDLE | 上部中间位置。 |
| POS_BOTTOM_LEFT | 左下位置。 |
| POS_SIDES_LEFT | 左侧位置。 |
| POS_UPPER_LEFT | 左上位置。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将结果保存到指定文件中。 |
| save(dest_stream) | 将文档保存到指定流。 |
| add_page_number(format_string) | 将页码添加到文件。页码文本可能包含 # 符号，该符号将被替换为页码数字。<br/>            页码位于页面底部，水平居中。 |
| add_page_number(formatted_text) | 在页面上添加页码。页码可能包含 # 符号，该符号将被替换为页码。<br/>            页码位于页面底部，水平居中。 |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | 在文档的各页添加页码。 |
| add_page_number(format_string, x, y) | 在文档的各页添加页码。 |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | 在文档的各页添加页码。 |
| add_page_number(formatted_text, x, y) | 在文档的各页添加页码。 |
| add_page_number(format_string, position) | 在文档的各页添加页码。 |
| add_page_number(formatted_text, position) | 在文档的各页添加页码。 |
| add_header(formatted_text, top_margin) | 在页面上添加页眉。 |
| add_header(formatted_text, top_margin, left_margin, right_margin) | 在页面上添加页眉。 |
| add_header(image_file, top_margin) | 将图像作为页眉添加到文件的各页。 |
| add_header(image_file, top_margin, left_margin, right_margin) | 将图像作为页眉添加到文件的各页。 |
| add_header(image_stream, top_margin) | 在页面上添加图像作为页眉。 |
| add_header(input_stream, top_margin, left_margin, right_margin) | 在页面上添加图像作为页眉。 |
| add_footer(formatted_text, bottom_margin) | 在文档的页面上添加页脚。 |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | 在文档的页面上添加页脚。 |
| add_footer(image_file, bottom_margin) | 在文档的页面上添加图像作为页脚。 |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | 在文档的页面上添加图像作为页脚。 |
| add_footer(image_stream, bottom_margin) | 在页面上添加图像作为页脚。 |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | 在页面上添加图像作为页脚。 |
| close() | 关闭已打开的文件并保存更改。 <br/>            警告。如果指定了输入或输出流，Close() 方法不会关闭它们。 |
| add_stamp(stamp) | 向文件添加印章。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

