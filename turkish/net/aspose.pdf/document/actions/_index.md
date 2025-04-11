---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Belge özelliği. Belge eylemlerini alır. Bu özellik, BeforClosing, BeforSaving vb. eylemleri almak/ayarlamak için olan DocumentActions sınıfının bir örneğidir.
type: docs
weight: 30
url: /tr/net/aspose.pdf/document/actions/
---
## Document.Actions özelliği

Belge eylemlerini alır. Bu özellik, BeforClosing, BeforSaving vb. eylemleri almak/ayarlamak için olan DocumentActions sınıfının bir örneğidir.

```csharp
public DocumentActionCollection Actions { get; }
```

## Örnekler

Bu örnek, belgenin açıldıktan sonraki eylemini nasıl elde edeceğinizi gösterir:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Ayrıca Bakınız

* sınıf [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* sınıf [Document](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)