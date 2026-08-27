---
title: "Classe FreeTextAnnotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Annotations.FreeTextAnnotation class. Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé ; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible."
type: docs
weight: 1900
url: /fr/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé ; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Constructeur à utiliser avec Generator. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Crée une nouvelle annotation FreeText sur la page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Obtient le type de l'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de bordure de l'annotation. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Tableau de points spécifiant la ligne d'appel. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Obtient la date et l'heure de création de l'annotation. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Obtient ou définit la chaîne d'apparence par défaut à utiliser lors du formatage du texte. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Objet qui représente l'apparence par défaut de l'annotation FreeText. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Obtient ou définit une chaîne de style par défaut. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Obtient ou définit le style de terminaison de ligne pour le point de terminaison de ligne. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtient le nom complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Une référence à l'annotation à laquelle cette annotation répond. Les deux annotations doivent se trouver sur la même page du document. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Obtient ou définit l'intention de l'annotation de texte libre. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Obtient ou définit un code spécifiant la forme d'alignement (justification) à utiliser lors de l'affichage du texte de l'annotation. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité constante à utiliser lors du rendu de l'annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Annotation contextuelle pour saisir ou modifier le texte associé à cette annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtient ou définit le rectangle de l'annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Une chaîne spécifiant la relation (le "type de réponse") entre cette annotation et celle spécifiée par InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Angle de rotation de l'annotation. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Obtient ou définit le style de terminaison de ligne pour le point de terminaison de ligne. Cette propriété est obsolète, veuillez utiliser EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Obtient le texte représentant la description de l'objet. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et un rectangle contenu dans ce rectangle. Le rectangle interne est l'endroit où le texte de l'annotation doit être affiché. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Obtient ou définit le style du texte dans l'apparence. Lorsque le style du texte est modifié, l'apparence du texte est mise à jour. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Obtient ou définit une étiquette de texte qui doit être affichée dans la barre de titre de la fenêtre contextuelle de l'annotation lorsqu'elle est ouverte et active. Cette entrée doit identifier l'utilisateur qui a ajouté l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Accepte un objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Met à jour les paramètres et l'apparence, selon la transformation Matrix. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Efface l'état et le modèle d'état de l'annotation. Par exemple, efface le statut de révision d'une annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Retourne toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Obtient l'état de l'annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Obtient le modèle d'état de l'annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Définit l'état Marqué et Non Marqué pour l'annotation. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Définit l'état de révision pour une annotation. Les états Marqué et Non Marqué sont ignorés car ils n'appartiennent pas au Review StateModel. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est prise à partir de la propriété Title de l'annotation cible. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Définit l'état de révision pour une annotation. Les états Marqué et Non Marqué sont ignorés car ils n'appartiennent pas au Review StateModel. Remarque, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle_1)(int, int, RichTextFontStyles) | Définit le formatage déterminé par le paramètre textStyle pour un fragment de texte de l'index fromInd à l'index toInd. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle)(RichTextFontStyles, string, double, Color) | Définit le formatage déterminé par le paramètre textStyle pour tout le texte de l'annotation. |

### Voir aussi

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


