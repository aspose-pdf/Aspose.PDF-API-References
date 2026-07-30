---
title: "Énum XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énum Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs de formatage"
type: docs
weight: 11730
url: /fr/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs de formatage

```csharp
public enum ParsingErrorsHandlingTypes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| TryIgnore | `0` | Dans ce cas, le convertisseur sera instruit d'essayer de poursuivre la conversion et d'ignorer les erreurs de formatage détectées. Dans ce cas, le succès n'est pas garanti, des problèmes graves peuvent survenir plus tard dans le convertisseur, et dans un tel cas une exception sera levée avec la liste des erreurs de formatage détectées. |
| ThrowExceptionImmediately | `1` | Dans ce cas, la conversion sera arrêtée immédiatement et une exception sera levée immédiatement après la détection de la première erreur de formatage. |
| InvokeCustomHandler | `2` | Ceci est la méthode la plus agile - le code personnalisé doit fournir (dans la propriété WarningCallback) un gestionnaire spécial qui sera appelé lorsqu'une erreur de formatage est détectée. Ce gestionnaire peut par ex. enregistrer ou compter les erreurs, etc., et fournira la décision de savoir si le traitement peut être poursuivi pour telle ou telle erreur. |

### Voir aussi

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


