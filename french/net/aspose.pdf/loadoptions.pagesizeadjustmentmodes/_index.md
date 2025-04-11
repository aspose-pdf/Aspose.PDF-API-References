---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Enum LoadOptionsPageSizeAdjustmentModes d'Aspose.Pdf. ATTENTION La fonctionnalité est implémentée mais n'a pas encore été mise dans l'API publique en raison d'un problème bloquant dans la couche OSHARED révélé pour le document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats comme HTML, EPUB, etc. ont généralement un design flottant, ce qui permet d'adapter la taille de page requise. Mais parfois, le contenu a des positions ou des tailles horizontales spécifiques qui ne permettent pas d'insérer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait dans ce cas, c'est-à-dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant.
type: docs
weight: 6140
url: /fr/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## Énumération LoadOptions.PageSizeAdjustmentModes

ATTENTION ! La fonctionnalité est implémentée mais n'a pas encore été mise dans l'API publique en raison d'un problème bloquant dans la couche OSHARED révélé pour le document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.), ont généralement un design flottant, donc, cela permet d'adapter la taille de page requise. Mais parfois, le contenu a des positions ou des tailles horizontales spécifiques qui ne permettent pas d'insérer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait dans ce cas (c'est-à-dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant).

```csharp
public enum PageSizeAdjustmentModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | Dans ce mode, les pages résultantes auront la taille de page requise définie dans LoadOptions, peu importe si le contenu après conversion dépasse les limites de la page ou non. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Ce mode définit un tel comportement : après l'obtention du résultat de la conversion et la détection du fait que certains contenus ont été tronqués, la largeur du port est augmentée pour s'adapter au contenu et la conversion est répétée. Ce mode permet d'obtenir moins de pages dans le résultat dans ce cas, mais nécessite un rendu répété (et donc plus de temps de traitement). |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)