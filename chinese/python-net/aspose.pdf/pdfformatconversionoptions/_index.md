---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示用于转换 PDF 文档的一组选项。"
type: docs
weight: 1220
url: /zh/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

表示用于转换 PDF 文档的一组选项。

PdfFormatConversionOptions 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | 初始化 PdfFormatConversionOptions 类的一个新实例 |
| PdfFormatConversionOptions(output_log_file_name, format) | 初始化 PdfFormatConversionOptions 类的一个新实例 |
| PdfFormatConversionOptions(format) | 初始化 PdfFormatConversionOptions 类的一个新实例 |
| PdfFormatConversionOptions(format, action) | 初始化 PdfFormatConversionOptions 类的一个新实例 |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | 初始化 PdfFormatConversionOptions 类的一个新实例 |
| PdfFormatConversionOptions(output_log_stream, format, action) | 初始化 PdfFormatConversionOptions 类的一个新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| is_async_image_streams_conversion_mode | 获取/设置 异步模式下图像流的运行。 |
| is_low_memory_mode | 是否启用低内存转换模式 |
| format | PDF 格式。 |
| log_file_name | 用于存储注释的文件路径。 |
| log_stream | 用于存储注释的流。 |
| error_action | 无法转换的对象的操作 |
| transparency_action | 图像遮罩对象的操作 |
| convert_soft_mask_action | 带软遮罩的图像的操作。 |
| default | 获取具有默认参数的 PdfFormatConversionOptions 对象 |
| non_specification_cases | 保存标志以控制 PDF/A 转换过程，以应对源文档<br/>            不符合 PDF/A 规范的情况。 |
| symbolic_font_encoding_strategy | 在符号 TrueType 字体<br/>            有多个编码子表时，复制符号字体的编码数据的策略。 |
| align_text | 此标志控制转换后文档的文本对齐。默认情况下，文档转换 <br/> 不会影响文本对齐，保持原样。但在某些情况下，字体替换<br/> 会导致转换后文档出现文本重叠或额外空格。当设置此标志时<br/> 将执行特殊的对齐操作。此标志应仅在文档出现文本重叠或额外空格问题时使用，因为使用此标志会降低<br/> 性能，并在某些情况下可能损坏文本内容。 |
| pua_text_processing_strategy | 处理 Unicode 私用区 (PUA) 符号的策略。 |
| optimize_file_size | 获取或设置一个标志，用于启用/禁用特殊转换模式，以获得文件大小更小的 PDF/A 文档。<br/> 现在此标志影响 PDF 文档中使用的字体优化，未来可能此标志<br/> 还将用于开启对其他数据结构（如图形）的优化。<br/> 此标志和模式的组合可以显著减小文件大小，但同时可能<br/> 大幅降低转换性能。 |
| exclude_fonts_strategy | 用于排除多余字体并减小文档文件大小的策略（们）。<br/> 仅当标志 [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) 设置为 true 时，此参数才有意义。<br/> 默认使用策略组合 [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) 和<br/> [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/)。 |
| font_embedding_options | 当某些字体无法嵌入 PDF 文档时的选项。 |
| unicode_processing_rules | 解决 Unicode 映射问题的规则。可以为 null。 |
| icc_profile_file_name | 获取或设置 ICC 配置文件的文件名。如果为 null，则使用默认 ICC 配置文件。 |
| not_accessible_fonts | 此属性是输出属性。它保存所有在计算机上未找到的字体（字体名称），<br/> 在最近一次 PDF/A 转换时。 |
| is_transfer_info | 获取或设置在转换为 PDF 2.0 时是否将信息从 Info 传递到 Metadata。默认 true。 |
| align_strategy | 文本对齐的策略。仅当标志 [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) 设置为 true 时，此参数才有意义。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

