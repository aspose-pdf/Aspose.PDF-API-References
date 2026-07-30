---
title: "Classe ColorBarAnnotation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Annotations.ColorBarAnnotation. Classe représentant l’annotation ColorBarAnnotation. La propriété Color est ignorée, à la place la couleur ColorsOfCMYK est utilisée. Lors de la création, le rapport entre la largeur et la hauteur détermine l’orientation de l’annotation, horizontale ou verticale. Ensuite, il vérifie que le rectangle de l’annotation se trouve en dehors du TrimBox et, si ce n’est pas le cas, il le décale vers l’emplacement le plus proche à l’extérieur du TrimBox en tenant compte de l’orientation de l’annotation. Il est possible de réduire la largeur et la hauteur afin que l’annotation tienne en dehors du TrimBox. S’il n’y a pas d’espace pour la mise en page, la largeur/hauteur peut être réglée à zéro ; dans ce cas l’annotation est présente sur la page mais n’est pas affichée."
type: docs
weight: 1690
url: /fr/net/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class

Classe représentant l'annotation ColorBarAnnotation. La propriété Color est ignorée, à la place la couleur ColorsOfCMYK est utilisée. Lors de la création, le rapport entre la largeur et la hauteur détermine l'orientation de l'annotation – horizontale ou verticale. Ensuite, il vérifie que le rectangle de l'annotation se trouve en dehors du TrimBox, et si ce n'est pas le cas, il est déplacé vers l'emplacement le plus proche à l'extérieur du TrimBox, en tenant compte de l'orientation de l'annotation. Il est possible de réduire la largeur (ou la hauteur) afin que l'annotation tienne en dehors du TrimBox. S'il n'y a pas d'espace pour la mise en page, la largeur/hauteur peut être réglée à zéro (dans ce cas, l'annotation est présente sur la page, mais n'est pas affichée).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | Crée une nouvelle annotation ColorBar sur la page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Obtient la liste des actions d'annotation. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | Obtient le type de l'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de bordure de l'annotation. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | Obtient ou définit la couleur (l'une de cyan, magenta, jaune, noir) pour laquelle l'annotation est dessinée. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
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
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Obtient ou définit le rectangle de l'annotation. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | Accepte un objet visiteur pour traiter l'annotation. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | Met à jour les paramètres et l'apparence, selon la transformation de matrice et le déplacement hors du TrimBox si nécessaire. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Retourne toujours null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Place le contenu de l'annotation directement sur la page, l'objet d'annotation sera supprimé. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |

### Voir aussi

* class [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


