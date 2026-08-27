---
title: "PdfFileInfo"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个用于访问 PDF 文档元信息的类。"
type: docs
weight: 270
url: /zh/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

表示一个用于访问 PDF 文档元信息的类。

PdfFileInfo 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileInfo() | 使用默认值初始化 Aspose.Pdf.Facades.PdfFileInfo 类的新实例。 |
| PdfFileInfo(input_stream) | 初始化 PdfFileInfo 类的新实例 |
| PdfFileInfo(input_stream, password) | 初始化 PdfFileInfo 类的新实例 |
| PdfFileInfo(input_file) | 初始化 PdfFileInfo 类的新实例 |
| PdfFileInfo(input_file, password) | 初始化 PdfFileInfo 类的新实例 |
| PdfFileInfo(document) | 初始化 PdfFileInfo 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| author | 获取或设置 PDF 文档的作者信息。 |
| is_encrypted | 检查 PDF 文档是否已加密。 |
| is_pdf_file | 检查源输入是否为有效的 PDF 文件。 |
| use_strict_validation | 通过使用 [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) 属性，使用严格的验证规则。 |
| creation_date | 获取或设置 PDF 文档的创建日期信息。 |
| creator | 获取或设置 PDF 文档的创建者信息。 |
| has_collection | 如果当前输入文件是包含 PDF 文件集合的 “Portfolio” 文件，则返回 true。 |
| input_file | 获取或设置输入文件。 |
| input_stream | 获取或设置输入流。 |
| keywords | 获取或设置 PDF 文档的关键字信息。 |
| mod_date | 获取或设置 PDF 文档的 ModDate 日期信息。 |
| number_of_pages | 获取文档页数。 |
| producer | 获取 PDF 文档的 Producer 信息。 |
| subject | 获取或设置 PDF 文档的 Subject 信息。 |
| 标题 | 获取或设置 PDF 文档的 Title 信息。 |
| password_type | 返回用于创建 PdfFileInfo 实例的密码类型。请参阅 [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) 中的可能取值。<br/>请注意，PDF 文档既可以使用用户（或打开）密码，也可以使用所有者（或权限、编辑）密码打开。 |
| has_open_password | 如果需要密码才能打开受密码保护的 PDF 文档，则返回 true。 |
| has_edit_password | 如果需要密码才能修改权限或文档安全属性，则返回 true。<br/>请注意，只有在 [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) 构造函数中提供了有效密码时，才能读取此属性。<br/>如果 PasswordType 为 Inaccessible（表示提供了无效密码），读取此属性将导致 [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/)。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_doc) | 初始化外观。 |
| bind_pdf(src_file) | 初始化外观。 |
| bind_pdf(src_stream) | 初始化外观。 |
| save(dest_stream) | 将更新后的 PDF 文档保存到指定的流中。 |
| save(dest_file) | 将更新后的 PDF 文档保存到指定的文件中。 |
| save_new_info(output_stream) | 将更新后的 PDF 文档保存到指定的流中。 |
| save_new_info(output_file) | 将更新后的 PDF 文档保存到指定的文件中。 |
| close() | 释放实例。 |
| clear_info() | 清除 PDF 文档的所有元信息。 |
| get_document_privilege() | 获取 PDF 文档的权限设置。 |
| get_meta_info(name) | 获取具有指定属性名称的 PDF 文档自定义信息。如果没有匹配该名称的属性，则返回空字符串。 |
| get_page_height(page_num) | 获取指定页面的高度。 |
| get_page_rotation(page_num) | 获取指定页面的旋转角度。 |
| get_page_width(page_num) | 获取指定页面的宽度。 |
| get_page_x_offset(page_num) | 获取指定页面显示区域的水平偏移量。 |
| get_page_y_offset(page_num) | 获取指定页面显示区域的垂直偏移量。 |
| get_pdf_version() | 获取 PDF 文档的版本信息。 |
| set_meta_info(name, value) | 设置 PDF 文档的自定义信息。 |
| save_new_info_with_xmp(output_file_name) | 通过设置文件信息显式更改指定属性，其他属性保持不变。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

