---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Sidans egenskap. Hämtar samlingen av operatorer i sidans innehållsström. OperatorCollection
type: docs
weight: 90
url: /sv/net/aspose.pdf/page/contents/
---
## Page.Contents egenskap

Hämtar samlingen av operatorer i sidans innehållsström. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Exempel

Exemplet visar hur man skannar operatorernas ström på sidan.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Se Även

* klass [OperatorCollection](../../operatorcollection/)
* klass [Page](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)