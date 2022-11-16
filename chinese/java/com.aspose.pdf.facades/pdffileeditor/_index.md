---
title: PdfFileEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 实现PDF文件拼接拆分提取页面制作小册子等操作。
type: docs
weight: 39
url: /zh/java/com.aspose.pdf.facades/pdffileeditor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, com.aspose.pdf.facades.APdfFileEditor

**所有已实现的接口：**
[com.aspose.pdf.facades.IPdfFileEditor](../../com.aspose.pdf.facades/ipdffileeditor)
```
public final class PdfFileEditor extends APdfFileEditor implements IPdfFileEditor
```

实现对PDF文件的操作：拼接、拆分、提取页面、制作小册子等。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileEditor()](#PdfFileEditor--) | PdfFileEditor 构造函数。 |
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
| [append(String inputFile, String portFile, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | 在 firstInputFile 末尾的 portFile 中追加从 startPage 到 endPage 范围内的 portFile 中选择的页面。 |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String---int-int-java.lang.String-) | 添加从 portFiles 文档中选择的页面。 |
| [concatenate(IDocument[] src, IDocument dest)](#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-) | 连接文档。 |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。 |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 连接两个文件。 |
| [concatenate(InputStream[] inputStream, OutputStream outputStream)](#concatenate-java.io.InputStream---java.io.OutputStream-) | 连接文件 |
| [concatenate(String firstInputFile, String secInputFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | 连接两个文件。 |
| [concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。 |
| [concatenate(String[] inputFiles, String outputFile)](#concatenate-java.lang.String---java.lang.String-) | 将文件连接成一个文件。 |
| [delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#delete-java.io.InputStream-int---java.io.OutputStream-) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [delete(String inputFile, int[] pageNumber, String outputFile)](#delete-java.lang.String-int---java.lang.String-) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | 提取由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | 提取由数字数组指定的页面，另存为新的 PDF 文件。 |
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
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 将其他文件的页面插入到 Pdf 文件的某个位置。 |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含（页面或表格单元格的）背景图像，这些背景图像由多个相同的平铺背景图像构成，并且彼此相邻。 |
| [isUseDiskBuffer()](#isUseDiskBuffer--) | 如果使用此选项，则目标文档将定期保存在磁盘上，并且进一步的连接将作为增量更新应用于它。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream)](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | 从 InputStream 到 outputStream 制作小册子。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | 从输入流制作小册子并将结果保存到输出流中。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---) | 制作从 firstInputStream 到 outputStream 的小册子。 |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---) | 制作从 firstInputStream 到 outputStream 的自定义小册子。 |
| [makeBooklet(String inputFile, String outputFile)](#makeBooklet-java.lang.String-java.lang.String-) | 从输入文件到输出文件制作小册子。 |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | 从 inputFile 到 outputFile 制作小册子。 |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-int---int---) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 从两个输入 PDF 流制作 N-Up 文档到 outputStream。 |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | 从输入流制作 N-Up 文档并将结果保存到输出流中。 |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | 制作从第一个输入流到输出流的 N-Up 文档。 |
| [makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)](#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-) | 从多输入 PDF 流到 outputStream 制作 N-Up 文档。 |
| [makeNUp(String inputFile, String outputFile, int x, int y)](#makeNUp-java.lang.String-java.lang.String-int-int-) | 制作从第一个输入文件到输出文件的 N-Up 文档。 |
| [makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | 制作从输入文件到输出文件的 N-Up 文档。 |
| [makeNUp(String firstInputFile, String secondInputFile, String outputFile)](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | 从两个输入 PDF 文件到 outputFile 制作 N-Up 文档。 |
| [makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)](#makeNUp-java.lang.String---java.lang.String-boolean-) | 从多输入 PDF 文件到 outputFile 制作 N-Up 文档。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面内容的大小。 |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | 调整文档页面内容的大小。 |
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
| [splitFromFirst(String inputFile, int location, String outputFile)](#splitFromFirst-java.lang.String-int-java.lang.String-) | 将 Pdf 文件从第一页拆分到指定位置，并将前面的部分另存为新文件。 |
| [splitToBulks(InputStream inputStream, int[][] numberOfPage)](#splitToBulks-java.io.InputStream-int-----) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [splitToBulks(String inputFile, int[][] numberOfPage)](#splitToBulks-java.lang.String-int-----) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [splitToEnd(InputStream inputStream, int location, OutputStream outputStream)](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | 从指定位置拆分，将后面的部分另存为一个新的文件Stream。 |
| [splitToEnd(String inputFile, int location, String outputFile)](#splitToEnd-java.lang.String-int-java.lang.String-) | 从位置拆分，并将后面的部分另存为新文件。 |
| [splitToPages(InputStream inputStream)](#splitToPages-java.io.InputStream-) | 将 Pdf 文件拆分为单页文档。 |
| [splitToPages(InputStream inputStream, String fileNameTemplate)](#splitToPages-java.io.InputStream-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [splitToPages(String inputFile)](#splitToPages-java.lang.String-) | 将 PDF 文件拆分为单页文档。 |
| [splitToPages(String inputFile, String fileNameTemplate)](#splitToPages-java.lang.String-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileEditor() {#PdfFileEditor--}
```
public PdfFileEditor()
```


PdfFileEditor 构造函数。

### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InmputStream src = new FileInputStream("input.pdf");
  OutputStream dest = new FileInputStream("output.pdf");
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
boolean - 布尔值
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
  InmputStream src = new FileInputStream("input.pdf");
  OutputStream dest = new FileInputStream("output.pdf");
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
      dest.close();
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
boolean - 布尔值
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
 fileEditor.append(instream, stream1,  3, 5, outstream);
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
 OtputStream outstream = new FileOutputStream("outfile.pdf");
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
 fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
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
 fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream);
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

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
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
 fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | 要连接的流数组。 |
| outputStream | java.io.OutputStream | 将存储结果文件的流。 |

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
### delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#delete-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入文件流。 |
| pageNumber | int[] | 输入文件的页面索引。 |
| outputStream | java.io.OutputStream | 输出文件流。 |

**退货：**
boolean - True 表示成功，否则为 false。
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
 OutputStream outStream = new FileInputStream("out.pdf");
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
### extract(String inputFile, int startPage, int endPage, String outputFile) {#extract-java.lang.String-int-int-java.lang.String-}
```
public boolean extract(String inputFile, int startPage, int endPage, String outputFile)
```


从输入文件中提取页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.Extract("input.pdf", 3, 7, "output.pdf");
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
### getAllowConcatenateExceptions() {#getAllowConcatenateExceptions--}
```
public boolean getAllowConcatenateExceptions()
```


如果设置为 true，则在发生错误时抛出异常。否则不会抛出异常，如果失败则方法返回 false。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException (true);
```

**退货：**
boolean - 布尔值
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


当操作结果作为附件存储到 HttpServletResponse 对象时获取附件名称。

**退货：**
java.lang.String - 字符串值
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
int - ContentDisposition 元素
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
	      pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted);
	      ```
if (pfe.getCorruptedItems().length >0)
```
	      {
	        for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems())
	        {
	           System.out.println(item.getIndex()+ " reason: " + item.getException());
	        }
	      }
```

**Returns:**
com.aspose.pdf.facades.PdfFileEditor.CorruptedItem[] - array of PdfFileEditor.CorruptedItem
### getCustomProgressConcatenationHandler() {#getCustomProgressConcatenationHandler--}
```
公共 PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```


Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. This field uses different types of events.

Simple concatenation has 8 events :
1)AllPagesCopied
2)DocumentEmbeddedFiles
3)DocumentForms
4)DocumentOutlines
5)DocumentJavaScript
6)DocumentLogicalStructure
7)DocumentConcated.
8)TotalPercentage.

Parallel concatenation informs about every page concatenation and has 3 events:
1)PageConcatenated
2)BlankPage
3)TotalPercentage

**Returns:**
[ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) - ConcatenationProgressHandler instance
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
公共布尔值 getIncrementalUpdates()
```


If true, incremental updates are made during concatenation.

**Returns:**
boolean - boolean value
### getKeepActions() {#getKeepActions--}
```
公共最终布尔值 getKeepActions()
```


If true actions will be copied from source documents. Defaulkt value : true.

**Returns:**
boolean - boolean value
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
公共布尔 getKeepFieldsUnique()
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Returns:**
boolean - boolean value
### getLastException() {#getLastException--}
```
公共最终 RuntimeException getLastException()
```


Gets last occurred exception. May be used to check the reason of failure.

```
PdfFileEditor pfe = new PdfFileEditor();
  如果 (!pfe.tryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
  {
     System.out.println("发生错误：");
     如果（pfe.getLastException（）！= null）
     {
         System.out.println((pfe.getLastException().getMessage());
         如果 (pfe.getLastException().getInnerException() != null)
             System.out.println((pfe.getLastException().getInnerException().getMessage());
     }
  }
```

**Returns:**
java.lang.RuntimeException
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
公共布尔 getMergeDuplicateLayers()
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Returns:**
boolean
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
公共布尔 getMergeDuplicateOutlines()
```


If true, duplicate outlines are merged.

**Returns:**
boolean - boolean value
### getOptimizeSize() {#getOptimizeSize--}
```
公共布尔 getOptimizeSize()
```


Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean - boolean value
### getOwnerPassword() {#getOwnerPassword--}
```
公共字符串 getOwnerPassword()
```


Gets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Returns:**
java.lang.String - String value
### getPreserveUserRights() {#getPreserveUserRights--}
```
公共布尔 getPreserveUserRights()
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Returns:**
boolean - boolean value
### getRemoveSignatures() {#getRemoveSignatures--}
```
公共最终布尔值 getRemoveSignatures()
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Returns:**
boolean - boolean value
### getSaveOptions() {#getSaveOptions--}
```
公共保存选项 getSaveOptions()
```


Gets or sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getUniqueSuffix() {#getUniqueSuffix--}
```
公共字符串 getUniqueSuffix()
```


Get format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
公共本机 int hashCode()
```




**Returns:**
int
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
公共布尔插入（InputStream inputStream，int insertLocation，InputStream portStream，int startPage，int endPage，OutputStream outputStream）
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 outstream sourceStream = new FileInputStream("file1.pdf");
 outstream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| startPage | int | From which page to start. |
| endPage | int | To which page to end. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True for success, or false.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
公共布尔插入（InputStream inputStream，int insertLocation，InputStream portStream，int[] pageNumber, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 outstream sourceStream = new FileInputStream("file1.pdf");
 outstream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileoutputStream("out.pdf");
 pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True if operation was succeeded.
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


Inserts pages from an other file into the Pdf file at a position.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Position in input file. |
| portFile | java.lang.String | The porting Pdf file. |
| startPage | int | Start position in portFile. |
| endPage | int | End position in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] 页码，字符串输出文件）
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 outstream sourceStream = new FileInputStream("file1.pdf");
 outstream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Insert position in input file. |
| portFile | java.lang.String | Pages from the Pdf file. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
公共布尔值 isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### isUseDiskBuffer() {#isUseDiskBuffer--}
```
公共最终布尔值 isUseDiskBuffer()
```


If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Returns:**
boolean - boolean value
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream)
```


Makes booklet from the InputStream to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | output pdf stream. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


Makes booklet from the input stream and save result into output stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] 左页，整数[右页）
```


Makes booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, 新整数[1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, int[] 左页，整数[右页）
```


Makes customized booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, 新整数[1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
公共布尔 makeBooklet（字符串输入文件，字符串输出文件）
```


Makes booklet from the input file to output file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("输入.pdf", "输出.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize)
```


Makes booklet from the inputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("输入.pdf", "输出.pdf", PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation is succeeded.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] 左页，整数[右页）
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("输入.pdf", "输出.pdf", PageSize.A4, new int[] { 2, 4, 6 }, 新整数[1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, int[] 左页，整数[右页）
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("输入.pdf", "输出.pdf", new int[] { 2, 4, 6 }, 新整数[1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| leftPages | int[] | The left pages of the booklet. |
| rightPages | int[] | The right pages of the booklet. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
公共布尔 makeNUp（InputStream firstInputStream，InputStream secondInputStream，OutputStream outputStream）
```


Makes N-Up document from the two input PDF streams to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream input1 = new FileInputStream("input1.pdf");
 InputStream input2 = new FileInputStream("input2.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp（输入1，输入2，输出）；
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | first input stream. |
| secondInputStream | java.io.InputStream | second input stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)
```


Makes N-Up document from the input stream and saves result into output stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


Makes N-Up document from the first input stream to output stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
公共布尔 makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("input1.pdf");
 InputStream stream2 = new FileInputStream("input2.pdf");
 InputStream stream3 = new FileInputStream("input3.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(新输入流[{ stream1, stream2, stream3 }, 输出, false);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | Input Pdf streams. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y)
```


Makes N-Up document from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("输入.pdf", "输出.pdf", 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


Makes N-Up document from the input file to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("输入.pdf", "输出.pdf", 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean makeNUp(String firstInputFile, String secondInputFile, String outputFile)
```


Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | first input file. |
| secondInputFile | java.lang.String | second input file. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
公共布尔 makeNUp（字符串[inputFiles, String outputFile, boolean isSidewise)
```


Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp(新字符串[{ "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Input Pdf files. |
| outputFile | java.lang.String | Output pdf file path and name. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically. |

**Returns:**
boolean - boolean - True for success, or false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents（文档来源，IPdfFileEditor.ContentsResizeParameters 参数）
```


Resizes pages of document. Blank margins are added around of shrinked page.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 文档 src = new Document("input.pdf");
 文件目标=新文件（）；
 APdfFileEditor.ContentsResizeParameters 参数 = new PdfFileEditor.ContentsResizeParameters(
     //左边距 = 页面宽度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
     无效的，
     //右边距是页面的10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //上边距 = 高度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容高度自动计算（类似于宽度）
     无效的，
     //底部保证金为10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents（文档，参数）；
 dest.save("输出.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Source document. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

### resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(IDocument source, int[] 页，IPdfFileEditor.ContentsResizeParameters 参数）
```


Resizes pages of document. Blank margins are added around of shrinked page.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 文档 doc = new Document("input.pdf");
 PdfFileEditor.ContentsResizeParameters 参数 = new PdfFileEditor.ContentsResizeParameters(
     //左边距 = 页面宽度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
     无效的，
     //右边距是页面的10% 
     PdfFileEditor.ContentsResizeValue.percents(10),
     //上边距 = 高度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容高度自动计算（类似于宽度）
     无效的，
     //底部保证金为10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, new int[] { 1, 2, 3}, 参数);
 doc.save("输出.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Source document. |
| pages | int[] | List of page indexes. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

### resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] 页，IPdfFileEditor.ContentsResizeParameters 参数）
```


Resizes contents of pages of the document.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
	      InputStream src = new FileInputStream("输入.pdf");
	      OutputStream dest = new FileOutputStream("output.pdf");
	      PdfFileEditor.ContentsResizeParameters 参数 = new PdfFileEditor.ContentsResizeParameters(
	          //左边距 = 页面宽度的 10%
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
	          无效的，
	          //右边距是页面的10% 
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //上边距 = 高度的 10%
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //新内容高度自动计算（类似于宽度）
	          无效的，
	          //底部保证金为10%
	          PdfFileEditor.ContentsResizeValue.percents(10)
	             );
	      fileEditor.resizeContents(src, dest, new int[] { 1, 2, 3}, 参数);
	      dest.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream with source document. |
| destination | java.io.OutputStream | Stream with the destination document. |
| pages | int[] | Array of page indexes. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

**Returns:**
boolean - Returns true if success.
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] 页面，双新宽度，双新高度）
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("输入.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents(src, dest, 
 //调整文档所有页面的大小
 无效的， 
 //新内容宽度= 200
 200, 
 //新内容高度= 300
 300);
 // 页面的其余区域将为空
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(String source, String destination, int[] 页，IPdfFileEditor.ContentsResizeParameters 参数）
```


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 PdfFileEditor.ContentsResizeParameters 参数 = new PdfFileEditor.ContentsResizeParameters(
     //左边距 = 页面宽度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容宽度自动计算为宽度 - 左边距 - 右边距（100% - 10% - 10% = 80%）
     无效的，
     //右边距是页面的10% 
     PdfFileEditor.ContentsResizeValue.percents(10),
     //上边距 = 高度的 10%
     PdfFileEditor.ContentsResizeValue.percents(10),
     //新内容高度自动计算（类似于宽度）
     无效的，
     //底部保证金为10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents("input.pdf", "output.pdf", new int[] { 1, 2,.3}, 参数);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Source document path. |
| destination | java.lang.String | Destination document path. |
| pages | int[] | Array of page indexes (page index starts from 1). |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Parameters of page resize. |

**Returns:**
boolean - trure if resize was successful.
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContents(String source, String destination, int[] 页面，双新宽度，双新高度）
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContents("输入.pdf", "输出.pdf", 
 //调整文档所有页面的大小
 无效的， 
 //新内容宽度= 200
 200, 
 //新内容高度= 300
 300);
 // 页面的其余区域将为空
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContentsPct(InputStream source, OutputStream destination, int[] 页面，双新宽度，双新高度）
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("输入.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct(src, dest, 
 //调整文档所有页面的大小
 无效的， 
 //新内容宽度 = 初始大小的 60%
 60, 
 //新内容高度=初始大小的60%
 60);
 // 页面的其余区域将为空（页边距）。左右边距的大小为 (100% - 60%) / 2 = 20%
 // 顶部和底部边距相同。
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - boolean value
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContentsPct(String source, String destination, int[] 页面，双新宽度，双新高度）
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizePct("输入.pdf", "输出.pdf",
 //调整文档所有页面的大小
 无效的， 
 //新内容宽度 = 初始大小的 60%
 60, 
 //新内容高度=初始大小的60%
 60);
 // 页面的其余区域将为空（页边距）。左右边距的大小为 (100% - 60%) / 2 = 20%
 // 顶部和底部边距相同。
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - true if resize was successful.
### resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization（文档来源，IPdfFileEditor.ContentsResizeParameters 参数）
```


Resizes pages of document. Blank margins are added around of shrinked page. Normalization helps to avoid not grouped saved content state unexpected behavior.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Document instance |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters instance |

### resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(IDocument source, int[] 页，IPdfFileEditor.ContentsResizeParameters 参数）
```


Resizes pages of document. Blank margins are added around of shrinked page. Normalization helps to avoid not grouped saved content state unexpected behavior.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Document instance |
| pages | int[] | array of int values |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters instance |

### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public void setAllowConcatenateExceptions（布尔值）
```


If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException (true);
``` |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName（字符串值）
```


Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams（布尔值）
```


If set to true, streams are closed after operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setCloseConcatenatedStreams (true);
``` |

### setConcatenationPacketSize(int value) {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```


Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int 值)
```


Sets how content will be stored when result of operation is stored into HttpServletResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat 值)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | int value |

### setCopyLogicalStructure(boolean value) {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure（布尔值）
```


If true then logical structure of the file is copied when concatenation is performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCopyOutlines(boolean value) {#setCopyOutlines-boolean-}
```
public void setCopyOutlines（布尔值）
```


If true then outlines will be copied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int 值)
```


This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler) {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
```
public void setCustomProgressConcatenationHandler（PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler）
```


Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. This field uses different types of events.

Simple concatenation has 8 events :
1)AllPagesCopied
2)DocumentEmbeddedFiles
3)DocumentForms
4)DocumentOutlines
5)DocumentJavaScript
6)DocumentLogicalStructure
7)DocumentConcated.
8)TotalPercentage.

Parallel concatenation informs about every page concatenation and has 3 events:
1)PageConcatenated
2)BlankPage
3)TotalPercentage

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProgressConcatenationHandler | [ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) | ConcatenationProgressHandler instance |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates（布尔值）
```


If true, incremental updates are made during concatenation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepActions(boolean value) {#setKeepActions-boolean-}
```
public final void setKeepActions(布尔值)
```


If true actions will be copied from source documents. Defaulkt value : true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique（布尔值）
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
公共无效 setMergeDuplicateLayers（布尔值）
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
公共无效 setMergeDuplicateOutlines（布尔值）
```


If true, duplicate outlines are merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
公共无效 setOptimizeSize（布尔值）
```


Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword（字符串值）
```


Sets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
公共无效 setPreserveUserRights（布尔值）
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public final void setRemoveSignatures（布尔值）
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions（SaveOptions 值）
```


Sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions object |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
公共无效 setTryMergeAdjacentSameBackgroundImages（布尔 tryMergeAdjacentSameBackgroundImages）
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public void setUniqueSuffix(字符串值)
```


Set format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

--------------------

```
PdfFileEditor ed = new PdfFileEditor();
   ed.setUniqueSuffix ( "_%NUM%");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setUseDiskBuffer(boolean value) {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(布尔值)
```


If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)
```


Splits from start to specified location,and saves the front part in output Stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitFromFirst(sourceStream, 5, outStream);
```

--------------------

The streams are NOT closed after this operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting point. |
| outputStream | java.io.OutputStream | Output file Stream. |

**Returns:**
boolean - True for success, or false.
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public boolean splitFromFirst(String inputFile, int location, String outputFile)
```


Splits Pdf file from first page to specified location,and saves the front part as a new file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitFromFirst("输入.pdf", 5, "输出.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting point. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
公共字节数组输入流[splitToBulks(InputStream inputStream, int[][] 页数）
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| numberOfPage | int[][] | The start page and the end page of each document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
公共字节数组输入流[] splitToBulks（字符串输入文件，int[][] 页数）
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file. |
| numberOfPage | int[][] | Array which contains array of double elements, which is start and end pages of document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitToEnd(InputStream inputStream, int location, OutputStream outputStream)
```


Splits from specified location, and saves the rear part as a new file Stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.splitToEnd(sourceStream, 5, outStream);
```

--------------------

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting position. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True if splitting was successful.
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public boolean splitToEnd(String inputFile, int location, String outputFile)
```


Splits from location, and saves the rear part as a new file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitToEnd("输入.pdf", 5, "输出.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting position. |
| outputFile | java.lang.String | Output Pdf file path. |

**Returns:**
boolean - True for success, or false.
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
公共字节数组输入流[] splitToPages（输入流输入流）
```


Splits the Pdf file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf stream. |

**Returns:**
java.io.ByteArrayInputStream[] - ByteArrayInputStream[] array
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public void splitToPages(InputStream inputStream, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of the soruce document. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number . For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
公共字节数组输入流[splitToPages（字符串输入文件）
```


Splits the PDF file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file name. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a single-page PDF document.
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public void splitToPages(String inputFile, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file name. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number . For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
