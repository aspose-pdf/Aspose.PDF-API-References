---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Dokumentegenskap. Hämtar dokumentåtgärder. Denna egenskap är en instans av DocumentActions-klassen som gör det möjligt att hämta/ange BeforClosing, BeforSaving osv. åtgärder
type: docs
weight: 30
url: /sv/net/aspose.pdf/document/actions/
---
## Document.Actions-egenskap

Hämtar dokumentåtgärder. Denna egenskap är en instans av DocumentActions-klassen som gör det möjligt att hämta/ange BeforClosing, BeforSaving osv. åtgärder.

```csharp
public DocumentActionCollection Actions { get; }
```

## Exempel

Detta exempel visar hur man får efteröppningsåtgärden för dokumentet:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Se Även

* klass [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)