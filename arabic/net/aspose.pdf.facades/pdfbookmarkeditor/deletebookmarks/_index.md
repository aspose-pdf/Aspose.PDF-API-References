---
title: PdfBookmarkEditor.DeleteBookmarks
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfBookmarkEditor. تحذف جميع العلامات المرجعية من مستند PDF
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

تحذف جميع العلامات المرجعية من مستند PDF.

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

تحذف العلامة المرجعية من مستند PDF.

```csharp
public void DeleteBookmarks(string title)
```

| المعامل | النوع | الوصف |
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