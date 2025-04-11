---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextEditOptions. Options des opérations d'édition de texte
type: docs
weight: 10820
url: /fr/net/aspose.pdf.text/texteditoptions/
---
## Classe TextEditOptions

Options des opérations d'édition de texte.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour la permission de transformation de langue spécifiée. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour le mode de comportement de remplacement de police spécifié. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour le mode de comportement de transformation de langue spécifié. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour le mode de comportement sans caractère spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Obtient ou définit la valeur qui permet l'utilisation de la transformation de langue lors de l'ajout ou de l'édition de texte. true - la transformation de langue sera appliquée si nécessaire (valeur par défaut). false - la transformation de langue NE sera PAS appliquée. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Obtient le mode de traitement du chemin de découpe du texte édité. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Obtient le mode qui définit le comportement pour les scénarios de remplacement de polices. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Obtient le mode qui définit le comportement pour les scénarios de transformation de langue. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Obtient ou définit le mode qui définit le comportement en cas de polices ne contenant pas les caractères demandés. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Obtient ou définit la valeur qui permet de rechercher le soulignement du texte sur la page du document source. (Obsolète) Veuillez utiliser TextSearchOptions.SearchForTextRelatedGraphics à la place. |

### Voir aussi

* classe [TextOptions](../textoptions/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)