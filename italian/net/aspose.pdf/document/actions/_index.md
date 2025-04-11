---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del documento. Ottiene le azioni del documento. Questa proprietà è un'istanza della classe DocumentActions che consente di ottenere/impostare azioni BeforClosing, BeforSaving, ecc.
type: docs
weight: 30
url: /it/net/aspose.pdf/document/actions/
---
## Proprietà Document.Actions

Ottiene le azioni del documento. Questa proprietà è un'istanza della classe DocumentActions che consente di ottenere/impostare azioni BeforClosing, BeforSaving, ecc.

```csharp
public DocumentActionCollection Actions { get; }
```

## Esempi

Questo esempio dimostra come ottenere l'azione dopo l'apertura del documento:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Vedi Anche

* classe [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)