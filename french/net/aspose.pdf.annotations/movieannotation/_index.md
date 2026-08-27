---
title: "Classe MovieAnnotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Annotations.MovieAnnotation. Représente une annotation vidéo contenant des graphiques animés et du son à présenter sur l'écran d'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, le film est lu."
type: docs
weight: 2200
url: /fr/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

Représente une annotation vidéo qui contient des graphiques animés et du son à présenter sur l'écran de l'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, la vidéo est lue.

```csharp
public sealed class MovieAnnotation : Annotation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | Constructeur à utiliser avec Generator. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | Crée une nouvelle annotation Son sur la page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | Obtient le type de l'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | Obtient ou définit la largeur et la hauteur de la boîte englobante du film, en pixels. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de bordure de l'annotation. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | Obtient ou définit une spécification de fichier identifiant un fichier vidéo auto-descriptif. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtient le nom complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Obtient l'index de la page qui contient l'annotation. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | Obtient ou définit un indicateur ou un flux spécifiant si et comment une image d'affiche représentant le film doit être affichée. Si vrai, l'image d'affiche doit être récupérée du fichier vidéo ; si faux, aucune affiche ne doit être affichée. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtient ou définit le rectangle de l'annotation. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | Obtient ou définit le nombre de degrés de rotation du film dans le sens des aiguilles d'une montre par rapport à la page. La valeur doit être un multiple de 90. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | Obtient ou définit le titre de l'Annotation vidéo. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | Accepte un objet visiteur pour traiter l'annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Met à jour les paramètres et l'apparence, selon la transformation Matrix. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Retourne toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |

### Voir aussi

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


