---
title: "Document.Actions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-egenskap. Hämtar dokumentåtgärder. Denna egenskap är en instans av DocumentActions-klassen som möjliggör att få/ange BeforClosing, BeforSaving etc. åtgärder"
type: docs
weight: 30
url: /sv/net/aspose.pdf/document/actions/
---
## Document.Actions property

Hämtar document‑åtgärder. Denna egenskap är en instans av DocumentActions‑klassen som tillåter att få/ställa in BeforClosing, BeforSaving osv. åtgärder.

```csharp
public DocumentActionCollection Actions { get; }
```

## Exempel

Detta exempel visar hur man hämtar efteröppningsåtgärden för dokumentet:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Se även

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


