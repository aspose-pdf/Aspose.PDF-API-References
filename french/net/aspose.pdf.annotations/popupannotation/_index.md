---
title: PopupAnnotation
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente lannotation contextuelle qui affiche le texte dans une fenêtre contextuelle pour la saisie et la modification.
type: docs
weight: 940
url: /fr/net/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class

Représente l'annotation contextuelle qui affiche le texte dans une fenêtre contextuelle pour la saisie et la modification.

```csharp
public sealed class PopupAnnotation : Annotation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PopupAnnotation](popupannotation#constructor)(Document) | Constructeur. à utiliser dans le générateur. |
| [PopupAnnotation](popupannotation#constructor_1)(Page, Rectangle) | Crée une nouvelle annotation Popup sur la page spécifiée. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/popupannotation/annotationtype) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtient ou définit les caractéristiques de bordure d'annotation.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtient les caractéristiques d'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtient ou définit le texte d'annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtient le nom qualifié complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'annotation a été récemment modifiée. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Open](../../aspose.pdf.annotations/popupannotation/open) { get; set; } | Obtient ou définit un indicateur spécifiant si l'annotation contextuelle doit initialement être affichée ouverte. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Parent](../../aspose.pdf.annotations/popupannotation/parent) { get; set; } | Obtient ou définit l'annotation parente à laquelle cette annotation contextuelle doit être associée. Si cette entrée est présente, les entrées Contenu, M, C et T de l'annotation parente doivent remplacer celles de l'annotation contextuelle elle-même. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Récupère ou définit le rectangle d'annotation. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/popupannotation/accept)(AnnotationSelector) | Accepte l'objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Mettre à jour les paramètres et l'apparence, selon la transformation matricielle. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Renvoie le rectangle d'annotation en tenant compte de la rotation de la page. |

### Voir également

* class [Annotation](../annotation)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
