---
title: DrawCurve
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea anotación de curva.
type: docs
weight: 360
url: /es/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

Crea anotación de curva.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| lineInfo | LineInfo | La instancia de la clase LineInfo. |
| page | Int32 | El número de página original donde se creará la anotación. |
| annotRect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| annotContents | String | El contenido de la anotación. |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Ver también

* class [LineInfo](../../lineinfo)
* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
