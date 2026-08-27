---
title: "Page.Contents"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Page property. Ottiene la raccolta di operatori nel flusso di contenuto della pagina. OperatorCollection"
type: docs
weight: 90
url: /it/net/aspose.pdf/page/contents/
---
## Page.Contents property

Ottiene la raccolta di operatori nel flusso di contenuto della pagina. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Esempi

L'esempio dimostra come eseguire la scansione del flusso di operatori della pagina.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Vedi anche

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


