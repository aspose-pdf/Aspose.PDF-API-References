---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Enum LoadOptionsMarginsAreaUsageModes d'Aspose.Pdf. Représente le mode d'utilisation de la zone de marges lors de la conversion comme HTML EPUB etc définit le traitement des instructions du format importé liées à l'utilisation des marges
type: docs
weight: 6130
url: /fr/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## Énumération LoadOptions.MarginsAreaUsageModes

Représente le mode d'utilisation de la zone de marges lors de la conversion (comme HTML, EPUB, etc.), définit le traitement des instructions du format importé liées à l'utilisation des marges.

```csharp
public enum MarginsAreaUsageModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | Dans ce mode, le convertisseur obéit au format du document importé (par exemple, CSS de l'HTML importé) dans l'utilisation de la zone de marges. Donc, si le format du document importé nécessite l'utilisation de la zone de marges pour le rendu, le convertisseur le permettra. |
| NeverPutContentOnMarginArea | `1` | Ce mode interdit strictement l'utilisation de la zone de marges, donc, le convertisseur n'utilisera jamais la zone de marges pour le rendu, même si le CSS ou le format du document source le permet ou l'exige. |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)