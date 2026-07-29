---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs de formatage."
type: docs
weight: 5790
url: /fr/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Le document source XSLFO peut contenir des erreurs de formatage. Cette énumération énumère les stratégies possibles de gestion de ces erreurs de formatage.

## Champs

| Champ | Description |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Ceci est la méthode la plus agile - le code personnalisé doit fournir (dans la propriété WarningCallback) un gestionnaire spécial qui sera appelé lorsqu'une erreur de formatage est détectée. Ce gestionnaire peut, par ex., enregistrer ou compter les erreurs, etc., et fournira la décision de savoir si le traitement peut être poursuivi pour cette ou cette autre erreur. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | Dans ce cas, la conversion sera arrêtée immédiatement et une exception sera levée immédiatement après la détection de la première erreur de formatage. |
| [TryIgnore](#TryIgnore) | Dans ce cas, le convertisseur sera instruit d'essayer de poursuivre la conversion et d'ignorer les erreurs de formatage trouvées. Dans ce cas, le succès n'est pas garanti, des problèmes graves peuvent survenir plus tard dans le convertisseur, et dans un tel cas une exception sera levée avec la liste des erreurs de formatage trouvées. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Ceci est la méthode la plus agile - le code personnalisé doit fournir (dans la propriété WarningCallback) un gestionnaire spécial qui sera appelé lorsqu'une erreur de formatage est détectée. Ce gestionnaire peut, par ex., enregistrer ou compter les erreurs, etc., et fournira la décision de savoir si le traitement peut être poursuivi pour cette ou cette autre erreur.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

Dans ce cas, la conversion sera arrêtée immédiatement et une exception sera levée immédiatement après la détection de la première erreur de formatage.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

Dans ce cas, le convertisseur sera instruit d'essayer de poursuivre la conversion et d'ignorer les erreurs de formatage trouvées. Dans ce cas, le succès n'est pas garanti, des problèmes graves peuvent survenir plus tard dans le convertisseur, et dans un tel cas une exception sera levée avec la liste des erreurs de formatage trouvées.
