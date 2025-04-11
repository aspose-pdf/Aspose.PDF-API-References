---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Modifica el autor de las anotaciones en el rango de páginas especificado
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## Método PdfAnnotationEditor.ModifyAnnotationsAuthor

Modifica el autor de las anotaciones en el rango de páginas especificado.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | Int32 | El número de página de inicio. |
| end | Int32 | El número de página final. |
| srcAuthor | String | El autor que debe ser modificado. |
| desAuthor | String | El nuevo autor. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)