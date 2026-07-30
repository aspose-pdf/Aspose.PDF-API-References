---
title: "Classe PdfPageEditor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.PdfPageEditor. Représente une classe permettant de modifier la page des fichiers PDF, y compris la rotation, le zoom, le déplacement de la position et le changement de la taille de la page."
type: docs
weight: 4710
url: /fr/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Représente une classe pour modifier la Page du fichier PDF, incluant la rotation de la Page, le zoom de la Page, le déplacement et le changement de taille de la Page.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Constructeur de la classe PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Constructeur de la classe PdfPageEditor. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Obtient ou définit la durée d'affichage des pages. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du contenu PDF original sur la page résultante, la valeur par défaut est AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Une table de hachage contient le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Obtient ou définit la taille de page du fichier de sortie. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Obtient ou définit les numéros de pages à modifier. Par défaut, chaque page sera modifiée. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Obtient ou définit la rotation des pages, la rotation doit être 0, 90, 180 ou 270. La valeur par défaut est 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Obtient ou définit la durée de l'effet de transition. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Obtient ou définit le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Obtient ou définit l'alignement vertical du contenu PDF original sur la page résultante, la valeur par défaut est VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Obtient ou définit le coefficient de zoom. La valeur 1.0 correspond à 100 %. La valeur par défaut est 1.0. L'exemple suivant montre comment modifier le zoom des pages du document. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Appliquer les modifications apportées aux pages du document. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libère Aspose.Pdf.Document lié à une façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Renvoie la taille de la boîte spécifiée dans le document. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Renvoie la rotation de la page spécifiée. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Renvoie le nombre total de pages. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Renvoie la taille de la page spécifiée. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Déplace l'origine de (0, 0) vers le point indiqué. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Enregistre le document modifié dans un flux. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Enregistre le document modifié dans un fichier. |

## Champs

| Nom | Description |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Stores verticales |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Stores verticales |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Balayage du bas vers le haut |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Scintillement diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | L'ancienne page se dissout |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Boîte vers l'intérieur |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Scintillement gauche-droite |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Balayage gauche-droite |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Boîte vers l'extérieur |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Balayage droite-gauche |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Division horizontale IN |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Division horizontale OUT |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | En division verticale |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Division verticale sortante |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Scintillement haut-bas |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Essuyage haut-bas |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


