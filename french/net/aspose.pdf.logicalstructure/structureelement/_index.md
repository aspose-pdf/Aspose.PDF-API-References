---
title: "Classe StructureElement"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.LogicalStructure.StructureElement class. Représente une classe de base pour les éléments de structure dans la structure logique."
type: docs
weight: 6840
url: /fr/net/aspose.pdf.logicalstructure/structureelement/
---
## StructureElement class

Représente une classe de base pour les éléments de structure dans la structure logique.

```csharp
public abstract class StructureElement : Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtient ou définit le texte réel pour l’élément de structure. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtient ou définit le texte alternatif pour l’élément de structure. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtient l’objet StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d’enfants d’objets Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtient l’objet AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtient ou définit le texte d’expansion pour l’élément de structure. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtient l’ID de l’élément de structure. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtient ou définit la langue de l’élément de structure. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtient la page sur laquelle certains ou tous les éléments enfants seront rendus. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtenir l’élément parent. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtient le type de l’élément de structure. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtient ou définit le titre de l’élément de structure. |

## Méthodes

| Nom | Description |
| --- | --- |
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
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_2)(Annotation) | Lie un élément de structure à l’Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag)(Artifact) | Lie un élément de structure à l’Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_1)(BDC) | Lie un élément de structure à l’opérateur BDC du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_3)(XForm) | Lie un élément de structure au XForm du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_4)(XImage) | Lie un élément de structure au XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Renvoie une chaîne qui représente l’objet actuel. |

### Voir aussi

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


