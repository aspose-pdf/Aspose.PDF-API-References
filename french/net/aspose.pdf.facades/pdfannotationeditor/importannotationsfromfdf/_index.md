---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Importe toutes les annotations à partir du fichier FDF
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## Méthode PdfAnnotationEditor.ImportAnnotationsFromFdf

Importe toutes les annotations à partir du fichier FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fdfFile | String | Le fichier FDF d'entrée. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)