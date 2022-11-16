---
title: PdfBookmarkEditor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示处理 PDF 文件书签的类，包括创建修改导出导入和删除。
type: docs
weight: 35
url: /zh/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfBookmarkEditor extends SaveableFacade
```

代表一个类来处理 PDF 文件的书签，包括创建、修改、导出、导入和删除。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfBookmarkEditor()](#PdfBookmarkEditor--) | 初始化新的 PdfBookmarkEditor 对象。 |
| [PdfBookmarkEditor(IDocument document)](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfBookmarkEditor 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭 PdfBookmarkEditor 实例并释放资源。 |
| [createBookmarkOfPage(String bookmarkName, int pageNumber)](#createBookmarkOfPage-java.lang.String-int-) | 为指定页面创建书签。 |
| [createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)](#createBookmarkOfPage-java.lang.String---int---) | 为指定页面创建书签。 |
| [createBookmarks()](#createBookmarks--) | 为所有页面创建书签。 |
| [createBookmarks(Bookmark bookmark)](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | 在文档中创建指定的书签。 |
| [createBookmarks(Color color, boolean boldFlag, boolean italicFlag)](#createBookmarks-java.awt.Color-boolean-boolean-) | 为具有指定颜色和样式（粗体、斜体）的所有页面创建书签。 |
| [deleteBookmarks()](#deleteBookmarks--) | 删除 PDF 文档的所有书签。 |
| [deleteBookmarks(String title)](#deleteBookmarks-java.lang.String-) | 删除 PDF 文档的书签。 |
| [dispose()](#dispose--) | 处理门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportBookmarksToHtml(String inPdfFile, String outHtmlFile)](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | 将书签导出到 HTML 文件。 |
| [exportBookmarksToXML(OutputStream output)](#exportBookmarksToXML-java.io.OutputStream-) | 将书签导出到 XML 流。 |
| [exportBookmarksToXML(String xmlFile)](#exportBookmarksToXML-java.lang.String-) | 将书签导出到 XML 文件。 |
| [extractBookmarks()](#extractBookmarks--) | 从文档中提取所有级别的书签。 |
| [extractBookmarks(boolean upperLevel)](#extractBookmarks-boolean-) | 从文档中提取所有级别的书签。 |
| [extractBookmarks(Bookmark bookmark)](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | 提取书签的子项，书签的标题类似于指定的 bookamrk。 |
| [extractBookmarks(String title)](#extractBookmarks-java.lang.String-) | 提取具有指定标题的书签。 |
| [extractBookmarksToHTML(String pdfFile, String cssFile)](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | 将书签导出到 HTML 文件。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [hashCode()](#hashCode--) |  |
| [importBookmarksWithXML(InputStream stream)](#importBookmarksWithXML-java.io.InputStream-) | 将书签从 XML 文件导入文档。 |
| [importBookmarksWithXML(String xmlFile)](#importBookmarksWithXML-java.lang.String-) | 将书签从 XML 文件导入文档。 |
| [modifyBookmarks(String sTitle, String dTitle)](#modifyBookmarks-java.lang.String-java.lang.String-) | 根据指定的书签标题修改书签标题。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定的流。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfBookmarkEditor() {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```


初始化新的 PdfBookmarkEditor 对象。

### PdfBookmarkEditor(IDocument document) {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
```
public PdfBookmarkEditor(IDocument document)
```


在文档的基础上初始化新的 PdfBookmarkEditor 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

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

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

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

### close() {#close--}
```
public void close()
```


关闭 PdfBookmarkEditor 实例并释放资源。

### createBookmarkOfPage(String bookmarkName, int pageNumber) {#createBookmarkOfPage-java.lang.String-int-}
```
public void createBookmarkOfPage(String bookmarkName, int pageNumber)
```


为指定页面创建书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarkOfPage("bookmark for page 1", 1);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bookmarkName | java.lang.String | 指定的书签名称。 |
| pageNumber | int | 指定的目标页面。 |

### createBookmarkOfPage(String[] bookmarkName, int[] pageNumber) {#createBookmarkOfPage-java.lang.String---int---}
```
public void createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)
```


为指定页面创建书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarkOfPage("bookmark for page 1", 1);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bookmarkName | java.lang.String[] | 书签标题数组。 |
| pageNumber | int[] | 书签目的地页面数组。 |

### createBookmarks() {#createBookmarks--}
```
public void createBookmarks()
```


为所有页面创建书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarks();
 editor.save("example_out.pdf");
