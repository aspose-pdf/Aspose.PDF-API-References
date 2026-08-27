---
title: "Classe PdfExtractor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Facades.PdfExtractor class. Classe permettant d'extraire des images et du texte d'un document PDF"
type: docs
weight: 4570
url: /fr/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Classe pour extraire les images et le texte d'un PDF Document.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Initialise un nouvel objet `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Initialise un nouvel objet `PdfExtractor` basé sur le *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Obtient ou définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Définit le mode du processus d'extraction d'images. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Définit le mode du résultat d'extraction de texte. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Est vrai lorsque le texte contient des symboles hébreux ou arabes. Ce cas doit être spécialement pris en compte car les fonctions de chaîne changent leur comportement et commencent le traitement du texte de droite à gauche (sauf les chiffres et les autres caractères non textuels). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Obtient ou définit le mot de passe du fichier d'entrée. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Définit ou obtient la résolution des images extraites. La valeur par défaut est 150. Les images avec une résolution supérieure sont plus nettes. Cependant, augmenter la résolution augmente le temps et la mémoire nécessaires à l'extraction des images. En général, pour obtenir une image claire, il suffit de régler la résolution à 150 ou 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Obtient ou définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Lie le document PDF depuis le flux. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Lie le fichier PDF d'entrée. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libère Aspose.Pdf.Document lié à une façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extrait les pièces jointes d'un document Pdf. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extrait la pièce jointe du fichier PDF par le nom de la pièce jointe. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extrait les images du fichier PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extrait le texte d'un document Pdf en utilisant l'encodage Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extrait le texte d'un document Pdf en utilisant l'encodage spécifié. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Enregistre tous les fichiers de pièces jointes dans des flux. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Enregistre la pièce jointe dans un fichier. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Obtient la liste des pièces jointes. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelé avant d'utiliser cette méthode. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Récupère l'image suivante du fichier PDF et l'enregistre dans un flux. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Récupère l'image suivante du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Récupère l'image suivante du fichier PDF et l'enregistre dans un flux avec le format d'image donné. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Récupère l'image suivante du document PDF avec le format d'image donné. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Enregistre le texte d'une page dans un flux. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Enregistre le texte d'une page dans un fichier. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Enregistre le texte dans un flux. voir aussi :[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Enregistre le texte dans un fichier. voir aussi :[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Enregistre le texte dans un flux. voir aussi :[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indique s'il est possible d'obtenir plus de texte ou non. |

### Voir aussi

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


