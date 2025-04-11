---
title: PdfContentEditor.CreatePolygon
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea anotación de polígono
type: docs
weight: 230
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## Método PdfContentEditor.CreatePolygon

Crea anotación de polígono.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Ver También

* clase [LineInfo](../../lineinfo/)
* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)