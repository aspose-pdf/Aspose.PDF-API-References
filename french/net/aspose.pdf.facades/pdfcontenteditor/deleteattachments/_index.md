---
title: PdfContentEditor.DeleteAttachments
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Supprime toutes les pièces jointes dans le document PDF
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## Méthode PdfContentEditor.DeleteAttachments

Supprime toutes les pièces jointes dans le document PDF.

```csharp
public void DeleteAttachments()
```

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)