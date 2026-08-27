---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于处理 PDF 文件书签（包括创建、修改、导出、导入和删除）的类。"
type: docs
weight: 370
url: /zh/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

表示用于处理 PDF 文件书签（包括创建、修改、导出、导入和删除）的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | 初始化新的 {@code PdfBookmarkEditor} 对象。 |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | 初始化新的 {@code PdfBookmarkEditor} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [close](#close--) | 关闭 PdfBookmarkEditor 实例并释放资源。 |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> 为指定页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> 为指定页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> 为所有页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> 为所有页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> 为所有页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> 删除 PDF 文档的所有书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> 删除 PDF 文档的所有书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> 将书签导出为 HTML 文件。 </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | 将书签导出到 XML 流。 |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> 将书签导出为 XML 文件。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> 从文档中提取所有层级的书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> 从文档中提取所有层级的书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | 从文档中提取所有层级的书签。 |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> 从文档中提取所有层级的书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> 将书签导出为 HTML 文件。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | 从 XML 文件导入书签到文档。 |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> 从 XML 文件导入书签到文档。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> 根据指定的书签标题修改书签标题。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

初始化新的 {@code PdfBookmarkEditor} 对象。

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
初始化新的 {@code PdfBookmarkEditor} 对象。

### close {#close--}
```
public void close()
```

关闭 PdfBookmarkEditor 实例并释放资源。

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> 为指定页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> 为指定页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> 为所有页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> 为所有页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> 为所有页面创建书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> 删除 PDF 文档的所有书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> 删除 PDF 文档的所有书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> 将书签导出为 HTML 文件。 </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
将书签导出到 XML 流。

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> 将书签导出为 XML 文件。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> 从文档中提取所有层级的书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
文档中存在的所有书签的集合。

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> 从文档中提取所有层级的书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
文档中存在的所有书签的集合。

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

从文档中提取所有层级的书签。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| upperLevel |  | 如果为 true，则仅提取上层书签。否则，递归提取所有书签。 |

**Returns:**
提取的书签列表。

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> 从文档中提取所有层级的书签。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
文档中存在的所有书签的集合。

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> 将书签导出为 HTML 文件。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
从 XML 文件导入书签到文档。

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> 从 XML 文件导入书签到文档。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> 根据指定的书签标题修改书签标题。 </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre>
