---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-metod. Ändrar bokmärkets titel enligt den angivna bokmärkets titel
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks metod

Ändrar bokmärkets titel enligt den angivna bokmärkets titel.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sTitle | Sträng | Källbokmärkets titel. |
| dTitle | Sträng | Ändrad bokmärkets titel. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)