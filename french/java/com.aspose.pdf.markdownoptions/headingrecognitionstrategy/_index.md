---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les types de stratégies de reconnaissance d'en-tête."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Représente les types de stratégies de reconnaissance d'en-tête.

## Champs

| Champ | Description |
| --- | --- |
| [Auto](#Auto) | Fournit une sélection automatique de la stratégie de reconnaissance d'en-tête. C'est l'option par défaut. Si le document contient des signets, la stratégie {@link HeadingRecognitionStrategy#Outlines} sera sélectionnée, sinon {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Représente la stratégie de reconnaissance d'en-tête au moyen de règles heuristiques et de statistiques de taille de police. |
| [None](#None) | Ne pas reconnaître les en-têtes. Cette option peut être utile dans des documents au format complexe. |
| [Outlines](#Outlines) | Représente la stratégie de reconnaissance d'en-tête au moyen de contours. |

### Auto {#Auto}
```
public static final int Auto
```

Fournit une sélection automatique de la stratégie de reconnaissance d'en-tête. C'est l'option par défaut. Si le document contient des signets, la stratégie {@link HeadingRecognitionStrategy#Outlines} sera sélectionnée, sinon {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Représente la stratégie de reconnaissance d'en-tête au moyen de règles heuristiques et de statistiques de taille de police.

### None {#None}
```
public static final int None
```

Ne pas reconnaître les en-têtes. Cette option peut être utile dans des documents au format complexe.

### Outlines {#Outlines}
```
public static final int Outlines
```

Représente la stratégie de reconnaissance d'en-tête au moyen de contours.
