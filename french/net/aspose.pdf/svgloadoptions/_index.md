---
title: "Classe SvgLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.SvgLoadOptions class. Représente les options de chargement/importation d'un fichier SVG dans un document pdf"
type: docs
weight: 10390
url: /fr/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

Représente les options de chargement/importation d'un fichier SVG dans un document pdf.

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
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Ajuste la taille de la page pdf à la taille du svg |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Obtient ou définit les informations de page qui doivent être appliquées lors du chargement du document. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Permet de sélectionner le moteur de conversion qui sera utilisé pendant la conversion. Actuellement, le nouveau moteur est en phase de B-testing, donc cette valeur est par défaut définie sur ConversionEngines.LegacyEngine |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


