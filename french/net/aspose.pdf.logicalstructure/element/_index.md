---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.Element. Représente une classe de base pour un élément dans la structure logique
type: docs
weight: 6320
url: /fr/net/aspose.pdf.logicalstructure/element/
---
## Classe Élément

Représente une classe de base pour un élément dans la structure logique.

```csharp
public abstract class Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d'enfants des objets Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtient l'élément parent. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute un Element à la collection d'enfants. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve des éléments d'un type donné |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère un Element dans la collection d'enfants à l'index spécifié. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprime l'enfant à. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Lier un élément de structure à l'Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Lier un élément de structure à l'Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Lier un élément de structure à l'opérateur BDC du flux de contenu. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Lier un élément de structure au XForm du flux de contenu. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Lier un élément de structure à l'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir aussi

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)