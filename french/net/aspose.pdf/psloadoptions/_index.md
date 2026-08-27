---
title: "Classe PsLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PsLoadOptions. Représente les options de chargement/importation d'un fichier .mhtfile dans un document pdf"
type: docs
weight: 9880
url: /fr/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

Représente les options de chargement/importation d'un fichier .mht dans un document pdf.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | Spécifie s'il faut enregistrer les polices non TrueType au format TTF. Cela réduit considérablement le volume du document résultant lors de la conversion PS vers PDF et augmente la vitesse de conversion des fichiers PS contenant une grande quantité de texte en polices non TrueType vers n'importe quel format de sortie. Cependant, il y a un léger décalage vertical du texte lors de la conversion d'un fichier PostSctipt en image. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Obtient ou définit les chemins des dossiers de polices. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


