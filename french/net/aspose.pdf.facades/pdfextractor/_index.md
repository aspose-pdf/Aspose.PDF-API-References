---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfExtractor. Classe pour extraire des images et du texte d'un document PDF
type: docs
weight: 4450
url: /fr/net/aspose.pdf.facades/pdfextractor/
---
## Classe PdfExtractor

Classe pour extraire des images et du texte d'un document PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Initialise un nouvel objet `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Initialise un nouvel objet `PdfExtractor` sur la base du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient le document sur lequel la façade travaille. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Définit le mode pour le processus d'extraction d'images. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Définit le mode pour le résultat de l'extraction de texte. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Est vrai lorsque le texte contient des symboles hébreux ou arabes. Ce cas doit être considéré spécialement car les fonctions de chaîne changent leur comportement et commencent à traiter le texte de droite à gauche (sauf pour les chiffres et autres caractères non textuels). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Obtient ou définit le mot de passe du fichier d'entrée. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Définit ou obtient la résolution pour les images extraites. La valeur par défaut est 150. Les images ayant une valeur de résolution plus élevée sont plus claires. Cependant, l'augmentation de la valeur de résolution entraîne une augmentation du temps et de la mémoire nécessaires pour extraire les images. En général, pour obtenir une image claire, il suffit de définir la résolution à 150 ou 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Obtient ou définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Lie le document PDF à partir du flux. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Lie le fichier PDF d'entrée. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Dispose le document Aspose.Pdf lié à une façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose la façade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extrait les pièces jointes d'un document PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extrait une pièce jointe au fichier PDF par le nom de la pièce jointe. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extrait des images d'un fichier PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extrait du texte d'un document PDF en utilisant l'encodage Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extrait du texte d'un document PDF en utilisant l'encodage spécifié. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Enregistre tous les fichiers de pièces jointes dans des flux. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Stocke la pièce jointe dans un fichier. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Obtient la liste des pièces jointes. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelé avant d'utiliser cette méthode. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Récupère la prochaine image du fichier PDF et la stocke dans le flux. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Récupère la prochaine image du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Récupère la prochaine image du fichier PDF et la stocke dans le flux avec le format d'image donné. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Récupère la prochaine image du document PDF avec le format d'image donné. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Enregistre le texte d'une page dans le flux. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Enregistre le texte d'une page dans un fichier. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Enregistre le texte dans le flux. voir aussi : [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Enregistre le texte dans un fichier. voir aussi : [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Enregistre le texte dans le flux. voir aussi : [`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indique si d'autres textes peuvent être récupérés ou non. |

### Voir aussi

* classe [Facade](../facade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)