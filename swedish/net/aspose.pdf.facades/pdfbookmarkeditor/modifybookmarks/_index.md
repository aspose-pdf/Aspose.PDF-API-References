---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfBookmarkEditor metod. Ändrar bokmärkesrubriken enligt den angivna bokmärkesrubriken"
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

Modifierar bokmärkestitel enligt den angivna bokmärkestiteln.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sTitle | String | Källbokmärkesrubrik. |
| dTitle | String | Modifierad bokmärkesrubrik. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


