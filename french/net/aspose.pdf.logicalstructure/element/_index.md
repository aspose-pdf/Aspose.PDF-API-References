---
title: "Classe Element"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.LogicalStructure.Element. Représente une classe de base pour les éléments dans la structure logique"
type: docs
weight: 6460
url: /fr/net/aspose.pdf.logicalstructure/element/
---
## Element class

Représente une classe de base pour les éléments dans la structure logique.

```csharp
public abstract class Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d’enfants d’objets Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtenir l’élément parent. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute l’Element à la collection d’enfants. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve les Elements d’un type donné |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère l’Element dans la collection d’enfants à l’index spécifié. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprimer l’enfant à. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Lie un élément de structure à l’Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Lie un élément de structure à l’Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Lie un élément de structure à l’opérateur BDC du flux de contenu. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Lie un élément de structure au XForm du flux de contenu. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Lie un élément de structure au XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Renvoie une chaîne qui représente l’objet actuel. |

### Voir aussi

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


