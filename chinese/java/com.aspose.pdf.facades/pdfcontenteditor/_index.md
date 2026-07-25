---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于编辑 PDF 文件内容的类。"
type: docs
weight: 380
url: /zh/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

表示用于编辑 PDF 文件内容的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | 文档事件类型。关闭文档。 |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | 文档事件类型。打开文档。 |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | 文档事件类型。打印后执行操作。 |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | 文档事件类型。保存后执行操作。 |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | 文档事件类型。打印前执行操作。 |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | 文档事件类型。保存前执行操作。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | PdfContentEditor 对象的构造函数。 |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | PdfContentEditor 对象的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> 为文档事件添加额外操作。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> 添加文档附件（无注释）。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> 添加文档附件（无注释）。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | 绑定 PDF 流以进行编辑。 |
| [bindPdf](#bindPdf-java.lang.String-) | 绑定 PDF 文件以进行编辑。 |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> 更改视图首选项。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | 关闭已打开的文档。 |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | 在 PDF 文档中创建用于启动应用程序的链接。 |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | 在 PDF 文档中创建用于启动应用程序的链接。 |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | 在 PDF 文档中创建用于启动应用程序的链接。 |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | 创建具有指定操作的书签。 |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | 创建插入符号注释。 |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | 在 PDF 文档中创建指向自定义操作的链接。 |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | 创建文件附件注释。 |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | 创建文件附件注释。 |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | 在 PDF 文档中创建自由文本注释 |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | 在 PDF 文档中创建指向 JavaScript 的链接。 |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | 创建线条注释。 |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | 在 PDF 文档中创建本地链接。 |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | 在 PDF 文档中创建本地链接。 |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | 在 PDF 文档中创建本地链接。 |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | 在 PDF 文档中创建标记注释。 |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | 创建指向另一个 PDF 文档页面的链接。 |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | 创建指向另一个 PDF 文档页面的链接。 |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | 创建指向另一个 PDF 文档页面的链接。 |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 创建多边形注释。 |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 创建折线注释。 |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | 在 PDF 文档中创建弹出注释。 |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | 创建橡皮图章注释。 |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | 创建橡皮图章注释。 |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | 创建橡皮图章注释。 |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | 创建方形-圆形注释。 |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | 在 PDF 文档中创建文本注释 |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | 在 PDF 文档中创建网页链接。 |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | 在 PDF 文档中创建网页链接。 |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | 在 PDF 文档中创建网页链接。 |
| [deleteAttachments](#deleteAttachments--) | <p> 删除 PDF 文档中的所有附件。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> 删除 PDF 文档中的所有图像。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> 删除指定页面上的指定图像。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> 通过印章索引删除指定页面上的多个印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> 从文档的所有页面中按 ID 删除印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> 按印章 ID 删除指定页面上的印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> 从文档的所有页面中删除具有指定 ID 的印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> 通过多个印章 ID 删除指定页面上的印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 创建曲线注释。 |
| [extractLink](#extractLink--) | <p> 提取 PDF 文档中包含的 Link 实例集合。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | 获取替换文本操作的一组参数 |
| [getStamps](#getStamps-int-) | 返回页面上印章的数组。 |
| [getTextEditOptions](#getTextEditOptions--) | 获取文本编辑选项。 |
| [getTextReplaceOptions](#getTextReplaceOptions--) | 获取文本替换选项。 |
| [getTextSearchOptions](#getTextSearchOptions--) | 获取文本搜索选项。 |
| [getViewerPreference](#getViewerPreference--) | <p> 返回视图首选项。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | 隐藏印章。隐藏后，可以使用 ShowStampById 方法恢复印章的可见性。 |
| [moveStamp](#moveStamp-int-int-double-double-) | 更改印章在页面上的位置。 |
| [moveStampById](#moveStampById-int-int-double-double-) | 更改印章在页面上的位置。 |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> 从文档中移除打开操作。此操作在合并多个在启动时使用显式 'GoTo' 操作的文档时非常有用。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> 在 PDF 文档的指定页面上将指定图像替换为另一图像。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> 在指定页面上替换 PDF 文件中的文本。 </p> <hr> <pre> The example demonstrates how to replace text in PDF document on the specified page. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // 使用指定字体更改文本 editor.replaceText("hello world", 1, "hi world", textState); // 保存文档 doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> 替换 PDF 文件中的文本。 </p> <hr> <pre> 示例演示如何在 PDF 文档中替换文本。默认情况下，它会替换首次找到的文本。 // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> 替换 PDF 文件中的文本并设置字体大小。 </p> <hr> <pre> 示例演示如何替换文本并为新文本设置字体大小。 // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // 使用指定字体更改文本 editor.replaceText("hello world", "hi world", textState); // 保存文档 doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | 为替换文本操作设置一组参数 |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 设置文本编辑选项。 |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | 设置文本替换选项。 |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置文本搜索选项。 |
| [showStampById](#showStampById-int-int-) | 显示由 HiddenStampById 隐藏的印章。 |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

文档事件类型。关闭文档。

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

文档事件类型。打开文档。

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

文档事件类型。打印后执行操作。

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

文档事件类型。保存后执行操作。

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

文档事件类型。打印前执行操作。

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

文档事件类型。保存前执行操作。

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

PdfContentEditor 对象的构造函数。

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
PdfContentEditor 对象的构造函数。

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> 为文档事件添加额外操作。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> 添加文档附件（无注释）。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> 添加文档附件（无注释）。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
绑定 PDF 流以进行编辑。

### bindPdf {#bindPdf-java.lang.String-}
绑定 PDF 文件以进行编辑。

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> 更改视图首选项。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| viewerAttribution |  | 在 ViewerPreference 类中定义的视图属性。 |

### close {#close--}
```
public void close()
```

关闭已打开的文档。

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
在 PDF 文档中创建用于启动应用程序的链接。

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
在 PDF 文档中创建用于启动应用程序的链接。

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
在 PDF 文档中创建用于启动应用程序的链接。

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
创建具有指定操作的书签。

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
创建插入符号注释。

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
在 PDF 文档中创建指向自定义操作的链接。

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
创建文件附件注释。

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
创建文件附件注释。

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
在 PDF 文档中创建自由文本注释

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
在 PDF 文档中创建指向 JavaScript 的链接。

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
创建线条注释。

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
在 PDF 文档中创建本地链接。

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
在 PDF 文档中创建本地链接。

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
在 PDF 文档中创建本地链接。

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
在 PDF 文档中创建标记注释。

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
创建指向另一个 PDF 文档页面的链接。

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
创建指向另一个 PDF 文档页面的链接。

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
创建指向另一个 PDF 文档页面的链接。

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
创建多边形注释。

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
创建折线注释。

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
在 PDF 文档中创建弹出注释。

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
创建橡皮图章注释。

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
创建橡皮图章注释。

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
创建橡皮图章注释。

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
创建方形-圆形注释。

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
在 PDF 文档中创建文本注释

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
在 PDF 文档中创建网页链接。

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
在 PDF 文档中创建网页链接。

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
在 PDF 文档中创建网页链接。

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> 删除 PDF 文档中的所有附件。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> 删除 PDF 文档中的所有图像。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> 删除指定页面上的指定图像。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 需要删除图像的页面编号。 |
| 索引 |  | 一个数组表示图像的索引。 |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> 通过印章索引删除指定页面上的多个印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 将删除印章的页面编号。 |
| 索引 |  | 印章索引。 |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> 从文档的所有页面中按 ID 删除印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stampId |  | 应删除的印章标识符。 |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> 按印章 ID 删除指定页面上的印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 将删除印章的页面编号。 |
| stampId |  | 应删除的印章标识符。 |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> 从文档的所有页面中删除具有指定 ID 的印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stampIds |  | 印章 ID 的数组。 |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> 通过多个印章 ID 删除指定页面上的印章。 </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 将删除印章的页码。 |
| stampIds |  | 印章 ID 的数组。 |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
创建曲线注释。

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> 提取 PDF 文档中包含的 Link 实例集合。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
Link 对象的集合

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

获取替换文本操作的一组参数

**Returns:**
ReplaceTextStrategy 元素

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

返回页面上印章的数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 将搜索印章的页码。 |

**Returns:**
印章数组。

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

获取文本编辑选项。

**Returns:**
TextEditOptions 元素

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

获取文本替换选项。

**Returns:**
TextReplaceOptions 元素

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

获取文本搜索选项。

**Returns:**
TextSearchOptions 元素

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> 返回视图首选项。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
返回 ViewerPrefernece 标志的集合

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

隐藏印章。隐藏后，可以使用 ShowStampById 方法恢复印章的可见性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 页面编号。 |
| stampId |  | 应隐藏的印章标识符。 |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

更改印章在页面上的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 页码。 |
| stampIndex |  | 页面上印章的索引。 |
| x |  | 新印章的水平位置。 |
| y |  | 新印章的垂直位置。 |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

更改印章在页面上的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 页码。 |
| stampId |  | 应移动的印章标识符。 |
| x |  | 页面上新印章的水平位置。 |
| y |  | 页面上新印章的垂直位置。 |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> 从文档中移除打开操作。此操作在合并多个在启动时使用显式 'GoTo' 操作的文档时非常有用。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> 在 PDF 文档的指定页面上将指定图像替换为另一图像。 </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> 在指定页面上替换 PDF 文件中的文本。 </p> <hr> <pre> The example demonstrates how to replace text in PDF document on the specified page. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> 在指定页面的 PDF 文件中替换文本。可以指定 {@code TextState} 对象（字体系列、颜色）来替换文本。 </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText(\"hello world\", 1, \"hi world\", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> 替换 PDF 文件中的文本。 </p> <hr> <pre> 示例演示如何在 PDF 文档中替换文本。默认情况下，它会替换首次找到的文本。 // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> 替换 PDF 文件中的文本并设置字体大小。 </p> <hr> <pre> 示例演示如何替换文本并为新文本设置字体大小。 // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> 使用指定的 {@code TextState} 对象在 PDF 文件中替换文本。 </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Courier New\"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText(\"hello world\", \"hi world\", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
为替换文本操作设置一组参数

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
设置文本编辑选项。

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
设置文本替换选项。

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
设置文本搜索选项。

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

显示由 HiddenStampById 隐藏的印章。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber |  | 页面编号。 |
| stampId |  | 应显示的印章标识符。 |
