---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un collegamento a JavaScript nel documento PDF
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## Metodo PdfContentEditor.CreateJavaScriptLink

Crea un collegamento a JavaScript nel documento PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| code | String | Il codice JavaScript. |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| originalPage | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo legato al collegamento. |
| color | Color | Il colore del rettangolo per il clic attivo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)