---
title: "类 PdfFileEditor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileEditor 类。实现对 PDF 文件的合并、拆分、提取页面、制作小册子等操作。"
type: docs
weight: 4580
url: /zh/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。

```csharp
public sealed class PdfFileEditor
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | 如果设置为 true，操作完成后流将被关闭。 |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | 当 UseDiskBuffer 设置为 true 时，在进行合并期间，在进行新的增量更新之前已合并的文档数量。 |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | 获取转换过程的日志。 |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认的 PDF 格式保存，且不进行转换。 |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | 如果为 true，则在执行合并时复制文件的逻辑结构。 |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | 如果为 true，则复制大纲。 |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | 此属性定义在合并过程中遇到损坏文件时的行为。可能的值有：StopWithError 和 ConcatenateIgnoringCorrupted。 |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | 在执行合并时遇到的问题数组。对于传递给 Concatenate() 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才能使用此属性。 |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | 如果为 true，则在合并期间进行增量更新。 |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | 如果为 true，则会从源文档复制操作。默认值：true。 |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | 如果为 true，则在合并表单时会使字段名称唯一。将向字段名称添加后缀，后缀模板可在 UniqueSuffix 属性中指定。 |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | 获取最近发生的异常。可用于检查失败原因。 |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | 如果此属性为 true，具有相同名称的合并文档的可选内容将合并为结果文档中的同一层。否则，具有相同名称的层将保存为结果文档中的不同层。 |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | 如果为 true，重复的大纲将被合并。 |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | 获取或设置优化标志。如果设置此标志，结果文件中相等的资源流将合并为一个 PDF 对象。这可以减小结果文件的大小，但可能导致执行速度变慢和更大的内存需求。默认值：false。 |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | 如果源输入 Pdf 文件已加密，则设置所有者密码。此属性尚未实现。 |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | 如果为 true，则将第一个文档的用户权限应用于合并文档。所有其他文档的用户权限将被忽略。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | 如果为 true，所有签名将从字段中移除（字段保留）；否则，可能会出现无效签名。 |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | 在合并表单时添加到字段名称以使其唯一的后缀格式。此字符串必须包含 %NUM% 子串，该子串将被数字替换。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段 "fieldName" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。 |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | 如果使用此选项，则目标文档将定期保存到磁盘，后续的合并将作为增量更新应用于该文档。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。 |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。边距以初始页面尺寸的百分比指定。 |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | 调整页面内容的大小并添加指定的边距。边距以初始页面尺寸的百分比指定。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | 在文档页面中添加分页符。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | 在文档页面中添加分页符。 |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | 在文档页面中添加分页符。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | 在 firstInputStream 末尾追加从 portStream 中选取的页面，范围为 startPage 到 endPage。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | 追加从 portStreams 中的文档数组中选取的页面。结果文档包括 firstInputFile 以及所有 portStreams 文档中位于 startPage 到 endPage 范围的页面。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | 在 firstInputFile 末尾追加从 portFile 中选取的页面，范围为 startPage 到 endPage。 |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | 追加从 portFiles 文档中选取的页面。结果文档包括 firstInputFile 以及所有 portFiles 文档中位于 startPage 到 endPage 范围的页面。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | 连接文档。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | 连接文件 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | 将多个文件连接为一个文件。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | 连接两个文件。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | 连接两个文件。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充缺失的页面。例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档后，结果文档的页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充缺失的页面。例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档后，结果文档的页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | 提取由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | 提取由数字数组指定的页面，并保存为新的 PDF 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | 从输入文件中提取页面，并保存为新的 Pdf 文件。 |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | 从输入文件中提取页面，并保存为新的 Pdf 文件。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | 将另一个文件中的页面插入到输入的 Pdf 文件中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | 将另一个文件中的页面插入到输入的 Pdf 文件中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | 将另一个文件中的页面插入到输入的 Pdf 文件中。 |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | 在指定位置将另一个文件中的页面插入到 Pdf 文件中。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | 从 InputStream 创建小册子并输出到 outputStream。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | 从输入文件创建小册子并输出到输出文件。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | 从输入流创建小册子并将结果保存到输出流。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | 从 inputFile 创建小册子并输出到 outputFile。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | 从 firstInputStream 创建自定义小册子并输出到 outputStream。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | 从 firstInputStream 创建小册子并输出到 outputStream。 |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | 从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | 从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。outputStream 的每一页将包含多页，这些页面是来自相同页码的输入流页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果为 false，则垂直堆叠。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | 从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含两页，一页来自第一个输入文件，另一页来自第二个输入文件。这两页水平堆叠。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | 从多个输入 PDF 文件生成 N‑Up 文档到 outputFile。outputFile 的每一页将包含多页，这些多页是来自输入文件中相同页码的页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | 从输入流生成 N‑Up 文档并将结果保存到输出流。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | 从 firstInputFile 生成 N‑Up 文档到 outputFile。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | 从第一个输入流生成 N‑Up 文档并保存到输出流。 |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | 从输入文件生成 N‑Up 文档到 outputFile。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | 调整文档页面的大小。收缩的页面周围会添加空白边距。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | 调整文档页面的大小。收缩的页面周围会添加空白边距。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | 调整文档页面内容的大小。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | 调整文档中页面内容的大小。如果页面被收缩，页面周围会添加空白边距。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | 调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以默认空间单位指定。 |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | 调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以默认空间单位指定。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | 调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以百分比指定。 |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | 调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以百分比指定。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | 从起始位置拆分到指定位置，并将前半部分保存到输出流。 |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | 将 Pdf 文件从第一页拆分到指定位置，并将前半部分另存为新文件。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | 将 Pdf 文件拆分为多个文档。文档可以是单页或多页。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | 从指定位置拆分，并将后半部分保存为新文件流。 |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | 从指定位置拆分，并将后半部分保存为新文件。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | 将 Pdf 文件拆分为单页文档。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | 将 PDF 文件拆分为单页文档。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | 将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名 temaplate 指定。 |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | 将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名 temaplate 指定。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | 追加从 portStreams 中的文档数组中选取的页面。结果文档包括 firstInputFile 以及所有 portStreams 文档中位于 startPage 到 endPage 范围的页面。 |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | 追加从 portFiles 文档中选取的页面。结果文档包括 firstInputFile 以及所有 portFiles 文档中位于 startPage 到 endPage 范围的页面。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | 连接文档。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | 连接文件 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | 将多个文件连接为一个文件。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | 连接两个文件。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充缺失的页面。例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档后，结果文档的页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充缺失的页面。例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档后，结果文档的页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | 提取由数字数组指定的页面，并保存为新的 Pdf 文件。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | 提取由数字数组指定的页面，并保存为新的 PDF 文件。 |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | 从输入文件中提取页面，并保存为新的 Pdf 文件。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | 将另一个文件中的页面插入到输入的 Pdf 文件中。 |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | 将另一个文件中的页面插入到输入的 Pdf 文件中。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | 从 InputStream 创建小册子并输出到 outputStream。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | 从输入文件创建小册子并输出到输出文件。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | 从输入流创建小册子并将结果保存到输出流。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | 从 inputFile 创建小册子并输出到 outputFile。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | 从 firstInputStream 创建自定义小册子并输出到 outputStream。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | 从 firstInputStream 创建小册子并输出到 outputStream。 |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | 从 firstInputFile 创建自定义小册子并输出到 outputFile。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | 从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | 从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。outputStream 的每一页将包含多页，这些页面是来自相同页码的输入流页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果为 false，则垂直堆叠。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | 从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含两页，一页来自第一个输入文件，另一页来自第二个输入文件。这两页水平堆叠。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | 从多个输入 PDF 文件生成 N‑Up 文档到 outputFile。outputFile 的每一页将包含多页，这些多页是来自输入文件中相同页码的页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | 从输入流生成 N‑Up 文档并将结果保存到输出流。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | 从 firstInputFile 生成 N‑Up 文档到 outputFile。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | 从第一个输入流生成 N‑Up 文档并保存到输出流。 |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | 从输入文件生成 N‑Up 文档到 outputFile。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | 调整文档页面内容的大小。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | 调整文档中页面内容的大小。如果页面被收缩，页面周围会添加空白边距。 |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | 调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以默认空间单位指定。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | 从起始位置拆分到指定位置，并将前半部分保存到输出流。 |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | 将 Pdf 文件从第一页拆分到指定位置，并将前半部分另存为新文件。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | 从指定位置拆分，并将后半部分保存为新文件流。 |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | 从指定位置拆分，并将后半部分保存为新文件。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | 在合并过程中遇到损坏的文件时执行的操作。 |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | 用于指定 Page 调整大小参数的类。允许设置以下参数：结果 Page 的尺寸（宽度、高度），以默认空间单位或初始 Pages 尺寸的百分比表示；左、上、下、右边距，以默认空间单位或初始 Page 尺寸的百分比表示；某些值可以为 null，以便自动计算。这些值将在显式指定的值计算后，从剩余 Page 尺寸中计算。例如：如果 Page 宽度 = 100，且新 Page 宽度指定为 60 单位，则左、右边距会自动计算为 (100 - 60) / 2 = 15。此类在 ResizeContents 方法中使用。 |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | 边距或内容大小的值，以默认空间单位的百分比表示。此类在 ContentsResizeParameters 中使用。 |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | 在合并期间提供有关损坏文件信息的类。 |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | 分页符位置的数据。 |

### 另请参见

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


