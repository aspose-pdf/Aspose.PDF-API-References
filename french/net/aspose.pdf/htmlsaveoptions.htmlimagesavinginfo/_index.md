---
title: HtmlSaveOptions.HtmlImageSavingInfo
second_title: Référence de l'API Aspose.PDF pour .NET
description: Cette classe représente un ensemble de données liées à lenregistrement du fichier image de ressource externe lors de la conversion PDF en HTML.
type: docs
weight: 3510
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion PDF en HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [HtmlImageSavingInfo](htmlimagesavinginfo)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [ResourceType](../../aspose.pdf/resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui va du convertisseur au code de la méthode personnalisée Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier |

## Des champs

| Nom | La description |
| --- | --- |
| [ContentStream](../../aspose.pdf/resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier enregistré. |
| [CustomProcessingCancelled](../../aspose.pdf/resourcesavinginfo/customprocessingcancelled) | cet indicateur doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas avec un code personnalisé mais avec le code du convertisseur lui-même en standard pour le convertisseur. Ainsi, ce paramètre défini sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui-même (dans les deux sens - pour enregistrer quelque part et pour nommer dans le fichier de référence). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlimagesavinginfo/htmlhostpagenumber) | Indique au code personnalisé à quelle page de l'ensemble généré de fichiers de page HTML appartient l'image enregistrée. Si le fractionnement sur les pages est désactivé, cette valeur contient toujours '1' puisque dans ce cas Une seule page HTML est générée. |
| [ImageType](../../aspose.pdf/htmlimagesavinginfo/imagetype) | Représente le type d'image enregistrée référencé dans HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider de ce qui doit être fait |
| [ParentType](../../aspose.pdf/htmlimagesavinginfo/parenttype) | L'image enregistrée peut appartenir au HTML lui-même ou peut être extraite. du SVG intégré au HTML. Cette propriété peut indiquer au code personnalisé quel est ce type de parent de l'image traitée. Il est défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider de ce qui doit être fait avec cette image (par exemple, le code personnalisé peut décider où enregistrer l'image ou comment elle doit être référencée dans le contenu du parent). |
| [PdfHostPageNumber](../../aspose.pdf/htmlimagesavinginfo/pdfhostpagenumber) | Indique au code personnalisé à quelle page du document PDF original appartient l'image enregistrée Puisqu'il est possible que toutes les pages du document original ne soient pas enregistrées, cette valeur nous indique le numéro de page hôte dans le PDF original. Si le numéro de page d'origine pour une raison quelconque est inconnu, il renvoie toujours '1' |
| [SupposedFileName](../../aspose.pdf/resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui va du convertisseur au code de la méthode personnalisée Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier |

### Voir également

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo)
* class [HtmlSaveOptions](../htmlsaveoptions)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->