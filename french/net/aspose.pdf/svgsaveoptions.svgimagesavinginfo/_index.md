---
title: Class SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgSaveOptionsSvgImageSavingInfo. Cette classe représente un ensemble de données liées à la sauvegarde des fichiers image de ressources externes lors de la conversion de PDF en HTML
type: docs
weight: 10260
url: /fr/net/aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
## Classe SvgSaveOptions.SvgImageSavingInfo

Cette classe représente un ensemble de données liées à la sauvegarde des fichiers image de ressources externes lors de la conversion de PDF en HTML.

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où sauvegarder ce fichier. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier sauvegardé. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour une raison quelconque, le fichier proposé doit être traité non pas avec le code personnalisé mais avec le code du convertisseur lui-même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui-même (dans les deux sens - pour le sauvegarder quelque part et pour le nommer dans le fichier référencé). |
| [ImageType](../../aspose.pdf/svgsaveoptions.svgimagesavinginfo/imagetype) | Représente le type d'image sauvegardée référencée dans HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider ce qui doit être fait. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où sauvegarder ce fichier. |

### Voir aussi

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [SvgSaveOptions](../svgsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)