---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Définit différents modes pouvant être utilisés lors de la conversion d'un document pdf en texte. Voir la classe {@code TextDevice}."
type: docs
weight: 5070
url: /fr/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Définit différents modes pouvant être utilisés lors de la conversion d'un document pdf en texte. Voir la classe {@code TextDevice}.

## Champs

| Champ | Description |
| --- | --- |
| [Flatten](#Flatten) | Représente le contenu PDF avec des fragments de texte positionnés selon leurs coordonnées. C’est essentiellement similaire au mode "Raw". Mais alors que le mode "Raw" se concentre sur la préservation de la structure des fragments de texte (opérateurs) dans un document, le mode "Flatten" se concentre sur le maintien du texte dans l'ordre de lecture. |
| [MemorySaving](#MemorySaving) | Extraction avec économie de mémoire. C’est presque identique au mode 'Raw' mais fonctionne légèrement plus rapidement et utilise moins de mémoire. |
| [Pure](#Pure) | Représente le contenu PDF avec un peu de routines de formatage. |
| [Raw](#Raw) | Représente le contenu PDF tel quel, c’est‑à‑dire sans formatage. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Représente le contenu PDF avec des fragments de texte positionnés selon leurs coordonnées. C’est essentiellement similaire au mode "Raw". Mais alors que le mode "Raw" se concentre sur la préservation de la structure des fragments de texte (opérateurs) dans un document, le mode "Flatten" se concentre sur le maintien du texte dans l'ordre de lecture.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Extraction avec économie de mémoire. C’est presque identique au mode 'Raw' mais fonctionne légèrement plus rapidement et utilise moins de mémoire.

### Pure {#Pure}
```
public static final int Pure
```

Représente le contenu PDF avec un peu de routines de formatage.

### Raw {#Raw}
```
public static final int Raw
```

Représente le contenu PDF tel quel, c’est‑à‑dire sans formatage.
