---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Propriété du document. Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/de définir les actions BeforClosing, BeforSaving, etc.
type: docs
weight: 30
url: /fr/net/aspose.pdf/document/actions/
---
## Propriété Document.Actions

Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/de définir les actions BeforClosing, BeforSaving, etc.

```csharp
public DocumentActionCollection Actions { get; }
```

## Exemples

Cet exemple démontre comment obtenir l'action après l'ouverture du document :

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Voir aussi

* classe [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)