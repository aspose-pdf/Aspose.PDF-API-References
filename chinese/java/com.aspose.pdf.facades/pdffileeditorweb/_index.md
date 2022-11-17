---
title: PdfFileEditorWeb
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 PdfFileEditorWeb 类
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, com.aspose.pdf.facades.APdfFileEditor

**所有已实现的接口：**
[com.aspose.pdf.facades.IPdfFileEditor](../../com.aspose.pdf.facades/ipdffileeditor)
```
public final class PdfFileEditorWeb extends APdfFileEditor implements IPdfFileEditor
```

表示 PdfFileEditorWeb 类

实现对PDF文件的操作：拼接、拆分、提取页面、制作小册子等。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileEditorWeb()](#PdfFileEditorWeb--) | PdfFileEditorWeb 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | 在文档页面中添加分页符。 |
| [addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | 在文档页面中添加分页符。 |
| [addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | 在文档页面中添加分页符。 |
| [addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | 在文档页面中添加分页符。 |
| [append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | 在 portStream 的 firstInputStream 末尾追加从 startPage 到 endPage 范围内的 portStream 中选择的页面。 |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-) | 添加从 portStreams 中的文档数组中选择的页面。 |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response)](#append-java.io.InputStream-java.io.InputStream---int-int-javax.servlet.http.HttpServletResponse-) | 将文档附加到源文档并将结果保存到响应对象中。 |
| [append(String inputFile, String portFile, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | 在 firstInputFile 末尾的 portFile 中追加从 startPage 到 endPage 范围内的 portFile 中选择的页面。 |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String---int-int-java.lang.String-) | 添加从 portFiles 文档中选择的页面。 |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response)](#append-java.lang.String-java.lang.String---int-int-javax.servlet.http.HttpServletResponse-) | 将文档附加到源文档并将结果保存到 HttpServletResponse 对象中。 |
| [concatenate(IDocument[] src, IDocument dest)](#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-) | 连接文档。 |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。 |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 连接两个文件。 |
| [concatenate(InputStream[] inputStream, OutputStream outputStream)](#concatenate-java.io.InputStream---java.io.OutputStream-) | 连接文件 |
| [concatenate(InputStream[] inputStream, HttpServletResponse response)](#concatenate-java.io.InputStream---javax.servlet.http.HttpServletResponse-) | 连接文件并将结果存储到 HttpServletResponse 对象中。 |
| [concatenate(String firstInputFile, String secInputFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | 连接两个文件。 |
| [concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。 |
| [concatenate(String[] inputFiles, String outputFile)](#concatenate-java.lang.String---java.lang.String-) | 将文件连接成一个文件。 |
| [concatenate(String[] inputFiles, HttpServletResponse response)](#concatenate-java.lang.String---javax.servlet.http.HttpServletResponse-) | 连接文件并将结果保存到 HttpResposnse 对象中。 |
| [delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#delete-java.io.InputStream-int---java.io.OutputStream-) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response)](#delete-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | 从文档中删除指定的页面并将结果保存到 HttpServletResponse 对象中。 |
| [delete(String inputFile, int[] pageNumber, String outputFile)](#delete-java.lang.String-int---java.lang.String-) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [delete(String inputFile, int[] pageNumber, HttpServletResponse response)](#delete-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | 从文档中删除指定的页面并将结果存储到 HttpServletResponse 对象中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | 提取由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response)](#extract-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | 从源文件中提取指定的页面并将结果存储到 HttpServletResponse 对象中。 |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | 提取由数字数组指定的页面，另存为新的 PDF 文件。 |
| [extract(String inputFile, int[] pageNumber, HttpServletResponse response)](#extract-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | 从源文件中提取指定的页面并将结果存储到 HttpServletResponse 对象中。 |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | 如果设置为 true，则在发生错误时抛出异常。 |
| [getAttachmentName()](#getAttachmentName--) | 当操作结果作为附件存储到 HttpServletResponse 对象时获取附件名称。 |
| [getClass()](#getClass--) |  |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | 如果设置为 true，流将在操作后关闭。 |
| [getConcatenationPacketSize()](#getConcatenationPacketSize--) | 当 UseDiskBuffer 设置为 true 时，在串联期间进行新的增量更新之前串联的文档数。 |
| [getContentDisposition()](#getContentDisposition--) | 获取当操作结果存储到 HttpServletResponse 对象时将如何存储内容。 |
| [getConversionLog()](#getConversionLog--) | 获取转换过程的日志。 |
| [getCopyLogicalStructure()](#getCopyLogicalStructure--) | 如果为真，则在执行连接时复制文件的逻辑结构。 |
| [getCopyOutlines()](#getCopyOutlines--) | 如果为真，则轮廓将被复制。 |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | 当连接进程遇到损坏的文件时，此属性定义行为。 |
| [getCorruptedItems()](#getCorruptedItems--) | 执行串联时遇到的问题数组。 |
| [getCustomProgressConcatenationHandler()](#getCustomProgressConcatenationHandler--) | 内部进度事件处理器的表示，它在级联期间工作，并将内部级联阶段的级联事件转换为外部客户的代码。 |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | 如果为真，则在串联期间进行增量更新。 |
| [getKeepActions()](#getKeepActions--) | 如果为真，将从源文档中复制操作。 |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | 如果为真，则在连接表单时字段名称将是唯一的。 |
| [getLastException()](#getLastException--) | 获取最后发生的异常。 |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | 如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。 |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | 如果为真，则合并重复的轮廓。 |
| [getOptimizeSize()](#getOptimizeSize--) | 获取或设置优化标志。 |
| [getOwnerPassword()](#getOwnerPassword--) | 如果源输入 Pdf 文件已加密，则获取所有者的密码。 |
| [getPreserveUserRights()](#getPreserveUserRights--) | 如果为真，则第一个文档的用户权限将应用于级联文档。 |
| [getRemoveSignatures()](#getRemoveSignatures--) | 如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。 |
| [getSaveOptions()](#getSaveOptions--) | 当结果存储为 HttpServletResponse 时获取或设置保存选项。 |
| [getUniqueSuffix()](#getUniqueSuffix--) | 获取添加到字段名称的后缀的格式，以使其在连接表单时唯一。 |
| [hashCode()](#hashCode--) |  |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response)](#insert-java.io.InputStream-int-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-) | 将文档插入其他文档并将结果存储到响应对象中。 |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 将其他文件的页面插入到 Pdf 文件的某个位置。 |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response)](#insert-java.lang.String-int-java.lang.String-int---javax.servlet.http.HttpServletResponse-) | 将文件内容插入源文件并将结果存储到 HttpServletResponse 对象中。 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [isUseDiskBuffer()](#isUseDiskBuffer--) | 如果使用此选项，则目标文档将定期保存在磁盘上，并且进一步的连接将作为增量更新应用于它。 |
| [makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-) | 从 PDF 文件制作小册子并将其存储到 HttpServletResponse 中。 |
| [makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response)](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 从源文件制作小册子并将结果存储到 HttpServletResponse 中。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream)](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | 从 InputStream 到 outputStream 制作小册子。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | 从输入流制作小册子并将结果保存到输出流中。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---) | 制作从 firstInputStream 到 outputStream 的小册子。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---) | 制作从 firstInputStream 到 outputStream 的自定义小册子。 |
| [makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-) | 从源文件制作小册子并将结果存储到 HttpServletResponse 对象中。 |
| [makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response)](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 从源文件制作小册子并将结果存储到 HttpServletResponse 对象中。 |
| [makeBooklet(String inputFile, String outputFile)](#makeBooklet-java.lang.String-java.lang.String-) | 从输入文件到输出文件制作小册子。 |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | 从 inputFile 到 outputFile 制作小册子。 |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-int---int---) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response)](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 制作 N-up 文档并将结果存储到 HttpServletResponse 对象中。 |
| [makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response)](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | 生成 N-up 文档并将结果存储到 HttpServletResponse 中。 |
| [makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 从两个输入 PDF 流制作 N-Up 文档到 outputStream。 |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | 从输入流制作 N-Up 文档并将结果保存到输出流中。 |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | 制作从第一个输入流到输出流的 N-Up 文档。 |
| [makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)](#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-) | 从多输入 PDF 流到 outputStream 制作 N-Up 文档。 |
| [makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response)](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | 制作 N-up 文档并将结果存储到 HttpServletResponse 对象中。 |
| [makeNUp(String inputFile, int x, int y, HttpServletResponse response)](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | 生成 N-up 文档并将结果存储到 HttpServletResponse 中。 |
| [makeNUp(String inputFile, String outputFile, int x, int y)](#makeNUp-java.lang.String-java.lang.String-int-int-) | 制作从第一个输入文件到输出文件的 N-Up 文档。 |
| [makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | 制作从输入文件到输出文件的 N-Up 文档。 |
| [makeNUp(String firstInputFile, String secondInputFile, String outputFile)](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | 从两个输入 PDF 文件到 outputFile 制作 N-Up 文档。 |
| [makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)](#makeNUp-java.lang.String---java.lang.String-boolean-) | 从多输入 PDF 文件到 outputFile 制作 N-Up 文档。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)](#resizeContents-com.aspose.ms.System.IO.Stream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | 调整文档中页面内容的大小。 |
| [resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面内容的大小。 |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)](#resizeContents-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | 调整文档中页面内容的大小。 |
| [resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档中页面内容的大小。 |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | 如果设置为 true，则在发生错误时抛出异常。 |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpServletResponse 对象时设置附件名称。 |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | 如果设置为 true，流将在操作后关闭。 |
| [setConcatenationPacketSize(int value)](#setConcatenationPacketSize-int-) | 当 UseDiskBuffer 设置为 true 时，在串联期间进行新的增量更新之前串联的文档数。 |
| [setContentDisposition(int value)](#setContentDisposition-int-) | 设置将操作结果存储到 HttpServletResponse 对象时如何存储内容。 |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setCopyLogicalStructure(boolean value)](#setCopyLogicalStructure-boolean-) | 如果为真，则在执行连接时复制文件的逻辑结构。 |
| [setCopyOutlines(boolean value)](#setCopyOutlines-boolean-) | 如果为真，则轮廓将被复制。 |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | 当连接进程遇到损坏的文件时，此属性定义行为。 |
| [setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | 内部进度事件处理器的表示，它在级联期间工作，并将内部级联阶段的级联事件转换为外部客户的代码。 |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | 如果为真，则在串联期间进行增量更新。 |
| [setKeepActions(boolean value)](#setKeepActions-boolean-) | 如果为真，将从源文档中复制操作。 |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | 如果为真，则在连接表单时字段名称将是唯一的。 |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) |  |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | 如果为真，则合并重复的轮廓。 |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | 获取或设置优化标志。 |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | 如果源输入 Pdf 文件已加密，则设置所有者的密码。 |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | 如果为真，则第一个文档的用户权限将应用于级联文档。 |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | 如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。 |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpServletResponse 时设置保存选项。 |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | 设置添加到字段名称的后缀的格式，以使其在连接表单时唯一。 |
| [setUseDiskBuffer(boolean value)](#setUseDiskBuffer-boolean-) | 如果使用此选项，则目标文档将定期保存在磁盘上，并且进一步的连接将作为增量更新应用于它。 |
| [splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | 从头开始拆分到指定位置，并将前面的部分保存在输出流中。 |
| [splitFromFirst(InputStream inputStream, int location, HttpServletResponse response)](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | 从开始到指定位置拆分文档并将结果存储到 HttpServletResponse 对象中。 |
| [splitFromFirst(String inputFile, int location, String outputFile)](#splitFromFirst-java.lang.String-int-java.lang.String-) | 将 Pdf 文件从第一页拆分到指定位置，并将前面的部分另存为新文件。 |
| [splitFromFirst(String inputFile, int location, HttpServletResponse response)](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | 将文档从第一页拆分到位置并将结果保存到 HttpServletResponse 对象中。 |
| [splitToBulks(InputStream inputStream, int[][] numberOfPage)](#splitToBulks-java.io.InputStream-int-----) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [splitToBulks(String inputFile, int[][] numberOfPage)](#splitToBulks-java.lang.String-int-----) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [splitToEnd(InputStream inputStream, int location, OutputStream outputStream)](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | 从指定位置拆分，将后面的部分另存为一个新的文件Stream。 |
| [splitToEnd(InputStream inputStream, int location, HttpServletResponse response)](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | 从指定位置拆分，将后面的部分保存到HttpServletResponse对象中。 |
| [splitToEnd(String inputFile, int location, String outputFile)](#splitToEnd-java.lang.String-int-java.lang.String-) | 从位置拆分，并将后面的部分另存为新文件。 |
| [splitToEnd(String inputFile, int location, HttpServletResponse response)](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | 从指定位置拆分，将后面的部分保存到HttpServletResponse对象中。 |
| [splitToPages(InputStream inputStream)](#splitToPages-java.io.InputStream-) | 将 Pdf 文件拆分为单页文档。 |
| [splitToPages(InputStream inputStream, String fileNameTemplate)](#splitToPages-java.io.InputStream-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [splitToPages(String inputFile)](#splitToPages-java.lang.String-) | 将 PDF 文件拆分为单页文档。 |
| [splitToPages(String inputFile, String fileNameTemplate)](#splitToPages-java.lang.String-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileEditorWeb() {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```


PdfFileEditorWeb 构造函数。

### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InputStream src = new FileInputStream("input.pdf", FileMode.Open);
  OutputStream dest = new FileOutputStream("output.pdf", FileMode.Create);
  fileEditor.addMargins(src, dest,
      //处理第 1、2、3 页
      new int[] { 1, 2, 3},
      //左边距为 10 个单位
      10,
      //右边距为 5 个单位
      5,
      //顶部边距为 5 个单位
      5,
      //底部边距为 5 个单位
      5);
      dest.Close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.io.InputStream | 包含源文档的流。 |
| destination | java.io.OutputStream | 将保存结果文档的流。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| leftMargin | double | 左边距。 |
| rightMargin | double | 右边距。 |
| topMargin | double | 上边距。 |
| bottomMargin | double | 底边距。 |

**退货：**
boolean - 如果操作成功则为真。
### addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMargins("input.pdf", "output.pdf",
      //处理第 1、2、3 页
      new int[] { 1, 2, 3},
      //左边距为 10 个单位
      10,
      //右边距为 5 个单位
      5,
      //顶部边距为 5 个单位
      5,
      //底部边距为 5 个单位
      5);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.lang.String | 源文档的路径。 |
| destination | java.lang.String | 保存结果文档的路径。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| leftMargin | double | 左边距。 |
| rightMargin | double | 右边距。 |
| topMargin | double | 上边距。 |
| bottomMargin | double | 底边距。 |

**退货：**
boolean - 如果调整大小成功则为真。
### addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以初始页面大小的百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InputStream src = new FileInputStream("input.pdf", FileMode.Open);
  OutputStream dest = new FileOutputStream("output.pdf", FileMode.Create);
  fileEditor.addMarginsPct(src, dest,
      //处理第 1、2、3 页
      new int[] { 1, 2, 3},
      //左边距是页面宽度的 15%
      15,
      //右边距是页面宽度的 10%
      10,
      //上边距是页面宽度的 20%
      20,
      //底部边距是页面宽度的 5%
      5);
      dest.Close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.io.InputStream | 包含源文档的流。 |
| destination | java.io.OutputStream | 将保存结果文档的流。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| leftMargin | double | 以初始页面大小的百分比表示的左边距。 |
| rightMargin | double | 以初始页面大小的百分比表示的右边距。 |
| topMargin | double | 以初始页面大小的百分比表示的上边距。 |
| bottomMargin | double | 以初始页面大小的百分比表示的下边距。 |

**退货：**
boolean - 如果动作执行成功则为真。
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以初始页面大小的百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMarginsPct("input.pdf", "output.pdf",
      //处理第 1、2、3 页
      new int[] { 1, 2, 3},
      //左边距是页面宽度的 15%
      15,
      //右边距是页面宽度的 10%
      10,
      //上边距是页面宽度的 20%
      20,
      //底部边距是页面宽度的 5%
      5);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.lang.String | 源文档的路径。 |
| destination | java.lang.String | 保存结果文档的路径。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| leftMargin | double | 以初始页面大小的百分比表示的左边距。 |
| rightMargin | double | 以初始页面大小的百分比表示的右边距。 |
| topMargin | double | 以初始页面大小的百分比表示的上边距。 |
| bottomMargin | double | 以初始页面大小的百分比表示的下边距。 |

**退货：**
布尔值 - 如果调整大小成功则为真
### addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)
```


在文档页面中添加分页符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | [Document](../../com.aspose.pdf/document) | 源文档。 |
| dest | [Document](../../com.aspose.pdf/document) | 目的地文件。 |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | 描述分页符位置的 PageBreak 对象数组。 |

### addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)
```


在文档页面中添加分页符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | [IDocument](../../com.aspose.pdf/idocument) | 源文档。 |
| dest | [IDocument](../../com.aspose.pdf/idocument) | 目的地文件。 |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | 描述分页符位置的 PageBreak 对象数组。 |

### addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)
```


在文档页面中添加分页符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | java.io.InputStream | 包含源文件的来源。 |
| dest | java.io.OutputStream | 将保存目标文档的源。 |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | 描述页面和将添加分页符的位置的 PageBreak 对象数组。 |

### addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)
```


在文档页面中添加分页符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | java.lang.String | 源文档的路径。 |
| dest | java.lang.String | 目标文档的路径。 |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | 描述页面和将添加分页符的位置的 PageBreak 对象数组。 |

### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


在 portStream 的 firstInputStream 末尾追加从 startPage 到 endPage 范围内的 portStream 中选择的页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1,  3, 5, "outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文件流。 |
| portStream | java.io.InputStream | 来自 Pdf 文件流的页面。 |
| startPage | int | 页面从 portFile Stream 开始。 |
| endPage | int | 页面以 portFile Stream 结束。 |
| outputStream | java.io.OutputStream | 输出 Pdf 文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


添加从 portStreams 中的文档数组中选择的页面。结果文档包括 firstInputFile 和 startPage 到 endPage 范围内的所有 portStreams 文档页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 Pdf 流。 |
| portStreams | java.io.InputStream[] | 要从中复制页面的文档。 |
| startPage | int | 页面在 portStreams 文件中开始。 |
| endPage | int | 页结束于 portStreams 文件。 |
| outputStream | java.io.OutputStream | 输出 Pdf 流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response) {#append-java.io.InputStream-java.io.InputStream---int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, HttpServletResponse response)
```


将文档附加到源文档并将结果保存到响应对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含源文档的流。 |
| portStreams | java.io.InputStream[] | 包含要附加文档的流数组。 |
| startPage | int | 附加页的起始页。 |
| endPage | int | 附加页的结束页。 |
| response | javax.servlet.http.HttpServletResponse | 将保存文档的响应对象。 |

**退货：**
boolean - 如果操作成功则为真。
### append(String inputFile, String portFile, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
```
public boolean append(String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


在 firstInputFile 末尾的 portFile 中追加从 startPage 到 endPage 范围内的 portFile 中选择的页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 Pdf 文件。 |
| portFile | java.lang.String | 来自 Pdf 文件的页面。 |
| startPage | int | 页面从 portFile 开始。 |
| endPage | int | 页面以 portFile 结尾。 |
| outputFile | java.lang.String | 输出 Pdf 文档。 |

**退货：**
boolean - 如果操作成功则为真。
### append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String---int-int-java.lang.String-}
```
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


添加从 portFiles 文档中选择的页面。结果文档包括 firstInputFile 和 startPage 到 endPage 范围内的所有 portFiles 文档页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", new String[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 Pdf 文件。 |
| portFiles | java.lang.String[] | 要从中复制页面的文档。 |
| startPage | int | 页面开始于 portFiles 文件。 |
| endPage | int | 页结束于 portFiles 文件。 |
| outputFile | java.lang.String | 输出 Pdf 文档。 |

**退货：**
boolean - 如果操作成功则为真。
### append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response) {#append-java.lang.String-java.lang.String---int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, HttpServletResponse response)
```


将文档附加到源文档并将结果保存到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 包含源文档的文件的名称。 |
| portFiles | java.lang.String[] | 包含附加文档的文件名数组 |
| startPage | int | 附加页的起始页。 |
| endPage | int | 附加页的结束页。 |
| response | javax.servlet.http.HttpServletResponse | 将保存文档的响应对象。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(IDocument[] src, IDocument dest) {#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-}
```
public boolean concatenate(IDocument[] src, IDocument dest)
```


连接文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | [IDocument\[\]](../../com.aspose.pdf/idocument) | 源文档数组。 |
| dest | [IDocument](../../com.aspose.pdf/idocument) | 目的地文件。 |

**退货：**
boolean - 如果连接成功则为真。
### concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)
```


将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。合并两个 Pdf 文档将生成包含页面的结果文档：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 InputStream blank = new FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new InputStream[] { stream1, stream2, blank } , outstream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | 第一个 Pdf 流。 |
| secInputStream | java.io.InputStream | 第二个 Pdf 流。 |
| blankPageStream | java.io.InputStream | 带有空白页的 Pdf 流 |
| outputStream | java.io.OutputStream | 输出 Pdf 流。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
```


连接两个文件。

\*

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Stream stream1 = new FileInputStream("file1.pdf", FileMode.Open, FileAccess.Read);
 Stream stream2 = new FileInputStream("file2.pdf", FileMode.Open, FileAccess.Read);
 Stream outstream = new FileInputStream("outfile.pdf", FileMode.Create, FileAccess.Write);
 fileEditor.concatenate(stream1, stream2, outstream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | 第一个文件的流。 |
| secInputStream | java.io.InputStream | 第二个文件的流。 |
| outputStream | java.io.OutputStream | 将存储结果文件的流。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(InputStream[] inputStream, OutputStream outputStream) {#concatenate-java.io.InputStream---java.io.OutputStream-}
```
public boolean concatenate(InputStream[] inputStream, OutputStream outputStream)
```


连接文件

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new InputStream[] { stream1, stream2 } , outstream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | 要连接的流数组。 |
| outputStream | java.io.OutputStream | 将存储结果文件的流。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(InputStream[] inputStream, HttpServletResponse response) {#concatenate-java.io.InputStream---javax.servlet.http.HttpServletResponse-}
```
public boolean concatenate(InputStream[] inputStream, HttpServletResponse response)
```


连接文件并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | 包含要连接的文件的流数组。 |
| response | javax.servlet.http.HttpServletResponse | 响应对象/ |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(String firstInputFile, String secInputFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean concatenate(String firstInputFile, String secInputFile, String outputFile)
```


连接两个文件。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | java.lang.String | 要连接的第一个文件。 |
| secInputFile | java.lang.String | 要连接的第二个文件。 |
| outputFile | java.lang.String | 输出文件。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)
```


将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。合并两个 Pdf 文档将生成包含页面的结果文档：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | java.lang.String | 第一个文件。 |
| secInputFile | java.lang.String | 第二个文件。 |
| blankPageFile | java.lang.String | 带有空白页的 PDF 文件。 |
| outputFile | java.lang.String | 结果文件。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(String[] inputFiles, String outputFile) {#concatenate-java.lang.String---java.lang.String-}
```
public boolean concatenate(String[] inputFiles, String outputFile)
```


将文件连接成一个文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate(new String[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | java.lang.String[] | 要连接的文件数组。 |
| outputFile | java.lang.String | 输出文件的名称。 |

**退货：**
boolean - 如果操作成功则为真。
### concatenate(String[] inputFiles, HttpServletResponse response) {#concatenate-java.lang.String---javax.servlet.http.HttpServletResponse-}
```
public boolean concatenate(String[] inputFiles, HttpServletResponse response)
```


连接文件并将结果保存到 HttpResposnse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | java.lang.String[] | 要连接的文件数组。 |
| response | javax.servlet.http.HttpServletResponse | 响应对象。 |

**退货：**
boolean - 如果连接成功则为 true。
### delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#delete-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.delete(inputStream, new int[] { 2, 3 }, outputStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文件流。 |
| pageNumber | int[] | 输入文件的页面索引。 |
| outputStream | java.io.OutputStream | 输出文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response) {#delete-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, HttpServletResponse response)
```


从文档中删除指定的页面并将结果保存到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| pageNumber | int[] | 将被删除的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse 对象 |

**退货：**
boolean - 如果操作成功则为真。
### delete(String inputFile, int[] pageNumber, String outputFile) {#delete-java.lang.String-int---java.lang.String-}
```
public boolean delete(String inputFile, int[] pageNumber, String outputFile)
```


从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件路径。 |
| pageNumber | int[] | 输入文件的页面索引。 |
| outputFile | java.lang.String | 输出文件路径。 |

**退货：**
boolean - 如果操作成功则为真。
### delete(String inputFile, int[] pageNumber, HttpServletResponse response) {#delete-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean delete(String inputFile, int[] pageNumber, HttpServletResponse response)
```


从文档中删除指定的页面并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件的路径。 |
| pageNumber | int[] | 必须删除的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果文档的响应对象。 |

**退货：**
boolean - 如果操作成功则为真。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
```


从输入文件中提取页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, 1, 3, 6, outStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文件流。 |
| startPage | int | 起始页码。 |
| endPage | int | 结束页码。 |
| outputStream | java.io.OutputStream | 输出 Pdf 文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#extract-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


提取由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文件流。 |
| pageNumber | int[] | 输入文件的页面索引。 |
| outputStream | java.io.OutputStream | 输出文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response) {#extract-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean extract(InputStream inputStream, int[] pageNumber, HttpServletResponse response)
```


从源文件中提取指定的页面并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| pageNumber | int[] | 将被提取的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### extract(String inputFile, int startPage, int endPage, String outputFile) {#extract-java.lang.String-int-int-java.lang.String-}
```
public boolean extract(String inputFile, int startPage, int endPage, String outputFile)
```


从输入文件中提取页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.extract("input.pdf", 3, 7, "output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 Pdf 文件路径。 |
| startPage | int | 起始页码。 |
| endPage | int | 结束页码。 |
| outputFile | java.lang.String | 输出 Pdf 文件路径。 |

**退货：**
boolean - True 表示成功，否则为 false。
### extract(String inputFile, int[] pageNumber, String outputFile) {#extract-java.lang.String-int---java.lang.String-}
```
public boolean extract(String inputFile, int[] pageNumber, String outputFile)
```


提取由数字数组指定的页面，另存为新的 PDF 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件路径。 |
| pageNumber | int[] | 输入文件的页面索引。 |
| outputFile | java.lang.String | 输出文件路径。 |

**退货：**
boolean - 如果操作成功则为真。
### extract(String inputFile, int[] pageNumber, HttpServletResponse response) {#extract-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean extract(String inputFile, int[] pageNumber, HttpServletResponse response)
```


从源文件中提取指定的页面并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件路径。 |
| pageNumber | int[] | 将被提取的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果成功提取页面则为真。
### getAllowConcatenateExceptions() {#getAllowConcatenateExceptions--}
```
public boolean getAllowConcatenateExceptions()
```


如果设置为 true，则在发生错误时抛出异常。否则不会抛出异常，如果失败则方法返回 false。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException ( true);
```

**退货：**
boolean - 布尔值
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


当操作结果作为附件存储到 HttpServletResponse 对象时获取附件名称。

**退货：**
java.lang.字符串
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```


如果设置为 true，流将在操作后关闭。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setCloseConcatenatedStreams ( true);
```

**退货：**
boolean - 布尔值
### getConcatenationPacketSize() {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```


当 UseDiskBuffer 设置为 true 时，在串联期间进行新的增量更新之前串联的文档数。

**退货：**
int - 整数值
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


获取当操作结果存储到 HttpServletResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**退货：**
整数
### getConversionLog() {#getConversionLog--}
```
public String getConversionLog()
```


获取转换过程的日志。

**退货：**
java.lang.字符串
### getCopyLogicalStructure() {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```


如果为真，则在执行连接时复制文件的逻辑结构。

**退货：**
boolean - 布尔值
### getCopyOutlines() {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```


如果为真，则轮廓将被复制。

**退货：**
boolean - 布尔值
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```


当连接进程遇到损坏的文件时，此属性定义行为。可能的值是：StopWithError 和 ConcatenateIgnoringCorrupted。

**退货：**
int - ConcatenateCorruptedFileAction 元素
### getCorruptedItems() {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem[] getCorruptedItems()
```


执行串联时遇到的问题数组。对于传递给 Concatenate() 函数的每个损坏文档，都会创建新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才可以使用此属性。

--------------------

```
//连接文档并显示有关损坏文档的信息
 PdfFileEditor pfe = new PdfFileEditor();
 pfe.setCorruptedFileAction( PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted);
 ```
如果 (pfe.getCorruptedItems().length >0)
```
 {
 for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems())
 {
 System.out.println(item.getIndex() + " reason: " + item.getException());
 }
 }
```

**退货：**
com.aspose.pdf.facades.PdfFileEditor.CorruptedItem[] - PdfFileEditor.CorruptedItem 数组
### getCustomProgressConcatenationHandler() {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```


内部进度事件处理器的表示，它在级联期间工作，并将内部级联阶段的级联事件转换为外部客户的代码。该字段使用不同类型的事件。

简单串联有 8 个事件：
1)复制所有页面
2)DocumentEmbedded文件
3)文件表格
4)文件大纲
5)文档JavaScript
6)文档逻辑结构
7)文件合并。
8) 总百分比。

并行连接通知每个页面连接并有 3 个事件：
1)PageConcatenated
2）空白页
3)总百分比

**退货：**
[ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) ConcatenationProgressHandler 实例
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```


如果为真，则在串联期间进行增量更新。

**退货：**
boolean - 布尔值
### getKeepActions() {#getKeepActions--}
```
public final boolean getKeepActions()
```


如果为真，将从源文档中复制操作。默认值：true。

**退货：**
boolean - 布尔值
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```


如果为真，则在连接表单时字段名称将是唯一的。后缀将添加到字段名称中，后缀模板可以在 UniqueSuffix 属性中指定。

**退货：**
boolean - 布尔值
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


获取最后发生的异常。可用于检查失败原因。

```
PdfFileEditor pfe = new PdfFileEditor();
  if (!pfe.tryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
  {
     System.out.println("Error occured:");
     if (pfe.getLastException() != null)
     {
         System.out.println((pfe.getLastException().getMessage());
         if (pfe.getLastException().getInnerException() != null)
             System.out.println((pfe.getLastException().getInnerException().getMessage());
     }
  }
```

**退货：**
java.lang.RuntimeException 异常
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```


如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。否则，具有相同名称的图层将在生成的文档中另存为不同的图层。

**退货：**
布尔值
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```


如果为真，则合并重复的轮廓。

**退货：**
boolean - 布尔值
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


获取或设置优化标志。如果设置此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**退货：**
boolean - 布尔值
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


如果源输入 Pdf 文件已加密，则获取所有者的密码。此属性尚未实现。

**退货：**
java.lang.String - 字符串对象
### getPreserveUserRights() {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```


如果为真，则第一个文档的用户权限将应用于级联文档。所有其他文档的用户权限都将被忽略。

**退货：**
boolean - 布尔值
### getRemoveSignatures() {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```


如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。

**退货：**
boolean - 布尔值
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


当结果存储为 HttpServletResponse 时获取或设置保存选项。默认值：PdfSaveOptions。

**退货：**
[SaveOptions](../../com.aspose.pdf/saveoptions)
### getUniqueSuffix() {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```


获取添加到字段名称的后缀的格式，以使其在连接表单时唯一。此字符串必须包含 %NUM% 子字符串，该子字符串将被替换为数字。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段“fieldName”的名称将是：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

**退货：**
java.lang.String - 字符串对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


将其他文件的页面插入到输入 Pdf 文件中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | Pdf 文件的输入流。 |
| insertLocation | int | 输入文件中的插入位置。 |
| portStream | java.io.InputStream | 页面的 Pdf 文件流。 |
| startPage | int | 从哪一页开始。 |
| endPage | int | 到哪一页结束。 |
| outputStream | java.io.OutputStream | 输出流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


将其他文件的页面插入到输入 Pdf 文件中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | Pdf 文件的输入流。 |
| insertLocation | int | 输入文件中的插入位置。 |
| portStream | java.io.InputStream | 页面的 Pdf 文件流。 |
| pageNumber | int[] | portFile 中移植的页码。 |
| outputStream | java.io.OutputStream | 输出流。 |

**退货：**
boolean - 如果操作成功则为真。
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response) {#insert-java.io.InputStream-int-java.io.InputStream-int---javax.servlet.http.HttpServletResponse-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, HttpServletResponse response)
```


将文档插入其他文档并将结果存储到响应对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 流式传输源文档 |
| insertLocation | int | 将插入其他文档的位置。 |
| portStream | java.io.InputStream | 要插入的文档。 |
| pageNumber | int[] | 将插入的第二个文档中的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的响应对象。 |

**退货：**
boolean - 如果操作成功则为真。
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


将其他文件的页面插入到 Pdf 文件的某个位置。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 Pdf 文件。 |
| insertLocation | int | 输入文件中的位置。 |
| portFile | java.lang.String | 移植 Pdf 文件。 |
| startPage | int | portFile 中的起始位置。 |
| endPage | int | portFile 中的结束位置。 |
| outputFile | java.lang.String | 输出 Pdf 文件。 |

**退货：**
boolean - True 表示成功，否则为 false。
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


将其他文件的页面插入到输入 Pdf 文件中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 Pdf 文件。 |
| insertLocation | int | 输入文件中的插入位置。 |
| portFile | java.lang.String | Pdf 文件中的页面。 |
| pageNumber | int[] | portFile 中移植的页码。 |
| outputFile | java.lang.String | 输出 Pdf 文件。 |

**退货：**
boolean - True 表示成功，否则为 false。
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response) {#insert-java.lang.String-int-java.lang.String-int---javax.servlet.http.HttpServletResponse-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, HttpServletResponse response)
```


将文件内容插入源文件并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件名。 |
| insertLocation | int | 将插入第二个文件的页码。 |
| portFile | java.lang.String | 将被插入的文件的路径。 |
| pageNumber | int[] | 将插入源文件中的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的响应对象。 |

**退货：**
布尔值 - true 表示插入成功。
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**退货：**
boolean - 布尔值
### isUseDiskBuffer() {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```


如果使用此选项，则目标文档将定期保存在磁盘上，并且进一步的连接将作为增量更新应用于它。

**退货：**
boolean - 布尔值
### makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response) {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(InputStream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)
```


从 PDF 文件制作小册子并将其存储到 HttpServletResponse 中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文档流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 所需的页面大小。 |
| leftPages | int[] | 将放置在左侧的页码数组。 |
| rightPages | int[] | 将放置在右侧的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response) {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(InputStream inputStream, PageSize pageSize, HttpServletResponse response)
```


从源文件制作小册子并将结果存储到 HttpServletResponse 中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文档流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出文件中所需的页面大小。 |
| response | javax.servlet.http.HttpServletResponse | 将保存结果的 Respose 对象。 |

**退货：**
boolean - 如果小册子构建成功则为真。
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream)
```


从 InputStream 到 outputStream 制作小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 pdf 流。 |
| outputStream | java.io.OutputStream | 输出pdf流。 |

**退货：**
boolean - 如果操作成功则为真。
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


从输入流制作小册子并将结果保存到输出流中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 PDF 流。 |
| outputStream | java.io.OutputStream | 输出pdf流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出 pdf 文件的页面大小。 |

**退货：**
boolean - 如果操作成功则为真。
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)
```


制作从 firstInputStream 到 outputStream 的小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| outputStream | java.io.OutputStream | 输出pdf流。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出 pdf 文件的页面大小。 |
| leftPages | int[] | 左边的页面。 |
| rightPages | int[] | 正确的页面。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)
```


制作从 firstInputStream 到 outputStream 的自定义小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| outputStream | java.io.OutputStream | 输出pdf流。 |
| leftPages | int[] | 左边的页面。 |
| rightPages | int[] | 正确的页面。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response) {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int---int---javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(String inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, HttpServletResponse response)
```


从源文件制作小册子并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件路径。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 所需的页面大小。 |
| leftPages | int[] | 要放置在左侧的页码数组。 |
| rightPages | int[] | 要放在右边的页码数组。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response) {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeBooklet(String inputFile, PageSize pageSize, HttpServletResponse response)
```


从源文件制作小册子并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件路径。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出文件中所需的页面大小。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
public boolean makeBooklet(String inputFile, String outputFile)
```


从输入文件到输出文件制作小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 pdf 文件路径和名称。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize)
```


从 inputFile 到 outputFile 制作小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 pdf 文件路径和名称。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出 pdf 文件的页面大小。 |

**退货：**
boolean - 如果操作成功则为真。
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)
```


制作从 firstInputFile 到 outputFile 的自定义小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出 pdf 文件的页面大小。 |
| leftPages | int[] | 左边的页面。 |
| rightPages | int[] | 正确的页面。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)
```


制作从 firstInputFile 到 outputFile 的自定义小册子。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| leftPages | int[] | 小册子的左页。 |
| rightPages | int[] | 小册子的右页。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response) {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(InputStream inputStream, int x, int y, PageSize pageSize, HttpServletResponse response)
```


制作 N-up 文档并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| x | int | 列数。 |
| y | int | 行数。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 结果文件中的页面大小。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response) {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(InputStream inputStream, int x, int y, HttpServletResponse response)
```


生成 N-up 文档并将结果存储到 HttpServletResponse 中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文档流。 |
| x | int | 列数。 |
| y | int | 行数。 |
| response | javax.servlet.http.HttpServletResponse | 存储结果的 HttpServletResponse。 |

**退货：**
boolean - 如果操作成功则为真。
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
```


从两个输入 PDF 流制作 N-Up 文档到 outputStream。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream input1 = new FileInputStream("input1.pdf");
 InputStream input2 = new FileInputStream("input2.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(input1, input2, output);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | 第一个输入流。 |
| secondInputStream | java.io.InputStream | 第二个输入流。 |
| outputStream | java.io.OutputStream | 输出 pdf 流。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)
```


从输入流制作 N-Up 文档并将结果保存到输出流中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 pdf 流。 |
| outputStream | java.io.OutputStream | 输出 pdf 流。 |
| x | int | 列数。 |
| y | int | 行数。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


制作从第一个输入流到输出流的 N-Up 文档。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 pdf 流。 |
| outputStream | java.io.OutputStream | 输出 pdf 流。 |
| x | int | 列数。 |
| y | int | 行数。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出 pdf 文件的页面大小。 |

**退货：**
boolean - 如果操作成功则为真。
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
public boolean makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


从多输入 PDF 流到 outputStream 制作 N-Up 文档。 outputStream 的每一页将包含多个页面，这些页面与相同页码的输入流中的页面组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则多页垂直堆叠。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("input1.pdf");
 InputStream stream2 = new FileInputStream("input2.pdf");
 InputStream stream3 = new FileInputStream("input3.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | 输入 Pdf 流。 |
| outputStream | java.io.OutputStream | 输出 pdf 流。 |
| isSidewise | boolean | 堆积方式，水平为真，垂直为假 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response) {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(String inputFile, int x, int y, PageSize pageSize, HttpServletResponse response)
```


制作 N-up 文档并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件的路径。 |
| x | int | 列数。 |
| y | int | 行数。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 结果文件中的页面大小。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### makeNUp(String inputFile, int x, int y, HttpServletResponse response) {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
```
public boolean makeNUp(String inputFile, int x, int y, HttpServletResponse response)
```


生成 N-up 文档并将结果存储到 HttpServletResponse 中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件名。 |
| x | int | 列数。 |
| y | int | 行数。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y)
```


制作从第一个输入文件到输出文件的 N-Up 文档。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 pdf 文件路径和名称。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| x | int | 列数。 |
| y | int | 行数。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


制作从输入文件到输出文件的 N-Up 文档。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 pdf 文件路径和名称。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| x | int | 列数。 |
| y | int | 行数。 |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出 pdf 文件的页面大小。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean makeNUp(String firstInputFile, String secondInputFile, String outputFile)
```


从两个输入 PDF 文件到 outputFile 制作 N-Up 文档。 outputFile 的每一页将包含两页，一页来自第一个输入文件，另一页来自第二个输入文件。两页水平堆叠。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | java.lang.String | 第一个输入文件。 |
| secondInputFile | java.lang.String | 第二个输入文件。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
public boolean makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)
```


从多输入 PDF 文件到 outputFile 制作 N-Up 文档。 outputFile 的每一页将包含多个页面，这些页面与相同页码的输入文件中的页面组合。如果 isSidewise 为真，则多页水平堆叠；如果 isSidewise 为假，则多页垂直堆叠。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | java.lang.String[] | 输入 Pdf 文件。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| isSidewise | boolean | 堆积方式，水平为真，垂直为假。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response) {#resizeContents-com.aspose.ms.System.IO.Stream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
```
public boolean resizeContents(System.IO.Stream source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)
```


调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | com.aspose.ms.System.IO.Stream | 源文件流。 |
| pages | int[] | 要调整大小的页面数组。 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | 调整参数。 |
| response | javax.servlet.http.HttpServletResponse | 保存结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)
```


调整文档页面的大小。在缩小的页面周围添加空白页边距。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Document src = new Document("input.pdf");
 Document dest = new Document();
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //左边距 = 页面宽度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
     null,
     //右边距是页面的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //上边距 = 高度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容高度自动计算（类似于宽度）
     null,
     //底部保证金为 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, parameters);
 dest.save("output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | 源文档。 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | 调整参数。 |

### resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


调整文档页面的大小。在缩小的页面周围添加空白页边距。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Document doc = new Document("input.pdf");
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //左边距 = 页面宽度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
     null,
     //右边距是页面的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //上边距 = 高度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容高度自动计算（类似于宽度）
     null,
     //底部保证金为 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, new int[] { 1, 2,.3}, parameters);
 doc.save("output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | 源文档。 |
| pages | int[] | 页面索引列表。 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | 调整参数。 |

### resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


调整文档页面内容的大小。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new fileOutputStream("output.pdf");
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
 //左边距 = 页面宽度的 10%
 PdfFileEditor.ContentsResizeValue.percents(10),
 //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
 null,
 //右边距是页面的 10%
 PdfFileEditor.ContentsResizeValue.percents(10),
 //上边距 = 高度的 10%
 PdfFileEditor.ContentsResizeValue.percents(10),
 //新内容高度自动计算（类似于宽度）
 null,
 //底部保证金为 10%
 PdfFileEditor.ContentsResizeValue.percents(10)
 );
 fileEditor.resizeContents(src, dest, new int[] { 1, 2, 3}, parameters);
 dest.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.io.InputStream | 流式传输源文档。 |
| destination | java.io.OutputStream | 与目标文档一起流式传输。 |
| pages | int[] | 页面索引数组。 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | 调整参数。 |

**退货：**
boolean - 如果成功则返回 true。
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。内容的新大小以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents(src, dest,
 //调整文档所有页面的大小
 null,
 //新内容宽度 = 200
 200,
 //新内容高度 = 300
 300);
 //页面的其余区域将为空
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.io.InputStream | 包含源文档的流。 |
| destination | java.io.OutputStream | 将保存结果文档的流。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| newWidth | double | 默认空间单位中页面内容的新宽度。 |
| newHeight | double | 默认空间单位中页面内容的新高度。 |

**退货：**
boolean - 如果调整大小成功则为真。
### resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response) {#resizeContents-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
```
public boolean resizeContents(String source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters, HttpServletResponse response)
```


调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.lang.String | 源文件的路径。 |
| pages | int[] | 要调整大小的页面数组。 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | 调整参数。 |
| response | javax.servlet.http.HttpServletResponse | 保存结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


调整文档中页面内容的大小。如果页面缩小，则会在页面周围添加空白页边距。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //左边距 = 页面宽度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
     null,
     //右边距是页面的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //上边距 = 高度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容高度自动计算（类似于宽度）
     null,
     //底部保证金为 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2,.3}, parameters);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.lang.String | 源文档路径。 |
| destination | java.lang.String | 目标文档路径。 |
| pages | int[] | 页面索引数组（页面索引从 1 开始）。 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | 页面调整大小的参数。 |

**退货：**
boolean - 如果调整大小成功则为真。
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。内容的新大小以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf",
 //调整文档所有页面的大小
 null,
 //新内容宽度 = 200
 200,
 //新内容高度 = 300
 300);
 //页面的其余区域将为空
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.lang.String | 源文档的路径。 |
| destination | java.lang.String | 保存结果文档的路径。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| newWidth | double | 默认空间单位中页面内容的新宽度。 |
| newHeight | double | 默认空间单位中页面内容的新高度。 |

**退货：**
boolean - 如果调整大小成功则为真。
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。新内容大小以百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct(src, dest,
 //调整文档所有页面的大小
 null,
 //新内容宽度 = 初始大小的 60%
 60,
 //新内容高度 = 初始大小的 60%
 60);
 //页面的其余区域将为空（页边距）。左右边距的大小为 (100% - 60%) / 2 = 20%
 //顶部和底部边距相同。
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.io.InputStream | 包含源文档的流。 |
| destination | java.io.OutputStream | 将保存结果文档的流。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| newWidth | double | 以百分比表示的页面内容的新宽度。 |
| newHeight | double | 以百分比表示的页面内容的新高度。 |

**退货：**
boolean - 如果调整大小成功则为真。
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。新内容大小以百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizePct("input.pdf", "output.pdf",
 //调整文档所有页面的大小
 null,
 //新内容宽度 = 初始大小的 60%
 60,
 //新内容高度 = 初始大小的 60%
 60);
 //页面的其余区域将为空（页边距）。左右边距的大小为 (100% - 60%) / 2 = 20%
 //顶部和底部边距相同。
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | java.lang.String | 源文档的路径。 |
| destination | java.lang.String | 保存结果文档的路径。 |
| pages | int[] | 页面索引数组。如果为空，则将处理所有文档页面。 |
| newWidth | double | 以百分比表示的页面内容的新宽度。 |
| newHeight | double | 以百分比表示的页面内容的新高度。 |

**退货：**
boolean - 如果调整大小成功则为真。
### resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)
```


调整文档页面的大小。在缩小的页面周围添加空白页边距。规范化有助于避免未分组的已保存内容状态的意外行为。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | 文档实例 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters 实例 |

### resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


调整文档页面的大小。在缩小的页面周围添加空白页边距。规范化有助于避免未分组的已保存内容状态的意外行为。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | 文档实例 |
| pages | int[] | 整数值数组 |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters 实例 |

### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public void setAllowConcatenateExceptions(boolean value)
```


如果设置为 true，则在发生错误时抛出异常。否则不会抛出异常，如果失败，方法将返回 false。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException ( true);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


当操作结果作为附件存储到 HttpServletResponse 对象时设置附件名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```


如果设置为 true，流将在操作后关闭。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setCloseConcatenatedStreams ( true);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setConcatenationPacketSize(int value) {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```


当 UseDiskBuffer 设置为 true 时，在串联期间进行新的增量更新之前串联的文档数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


设置将操作结果存储到 HttpServletResponse 对象时如何存储内容。可能的值：内联/附件。默认值：内联。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存而不进行转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素 |

### setCopyLogicalStructure(boolean value) {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```


如果为真，则在执行连接时复制文件的逻辑结构。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCopyOutlines(boolean value) {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```


如果为真，则轮廓将被复制。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```


当连接进程遇到损坏的文件时，此属性定义行为。可能的值是：StopWithError 和 ConcatenateIgnoringCorrupted。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ConcatenateCorruptedFileAction 元素 |

### setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler) {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
```
public void setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)
```


内部进度事件处理器的表示，它在级联期间工作，并将内部级联阶段的级联事件转换为外部客户的代码。该字段使用不同类型的事件。

简单串联有 8 个事件：
1)复制所有页面
2)DocumentEmbedded文件
3)文件表格
4)文件大纲
5)文档JavaScript
6)文档逻辑结构
7)文件合并。
8) 总百分比。

并行连接通知每个页面连接并有 3 个事件：
1)PageConcatenated
2）空白页
3)总百分比

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| customProgressConcatenationHandler | [ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) | ConcatenationProgressHandler 实例 |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```


如果为真，则在串联期间进行增量更新。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeepActions(boolean value) {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```


如果为真，将从源文档中复制操作。默认值：true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```


如果为真，则在连接表单时字段名称将是唯一的。后缀将添加到字段名称中，后缀模板可以在 UniqueSuffix 属性中指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```


如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。否则，具有相同名称的图层将在生成的文档中另存为不同的图层。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```


如果为真，则合并重复的轮廓。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


获取或设置优化标志。如果设置此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


如果源输入 Pdf 文件已加密，则设置所有者的密码。此属性尚未实现。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```


如果为真，则第一个文档的用户权限将应用于级联文档。所有其他文档的用户权限都将被忽略。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```


如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


当结果存储为 HttpServletResponse 时设置保存选项。默认值：PdfSaveOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。在这种情况下，目标格式的渲染器（DOCS 格式的 fe MsWord）有时会在背景图像的各个部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果看起来导出的文档包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不需要的效果。注意力！这种质量优化通常会减慢转换速度，因此请仅在确实需要时才使用此选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | 布尔值 |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public void setUniqueSuffix(String value)
```


设置添加到字段名称的后缀的格式，以使其在连接表单时唯一。此字符串必须包含 %NUM% 子字符串，该子字符串将被替换为数字。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段“fieldName”的名称将是：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

--------------------

```
PdfFileEditor ed = new PdfFileEditor();
   ed.setUniqueSuffix ( "_%NUM%");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setUseDiskBuffer(boolean value) {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```


如果使用此选项，则目标文档将定期保存在磁盘上，并且进一步的连接将作为增量更新应用于它。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)
```


从头开始拆分到指定位置，并将前面的部分保存在输出流中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitFromFirst(sourceStream, 5, outStream);
```

--------------------

在此操作后，流不会关闭。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源 Pdf 文件流。 |
| location | int | 分裂点。 |
| outputStream | java.io.OutputStream | 输出文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### splitFromFirst(InputStream inputStream, int location, HttpServletResponse response) {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitFromFirst(InputStream inputStream, int location, HttpServletResponse response)
```


从开始到指定位置拆分文档并将结果存储到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| location | int | 分裂点。 |
| response | javax.servlet.http.HttpServletResponse | 将存储结果的 HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public boolean splitFromFirst(String inputFile, int location, String outputFile)
```


将 Pdf 文件从第一页拆分到指定位置，并将前面的部分另存为新文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitFromFirst("input.pdf", 5, "out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源 Pdf 文件。 |
| location | int | 分裂点。 |
| outputFile | java.lang.String | 输出 Pdf 文件。 |

**退货：**
boolean - True 表示成功，否则为 false。
### splitFromFirst(String inputFile, int location, HttpServletResponse response) {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitFromFirst(String inputFile, int location, HttpServletResponse response)
```


将文档从第一页拆分到位置并将结果保存到 HttpServletResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件名。 |
| location | int | 分割点。 |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
public ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] numberOfPage)
```


将 Pdf 文件拆分为多个文档。文档可以是单页或多页。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 PDF 流。 |
| numberOfPage | int[][] | 每个文档的起始页和结束页。 |

**退货：**
java.io.ByteArrayInputStream[] - 输出PDF流，每个流缓冲一个PDF文档。
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
public ByteArrayInputStream[] splitToBulks(String inputFile, int[][] numberOfPage)
```


将 Pdf 文件拆分为多个文档。文档可以是单页或多页。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 PDF 文件。 |
| numberOfPage | int[][] | 包含 double 元素数组的数组，即文档的起始页和结束页。 |

**退货：**
java.io.ByteArrayInputStream[] - 输出PDF流，每个流缓冲一个PDF文档。
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitToEnd(InputStream inputStream, int location, OutputStream outputStream)
```


从指定位置拆分，将后面的部分另存为一个新的文件Stream。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitToEnd(sourceStream, 5, outStream);
```

--------------------

除非指定 CloseConcatedStreams，否则在此操作后不会关闭流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源 Pdf 文件流。 |
| location | int | 分裂的位置。 |
| outputStream | java.io.OutputStream | 输出 Pdf 文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
### splitToEnd(InputStream inputStream, int location, HttpServletResponse response) {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitToEnd(InputStream inputStream, int location, HttpServletResponse response)
```


从指定位置拆分，将后面的部分保存到HttpServletResponse对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| location | int | 分割点。 |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse 对象。 |

**退货：**
boolean - 如果拆分成功则为 true。
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public boolean splitToEnd(String inputFile, int location, String outputFile)
```


从位置拆分，并将后面的部分另存为新文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitToEnd("input.pdf", 5, "out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源 Pdf 文件。 |
| location | int | 分裂的位置。 |
| outputFile | java.lang.String | 输出 Pdf 文件路径。 |

**退货：**
boolean - True 表示成功，否则为 false。
### splitToEnd(String inputFile, int location, HttpServletResponse response) {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
```
public boolean splitToEnd(String inputFile, int location, HttpServletResponse response)
```


从指定位置拆分，将后面的部分保存到HttpServletResponse对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件名。 |
| location | int | 分割点。 |
| response | javax.servlet.http.HttpServletResponse | HttpServletResponse 对象。 |

**退货：**
boolean - 如果操作成功则为真。
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
public ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


将 Pdf 文件拆分为单页文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 Pdf 流。 |

**退货：**
java.io.ByteArrayInputStream[] - 包含文档页面的内存流数组。
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public void splitToPages(InputStream inputStream, String fileNameTemplate)
```


将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| fileNameTemplate | java.lang.String | 结果文件名的模板。必须包含替换为页码的 %NUM%。例如，如果指定了 c:/dir/page%NUM%.pdf，则生成的文件将具有以下名称：c:/dir/page1.pdf、c:/dir/page2.pdf 等。 |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
public ByteArrayInputStream[] splitToPages(String inputFile)
```


将 PDF 文件拆分为单页文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入 PDF 文件名。 |

**退货：**
java.io.ByteArrayInputStream[] - 输出 PDF 流，每个流缓冲一个单页 PDF 文档。
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public void splitToPages(String inputFile, String fileNameTemplate)
```


将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件名。 |
| fileNameTemplate | java.lang.String | 结果文件名的模板。必须包含替换为页码的 %NUM%。例如，如果指定了 c:/dir/page%NUM%.pdf，则生成的文件将具有以下名称：c:/dir/page1.pdf、c:/dir/page2.pdf 等。 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
