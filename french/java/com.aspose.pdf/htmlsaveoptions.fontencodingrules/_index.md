---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette énumération définit les règles qui ajustent la logique d'encodage"
type: docs
weight: 2050
url: /fr/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Cette énumération définit les règles qui ajustent la logique d'encodage

## Champs

| Champ | Description |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode est un mécanisme spécial qui aide à décoder les codes d'entrée en symboles Unicode. Selon la spécification, il doit être utilisé en premier parmi tous les mécanismes pour obtenir des symboles Unicode pour un code d'entrée spécifique. Mais certains documents ont des polices non standard et, pour convertir correctement ces documents, il peut être nécessaire de diminuer la priorité de ToUnicode et d'utiliser d'autres mécanismes pour décoder les codes d'entrée. |
| [Default](#Default) | Laisser la logique d'encodage "tel quel" - conformément à la spécification PDF |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode est un mécanisme spécial qui aide à décoder les codes d'entrée en symboles Unicode. Selon la spécification, il doit être utilisé en premier parmi tous les mécanismes pour obtenir des symboles Unicode pour un code d'entrée spécifique. Mais certains documents ont des polices non standard et, pour convertir correctement ces documents, il peut être nécessaire de diminuer la priorité de ToUnicode et d'utiliser d'autres mécanismes pour décoder les codes d'entrée.

### Default {#Default}
```
public static final byte Default
```

Laisser la logique d'encodage "tel quel" - conformément à la spécification PDF
