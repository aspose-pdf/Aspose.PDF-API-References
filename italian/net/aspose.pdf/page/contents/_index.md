---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Proprietà della pagina. Ottiene la collezione di operatori nel flusso di contenuto della pagina. OperatorCollection
type: docs
weight: 90
url: /it/net/aspose.pdf/page/contents/
---
## Proprietà Page.Contents

Ottiene la collezione di operatori nel flusso di contenuto della pagina. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Esempi

L'esempio dimostra come scansionare il flusso di operatori della pagina.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Vedi Anche

* classe [OperatorCollection](../../operatorcollection/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)