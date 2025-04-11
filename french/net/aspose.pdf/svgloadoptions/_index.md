---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgLoadOptions. Représente les options pour charger/importer un fichier SVG dans un document PDF
type: docs
weight: 10210
url: /fr/net/aspose.pdf/svgloadoptions/
---
## Classe SvgLoadOptions

Représente les options pour charger/importer un fichier SVG dans un document PDF.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Ajuste la taille de la page PDF à la taille SVG |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Obtient ou définit les informations de page qui doivent être appliquées lors du chargement du document. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Permet de sélectionner le moteur de conversion qui sera utilisé lors de la conversion. Actuellement, un nouveau moteur est en phase de test B, donc cette valeur est par défaut définie sur ConversionEngines.LegacyEngine |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)