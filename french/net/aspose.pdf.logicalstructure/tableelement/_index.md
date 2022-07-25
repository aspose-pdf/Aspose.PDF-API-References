---
title: TableElement
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente lélément de structure Table dans la structure logique.
type: docs
weight: 4610
url: /fr/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Représente l'élément de structure Table dans la structure logique.

```csharp
public sealed class TableElement : BLSElement
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Obtient ou définit le texte réel de l'élément de structure. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Obtient ou définit l'alignement de la table. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Obtient ou définit le texte alternatif pour l'élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | ObtientStructureAttributeCollection objet. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan du tableau. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Obtient ou définit la bordure du tableau. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Obtient ou définit la table verticale brisée ; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Obtient la collection enfants deElement objets. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Obtient ou définit l'ajustement de colonne de table. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Obtient les largeurs de colonne du tableau. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Obtient ou définit les styles des coins de bordure |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | ObtientAttributeOwnerStandard objet. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Obtient la bordure de cellule par défaut. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Obtient ou définit le remplissage de cellule par défaut. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Obtient ou définit l'état du texte de cellule par défaut. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Obtient ou définit la largeur de colonne par défaut. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Obtient ou définit le texte d'expansion pour l'élément de structure. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Obtient l'ID de l'élément de structure. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Obtient ou définit la bordure incluse dans les largeurs de colonne. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Obtient ou définit le tableau est cassé - sera tronqué pour la page suivante. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Obtient ou définit la langue de l'élément de structure. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Obtient ou définit la coordonnée gauche de la table. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Obtenir l'élément parent. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Obtient ou définit le nombre maximal de colonnes pour la table. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Obtient le nombre de premières lignes répété sur plusieurs pages. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Obtient le style pour les lignes répétées. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Obtient le type d'élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Obtient ou définit le titre de l'élément de structure. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Obtient ou définit la coordonnée du dessus de table. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | AjouterElement à la collecte des enfants. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Modifier l'élément parent pour l'élément de structure actuel |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Effacer l'ID de l'élément de structure. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | Crée[`TableTHeadElement`](../tabletheadelement) et l'a ajouté à la table actuelle. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | Crée[`TableTFootElement`](../tabletfootelement) et l'a ajouté à la table actuelle. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | Crée[`TableTHeadElement`](../tabletheadelement) et l'a ajouté à la table actuelle. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Rechercher des éléments d'un type donné |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Générer un ID pour l'élément de structure. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Définit l'ID de l'élément de structure. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Définit une balise personnalisée pour l'élément de structure. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir également

* class [BLSElement](../blselement)
* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
