---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.TableTRElement. Représente l'élément de structure TR dans la structure logique du tableau
type: docs
weight: 6850
url: /fr/net/aspose.pdf.logicalstructure/tabletrelement/
---
## Classe TableTRElement

Représente l'élément de structure TR dans la structure logique du tableau.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtient ou définit le texte réel pour l'élément de structure. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtient ou définit le texte alternatif pour l'élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtient l'objet StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Obtient ou définit la couleur de fond de la ligne. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Obtient ou définit la bordure de la ligne. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d'enfants des objets Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtient l'objet AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Obtient la bordure de cellule par défaut. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Obtient ou définit la marge par défaut pour les cellules de ligne. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Obtient ou définit l'état de texte par défaut pour les cellules de ligne |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtient ou définit le texte d'expansion pour l'élément de structure. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Obtient la hauteur de ligne fixe - la ligne peut avoir une hauteur fixe. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtient l'ID pour l'élément de structure. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Obtient si la ligne fixe est dans une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante. Par défaut, faux. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Obtient si la ligne peut être rompue entre deux pages. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtient ou définit la langue pour l'élément de structure. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Obtient la hauteur de la ligne. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtient l'élément parent. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtient le type de l'élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtient ou définit le titre pour l'élément de structure. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Obtient ou définit l'alignement vertical. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute un élément à la collection d'enfants. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Change l'élément parent pour l'élément de structure actuel |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Efface l'ID pour l'élément de structure. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Crée un [`TableTHElement`](../tablethelement/) et l'ajoute au tableau actuel. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Crée un [`TableTHElement`](../tablethelement/) et l'ajoute au tableau actuel. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve des éléments d'un type donné |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Génère un ID pour l'élément de structure. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère un élément dans la collection d'enfants à l'index spécifié. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Supprime : un élément de la structure, une référence à celui-ci de l'objet parent, des références à celui-ci des objets enfants, l'objet correspondant du document. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Supprime un élément de la structure, une référence à celui-ci de l'objet parent, des références à celui-ci des objets enfants, et l'objet correspondant du document. Insère les objets enfants de l'objet supprimé dans la collection d'enfants de son ancien parent en commençant à l'index de l'objet supprimé. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprime l'enfant à. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Définit l'ID pour l'élément de structure. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Définit une balise personnalisée pour l'élément de structure. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Lie un élément de structure à l'annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Lie un élément de structure à l'artefact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Lie un élément de structure à l'opérateur BDC du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Lie un élément de structure au XForm du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Lie un élément de structure à l'image X. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir aussi

* classe [TableChildElement](../tablechildelement/)
* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)