---
title: "PdfConverter"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个类，用于将 pdf 文件的每一页转换为图像，目前支持 BMP、JPEG、PNG 和 TIFF。<br/>            支持的 pdf 内容包括图片、表单和注释。"
type: docs
weight: 200
url: /zh/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

表示一个将 PDF 文件的每页转换为图像的类，目前支持 BMP、JPEG、PNG 和 TIFF。<br/>            支持的 PDF 内容：图片、表单、评论。

PdfConverter 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfConverter() | 初始化新的 [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) 对象。 |
| PdfConverter(document) | 初始化 PdfConverter 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| coordinate_type | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| show_hidden_areas | 获取或设置控制页面上隐藏区域可见性的标志。 |
| rendering_options | 获取或设置渲染选项。 |
| form_presentation_mode | 获取或设置表单呈现模式。 |
| resolution | 获取或设置转换期间的分辨率。分辨率越高，转换速度越慢。默认值为 150。 |
| start_page | 获取或设置要转换的起始位置。最小值为 1。 |
| end_page | 获取或设置要转换的结束位置。 |
| password | 获取或设置文档的 OwnerPassword。 |
| user_password | 获取或设置文档的 UserPassword。 |
| page_count | 获取页数。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(input_file) | 绑定一个 Pdf 文件以进行转换。 |
| bind_pdf(input_stream) | 绑定一个 Pdf 流进行转换。 |
| bind_pdf(src_doc) | 初始化外观。 |
| save_as_tiff(output_file) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, compression_type) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, image_width, image_height) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, page_size) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, page_size, settings) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, image_width, image_height, compression_type) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, image_width, image_height, settings) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_stream) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| save_as_tiff(output_stream, compression_type) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_stream, page_size) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| save_as_tiff(output_stream, page_size, settings) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| save_as_tiff(output_stream, image_width, image_height) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| save_as_tiff(output_stream, image_width, image_height, settings) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| save_as_tiff(output_file, settings) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_file, settings, converter) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 文件中。 |
| save_as_tiff(output_stream, settings) | 将 PDF 文档的每页转换为具有页面尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| save_as_tiff(output_stream, settings, converter) | 将 PDF 文档的每页转换为具有指定尺寸的图像，并将图像保存到单个 TIFF 流中。 |
| save_as_tiff_class_f(output_file, image_width, image_height) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 文件。 |
| save_as_tiff_class_f(output_file, page_size) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 文件。 |
| save_as_tiff_class_f(output_stream, image_width, image_height) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| save_as_tiff_class_f(output_stream, page_size) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| save_as_tiff_class_f(output_file) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 文件。 |
| save_as_tiff_class_f(output_stream) | 将 PDF 文档的每页转换为图像，并将图像保存到单个 TIFF ClassF 流中。 |
| get_next_image(output_file) | 将图像保存到文件，使用默认的图像格式 - jpeg。 |
| get_next_image(output_file, page_size) | 将图像保存到文件，使用给定的页面大小和默认的图像格式 - jpeg。 |
| get_next_image(output_file, format) | 将图像保存到文件，使用指定的图像格式。 |
| get_next_image(output_file, page_size, format) | 将图像保存到文件，使用给定的页面大小和图像格式。 |
| get_next_image(output_stream) | 将图像保存到流，使用默认的图像格式 - jpeg。 |
| get_next_image(output_stream, page_size) | 将图像保存到流，使用给定的页面大小。 |
| get_next_image(output_stream, format) | 将图像保存到流，使用给定的图像格式。 |
| get_next_image(output_stream, page_size, format) | 将图像保存到流，使用给定的页面大小。 |
| get_next_image(output_file, format, image_width, image_height, quality) | 将图像保存到文件，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_stream, format, image_width, image_height, quality) | 将图像保存到流中，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_file, format, image_width, image_height, quality) | 将图像保存到文件中，使用给定的图像格式、图像尺寸和质量。 |
| get_next_image(output_stream, format, image_width, image_height, quality) | 将图像保存到流中，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_file, format, image_width, image_height) | 将图像保存到文件，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_stream, format, image_width, image_height) | 将图像保存到流中，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_stream, format, quality) | 将图像保存到流中，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_stream, page_size, format, quality) | 将图像保存到流中，使用给定的页面尺寸、图像格式和质量。 |
| get_next_image(output_file, format, quality) | 将图像保存到文件，使用给定的图像格式、尺寸和质量。 |
| get_next_image(output_file, page_size, format, quality) | 将图像保存到文件中，使用给定的页面尺寸、图像格式和质量。 |
| close() | 关闭 PdfConverter 实例并释放资源。 |
| do_convert() | 执行一些初始化工作，以将 PDF 文档转换为图像。 |
| has_next_image() | 指示 PDF 文件是否还有更多图像。 |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | None |
| merge_images_as_tiff(input_images_streams) | 将 tiff 流列表合并为一个多帧 tiff 流。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

