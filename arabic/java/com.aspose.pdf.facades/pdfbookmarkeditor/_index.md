---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة للعمل مع إشارات PDF بما في ذلك الإنشاء، التعديل، التصدير، الاستيراد والحذف."
type: docs
weight: 370
url: /ar/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

يمثل فئة للعمل مع إشارات PDF بما في ذلك الإنشاء، التعديل، التصدير، الاستيراد والحذف.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | يُهيئ كائنًا جديدًا {@code PdfBookmarkEditor}. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | يُهيئ كائنًا جديدًا {@code PdfBookmarkEditor}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | أغلق نسخة PdfBookmarkEditor وحرّر الموارد. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> ينشئ إشارات مرجعية للصفحات المحددة. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> ينشئ إشارة مرجعية للصفحة المحددة. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> ينشئ إشارات مرجعية لجميع الصفحات. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> ينشئ إشارات مرجعية لجميع الصفحات. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> ينشئ إشارات مرجعية لجميع الصفحات. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> يحذف جميع الإشارات المرجعية لوثيقة PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> يحذف جميع الإشارات المرجعية لوثيقة PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> يصدر العلامات المرجعية إلى ملف HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | يصدر العلامات المرجعية إلى تدفق XML. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> يصدر العلامات المرجعية إلى ملف XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> يستخرج العلامات المرجعية من جميع المستويات من المستند. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> يستخرج العلامات المرجعية من جميع المستويات من المستند. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | يستخرج العلامات المرجعية من جميع المستويات من المستند. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> يستخرج العلامات المرجعية من جميع المستويات من المستند. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> يصدر العلامات المرجعية إلى ملف HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | يستورد العلامات المرجعية إلى المستند من ملف XML. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> يستورد العلامات المرجعية إلى المستند من ملف XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> يغيّر عنوان العلامة المرجعية وفقًا للعنوان المحدد. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

يُهيئ كائنًا جديدًا {@code PdfBookmarkEditor}.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
يُهيئ كائنًا جديدًا {@code PdfBookmarkEditor}.

### close {#close--}
```
public void close()
```

أغلق نسخة PdfBookmarkEditor وحرّر الموارد.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> ينشئ إشارات مرجعية للصفحات المحددة. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> ينشئ إشارة مرجعية للصفحة المحددة. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> ينشئ إشارات مرجعية لجميع الصفحات. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> ينشئ إشارات مرجعية لجميع الصفحات. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> ينشئ إشارات مرجعية لجميع الصفحات. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> يحذف جميع الإشارات المرجعية لوثيقة PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> يحذف جميع الإشارات المرجعية لوثيقة PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> يصدر العلامات المرجعية إلى ملف HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
يصدر العلامات المرجعية إلى تدفق XML.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> يصدر العلامات المرجعية إلى ملف XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> يستخرج العلامات المرجعية من جميع المستويات من المستند. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
مجموعة العلامات المرجعية لجميع العلامات الموجودة في المستند.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> يستخرج العلامات المرجعية من جميع المستويات من المستند. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
مجموعة العلامات المرجعية لجميع العلامات الموجودة في المستند.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

يستخرج العلامات المرجعية من جميع المستويات من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| upperLevel |  | إذا كان true، يستخرج فقط العلامات المرجعية من المستوى العلوي. وإلا، يستخرج جميع العلامات المرجعية بشكل متكرر. |

**Returns:**
قائمة العلامات المرجعية المستخرجة.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> يستخرج العلامات المرجعية من جميع المستويات من المستند. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
مجموعة العلامات المرجعية لجميع العلامات الموجودة في المستند.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> يصدر العلامات المرجعية إلى ملف HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
يستورد العلامات المرجعية إلى المستند من ملف XML.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> يستورد العلامات المرجعية إلى المستند من ملف XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> يغيّر عنوان العلامة المرجعية وفقًا للعنوان المحدد. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre>
