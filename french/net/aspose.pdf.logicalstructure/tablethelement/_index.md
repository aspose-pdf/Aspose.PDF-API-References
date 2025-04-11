---
title: Class TableTHElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableTHElement. Représente l'élément de structure TH dans la structure logique du tableau
type: docs
weight: 6830
url: /fr/net/aspose.pdf.logicalstructure/tablethelement/
---
## Classe TableTHElement

Représente l'élément de structure TH dans la structure logique du tableau.

```csharp
public sealed class TableTHElement : TableCellElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtient ou définit le texte réel pour l'élément de structure. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Obtient ou définit l'alignement de la cellule. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtient ou définit le texte alternatif pour l'élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtient l'objet StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Obtient ou définit la couleur de fond de la cellule. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Obtient ou définit la bordure de la cellule. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d'enfants des objets Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Obtient ou définit l'étendue de la colonne. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtient l'objet AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Obtient ou définit l'état de texte par défaut de la cellule. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtient ou définit le texte d'expansion pour l'élément de structure. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtient l'ID pour l'élément de structure. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Obtient ou définit si la cellule a une bordure. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Obtient ou définit si le texte de la cellule est enroulé. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtient ou définit la langue pour l'élément de structure. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Obtient ou définit le rembourrage. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtient l'élément parent. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Obtient ou définit l'étendue de la ligne. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Obtient l'objet StructureTextState pour l'élément actuel. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtient le type de l'élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtient ou définit le titre pour l'élément de structure. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute un élément à la collection d'enfants. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Change l'élément parent pour l'élément de structure actuel |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Efface l'ID pour l'élément de structure. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve des éléments d'un type donné |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Génère un ID pour l'élément de structure. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère un élément dans la collection d'enfants à l'index spécifié. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Supprime : un élément de la structure, une référence à celui-ci de l'objet parent, des références à celui-ci des objets enfants, l'objet correspondant du document. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Supprime un élément de la structure, une référence à celui-ci de l'objet parent, des références à celui-ci des objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'objet supprimé dans la collection d'objets enfants de son ancien parent en commençant à l'index de l'objet supprimé. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprime l'enfant à. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Définit l'ID pour l'élément de structure. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Définit une balise personnalisée pour l'élément de structure. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Lier un élément de structure à l'annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Lier un élément de structure à l'artefact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Lier un élément de structure à l'opérateur BDC du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Lier un élément de structure au XForm du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Lier un élément de structure à l'image X. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir aussi

* classe [TableCellElement](../tablecellelement/)
* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)