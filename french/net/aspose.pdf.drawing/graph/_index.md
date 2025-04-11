---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Drawing.Graph. Représente un paragraphe générateur de graphiques.
type: docs
weight: 3940
url: /fr/net/aspose.pdf.drawing/graph/
---
## Classe Graph

Représente un paragraphe générateur de graphiques.

```csharp
public sealed class Graph : BaseParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Initialise une nouvelle instance de la classe `Graph`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Obtient ou définit la bordure. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Obtient ou définit un objet [`GraphInfo`](./graphinfo/) qui indique les informations sur le graphique, telles que la couleur, la largeur de ligne, etc. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Obtient ou définit une valeur flottante qui indique la hauteur du graphique. L'unité est le point. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien du fragment (pour le générateur de PDF). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Obtient ou définit le changement de position actuelle après le traitement du paragraphe. (par défaut vrai) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération de PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération de PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération de PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération de PDF) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Obtient ou définit la coordonnée gauche du tableau. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de PDF). |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Obtient ou définit une collection [`Shapes`](./shapes/) qui indique toutes les formes dans le graphique. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Obtient ou définit une valeur de chaîne qui indique le titre du graphique. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Obtient ou définit la coordonnée supérieure du tableau. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Obtient ou définit une valeur flottante qui indique la largeur du graphique. L'unité est le point. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte sur la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Clone le graphique. |

### Voir aussi

* classe [BaseParagraph](../../aspose.pdf/baseparagraph/)
* espace de noms [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)