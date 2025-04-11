---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FreeTextAnnotation. Représente une annotation de texte libre qui affiche du texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a pas d'état ouvert ou fermé ; au lieu d'être affiché dans une fenêtre contextuelle, le texte est toujours visible.
type: docs
weight: 1810
url: /fr/net/aspose.pdf.annotations/freetextannotation/
---
## Classe FreeTextAnnotation

Représente une annotation de texte libre qui affiche du texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a pas d'état ouvert ou fermé ; au lieu d'être affiché dans une fenêtre contextuelle, le texte est toujours visible.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Constructeur à utiliser avec le générateur. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Crée une nouvelle annotation de texte libre sur la page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de la bordure de l'annotation. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Tableau de points spécifiant la ligne d'appel. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Obtient la date et l'heure de création de l'annotation. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Obtient ou définit la chaîne d'apparence par défaut à utiliser pour le formatage du texte. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Objet qui représente l'apparence par défaut de l'annotation de texte libre. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Obtient ou définit une chaîne de style par défaut. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Obtient ou définit le style de fin de ligne pour le point de fin de ligne. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtient le nom complet qualifié de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien de fragment (pour le générateur de pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Une référence à l'annotation à laquelle cette annotation est "en réponse". Les deux annotations doivent être sur la même page du document. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Obtient ou définit l'intention de l'annotation de texte libre. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. Par défaut, c'est faux. (pour la génération de pdf) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Obtient ou définit un code spécifiant la forme de quadding (justification) à utiliser pour afficher le texte de l'annotation. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité constante à utiliser pour peindre l'annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotation contextuelle pour entrer ou modifier le texte associé à cette annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtient ou définit le rectangle de l'annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Une chaîne spécifiant la relation (le "type de réponse") entre cette annotation et une spécifiée par InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Angle de rotation de l'annotation. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Obtient ou définit le style de début de ligne pour le point de début de ligne. Cette propriété est obsolète, veuillez utiliser EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtient le texte représentant la description de l'objet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et un rectangle contenu dans ce rectangle. Le rectangle intérieur est l'endroit où le texte de l'annotation doit être affiché. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Obtient ou définit le style du texte dans l'apparence. Lorsque le style de texte est modifié, l'apparence du texte est mise à jour. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtient ou définit un texte qui doit être affiché dans la barre de titre de l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte sur la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Accepte l'objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Met à jour les paramètres et l'apparence, selon la transformation de matrice. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Efface l'état et le modèle d'état de l'annotation. Par exemple, efface le statut de révision d'une annotation. Notez que l'état est stocké dans d'autres annotations de texte qui ont des clés d'état et de modèle d'état. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Place le contenu de l'annotation directement sur la page, l'objet annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtient l'état de l'annotation. Notez que l'état est stocké dans d'autres annotations de texte qui ont des clés d'état et de modèle d'état. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtient le modèle d'état de l'annotation. Notez que l'état est stocké dans d'autres annotations de texte qui ont des clés d'état et de modèle d'état. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Définit l'état marqué et non marqué pour l'annotation. Notez que l'état est stocké dans d'autres annotations de texte qui ont des clés d'état et de modèle d'état. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Définit l'état de révision pour une annotation. Les états marqués et non marqués sont ignorés car ils n'appartiennent pas au modèle d'état de révision. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est prise à partir de la propriété Title de l'annotation cible. Notez que l'état est stocké dans d'autres annotations de texte qui ont des clés d'état et de modèle d'état. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Définit l'état de révision pour une annotation. Les états marqués et non marqués sont ignorés car ils n'appartiennent pas au modèle d'état de révision. Notez que l'état est stocké dans d'autres annotations de texte qui ont des clés d'état et de modèle d'état. |

### Voir aussi

* classe [MarkupAnnotation](../markupannotation/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)