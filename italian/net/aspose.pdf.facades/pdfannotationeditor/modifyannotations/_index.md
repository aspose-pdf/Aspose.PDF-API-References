---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfAnnotationEditor. Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà delle annotazioni: Modified, Title, Contents, Color, Subject e Open."
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

Modifica le annotazioni del tipo specificato nell'intervallo di pagine specificato. Supporta la modifica delle seguenti proprietà dell'annotazione: Modified, Title, Contents, Color, Subject e Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start | Int32 | Il numero della pagina iniziale. |
| end | Int32 | Il numero della pagina finale. |
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

### Vedi anche

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


