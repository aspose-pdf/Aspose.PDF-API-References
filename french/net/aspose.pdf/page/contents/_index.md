---
title: "Page.Contents"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Page. Obtient la collection des opérateurs dans le flux de contenu de la page. OperatorCollection"
type: docs
weight: 90
url: /fr/net/aspose.pdf/page/contents/
---
## Page.Contents property

Obtient la collection des opérateurs dans le flux de contenu de la page. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Exemples

L'exemple montre comment analyser le flux des opérateurs de la page.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Voir aussi

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


