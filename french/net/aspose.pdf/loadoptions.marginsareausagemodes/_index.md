---
title: "Enum LoadOptions.MarginsAreaUsageModes"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Enum Aspose.Pdf.LoadOptionsMarginsAreaUsageModes. Représente le mode d'utilisation de la zone des marges lors de la conversion, comme HTML, EPUB, etc., définit le traitement des instructions du format importé liées à l'utilisation des marges."
type: docs
weight: 6270
url: /fr/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

Représente le mode d'utilisation de la zone des marges lors de la conversion (comme HTML, EPUB, etc.), définit le traitement des instructions du format importé liées à l'utilisation des marges.

```csharp
public enum MarginsAreaUsageModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | Dans ce mode, le convertisseur respecte le format du document importé (par ex. le CSS du HTML importé) dans l'utilisation de la zone des marges. Ainsi, si le format du document importé nécessite l'utilisation de la zone des marges pour le rendu, le convertisseur le permettra. |
| NeverPutContentOnMarginArea | `1` | Ce mode interdit strictement l'utilisation de la zone des marges, ainsi le convertisseur n'utilisera jamais la zone des marges pour le rendu, même si le CSS ou le format du document source le permet ou l'exige. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


