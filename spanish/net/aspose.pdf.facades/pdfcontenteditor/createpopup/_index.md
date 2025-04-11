---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea una anotación emergente en el documento PDF
type: docs
weight: 250
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## Método PdfContentEditor.CreatePopup

Crea una anotación emergente en el documento PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo de la anotación que define la ubicación de la anotación en la página. |
| contents | String | El contenido de la anotación. |
| open | Boolean | Un indicador que especifica si la anotación emergente debe mostrarse inicialmente abierta. |
| page | Int32 | El número de la página original donde se creará la anotación. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)