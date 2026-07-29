---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PdfFileEditorWeb 类，实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。"
type: docs
weight: 480
url: /zh/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

表示 PdfFileEditorWeb 类，实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | PdfFileEditorWeb 构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | 调整页面内容大小并添加指定的边距。 |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | 将文档追加到源文档，并将结果保存到响应对象中。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | 追加页面，这些页面从 portStreams 中的文档数组中选择。 |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | 追加页面，这些页面在 portStream 中从 startPage 到 endPage 范围内选择，并在 firstInputStream 末尾的 portStream 中。 |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | 将文档追加到源文档，并将结果保存到 HttpServletResponse 对象中。 |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | 追加页面，这些页面从 portFiles 文档中选择。 |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | 追加页面，这些页面在 portFile 中从 startPage 到 endPage 范围内选择，并在 firstInputFile 末尾的 portFile 中。 |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | 合并文档。 |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | 连接文件并将结果存储到 HttpServletResponse 对象中。 |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | 合并文件 |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。 |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 合并两个文件。 |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | 连接文件并将结果保存到 HttpResposnse 对象中。 |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | 将文件合并为一个文件。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | 合并两个文件。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。 |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | 删除文档中指定的页面，并将结果保存到 HttpServletResponse 对象中。 |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | 删除文档中指定的页面，并将结果存储到 HttpServletResponse 对象中。 |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | 提取源文件中指定的页面并将结果存储到 HttpServletResponse 对象中。 |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | 提取由数字数组指定的页面，保存为新的 Pdf 文件。 |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 从输入文件中提取页面，保存为新的 Pdf 文件。 |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | 提取源文件中指定的页面并将结果存储到 HttpServletResponse 对象中。 |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | 提取由数字数组指定的页面，保存为新的 PDF 文件。 |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | 从输入文件中提取页面，保存为新的 Pdf 文件。 |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | 已弃用。此属性已弃用，不能用于抛出异常。 |
| [getAttachmentName](#getAttachmentName--) | 获取当操作结果以附件形式存储到 HttpServletResponse 对象时的附件名称。 |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | 如果设置为 true，操作完成后流将被关闭。 |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | 当 UseDiskBuffer 设置为 true 时，在连接期间在进行新的增量更新之前已连接的文档数量。 |
| [getContentDisposition](#getContentDisposition--) | 获取当操作结果存储到 HttpServletResponse 对象时内容的存储方式。 |
| [getConversionLog](#getConversionLog--) | 获取转换过程的日志。 |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | 如果为 true，则在执行连接时复制文件的逻辑结构。 |
| [getCopyOutlines](#getCopyOutlines--) | 如果为 true，则复制大纲。 |
| [getCorruptedFileAction](#getCorruptedFileAction--) | 此属性定义在连接过程中遇到损坏文件时的行为。 |
| [getCorruptedItems](#getCorruptedItems--) | 执行连接时遇到的问题数组。 |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | 表示在连接期间工作的内部进度事件处理器，并将内部连接阶段的事件转换为外部客户代码。 |
| [getIncrementalUpdates](#getIncrementalUpdates--) | 如果为 true，则在连接期间进行增量更新。 |
| [getKeepActions](#getKeepActions--) | 如果为 true，则会从源文档复制操作。 |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | 如果为 true，则在合并表单时字段名称将被设为唯一。 |
| [getLastException](#getLastException--) | 获取最近一次发生的异常。 |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | 如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。 |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | 如果为 true，合并重复的大纲。 |
| [getOptimizeSize](#getOptimizeSize--) | 获取或设置优化标志。 |
| [getOwnerPassword](#getOwnerPassword--) | 如果源输入 PDF 文件已加密，则获取所有者密码。 |
| [getPreserveUserRights](#getPreserveUserRights--) | 如果为 true，则将第一个文档的用户权限应用于连接后的文档。 |
| [getRemoveSignatures](#getRemoveSignatures--) | 如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。 |
| [getSaveOptions](#getSaveOptions--) | 获取或设置当结果存储为 HttpServletResponse 时的保存选项。 |
| [getUniqueSuffix](#getUniqueSuffix--) | 获取在合并表单时添加到字段名称以使其唯一的后缀格式。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | 将文档插入到另一个文档中，并将结果存储到响应对象中。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | 将另一个文件的页面插入到输入 PDF 文件中。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | 将另一个文件的页面插入到输入 PDF 文件中。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | 将文件内容插入到源文件中，并将结果存储到 HttpServletResponse 对象中。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | 将另一个文件的页面插入到输入 PDF 文件中。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 在指定位置将另一个文件的页面插入到 PDF 文件中。 |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含由多个相同的平铺背景图像并排放置而构成的页面或表格单元格的背景图像。 |
| [isUseDiskBuffer](#isUseDiskBuffer--) | 如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | 从 InputStream 创建小册子并输出到 outputStream。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | 从 firstInputStream 创建自定义小册子并输出到 outputStream。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | 从输入流创建小册子并将结果保存到输出流。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | 从 firstInputStream 创建小册子并输出到 outputStream。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 从源文件制作小册子，并将结果存储到 HttpServletResponse 中。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | 从 PDF 文件制作小册子，并将其存储到 HttpServletResponse 中。 |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 从源文件制作小册子，并将结果存储到 HttpServletResponse 对象中。 |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | 从源文件制作小册子，并将结果存储到 HttpServletResponse 对象中。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | 从输入文件创建小册子并输出到输出文件。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | 从 inputFile 创建小册子并输出到 outputFile。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | 从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。 |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | 制作 N-up 文档，并将结果存储到 HttpServletResponse 中。 |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 制作 N-up 文档，并将结果存储到 HttpServletResponse 对象中。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | 从输入流创建 N-Up 文档并将结果保存到输出流。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | 从第一个输入流创建 N-Up 文档并输出到输出流。 |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | 从多个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | 制作 N-up 文档，并将结果存储到 HttpServletResponse 中。 |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 制作 N-up 文档，并将结果存储到 HttpServletResponse 对象中。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | 从 firstInputFile 创建 N-Up 文档并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | 从输入文件创建 N-Up 文档并输出到 outputFile。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | 从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。 |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的内容大小。 |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | 调整文档中页面的内容大小。 |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | 调整文档中页面的内容大小。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档中页面的内容大小。 |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | 调整文档页面的内容大小。 |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | 已弃用。此属性已弃用，不能用于抛出异常。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 设置附件的名称，当操作结果以附件形式存储到 HttpServletResponse 对象时使用。 |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | 如果设置为 true，操作完成后流将被关闭。 |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | 当 UseDiskBuffer 设置为 true 时，在连接期间在进行新的增量更新之前已连接的文档数量。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpServletResponse 对象时内容的存储方式。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | 如果为 true，则在执行连接时复制文件的逻辑结构。 |
| [setCopyOutlines](#setCopyOutlines-boolean-) | 如果为 true，则复制大纲。 |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | 此属性定义在连接过程中遇到损坏文件时的行为。 |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | 表示在连接期间工作的内部进度事件处理器，并将内部连接阶段的事件转换为外部客户代码。 |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | 如果为 true，则在连接期间进行增量更新。 |
| [setKeepActions](#setKeepActions-boolean-) | 如果为 true，则会从源文档复制操作。 |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | 如果为 true，则在合并表单时字段名称将被设为唯一。 |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | 如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。 |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | 如果为 true，合并重复的大纲。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 获取或设置优化标志。 |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | 如果源输入 Pdf 文件已加密，则设置所有者密码。 |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | 如果为 true，则将第一个文档的用户权限应用于连接后的文档。 |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | 如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 设置当结果存储为 HttpServletResponse 时的保存选项。 |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含由多个相同的平铺背景图像并排放置而构成的页面或表格单元格的背景图像。 |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | 设置在表单合并时添加到字段名称以使其唯一的后缀格式。 |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | 如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | 将文档从起始位置拆分到指定位置，并将结果存储到 HttpServletResponse 对象中。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | 从起始位置拆分到指定位置，并将前半部分保存到输出流中。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | 将文档从第一页拆分到指定位置，并将结果保存到 HttpServletResponse 对象中。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | 将 Pdf 文件从第一页拆分到指定位置，并将前半部分保存为新文件。 |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | 将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。 |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | 将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | 从指定位置拆分，并将后部保存到 HttpServletResponse 对象中。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | 从指定位置拆分，并将后半部分保存为新的文件流。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | 从指定位置拆分，并将后部保存到 HttpServletResponse 对象中。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | 从该位置拆分，并将后半部分保存为新文件。 |
| [splitToPages](#splitToPages-java.io.InputStream-) | 将 Pdf 文件拆分为单页文档。 |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [splitToPages](#splitToPages-java.lang.String-) | 将 PDF 文件拆分为单页文档。 |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

PdfFileEditorWeb 构造函数。

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
调整页面内容大小并添加指定的边距。

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
将文档追加到源文档，并将结果保存到响应对象中。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
追加页面，这些页面从 portStreams 中的文档数组中选择。

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
追加页面，这些页面在 portStream 中从 startPage 到 endPage 范围内选择，并在 firstInputStream 末尾的 portStream 中。

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
将文档追加到源文档，并将结果保存到 HttpServletResponse 对象中。

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
追加页面，这些页面从 portFiles 文档中选择。

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
追加页面，这些页面在 portFile 中从 startPage 到 endPage 范围内选择，并在 firstInputFile 末尾的 portFile 中。

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
合并文档。

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
连接文件并将结果存储到 HttpServletResponse 对象中。

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
合并文件

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
合并两个文件。

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
连接文件并将结果保存到 HttpResposnse 对象中。

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
将文件合并为一个文件。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
合并两个文件。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
将两个 Pdf 文档合并为一个新 Pdf 文档，页面交替排列，并用空白页填充空白位置。

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
删除文档中指定的页面，并将结果保存到 HttpServletResponse 对象中。

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
删除文档中指定的页面，并将结果存储到 HttpServletResponse 对象中。

### delete {#delete-java.lang.String-int:A-java.lang.String-}
从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
提取源文件中指定的页面并将结果存储到 HttpServletResponse 对象中。

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
提取由数字数组指定的页面，保存为新的 Pdf 文件。

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
从输入文件中提取页面，保存为新的 Pdf 文件。

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
提取源文件中指定的页面并将结果存储到 HttpServletResponse 对象中。

### extract {#extract-java.lang.String-int:A-java.lang.String-}
提取由数字数组指定的页面，保存为新的 PDF 文件。

### extract {#extract-java.lang.String-int-int-java.lang.String-}
从输入文件中提取页面，保存为新的 Pdf 文件。

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

已弃用。此属性已弃用，不能用于抛出异常。

**Returns:**
布尔值

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

获取当操作结果以附件形式存储到 HttpServletResponse 对象时的附件名称。

**Returns:**
string 值

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

如果设置为 true，操作完成后流将被关闭。

**Returns:**
布尔值

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

当 UseDiskBuffer 设置为 true 时，在连接期间在进行新的增量更新之前已连接的文档数量。

**Returns:**
int 值

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

获取当操作结果存储到 HttpServletResponse 对象时内容的存储方式。

**Returns:**
ContentDisposition 元素

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

获取转换过程的日志。

**Returns:**
string 值

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

如果为 true，则在执行连接时复制文件的逻辑结构。

**Returns:**
布尔值

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

如果为 true，则复制大纲。

**Returns:**
布尔值

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

此属性定义在连接过程中遇到损坏文件时的行为。

**Returns:**
ConcatenateCorruptedFileAction 元素

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

执行连接时遇到的问题数组。

**Returns:**
PdfFileEditor.CorruptedItem 数组

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

表示在连接期间工作的内部进度事件处理器，并将内部连接阶段的事件转换为外部客户代码。

**Returns:**
ConcatenationProgressHandler 实例

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

如果为 true，则在连接期间进行增量更新。

**Returns:**
布尔值

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

如果为 true，则会从源文档复制操作。

**Returns:**
布尔值

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

如果为 true，则在合并表单时字段名称将被设为唯一。

**Returns:**
布尔值

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

获取最近一次发生的异常。

**Returns:**
java.lang.Exception 对象

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。

**Returns:**
布尔值

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

如果为 true，合并重复的大纲。

**Returns:**
布尔值

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

获取或设置优化标志。

**Returns:**
布尔值

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

如果源输入 PDF 文件已加密，则获取所有者密码。

**Returns:**
字符串对象

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

如果为 true，则将第一个文档的用户权限应用于连接后的文档。

**Returns:**
布尔值

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。

**Returns:**
布尔值

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取或设置当结果存储为 HttpServletResponse 时的保存选项。

**Returns:**
SaveOptions 对象

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

获取在合并表单时添加到字段名称以使其唯一的后缀格式。

**Returns:**
字符串对象

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
将文档插入到另一个文档中，并将结果存储到响应对象中。

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
将另一个文件的页面插入到输入 PDF 文件中。

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
将另一个文件的页面插入到输入 PDF 文件中。

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
将文件内容插入到源文件中，并将结果存储到 HttpServletResponse 对象中。

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
将另一个文件的页面插入到输入 PDF 文件中。

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
在指定位置将另一个文件的页面插入到 PDF 文件中。

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

有时 PDF 包含由多个相同的平铺背景图像并排放置而构成的页面或表格单元格的背景图像。

**Returns:**
布尔值

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。

**Returns:**
布尔值

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
从 InputStream 创建小册子并输出到 outputStream。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
从 firstInputStream 创建自定义小册子并输出到 outputStream。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
从输入流创建小册子并将结果保存到输出流。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
从 firstInputStream 创建小册子并输出到 outputStream。

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
从源文件制作小册子，并将结果存储到 HttpServletResponse 中。

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
从 PDF 文件制作小册子，并将其存储到 HttpServletResponse 中。

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
从源文件制作小册子，并将结果存储到 HttpServletResponse 对象中。

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
从源文件制作小册子，并将结果存储到 HttpServletResponse 对象中。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
从输入文件创建小册子并输出到输出文件。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
从 firstInputFile 创建自定义小册子并输出到 outputFile。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
从 inputFile 创建小册子并输出到 outputFile。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
从 firstInputFile 创建自定义小册子并输出到 outputFile。

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
制作 N-up 文档，并将结果存储到 HttpServletResponse 中。

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
制作 N-up 文档，并将结果存储到 HttpServletResponse 对象中。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
从输入流创建 N-Up 文档并将结果保存到输出流。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
从第一个输入流创建 N-Up 文档并输出到输出流。

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
从多个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
制作 N-up 文档，并将结果存储到 HttpServletResponse 中。

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
制作 N-up 文档，并将结果存储到 HttpServletResponse 对象中。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
从 firstInputFile 创建 N-Up 文档并输出到 outputFile。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
从输入文件创建 N-Up 文档并输出到 outputFile。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
调整文档页面的内容大小。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的内容大小。

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
调整文档中页面的内容大小。

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
调整文档中页面的内容大小。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
调整文档页面的内容大小。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档中页面的内容大小。

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
调整文档页面的内容大小。

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
调整文档页面的内容大小。

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

已弃用。此属性已弃用，不能用于抛出异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAttachmentName {#setAttachmentName-java.lang.String-}
设置附件的名称，当操作结果以附件形式存储到 HttpServletResponse 对象时使用。

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

如果设置为 true，操作完成后流将被关闭。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

当 UseDiskBuffer 设置为 true 时，在连接期间在进行新的增量更新之前已连接的文档数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpServletResponse 对象时内容的存储方式。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

如果为 true，则在执行连接时复制文件的逻辑结构。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

如果为 true，则复制大纲。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

此属性定义在连接过程中遇到损坏文件时的行为。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ConcatenateCorruptedFileAction 元素 |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
表示在连接期间工作的内部进度事件处理器，并将内部连接阶段的事件转换为外部客户代码。

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

如果为 true，则在连接期间进行增量更新。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

如果为 true，则会从源文档复制操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

如果为 true，则在合并表单时字段名称将被设为唯一。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

如果为 true，合并重复的大纲。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

获取或设置优化标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
如果源输入 Pdf 文件已加密，则设置所有者密码。

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

如果为 true，则将第一个文档的用户权限应用于连接后的文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
设置当结果存储为 HttpServletResponse 时的保存选项。

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

有时 PDF 包含由多个相同的平铺背景图像并排放置而构成的页面或表格单元格的背景图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | 布尔值 |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
设置在表单合并时添加到字段名称以使其唯一的后缀格式。

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
将文档从起始位置拆分到指定位置，并将结果存储到 HttpServletResponse 对象中。

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
从起始位置拆分到指定位置，并将前半部分保存到输出流中。

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
将文档从第一页拆分到指定位置，并将结果保存到 HttpServletResponse 对象中。

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
将 Pdf 文件从第一页拆分到指定位置，并将前半部分保存为新文件。

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
从指定位置拆分，并将后部保存到 HttpServletResponse 对象中。

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
从指定位置拆分，并将后半部分保存为新的文件流。

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
从指定位置拆分，并将后部保存到 HttpServletResponse 对象中。

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
从该位置拆分，并将后半部分保存为新文件。

### splitToPages {#splitToPages-java.io.InputStream-}
将 Pdf 文件拆分为单页文档。

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
将 Pdf 文件拆分为单页文档并保存到指定路径。

### splitToPages {#splitToPages-java.lang.String-}
将 PDF 文件拆分为单页文档。

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
将 Pdf 文件拆分为单页文档并保存到指定路径。
