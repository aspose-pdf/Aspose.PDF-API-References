---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent une action GoTo explicite au démarrage"
type: docs
weight: 430
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent une action 'GoTo' explicite au démarrage.

```csharp
public void RemoveDocumentOpenAction()
```

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


