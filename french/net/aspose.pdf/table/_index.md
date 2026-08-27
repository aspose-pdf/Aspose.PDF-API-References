---
title: "Classe Table"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Table. Représente un tableau qui peut être ajouté à la page"
type: docs
weight: 10460
url: /fr/net/aspose.pdf/table/
---
## Table class

Représente un tableau qui peut être ajouté à la page.

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
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Obtient ou définit l'alignement du tableau. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Obtient ou définit la couleur d'arrière-plan du tableau |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Obtient ou définit la bordure. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Obtient ou définit le texte de rupture pour le tableau |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Obtient ou définit la rupture verticale du tableau; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Obtient ou définit l'ajustement des colonnes du tableau. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Obtient les largeurs des colonnes du tableau. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Obtient ou définit les styles des coins de la bordure |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Obtient la bordure de cellule par défaut ; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Obtient ou définit le remplissage de cellule par défaut. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Obtient ou définit l’état de texte par défaut de la cellule. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Obtient la bordure de cellule par défaut ; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Obtient ou définit la bordure incluse dans les largeurs de colonne. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Obtient ou définit si le tableau est rompu - sera tronqué pour la page suivante. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Obtient ou définit la coordonnée gauche du tableau. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Obtient ou définit le nombre maximal de colonnes pour le tableau |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Obtient le nombre de premières lignes répété sur plusieurs pages |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Obtient le style des lignes répétées |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Obtient les lignes du tableau. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Obtient ou définit la coordonnée supérieure du tableau. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Clone le tableau. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Obtenir la hauteur. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Obtenir la largeur. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Importe un tableau unidimensionnel de données dans le tableau. L'importation place une cellule pour chaque élément du tableau et commence à la ligne et à la colonne définies dans les paramètres. Pendant l'importation, si l'on détecte que les lignes nécessaires sont encore absentes (c.-à-d. que le tableau cible est trop petit pour absorber toutes les données), les lignes nécessaires seront créées |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Importe des données de System.Data.DataTable dans Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Importe un objet DataTable dans le tableau. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Importe un objet DataTable, mais pas en tant qu'entité complète. Seules les lignes et colonnes spécifiées sont importées. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Importe les données d'un objet DataView dans le tableau. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Définir la hauteur. |

### Voir aussi

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


