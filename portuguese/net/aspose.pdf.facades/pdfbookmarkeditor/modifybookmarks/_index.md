---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Modifica o título do marcador de acordo com o título de marcador especificado
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## Método PdfBookmarkEditor.ModifyBookmarks

Modifica o título do marcador de acordo com o título de marcador especificado.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sTitle | String | Título do marcador de origem. |
| dTitle | String | Título do marcador modificado. |

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)