---
title: "Classe CgmLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.CgmLoadOptions. Contient des options pour charger/importer un fichier CGM dans un document pdf"
type: docs
weight: 3120
url: /fr/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

Contient des options pour le chargement/l'importation d'un fichier CGM dans un document pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Crée les options de chargement par défaut pour convertir un fichier CGM en document pdf. Taille de page pdf par défaut - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Crée des options de chargement avec la taille de page définie !:pageSize. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Obtient ou définit la taille de page de sortie pour l’importation. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


