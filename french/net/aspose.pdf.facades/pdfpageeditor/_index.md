---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfPageEditor. Représente une classe pour éditer les pages des fichiers PDF, y compris la rotation de page, le zoom de page, le déplacement de position et le changement de taille de page.
type: docs
weight: 4590
url: /fr/net/aspose.pdf.facades/pdfpageeditor/
---
## Classe PdfPageEditor

Représente une classe pour éditer la page d'un fichier PDF, y compris la rotation de page, le zoom de page, le déplacement de position et le changement de taille de page.

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur lequel il travaille. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Obtient ou définit l'alignement horizontal du contenu PDF original sur la page résultante, par défaut c'est AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Un hashtable contenant le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Obtient ou définit la taille de page du fichier de sortie. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Obtient ou définit les numéros de page à éditer. Par défaut, chaque page serait éditée. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Obtient ou définit la rotation des pages, la rotation doit être 0, 90, 180 ou 270. La valeur par défaut est 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Obtient ou définit la durée de l'effet de transition. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Obtient ou définit le style de transition à utiliser lors du passage à cette page depuis une autre pendant une présentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Obtient ou définit l'alignement vertical du contenu PDF original sur la page résultante, par défaut c'est VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Obtient ou définit le coefficient de zoom. La valeur 1.0 correspond à 100 %. La valeur par défaut est 1.0.  L'exemple suivant démontre comment changer le zoom des pages du document. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Applique les modifications apportées aux pages du document. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Dispose d'Aspose.Pdf.Document lié à une façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Retourne la taille de la boîte spécifiée dans le document. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Retourne la rotation de la page spécifiée. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Retourne le nombre total de pages. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Retourne la taille de la page de la page spécifiée. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Déplace l'origine de (0, 0) au point désigné. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Enregistre le document modifié dans le flux. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Enregistre le document modifié dans un fichier. |

## Champs

| Nom | Description |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Stores verticales |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Stores verticales |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Essuyage Bas-Haut |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Scintillement Diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | La vieille page se dissout |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Boîte intérieure |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Scintillement Gauche-Droite |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Essuyage Gauche-Droite |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Boîte extérieure |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Essuyage Droite-Gauche |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Division Horizontale IN |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Division Horizontale Out |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | Division Verticale In |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Division Verticale Out |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Scintillement Haut-Bas |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Essuyage Haut-Bas |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)