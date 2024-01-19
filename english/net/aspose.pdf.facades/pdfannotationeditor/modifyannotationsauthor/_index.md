---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor method. Modifies the author of annotations on the specified page range
type: docs
weight: 130
url: /net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

Modifies the author of annotations on the specified page range.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| start | Int32 | The start page number. |
| end | Int32 | The end page number. |
| srcAuthor | String | The author that must be modified. |
| desAuthor | String | The new author. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


