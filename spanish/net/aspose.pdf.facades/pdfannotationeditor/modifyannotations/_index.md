---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Soporta modificar las siguientes propiedades de la anotación: Modificado, Título, Contenidos, Color, Asunto y Abrir.
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## Método PdfAnnotationEditor.ModifyAnnotations

Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Soporta modificar las siguientes propiedades de la anotación: Modificado, Título, Contenidos, Color, Asunto y Abrir.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | Int32 | El número de página de inicio. |
| end | Int32 | El número de página final. |
| annotation | Annotation | El objeto de anotación contiene nuevas propiedades. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### Ver También

* clase [Annotation](../../../aspose.pdf.annotations/annotation/)
* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)