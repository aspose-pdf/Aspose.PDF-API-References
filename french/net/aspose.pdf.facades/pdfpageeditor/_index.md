---
title: PdfPageEditor
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour modifier la page du fichier PDF y compris la rotation de la page le zoom de la page le déplacement de la position et la modification de la taille de la page.
type: docs
weight: 2600
url: /fr/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Représente une classe pour modifier la page du fichier PDF, y compris la rotation de la page, le zoom de la page, le déplacement de la position et la modification de la taille de la page.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | Constructeur pour la classe PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | Constructeur pour la classe PdfPageEditor. |

## Propriétés

| Nom | La description |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | Obtient ou définit la durée d'affichage des pages. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | Obtient ou définit l'alignement horizontal du contenu PDF d'origine sur la page de résultats, la valeur par défaut est AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | Une table de hachage contient le numéro de page et le degré de rotation, la clé représente le numéro de page, la valeur de la clé représente la rotation en degrés. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | Obtient ou définit la taille de page du fichier de sortie. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | Obtient ou définit les numéros de page à modifier. Par défaut, chaque page serait éditée. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | Obtient ou définit la rotation des pages, la rotation doit être de 0, 90, 180 ou 270. La valeur par défaut est 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | Obtient ou définit la durée de l'effet de transition. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | Obtient ou définit le style de transition à utiliser lors du déplacement vers cette page à partir d'une autre lors d'une présentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | Obtient ou définit l'alignement vertical du contenu PDF d'origine sur la page de résultats, la valeur par défaut est VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | Obtient ou définit le coefficient de zoom. La valeur 1.0 correspond à 100 %. La valeur par défaut est 1.0.  L'exemple suivant montre comment modifier le zoom des pages du document. |

## Méthodes

| Nom | La description |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | Appliquer les modifications apportées aux pages du document. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialise la façade. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Dispose Aspose.Pdf.Document relié avec une façade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | Renvoie la taille de la zone spécifiée dans le document. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | Renvoie la rotation de la page spécifiée. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | Renvoie le nombre total de pages. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | Renvoie la taille de page de la page spécifiée. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | Déplace l'origine de (0, 0) au point désigné. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | Enregistre le document modifié dans le flux. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | Enregistre le document modifié dans un fichier. |

## Des champs

| Nom | La description |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | Stores verticaux |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | Stores verticaux |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | Essuyage de bas en haut |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | Paillettes diagonales |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | L'ancienne page se dissout |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | Boîte intérieure |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | Paillettes gauche-droite |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | Balayage gauche-droite |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | Boîte extérieure |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | Balayage droite-gauche |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | Dans la division horizontale |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | Hors division horizontale |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | En division verticale |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | Fractionnement vertical |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | Paillettes de haut en bas |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | Essuyage haut-bas |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
