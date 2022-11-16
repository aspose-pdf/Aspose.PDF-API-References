---
title: PdfContentEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示一个类来编辑 PDF 文件内容。
type: docs
weight: 36
url: /zh/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfContentEditor extends SaveableFacade
```

表示一个类来编辑 PDF 文件的内容。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfContentEditor()](#PdfContentEditor--) | PdfContentEditor 对象的构造函数。 |
| [PdfContentEditor(IDocument document)](#PdfContentEditor-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfContentEditor 对象。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT-CLOSE) | 文档事件类型。 |
| [DOCUMENT_OPEN](#DOCUMENT-OPEN) | 文档事件类型。 |
| [DOCUMENT_PRINTED](#DOCUMENT-PRINTED) | 文档事件类型。 |
| [DOCUMENT_SAVED](#DOCUMENT-SAVED) | 文档事件类型。 |
| [DOCUMENT_WILL_PRINT](#DOCUMENT-WILL-PRINT) | 文档事件类型。 |
| [DOCUMENT_WILL_SAVE](#DOCUMENT-WILL-SAVE) | 文档事件类型。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addDocumentAdditionalAction(String eventType, String code)](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | 为文档事件添加额外的操作。 |
| [addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description)](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | 添加没有注释的文档附件。 |
| [addDocumentAttachment(String fileAttachmentPath, String description)](#addDocumentAttachment-java.lang.String-java.lang.String-) | 添加没有注释的文档附件。 |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | 绑定 PDF 流以进行编辑。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | 绑定 PDF 文件进行编辑。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [changeViewerPreference(int viewerAttribution)](#changeViewerPreference-int-) | 更改视图首选项。 |
| [close()](#close--) | 关闭打开的文档。 |
| [createApplicationLink(Rectangle rect, String application, int page)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | 创建链接以启动 PDF 文档中的应用程序。 |
| [createApplicationLink(Rectangle rect, String application, int page, Color clr)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | 创建链接以启动 PDF 文档中的应用程序。 |
| [createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---) | 创建链接以启动 PDF 文档中的应用程序。 |
| [createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination)](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | 使用指定的操作创建书签。 |
| [createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color)](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | 创建插入符号注释。 |
| [createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName)](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-int---) | 在 PDF 文档中创建自定义操作的链接。 |
| [createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name)](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | 创建文件附件注释。 |
| [createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name)](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | 创建文件附件注释。 |
| [createFreeText(Rectangle rect, String contents, int page)](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | 在 PDF 文档中创建自由文本注释 |
| [createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color)](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | 在 PDF 文档中创建指向 JavaScript 的链接。 |
| [createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray)](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int---java.lang.String---) | 创建线注释。 |
| [createLocalLink(Rectangle rect, int desPage, int originalPage)](#createLocalLink-java.awt.Rectangle-int-int-) | 在 PDF 文档中创建本地链接。 |
| [createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | 在 PDF 文档中创建本地链接。 |
| [createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName)](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-int---) | 在 PDF 文档中创建本地链接。 |
| [createMarkup(Rectangle rect, String contents, int type, int page, Color clr)](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | 在 PDF 文档中创建标记注释。 |
| [createMovie(Rectangle rect, String filePath, int page)](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | 创建到另一个 PDF 文档页面的链接。 |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | 创建到另一个 PDF 文档页面的链接。 |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-int---) | 创建到另一个 PDF 文档页面的链接。 |
| [createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 创建折线注释。 |
| [createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 创建多边形注释。 |
| [createPopup(Rectangle rect, String contents, boolean open, int page)](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | 在 PDF 文档中创建弹出式注释。 |
| [createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | 创建橡皮图章注释。 |
| [createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | 创建橡皮图章注释。 |
| [createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | 创建橡皮图章注释。 |
| [createSound(Rectangle rect, String filePath, String name, int page, String rate)](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth)](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | 创建方圆注释。 |
| [createText(Rectangle rect, String title, String contents, boolean open, String icon, int page)](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | 在 PDF 文档中创建文本注释 |
| [createWebLink(Rectangle rect, String url, int originalPage)](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | 在 PDF 文档中创建 Web 链接。 |
| [createWebLink(Rectangle rect, String url, int originalPage, Color clr)](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | 在 PDF 文档中创建 Web 链接。 |
| [createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName)](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---) | 在 PDF 文档中创建 Web 链接。 |
| [deleteAttachments()](#deleteAttachments--) | 删除 PDF 文档中的所有附件。 |
| [deleteImage()](#deleteImage--) | 从 PDF 文档中删除所有图像。 |
| [deleteImage(int pageNumber, int[] index)](#deleteImage-int-int---) | 删除指定页面上的指定图像。 |
| [deleteStamp(int pageNumber, int[] index)](#deleteStamp-int-int---) | 通过标记索引删除指定页面上的多个标记。 |
| [deleteStampById(int stampId)](#deleteStampById-int-) | 从文档的所有页面删除 ID 标记。 |
| [deleteStampById(int pageNumber, int stampId)](#deleteStampById-int-int-) | 按图章 ID 删除指定页面上的图章。 |
| [deleteStampByIds(int pageNumber, int[] stampIds)](#deleteStampByIds-int-int---) | 通过多个图章 ID 删除指定页面上的图章。 |
| [deleteStampByIds(int[] stampIds)](#deleteStampByIds-int---) | 从文档的所有页面中删除具有指定 ID 的图章。 |
| [dispose()](#dispose--) | 处理门面。 |
| [drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | 创建曲线注释。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractLink()](#extractLink--) | 提取 PDF 文档中包含的链接实例的集合。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getReplaceTextStrategy()](#getReplaceTextStrategy--) | 获取一组用于替换文本操作的参数 |
| [getStamps(int pageNumber)](#getStamps-int-) | 返回页面上的邮票数组。 |
| [getTextEditOptions()](#getTextEditOptions--) | 获取文本编辑选项。 |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | 获取文本替换选项。 |
| [getTextSearchOptions()](#getTextSearchOptions--) | 获取文本搜索选项。 |
| [getViewerPreference()](#getViewerPreference--) | 返回视图首选项。 |
| [hashCode()](#hashCode--) |  |
| [hideStampById(int pageNumber, int stampId)](#hideStampById-int-int-) | 隐藏图章。 |
| [moveStamp(int pageNumber, int stampIndex, double x, double y)](#moveStamp-int-int-double-double-) | 更改图章在页面上的位置。 |
| [moveStampById(int pageNumber, int stampId, double x, double y)](#moveStampById-int-int-double-double-) | 更改图章在页面上的位置。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDocumentOpenAction()](#removeDocumentOpenAction--) | 从文档中删除打开操作。 |
| [replaceImage(int pageNumber, int index, String imageFile)](#replaceImage-int-int-java.lang.String-) | 用另一个图像替换 PDF 文档指定页面上的指定图像。 |
| [replaceText(String srcString, int thePage, String destString)](#replaceText-java.lang.String-int-java.lang.String-) | 在指定页面上替换 PDF 文件中的文本。 |
| [replaceText(String srcString, int thePage, String destString, TextState textState)](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | 在指定页面上替换 PDF 文件中的文本。 |
| [replaceText(String srcString, String destString)](#replaceText-java.lang.String-java.lang.String-) | 替换 PDF 文件中的文本。 |
| [replaceText(String srcString, String destString, TextState textState)](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | 使用指定的 TextState 对象替换 PDF 文件中的文本。 |
| [replaceText(String srcString, String destString, int fontSize)](#replaceText-java.lang.String-java.lang.String-int-) | 替换 PDF 文件中的文本并设置字体大小。 |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定的流。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [setReplaceTextStrategy(ReplaceTextStrategy value)](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | 为替换文本操作设置一组参数 |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 设置文本编辑选项。 |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | 设置文本替换选项。 |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置文本搜索选项。 |
| [showStampById(int pageNumber, int stampId)](#showStampById-int-int-) | 显示被 HiddenStampById 隐藏的图章。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfContentEditor() {#PdfContentEditor--}
```
public PdfContentEditor()
```


PdfContentEditor 对象的构造函数。

### PdfContentEditor(IDocument document) {#PdfContentEditor-com.aspose.pdf.IDocument-}
```
public PdfContentEditor(IDocument document)
```


在文档的基础上初始化新的 PdfContentEditor 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### DOCUMENT_CLOSE {#DOCUMENT-CLOSE}
```
public static final String DOCUMENT_CLOSE
```


文档事件类型。关闭文档。

### DOCUMENT_OPEN {#DOCUMENT-OPEN}
```
public static final String DOCUMENT_OPEN
```


文档事件类型。打开文档。

### DOCUMENT_PRINTED {#DOCUMENT-PRINTED}
```
public static final String DOCUMENT_PRINTED
```


文档事件类型。打印后执行一个动作。

### DOCUMENT_SAVED {#DOCUMENT-SAVED}
```
public static final String DOCUMENT_SAVED
```


文档事件类型。保存后执行动作。

### DOCUMENT_WILL_PRINT {#DOCUMENT-WILL-PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```


