---
title: PdfFileEditor
second_title: Aspose.PDF for .NET API 参考
description: 实现对PDF文件的操作拼接拆分提取页面制作小册子等
type: docs
weight: 2470
url: /zh/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

实现对PDF文件的操作：拼接、拆分、提取页面、制作小册子等

```csharp
public sealed class PdfFileEditor
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | 获取或设置操作结果作为附件存储到 HttpResponse 对象时的附件名称。 |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | 如果设置为 true，则流在操作后关闭。 |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | 当 UseDiskBuffer 设置为 true 时，在连接期间进行新的增量更新之前连接的文档数。 |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | 获取或设置在将操作结果存储到 HttpResponse 对象时如何存储内容。可能的值：inline / attachment. 默认值：inline. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | 获取转换过程的日志。 |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。 如果未指定此属性，则文件将保存为默认 PDF 格式而不进行转换。 |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | 如果为真，则在执行连接时复制文件的逻辑结构。 |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | 如果为 true，则将复制轮廓。 |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | 此属性定义连接过程遇到损坏文件时的行为。 可能的值是：StopWithError 和 ConcatenateIgnoringCorrupted。 |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | 执行串联时遇到的问题的数组。对于传递给 Concatenate() 的每个损坏的文档， 函数都会创建新的 CorruptedItem 条目。 只有在 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才能使用此属性。 |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | 如果为真，则在串联期间进行增量更新。 |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | 如果真实的操作将从源文档中复制。默认值：true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | 如果为 true，则连接表单时字段名称将是唯一的。 字段名称将添加后缀，可以在 UniqueSuffix 属性中指定后缀模板。 |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | 获取最后发生的异常。可用于检查失败原因。 |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | 如果此属性为真，则具有相同名称的连接文档的可选内容将合并到结果文档中的一层。 否则，具有相同名称的图层将在结果文档中保存为不同的图层。 |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | 如果为真，则合并重复的轮廓。 |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | 获取或设置优化标志。如果设置了此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。 这可以减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。 默认值：false。 |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | 如果源输入 Pdf 文件被加密，则设置所有者的密码。 此属性尚未实现。 |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | 如果为真，则将第一个文档的用户权限应用于级联文档。所有其他文档的用户权限都将被忽略。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | 如果为真，所有签名将从字段中删除（字段将保留）；否则，你会得到无效的签名。 |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | 获取或设置结果存储为 HttpResponse 时的保存选项。 默认值：PdfSaveOptions。 |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | 添加到字段名称以使其在连接表单时唯一的后缀格式。 此字符串必须包含将替换为数字的 %NUM% 子字符串。 例如，如果 UniqueSuffix = "ABC%NUM%" 那么对于字段“fieldName”名称将是： fieldNameABC1、fieldNameABC2、fieldNameABC3 等 |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | 如果使用此选项，则目标文档将定期保存在磁盘上，并且进一步的串联将作为增量更新应用于它。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。 以默认空间单位指定边距。 |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。 以默认空间单位指定边距。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。 边距以初始页面大小的百分比指定。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。 边距以初始页面大小的百分比指定。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | 在文档页面中添加分页符。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | 在文档页面中添加分页符。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | 在文档页面中添加分页符。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | 在portStream 的firstInputStream 末尾追加从startPage 到endPage 范围内从portStream 中选择的页面。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | 将文档附加到源文档并将结果保存到响应对象中。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | 追加页面，这些页面是从 portStreams 中的文档数组中选择的。 结果文档包括 firstInputFile 和 startPage 到 endPage 范围内的所有 portStreams 文档页面。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | 在portFile 的firstInputFile 的末尾追加从startPage 到endPage 范围内从portFile 中选择的页面。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | 将文档附加到源文档并将结果保存到 HttpResponse 对象中。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | 附加页面，这些页面是从 portFiles 文档中选择的。 结果文档包括 firstInputFile 和所有 portFiles 文档页面在 startPage 到 endPage 范围内。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | 连接文档。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | 连接文件并将结果存储到 HttpResponse 对象中。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | 连接文件 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | 连接文件并将 reslt 保存到 HttpResposnse 对象中。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | 将文件连接成一个文件。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | 连接两个文件。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | 连接两个文件。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | 将两个 Pdf 文档以交替方式合并成一个新的 Pdf 文档，并用空白页填充空白处。 例如：document1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1', p2', p3'. 合并两个 Pdf 文档将产生带有页面的结果文档：p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | 将两个 Pdf 文档以交替方式合并成一个新的 Pdf 文档，并用空白页填充空白处。 例如：document1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1', p2', p3'. 合并两个 Pdf 文档将产生带有页面的结果文档：p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | 从文档中删除指定页面并将结果保存到 HttpResponse 对象中。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | 从文档中删除指定页面并将结果存储到 HttpResponse 对象中。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | 提取数字数组指定的页面，另存为新的 Pdf 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | 提取数字数组指定的页面，另存为新的 PDF 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | 将文档插入其他文档并将结果存储到响应对象中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | 将其他文件中的页面插入到输入 Pdf 文件中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | 将文件内容插入源文件并将结果存储到 HttpResponse 对象中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | 将其他文件中的页面插入到输入 Pdf 文件中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | 将其他文件中的页面插入到输入 Pdf 文件中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | 将其他文件中的页面插入到 Pdf 文件的某个位置。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | 制作从 InputStream 到 outputStream. 的小册子 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | 制作从输入文件到输出文件的小册子。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | 从源文件制作小册子并将结果存储到 HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | 从输入流制作小册子并将结果保存到输出流中。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | 制作从 inputFile 到 outputFile. 的小册子 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | 制作从 firstInputStream 到 outputStream 的自定义小册子。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | 从 PDF 文件制作小册子并将其存储到 HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | 制作从 firstInputStream 到 outputStream. 的小册子 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | 从两个输入 PDF 流生成 N-Up 文档到 outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | 将多输入 PDF 流中的 N-Up 文档制作成 outputStream。 outputStream 的每一页将包含多个页面，这些页面与相同页码的输入流中的页面 组合。如果isSidewise为真，多页横向堆积 ，如果isSidewise为假，多页垂直堆积。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | 将两个输入 PDF 文件中的 N-Up 文档制作成 outputFile。 outputFile 的每一页将包含两页，一页来自第一个输入文件 ，另一页来自第二个输入文件。这两页是水平堆积的。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | 从多输入 PDF 文件制作 N-Up 文档到 outputFile。 outputFile 的每一页将包含多页，这些页与相同页码的输入文件中的 页组合。如果 isSidewise 为 true，则多页水平堆积 ，如果 isSidewise 为 false，则垂直堆积。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | 从输入流生成 N-Up 文档并将结果保存到输出流中。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | 使 N-Up 文档从 firstInputFile 到 outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | 将 N-Up 文档从第一个输入流转换为输出流。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | 将输入文件中的 N-Up 文档制作为 outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | 调整文档页面的大小。在缩小的页面周围添加空白边距。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | 调整文档页面的大小。在缩小的页面周围添加空白边距。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | 调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | 调整文档页面内容的大小。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | 调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | 调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | 调整文档页面内容的大小。 缩小页面内容并添加边距。 以默认空间单位指定新的内容大小。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | 调整文档页面内容的大小。 缩小页面内容并添加边距。 以默认空间单位指定新的内容大小。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | 调整文档页面内容的大小。 缩小页面内容并添加边距。 以百分比指定新内容大小。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | 调整文档页面内容的大小。 缩小页面内容并添加边距。 以百分比指定新内容大小。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | 将文档从开始拆分到指定位置，并将结果存储到 HttpResponse 对象中。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | 从开始到指定位置拆分，并将前面部分保存在输出流中。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | 将文档从第一页拆分到某个位置，并将结果保存到 HttpResponse 对象中。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | 将PDF文件从第一页拆分到指定位置，并将前面部分另存为新文件。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | 从指定位置拆分，并将后面部分保存到 HttpResponse 对象中。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | 从指定位置拆分，并将后面部分保存为新文件 Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | 从指定位置拆分，并将后面部分保存到 HttpResponse 对象中。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | 从位置拆分，并将后部保存为新文件。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | 将 Pdf 文件拆分为单页文档。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | 将 PDF 文件拆分为单页文档。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | 将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | 将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名称模板指定。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | 将文档附加到源文档并将结果保存到响应对象中。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | 追加页面，这些页面是从 portStreams 中的文档数组中选择的。 结果文档包括 firstInputFile 和 startPage 到 endPage 范围内的所有 portStreams 文档页面。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | 将文档附加到源文档并将结果保存到 HttpResponse 对象中。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | 附加页面，这些页面是从 portFiles 文档中选择的。 结果文档包括 firstInputFile 和所有 portFiles 文档页面在 startPage 到 endPage 范围内。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | 连接文档。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | 连接文件并将结果存储到 HttpResponse 对象中。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | 连接文件 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | 连接文件并将 reslt 保存到 HttpResposnse 对象中。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | 将文件连接成一个文件。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | 连接两个文件。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | 将两个 Pdf 文档以交替方式合并成一个新的 Pdf 文档，并用空白页填充空白处。 例如：document1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1', p2', p3'. 合并两个 Pdf 文档将产生带有页面的结果文档：p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | 将两个 Pdf 文档以交替方式合并成一个新的 Pdf 文档，并用空白页填充空白处。 例如：document1 有 5 页：p1、p2、p3、p4、p5。 document2 有 3 页：p1', p2', p3'. 合并两个 Pdf 文档将产生带有页面的结果文档：p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | 从文档中删除指定页面并将结果保存到 HttpResponse 对象中。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | 从文档中删除指定页面并将结果存储到 HttpResponse 对象中。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | 从输入文件中删除由数字数组指定的页面，另存为新的 Pdf 文件。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | 提取数字数组指定的页面，另存为新的 Pdf 文件。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | 从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | 提取数字数组指定的页面，另存为新的 PDF 文件。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | 从输入文件中提取页面，另存为新的 Pdf 文件。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | 将文档插入其他文档并将结果存储到响应对象中。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | 将其他文件中的页面插入到输入 Pdf 文件中。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | 将文件内容插入源文件并将结果存储到 HttpResponse 对象中。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | 将其他文件中的页面插入到输入 Pdf 文件中。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | 制作从 InputStream 到 outputStream. 的小册子 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | 制作从输入文件到输出文件的小册子。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | 从源文件制作小册子并将结果存储到 HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | 从输入流制作小册子并将结果保存到输出流中。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | 制作从 inputFile 到 outputFile. 的小册子 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | 制作从 firstInputStream 到 outputStream 的自定义小册子。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | 从 PDF 文件制作小册子并将其存储到 HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | 制作从 firstInputStream 到 outputStream. 的小册子 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | 从源文件制作小册子并将结果存储到 HttpResponse 对象中。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | 制作从 firstInputFile 到 outputFile 的自定义小册子。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | 从两个输入 PDF 流生成 N-Up 文档到 outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | 将多输入 PDF 流中的 N-Up 文档制作成 outputStream。 outputStream 的每一页将包含多个页面，这些页面与相同页码的输入流中的页面 组合。如果isSidewise为真，多页横向堆积 ，如果isSidewise为假，多页垂直堆积。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | 将两个输入 PDF 文件中的 N-Up 文档制作成 outputFile。 outputFile 的每一页将包含两页，一页来自第一个输入文件 ，另一页来自第二个输入文件。这两页是水平堆积的。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | 从多输入 PDF 文件制作 N-Up 文档到 outputFile。 outputFile 的每一页将包含多页，这些页与相同页码的输入文件中的 页组合。如果 isSidewise 为 true，则多页水平堆积 ，如果 isSidewise 为 false，则垂直堆积。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | 从输入流生成 N-Up 文档并将结果保存到输出流中。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | 使 N-Up 文档从 firstInputFile 到 outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | 将 N-Up 文档从第一个输入流转换为输出流。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | 制作 N-up 文档并将结果存储到 HttpResponse 对象中。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | 将输入文件中的 N-Up 文档制作为 outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | 调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | 调整文档页面内容的大小。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | 调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | 调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | 调整文档页面内容的大小。 缩小页面内容并添加边距。 以默认空间单位指定新的内容大小。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | 将文档从开始拆分到指定位置，并将结果存储到 HttpResponse 对象中。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | 从开始到指定位置拆分，并将前面部分保存在输出流中。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | 将文档从第一页拆分到某个位置，并将结果保存到 HttpResponse 对象中。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | 将PDF文件从第一页拆分到指定位置，并将前面部分另存为新文件。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | 从指定位置拆分，并将后面部分保存到 HttpResponse 对象中。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | 从指定位置拆分，并将后面部分保存为新文件 Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | 从指定位置拆分，并将后面部分保存到 HttpResponse 对象中。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | 从位置拆分，并将后部保存为新文件。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | 在连接过程中遇到损坏的文件时执行的操作。 |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | 用于指定页面大小调整参数的类。 允许设置以下参数： 结果页面的大小（宽度、高度），默认空间单位或初始页面大小的百分比； 以默认空间单位或初始页面大小的百分比表示的左、上、下和右页边距； 某些值可能为自动计算保留为空。这些值将在计算明确指定的值后从页面大小的其余部分计算 。 例如：如果页面宽度 = 100 并且新页面宽度指定为 60 个单位，则自动计算 左右边距： (100 - 60) / 2 = 15. 这个类用于 ResizeContents 方法。 |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | 以默认空间单位的百分比指定的边距或内容大小的值。 此类用于 ContentsResizeParameters。 |
| class [CorruptedItem](pdffileeditor.corrupteditem) | 在连接时提供有关损坏文件信息的类。 |
| class [PageBreak](pdffileeditor.pagebreak) | 分页位置数据。 |

### 也可以看看

* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
