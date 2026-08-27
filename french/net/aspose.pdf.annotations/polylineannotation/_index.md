---
title: "Classe PolylineAnnotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Annotations.PolylineAnnotation classe. Représente une Annotation polyline qui est similaire à un polygone sauf que le premier et le dernier sommet ne sont pas implicitement connectés"
type: docs
weight: 2410
url: /fr/net/aspose.pdf.annotations/polylineannotation/
---
## PolylineAnnotation class

Représente l'annotation polyline qui est similaire à un polygone, sauf que le premier et le dernier sommet ne sont pas implicitement connectés.

```csharp
public sealed class PolylineAnnotation : PolyAnnotation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PolylineAnnotation](polylineannotation/)(Page, Rectangle, Point[]) | Crée une nouvelle Annotation Polyline sur la Page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/polylineannotation/annotationtype/) { get; } | Obtient le type de l'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de bordure de l'annotation. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Obtient la date et l'heure de création de l'annotation. |
| [EndingStyle](../../aspose.pdf.annotations/polyannotation/endingstyle/) { get; set; } | Obtient ou définit le style de la terminaison de la deuxième ligne. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtient le nom complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Une référence à l'annotation à laquelle cette annotation répond. Les deux annotations doivent se trouver sur la même page du document. |
| [Intent](../../aspose.pdf.annotations/polyannotation/intent/) { get; set; } | Obtient ou définit l'intention de l'annotation de polygone ou de polyligne. |
| [InteriorColor](../../aspose.pdf.annotations/polyannotation/interiorcolor/) { get; set; } | Obtient ou définit la couleur intérieure avec laquelle remplir les terminaisons de ligne de l'annotation. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Measure](../../aspose.pdf.annotations/polyannotation/measure/) { get; set; } | Unités de mesure spécifiées pour cette annotation. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité constante à utiliser lors du rendu de l'annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotation contextuelle pour saisir ou modifier le texte associé à cette annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtient ou définit le rectangle de l'annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Une chaîne spécifiant la relation (le "type de réponse") entre cette annotation et celle spécifiée par InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| [StartingStyle](../../aspose.pdf.annotations/polyannotation/startingstyle/) { get; set; } | Obtient ou définit le style de la terminaison de la première ligne. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtient le texte représentant la description de l'objet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtient ou définit une étiquette de texte qui doit être affichée dans la barre de titre de la fenêtre contextuelle de l'annotation lorsqu'elle est ouverte et active. Cette entrée doit identifier l'utilisateur qui a ajouté l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [Vertices](../../aspose.pdf.annotations/polyannotation/vertices/) { get; set; } | Obtient ou définit un tableau de points représentant les coordonnées horizontales et verticales de chaque sommet. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/polylineannotation/accept/)(AnnotationSelector) | Accepte un objet visiteur pour traiter l'annotation. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/polyannotation/changeafterresize/)(Matrix) | Met à jour les points dans Vertices, selon la transformation matricielle. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Efface l'état et le modèle d'état de l'annotation. Par exemple, efface le statut de révision d'une annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Retourne toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtient l'état de l'annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtient le modèle d'état de l'annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Définit l'état Marqué et Non Marqué pour l'annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Définit l'état de révision pour une annotation. Les états Marqué et Non Marqué sont ignorés car ils n'appartiennent pas au Review StateModel. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est prise à partir de la propriété Title de l'annotation cible. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Définit l'état de révision pour une annotation. Les états Marqué et Non Marqué sont ignorés car ils n'appartiennent pas au Review StateModel. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |

### Voir aussi

* class [PolyAnnotation](../polyannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


