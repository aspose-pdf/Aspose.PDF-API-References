---
title: "OutputIntents.CopyTo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "OutputIntents méthode. Copie les éléments de la collection vers le tableau en commençant à l'index arrayIndex spécifié"
type: docs
weight: 70
url: /fr/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

Copie les éléments de la collection dans le *array*, en commençant à l'*arrayIndex* particulier dans le tableau.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tableau | OutputIntent[] | Le tableau unidimensionnel qui est la destination des intentions de sortie copiées depuis la collection. Le tableau doit être indexé à partir de zéro. |
| arrayIndex | Int32 | L'index à base zéro dans *array* où la copie commence. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *array* est nul. |
| ArgumentOutOfRangeException | *arrayIndex* est inférieur à 0. |
| ArgumentException | Le nombre d'éléments dans la source [`OutputIntents`](../) est supérieur à l'espace disponible depuis *arrayIndex* jusqu'à la fin du *array* de destination. |

### Voir aussi

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


