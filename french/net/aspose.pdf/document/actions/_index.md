---
title: "Document.Actions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Document. Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d’obtenir/définir les actions BeforClosing BeforSaving etc."
type: docs
weight: 30
url: /fr/net/aspose.pdf/document/actions/
---
## Document.Actions property

Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/définir les actions BeforClosing, BeforSaving, etc.

```csharp
public DocumentActionCollection Actions { get; }
```

## Exemples

Cet exemple montre comment obtenir l’action après ouverture du document :

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Voir aussi

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


