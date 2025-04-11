---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.SubmitFormAction. Classe qui décrit l'action de soumission de formulaire
type: docs
weight: 2640
url: /fr/net/aspose.pdf.annotations/submitformaction/
---
## Classe SubmitFormAction

Classe qui décrit l'action de soumission de formulaire.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Initialise l'objet SubmitFormAction. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Obtient ou définit les drapeaux de l'action de soumission |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Actions suivantes dans la séquence. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL de destination. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Obtient la chaîne pour l'action ECMAScript. |

## Champs

| Nom | Description |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Si défini, toutes les valeurs de champ soumises représentant des dates seront converties au format standard. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Si défini, l'entrée F du FDF soumis sera une spécification de fichier contenant un flux de fichier intégré représentant le fichier PDF à partir duquel le FDF est soumis. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Si défini, le FDF soumis exclura l'entrée F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Si défini, il inclura uniquement les annotations de balisage dont l'entrée T correspond au nom de l'utilisateur actuel. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Si clair, le tableau Fields spécifie quels champs inclure dans la soumission. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Si défini, les noms et valeurs des champs seront soumis au format de formulaire HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Si défini, les noms et valeurs des champs seront soumis en utilisant une requête HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Si défini, le fichier FDF soumis inclura toutes les annotations de balisage dans le document PDF sous-jacent. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Si défini, le fichier FDF soumis inclura le contenu de toutes les mises à jour incrémentielles. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Si défini, tous les champs désignés par le tableau Fields et le drapeau Include/Exclude seront soumis. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Si défini, les coordonnées du clic de souris qui a causé l'action de soumission de formulaire seront transmises comme partie des données du formulaire. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Si défini, le document sera soumis en tant que PDF, en utilisant le type de contenu MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Si défini, les noms et valeurs des champs seront soumis en tant que XFDF. |

### Voir aussi

* classe [PdfAction](../pdfaction/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)