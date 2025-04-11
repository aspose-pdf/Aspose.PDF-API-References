---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient la collection d'opérateurs dans le flux de contenu de la page. OperatorCollection
type: docs
weight: 90
url: /fr/net/aspose.pdf/page/contents/
---
## Propriété Page.Contents

Obtient la collection d'opérateurs dans le flux de contenu de la page. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Exemples

L'exemple démontre comment scanner le flux d'opérateurs de la page.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Voir aussi

* classe [OperatorCollection](../../operatorcollection/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)