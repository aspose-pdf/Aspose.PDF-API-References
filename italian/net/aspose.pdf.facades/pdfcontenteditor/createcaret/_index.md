---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodo. crea annotazione di curatore.
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## Metodo PdfContentEditor.CreateCaret

Crea annotazione caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale dove verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| caretRect | Rectangle | I confini effettivi del caret sottostante. |
| symbol | String | Un simbolo sarà associato al caret. Il valore può essere: "P" (Paragrafo), "None". |
| annotContents | String | I contenuti dell'annotazione. |
| color | Color | Il colore dell'annotazione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)