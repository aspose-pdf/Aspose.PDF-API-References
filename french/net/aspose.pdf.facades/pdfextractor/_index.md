---
title: PdfExtractor
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe pour extraire des images et du texte dun document PDF.
type: docs
weight: 2460
url: /fr/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Classe pour extraire des images et du texte d'un document PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Initialise nouveau[`PdfExtractor`](../pdfextractor) objet. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Initialise nouveau[`PdfExtractor`](../pdfextractor) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Définit le mode de traitement des images d'extraction. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Définit le mode d'extraction du résultat du texte. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | Est vrai lorsque le texte contient des symboles hébreux ou arabes. Ce cas doit être particulièrement considéré car les fonctions de chaîne changent leur comportement et commencent à traiter le texte de droite à gauche (sauf les nombres et autres caractères non textuels). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Obtient ou définit le mot de passe du fichier d'entrée. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Définit ou obtient la résolution des images extraites. La valeur par défaut est 150. Les images qui ont une valeur de résolution supérieure sont plus claires. Cependant, l'augmentation de la valeur de résolution entraîne une augmentation du temps et de la mémoire nécessaires pour extraire les images. Habituellement, pour obtenir une image claire, c'est suffisant pour régler la résolution sur 150 ou 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Obtient ou définit la page de démarrage dans la plage de pages où l'opération d'extraction sera effectuée. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Obtient ou définit les options de recherche de texte. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Lie le document PDF à partir du flux. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | Lier le fichier PDF d'entrée. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Dispose Aspose.Pdf.Document relié avec une façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Extrait les pièces jointes d'un document PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Extrait la pièce jointe au fichier PDF par nom de pièce jointe. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | Extraire des images d'un fichier PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Extrait le texte d'un document PDF en utilisant l'encodage Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Extrait le texte d'un document PDF en utilisant l'encodage spécifié. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Enregistre tous les fichiers joints dans les flux. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Stocke la pièce jointe dans le fichier. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Obtient la liste des pièces jointes. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelé avant d'utiliser cette méthode. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | Récupérer l'image suivante du fichier PDF et la stocker dans le flux. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | Récupère l'image suivante du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | Récupérer l'image suivante du fichier PDF et la stocker dans le flux avec le format d'image donné. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Récupère l'image suivante du document PDF avec le format d'image donné. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Enregistre le texte d'une page à diffuser. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Enregistre le texte d'une page dans un fichier. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Enregistre le texte à diffuser. voir également:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Enregistre le texte dans un fichier. voir également:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Enregistre le texte à diffuser. voir également:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | Vérifie si plus d'images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Indique si vous pouvez obtenir plus de textes ou non. |

### Voir également

* class [Facade](../facade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
