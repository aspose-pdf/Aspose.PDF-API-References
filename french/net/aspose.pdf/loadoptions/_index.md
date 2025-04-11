---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LoadOptions. Le type LoadOptions contient un niveau d'abstraction sur les options de chargement individuelles
type: docs
weight: 6120
url: /fr/net/aspose.pdf/loadoptions/
---
## Classe LoadOptions

Le type LoadOptions contient un niveau d'abstraction sur les options de chargement individuelles

```csharp
public abstract class LoadOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple, permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit `LoadOptions`. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continue soit Abort. Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abort dans ce cas l'opération de chargement doit cesser. |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)