文档事件类型。打印前执行一个动作。

### DOCUMENT_WILL_SAVE {#DOCUMENT-WILL-SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```


文档事件类型。保存前执行一个动作。

### addDocumentAdditionalAction(String eventType, String code) {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
```
public void addDocumentAdditionalAction(String eventType, String code)
```


为文档事件添加额外的操作。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| eventType | java.lang.String | 文档事件类型。 |
| code | java.lang.String | JavaScript 的代码。 |

### addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description) {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
```
public void addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description)
```


添加没有注释的文档附件。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 InputStream attStream = new FileInputStream("attachment_file.pdf")
     editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
     editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileAttachmentStream | java.io.InputStream | 文件的流将被附加。 |
| fileAttachmentName | java.lang.String | 附件名称。 |
| description | java.lang.String | 描述信息。 |

### addDocumentAttachment(String fileAttachmentPath, String description) {#addDocumentAttachment-java.lang.String-java.lang.String-}
```
public void addDocumentAttachment(String fileAttachmentPath, String description)
```


添加没有注释的文档附件。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileAttachmentPath | java.lang.String | 文件的路径将被附加。 |
| description | java.lang.String | 描述信息。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


绑定 PDF 流以进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 要编辑的 PDF 流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


绑定 PDF 文件进行编辑。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 要编辑的 PDF 文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### changeViewerPreference(int viewerAttribution) {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```


