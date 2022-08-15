---
title: CircleAnnotation
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe représentant lannotation Cercle.
type: docs
weight: 250
url: /fr/net/aspose.pdf.annotations/circleannotation/
---
## CircleAnnotation class

Classe représentant l'annotation Cercle.

```csharp
public sealed class CircleAnnotation : CommonFigureAnnotation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [CircleAnnotation](circleannotation#constructor)(Document) | Constructeur pour l'annotation Circle. |
| [CircleAnnotation](circleannotation#constructor_1)(Page, Rectangle) | Crée une nouvelle annotation Cercle sur la page spécifiée. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/circleannotation/annotationtype) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtient ou définit les caractéristiques de bordure d'annotation.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtient les caractéristiques d'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtient ou définit le texte d'annotation. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Obtient la date et l'heure de création de l'annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Drapeaux de l'annotation. |
| [Frame](../../aspose.pdf.annotations/commonfigureannotation/frame) { get; set; } | Le rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et les limites réelles du carré ou du cercle sous-jacent. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtient le nom qualifié complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | Une référence à l'annotation à laquelle cette annotation est "en réponse". Les deux annotations doivent se trouver sur la même page du document. |
| [InteriorColor](../../aspose.pdf.annotations/commonfigureannotation/interiorcolor) { get; set; } | Couleur intérieure avec laquelle remplir le rectangle ou l'ellipse de l'annotation. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'annotation a été récemment modifiée. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Obtient ou définit la valeur d'opacité constante à utiliser pour peindre l'annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Annotation contextuelle permettant de saisir ou de modifier le texte associé à cette annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Récupère ou définit le rectangle d'annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | Une chaîne spécifiant la relation (le "type de réponse") entre cette annotation et celle spécifiée par InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Obtient le texte représentant la description de l'objet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Obtient ou définit un texte qui doit être affiché dans la barre de titre de l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/circleannotation/accept)(AnnotationSelector) | Accepte l'objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Mettre à jour les paramètres et l'apparence, selon la transformation matricielle. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Renvoie le rectangle d'annotation en tenant compte de la rotation de la page. |

### Voir également

* class [CommonFigureAnnotation](../commonfigureannotation)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
