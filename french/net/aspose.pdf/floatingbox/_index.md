---
title: FloatingBox
second_title: Référence de l'API Aspose.PDF pour .NET
description: 
type: docs
weight: 2840
url: /fr/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FloatingBox](floatingbox#constructor)() | Initialise une nouvelle instance du[`FloatingBox`](../floatingbox) classe. |
| [FloatingBox](floatingbox#constructor_1)(float, float) | Initialise une nouvelle instance du[`FloatingBox`](../floatingbox) classe avec largeur et hauteur spécifiées. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor) { get; set; } | Obtient ou définit un[`Color`](../color) objet qui indique la couleur de fond de la boîte flottante. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage) { get; set; } | Obtient ou définit l'image d'arrière-plan de la page (pour le générateur uniquement). |
| [Border](../../aspose.pdf/floatingbox/border) { get; set; } | Obtient ou définit un[`BorderInfo`](../borderinfo)objet qui indique les informations de bordure de la boîte flottante. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo) { get; set; } | Obtient ou définit une colonne info |
| [Height](../../aspose.pdf/floatingbox/height) { get; set; } | Obtient ou définit une valeur flottante qui indique la hauteur de la boîte flottante. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante. La valeur par défaut est false.L'attribut n'est valide que lorsque le paragraphe lui-même et l'objet auquel son ReferenceParagraphID fait référence sont inclus dans RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left) { get; set; } | Obtient ou définit la coordonnée gauche de la table. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Padding](../../aspose.pdf/floatingbox/padding) { get; set; } | Obtient ou définit un[`MarginInfo`](../margininfo) objet qui indique le rembourrage de la boîte flottante. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs) { get; set; } | Obtient ou définit un[`Paragraphs`](./paragraphs) collection qui indique tous les paragraphes de la cellule. |
| [Top](../../aspose.pdf/floatingbox/top) { get; set; } | Obtient ou définit la coordonnée du dessus de table. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [Width](../../aspose.pdf/floatingbox/width) { get; set; } | Obtient ou définit une valeur flottante qui indique la largeur de la boîte flottante. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone)() | Clone un nouveau[`FloatingBox`](../floatingbox) objet. Les paragraphes dans la zone flottante ne sont pas clonés. |

### Voir également

* class [BaseParagraph](../baseparagraph)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->