更改视图首选项。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.changeViewerPreference(ViewerPreference.HideMenubar);
 editor.changeViewerPreference(ViewerPreference.PageModeUseNone);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| viewerAttribution | int | ViewerPreference 类中定义的视图属性。 |

### close() {#close--}
```
public void close()
```


关闭打开的文档。

### createApplicationLink(Rectangle rect, String application, int page) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
```
public void createApplicationLink(Rectangle rect, String application, int page)
```


创建链接以启动 PDF 文档中的应用程序。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createApplicationLink(new Rectangle(0, 0, 100, 100), "explorer", 1 });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| application | java.lang.String | 要启动的应用程序的路径。 |
| page | int | 将创建与链接绑定的矩形的原始页面数。 |

### createApplicationLink(Rectangle rect, String application, int page, Color clr) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
```
public void createApplicationLink(Rectangle rect, String application, int page, Color clr)
```


创建链接以启动 PDF 文档中的应用程序。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createApplicationLink(new Rectangle(0, 0, 100, 100),
     "explorer", 1, Color.red });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| application | java.lang.String | 要启动的应用程序的路径。 |
| page | int | 将创建与链接绑定的矩形的原始页面数。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |

### createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---}
```
public void createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName)
```


创建链接以启动 PDF 文档中的应用程序。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| application | java.lang.String | 要启动的应用程序的路径。 |
| page | int | 将创建与链接绑定的矩形的原始页面数。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |
| actionName | int[] | 对应于 Acrobat 查看器中执行的菜单项的操作数组（PredefinedAction 枚举的成员）。 |

### createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination) {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
```
public void createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination)
```


使用指定的操作创建书签。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarksAction("bookmark title",
     Color.red, true, true, null, "GoTo", 1(page number));
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | 书签的标题。 |
| color | java.awt.Color | 书签标题的颜色。 |
| boldFlag | boolean | 大胆归属的旗帜。 |
| italicFlag | boolean | 斜体属性的标志。 |
| file | java.lang.String | 操作类型为“GoToR”或“启动”时需要的另一个文件或应用程序。 |
| actionType | java.lang.String | 动作类型。值可以是：“GoToR”、“Launch”、“GoTo”、“URI”。 |
| destination | java.lang.String | 本地目标或远程目标或 URL。 |

### createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color) {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
```
public void createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color)
```


创建插入符号注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createCaret(1,
 	    new Rectangle(50, 50, 100, 100),
 	    new Rectangle(60, 60, 70, 70),
 	    "None", "Welcome to Aspose", Color.red);
  editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| caretRect | java.awt.Rectangle | 底层插入符号的实际边界。 |
