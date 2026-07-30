---
title: "Classe HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Cette classe représente un ensemble de données liées à l’enregistrement des fichiers image de ressources externes lors de la conversion PDF vers HTML"
type: docs
weight: 5770
url: /fr/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Cette classe représente un ensemble de données liées à l'enregistrement du fichier image de ressource externe lors de la conversion PDF vers HTML.

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier enregistré. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour certaines raisons, le fichier proposé doit être traité non pas par le code personnalisé mais par le code du convertisseur lui‑même de manière standard. Ainsi, le fait de le définir sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui‑même (dans les deux sens – pour l'enregistrement quelque part et pour le nommage dans le fichier de référence). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Indique au code personnalisé à quelle page du jeu de fichiers HTML générés l’image enregistrée se rapporte. Si la division en pages est désactivée, cette valeur contient toujours « 1 » car dans ce cas une seule page HTML est générée. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Représente le type d’image enregistrée référencée dans le HTML. Défini par le convertisseur et peut être utilisé dans le code personnalisé pour décider de l’action à entreprendre |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | L’image enregistrée peut concerner le HTML lui‑même ou être extraite d’un SVG intégré au HTML. Cette propriété peut indiquer au code personnalisé le type de parent de l’image traitée. Elle est définie par le convertisseur et peut être utilisée dans le code personnalisé pour décider de ce qui doit être fait avec cette image (par ex. le code personnalisé peut décider où enregistrer l’image ou comment elle doit être référencée dans le contenu du parent). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Indique au code personnalisé à quelle page du document PDF original l’image enregistrée se rapporte. Puisqu’il est possible que toutes les pages du document original ne soient pas enregistrées, cette valeur indique le numéro de page d’origine dans le PDF. Si, pour une raison quelconque, le numéro de page d’origine est inconnu, elle renvoie toujours « 1 ». |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui provient du convertisseur vers le code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où enregistrer ce fichier. |

### Voir aussi

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


