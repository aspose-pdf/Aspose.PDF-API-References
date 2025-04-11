---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Modifica o autor das anotações no intervalo de páginas especificado
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## Método PdfAnnotationEditor.ModifyAnnotationsAuthor

Modifica o autor das anotações no intervalo de páginas especificado.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| start | Int32 | O número da página inicial. |
| end | Int32 | O número da página final. |
| srcAuthor | String | O autor que deve ser modificado. |
| desAuthor | String | O novo autor. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)