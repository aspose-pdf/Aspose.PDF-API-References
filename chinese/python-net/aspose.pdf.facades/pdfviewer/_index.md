---
title: "PdfViewer"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示用于查看或打印 pdf 的类。"
type: docs
weight: 370
url: /zh/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

表示用于查看或打印 pdf 的类。

PdfViewer 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfViewer() | 初始化新的 [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) 对象。 |
| PdfViewer(document) | 初始化 PdfViewer 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| show_hidden_areas | 获取或设置控制页面上隐藏区域可见性的标志。 |
| print_status | 获取打印作业的结果。如果成功则为 null；否则为异常对象。 |
| use_intermidiate_image | 获取/设置在文件模式下打印时将 PDF 页面转换为中间 PNG 文件的使用情况。当输出文件大小重要时使用它。 |
| coordinate_type | 获取或设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| print_as_image | 设置或获取 PdfViewer 的图像打印模式。 |
| page_count | 获取当前 PDF 文件的页数。 |
| password | 获取或设置输入文档的密码。 |
| print_page_dialog | 获取或设置一个布尔值，指示打印时是否显示页码对话框。 |
| print_as_grayscale | 获取或设置一个布尔值，指示页面是否以灰度方式打印。默认值为 false。 |
| printer_job_name | 获取或设置文档打印时在打印队列中的名称。默认值为文件名。 |
| form_presentation_mode | 获取或设置表单呈现模式。 |
| rendering_options | 获取或设置渲染选项。 |
| vertical_alignment | 获取或设置指示垂直对齐方式的值 |
| horizontal_alignment | 获取或设置指示水平对齐方式的值 |
| auto_resize | 获取或设置一个布尔值，指示文件是否以优化大小进行打印。 |
| auto_rotate | 获取或设置一个布尔值，指示文件是否使用自动旋转进行打印 |
| auto_rotate_mode | 获取或设置一个 AutoRotateMode 值，指示旋转方向 |
| resolution | 获取或设置查看和打印时的分辨率。分辨率越高，速度越慢。默认值为 150。 |
| scale_factor | 获取或设置一个浮点值，指示缩放因子。默认值为 1.0。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| print_large_pdf(file_path) | 打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百页或更多，或其大小 <br/>             超过 3 MB，建议使用此方法以获得更好的性能。 |
| print_large_pdf(input_stream) | 打开并打印大型 Pdf 流。如果您的 Pdf 文件有数百页或更多，或其大小 <br/>             超过 3 MB，建议使用此方法以获得更好的性能。 |
| print_large_pdf(file_path, printer_settings) | 使用指定的打印机设置打开并打印大型 Pdf 文件。如果您的 Pdf 文件有数百 <br/>             页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| print_large_pdf(input_stream, printer_settings) | 使用指定的打印机设置打开并打印大型 Pdf 流。如果您的 Pdf 文件有数百 <br/>             页或更多，或其大小超过 3 MB，建议使用此方法以获得更好的性能。 |
| print_large_pdf(file_path, page_settings, printer_settings) | 使用指定的页面设置和打印机设置打开并打印大型 Pdf 文件。如果您的 Pdf <br/>             文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以 <br/>             获得更好的性能。 |
| print_large_pdf(input_stream, page_settings, printer_settings) | 使用指定的页面设置和打印机设置打开并打印大型 Pdf 流。如果您的 Pdf <br/>             文件有数百页或更多，或其大小超过 3 MB，建议使用此方法以 <br/>             获得更好的性能。 |
| print_document_with_settings(page_settings, printer_settings) | 使用设置打印 Pdf 文档。如果文档尺寸与页面尺寸不兼容，pdf.kit 将扩展文档以适应页面尺寸。 |
| print_document_with_settings(printer_settings) | 使用设置打印 Pdf 文档。如果文档尺寸与页面尺寸不兼容，pdf.kit 将扩展文档以适应页面尺寸。 |
| open_pdf_file(file_path) | 打开一个 Pdf 文件，但并未实际解码该 Pdf 文件的页面。 |
| open_pdf_file(input_stream) | 打开一个 Pdf 文件流。但并未实际解码该 Pdf 文件的页面。 |
| bind_pdf(src_file) | 初始化外观。 |
| bind_pdf(src_stream) | 初始化外观。 |
| bind_pdf(src_doc) | 初始化外观。 |
| save(dest_file) | 将结果 PDF 文档保存到文件。 |
| save(dest_stream) | 将结果 PDF 文档保存到流。 |
| decode_all_pages() | 获取当前 pdf 文件的页面。 |
| decode_page(page_number) | 解码一个 Pdf 文件的页面。 |
| print_document_with_setup() | 使用设置对话框打印 Pdf 文档。通过对话框选择打印机。 |
| print_document() | 使用设置对话框打印 Pdf 文档。通过对话框选择打印机。 |
| get_default_page_settings() | 获取默认页面设置。 |
| get_default_printer_settings() | 获取默认打印机设置。 |
| close_pdf_file() | 关闭当前 Pdf 文件。 |
| close() | 关闭当前 Pdf 文件。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