| symbol | java.lang.String | 符号将与插入符号相关联。值可以是：“P”（段落）、“无”。 |
| annotContents | java.lang.String | 注释的内容。 |
| color | java.awt.Color | 注释的颜色。 |

### createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName) {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-int---}
```
public void createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName)
```


在 PDF 文档中创建自定义操作的链接。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| originalPage | int | 将创建与链接绑定的矩形的原始页面数。 |
| color | java.awt.Color | 活动点击矩形的颜色。 |
| actionName | int[] | 对应于 Acrobat 查看器中执行的菜单项的操作数组（PredefinedAction 枚举的成员）。 |

### createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name) {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
```
public void createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name)
```


创建文件附件注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 java.io.InputStream attStream = new java.io.FileInputStream("attachment_file.pdf");

     editor.createFileAttachment(new Rectangle(0, 0, 100, 100),
         "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
     editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| contents | java.lang.String | 注释的内容。 |
| attachmentStream | java.io.InputStream | 附件文件流。 |
| attachmentName | java.lang.String | 附件名称。 |
| page | int | 将在其中创建注释的原始页码。 |
| name | java.lang.String | 图标的名称将用于显示注释。该值可以是：“Graph”、“PushPin”、“Paperclip”、“Tag”。 |

### createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name) {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
```
public void createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name)
```


创建文件附件注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createFileAttachment(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| contents | java.lang.String | 注释的内容。 |
| filePath | java.lang.String | 文件的路径将被附加。 |
| page | int | 将在其中创建注释的原始页码。 |
| name | java.lang.String | 图标的名称将用于显示注释。该值可以是：“Graph”、“PushPin”、“Paperclip”、“Tag”。 |

### createFreeText(Rectangle rect, String contents, int page) {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
```
public void createFreeText(Rectangle rect, String contents, int page)
```


在 PDF 文档中创建自由文本注释

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createFreeText(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| contents | java.lang.String | 注释的内容。 |
| page | int | 将在其中创建文本注释的原始页码。 |

### createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color) {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
```
public void createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color)
```


在 PDF 文档中创建指向 JavaScript 的链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createJavaScriptLink("app.alert('welcome to aspose!');",
     new Rectangle(0, 0, 100, 100), 1, Color.red });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| code | java.lang.String | JavaScript 代码。 |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| originalPage | int | 将创建与链接绑定的矩形的原始页面数。 |
| color | java.awt.Color | 活动点击矩形的颜色。 |

### createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray) {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int---java.lang.String---}
```
public void createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray)
```


创建线注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLine(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
     1, 1, Color.red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| contents | java.lang.String | 注释的内容。 |
| x1 | float | 直线的起始水平坐标。 |
| y1 | float | 线的起始垂直坐标。 |
| x2 | float | 线的结束水平坐标。 |
| y2 | float | 线的结束垂直坐标。 |
| page | int | 将在其中创建注释的原始页码。 |
| border | int | 以磅为单位的边框宽度。如果此值为 0，则不绘制边框。默认值为 1。 |
| clr | java.awt.Color | 线的颜色。 |
| borderStyle | java.lang.String | 边框样式指定要在绘制线条时使用的宽度和破折号图案。该值可以是：“S”（实线）、“D”（虚线）、“B”（斜角）、“I”（内嵌）、“U”（下划线）。 |
| dashArray | int[] | 一个破折号数组，定义用于绘制虚线边框的破折号和间隙模式。如果使用它，borderSyle 必须相应地设置为“D”。 |
| LEArray | java.lang.String[] | 两个值的数组，分别指定绘图线的开始和结束样式。值可以是：“Square”、“Circle”、“Diamond”、“OpenArrow”、“ClosedArrow”、“None”、“Butt”、“ROpenArrow”、“RClosedArrow”、“Slash”。 |

### createLocalLink(Rectangle rect, int desPage, int originalPage) {#createLocalLink-java.awt.Rectangle-int-int-}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage)
```


在 PDF 文档中创建本地链接。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| desPage | int | 目标页面。 |
| originalPage | int | 将创建与本地链接绑定的矩形的原始页面数。 |

### createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr) {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```


在 PDF 文档中创建本地链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLocalLink(new Rectangle(0, 0, 100, 100),
     2, 1, Color.red });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| desPage | int | 目标页面。 |
| originalPage | int | 将创建与本地链接绑定的矩形的原始页面数。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |

### createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName) {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-int---}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName)
```


在 PDF 文档中创建本地链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLocalLink(new Rectangle(0, 0, 100, 100),
     2, 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| desPage | int | 目标页面。 |
| originalPage | int | 将创建与本地链接绑定的矩形的原始页面数。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |
| actionName | int[] | 对应于 Acrobat 查看器中执行的菜单项的操作数组（PredefinedAction 枚举的成员）。 |

### createMarkup(Rectangle rect, String contents, int type, int page, Color clr) {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
```
public void createMarkup(Rectangle rect, String contents, int type, int page, Color clr)
```


在 PDF 文档中创建标记注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createMarkup(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", 0, 1, Color.red);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义页面上注释位置的矩形。 |
| contents | java.lang.String | 注释的内容。 |
| type | int | 标记注释的类型。可以是 0（突出显示）、1（下划线）、2（删除线）、3（波浪线）。 |
| page | int | 将在其中创建注释的原始页码。 |
| clr | java.awt.Color | 标记的颜色。 |

### createMovie(Rectangle rect, String filePath, int page) {#createMovie-java.awt.Rectangle-java.lang.String-int-}
```
public void createMovie(Rectangle rect, String filePath, int page)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle |  |
| filePath | java.lang.String |  |
| page | int |  |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage)
```


创建到另一个 PDF 文档页面的链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| remotePdf | java.lang.String | 将打开哪一页的 PDF 文档。 |
| originalPage | int | 将创建与链接绑定的矩形的原始页面数。 |
| destinationPage | int | 目标页面。 |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr)
```


创建到另一个 PDF 文档页面的链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100),
     "another_example.pdf", 1, 1, Color.red });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| remotePdf | java.lang.String | 将打开哪一页的 PDF 文档。 |
