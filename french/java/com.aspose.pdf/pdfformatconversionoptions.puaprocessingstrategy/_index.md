---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Certains documents PDF contiennent des symboles Unicode spéciaux, appartenant à la zone d’utilisation privée (PUA), voir la description sur https://en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles."
type: docs
weight: 3750
url: /fr/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Certains documents PDF contiennent des symboles Unicode spéciaux, appartenant à la zone d'utilisation privée (PUA) ; voir la description sur https://en.wikipedia.org/wiki/Private_Use_Areas. Ces symboles provoquent des erreurs de conformité PDF/A telles que "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Cette énumération déclare des stratégies pouvant être utilisées pour gérer les symboles PUA.

## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Désactiver le traitement des symboles PUA. Cette stratégie est utilisée par défaut pour les documents PDF/A avec conformité Niveau B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Cette stratégie fonctionne plus lentement que 'SurroundPuaTextWithEmptyActualText' mais elle peut supprimer les erreurs conformes au PUA pour les documents qui ne peuvent pas être correctement traités par SurroundPuaTextWithEmptyActualText. Les symboles PUA sont remplacés par le symbole 'space' ou par un Unicode spécial (certains symboles PUA ont des analogues Unicode). La substitution est appliquée non pas au texte du document mais aux données internes de la police ToUnicode, de sorte qu'elle n'affecte pas la visibilité du symbole mais affecte sa présentation lors des opérations de copie/coller dans le presse‑papier du système. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Insère un bloc de contenu marqué avec une entrée ActualText contenant du texte vide. Cette stratégie donne de bons résultats pour les documents sans blocs de contenu marqués. Utilisée par défaut pour les documents PDF/A avec conformité Niveau A. |

### None {#None}
```
public static final int None
```

Désactiver le traitement des symboles PUA. Cette stratégie est utilisée par défaut pour les documents PDF/A avec conformité Niveau B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Cette stratégie fonctionne plus lentement que 'SurroundPuaTextWithEmptyActualText' mais elle peut supprimer les erreurs conformes au PUA pour les documents qui ne peuvent pas être correctement traités par SurroundPuaTextWithEmptyActualText. Les symboles PUA sont remplacés par le symbole 'space' ou par un Unicode spécial (certains symboles PUA ont des analogues Unicode). La substitution est appliquée non pas au texte du document mais aux données internes de la police ToUnicode, de sorte qu'elle n'affecte pas la visibilité du symbole mais affecte sa présentation lors des opérations de copie/coller dans le presse‑papier du système.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Insère un bloc de contenu marqué avec une entrée ActualText contenant du texte vide. Cette stratégie donne de bons résultats pour les documents sans blocs de contenu marqués. Utilisée par défaut pour les documents PDF/A avec conformité Niveau A.
