---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea anotación de cuadrado-círculo
type: docs
weight: 280
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## Método PdfContentEditor.CreateSquareCircle

Crea anotación de cuadrado-círculo.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectángulo | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | Cadena | El contenido de la anotación. |
| clr | Color | El color del cuadrado o círculo. |
| square | Booleano | Verdadero (cuadrado), falso (círculo). |
| page | Int32 | El número de la página original donde se creará la anotación. |
| borderWidth | Int32 | El ancho del borde del cuadrado o círculo. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)