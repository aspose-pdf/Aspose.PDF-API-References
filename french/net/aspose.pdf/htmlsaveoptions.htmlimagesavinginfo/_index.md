---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Cette classe représente un ensemble de données liées à la sauvegarde des fichiers d'image de ressources externes lors de la conversion de PDF en HTML
type: docs
weight: 5640
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## Classe HtmlSaveOptions.HtmlImageSavingInfo

Cette classe représente un ensemble de données liées à la sauvegarde des fichiers d'image de ressources externes lors de la conversion de PDF en HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où sauvegarder ce fichier. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier sauvegardé. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour une raison quelconque, le fichier proposé doit être traité non pas avec le code personnalisé mais avec le code du convertisseur lui-même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui-même (dans les deux sens - pour le sauvegarder quelque part et pour le nommer dans le fichier référencé). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Indique au code personnalisé à quelle page de l'ensemble généré de fichiers HTML la sauvegarde de l'image se rapporte. Si le fractionnement en pages est désactivé, cette valeur contient toujours '1' car dans ce cas, une seule page HTML est générée. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Représente le type d'image sauvegardée référencée dans HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider ce qui doit être fait. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | L'image sauvegardée peut se rapporter à HTML lui-même ou peut être extraite d'un SVG intégré dans HTML. Cette propriété peut indiquer au code personnalisé quel est le type de parent de l'image traitée. Elle est définie par le convertisseur et peut être utilisée dans le code personnalisé pour décider ce qui doit être fait avec cette image (par exemple, le code personnalisé peut décider où sauvegarder l'image ou comment elle doit être référencée dans le contenu parent). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Indique au code personnalisé à quelle page du document PDF original l'image sauvegardée se rapporte. Étant donné qu'il est possible que toutes les pages du document original ne soient pas sauvegardées, cette valeur nous indique le numéro de page hôte dans le PDF original. Si le numéro de page original est inconnu pour une raison quelconque, il renvoie toujours '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où sauvegarder ce fichier. |

### Voir aussi

* classe [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)