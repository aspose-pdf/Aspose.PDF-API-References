---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Elimina todas las anotaciones en el documento
type: docs
weight: 30
url: /es/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Elimina todas las anotaciones en el documento.

```csharp
public void DeleteAnnotations()
```

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Elimina todas las anotaciones del tipo especificado en el documento.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotType | String | El tipo de anotación que será eliminado. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)