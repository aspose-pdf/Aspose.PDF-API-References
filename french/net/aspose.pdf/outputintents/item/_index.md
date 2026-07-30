---
title: "OutputIntents.Item"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "OutputIntents propriété. Obtient l'intention de sortie à l'index spécifié."
type: docs
weight: 30
url: /fr/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Obtient l'output intent à l'*index* spécifié.

```csharp
public OutputIntent this[int index] { get; }
```

| Paramètre | Description |
| --- | --- |
| index | L'index à base zéro de l'intention de sortie à obtenir. |

### Valeur de retour

L'intention de sortie à l'*index* spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* est inférieur à 0 ou *index* est égal ou supérieur à [`Count`](../count/). |
| InvalidOperationException | Le document contenant la collection n’a pas de catalogue pour accéder aux OutputIntents. |

### Voir aussi

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


