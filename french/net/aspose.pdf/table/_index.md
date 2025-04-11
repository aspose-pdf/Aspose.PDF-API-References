---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Table. Représente une table qui peut être ajoutée à la page
type: docs
weight: 10280
url: /fr/net/aspose.pdf/table/
---
## Classe Table

Représente une table qui peut être ajoutée à la page.

```csharp
public sealed class Table : BaseParagraph
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Table](table/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Obtient ou définit l'alignement de la table. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Obtient ou définit la couleur de fond de la table |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Obtient ou définit la bordure. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Obtient ou définit le texte de rupture pour la table |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Obtient ou définit si la table est verticalement cassée ; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Obtient ou définit l'ajustement des colonnes de la table. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Obtient les largeurs des colonnes de la table. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Obtient ou définit les styles des coins de la bordure |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Obtient la bordure par défaut des cellules ; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Obtient ou définit le remplissage par défaut des cellules. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Obtient ou définit l'état de texte par défaut des cellules. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Obtient la bordure par défaut des cellules ; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien du fragment (pour le générateur de pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Obtient ou définit si la bordure est incluse dans les largeurs de colonne. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Obtient ou définit si la table est cassée - sera tronquée pour la page suivante. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération de pdf) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Obtient ou définit la coordonnée gauche de la table. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Obtient ou définit le nombre maximum de colonnes pour la table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Obtient le nombre de premières lignes répétées sur plusieurs pages |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Obtient le style pour les lignes répétées |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Obtient les lignes de la table. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Obtient ou définit la coordonnée supérieure de la table. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Clone la table. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Obtient la hauteur. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Obtient la largeur. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importe un tableau unidimensionnel de données dans la table. L'importation se fait une cellule par élément du tableau et commence à partir de la ligne et de la colonne définies dans les paramètres. Pendant l'importation, si des lignes nécessaires sont encore absentes (c'est-à-dire que la table cible est trop petite pour absorber toutes les données), les lignes nécessaires seront créées |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importe des données de System.Data.DataTable dans Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importe un objet DataTable dans la table. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importe un objet DataTable, mais pas en tant qu'entité entière. Seules les lignes et colonnes spécifiées sont importées. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importe les données d'un objet DataView dans la table. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Définit la hauteur. |

### Voir aussi

* classe [BaseParagraph](../baseparagraph/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)