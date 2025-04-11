---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metod. Ändrar författaren av anteckningar på det angivna sidintervallet
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor metod

Ändrar författaren av anteckningar på det angivna sidintervallet.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Det första sidnumret. |
| end | Int32 | Det sista sidnumret. |
| srcAuthor | String | Den författare som måste ändras. |
| desAuthor | String | Den nya författaren. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)