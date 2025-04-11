---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileStamp. Classe pour ajouter des tampons, des filigranes ou des arrière-plans aux fichiers PDF
type: docs
weight: 4570
url: /fr/net/aspose.pdf.facades/pdffilestamp/
---
## Classe PdfFileStamp

Classe pour ajouter des tampons (filigrane ou arrière-plan) aux fichiers PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Constructeur de la classe PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Initialise un nouvel objet `PdfFileStamp` sur la base du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré dans le format PDF par défaut sans conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur lequel elle travaille. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Conserve la sécurité si vrai. (Cette fonctionnalité sera mise en œuvre dans les prochaines versions). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Obtient ou définit le style de numérotation des pages. Valeurs possibles : NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Obtient ou définit le drapeau d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est défini. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des besoins en mémoire plus importants. Valeur par défaut : false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Obtient la hauteur de la première page dans le fichier source. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Obtient ou définit la rotation du numéro de page. La rotation est en degrés. La valeur par défaut est 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Obtient la largeur de la première page dans le fichier d'entrée. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | ID du tampon du prochain tampon ajouté (y compris les en-têtes/pieds de page/numéros de page). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Obtient ou définit le numéro de départ pour la première page dans le fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est défini sur 100, les pages du document auront les numéros 100, 101, 102... |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Ajoute un pied de page aux pages du document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Ajoute une image comme pied de page de la page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Ajoute une image comme pied de page aux pages du document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Ajoute un pied de page aux pages du document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Ajoute une image comme pied de page de la page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Ajoute une image comme pied de page des pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Ajoute un en-tête à la page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Ajoute une image comme en-tête sur les pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Ajoute une image comme en-tête aux pages du fichier. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Ajoute un en-tête aux pages du fichier. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Ajoute une image en haut de la page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Ajoute une image comme en-tête sur les pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Ajoute un numéro de page à la page. Le numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page centré horizontalement. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Ajoute un numéro de page au fichier. Le texte du numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page centré horizontalement. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Ajoute un numéro de page aux pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Ajoute un numéro de page aux pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Ajoute un numéro de page à la position spécifiée sur la page. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Ajoute un numéro de page à la position spécifiée sur la page. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Ajoute un numéro de page aux pages du document. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Ajoute un numéro de page aux pages du document. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Ajoute un tampon au fichier. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Ferme les fichiers ouverts et enregistre les modifications. Avertissement. Si des flux d'entrée ou de sortie sont spécifiés, ils ne sont pas fermés par la méthode Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Enregistre le document dans le flux spécifié. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Enregistre le résultat dans le fichier spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Position en bas à gauche. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Position en bas au milieu. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Position en bas à droite. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Position à gauche. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Position à droite. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Position en haut à gauche. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Position en haut au milieu. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Position en haut à droite. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)