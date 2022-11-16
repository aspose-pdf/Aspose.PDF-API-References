---
title: IPdfFileEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 实现PDF文件拼接拆分提取页面制作小册子等操作。
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

实现对PDF文件的操作：拼接、拆分、提取页面、制作小册子等。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | 调整页面内容的大小并添加指定的边距。 |
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
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | 提取由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | 提取由数字数组指定的页面，另存为新的 PDF 文件。 |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | 是允许连接异常 |
| [getAttachmentName()](#getAttachmentName--) | 当操作结果作为附件存储到 HttpServletResponse 对象时获取附件名称。 |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | 如果设置为 true，流将在操作后关闭。 |
| [getContentDisposition()](#getContentDisposition--) | 获取当操作结果存储到 HttpServletResponse 对象时将如何存储内容。 |
| [getConversionLog()](#getConversionLog--) | 获取转换过程的日志。 |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | 当连接进程遇到损坏的文件时，此属性定义行为。 |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | 如果为真，则在串联期间进行增量更新。 |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | 如果为真，则在连接表单时字段名称将是唯一的。 |
| [getLastException()](#getLastException--) | 获取最后发生的异常。 |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | 如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。 |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | 如果为真，则合并重复的轮廓。 |
| [getOwnerPassword()](#getOwnerPassword--) | 如果源输入 Pdf 文件已加密，则获取所有者的密码。 |
| [getPreserveUserRights()](#getPreserveUserRights--) | 如果为真，则第一个文档的用户权限将应用于级联文档。 |
| [getRemoveSignatures()](#getRemoveSignatures--) | 如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。 |
| [getSaveOptions()](#getSaveOptions--) | 当结果存储为 HttpServletResponse 时获取或设置保存选项。 |
| [getUniqueSuffix()](#getUniqueSuffix--) | 获取添加到字段名称的后缀的格式，以使其在连接表单时唯一。 |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 将其他文件的页面插入到 Pdf 文件的某个位置。 |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | 将其他文件的页面插入到输入 Pdf 文件中。 |
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
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | 调整文档页面内容的大小。 |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | 调整文档页面内容的大小。 |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | 如果设置为 true，则在发生错误时抛出异常。 |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpServletResponse 对象时设置附件名称。 |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | 如果设置为 true，流将在操作后关闭。 |
| [setContentDisposition(int value)](#setContentDisposition-int-) | 设置将操作结果存储到 HttpServletResponse 对象时如何存储内容。 |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | 当连接进程遇到损坏的文件时，此属性定义行为。 |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | 如果为真，则在串联期间进行增量更新。 |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | 如果为真，则在连接表单时字段名称将是唯一的。 |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) | 如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。 |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | 如果为真，则合并重复的轮廓。 |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | 如果源输入 Pdf 文件已加密，则设置所有者的密码。 |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | 如果为真，则第一个文档的用户权限将应用于级联文档。 |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | 如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。 |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpServletResponse 时设置保存选项。 |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | 设置添加到字段名称的后缀的格式，以使其在连接表单时唯一。 |
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
### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public abstract boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.addMargins(src, dest,
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 10 units
 	10,
 	// right margin is 5 units
 	5,
 	// top margin is 5 units
 	5,
 	// bottom margin is 5 units
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
public abstract boolean addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.addMargins("input.pdf", "output.pdf",
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 10 units
 	10,
 	// right margin is 5 units
 	5,
 	// top margin is 5 units
 	5,
 	// bottom margin is 5 units
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
public abstract boolean addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以初始页面大小的百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.addMarginsPct(src, dest,
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 15% of page width
 	15,
 	// right margin is 10% of page width
 	10,
 	// top margin is 20% of page width
 	20,
 	// bottom margin is 5% of page width
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
布尔值 - 如果调整大小成功则为真
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public abstract boolean addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


调整页面内容的大小并添加指定的边距。边距以初始页面大小的百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.addMarginsPct("input.pdf", "output.pdf",
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 15% of page width
 	15,
 	// right margin is 10% of page width
 	10,
 	// top margin is 20% of page width
 	20,
 	// bottom margin is 5% of page width
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
### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
public abstract boolean append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


在 portStream 的 firstInputStream 末尾追加从 startPage 到 endPage 范围内的 portStream 中选择的页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1, 3, 5, outstream);
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
public abstract boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


添加从 portStreams 中的文档数组中选择的页面。结果文档包括 firstInputFile 和 startPage 到 endPage 范围内的所有 portStreams 文档页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, new Stream[]
 { stream1, stream2 }, 3, 5, outstream);
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
public abstract boolean append(String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


在 firstInputFile 末尾的 portFile 中追加从 startPage 到 endPage 范围内的 portFile 中选择的页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf");
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
public abstract boolean append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


添加从 portFiles 文档中选择的页面。结果文档包括 firstInputFile 和 startPage 到 endPage 范围内的所有 portFiles 文档页面。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", new string[]
 { "file1.pdf", "file2.pdf" }, 3, 5, "outfile.pdf");
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
public abstract boolean concatenate(IDocument[] src, IDocument dest)
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
public abstract boolean concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)
```


将两个 Pdf 文档以交替方式合并为一个新的 Pdf 文档，并用空白页填充空白处。例如：文档 1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1'、p2'、p3'。合并两个 Pdf 文档将生成包含页面的结果文档：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 InputStream blank = new FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[]
 { stream1, stream2, blank }, outstream);
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
public abstract boolean concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
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
public abstract boolean concatenate(InputStream[] inputStream, OutputStream outputStream)
```


连接文件

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[]
 { stream1, stream2 }, outstream);
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
public abstract boolean concatenate(String firstInputFile, String secInputFile, String outputFile)
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
public abstract boolean concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)
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
public abstract boolean concatenate(String[] inputFiles, String outputFile)
```


将文件连接成一个文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.concatenate(new string[]
 { "src1.pdf", "src2.pdf" }, "dest.pdf");
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
public abstract boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.Delete(inputStream, new int[]
 { 2, 3 }, outputStream);
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
public abstract boolean delete(String inputFile, int[] pageNumber, String outputFile)
```


从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.delete("input.pdf", new int[]
 { 2, 3 }, "out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件路径。 |
| pageNumber | int[] | 输入文件的页面索引。 |
| outputFile | java.lang.String | 输出文件路径。 |

**退货：**
boolean - 如果操作成功则为真。
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
public abstract boolean extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
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
public abstract boolean extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


提取由数字数组指定的页面，另存为新的 Pdf 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, new int[]
 { 3, 5, 8 }, outStream);
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
public abstract boolean extract(String inputFile, int startPage, int endPage, String outputFile)
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
public abstract boolean extract(String inputFile, int[] pageNumber, String outputFile)
```


提取由数字数组指定的页面，另存为新的 PDF 文件。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.extract("input.pdf", new int[]
 { 3, 5, 7 }, "output.pdf");
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
public abstract boolean getAllowConcatenateExceptions()
```


是允许连接异常

**退货：**
boolean - 布尔值
### getAttachmentName() {#getAttachmentName--}
```
public abstract String getAttachmentName()
```


当操作结果作为附件存储到 HttpServletResponse 对象时获取附件名称。

**退货：**
java.lang.String - 字符串值
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
public abstract boolean getCloseConcatenatedStreams()
```


如果设置为 true，流将在操作后关闭。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setCloseConcatenatedStreams(true);
```

**退货：**
boolean - 布尔值
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


获取当操作结果存储到 HttpServletResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**退货：**
int - ContentDisposition 元素
### getConversionLog() {#getConversionLog--}
```
public abstract String getConversionLog()
```


获取转换过程的日志。

**退货：**
java.lang.String - 字符串值
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
public abstract int getCorruptedFileAction()
```


当连接进程遇到损坏的文件时，此属性定义行为。可能的值是：StopWithError 和 ConcatenateIgnoringCorrupted。

**退货：**
int - ConcatenateCorruptedFileAction 元素
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
public abstract boolean getIncrementalUpdates()
```


如果为真，则在串联期间进行增量更新。

**退货：**
boolean - 布尔值
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
public abstract boolean getKeepFieldsUnique()
```


如果为真，则在连接表单时字段名称将是唯一的。后缀将添加到字段名称中，后缀模板可以在 UniqueSuffix 属性中指定。

**退货：**
boolean - 布尔值
### getLastException() {#getLastException--}
```
public abstract Exception getLastException()
```


获取最后发生的异常。当 AllowconcatenateExceptions = false 时，可用于检查失败原因。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setAllowConcatenateExceptions(false);
 if (!pfe.concatenate("", "", ""))
 {
     System.out.println("");
     if (pfe.getLastException() != null)
     {
 	System.out.println(pfe.getLastException().getMessage());
 	if (pfe.getLastException().getCause() != null)
 	    System.out.println(pfe.getLastException().getCause().getMessage());
     }
 }
```

**退货：**
java.lang.Exception - java.lang.Exception 对象
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
public abstract boolean getMergeDuplicateLayers()
```


如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。否则，具有相同名称的图层将在生成的文档中另存为不同的图层。

**退货：**
boolean - 布尔值
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
public abstract boolean getMergeDuplicateOutlines()
```


如果为真，则合并重复的轮廓。

**退货：**
boolean - 布尔值
### getOwnerPassword() {#getOwnerPassword--}
```
public abstract String getOwnerPassword()
```


如果源输入 Pdf 文件已加密，则获取所有者的密码。此属性尚未实现。

**退货：**
java.lang.String - 字符串值
### getPreserveUserRights() {#getPreserveUserRights--}
```
public abstract boolean getPreserveUserRights()
```


如果为真，则第一个文档的用户权限将应用于级联文档。所有其他文档的用户权限都将被忽略。

**退货：**
boolean - 布尔值
### getRemoveSignatures() {#getRemoveSignatures--}
```
public abstract boolean getRemoveSignatures()
```


如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。

**退货：**
boolean - 布尔值
### getSaveOptions() {#getSaveOptions--}
```
public abstract SaveOptions getSaveOptions()
```


当结果存储为 HttpServletResponse 时获取或设置保存选项。默认值：PdfSaveOptions。

**退货：**
[SaveOptions](../../com.aspose.pdf/saveoptions) - 保存选项对象
### getUniqueSuffix() {#getUniqueSuffix--}
```
public abstract String getUniqueSuffix()
```


获取添加到字段名称的后缀的格式，以使其在连接表单时唯一。此字符串必须包含 %NUM% 子字符串，该子字符串将被替换为数字。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段“fieldName”的名称将是：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

**退货：**
java.lang.String - 字符串值
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
public abstract boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
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
public abstract boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


将其他文件的页面插入到输入 Pdf 文件中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, new int[]
 { 3, 4, 5 }, outStream);
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
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
public abstract boolean insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
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
public abstract boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


将其他文件的页面插入到输入 Pdf 文件中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "out.pdf", 2, 6, "out.pdf");
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
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream)
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
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)
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
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)
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
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)
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
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
public abstract boolean makeBooklet(String inputFile, String outputFile)
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
public abstract boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize)
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
public abstract boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)
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
public abstract boolean makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)
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
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public abstract boolean makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
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
public abstract boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)
```


从输入流制作 N-Up 文档并将结果保存到输出流中。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
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
public abstract boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


制作从第一个输入流到输出流的 N-Up 文档。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
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
public abstract boolean makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


从多输入 PDF 流到 outputStream 制作 N-Up 文档。 outputStream 的每一页将包含多个页面，这些页面与相同页码的输入流中的页面组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则多页垂直堆叠。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("input1.pdf");
 InputStream stream2 = new FileInputStream("input2.pdf");
 InputStream stream3 = new FileInputStream("input3.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(new Stream[]
 { stream1, stream2, stream3 }, output, false);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | 输入 Pdf 流。 |
| outputStream | java.io.OutputStream | 输出 pdf 流。 |
| isSidewise | boolean | 堆积方式，水平为 true，垂直为 flase |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public abstract boolean makeNUp(String inputFile, String outputFile, int x, int y)
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
public abstract boolean makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)
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
public abstract boolean makeNUp(String firstInputFile, String secondInputFile, String outputFile)
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
public abstract boolean makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)
```


