---
title: "Classe SaveOptions.ResourceSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.SaveOptionsResourceSavingInfo. Cette classe représente un ensemble de données liées à la sauvegarde de fichiers de ressources externes qui se produit lors de la conversion de PDF vers un autre format, p. ex. HTML"
type: docs
weight: 10090
url: /fr/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## SaveOptions.ResourceSavingInfo class

Cette classe représente un ensemble de données liées à l'enregistrement du fichier de ressource externe qui se produit lors de la conversion du PDF vers un autre format (p. ex. HTML)

```csharp
public class ResourceSavingInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier enregistré. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard. Ainsi, le fait de le définir sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l'enregistrement quelque part et pour le nommage dans le fichier de référence). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


