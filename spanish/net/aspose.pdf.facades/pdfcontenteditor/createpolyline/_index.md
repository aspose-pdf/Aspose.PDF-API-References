---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea anotación de polilínea
type: docs
weight: 240
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## Método PdfContentEditor.CreatePolyLine

Crea anotación de polilínea.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lineInfo | LineInfo | La instancia de la clase LineInfo. |
| page | Int32 | El número de la página original donde se creará la anotación. |
| annotRect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| annotContents | String | El contenido de la anotación. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Ver También

* clase [LineInfo](../../lineinfo/)
* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)