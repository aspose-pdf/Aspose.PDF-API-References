---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un collegamento a JavaScript nel documento PDF"
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

Crea un collegamento a JavaScript nel documento PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codice | String | Il codice JavaScript. |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| originalPage | Int32 | Il numero della pagina originale dove verrà creato il rettangolo associato al collegamento. |
| color | Color | Il colore del rettangolo per il clic attivo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


