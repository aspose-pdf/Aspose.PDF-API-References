---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.CdrLoadOptions. La classe décrit les options de chargement CDR
type: docs
weight: 2960
url: /fr/net/aspose.pdf/cdrloadoptions/
---
## Classe CdrLoadOptions

La classe décrit les options de chargement CDR.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)