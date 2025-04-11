---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. Le document XSLFO source peut contenir des erreurs de formatage. Cet enum énumère les stratégies possibles de gestion de ces erreurs de formatage.
type: docs
weight: 11540
url: /fr/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## Énumération XslFoLoadOptions.ParsingErrorsHandlingTypes

Le document XSLFO source peut contenir des erreurs de formatage. Cet enum énumère les stratégies possibles de gestion de ces erreurs de formatage.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| TryIgnore | `0` | Dans ce cas, le convertisseur sera instruit d'essayer de procéder à la conversion et d'ignorer les erreurs de formatage trouvées. Dans ce cas, le succès n'est pas garanti, des problèmes graves peuvent survenir plus tard dans le convertisseur, et dans ce cas, une exception sera levée avec la liste des erreurs de formatage trouvées. |
| ThrowExceptionImmediately | `1` | Dans ce cas, la conversion sera arrêtée immédiatement et une exception sera levée immédiatement après la détection de la première erreur de formatage. |
| InvokeCustomHandler | `2` | C'est la méthode la plus agile - le code personnalisé doit fournir (dans la propriété WarningCallback) un gestionnaire spécial qui sera appelé lorsque l'erreur de formatage est détectée. Ce gestionnaire peut, par exemple, enregistrer ou compter les erreurs, etc., et fournira une décision quant à savoir si le traitement peut être poursuivi pour cette erreur ou cette erreur. |

### Voir aussi

* classe [XslFoLoadOptions](../xslfoloadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)