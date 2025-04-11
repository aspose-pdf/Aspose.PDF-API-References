---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Dokumenteneigenschaft. Ruft Dokumentaktionen ab. Diese Eigenschaft ist eine Instanz der DocumentActions-Klasse, die es ermöglicht, BeforClosing, BeforSaving usw. Aktionen zu erhalten/zu setzen.
type: docs
weight: 30
url: /de/net/aspose.pdf/document/actions/
---
## Document.Actions-Eigenschaft

Ruft Dokumentaktionen ab. Diese Eigenschaft ist eine Instanz der DocumentActions-Klasse, die es ermöglicht, BeforClosing, BeforSaving usw. Aktionen zu erhalten/zu setzen.

```csharp
public DocumentActionCollection Actions { get; }
```

## Beispiele

Dieses Beispiel zeigt, wie man die Nach-Öffnen-Aktion des Dokuments erhält:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Siehe auch

* Klasse [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)