```

### createBookmarks(Bookmark bookmark) {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
```
public void createBookmarks(Bookmark bookmark)
```


在文档中创建指定的书签。该方法可用于形成嵌套的书签层次结构。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
  editor.bindPdf("example.pdf");
  Bookmark bm1=new Bookmark();
  bm1.setPageNumber(1);
  bm1.setTitle("First child");
 	Bookmark bm2=new Bookmark();
 	bm2.setPageNumber(2);
  bm2.setTitle("Second child");
  Bookmark bm=new Bookmark();
  bm.setAction=(GoTo");
  bm.setPageNumber(1);
  bm.setTitle("Parent");
  Bookmarks bms=new Bookmarks();
  bms.add(bm1);
  bms.add(bm2);
  bm.setChildItem(bms);
  editor.setCreateBookmarks(bm);
  editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bookmark | [Bookmark](../../com.aspose.pdf.facades/bookmark) | 书签将添加到文档中。 |

### createBookmarks(Color color, boolean boldFlag, boolean italicFlag) {#createBookmarks-java.awt.Color-boolean-boolean-}
```
public void createBookmarks(Color color, boolean boldFlag, boolean italicFlag)
```


为具有指定颜色和样式（粗体、斜体）的所有页面创建书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarks(System.Drawing.Color.Red, true, true);
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | java.awt.Color | 标题的颜色。 |
| boldFlag | boolean | 大胆归属的旗帜。 |
| italicFlag | boolean | 斜体属性的标志。 |

### deleteBookmarks() {#deleteBookmarks--}
```
public void deleteBookmarks()
```


删除 PDF 文档的所有书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.deleteBookmarks();
 editor.save("example_out.pdf");
```

### deleteBookmarks(String title) {#deleteBookmarks-java.lang.String-}
```
public void deleteBookmarks(String title)
```


删除 PDF 文档的书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.deleteBookmarks("existing bookmark title");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | 书签的标题已删除。 |

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

此方法已过时，请改用 close() 。

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
### exportBookmarksToHtml(String inPdfFile, String outHtmlFile) {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
```
public static void exportBookmarksToHtml(String inPdfFile, String outHtmlFile)
```


将书签导出到 HTML 文件。

--------------------

```
PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inPdfFile | java.lang.String | 输入要导出书签的 PDF 文件。 |
| outHtmlFile | java.lang.String | 输出 HTML 文件 |

### exportBookmarksToXML(OutputStream output) {#exportBookmarksToXML-java.io.OutputStream-}
```
public void exportBookmarksToXML(OutputStream output)
```


将书签导出到 XML 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.OutputStream | 将存储数据的输出流。 |

### exportBookmarksToXML(String xmlFile) {#exportBookmarksToXML-java.lang.String-}
```
public void exportBookmarksToXML(String xmlFile)
```


将书签导出到 XML 文件。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.exportBookmarksToXML("bookmarks.xml");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | java.lang.String | 输出 XML 文件。 |

### extractBookmarks() {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```


从文档中提取所有级别的书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 Bookmarks bms = editor.ExtractBookmarks();
 for(Bookmark bm : bms)
     System.out.println(bm.Title);
```

**退货：**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - 文档中存在的所有书签的书签集合。
### extractBookmarks(boolean upperLevel) {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```


从文档中提取所有级别的书签。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| upperLevel | boolean | 如果为真，则仅提取上层书签。否则，递归地提取所有书签。 |

**退货：**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - 提取的书签列表。
### extractBookmarks(Bookmark bookmark) {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
```
public Bookmarks extractBookmarks(Bookmark bookmark)
```


提取书签的子项，书签的标题类似于指定的 bookamrk。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 Bookmark bookmark = new Bookmark();
 bookmark.setTitle ( "Title");
 Bookmarks bms = editor.ExtractBookmarks(bookmark);
 for(Bookmark bm : ```
(Iterable)
```bms)
     System.out.println(bm.Title);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bookmark | [Bookmark](../../com.aspose.pdf.facades/bookmark) | 指定的书签。 |

**退货：**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - 带有子书签的书签收藏。
### extractBookmarks(String title) {#extractBookmarks-java.lang.String-}
```
public Bookmarks extractBookmarks(String title)
```


提取具有指定标题的书签。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
  editor.bindPdf("example.pdf");
 	Bookmarks bms = editor.ExtractBookmarks("Title");
  for(Bookmark bm : ```
(Iterable)
```bms)
      System.out.println(bm.Title);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | java.lang.String | 提取的项目标题。 |

**退货：**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - 书签对象集合具有相同标题的项目。
### extractBookmarksToHTML(String pdfFile, String cssFile) {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
```
public void extractBookmarksToHTML(String pdfFile, String cssFile)
```


将书签导出到 HTML 文件。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.extractBookmarksToHTML("example.pdf", null);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfFile | java.lang.String | 将导出书签的 PDF 文件。 |
| cssFile | java.lang.String | 显示 HTML 文件的 CSS 文件，可以为空。 |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### importBookmarksWithXML(InputStream stream) {#importBookmarksWithXML-java.io.InputStream-}
```
public void importBookmarksWithXML(InputStream stream)
```


将书签从 XML 文件导入文档。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 带有书签数据的流。 |

### importBookmarksWithXML(String xmlFile) {#importBookmarksWithXML-java.lang.String-}
```
public void importBookmarksWithXML(String xmlFile)
```


将书签从 XML 文件导入文档。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.importBookmarksWithXML("bookmarks.xml");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | java.lang.String | 包含书签列表的 XML 文件。 |

### modifyBookmarks(String sTitle, String dTitle) {#modifyBookmarks-java.lang.String-java.lang.String-}
```
public void modifyBookmarks(String sTitle, String dTitle)
```


根据指定的书签标题修改书签标题。

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.modifyBookmarks("existing bookmark title", "new bookmark title");
 editor.save("example_out.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sTitle | java.lang.String | 源书签标题。 |
| dTitle | java.lang.String | 修改后的书签标题。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
