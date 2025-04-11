---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria um marcador com a ação especificada
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## Método PdfContentEditor.CreateBookmarksAction

Cria um marcador com a ação especificada.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| title | String | O título do marcador. |
| color | Color | A cor do título do marcador. |
| boldFlag | Boolean | O indicador de atribuição em negrito. |
| italicFlag | Boolean | O indicador de atribuição em itálico. |
| file | String | Outro arquivo ou aplicativo necessário quando o tipo de ação é "GoToR" ou "Launch". |
| actionType | String | O tipo de ação. O valor pode ser: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | O destino local ou remoto ou URL. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)