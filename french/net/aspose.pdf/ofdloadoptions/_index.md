---
title: "Classe OfdLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.OfdLoadOptions classe. Options de chargement pour le format OFD."
type: docs
weight: 7200
url: /fr/net/aspose.pdf/ofdloadoptions/
---
## OfdLoadOptions class

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
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


