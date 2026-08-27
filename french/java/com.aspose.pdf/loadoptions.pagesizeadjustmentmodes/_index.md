---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "ATTENTION! La fonctionnalité a été implémentée mais n’a pas encore été mise dans l’API publique car un problème bloquant dans la couche OSHARED a été révélé pour le document d’exemple. Représente le mode d’utilisation de la taille de page."
type: docs
weight: 2810
url: /fr/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

ATTENTION ! La fonctionnalité est implémentée mais n’a pas encore été exposée dans l’API publique en raison d’un problème bloquant dans la couche OSHARED détecté pour le document d’exemple. Représente le mode d’utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d’ajuster la taille de page requise. Mais parfois le contenu spécifie des positions ou une taille horizontales qui ne permettent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant).

## Champs

| Champ | Description |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Ce mode définit ce comportement : après l’obtention du résultat de conversion, et la détection du fait que certains contenus ont été tronqués, la largeur de la portview est agrandie pour s’adapter au contenu et la conversion est répétée. Ce mode permet d’obtenir moins de pages dans le résultat dans ce cas, mais nécessite un rendu répété (et donc plus de temps de traitement). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | Dans ce mode, les pages de résultat auront la taille de page requise définie dans LoadOptions, que le contenu après conversion dépasse ou non les limites de la page. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Ce mode définit ce comportement : après l’obtention du résultat de conversion, et la détection du fait que certains contenus ont été tronqués, la largeur de la portview est agrandie pour s’adapter au contenu et la conversion est répétée. Ce mode permet d’obtenir moins de pages dans le résultat dans ce cas, mais nécessite un rendu répété (et donc plus de temps de traitement).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

Dans ce mode, les pages de résultat auront la taille de page requise définie dans LoadOptions, que le contenu après conversion dépasse ou non les limites de la page.
