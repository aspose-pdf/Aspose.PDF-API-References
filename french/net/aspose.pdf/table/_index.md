---
title: Table
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un tableau qui peut être ajouté à la page.
type: docs
weight: 6500
url: /fr/net/aspose.pdf/table/
---
## Table class

Représente un tableau qui peut être ajouté à la page.

```csharp
public sealed class Table : BaseParagraph
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Table](table)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Obtient ou définit l'alignement de la table. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan du tableau |
| [Border](../../aspose.pdf/table/border) { get; set; } | Obtient ou définit la bordure. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | Obtient ou définit le texte de rupture pour table |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Obtient ou définit la table verticale brisée ; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Obtient ou définit l'ajustement de colonne de table. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Obtient les largeurs de colonne du tableau. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Obtient ou définit les styles des coins de bordure |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Obtient la bordure de cellule par défaut ; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Obtient ou définit le remplissage de cellule par défaut. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Obtient ou définit l'état du texte de cellule par défaut. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Obtient la bordure de cellule par défaut ; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Obtient ou définit la bordure incluse dans les largeurs de colonne. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Obtient ou définit le tableau est cassé - sera tronqué pour la page suivante. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Obtient ou définit la coordonnée gauche de la table. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | Obtient ou définit le nombre maximal de colonnes pour table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Obtient le nombre de premières lignes répété sur plusieurs pages |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Obtient le style pour répéter les lignes |
| [Rows](../../aspose.pdf/table/rows) { get; } | Obtient les lignes de la table. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Obtient ou définit la coordonnée du dessus de table. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Cloner la table. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Obtenir la hauteur. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Obtenir la largeur. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Importe un tableau unidimensionnel de données dans la table. L'importation va d'une cellule par élément de chaque tableau et commence à partir de la ligne et de la colonne définies dans les paramètres. Lors de l'importation, s'il est détecté que les lignes nécessaires sont toujours absentes (c'est-à-dire que la table cible est trop petite pour absorber toutes les données), les lignes nécessaires seront créées |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | Importe des données de System.Data.DataTable dans Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importe unDataTable objet dans la table. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importe unDataTable objet, mais pas en tant qu'entité entière. Seules les lignes et les colonnes spécifiées sont importées. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | Importe unDataView les données de l'objet dans la table. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Définir la hauteur. |

### Voir également

* class [BaseParagraph](../baseparagraph)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
