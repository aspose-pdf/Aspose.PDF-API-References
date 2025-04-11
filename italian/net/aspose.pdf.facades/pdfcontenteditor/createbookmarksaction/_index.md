---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un segnalibro con l'azione specificata
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## Metodo PdfContentEditor.CreateBookmarksAction

Crea un segnalibro con l'azione specificata.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| title | String | Il titolo del segnalibro. |
| color | Color | Il colore del titolo del segnalibro. |
| boldFlag | Boolean | Il flag di attribuzione in grassetto. |
| italicFlag | Boolean | Il flag di attribuzione in corsivo. |
| file | String | Un altro file o applicazione richiesto quando il tipo di azione è "GoToR" o "Launch". |
| actionType | String | Il tipo di azione. Il valore può essere: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | La destinazione locale o la destinazione remota o l'URL. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)