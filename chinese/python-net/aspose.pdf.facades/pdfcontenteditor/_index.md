---
title: "PdfContentEditor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示一个用于编辑 PDF 文件内容的类。"
type: docs
weight: 190
url: /zh/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

表示一个用于编辑 PDF 文件内容的类。

PdfContentEditor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfContentEditor() | PdfContentEditor 对象的构造函数。 |
| PdfContentEditor(document) | 初始化 PdfContentEditor 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| document | 获取正在处理的文档外观。 |
| text_search_options | 获取或设置文本搜索选项。 |
| text_edit_options | 获取或设置文本编辑选项。 |
| text_replace_options | 获取或设置文本替换选项。 |
| replace_text_strategy | 用于文本替换操作的一组参数 |
| DOCUMENT_OPEN | 文档事件类型。打开文档。 |
| DOCUMENT_CLOSE | 文档事件类型。关闭文档。 |
| DOCUMENT_WILL_SAVE | 文档事件类型。保存前执行操作。 |
| DOCUMENT_SAVED | 文档事件类型。保存后执行操作。 |
| DOCUMENT_WILL_PRINT | 文档事件类型。打印前执行操作。 |
| DOCUMENT_PRINTED | 文档事件类型。打印后执行操作。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(input_file) | 绑定 PDF 文件以进行编辑。 |
| bind_pdf(input_stream) | 绑定 PDF 流以进行编辑。 |
| bind_pdf(src_doc) | 绑定 PDF 文档以进行编辑。 |
| save(dest_file) | 将 PDF 文档保存到指定文件。 |
| save(dest_stream) | 将 PDF 文档保存到指定流。 |
| create_web_link(rect, url, original_page, clr) | 在 PDF 文档中创建网页链接。 |
| create_web_link(rect, url, original_page) | 在 PDF 文档中创建网页链接。 |
| create_local_link(rect, des_page, original_page, clr) | 在 PDF 文档中创建本地链接。 |
| create_local_link(rect, des_page, original_page) | 在 PDF 文档中创建本地链接。 |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | 创建一个链接到另一个 PDF 文档页面。 |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | 创建一个链接到另一个 PDF 文档页面。 |
| create_application_link(rect, application, page, clr) | 创建一个链接以在 PDF 文档中启动应用程序。 |
| create_application_link(rect, application, page) | 创建一个链接以在 PDF 文档中启动应用程序。 |
| create_file_attachment(rect, contents, file_path, page, name) | 创建文件附件注释。 |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | 创建文件附件注释。 |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | 创建文件附件注释。 |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | 创建文件附件注释。 |
| add_document_attachment(file_attachment_path, description) | 添加没有注释的文档附件。 |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | 添加没有注释的文档附件。 |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | 创建橡皮图章注释。 |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | 创建橡皮图章注释。 |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | 创建橡皮图章注释。 |
| delete_image(page_number, index) | 删除指定页面上的指定图像。 |
| delete_image() | 删除指定页面上的指定图像。 |
| replace_text(src_string, the_page, dest_string, text_state) | 在指定页面的 PDF 文件中替换文本。可以指定 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 对象（字体系列、颜色）来替换文本。 |
| replace_text(src_string, dest_string) | 在指定页面的 PDF 文件中替换文本。可以指定 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 对象（字体系列、颜色）来替换文本。 |
| replace_text(src_string, the_page, dest_string) | 在指定页面的 PDF 文件中替换文本。可以指定 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 对象（字体系列、颜色）来替换文本。 |
| replace_text(src_string, dest_string, text_state) | 在指定页面的 PDF 文件中替换文本。可以指定 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 对象（字体系列、颜色）来替换文本。 |
| replace_text(src_string, dest_string, font_size) | 在指定页面的 PDF 文件中替换文本。可以指定 [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 对象（字体系列、颜色）来替换文本。 |
| delete_stamp_by_ids(stamp_ids) | 删除文档所有页面中具有指定 ID 的印章。 |
| delete_stamp_by_ids(page_number, stamp_ids) | 删除文档所有页面中具有指定 ID 的印章。 |
| delete_stamp_by_id(page_number, stamp_id) | 删除文档所有页面中具有指定 ID 的印章。 |
| delete_stamp_by_id(stamp_id) | 删除文档所有页面中具有指定 ID 的印章。 |
| close() | 关闭已打开的文档。 |
| extract_link() | 提取 PDF 文档中包含的 Link 实例集合。 |
| create_java_script_link(code, rect, original_page, color) | 在 PDF 文档中创建指向 JavaScript 的链接。 |
| create_text(rect, title, contents, open, icon, page) | 在 PDF 文档中创建文本注释 |
| create_free_text(rect, contents, page) | 在 PDF 文档中创建自由文本注释 |
| create_markup(rect, contents, type, page, clr) | 在 PDF 文档中创建标记注释。 |
| create_popup(rect, contents, open, page) | 在 PDF 文档中创建弹出注释。 |
| delete_attachments() | 删除 PDF 文档中的所有附件。 |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | 创建线条注释。 |
| create_square_circle(rect, contents, clr, square, page, border_width) | 创建方形-圆形注释。 |
| draw_curve(line_info, page, annot_rect, annot_contents) | 创建曲线注释。 |
| create_polygon(line_info, page, annot_rect, annot_contents) | 创建多边形注释。 |
| create_poly_line(line_info, page, annot_rect, annot_contents) | 创建折线注释。 |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | 创建插入符号注释。 |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | 创建具有指定操作的书签。 |
| add_document_additional_action(event_type, code) | 为文档事件添加额外操作。 |
| remove_document_open_action() | 从文档中移除打开操作。此操作在合并多个在启动时使用显式 'GoTo' 操作的文档时非常有用。 |
| change_viewer_preference(viewer_attribution) | 更改视图首选项。 |
| get_viewer_preference() | 返回视图首选项。 |
| replace_image(page_number, index, image_file) | 将 PDF 文档中指定页面的指定图像替换为另一张图像。 |
| create_movie(rect, file_path, page) | 创建电影注释。 |
| create_sound(rect, file_path, name, page, rate) | 创建声音注释。 |
| delete_stamp(page_number, index) | 按印章索引删除指定页面上的多个印章。 |
| hide_stamp_by_id(page_number, stamp_id) | 隐藏印章。隐藏后，可使用 ShowStampById 方法恢复印章的可见性。 |
| show_stamp_by_id(page_number, stamp_id) | 显示被 HiddenStampById 隐藏的印章。 |
| move_stamp_by_id(page_number, stamp_id, x, y) | 更改印章在页面上的位置。 |
| move_stamp(page_number, stamp_index, x, y) | 更改印章在页面上的位置。 |
| get_stamps(page_number) | 返回页面上印章的数组。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

