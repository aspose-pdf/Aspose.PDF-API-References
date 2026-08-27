---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfBookmarkEditor. تحذف جميع العلامات المرجعية في مستند PDF"
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

يحذف جميع الإشارات المرجعية في PDF Document.

```csharp
public void DeleteBookmarks()
```

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

يحذف الإشارة المرجعية في PDF Document.

```csharp
public void DeleteBookmarks(string title)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| title | String | عنوان العلامة المرجعية المحذوفة. |

## أمثلة

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


