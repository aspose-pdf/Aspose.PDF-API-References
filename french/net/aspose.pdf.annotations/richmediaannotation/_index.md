---
title: RichMediaAnnotation
second_title: Référence de l'API Aspose.PDF pour .NET
description: La classe décrit RichMediaAnnotation qui permet dintégrer des données vidéo/audio dans un document PDF.
type: docs
weight: 1030
url: /fr/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

La classe décrit RichMediaAnnotation qui permet d'intégrer des données vidéo/audio dans un document PDF.

```csharp
public class RichMediaAnnotation : Annotation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation)(Page, Rectangle) | Initialise RichMediaAnnotation. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtient la liste des actions d'annotation. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon) { get; set; } | Evénement qui active l'application. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtient ou définit les caractéristiques de bordure d'annotation.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtient les caractéristiques d'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content) { get; } | Données du contenu Rich Media. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtient ou définit le texte d'annotation. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables) { get; set; } | Définit ou récupère les variables flash transmises au joueur. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer) { get; set; } | Définit ou obtient un lecteur flash personnalisé pour lire les données vidéo/audio. |
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
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtient l'index de la page qui contient l'annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Récupère ou définit le rectangle d'annotation. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type) { get; set; } | Obtient ou définit le type de contenu. Valeurs possibles : Audio, Vidéo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept)(AnnotationSelector) | Accepte le visiteur pour cette annotation. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata)(string, Stream) | Ajouter des données nommées personnalisées (par exemple requises pour le script flash). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Mettre à jour les paramètres et l'apparence, selon la transformation matricielle. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Renvoie le rectangle d'annotation en tenant compte de la rotation de la page. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent)(string, Stream) | Définir le flux de contenu. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter)(Stream) | Définir l'affiche de l'annotation. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update)() | Met à jour les données avec les paramètres spécifiés. |

## Autres membres

| Nom | La description |
| --- | --- |
| enum [ActivationEvent](richmediaannotation.activationevent) | Evénement qui active l'annotation. |
| enum [ContentType](richmediaannotation.contenttype) | Type de multimédia. |

### Voir également

* class [Annotation](../annotation)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