从多输入 PDF 文件到 outputFile 制作 N-Up 文档。 outputFile 的每一页将包含多个页面，这些页面与相同页码的输入文件中的页面组合。如果 isSidewise 为真，则多页水平堆叠；如果 isSidewise 为假，则多页垂直堆叠。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp(new string[]
 { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | java.lang.String[] | 输入 Pdf 文件。 |
| outputFile | java.lang.String | 输出pdf文件路径和名称。 |
| isSidewise | boolean | 堆积方式，水平为 true，垂直为 flase。 |

**退货：**
boolean - boolean - True 表示成功，或者 false。
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public abstract boolean resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。内容的新大小以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents(src, dest,
 // resize all pages of document
 	null,
 	// new contents width = 200
 	200,
 	// new contents height = 300
 	300);
 // rest area of page will be empty
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
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public abstract boolean resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。内容的新大小以默认空间单位指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf",
 // resize all pages of document
 	null,
 	// new contents width = 200
 	200,
 	// new contents height = 300
 	300);
 // rest area of page will be empty
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
public abstract boolean resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。新内容大小以百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct(src, dest,
 // resize all pages of document
 	null,
 	// new contents width = 60% of initial size
 	60,
 	// new contents height = 60% of initial size
 	60);
 // Rest area of page will be empty (page margins). Size of left and right
 // margins is (100% - 60%) / 2 = 20%
 // The same for top and bottom margins.
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
public abstract boolean resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)
```


调整文档页面内容的大小。缩小页面内容并增加页边距。新内容大小以百分比指定。

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContentsPct("input.pdf", "output.pdf",
 // resize all pages of document
 	null,
 	// new contents width = 60% of initial size
 	60,
 	// new contents height = 60% of initial size
 	60);
 // Rest area of page will be empty (page margins). Size of left and right
 // margins is (100% - 60%) / 2 = 20%
 // The same for top and bottom margins.
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
### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public abstract void setAllowConcatenateExceptions(boolean value)
```


