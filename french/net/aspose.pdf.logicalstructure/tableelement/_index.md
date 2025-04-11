---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableElement. Représente l'élément de structure de table dans la structure logique
type: docs
weight: 6780
url: /fr/net/aspose.pdf.logicalstructure/tableelement/
---
## Classe TableElement

Représente l'élément de structure de table dans la structure logique.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtient ou définit le texte réel pour l'élément de structure. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Obtient ou définit l'alignement de la table. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtient ou définit le texte alternatif pour l'élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtient l'objet StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Obtient ou définit la couleur de fond de la table. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Obtient ou définit la bordure de la table. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Obtient ou définit si la table est verticalement cassée; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d'enfants d'objets Element. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Obtient ou définit l'ajustement des colonnes de la table. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Obtient les largeurs des colonnes de la table. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Obtient ou définit les styles des coins de la bordure |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtient l'objet AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Obtient la bordure de cellule par défaut. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Obtient ou définit le remplissage de cellule par défaut. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Obtient ou définit l'état de texte de cellule par défaut. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Obtient ou définit la largeur de colonne par défaut. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtient ou définit le texte d'expansion pour l'élément de structure. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtient l'ID pour l'élément de structure. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Obtient ou définit si la bordure est incluse dans les largeurs de colonne. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Obtient ou définit si la table est cassée - sera tronquée pour la page suivante. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtient ou définit la langue pour l'élément de structure. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Obtient ou définit la coordonnée gauche de la table. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtient l'élément parent. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Obtient ou définit le nombre maximum de colonnes pour la table. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Obtient le nombre de premières lignes répétées sur plusieurs pages. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Obtient le style pour les lignes répétées. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtient le type d'élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtient ou définit le titre pour l'élément de structure. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Obtient ou définit la coordonnée supérieure de la table. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute un élément à la collection d'enfants. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Change l'élément parent pour l'élément de structure actuel |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Efface l'ID pour l'élément de structure. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Crée [`TableTHeadElement`](../tabletheadelement/) et l'ajoute à la table actuelle. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Crée [`TableTFootElement`](../tabletfootelement/) et l'ajoute à la table actuelle. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Crée [`TableTHeadElement`](../tabletheadelement/) et l'ajoute à la table actuelle. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve des éléments d'un type donné |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Génère un ID pour l'élément de structure. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère un élément dans la collection d'enfants à l'index spécifié. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Supprime : un élément de la structure, une référence à celui-ci de l'objet parent, des références à celui-ci des objets enfants, l'objet correspondant du document. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Supprime un élément de la structure, une référence à celui-ci de l'objet parent, des références à celui-ci des objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'objet supprimé dans la collection d'objets enfants de son ancien parent en commençant à l'index de l'objet supprimé. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprime l'enfant à. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Définit l'ID pour l'élément de structure. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Définit une balise personnalisée pour l'élément de structure. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Lien d'un élément de structure à l'annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Lien d'un élément de structure à l'artefact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Lien d'un élément de structure à l'opérateur BDC du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Lien d'un élément de structure au XForm du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Lien d'un élément de structure à l'image X. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir aussi

* classe [BLSElement](../blselement/)
* interface [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)