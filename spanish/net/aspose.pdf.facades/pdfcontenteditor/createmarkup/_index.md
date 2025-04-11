---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea una anotación de marcado en un documento PDF
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## Método PdfContentEditor.CreateMarkup

Crea una anotación de marcado en un documento PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| type | Int32 | El tipo de anotación de marcado. Puede ser 0 (Resaltar), 1 (Subrayar), 2 (Tachar), 3 (Ondulado). |
| page | Int32 | El número de la página original donde se creará la anotación. |
| clr | Color | El color del marcado. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)