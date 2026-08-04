---
title: "PdfFileEditor"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "实现 PDF 文件的合并、拆分、提取页面、制作小册子等操作。"
type: docs
weight: 220
url: /zh/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。

PdfFileEditor 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFileEditor() | 初始化 PdfFileEditor 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| conversion_log | 获取转换过程的日志。 |
| merge_duplicate_layers | 如果此属性为 true，则具有相同名称的合并文档的可选内容将合并为结果文档中的一个图层。<br/>否则，具有相同名称的图层将保存为结果文档中的不同图层。 |
| copy_outlines | 如果为 true，则会复制大纲。 |
| copy_logical_structure | 如果为 true，则在执行合并时复制文件的逻辑结构。 |
| merge_duplicate_outlines | 如果为 true，重复的大纲将被合并。 |
| preserve_user_rights | 如果为 true，首个文档的用户权限将应用于合并后的文档。所有其他文档的用户权限将被忽略。 |
| incremental_updates | 如果为 true，在合并期间将进行增量更新。 |
| optimize_size | 获取或设置优化标志。如果设置此标志，结果文件中相等的资源流将合并为一个 PDF 对象。<br/>            这可以减小结果文件的大小，但可能导致执行速度变慢和更高的内存需求。<br/>            默认值：false。 |
| corrupted_items | 在执行合并时遇到的问题数组。对于传递给 Concatenate() 的每个损坏文档，<br/>会创建一个新的 CorruptedItem 条目。<br/>此属性仅在 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时可用。 |
| corrupted_file_action | 此属性定义在合并过程中遇到损坏文件时的行为。<br/>可能的值有：StopWithError 和 ConcatenateIgnoringCorrupted。 |
| owner_password | 如果源输入 PDF 文件已加密，则设置所有者密码。<br/>此属性尚未实现。 |
| allow_concatenate_exceptions | 如果设置为 true，则在发生错误时抛出异常。否则，不抛出异常，方法在失败时返回 false。 |
| close_concatenated_streams | 如果设置为 true，操作完成后将关闭流。 |
| unique_suffix | 在表单合并时添加到字段名称以使其唯一的后缀格式。<br/>此字符串必须包含 %NUM% 子串，该子串将被数字替换。<br/>例如，如果 UniqueSuffix = "ABC%NUM%"，则字段 "fieldName" 的名称将为：<br/>fieldNameABC1, fieldNameABC2, fieldNameABC3 等。 |
| keep_actions | 如果为 true，将从源文档复制操作。默认值：true。 |
| keep_fields_unique | 如果为 true，则在合并表单时字段名称将被设为唯一。<br/>            将向字段名称添加后缀，后缀模板可以在 UniqueSuffix 属性中指定。 |
| remove_signatures | 如果为 true，所有签名将从字段中移除（字段将保留）；否则，可能会出现无效的签名。 |
| use_disk_buffer | 如果使用此选项，则目标文档将定期保存在磁盘上，后续的合并将作为增量更新应用于该文档。 |
| concatenation_packet_size | 当 UseDiskBuffer 设置为 true 时，在进行合并期间，在创建新的增量更新之前已合并的文档数量。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | 合并两个文件。 |
| try_concatenate(src, dest) | 合并文档。 |
| try_concatenate(input_files, output_file) | 将多个文件合并为一个文件。 |
| try_concatenate(input_stream, output_stream) | 合并文件 |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | 合并两个文件。 |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | 合并文件 |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | 追加页面，这些页面从 portStreams 中的文档数组中选择。<br/>            结果文档包括 firstInputFile 以及所有 portStreams 文档在 startPage 到 endPage 范围内的页面。 |
| try_append(input_file, port_files, start_page, end_page, output_file) | 追加页面，这些页面从 portFiles 文档中选择。 <br/>            结果文档包括 firstInputFile 以及所有 portFiles 文档在 startPage 到 endPage 范围内的页面。 |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | 将页面从另一个文件插入到输入的 Pdf 文件中。 |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | 将页面从另一个文件插入到输入的 Pdf 文件中。 |
| try_delete(input_file, page_number, output_file) | 删除由数字数组指定的页面，从输入文件中，保存为新的 Pdf 文件。 |
| try_delete(input_stream, page_number, output_stream) | 删除由数字数组指定的页面，从输入文件中，保存为新的 Pdf 文件。 |
| try_extract(input_file, start_page, end_page, output_file) | 提取页面从输入文件，保存为新的 Pdf 文件。 |
| try_extract(input_file, page_number, output_file) | 提取由数字数组指定的页面，保存为新的 PDF 文件。 |
| try_extract(input_stream, page_number, output_stream) | 提取由数字数组指定的页面，保存为新的 Pdf 文件。 |
| try_split_from_first(input_file, location, output_file) | 从第一页到指定位置拆分 Pdf 文件，并将前部保存为新文件。 |
| try_split_from_first(input_stream, location, output_stream) | 从起始位置到指定位置拆分，并将前部保存到输出 Stream 中。 |
| try_split_to_end(input_file, location, output_file) | 从指定位置拆分，并将后部保存为新文件。 |
| try_split_to_end(input_stream, location, output_stream) | 从指定位置拆分，并将后部保存为新文件 Stream。 |
| try_make_booklet(input_file, output_file) | 从输入文件制作小册子到输出文件。 |
| try_make_booklet(input_stream, output_stream) | 从 InputStream 制作小册子到 outputStream。 |
| try_make_booklet(input_file, output_file, page_size) | 从 inputFile 制作小册子到 outputFile。 |
| try_make_booklet(input_stream, output_stream, page_size) | 从输入流制作小册子并将结果保存到输出流。 |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | 从 firstInputFile 创建自定义小册子到 outputFile。 |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | 从 firstInputStream 创建自定义小册子到 outputStream。 |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | 从 firstInputFile 创建自定义小册子到 outputFile。 |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | 从 firstInputStream 创建小册子到 outputStream。 |
| try_make_n_up(input_file, output_file, x, y) | 从 firstInputFile 创建 N-Up 文档到 outputFile。 |
| try_make_n_up(input_stream, output_stream, x, y) | 从输入流创建 N-Up 文档并将结果保存到输出流。 |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | 从第一个输入流创建 N-Up 文档到输出流。 |
| try_make_n_up(first_input_file, second_input_file, output_file) | 从 firstInputFile 创建 N-Up 文档到 outputFile。 |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | 从输入流创建 N-Up 文档并将结果保存到输出流。 |
| try_make_n_up(input_files, output_file, is_sidewise) | 从多个输入 PDF 文件创建 N-Up 文档到 outputFile。<br/>            outputFile 的每一页将包含多页，这些页面是来自输入文件中相同页码的页面的组合。<br/>            如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 |
| try_make_n_up(input_streams, output_stream, is_sidewise) | 从多个输入 PDF 流创建 N-Up 文档到 outputStream。<br/>            outputStream 的每一页将包含多页，这些页面是来自输入流中相同页码的页面的组合。<br/>            如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 |
| try_make_n_up(input_file, output_file, x, y, page_size) | 从输入文件创建 N-Up 文档到 outputFile。 |
| try_resize_contents(source, destination, pages, parameters) | 调整文档页面内容的大小。 |
| try_resize_contents(source, destination, pages, new_width, new_height) | 调整文档页面内容的大小。<br/>            缩小页面内容并添加边距。<br/>            内容的新尺寸以默认空间单位指定。 |
| try_resize_contents(source, destination, pages, parameters) | 调整文档中页面的内容大小。如果页面被缩小，则在页面周围添加空白边距。 |
| concatenate(first_input_file, sec_input_file, output_file) | 连接文件并将结果保存到 HttpResposnse 对象中。 |
| concatenate(first_input_stream, sec_input_stream, output_stream) | 连接文件并将结果存储到 HttpResponse 对象中。 |
| concatenate(src, dest) | 合并文档。 |
| concatenate(input_files, output_file) | 连接文件并将结果保存到 HttpResposnse 对象中。 |
| concatenate(input_stream, output_stream) | 连接文件并将结果存储到 HttpResponse 对象中。 |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | 连接文件并将结果保存到 HttpResposnse 对象中。 |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | 连接文件并将结果存储到 HttpResponse 对象中。 |
| append(input_stream, port_streams, start_page, end_page, output_stream) | 将文档追加到源文档并将结果保存到 response 对象中。 |
| append(input_file, port_files, start_page, end_page, output_file) | 将文档追加到源文档并将结果保存到 HttpResponse 对象中。 |
| append(input_file, port_file, start_page, end_page, output_file) | 将文档追加到源文档并将结果保存到 HttpResponse 对象中。 |
| append(input_stream, port_stream, start_page, end_page, output_stream) | 将文档追加到源文档并将结果保存到 response 对象中。 |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | 将文件内容插入到源文件中并将结果存储到 HttpResponse 对象中。 |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | 将文档插入到另一个文档中并将结果存储到 response 对象中。 |
| insert(input_file, insert_location, port_file, page_number, output_file) | 将文件内容插入到源文件中并将结果存储到 HttpResponse 对象中。 |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | 将文档插入到另一个文档中并将结果存储到 response 对象中。 |
| delete(input_file, page_number, output_file) | 删除文档中指定的页面并将结果存储到 HttpResponse 对象中。 |
| delete(input_stream, page_number, output_stream) | 从文档中删除指定的页面并将结果保存到 HttpResponse 对象中。 |
| extract(input_file, start_page, end_page, output_file) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| extract(input_file, page_number, output_file) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| extract(input_stream, start_page, end_page, output_stream) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| extract(input_stream, page_number, output_stream) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| split_from_first(input_file, location, output_file) | 将文档从第一页拆分至指定位置，并将结果保存到 HttpResponse 对象中。 |
| split_from_first(input_stream, location, output_stream) | 将文档从起始位置拆分至指定位置，并将结果存储到 HttpResponse 对象中。 |
| split_to_end(input_file, location, output_file) | 从指定位置拆分，并将后部保存到 HttpResponse 对象中。 |
| split_to_end(input_stream, location, output_stream) | 从指定位置拆分，并将后部保存到 HttpResponse 对象中。 |
| make_booklet(input_file, output_file) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| make_booklet(input_stream, output_stream) | 从 PDF 文件制作小册子并将其存储到 HttpResponse 中。 |
| make_booklet(input_file, output_file, page_size) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| make_booklet(input_stream, output_stream, page_size) | 从 PDF 文件制作小册子并将其存储到 HttpResponse 中。 |
| make_booklet(input_file, output_file, left_pages, right_pages) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | 从 PDF 文件制作小册子并将其存储到 HttpResponse 中。 |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | 从 PDF 文件制作小册子并将其存储到 HttpResponse 中。 |
| make_n_up(input_file, output_file, x, y) | 生成 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| make_n_up(input_stream, output_stream, x, y) | 生成 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| make_n_up(input_stream, output_stream, x, y, page_size) | 生成 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| make_n_up(first_input_file, second_input_file, output_file) | 生成 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| make_n_up(first_input_stream, second_input_stream, output_stream) | 生成 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| make_n_up(input_files, output_file, is_sidewise) | 从多个输入 PDF 文件创建 N-Up 文档到 outputFile。<br/>            outputFile 的每一页将包含多页，这些页面是来自输入文件中相同页码的页面的组合。<br/>            如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 |
| make_n_up(input_streams, output_stream, is_sidewise) | 从多个输入 PDF 流创建 N-Up 文档到 outputStream。<br/>            outputStream 的每一页将包含多页，这些页面是来自输入流中相同页码的页面的组合。<br/>            如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 |
| make_n_up(input_file, output_file, x, y, page_size) | 生成 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| split_to_pages(input_file, file_name_template) | 将 PDF 文件拆分为单页文档。 |
| split_to_pages(input_stream, file_name_template) | 将 PDF 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。 |
| resize_contents(source, destination, pages, parameters) | 调整文档中页面内容的大小。如果页面被缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。 |
| resize_contents(source, destination, pages, new_width, new_height) | 调整文档页面内容的大小。<br/>            缩小页面内容并添加边距。<br/>            内容的新尺寸以默认空间单位指定。 |
| resize_contents(source, destination, pages, new_width, new_height) | 调整文档页面内容的大小。<br/>            缩小页面内容并添加边距。<br/>            内容的新尺寸以默认空间单位指定。 |
| resize_contents(source, destination, pages, parameters) | 调整文档中页面内容的大小。如果页面被缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。 |
| resize_contents(source, pages, parameters) | 调整文档页面的大小。对缩小的页面在周围添加空白边距。 |
| resize_contents(source, parameters) | 调整文档页面的大小。对缩小的页面在周围添加空白边距。 |
| resize_contents_pct(source, destination, pages, new_width, new_height) | 调整文档页面的内容。<br/>            缩小页面内容并添加边距。<br/>            新的内容尺寸以百分比指定。 |
| resize_contents_pct(source, destination, pages, new_width, new_height) | 调整文档页面的内容。<br/>            缩小页面内容并添加边距。<br/>            新的内容尺寸以百分比指定。 |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 调整页面内容并添加指定的边距。 <br/>            边距以默认空间单位指定。 |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 调整页面内容并添加指定的边距。 <br/>            边距以默认空间单位指定。 |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 调整页面内容并添加指定的边距。<br/>            边距以初始页面尺寸的百分比指定。 |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | 调整页面内容并添加指定的边距。<br/>            边距以初始页面尺寸的百分比指定。 |
| add_page_break(src, dest, page_breaks) | 在文档页面中添加分页符。 |
| add_page_break(src, dest, page_breaks) | 在文档页面中添加分页符。 |
| add_page_break(src, dest, page_breaks) | 在文档页面中添加分页符。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

