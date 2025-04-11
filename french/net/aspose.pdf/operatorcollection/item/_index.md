---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriété OperatorCollection. Obtient l'opérateur par son index
type: docs
weight: 40
url: /fr/net/aspose.pdf/operatorcollection/item/
---
## Indexeur OperatorCollection

Obtient l'opérateur par son index.

```csharp
public override Operator this[int index] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| index | Index de l'opérateur. La numérotation commence à 1. |

### Valeur de retour

Opérateur de l'index demandé

## Exemples

L'exemple démontre comment obtenir l'opérateur du contenu de la page par index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Voir aussi

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)