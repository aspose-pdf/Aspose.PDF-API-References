---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class.
type: docs
weight: 4870
url: /fr/net/aspose.pdf/floatingbox/
---
## Classe FloatingBox

```csharp
public class FloatingBox : BaseParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Initialise une nouvelle instance de la classe `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Initialise une nouvelle instance de la classe `FloatingBox` avec une largeur et une hauteur spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Obtient ou définit un objet [`Color`](../color/) qui indique la couleur de fond de la boîte flottante. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Obtient ou définit l'image de fond pour la page (pour le générateur uniquement, non remplie lors de la lecture du document). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Obtient ou définit un objet [`BorderInfo`](../borderinfo/) qui indique les informations de bordure de la boîte flottante. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Obtient ou définit des informations sur la colonne |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Obtient ou définit une valeur flottante qui indique la hauteur de la boîte flottante. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante. La valeur par défaut est false. L'attribut n'est valide que lorsque le paragraphe lui-même et l'objet référencé par son ReferenceParagraphID sont tous deux inclus dans RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Obtient ou définit la coordonnée gauche du tableau. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération PDF) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Obtient ou définit un objet [`MarginInfo`](../margininfo/) qui indique le rembourrage de la boîte flottante. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Obtient ou définit une collection [`Paragraphs`](./paragraphs/) qui indique tous les paragraphes dans la cellule. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Spécifie une variante pour déterminer l'emplacement de la FloatingBox sur la page. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Obtient ou définit la coordonnée supérieure du tableau. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Obtient ou définit une valeur flottante qui indique la largeur de la boîte flottante. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte sur la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Clone un nouvel objet `FloatingBox`. Les paragraphes dans la boîte flottante ne sont pas clonés. |

### Voir aussi

* classe [BaseParagraph](../baseparagraph/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)