---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette énumération décrit les mesures d'anticrénelage possibles pendant la conversion"
type: docs
weight: 2000
url: /fr/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Cette énumération décrit les mesures d'anticrénelage possibles pendant la conversion

## Champs

| Champ | Description |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Aucun traitement d'anticrénelage spécial n'est utilisé. C'est une option optimale pour la grande majorité des documents et elle ne nécessite pas de temps supplémentaire lors de la conversion. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | Dans ce cas, le convertisseur tente de détecter les zones contenant des éléments graphiques d'arrière-plan adjacents et de corriger le HTML résultant de manière appropriée. Cette option permet d'améliorer le résultat de l'exportation pour les documents contenant des arrière-plans composés de plusieurs éléments graphiques adjacents (pour ce type de documents, les rendus PDF, par ex. Acrobat Reader, essaient généralement d'adoucir les frontières des éléments lors du rendu). Avec cette option, le convertisseur imite ce comportement des rendus PDF. Cette option permet d'améliorer la mise en page du résultat d'exportation pour certains documents spécifiques (qui utilisent de tels arrière-plans composés), mais elle nécessite un temps supplémentaire de traitement (généralement environ 10‑15 % de temps additionnel). Ainsi, l'utilisation de ce mode dans le cas général n'est pas recommandée. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Aucun traitement d'anticrénelage spécial n'est utilisé. C'est une option optimale pour la grande majorité des documents et elle ne nécessite pas de temps supplémentaire lors de la conversion.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

Dans ce cas, le convertisseur tente de détecter les zones contenant des éléments graphiques d'arrière-plan adjacents et de corriger le HTML résultant de manière appropriée. Cette option permet d'améliorer le résultat de l'exportation pour les documents contenant des arrière-plans composés de plusieurs éléments graphiques adjacents (pour ce type de documents, les rendus PDF, par ex. Acrobat Reader, essaient généralement d'adoucir les frontières des éléments lors du rendu). Avec cette option, le convertisseur imite ce comportement des rendus PDF. Cette option permet d'améliorer la mise en page du résultat d'exportation pour certains documents spécifiques (qui utilisent de tels arrière-plans composés), mais elle nécessite un temps supplémentaire de traitement (généralement environ 10‑15 % de temps additionnel). Ainsi, l'utilisation de ce mode dans le cas général n'est pas recommandée.
