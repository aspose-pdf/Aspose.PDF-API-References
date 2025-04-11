---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do documento. Obtém ações do documento. Esta propriedade é uma instância da classe DocumentActions que permite obter/configurar ações de BeforClosing, BeforSaving, etc.
type: docs
weight: 30
url: /pt/net/aspose.pdf/document/actions/
---
## Propriedade Document.Actions

Obtém ações do documento. Esta propriedade é uma instância da classe DocumentActions que permite obter/configurar ações de BeforClosing, BeforSaving, etc.

```csharp
public DocumentActionCollection Actions { get; }
```

## Exemplos

Este exemplo demonstra como obter a ação após abrir o documento:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Veja Também

* classe [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)