如果设置为 true，则在发生错误时抛出异常。否则不会抛出异常，如果失败则方法返回 false。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setAllowConcatenatedException(true);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName(String value)
```


当操作结果作为附件存储到 HttpServletResponse 对象时设置附件名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public abstract void setCloseConcatenatedStreams(boolean value)
```


如果设置为 true，流将在操作后关闭。

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setCloseConcatenatedStreams(true);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition(int value)
```


设置将操作结果存储到 HttpServletResponse 对象时如何存储内容。可能的值：内联/附件。默认值：内联。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ContentDisposition 元素 |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public abstract void setConvertTo(PdfFormat value)
```


设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存而不进行转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素 |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public abstract void setCorruptedFileAction(int value)
```


当连接进程遇到损坏的文件时，此属性定义行为。可能的值是：StopWithError 和 ConcatenateIgnoringCorrupted。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ConcatenateCorruptedFileAction 元素 |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public abstract void setIncrementalUpdates(boolean value)
```


如果为真，则在串联期间进行增量更新。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public abstract void setKeepFieldsUnique(boolean value)
```


如果为真，则在连接表单时字段名称将是唯一的。后缀将添加到字段名称中，后缀模板可以在 UniqueSuffix 属性中指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public abstract void setMergeDuplicateLayers(boolean value)
```


