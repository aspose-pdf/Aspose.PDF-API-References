---
title: "Page.Contents"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Page-egenskap. Hämtar samling av operatorer i sidans innehållsström. OperatorCollection"
type: docs
weight: 90
url: /sv/net/aspose.pdf/page/contents/
---
## Page.Contents property

Hämtar samling av operatorer i sidans innehållsström. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Exempel

Exemplet visar hur man skannar operatorströmmen för en sida.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Se även

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


