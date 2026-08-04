---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个用于处理 PDF 文件书签的类，包括创建、修改、导出、导入和删除。"
type: docs
weight: 180
url: /zh/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

表示一个用于处理 PDF 文件书签的类，包括创建、修改、导出、导入和删除。

PdfBookmarkEditor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfBookmarkEditor() | 初始化新的 [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) 对象。 |
| PdfBookmarkEditor(document) | 初始化 PdfBookmarkEditor 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(src_file) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_stream) | 绑定 PDF 文档以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将 PDF 文档保存到指定文件。 |
| save(dest_stream) | 将 PDF 文档保存到指定流。 |
| create_bookmarks() | 为所有页面创建书签。 |
| create_bookmarks(bookmark) | 为所有页面创建书签。 |
| create_bookmarks(color, bold_flag, italic_flag) | 使用指定的颜色和样式（粗体，斜体）为所有页面创建书签。 |
| create_bookmark_of_page(bookmark_name, page_number) | 为指定页面创建书签。 |
| create_bookmark_of_page(bookmark_name, page_number) | 为指定的页面创建书签。 |
| delete_bookmarks() | 删除 PDF 文档的所有书签。 |
| delete_bookmarks(title) | 删除 PDF 文档的书签。 |
| extract_bookmarks() | 从文档中提取所有层级的书签。 |
| extract_bookmarks(upper_level) | 从文档中提取所有层级的书签。 |
| extract_bookmarks(title) | 提取具有指定标题的书签。 |
| extract_bookmarks(bookmark) | 从文档中提取所有层级的书签。 |
| export_bookmarks_to_xml(xml_file) | 将书签导出为 XML 文件。 |
| export_bookmarks_to_xml(stream) | 将书签导出到 XML 流。 |
| import_bookmarks_with_xml(xml_file) | 从 XML 文件将书签导入到文档中。 |
| import_bookmarks_with_xml(stream) | 从 XML 文件将书签导入到文档中。 |
| close() | 释放与当前外观关联的所有资源。 |
| modify_bookmarks(s_title, d_title) | 根据指定的书签标题修改书签标题。 |
| extract_bookmarks_to_html(pdf_file, css_file) | 将书签导出为 HTML 文件。 |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | 将书签导出为 HTML 文件。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

