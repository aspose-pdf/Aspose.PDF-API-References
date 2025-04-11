---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriété OutputIntents. Obtient l'intention de sortie à l'index spécifié
type: docs
weight: 30
url: /fr/net/aspose.pdf/outputintents/item/
---
## Indexeur OutputIntents

Obtient l'intention de sortie à l'*index* spécifié.

```csharp
public OutputIntent this[int index] { get; }
```

| Paramètre | Description |
| --- | --- |
| index | L'index basé sur zéro de l'intention de sortie à obtenir. |

### Valeur de retour

L'intention de sortie à l'*index* spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* est inférieur à 0 ou *index* est égal ou supérieur à [`Count`](../count/). |
| InvalidOperationException | Le document qui contient la collection n'a pas de catalogue pour accéder aux OutputIntents. |

### Voir aussi

* classe [OutputIntent](../../outputintent/)
* classe [OutputIntents](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)