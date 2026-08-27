---
title: "PdfFileMend"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个用于在现有 PDF 文档页面上添加文本和图像的类。"
type: docs
weight: 280
url: /zh/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

表示一个用于在现有 PDF 文档页面上添加文本和图像的类。

PdfFileMend 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileMend() | 构造函数。 |
| PdfFileMend(input_file_name, output_file_name) | 初始化 PdfFileMend 类的新实例 |
| PdfFileMend(input_stream, output_stream) | 初始化 PdfFileMend 类的新实例 |
| PdfFileMend(document) | 初始化 PdfFileMend 类的新实例 |
| PdfFileMend(document, output_file_name) | 初始化 PdfFileMend 类的新实例 |
| PdfFileMend(document, dest_stream) | 初始化 PdfFileMend 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| input_stream | 设置输入流。 |
| output_stream | 设置输出流。 |
| input_file | 设置输入文件。 |
| output_file | 设置输出文件。 |
| wrap_mode | 设置或获取换行算法。参见 WordWrapMode 和 IsWordWrap。 |
| text_positioning_mode | 设置或获取文本定位策略。 [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            默认模式为 Legacy。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将 PDF 文档保存到指定文件。 |
| save(dest_stream) | 将 PDF 文档保存到指定流。 |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 在指定坐标处向 PDF 文档的指定多个页面添加图像。 |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 在指定坐标处向 PDF 文档的指定多个页面添加图像。 |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 在指定坐标处向 PDF 文档的指定页面添加图像。 |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 在指定坐标处向 PDF 文档的指定多个页面添加图像。 |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 在指定坐标处向 PDF 文档的指定多个页面添加图像。 |
| add_text(text, page_num, lower_left_x, lower_left_y) | 未实现。 |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 未实现。 |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 未实现。 |
| close() | 关闭 PdfFileMend 对象。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

