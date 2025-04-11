---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Propriedade da página. Obtém a coleção de operadores no fluxo de conteúdo da página. OperatorCollection
type: docs
weight: 90
url: /pt/net/aspose.pdf/page/contents/
---
## Propriedade Page.Contents

Obtém a coleção de operadores no fluxo de conteúdo da página. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Exemplos

O exemplo demonstra como escanear o fluxo de operadores da página.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Veja Também

* classe [OperatorCollection](../../operatorcollection/)
* classe [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)