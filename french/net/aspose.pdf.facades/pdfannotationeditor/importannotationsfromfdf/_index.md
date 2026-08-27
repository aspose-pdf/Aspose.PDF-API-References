---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfAnnotationEditor. Importe toutes les annotations du fichier FDF"
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

Importe toutes les annotations depuis le fichier FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fdfFile | String | Le fichier FDF d’entrée. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


