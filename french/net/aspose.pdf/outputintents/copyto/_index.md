---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: Méthode OutputIntents. Copie les éléments de la collection dans le tableau en commençant à l'index *arrayIndex* particulier dans le tableau
type: docs
weight: 70
url: /fr/net/aspose.pdf/outputintents/copyto/
---
## Méthode OutputIntents.CopyTo

Copie les éléments de la collection dans le *tableau*, en commençant à l'*arrayIndex* particulier dans le tableau.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tableau | OutputIntent[] | Le tableau unidimensionnel qui est la destination des intentions de sortie copiées de la collection. Le tableau doit avoir un index basé sur zéro. |
| arrayIndex | Int32 | L'index basé sur zéro dans le *tableau* où la copie commence. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Le *tableau* est nul. |
| ArgumentOutOfRangeException | *arrayIndex* est inférieur à 0. |
| ArgumentException | Le nombre d'éléments dans la source [`OutputIntents`](../) est supérieur à l'espace disponible de *arrayIndex* à la fin du *tableau* de destination. |

### Voir aussi

* classe [OutputIntent](../../outputintent/)
* classe [OutputIntents](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)