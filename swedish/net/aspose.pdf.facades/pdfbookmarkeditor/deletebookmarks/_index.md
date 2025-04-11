---
title: PdfBookmarkEditor.DeleteBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metod. Tar bort alla bokmärken i PDF-dokumentet
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Tar bort alla bokmärken i PDF-dokumentet.

```csharp
public void DeleteBookmarks()
```

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Tar bort bokmärket i PDF-dokumentet.

```csharp
public void DeleteBookmarks(string title)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| title | Sträng | Titeln på det borttagna bokmärket. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)