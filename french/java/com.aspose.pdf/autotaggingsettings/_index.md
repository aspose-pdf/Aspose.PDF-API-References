---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Fournit les paramètres pour la fonctionnalité de balisage automatique dans les documents PDF. La classe {@link AutoTaggingSettings} permet de configurer les options de balisage automatique du contenu PDF. Elle."
type: docs
weight: 230
url: /fr/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Fournit les paramètres pour la fonctionnalité de balisage automatique dans les documents PDF. La classe {@link AutoTaggingSettings} permet de configurer les options de balisage automatique du contenu PDF. Elle comprend des propriétés pour activer ou désactiver le balisage automatique, spécifier une stratégie de reconnaissance des titres, et définir les niveaux de titres en fonction des tailles de police.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefault](#getDefault--) | Obtient les paramètres par défaut pour la fonctionnalité de balisage automatique dans les documents PDF. Les paramètres par défaut activent le balisage automatique et utilisent la stratégie automatique pour la reconnaissance des titres. Ces paramètres peuvent être utilisés comme configuration de base pour la conversion de format PDF ou d'autres opérations nécessitant le balisage automatique du contenu PDF. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Obtient ou définit une valeur indiquant si la fonctionnalité de balisage automatique est activée. Lorsqu'elle est activée, la fonctionnalité de balisage automatique génère automatiquement du contenu balisé pour le document PDF, ce qui peut améliorer l'accessibilité et la structure. |
| [getHeadingLevels](#getHeadingLevels--) | Obtient ou définit les niveaux de titres utilisés pour déterminer la structure des titres dans un document PDF. La propriété {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permet de configurer le mappage des tailles de police aux niveaux de titres. Elle est utilisée pendant le processus de balisage automatique pour identifier et attribuer les niveaux de titres appropriés en fonction de la taille de police des éléments de texte du document. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Obtient ou définit la stratégie utilisée pour reconnaître les titres dans le document lors du balisage automatique. La propriété {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) détermine comment les titres sont identifiés dans le document. Les stratégies disponibles incluent la reconnaissance des titres basée sur les contours, l'analyse heuristique ou la détection automatique. Définir cette propriété sur {@link HeadingRecognitionStrategy#None} désactive la reconnaissance des titres. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Obtient ou définit une valeur indiquant si la fonctionnalité de balisage automatique est activée. Lorsqu'elle est activée, la fonctionnalité de balisage automatique génère automatiquement du contenu balisé pour le document PDF, ce qui peut améliorer l'accessibilité et la structure. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Obtient ou définit les niveaux de titres utilisés pour déterminer la structure des titres dans un document PDF. La propriété {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permet de configurer le mappage des tailles de police aux niveaux de titres. Elle est utilisée pendant le processus de balisage automatique pour identifier et attribuer les niveaux de titres appropriés en fonction de la taille de police des éléments de texte du document. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Obtient ou définit la stratégie utilisée pour reconnaître les titres dans le document lors du balisage automatique. La propriété {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) détermine comment les titres sont identifiés dans le document. Les stratégies disponibles incluent la reconnaissance des titres basée sur les contours, l'analyse heuristique ou la détection automatique. Définir cette propriété sur {@link HeadingRecognitionStrategy#None} désactive la reconnaissance des titres. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Obtient les paramètres par défaut pour la fonctionnalité de balisage automatique dans les documents PDF. Les paramètres par défaut activent le balisage automatique et utilisent la stratégie automatique pour la reconnaissance des titres. Ces paramètres peuvent être utilisés comme configuration de base pour la conversion de format PDF ou d'autres opérations nécessitant le balisage automatique du contenu PDF.

**Returns:**
Instance AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Obtient ou définit une valeur indiquant si la fonctionnalité de balisage automatique est activée. Lorsqu'elle est activée, la fonctionnalité de balisage automatique génère automatiquement du contenu balisé pour le document PDF, ce qui peut améliorer l'accessibilité et la structure.

**Returns:**
valeur booléenne

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Obtient ou définit les niveaux de titres utilisés pour déterminer la structure des titres dans un document PDF. La propriété {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permet de configurer le mappage des tailles de police aux niveaux de titres. Elle est utilisée pendant le processus de balisage automatique pour identifier et attribuer les niveaux de titres appropriés en fonction de la taille de police des éléments de texte du document.

**Returns:**
Instance de HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Obtient ou définit la stratégie utilisée pour reconnaître les titres dans le document lors du balisage automatique. La propriété {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) détermine comment les titres sont identifiés dans le document. Les stratégies disponibles incluent la reconnaissance des titres basée sur les contours, l'analyse heuristique ou la détection automatique. Définir cette propriété sur {@link HeadingRecognitionStrategy#None} désactive la reconnaissance des titres.

**Returns:**
Élément HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Obtient ou définit une valeur indiquant si la fonctionnalité de balisage automatique est activée. Lorsqu'elle est activée, la fonctionnalité de balisage automatique génère automatiquement du contenu balisé pour le document PDF, ce qui peut améliorer l'accessibilité et la structure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Obtient ou définit les niveaux de titres utilisés pour déterminer la structure des titres dans un document PDF. La propriété {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permet de configurer le mappage des tailles de police aux niveaux de titres. Elle est utilisée pendant le processus de balisage automatique pour identifier et attribuer les niveaux de titres appropriés en fonction de la taille de police des éléments de texte du document.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Obtient ou définit la stratégie utilisée pour reconnaître les titres dans le document lors du balisage automatique. La propriété {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) détermine comment les titres sont identifiés dans le document. Les stratégies disponibles incluent la reconnaissance des titres basée sur les contours, l'analyse heuristique ou la détection automatique. Définir cette propriété sur {@link HeadingRecognitionStrategy#None} désactive la reconnaissance des titres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément HeadingRecognitionStrategy |