如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层中。否则，具有相同名称的图层将在生成的文档中另存为不同的图层。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public abstract void setMergeDuplicateOutlines(boolean value)
```


如果为真，则合并重复的轮廓。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public abstract void setOwnerPassword(String value)
```


如果源输入 Pdf 文件已加密，则设置所有者的密码。此属性尚未实现。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public abstract void setPreserveUserRights(boolean value)
```


如果为真，则第一个文档的用户权限将应用于级联文档。所有其他文档的用户权限都将被忽略。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public abstract void setRemoveSignatures(boolean value)
```


如果为真，所有签名将从字段中删除（字段将保留）；否则，您会得到无效的签名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


当结果存储为 HttpServletResponse 时设置保存选项。默认值：PdfSaveOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项对象 |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public abstract void setUniqueSuffix(String value)
```


设置添加到字段名称的后缀的格式，以使其在连接表单时唯一。此字符串必须包含 %NUM% 子字符串，该子字符串将被替换为数字。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段“fieldName”的名称将是：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

--------------------

```
PdfFileEditor ed = new PdfFileEditor();
 ed.setUniqueSuffix("_%NUM%");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public abstract boolean splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)
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
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public abstract boolean splitFromFirst(String inputFile, int location, String outputFile)
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
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
public abstract ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] numberOfPage)
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
public abstract ByteArrayInputStream[] splitToBulks(String inputFile, int[][] numberOfPage)
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
public abstract boolean splitToEnd(InputStream inputStream, int location, OutputStream outputStream)
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
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public abstract boolean splitToEnd(String inputFile, int location, String outputFile)
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
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
public abstract ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


将 Pdf 文件拆分为单页文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 Pdf 流。 |

**退货：**
java.io.ByteArrayInputStream[] - 字节数组输入流[大批
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public abstract void splitToPages(InputStream inputStream, String fileNameTemplate)
```


将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 源文档流。 |
| fileNameTemplate | java.lang.String | 结果文件名的模板。必须包含用页码替换的 %NUM%。例如，如果指定了 c:/dir/page%NUM%.pdf，则生成的文件将具有以下名称：c:/dir/page1.pdf、c:/dir/page2.pdf 等。 |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
public abstract ByteArrayInputStream[] splitToPages(String inputFile)
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
public abstract void splitToPages(String inputFile, String fileNameTemplate)
```


将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件名。 |
| fileNameTemplate | java.lang.String | 结果文件名的模板。必须包含用页码替换的 %NUM%。例如，如果指定了 c:/dir/page%NUM%.pdf，则生成的文件将具有以下名称：c:/dir/page1.pdf、c:/dir/page2.pdf 等。 |
