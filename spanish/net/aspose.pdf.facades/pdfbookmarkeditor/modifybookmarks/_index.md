---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Modifica el título del marcador de acuerdo con el título de marcador especificado
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## Método PdfBookmarkEditor.ModifyBookmarks

Modifica el título del marcador de acuerdo con el título de marcador especificado.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sTitle | String | Título del marcador de origen. |
| dTitle | String | Título del marcador modificado. |

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)