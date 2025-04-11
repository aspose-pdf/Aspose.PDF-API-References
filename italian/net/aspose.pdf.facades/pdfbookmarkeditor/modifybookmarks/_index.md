---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfBookmarkEditor. Modifica il titolo del segnalibro secondo il titolo del segnalibro specificato
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## Metodo PdfBookmarkEditor.ModifyBookmarks

Modifica il titolo del segnalibro secondo il titolo del segnalibro specificato.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sTitle | String | Titolo del segnalibro sorgente. |
| dTitle | String | Titolo del segnalibro modificato. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)