---
title: RemoveDocumentOpenAction
second_title: Référence de l'API Aspose.PDF pour .NET
description: Supprime laction douverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent laction explicite GoTo au démarrage.
type: docs
weight: 430
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent l'action explicite 'GoTo' au démarrage.

```csharp
public void RemoveDocumentOpenAction()
```

### Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Voir également

* class [PdfContentEditor](../../pdfcontenteditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->