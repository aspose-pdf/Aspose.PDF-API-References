---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfAnnotationEditor. Elimina l'annotazione con il nome dell'annotazione specificato
type: docs
weight: 20
url: /it/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## Metodo PdfAnnotationEditor.DeleteAnnotation

Elimina l'annotazione con il nome dell'annotazione specificato.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| annotName | String | Il nome dell'annotazione |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)