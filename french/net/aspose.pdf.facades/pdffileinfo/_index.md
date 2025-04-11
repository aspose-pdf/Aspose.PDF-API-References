---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileInfo. Représente une classe pour accéder aux métadonnées du document PDF
type: docs
weight: 4520
url: /fr/net/aspose.pdf.facades/pdffileinfo/
---
## Classe PdfFileInfo

Représente une classe pour accéder aux métadonnées du document PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Initialise une nouvelle instance de la classe Aspose.Pdf.Facades.PdfFileInfo avec des valeurs par défaut. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Initialise un nouvel objet `PdfFileInfo` sur la base du *document*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Initialise une nouvelle instance de la classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Initialise une nouvelle instance de la classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Initialise une nouvelle instance de la classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Initialise une nouvelle instance de la classe Aspose.Pdf.Facades.PdfFileInfo. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Obtient ou définit les informations sur l'auteur du document PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Obtient ou définit les informations sur la date de création du document PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Obtient ou définit les informations sur le créateur du document PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient le façade du document sur lequel il travaille. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Renvoie vrai si le fichier d'entrée actuel est un fichier 'Portfolio' contenant une collection de fichiers PDF. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Renvoie vrai si un mot de passe est nécessaire pour modifier les permissions ou la propriété de sécurité du document. Faites attention, cette propriété ne peut être lue que si un mot de passe valide a été fourni dans le constructeur `PdfFileInfo`. Si le PasswordType est Inaccessible (ce qui signifie qu'un mot de passe invalide a été fourni), la lecture de cette propriété échouera avec [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Renvoie vrai si un mot de passe est nécessaire pour ouvrir un document PDF protégé par mot de passe. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Obtient ou définit les informations personnalisées du document PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Vérifie si le document PDF est crypté. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Vérifie si l'entrée source est un fichier PDF valide. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Obtient ou définit les informations sur les mots-clés du document PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Obtient ou définit les informations sur la date de modification du document PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Obtient le nombre de pages du document. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Renvoie le type de mot de passe qui a été passé pour créer l'instance PdfFileInfo. Voir les valeurs possibles dans [`PasswordType`](./passwordtype/). Faites attention, le document PDF peut être ouvert en utilisant à la fois le mot de passe utilisateur (ou d'ouverture) et le mot de passe propriétaire (ou permissions, édition). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Obtient les informations sur le producteur du document PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Obtient ou définit les informations sur le sujet du document PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Obtient ou définit les informations sur le titre du document PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Utilise des règles de validation strictes via la propriété [`IsPdfFile`](./ispdffile/). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Efface toutes les métadonnées du document PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Désinitialise l'instance. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Obtient les paramètres de privilège du document PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Obtient les informations personnalisées du document PDF avec le nom de la propriété. S'il n'y a pas de propriété correspondant au nom, cela renverra une chaîne vide. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Obtient la hauteur de la page spécifiée. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Obtient la rotation de la page spécifiée. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Obtient la largeur de la page spécifiée. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Obtient le décalage horizontal de la zone d'affichage de la page spécifiée. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Obtient le décalage vertical de la zone d'affichage de la page spécifiée. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Obtient les informations de version du document PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Enregistre le document PDF dans le fichier spécifié. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Enregistre le document PDF mis à jour dans le fichier spécifié. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Modifie les propriétés spécifiées explicitement en définissant les informations du fichier, les autres propriétés restent. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Définit les informations personnalisées du document PDF. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)