---
title: PdfFileStamp
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe pour ajouter des tampons filigrane ou arrière-plan aux fichiers PDF.
type: docs
weight: 2580
url: /fr/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Classe pour ajouter des tampons (filigrane ou arrière-plan) aux fichiers PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | Constructeur du PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Initialise nouveau[`PdfFileStamp`](../pdffilestamp) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | Obtient ou définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | Obtient ou définit la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. Valeur possible : en ligne / pièce jointe. Par défaut : en ligne. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | Définit le format de fichier PDF. Le fichier de résultat sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Maintient la sécurité si vrai. (Cette fonctionnalité sera implémentée dans les prochaines versions). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Obtient ou définit le style de numérotation des pages. Valeurs possibles : NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Obtient ou définit l'indicateur d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si cet indicateur est activé. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des besoins en mémoire plus importants. Valeur par défaut : false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Obtient la hauteur de la première page dans le fichier source. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Obtient ou définit la rotation du numéro de page. La rotation est en degrés. La valeur par défaut est 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Obtient la largeur de la première page dans le fichier d'entrée. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | Obtient ou définit l'objet de réponse où le résultat de l'opération sera stocké. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | ID de tampon du prochain tampon ajouté (y compris les en-têtes de page/les sirènes/les numéros de page). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Obtient ou définit le numéro de départ de la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est défini sur 100, les pages du document auront les numéros 100, 101, 102... |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Ajoute un pied de page aux pages du document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Ajoute une image en pied de page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Ajoute une image comme pied de page aux pages du document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Ajoute un pied de page aux pages du document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Ajoute une image en pied de page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Ajoute une image en pied de page des pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Ajoute un en-tête à la page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Ajoute une image comme en-tête sur les pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Ajoute une image comme en-tête aux pages du fichier. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Ajoute un en-tête aux pages du fichier. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Ajoute une image en haut de la page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Ajoute une image comme en-tête sur les pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Ajoute un numéro de page à la page. Le numéro de page peut contenir le signe # qui sera remplacé par le numéro de page. Le numéro de page est placé en bas de la page centré horizontalement. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Ajouter le numéro de page au fichier. Le texte du numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page centré horizontalement. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Ajoute un numéro de page aux pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Ajoute un numéro de page aux pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Ajoute un numéro de page à la position spécifiée sur la page. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Ajoute un numéro de page à la position spécifiée sur la page. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Ajoute un numéro de page aux pages du document. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Ajoute un numéro de page aux pages du document. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Ajoute un tampon au fichier. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Ferme les fichiers ouverts et enregistre les modifications. Avertissement. Si des flux d'entrée ou de sortie sont spécifiés, ils ne sont pas fermés par la méthode Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Enregistre le document dans le flux spécifié. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Enregistre le résultat dans le fichier spécifié. |

## Des champs

| Nom | La description |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Position en bas à gauche. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Position médiane inférieure. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Position en bas à droite. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Position gauche. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Position droite. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Position let supérieure. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Position médiane supérieure. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Position supérieure droite. |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
