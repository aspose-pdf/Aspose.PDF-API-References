---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Importa todas as anotações do arquivo FDF
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## Método PdfAnnotationEditor.ImportAnnotationsFromFdf

Importa todas as anotações do arquivo FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fdfFile | String | O arquivo FDF de entrada. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)