---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates squarecircle annotation
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## Metodo PdfContentEditor.CreateSquareCircle

Crea annotazione quadrato-cerchio.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| clr | Color | Il colore del quadrato o del cerchio. |
| square | Boolean | Vero (quadrato), falso (cerchio). |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| borderWidth | Int32 | La larghezza del bordo del quadrato o del cerchio. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)