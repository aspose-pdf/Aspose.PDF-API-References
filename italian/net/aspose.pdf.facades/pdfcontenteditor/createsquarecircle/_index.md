---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un'annotazione squarecircle"
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

Crea un'annotazione quadrato-circolo.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| clr | Color | Il colore del quadrato o del cerchio. |
| square | Boolean | True (square), false (sircle). |
| pagina | Int32 | Il numero della pagina originale dove verrà creata l'annotazione. |
| borderWidth | Int32 | La larghezza del bordo del quadrato o del cerchio. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


