---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent une action 'GoTo' explicite au démarrage.
type: docs
weight: 430
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## Méthode PdfContentEditor.RemoveDocumentOpenAction

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

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)