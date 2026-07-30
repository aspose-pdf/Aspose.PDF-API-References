---
title: "Classe TableTHElement"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.LogicalStructure.TableTHElement classe. Représente l'élément de structure TH dans la structure logique du tableau."
type: docs
weight: 6970
url: /fr/net/aspose.pdf.logicalstructure/tablethelement/
---
## TableTHElement class

Représente l'élément de structure TH dans la structure logique du tableau.

```csharp
public sealed class TableTHElement : TableCellElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtient ou définit le texte réel pour l’élément de structure. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Obtient ou définit l’alignement de la cellule. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtient ou définit le texte alternatif pour l’élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtient l’objet StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Obtient ou définit la couleur d’arrière‑plan de la cellule. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Obtient ou définit la bordure de la cellule. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d’enfants d’objets Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Obtient ou définit l’étendue de la colonne. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtient l’objet AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Obtient ou définit l’état de texte par défaut de la cellule. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtient ou définit le texte d’expansion pour l’élément de structure. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtient l’ID de l’élément de structure. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Obtient ou définit si la cellule possède une bordure. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Obtient ou définit le texte de la cellule avec retour à la ligne. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtient ou définit la langue de l’élément de structure. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Obtient ou définit le remplissage. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtenir l’élément parent. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Obtient ou définit la fusion de lignes. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Obtient l’objet StructureTextState pour l’élément actuel. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtient le type de l’élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtient ou définit le titre de l’élément de structure. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute l’Element à la collection d’enfants. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Modifie l’élément parent pour l’élément de structure actuel |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Efface l’ID de l’élément de structure. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve les Elements d’un type donné |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Génère l’ID pour l’élément de structure. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère l’Element dans la collection d’enfants à l’index spécifié. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Supprime : un élément de la structure, une référence à celui‑ci depuis l’objet parent, les références depuis les objets enfants, l’objet correspondant du document. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Supprime un élément de la structure, une référence à celui‑ci depuis l’objet parent, les références depuis les objets enfants, ainsi que l’objet correspondant du document. Insère les objets enfants de l’objet supprimé dans la collection d’objets enfants de son ancien parent à partir de l’index de l’objet supprimé. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprimer l’enfant à. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Définit l’ID pour l’élément de structure. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Définit la balise personnalisée pour l’élément de structure. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Lie un élément de structure à l’Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Lie un élément de structure à l’Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Lie un élément de structure à l’opérateur BDC du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Lie un élément de structure au XForm du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Lie un élément de structure au XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Renvoie une chaîne qui représente l’objet actuel. |

### Voir aussi

* class [TableCellElement](../tablecellelement/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


