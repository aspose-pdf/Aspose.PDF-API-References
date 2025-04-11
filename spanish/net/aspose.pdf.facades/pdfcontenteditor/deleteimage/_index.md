---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Elimina las imágenes especificadas en la página especificada
type: docs
weight: 320
url: /es/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Elimina las imágenes especificadas en la página especificada.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | El número de página en la que se deben eliminar las imágenes. |
| index | Int32[] | Un array que representa los índices de las imágenes. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Elimina todas las imágenes del documento PDF.

```csharp
public void DeleteImage()
```

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)