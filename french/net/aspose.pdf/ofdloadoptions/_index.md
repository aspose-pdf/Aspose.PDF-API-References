---
title: Class OfdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OfdLoadOptions. Options de chargement pour le format OFD
type: docs
weight: 7060
url: /fr/net/aspose.pdf/ofdloadoptions/
---
## Classe OfdLoadOptions

Options de chargement pour le format OFD.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement se poursuit, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)