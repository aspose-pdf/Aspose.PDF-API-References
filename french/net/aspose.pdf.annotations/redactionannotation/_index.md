---
title: Class RedactionAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.RedactionAnnotation. Représente l'annotation de rédaction
type: docs
weight: 2400
url: /fr/net/aspose.pdf.annotations/redactionannotation/
---
## Classe RedactionAnnotation

Représente l'annotation de rédaction.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | Constructeur pour RedactionAnnotation. À utiliser dans le générateur. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | Constructeur pour RedactAnnotation. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de la bordure de l'annotation. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | Obtient ou définit la couleur de la bordure qui est dessinée lorsque la rédaction n'est pas active. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtient la date et l'heure de création de l'annotation. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | Obtient ou définit la chaîne d'apparence par défaut à utiliser pour le formatage du texte. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | Obtient ou définit la couleur de remplissage de l'annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Drapeaux de l'annotation. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | Obtient ou définit la taille de police pour OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtient le nom complet qualifié de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien de fragment (pour le générateur PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Une référence à l'annotation à laquelle cette annotation est "en réponse". Les deux annotations doivent être sur la même page du document. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité constante à utiliser pour peindre l'annotation. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | Obtient ou définit le texte à imprimer sur l'annotation de rédaction. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotation contextuelle pour entrer ou modifier le texte associé à cette annotation. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | Un tableau de nombres 8xN spécifiant les coordonnées de la région de contenu qui doit être supprimée. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtient ou définit le rectangle de l'annotation. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | Si vrai, le texte superposé sera répété sur l'annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Une chaîne spécifiant la relation (le "type de réponse") entre cette annotation et une spécifiée par InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtient le texte représentant la description de l'objet. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | Obtient ou définit l'alignement du texte superposé. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtient ou définit un texte qui doit être affiché dans la barre de titre de l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | Accepte l'objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Met à jour les paramètres et l'apparence, selon la transformation de matrice. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Efface l'état et le modèle d'état pour l'annotation. Par exemple, efface le statut de révision pour une annotation. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | Aplati l'annotation, c'est-à-dire supprime l'annotation et ajoute son |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtient l'état de l'annotation. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtient le modèle d'état de l'annotation. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | Aplati l'annotation et rédige le contenu de la page (c'est-à-dire supprime le texte et l'image sous l'annotation de rédaction) |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Définit l'état marqué et non marqué pour l'annotation. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Définit l'état de révision pour une annotation. Les états marqués et non marqués sont ignorés car ils n'appartiennent pas au modèle d'état de révision. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est tirée de la propriété Title de l'annotation cible. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Définit l'état de révision pour une annotation. Les états marqués et non marqués sont ignorés car ils n'appartiennent pas au modèle d'état de révision. Notez que l'état est stocké dans une autre annotation de texte qui a des clés d'état et de modèle d'état. |

### Voir aussi

* classe [MarkupAnnotation](../markupannotation/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)