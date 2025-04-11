---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfAnnotationEditor. Importa tutte le annotazioni dal file FDF
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## Metodo PdfAnnotationEditor.ImportAnnotationsFromFdf

Importa tutte le annotazioni dal file FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fdfFile | String | Il file FDF di input. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)