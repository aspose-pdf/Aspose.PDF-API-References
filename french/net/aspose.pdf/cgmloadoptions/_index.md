---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.CgmLoadOptions. Contient des options pour charger/importer un fichier CGM dans un document pdf
type: docs
weight: 3010
url: /fr/net/aspose.pdf/cgmloadoptions/
---
## Classe CgmLoadOptions

Contient des options pour charger/importer un fichier CGM dans un document pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Crée des options de chargement par défaut pour convertir un fichier CGM en document pdf. Taille de page pdf par défaut - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Crée des options de chargement avec une !:pageSize définie. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Obtient ou définit la taille de page de sortie pour l'importation. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)