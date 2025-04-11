---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor method. Modifies the annotations of the specifed type on the specified page range. It supports to modify next annotation properties Modified Title Contents Color Subject and Open
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## Metodo PdfAnnotationEditor.ModifyAnnotations

Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà delle annotazioni: Modificato, Titolo, Contenuti, Colore, Oggetto e Aperto.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | Int32 | Il numero della pagina di inizio. |
| end | Int32 | Il numero della pagina di fine. |
| annotation | Annotation | L'oggetto annotazione contiene nuove proprietà. |

## Esempi

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

### Vedi Anche

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)