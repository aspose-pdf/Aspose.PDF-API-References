---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea una anotación de texto libre en el documento PDF
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## Método PdfContentEditor.CreateFreeText

Crea una anotación de texto libre en el documento PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| page | Int32 | El número de la página original donde se creará la anotación de texto. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)