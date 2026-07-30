---
title: "OperatorCollection.Item"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété OperatorCollection. Obtient l'opérateur par son indice."
type: docs
weight: 40
url: /fr/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Obtient l’opérateur par son indice.

```csharp
public override Operator this[int index] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| index | Indice de l'opérateur. La numérotation commence à 1. |

### Valeur de retour

Opérateur à l'indice demandé

## Exemples

L'exemple montre comment obtenir l'opérateur du contenu de la page par indice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


