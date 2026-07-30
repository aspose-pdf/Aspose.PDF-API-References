---
title: "Énumération TextExtractionOptions.TextFormattingMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. Définit différents modes pouvant être utilisés lors de la conversion d'un document pdf en texte. Voir la classe TextDevice"
type: docs
weight: 11080
url: /fr/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

Définit différents modes pouvant être utilisés lors de la conversion d'un document pdf en texte. Voir la classe !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Pure | `0` | Représente le contenu pdf avec un peu de routines de formatage. |
| Raw | `1` | Représente le contenu pdf tel quel, c’est‑à‑dire sans formatage. |
| Flatten | `2` | Représente le contenu pdf avec le positionnement des fragments de texte par leurs coordonnées. C’est essentiellement similaire au mode "Raw". Mais alors que le mode "Raw" se concentre sur la préservation de la structure des fragments de texte (opérateurs) dans un document, le mode "Flatten" se concentre sur le maintien du texte dans l'ordre de lecture. |
| MemorySaving | `3` | Extraction avec économie de mémoire. C’est presque identique au mode 'Raw' mais fonctionne légèrement plus rapidement et utilise moins de mémoire. |

### Voir aussi

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