| originalPage | int | 将创建与链接绑定的矩形的原始页面数。 |
| destinationPage | int | 目标页面。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-int---}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName)
```


创建到另一个 PDF 文档页面的链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100),
     "another_example.pdf", 1, 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| remotePdf | java.lang.String | 将打开哪一页的 PDF 文档。 |
| originalPage | int | 将创建与链接绑定的矩形的原始页面数。 |
| destinationPage | int | 目标页面。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |
| actionName | int[] | 对应于 Acrobat 查看器中执行的菜单项的操作数组（PredefinedAction 枚举的成员）。 |

### createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


创建折线注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100, 100, 50 });
 lineInfo.setVisibility ( true);
 editor.createPolyLine(lineInfo, 1 , new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | LineInfo 类的实例。 |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| annotContents | java.lang.String | 注释的内容。 |

### createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


创建多边形注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100, 100, 50 });
 lineInfo.setVisibility ( true);
 editor.createPolygon(lineInfo, 1 , new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | LineInfo 类的实例。 |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| annotContents | java.lang.String | 注释的内容。 |

### createPopup(Rectangle rect, String contents, boolean open, int page) {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
```
public void createPopup(Rectangle rect, String contents, boolean open, int page)
```


在 PDF 文档中创建弹出式注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPopup(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| contents | java.lang.String | 注释的内容。 |
| open | boolean | 一个标志，指定弹出式注释最初是否应该显示为打开状态。 |
| page | int | 将在其中创建注释的原始页码。 |

### createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
```
public void createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream)
```


创建橡皮图章注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
  InputStream appStream = new FileInputStream("appearance_file.pdf");
 	    editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	        "Welcome to Aspose", Color.red, appStream);
      editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| annotContents | java.lang.String | 注释的内容。 |
| color | java.awt.Color | 注释的颜色。 |
| appearanceStream | java.io.InputStream | 外观文件流。 |

### createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
```
public void createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile)
```


创建橡皮图章注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red, "appearance_file.pdf");
  editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| annotContents | java.lang.String | 注释的内容。 |
| color | java.awt.Color | 注释的颜色。 |
| appearanceFile | java.lang.String | 外观文件路径。 |

### createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
```
public void createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color)
```


创建橡皮图章注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red);
  editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| icon | java.lang.String | 字符串值 |
| annotContents | java.lang.String | 注释的内容。 |
| color | java.awt.Color | 注释的颜色。 |

### createSound(Rectangle rect, String filePath, String name, int page, String rate) {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
```
public void createSound(Rectangle rect, String filePath, String name, int page, String rate)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle |  |
| filePath | java.lang.String |  |
| name | java.lang.String |  |
| page | int |  |
| rate | java.lang.String |  |

### createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth) {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
```
public void createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth)
```


创建方圆注释。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createSquareCircle(new Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red, false, 1, 5);
  editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| contents | java.lang.String | 注释的内容。 |
| clr | java.awt.Color | 正方形或圆形的颜色。 |
| square | boolean | 真（方形），假（圆形）。 |
| page | int | 将在其中创建注释的原始页码。 |
| borderWidth | int | 正方形或圆形的边框宽度。 |

### createText(Rectangle rect, String title, String contents, boolean open, String icon, int page) {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
```
public void createText(Rectangle rect, String title, String contents, boolean open, String icon, int page)
```


在 PDF 文档中创建文本注释

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createText(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| title | java.lang.String | 注释的标题。 |
| contents | java.lang.String | 注释的内容。 |
| open | boolean | 一个标志，指定注释最初是否应显示为打开状态。 |
| icon | java.lang.String | 图标的名称将用于显示注释。这个值可以是："Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | int | 将在其中创建文本注释的原始页码。 |

### createWebLink(Rectangle rect, String url, int originalPage) {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
```
public void createWebLink(Rectangle rect, String url, int originalPage)
```


在 PDF 文档中创建 Web 链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| url | java.lang.String | Web 链接目标。 |
| originalPage | int | 将创建与 Web 链接绑定的矩形的原始页面数。 |

### createWebLink(Rectangle rect, String url, int originalPage, Color clr) {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
```
public void createWebLink(Rectangle rect, String url, int originalPage, Color clr)
```


在 PDF 文档中创建 Web 链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100),
     "http://www.aspose.com", 1, Color.red });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| url | java.lang.String | Web 链接目标。 |
| originalPage | int | 将创建与 Web 链接绑定的矩形的原始页面数。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |

### createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName) {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---}
```
public void createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName)
```


在 PDF 文档中创建 Web 链接。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100),
     "http://www.aspose.com", 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | java.awt.Rectangle | 活动点击的矩形。 |
| url | java.lang.String | Web 链接目标。 |
| originalPage | int | 将在其上创建与 Web 链接绑定的矩形的原始页面数。 |
| clr | java.awt.Color | 活动点击矩形的颜色。 |
| actionName | int[] | 对应于 Acrobat 查看器中执行的菜单项的操作数组（PredefinedAction 枚举的成员）。 |

### deleteAttachments() {#deleteAttachments--}
```
public void deleteAttachments()
```


删除 PDF 文档中的所有附件。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAttachments();
 editor.save("example_out.pdf");
```

### deleteImage() {#deleteImage--}
```
public void deleteImage()
```


从 PDF 文档中删除所有图像。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteImage();
 editor.save("example_out.pdf");
```

### deleteImage(int pageNumber, int[] index) {#deleteImage-int-int---}
```
public void deleteImage(int pageNumber, int[] index)
```


删除指定页面上的指定图像。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteImage(1, new int[] {1, 2});
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 必须删除图像的页数。 |
| index | int[] | 数组代表图像的索引。 |

### deleteStamp(int pageNumber, int[] index) {#deleteStamp-int-int---}
```
public void deleteStamp(int pageNumber, int[] index)
```


