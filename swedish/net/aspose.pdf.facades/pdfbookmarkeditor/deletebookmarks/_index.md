---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfBookmarkEditor-metod. Tar bort alla bokmärken i PDF-dokumentet"
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Raderar alla bokmärken i PDF-dokumentet.

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

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Raderar bokmärket i PDF-dokumentet.

```csharp
public void DeleteBookmarks(string title)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| titel | String | Titeln på det borttagna bokmärket. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


