---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Elimina la anotación con el nombre de anotación especificado
type: docs
weight: 20
url: /es/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## Método PdfAnnotationEditor.DeleteAnnotation

Elimina la anotación con el nombre de anotación especificado.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotName | String | El nombre de la anotación |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)