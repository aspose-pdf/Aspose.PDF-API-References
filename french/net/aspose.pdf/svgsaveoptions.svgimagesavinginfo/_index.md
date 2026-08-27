---
title: "Classe SvgSaveOptions.SvgImageSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "classe Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. Cette classe représente un ensemble de données liées à l'enregistrement des fichiers image de ressources externes lors de la conversion PDF vers HTML"
type: docs
weight: 10440
url: /fr/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## SvgSaveOptions.SvgImageSavingInfo class

Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion PDF vers HTML.

```csharp
public class SvgImageSavingInfo : ResourceSavingInfo
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgImageSavingInfo](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/.ctor)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier enregistré. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard. Ainsi, le fait de le définir sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l'enregistrement quelque part et pour le nommage dans le fichier de référence). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | représente le type d'image enregistrée référencée dans le HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider de l'action à entreprendre. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier. |

### Voir aussi

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


