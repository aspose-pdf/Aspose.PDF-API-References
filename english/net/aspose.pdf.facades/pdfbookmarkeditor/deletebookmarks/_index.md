---
title: PdfBookmarkEditor.DeleteBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor method. Deletes all bookmarks of the PDF document
type: docs
weight: 40
url: /net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Deletes all bookmarks of the PDF document.

```csharp
public void DeleteBookmarks()
```

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Deletes the bookmark of the PDF document.

```csharp
public void DeleteBookmarks(string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | The title of bookmark deleted. |

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