通过标记索引删除指定页面上的多个标记。

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStamp(1, new int[] { 2, 3, 5} );
 contentEditor.save("outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 戳记将被删除的页码。 |
| index | int[] | 邮票索引。 |

### deleteStampById(int stampId) {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```


从文档的所有页面删除 ID 标记。

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampById(100);
 contentEditor.save("outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stampId | int | 应删除的戳记标识符。 |

### deleteStampById(int pageNumber, int stampId) {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```


按图章 ID 删除指定页面上的图章。

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampById(1, 100);
 contentEditor.save("outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 戳记将被删除的页码。 |
| stampId | int | 应删除的戳记标识符。 |

### deleteStampByIds(int pageNumber, int[] stampIds) {#deleteStampByIds-int-int---}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```


通过多个图章 ID 删除指定页面上的图章。

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampByIds(1, new int[] { 100, 101 } );
 contentEditor.save("outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 将删除图章的页码。 |
| stampIds | int[] | 邮票 ID 数组。 |

### deleteStampByIds(int[] stampIds) {#deleteStampByIds-int---}
```
public void deleteStampByIds(int[] stampIds)
```


从文档的所有页面中删除具有指定 ID 的图章。

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampByIds(new int[] { 102, 103 } );
 contentEditor.save("outfile.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stampIds | int[] | 邮票 ID 数组。 |

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

此方法已过时，请改用 close() 。

### drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


创建曲线注释。

```
PdfContentEditor editor = new PdfContentEditor();
 newApiEditor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100 });  //x1, y1, x2, y2, .. xn, yn
 lineInfo.setVisibility ( true);
 editor.drawCurve(lineInfo, 1, new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | LineInfo 类的实例。 |
| page | int | 将在其中创建注释的原始页码。 |
| annotRect | java.awt.Rectangle | 定义注释在页面上的位置的注释矩形。 |
| annotContents | java.lang.String | 注释的内容。 |

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
### extractLink() {#extractLink--}
```
public List<Annotation> extractLink()
```


提取 PDF 文档中包含的链接实例的集合。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 List links = editor.extractLink();
 for (object obj : links)
 {
     Link link = (Link)obj;
     // work with Link instance
 }
```

**退货：**
java.util.List<com.aspose.pdf.Annotation> - Link 对象的集合
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getReplaceTextStrategy() {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```


获取一组用于替换文本操作的参数

**退货：**
[ReplaceTextStrategy](../../com.aspose.pdf.facades/replacetextstrategy) 替换文本策略元素
### getStamps(int pageNumber) {#getStamps-int-}
```
public StampInfo[] getStamps(int pageNumber)
```


返回页面上的邮票数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 将在其中搜索邮票的页码。 |

**退货：**
com.aspose.pdf.facades.StampInfo[] - 邮票阵列。
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


获取文本编辑选项。

**退货：**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - TextEditOptions 元素
### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


获取文本替换选项。

**退货：**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) TextReplaceOptions 元素
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


获取文本搜索选项。

**退货：**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) TextSearchOptions 元素
### getViewerPreference() {#getViewerPreference--}
```
public int getViewerPreference()
```


返回视图首选项。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 int prefValue = editor.GetViewerPreference();
 if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
 { // ... }
```

**退货：**
int - 返回一组 ViewerPrefernece 标志
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### hideStampById(int pageNumber, int stampId) {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```


隐藏图章。隐藏后，可以使用 ShowStampById 方法恢复图章可见性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页码。 |
| stampId | int | 应该隐藏的邮票标识符。 |

### moveStamp(int pageNumber, int stampIndex, double x, double y) {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```


更改图章在页面上的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页数。 |
| stampIndex | int | 页面上的图章索引。 |
| x | double | 新邮票水平位置。 |
| y | double | 新邮票垂直位置。 |

### moveStampById(int pageNumber, int stampId, double x, double y) {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```


更改图章在页面上的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页码。 |
| stampId | int | 应移动的邮票标识符。 |
| x | double | 页面上的新图章水平位置。 |
| y | double | 页面上的新图章垂直位置。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeDocumentOpenAction() {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```


从文档中删除打开操作。当连接多个在启动时使用显式“GoTo”操作的文档时，此操作很有用。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.removeDocumentOpenAction();
 editor.save("example_out.pdf");
```

### replaceImage(int pageNumber, int index, String imageFile) {#replaceImage-int-int-java.lang.String-}
```
public void replaceImage(int pageNumber, int index, String imageFile)
```


用另一个图像替换 PDF 文档指定页面上的指定图像。

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.replaceImage(1, 1, "image.jpg");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 替换图像的页数。 |
| index | int | 必须替换图像对象的索引。 |
| imageFile | java.lang.String | 图像文件将用于替换。 |

### replaceText(String srcString, int thePage, String destString) {#replaceText-java.lang.String-int-java.lang.String-}
```
public boolean replaceText(String srcString, int thePage, String destString)
```


在指定页面上替换 PDF 文件中的文本。

--------------------

```
The example demonstrates how to replace text in PDF document on the specified page.


 // open document
 Document doc = new Document(inFile);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // change text
 editor.replaceText("hello world", 1, "hi world");
 // save document
 doc.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | java.lang.String | 要更换的刺。 |
| thePage | int | 页码（所有页面均为 0） |
| destString | java.lang.String | 替换字符串。 |

**退货：**
boolean - 如果进行了替换则返回 true。
### replaceText(String srcString, int thePage, String destString, TextState textState) {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
```
public boolean replaceText(String srcString, int thePage, String destString, TextState textState)
```


在指定页面上替换 PDF 文件中的文本。可以指定 TextState 对象（字体系列、颜色）来替换文本。

--------------------

```
The example demonstrates how to replace text on the first page of the PDF document and set ```
TextState
```
 新文本的文本属性。


 // 打开文档
 文档 doc = 新文档(inFile);
 com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("信使新");
 font.isEmbedded（真）；
 // 创建 PdfContentEditor 对象来编辑文本
 PdfContentEditor 编辑器 = new PdfContentEditor();
 editor.bindPdf(doc);
 // 创建文本状态对象
 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState();
 textState.setFont(字体);
 textState.setFontSize ( 17);
 textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic);
 textState.setForegroundColor ( com.aspose.pdf.Color.getRed());
 // 改变指定字体的文本
 editor.replaceText("hello world", 1, "hi world", textState);
 // 保存文件
 文档保存（输出文件）；
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The string to be replaced. |
| thePage | int | Page number (0 means "all pages"). |
| destString | java.lang.String | The replaced string. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state (Text Color, Font etc). |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, String destString) {#replaceText-java.lang.String-java.lang.String-}
```
公共布尔替换文本（字符串 srcString，字符串 destString）
```


Replaces text in the PDF file.

--------------------

```
该示例演示如何替换 PDF 文档中的文本。


 // 打开文档
 文档 doc = 新文档(inFile);
 // 创建 PdfContentEditor 对象来编辑文本
 PdfContentEditor 编辑器 = new PdfContentEditor();
 editor.bindPdf(doc);
 // 改变文本
 editor.replaceText("hello world", "hi world");
 // 保存文件
 文档保存（输出文件）；
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The string to be replaced. |
| destString | java.lang.String | Replacing string. |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, String destString, TextState textState) {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
```
public boolean replaceText(String srcString, String destString, TextState textState)
```


Replaces text in the PDF file using specified  TextState  object.

--------------------

```
该示例演示如何替换文本和设置 ```
文本状态
``` text properties for the new text.


 Document doc = new Document(inFile);
 // Create font and mark it to be embedded
 com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New");
 font.isEmbedded ( true);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // create textState object
 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState();
 textState.setFont ( font);
 textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic);
 // change text with specified font
 editor.replaceText("hello world", "hi world", textState);
 // save document
 doc.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | java.lang.String | 要替换的字符串 |
| destString | java.lang.String | 替换字符串 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 文本状态（文本颜色、字体等） |

**退货：**
boolean - 如果进行了替换则返回 true。
### replaceText(String srcString, String destString, int fontSize) {#replaceText-java.lang.String-java.lang.String-int-}
```
public boolean replaceText(String srcString, String destString, int fontSize)
```


替换 PDF 文件中的文本并设置字体大小。

--------------------

```
The example demonstrates how to replace text and set font size for the new text.


 // open document
 Document doc = new Document(inFile);
 // Create font and mark it to be embedded
 com.aspose.pdf.Font font = FontRepository.FindFont("Courier New");
 font.isEmbedded ( true);
 // create PdfContentEditor object to edit text
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // change text with specified font
 editor.replaceText("hello world", "hi world", 14);
 // save document
 doc.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcString | java.lang.String | 要替换的字符串。 |
| destString | java.lang.String | 替换字符串。 |
| fontSize | int | 字体大小。 |

**退货：**
boolean - 如果进行了替换则返回 true。
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


将 PDF 文档保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 目标流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将 PDF 文档保存到指定文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 目标文件。 |

### setReplaceTextStrategy(ReplaceTextStrategy value) {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
```
public void setReplaceTextStrategy(ReplaceTextStrategy value)
```


为替换文本操作设置一组参数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ReplaceTextStrategy](../../com.aspose.pdf.facades/replacetextstrategy) | ReplaceTextStrategy 元素 |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


设置文本编辑选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | setTextEditOptions 元素 |

### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions(TextReplaceOptions value)
```


设置文本替换选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | TextReplaceOptions 元素 |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


设置文本搜索选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions 元素 |

### showStampById(int pageNumber, int stampId) {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```


显示被 HiddenStampById 隐藏的图章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页码。 |
| stampId | int | 应显示的邮票标识符。 |

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
