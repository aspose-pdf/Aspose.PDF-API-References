---
title: "Document"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示 PDF 文档的类"
type: docs
weight: 230
url: /zh/python-net/aspose.pdf/document/
---

## Document class

表示 PDF 文档的类

Document 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Document(input) | 初始化 Document 类的新实例 |
| Document(input, password, is_managed_stream) | 初始化 Document 类的新实例 |
| Document(input, is_managed_stream) | 初始化 Document 类的新实例 |
| Document(filename) | 初始化 Document 类的新实例 |
| Document(input, password) | 初始化 Document 类的新实例 |
| Document() | 初始化空文档。 |
| Document(filename, options) | 初始化 Document 类的新实例 |
| Document(input, options) | 初始化 Document 类的新实例 |
| Document(filename, password) | 初始化 Document 类的新实例 |
| Document(filename, password, is_managed_stream) | 初始化 Document 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| java_script | 文档级别的 JavaScript 集合。 |
| is_licensed | 获取系统的授权状态。系统在授权模式下返回 true，否则返回 false。 |
| page_info | 获取或设置页面信息。（仅用于生成器，读取文档时不填充） |
| enable_signature_sanitization | 获取或设置用于管理签名字段清理的标志。默认启用。 |
| is_pdfa_compliant | 获取文档是否符合 PDF/A 标准。 |
| is_pdf_ua_compliant | 获取文档是否符合 PDF/UA 标准。 |
| is_xref_gaps_allowed | 获取或设置文档是否符合 PDF/A 标准。 |
| named_destinations | 文档中命名目标的集合。 |
| destinations | 获取目标的集合。<br/>            已弃用。请使用 NamedDestinations。 |
| pdf_format | 获取 PDF 格式 |
| embed_standard_fonts | 声明文档必须嵌入所有标准 Type1 字体的属性 <br/>            该字体的 IsEmbedded 标志被设为 true。所有 PDF 字体都可以通过将 IsEmbedded 标志设为 true 简单地嵌入文档，但 PDF 标准 Type1 字体是此规则的例外。<br/>            标准 Type1 字体的嵌入需要大量时间，因此嵌入这些字体时不仅需要为指定字体将 IsEmbedded 标志设为 true，还需要在文档级别设置额外的标志 - EmbedStandardFonts = true;<br/>            此属性只能为所有字体设置一次。<br/>            默认值为 false. |
| disable_font_license_verifications | 如果字体的许可证禁止，许多与字体相关的操作将无法执行。<br/>            例如，如果许可证规则禁用嵌入，则某些字体无法嵌入到 PDF 文档中。<br/>            此标志用于在当前 PDF 文档中禁用所有字体的任何许可证限制。<br/>            使用此标志时请谨慎。设置后意味着设置此标志的人，<br/>            必须自行承担可能的许可证/法律违规责任。<br/>            因此，他需自行承担风险。<br/>            强烈建议仅在完全确信不会侵犯版权法时才使用此标志。<br/>            默认值为 false. |
| font_utilities | IDocumentFontUtilities 实例 |
| collection | 获取文档的集合。 |
| version | 从 PDF 文件头获取 PDF 的版本。 |
| open_action | 获取或设置文档打开时执行的操作。 |
| hide_tool_bar | 获取或设置标志，指定文档激活时是否隐藏工具栏。 |
| hide_menubar | 获取或设置标志，指定文档激活时是否隐藏菜单栏。 |
| hide_window_ui | 获取或设置标志，指定文档激活时是否隐藏用户界面元素。 |
| fit_window | 获取或设置标志，指定文档窗口是否必须调整大小以适应首次显示的页面。 |
| center_window | 获取或设置标志，指定文档窗口的位置是否在屏幕上居中。 |
| display_doc_title | 获取或设置标志，指定文档窗口标题栏是否应显示文档标题。 |
| pages | 获取或设置文档页面的集合。<br/>            请注意，集合中的页面编号从 1 开始。 |
| outlines | 获取文档大纲。 |
| actions | 获取文档操作。此属性是 DocumentActions 类的实例，允许获取/设置 BeforClosing、BeforSaving 等操作。 |
| form | 获取文档的 Acro Form。 |
| embedded_files | 获取嵌入文档的文件集合。 |
| direction | 获取或设置文本的阅读顺序：L2R（从左到右）或 R2L（从右到左）。 |
| page_mode | 获取或设置页面模式，指定打开文档时的显示方式。 |
| non_full_screen_page_mode | 获取或设置页面模式，指定退出全屏模式时文档的显示方式。 |
| page_layout | 获取或设置页面布局，该布局将在打开文档时使用。 |
| duplex | 获取或设置打印双面模式的处理选项，以在打印对话框中打印文件时使用。 |
| file_name | 导致此文档的 PDF 文件名称 |
| info | 获取文档信息。 |
| 元数据 | 文档元数据。<br/>            （PDF 文档可能包含一般信息，<br/>             如文档的标题、作者以及创建和修改日期。<br/>             这些关于文档的全局信息（相对于其内容或结构）称为元数据，<br/>             旨在帮助在外部数据库中对文档进行编目和搜索。） |
| 逻辑结构 | 获取文档的逻辑结构。 |
| 处理签名更改 | 如果文档在有更改且带有签名的情况下保存，则抛出异常 |
| 加密算法 | 如果文档已加密，则获取安全设置。 <br/>            如果文档未加密，则在 .net 1.1 中会抛出相应的异常<br/>            或在其他 .net 版本中 CryptoAlgorithm 为 null。 |
| 是否线性化 | 获取或设置指示文档是否线性化的值。 |
| 权限 | 获取文档的权限。 |
| is_encrypted | 获取文档的加密状态。如果文档已加密，则为 true。 |
| id | 获取 ID。 |
| background | 获取或设置文档的背景颜色。 |
| optimize_size | 获取或设置优化标志。当向文档添加页面时，如果设置了此标志，结果文件中相等的资源流将<br/>            合并为一个 PDF 对象。<br/>            这可以减小生成文件的大小，但可能导致执行速度变慢和内存需求增大。<br/>            默认值：false。 |
| allow_reuse_page_content | 允许合并页面内容以优化文档大小。如果使用此功能，不同但重复的页面可能引用同一个内容对象。<br/>            请注意，此模式可能导致副作用，例如在更改其他页面时页面内容会随之改变。 |
| 忽略损坏的对象 | 获取或设置在源文件中忽略错误的标志。 <br/>            当从源文档复制页面到目标文档时，如果此标志为 false 且源文件中的某些对象损坏，复制过程会因异常而停止。<br/>            示例：dest.Pages.Add(src.Pages);<br/>            如果此标志设置为 true，则损坏的对象将被替换为空值。<br/>            默认值：true。 |
| 页面标签 | 获取文档中的页面标签。 |
| 启用对象卸载 | 获取或设置允许文档部分从内存中卸载的标志。 <br/>            这可以降低内存使用，但可能对性能产生负面影响。 |
| 标记内容 | 获取对 TaggedPdf 内容的访问。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| save(output) | 将文档存储到流中。 |
| save(output_file_name) | 将文档保存到指定文件中。 |
| save() | 将文档存储到流中。 |
| save(options) | 使用保存选项保存文档。 |
| save(output_file_name, format) | 使用新名称和文件格式保存文档。 |
| save(output_stream, format) | 使用新名称和文件格式保存文档。 |
| save(output_file_name, options) | 使用新名称并设置保存选项来保存文档。 |
| save(output_stream, options) | 使用保存选项将文档保存到流中。 |
| export_annotations_to_xfdf(file_name) | 将所有文档批注导出到 XFDF 文件 |
| export_annotations_to_xfdf(stream) | 将所有文档批注导出到流中。 |
| send_to(device, output) | 将整个文档发送到文档设备进行处理。 |
| send_to(device, from_page, to_page, output) | 将文档的特定页面发送到文档设备进行处理。 |
| send_to(device, output_file_name) | 将整个文档发送到文档设备进行处理。 |
| send_to(device, from_page, to_page, output_file_name) | 将整个文档发送到文档设备进行处理。 |
| import_annotations_from_xfdf(file_name) | 将批注从 XFDF 文件导入到文档中。 |
| import_annotations_from_xfdf(stream) | 从流导入批注到文档。 |
| validate(output_log_file_name, format) | 将文档验证到指定文件。 |
| validate(output_log_stream, format) | 将文档验证到指定文件。 |
| validate(options) | 将文档验证到指定文件。 |
| convert(output_log_file_name, format, action, transparency_action) | 转换文档并将错误保存到指定文件。 |
| convert(output_log_stream, format, action, transparency_action) | 转换文档并将错误保存到指定文件。 |
| convert(output_log_file_name, format, action) | 转换文档并将错误保存到指定文件。 |
| convert(options) | 使用指定的转换选项转换文档 |
| convert(output_log_stream, format, action) | 转换文档并将错误保存到指定文件。 |
| convert(fixup, output_log, only_validation, parameters) | 通过应用 Fixup 转换文档。 |
| convert(fixup, output_log, only_validation, parameters) | 通过应用 Fixup 转换文档。 |
| convert(src_file_name, load_options, dst_file_name, save_options) | 将源文件（源格式）转换为目标文件（目标格式）。 |
| convert(src_stream, load_options, dst_file_name, save_options) | 将流（源格式）转换为目标文件（目标格式）。 |
| convert(src_file_name, load_options, dst_stream, save_options) | 将流（源格式）转换为目标文件（目标格式）。 |
| convert(src_stream, load_options, dst_stream, save_options) | 将流（源格式）转换为目标文件（目标格式）。 |
| flatten() | 从文档中移除所有字段并用其值替代。 |
| flatten(flatten_settings) | 从文档中移除所有字段并用其值替代。 |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | 加密文档。随后调用 Save 以获取加密后的文档版本。 |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | 加密文档。随后调用 Save 以获取加密后的文档版本。 |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | 加密文档。随后调用 Save 以获取加密后的文档版本。 |
| optimize_resources() | 优化文档中的资源：<br/>            1. 未在文档页面中使用的资源将被移除；<br/>            2. 相同的资源将合并为一个对象； <br/>            3. 未使用的对象将被删除。 |
| optimize_resources(strategy) | 根据定义的优化策略优化文档中的资源。 |
| bind_xml(file) | 将 xml 绑定到文档 |
| bind_xml(xml_file, xsl_file) | 将 xml 绑定到文档 |
| bind_xml(xml_stream, xsl_stream) | 将 xml/xsl 绑定到文档 |
| bind_xml(stream) | 将 xml/xsl 绑定到文档 |
| remove_pdfa_compliance() | 从文档中移除 pdfa 合规性 |
| remove_pdf_ua_compliance() | 从文档中移除 pdfUa 合规性 |
| set_title(title) | 设置 PDF 文档的标题 |
| process_paragraphs() | 为生成器处理段落。 |
| remove_metadata() | 从文档中移除元数据。 |
| change_passwords(owner_password, new_user_password, new_owner_password) | 更改文档密码。此操作只能使用所有者密码进行。 |
| decrypt() | 解密文档。随后调用 Save 以获取文档的解密版本。 |
| optimize() | Linearize document in order to<br/>            - 尽快打开首页；<br/>            - 尽快显示下一页或通过链接跳转到下一页；<br/>            - 当页面数据通过慢速通道传输时，逐步显示页面（优先显示最有用的数据）；<br/>            - 允许用户交互，例如点击链接，即使在整个页面尚未接收完毕并显示时也能执行。<br/>            调用此方法并不会实际保存文档。相反，文档仅被准备为优化结构，<br/>            然后调用 Save 以获取优化后的文档。 |
| get_catalog_value(key) | 返回目录字典中的项值。 |
| free_memory() | 清除内存 |
| save_xml(file) | 将文档保存为 XML。 |
| get_object_by_id(id) | 获取文档中具有指定 ID 的对象。 |
| repair() | 修复损坏的文档。 |
| get_xmp_metadata(stream) | 从文档获取 XMP 元数据。 |
| set_xmp_metadata(stream) | 设置文档的 XMP 元数据。 |
| check(do_repair) | 验证文档。 |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | 将文档中的页面树节点组织为平衡树。<br/>            仅当文档的页面对象数量超过 nodesNumInSubtrees 时才执行，否则不做任何操作。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

