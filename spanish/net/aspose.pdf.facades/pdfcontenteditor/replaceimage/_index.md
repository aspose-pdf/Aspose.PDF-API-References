---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Reemplaza la imagen especificada en la página especificada del documento PDF con otra imagen
type: docs
weight: 440
url: /es/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## Método PdfContentEditor.ReplaceImage

Reemplaza la imagen especificada en la página especificada del documento PDF con otra imagen.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de página en la que se reemplaza la imagen. |
| index | Int32 | El índice del objeto de imagen que debe ser reemplazado. |
| imageFile | String | El archivo de imagen que se utilizará para el reemplazo. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)