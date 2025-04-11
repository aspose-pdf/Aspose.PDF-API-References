---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-Methode. Ändert den Titel des Lesezeichens gemäß dem angegebenen Lesezeichentitel
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks-Methode

Ändert den Titel des Lesezeichens gemäß dem angegebenen Lesezeichentitel.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sTitle | String | Quell-Lesezeichentitel. |
| dTitle | String | Geänderter Lesezeichentitel. |

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)