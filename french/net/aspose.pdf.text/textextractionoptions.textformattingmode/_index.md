---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Enum TextExtractionOptions.TextFormattingMode d'Aspose.Pdf.Text. Définit différents modes qui peuvent être utilisés lors de la conversion d'un document pdf en texte. Voir la classe TextDevice
type: docs
weight: 10900
url: /fr/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## Énumération TextExtractionOptions.TextFormattingMode

Définit différents modes qui peuvent être utilisés lors de la conversion d'un document pdf en texte. Voir la classe !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Pur | `0` | Représente le contenu pdf avec un peu de routines de formatage. |
| Brut | `1` | Représente le contenu pdf tel quel, c'est-à-dire sans formatage. |
| Aplatir | `2` | Représente le contenu pdf en positionnant les fragments de texte par leurs coordonnées. C'est essentiellement similaire au mode "Brut". Mais alors que "Brut" se concentre sur la préservation de la structure des fragments de texte (opérateurs) dans un document, "Aplatir" se concentre sur le maintien du texte dans l'ordre dans lequel il est lu. |
| ÉconomieDeMémoire | `3` | Extraction avec économie de mémoire. C'est presque identique au mode 'Brut' mais fonctionne légèrement plus vite et utilise moins de mémoire. |

### Voir aussi

* classe [TextExtractionOptions](../textextractionoptions/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)