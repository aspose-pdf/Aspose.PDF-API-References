---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Importa todas las anotaciones desde un archivo FDF
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## Método PdfAnnotationEditor.ImportAnnotationsFromFdf

Importa todas las anotaciones desde un archivo FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fdfFile | String | El archivo FDF de entrada. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)