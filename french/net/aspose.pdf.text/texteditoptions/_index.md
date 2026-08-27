---
title: "Classe TextEditOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextEditOptions. Décrit les options des opérations de modification de texte"
type: docs
weight: 11000
url: /fr/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

Décrit les options des opérations de modification de texte.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour l'autorisation de transformation linguistique spécifiée. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour le mode de comportement de remplacement de police spécifié. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour le mode de comportement de transformation linguistique spécifié. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Initialise une nouvelle instance de l'objet `TextEditOptions` pour le mode de comportement sans caractère spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Obtient ou définit la valeur qui autorise l'utilisation de la transformation linguistique lors de l'ajout ou de la modification de texte. true - la transformation linguistique sera appliquée si nécessaire (valeur par défaut). false - la transformation linguistique NE sera PAS appliquée. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Obtient le mode de traitement du chemin de découpe du texte modifié. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Obtient le mode qui définit le comportement pour les scénarios de remplacement de polices. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Obtient le mode qui définit le comportement pour les scénarios de transformation linguistique. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Obtient ou définit le mode qui définit le comportement dans le cas où les polices ne contiennent pas les caractères demandés. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Obtient ou définit la police utilisée pour le remplacement si la police de l'utilisateur ne contient pas le caractère requis. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Obtient ou définit la valeur qui autorise la recherche de soulignement de texte sur la page du document source. (Obsolète) Veuillez utiliser TextSearchOptions.SearchForTextRelatedGraphics à la place. |

### Voir aussi

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


