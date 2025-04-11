---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodo. Modifica l'autore delle annotazioni su un intervallo delle pagine specificato.
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## Metodo PdfAnnotationEditor.ModifyAnnotationsAuthor

Modifica l'autore delle annotazioni nell'intervallo di pagine specificato.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | Int32 | Il numero della pagina di inizio. |
| end | Int32 | Il numero della pagina di fine. |
| srcAuthor | String | L'autore che deve essere modificato. |
| desAuthor | String | Il nuovo autore. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)