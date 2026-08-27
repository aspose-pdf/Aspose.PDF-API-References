---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。"
type: docs
weight: 410
url: /zh/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

实现对 PDF 文件的操作：合并、拆分、提取页面、制作小册子等。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | PdfFileEditor 构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> 调整页面内容大小并添加指定的边距。边距以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> 调整页面内容大小并添加指定的边距。边距以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> 调整页面内容大小并添加指定的边距。边距以初始页面尺寸的百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> 调整页面内容大小并添加指定的边距。边距以初始页面尺寸的百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | 在文档页面中添加分页符。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> 追加页面，这些页面从 portStreams 中的文档数组中选择。结果文档包括 firstInputFile 和所有 portStreams 文档在 startPage 到 endPage 范围内的页面。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> 追加页面，这些页面从 portStream 中在 startPage 到 endPage 范围内选择，并在 firstInputStream 末尾追加。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> 追加页面，这些页面从 portFiles 文档中选择。结果文档包括 firstInputFile 和所有 portFiles 文档在 startPage 到 endPage 范围内的页面。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> 追加页面，这些页面从 portFile 中在 startPage 到 endPage 范围内选择，并在 firstInputFile 末尾追加。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | 合并文档。 |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> 合并文件 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充空缺位置。 例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档将生成结果文档，页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> 合并两个文件。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> 将多个文件合并为一个文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> 合并两个文件。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充空缺位置。 例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档将生成结果文档，页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> 提取由数字数组指定的页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> 从输入文件提取页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> 提取由数字数组指定的页面，并保存为新的 PDF 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> 从输入文件提取页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> 如果设置为 true，则在发生错误时抛出异常。否则不抛出异常，方法在失败时返回 false。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | 获取当操作结果以附件形式存储到 HttpServletResponse 对象时的附件名称。 |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | 如果设置为 true，操作完成后流将被关闭。 |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | 当 UseDiskBuffer 设置为 true 时，在连接期间在进行新的增量更新之前已连接的文档数量。 |
| [getContentDisposition](#getContentDisposition--) | 获取当操作结果存储到 HttpServletResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。 |
| [getConversionLog](#getConversionLog--) | 获取转换过程的日志。 |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | 如果为 true，则在执行连接时复制文件的逻辑结构。 |
| [getCopyOutlines](#getCopyOutlines--) | 如果为 true，则复制大纲。 |
| [getCorruptedFileAction](#getCorruptedFileAction--) | 此属性定义在连接过程中遇到损坏文件时的行为。可能的值有：StopWithError 和 ConcatenateIgnoringCorrupted。 |
| [getCorruptedItems](#getCorruptedItems--) | <p> 在执行连接时遇到的问题数组。对于传递给 Concatenate() 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才能使用此属性。 </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PunPdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | 表示在连接期间工作的内部进度事件处理器，并将内部连接阶段的事件转换为外部客户代码。 |
| [getIncrementalUpdates](#getIncrementalUpdates--) | 如果为 true，则在连接期间进行增量更新。 |
| [getKeepActions](#getKeepActions--) | 如果为 true，则会从源文档复制操作。 |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | 如果为 true，则在表单连接时使字段名称唯一。将向字段名称添加后缀，后缀模板可在 UniqueSuffix 属性中指定。 |
| [getLastException](#getLastException--) | 获取最近一次发生的异常。 |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | 如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。 |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | 如果为 true，合并重复的大纲。 |
| [getOptimizeSize](#getOptimizeSize--) | 获取或设置优化标志。 |
| [getOwnerPassword](#getOwnerPassword--) | 获取当源输入 Pdf 文件被加密时的所有者密码。此属性尚未实现。 |
| [getPreserveUserRights](#getPreserveUserRights--) | 如果为 true，则将第一个文档的用户权限应用于连接后的文档。 |
| [getRemoveSignatures](#getRemoveSignatures--) | 如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。 |
| [getSaveOptions](#getSaveOptions--) | 获取或设置当结果存储为 HttpServletResponse 时的保存选项。默认值：PdfSaveOptions。 |
| [getUniqueSuffix](#getUniqueSuffix--) | 获取在表单连接时添加到字段名称以使其唯一的后缀格式。此字符串必须包含 %NUM% 子串，该子串将在运行时被数字替换。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段 "fieldName" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> 将另一个文件的页面插入到输入的 Pdf 文件中。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> 将另一个文件的页面插入到输入的 Pdf 文件中。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> 将另一个文件的页面插入到输入的 Pdf 文件中。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> 将另一个文件的页面插入到 Pdf 文件的指定位置。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | 有时 PDF 包含由多个相同的平铺背景图像并排放置而构成的页面或表格单元格的背景图像。 |
| [isUseDiskBuffer](#isUseDiskBuffer--) | 如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> 将 InputStream 制作成小册子并输出到 outputStream。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> 将 firstInputStream 定制为小册子并输出到 outputStream。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> 将输入流制作成小册子并将结果保存到输出流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> 将 firstInputStream 制作成小册子并输出到 outputStream（使用 PageSize.A4 和自定义页码）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> 将输入文件制作成小册子并输出到输出文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> 将 firstInputFile 定制为小册子并输出到 outputFile。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> 将 inputFile 制作成小册子并输出到 outputFile（使用 PageSize.A4）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> 将 firstInputFile 定制为小册子并输出到 outputFile（使用 PageSize.A4 和自定义页码）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> 将多个输入 PDF 流制作成 N-Up 文档并输出到 outputStream。outputStream 的每一页将包含多页，这些多页是来自相同页码的输入流页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果为 false，则垂直堆叠。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> 将两个输入 PDF 流制作成 N-Up 文档并输出到 outputStream。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> 将输入流制作成 N-Up 文档并将结果保存到输出流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> 将第一个输入流制作成 N-Up 文档并输出到输出流（使用 PageSize.A4）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> 将多个输入 PDF 文件制作成 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含多页，这些页是来自输入文件中相同页码的页面组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> 将 firstInputFile 制作成 N-Up 文档并输出到 outputFile。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> 将输入文件制作成 N-Up 文档并输出到 outputFile。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> 将两个输入 PDF 文件制作成 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含两页，一页来自第一个输入文件，另一页来自第二个输入文件。这两页水平堆叠。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的内容大小。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档中页面的内容大小。 |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct(\"input.pdf\", \"output.pdf\", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | 调整文档页面的大小。 |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> 如果设置为 true，则在发生错误时抛出异常。否则不抛出异常，方法在失败时返回 false。 </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 设置附件的名称，当操作结果以附件形式存储到 HttpServletResponse 对象时使用。 |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> 如果设置为 true，则在操作后关闭流。 </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | 当 UseDiskBuffer 设置为 true 时，在连接期间在进行新的增量更新之前已连接的文档数量。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置内容在操作结果存储到 HttpServletResponse 对象时的存储方式。可能的取值：inline / attachment。默认：inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存且不进行转换。 |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | 如果为 true，则在执行连接时复制文件的逻辑结构。 |
| [setCopyOutlines](#setCopyOutlines-boolean-) | 如果为 true，则复制大纲。 |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | 此属性定义在连接过程中遇到损坏文件时的行为。可能的值有：StopWithError 和 ConcatenateIgnoringCorrupted。 |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | 表示在连接期间工作的内部进度事件处理器，并将内部连接阶段的事件转换为外部客户代码。 |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | 如果为 true，则在连接期间进行增量更新。 |
| [setKeepActions](#setKeepActions-boolean-) | 如果为 true，则会从源文档复制操作。 |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | 如果为 true，则在表单连接时使字段名称唯一。将向字段名称添加后缀，后缀模板可在 UniqueSuffix 属性中指定。 |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | 如果此属性为 true，具有相同名称的连接文档的可选内容将合并为结果文档中的一个层。 |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | 如果为 true，合并重复的大纲。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 获取或设置优化标志。 |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | 如果源输入 Pdf 文件已加密，则设置所有者密码。此属性尚未实现。 |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | 如果为 true，则将第一个文档的用户权限应用于连接后的文档。 |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | 如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 设置在结果存储为 HttpServletResponse 时的保存选项。默认值：PdfSaveOptions。 |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | 有时 PDF 包含由多个相同的平铺背景图像并排放置而构成的页面或表格单元格的背景图像。 |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> 设置在表单合并时添加到字段名以使其唯一的后缀格式。该字符串必须包含 %NUM% 子串，系统会用数字替换。例如如果 UniqueSuffix = \"ABC%NUM%\"，则字段 \"fieldName\" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。 </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( \"_%NUM%\"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | 如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> 从起始位置拆分到指定位置，并将前段保存到输出流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> 该操作后流不会被关闭。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> 将 Pdf 文件从第一页拆分到指定位置，并将前段保存为新文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst(\"input.pdf\", 5, \"out.pdf\"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | 将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。 |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | 将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> 从指定位置拆分，并将后段保存为新的文件流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> 除非指定了 CloseConcatedStreams，否则该操作后流不会被关闭。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> 从指定位置拆分，并将后段保存为新文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd(\"input.pdf\", 5, \"out.pdf\"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | 将 Pdf 文件拆分为单页文档。 |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |
| [splitToPages](#splitToPages-java.lang.String-) | 将 PDF 文件拆分为单页文档。 |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | 将 Pdf 文件拆分为单页文档并保存到指定路径。 |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

PdfFileEditor 构造函数。

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> 调整页面内容大小并添加指定的边距。边距以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> 调整页面内容大小并添加指定的边距。边距以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> 调整页面内容大小并添加指定的边距。边距以初始页面尺寸的百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> 调整页面内容大小并添加指定的边距。边距以初始页面尺寸的百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
在文档页面中添加分页符。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> 追加页面，这些页面从 portStreams 中的文档数组中选择。结果文档包括 firstInputFile 和所有 portStreams 文档在 startPage 到 endPage 范围内的页面。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> 追加页面，这些页面从 portStream 中在 startPage 到 endPage 范围内选择，并在 firstInputStream 末尾追加。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> 追加页面，这些页面从 portFiles 文档中选择。结果文档包括 firstInputFile 和所有 portFiles 文档在 startPage 到 endPage 范围内的页面。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> 追加页面，这些页面从 portFile 中在 startPage 到 endPage 范围内选择，并在 firstInputFile 末尾追加。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
合并文档。

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> 合并文件 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充空缺位置。 例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档将生成结果文档，页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> 合并两个文件。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> 将多个文件合并为一个文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> 合并两个文件。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> 将两个 Pdf 文档交替合并为一个新的 Pdf 文档，并用空白页填充空缺位置。 例如：document1 有 5 页：p1、p2、p3、p4、p5。document2 有 3 页：p1'、p2'、p3'。合并这两个 Pdf 文档将生成结果文档，页面顺序为：p1、p1'、p2、p2'、p3、p3'、p4、blankpage、p5、blankpage。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> 从输入文件中删除由数字数组指定的页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> 提取由数字数组指定的页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> 从输入文件提取页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> 提取由数字数组指定的页面，并保存为新的 PDF 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> 从输入文件提取页面，并保存为新的 Pdf 文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> 如果设置为 true，则在发生错误时抛出异常。否则不抛出异常，方法在失败时返回 false。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
布尔值 @deprecated 此属性已弃用，不能用于允许抛出异常。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

获取当操作结果以附件形式存储到 HttpServletResponse 对象时的附件名称。

**Returns:**
字符串值

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

获取当操作结果存储到 HttpServletResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。

**Returns:**
ContentDisposition 元素 @see ContentDisposition

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

此属性定义在连接过程中遇到损坏文件时的行为。可能的值有：StopWithError 和 ConcatenateIgnoringCorrupted。

**Returns:**
ConcatenateCorruptedFileAction 元素 @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> 在执行连接时遇到的问题数组。对于传递给 Concatenate() 函数的每个损坏文档，都会创建一个新的 CorruptedItem 条目。仅当 CorruptedFileAction 为 ConcatenateIgnoringCorrupted 时才能使用此属性。 </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PunPdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

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

如果为 true，则在表单连接时使字段名称唯一。将向字段名称添加后缀，后缀模板可在 UniqueSuffix 属性中指定。

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

获取当源输入 Pdf 文件被加密时的所有者密码。此属性尚未实现。

**Returns:**
字符串值

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

如果为 true，则将第一个文档的用户权限应用于连接后的文档。

**Returns:**
布尔值

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。

**Returns:**
布尔值

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取或设置当结果存储为 HttpServletResponse 时的保存选项。默认值：PdfSaveOptions。

**Returns:**
SaveOptions 对象

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

获取在表单连接时添加到字段名称以使其唯一的后缀格式。此字符串必须包含 %NUM% 子串，该子串将在运行时被数字替换。例如，如果 UniqueSuffix = "ABC%NUM%"，则字段 "fieldName" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。

**Returns:**
字符串值

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> 将另一个文件的页面插入到输入的 Pdf 文件中。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> 将另一个文件的页面插入到输入的 Pdf 文件中。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> 将另一个文件的页面插入到输入的 Pdf 文件中。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> 将另一个文件的页面插入到 Pdf 文件的指定位置。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> 将 InputStream 制作成小册子并输出到 outputStream。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> 将 firstInputStream 定制为小册子并输出到 outputStream。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> 将输入流制作成小册子并将结果保存到输出流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> 将 firstInputStream 制作成小册子并输出到 outputStream（使用 PageSize.A4 和自定义页码）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> 将输入文件制作成小册子并输出到输出文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> 将 firstInputFile 定制为小册子并输出到 outputFile。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> 将 inputFile 制作成小册子并输出到 outputFile（使用 PageSize.A4）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> 将 firstInputFile 定制为小册子并输出到 outputFile（使用 PageSize.A4 和自定义页码）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> 将多个输入 PDF 流制作成 N-Up 文档并输出到 outputStream。outputStream 的每一页将包含多页，这些多页是来自相同页码的输入流页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果为 false，则垂直堆叠。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> 将两个输入 PDF 流制作成 N-Up 文档并输出到 outputStream。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> 将输入流制作成 N-Up 文档并将结果保存到输出流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> 将第一个输入流制作成 N-Up 文档并输出到输出流（使用 PageSize.A4）。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> 将多个输入 PDF 文件制作成 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含多页，这些页是来自输入文件中相同页码的页面组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> 将 firstInputFile 制作成 N-Up 文档并输出到 outputFile。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> 将输入文件制作成 N-Up 文档并输出到 outputFile。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> 将两个输入 PDF 文件制作成 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含两页，一页来自第一个输入文件，另一页来自第二个输入文件。这两页水平堆叠。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的内容大小。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档中页面的内容大小。

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> 调整文档页面内容的大小。缩小页面内容并添加边距。内容的新大小以百分比指定。 </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct(\"input.pdf\", \"output.pdf\", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
调整文档页面的大小。

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> 如果设置为 true，则在发生错误时抛出异常。否则不抛出异常，方法在失败时返回 false。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated 此属性已弃用，不能用于允许抛出异常。 |

### setAttachmentName {#setAttachmentName-java.lang.String-}
设置附件的名称，当操作结果以附件形式存储到 HttpServletResponse 对象时使用。

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> 如果设置为 true，则在操作后关闭流。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
设置内容在操作结果存储到 HttpServletResponse 对象时的存储方式。可能的取值：inline / attachment。默认：inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存且不进行转换。

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

此属性定义在连接过程中遇到损坏文件时的行为。可能的值有：StopWithError 和 ConcatenateIgnoringCorrupted。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @see ConcatenateCorruptedFileAction |

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

如果为 true，则在表单连接时使字段名称唯一。将向字段名称添加后缀，后缀模板可在 UniqueSuffix 属性中指定。

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
如果源输入 Pdf 文件已加密，则设置所有者密码。此属性尚未实现。

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
public final void setRemoveSignatures(boolean value)
```

如果为 true，所有签名将从字段中移除（字段仍然保留）；否则，可能会得到无效的签名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
设置在结果存储为 HttpServletResponse 时的保存选项。默认值：PdfSaveOptions。

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
<p> 设置在表单合并时添加到字段名以使其唯一的后缀格式。该字符串必须包含 %NUM% 子串，系统会用数字替换。例如如果 UniqueSuffix = \"ABC%NUM%\"，则字段 \"fieldName\" 的名称将为：fieldNameABC1、fieldNameABC2、fieldNameABC3 等。 </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( \"_%NUM%\"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

如果使用此选项，则目标文档将定期保存到磁盘，后续的连接将作为增量更新应用于该文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> 从起始位置拆分到指定位置，并将前段保存到输出流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> 该操作后流不会被关闭。

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> 将 Pdf 文件从第一页拆分到指定位置，并将前段保存为新文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst(\"input.pdf\", 5, \"out.pdf\"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
将 Pdf 文件拆分为多个文档。文档可以是单页的，也可以是多页的。

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> 从指定位置拆分，并将后段保存为新的文件流。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> 除非指定了 CloseConcatedStreams，否则该操作后流不会被关闭。

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> 从指定位置拆分，并将后段保存为新文件。 </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd(\"input.pdf\", 5, \"out.pdf\"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
将 Pdf 文件拆分为单页文档。

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
将 Pdf 文件拆分为单页文档并保存到指定路径。

### splitToPages {#splitToPages-java.lang.String-}
将 PDF 文件拆分为单页文档。

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
将 Pdf 文件拆分为单页文档并保存到指定路径。
