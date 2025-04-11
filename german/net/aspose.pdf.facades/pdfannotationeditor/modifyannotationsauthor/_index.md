---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Ändert den Autor von Annotationen im angegebenen Seitenbereich
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor-Methode

Ändert den Autor von Annotationen im angegebenen Seitenbereich.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | Int32 | Die Startseitenzahl. |
| end | Int32 | Die Endseitenzahl. |
| srcAuthor | String | Der Autor, der geändert werden muss. |
| desAuthor | String | Der neue Autor. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)