---
title: PDF3DAnnotation
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe PDF3DAnnotation. Cette classe ne peut pas être héritée.
type: docs
weight: 770
url: /fr/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation class

Classe PDF3DAnnotation. Cette classe ne peut pas être héritée.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation#constructor)(Page, Rectangle, PDF3DArtwork) | Initialise une nouvelle instance du[`PDF3DAnnotation`](../pdf3dannotation) classe. |
| [PDF3DAnnotation](pdf3dannotation#constructor_1)(Page, Rectangle, PDF3DArtwork, PDF3DActivation) | Initialise une nouvelle instance du[`PDF3DAnnotation`](../pdf3dannotation) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/pdf3dannotation/annotationtype) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtient ou définit les caractéristiques de bordure d'annotation.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtient les caractéristiques d'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Content](../../aspose.pdf.annotations/pdf3dannotation/content) { get; set; } | Obtient ou définit le contenu. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtient ou définit le texte d'annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtient le nom qualifié complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [LightingScheme](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme) { get; } | Obtient le schéma d'éclairage. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'annotation a été récemment modifiée. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Pdf3DArtwork](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork) { get; } | Obtient l'illustration 3D. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Récupère ou définit le rectangle d'annotation. |
| [RenderMode](../../aspose.pdf.annotations/pdf3dannotation/rendermode) { get; } | Obtient le mode de rendu. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ViewArray](../../aspose.pdf.annotations/pdf3dannotation/viewarray) { get; } | Obtient le tableau de vue. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pdf3dannotation/accept)(AnnotationSelector) | Accepte le visiteur pour le traitement des annotations. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Mettre à jour les paramètres et l'apparence, selon la transformation matricielle. |
| [ClearImagePreview](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview)() | Efface l'aperçu de l'image. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview)() | Obtient l'aperçu de l'image. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Renvoie le rectangle d'annotation en tenant compte de la rotation de la page. |
| [SetDefaultViewIndex](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex)(int) | Définit l'index de la vue par défaut. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview)(Stream) | Définit l'aperçu de l'image. |
| [SetImagePreview](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview#setimagepreview_1)(string) | Définit l'aperçu de l'image. |

### Voir également

* class [Annotation](../annotation)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
