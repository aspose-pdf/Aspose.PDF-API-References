---
title: RedactionAnnotation
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente lannotation expurgée.
type: docs
weight: 960
url: /fr/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

Représente l'annotation expurgée.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [RedactionAnnotation](redactionannotation#constructor)(Document) | Constructeur pour RedactionAnnotation. Pour une utilisation dans le générateur. |
| [RedactionAnnotation](redactionannotation#constructor_1)(Page, Rectangle) | Constructeur pour RedactAnnotation. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtient ou définit les caractéristiques de bordure d'annotation.[`Border`](../annotation/border) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor) { get; set; } | Obtient ou définit la couleur de la bordure qui est dessinée lorsque la rédaction n'est pas active. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtient les caractéristiques d'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtient ou définit le texte d'annotation. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Obtient la date et l'heure de création de l'annotation. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance) { get; set; } | Obtient ou définit la chaîne d'apparence par défaut à utiliser pour formater le texte. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor) { get; set; } | Obtient ou définit la couleur pour remplir l'annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtient le nom qualifié complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Une référence à l'annotation à laquelle cette annotation est "en réponse". Les deux annotations doivent se trouver sur la même page du document. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'annotation a été récemment modifiée. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Obtient ou définit la valeur d'opacité constante à utiliser pour peindre l'annotation. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext) { get; set; } | Texte à imprimer sur l'annotation expurgée. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Annotation contextuelle permettant de saisir ou de modifier le texte associé à cette annotation. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint) { get; set; } | Un tableau de nombres 8xN spécifiant les coordonnées de la région de contenu qui doit être supprimée. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Récupère ou définit le rectangle d'annotation. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat) { get; set; } | Si vrai, le texte superposé sera répété sur l'annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Une chaîne spécifiant la relation (le "type de réponse") entre cette annotation et celle spécifiée par InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Obtient le texte représentant la description de l'objet. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment) { get; set; } | Obtient ou définit. Alignement du texte superposé. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Obtient ou définit un texte qui doit être affiché dans la barre de titre de l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept)(AnnotationSelector) | Accepte l'objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Mettre à jour les paramètres et l'apparence, selon la transformation matricielle. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten)() | Aplatit l'annotation, c'est-à-dire supprime l'annotation et ajoute its |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Renvoie le rectangle d'annotation en tenant compte de la rotation de la page. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact)() | Aplatit l'annotation et masque le contenu de la page (c'est-à-dire supprime le texte et l'image sous l'annotation masquée) |

### Voir également

* class [MarkupAnnotation](../markupannotation)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
