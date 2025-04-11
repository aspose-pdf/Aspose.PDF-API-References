---
title: Class OBJRElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LogicalStructure.OBJRElement. Représente une entité de référence d'objet dans la structure logique
type: docs
weight: 6530
url: /fr/net/aspose.pdf.logicalstructure/objrelement/
---
## Classe OBJRElement

Représente une entité de référence d'objet dans la structure logique.

```csharp
public sealed class OBJRElement : Element
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtient la collection d'enfants d'objets Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtient l'élément parent. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Ajoute un Element à la collection d'enfants. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Efface tous les enfants. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Trouve des éléments d'un type donné |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Insère un Element dans la collection d'enfants à l'index spécifié. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Supprime l'enfant à. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_2)(Annotation) | Lier un élément de structure à l'Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag)(Artifact) | Lier un élément de structure à l'Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_1)(BDC) | Lier un élément de structure à l'opérateur BDC du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_3)(XForm) | Lier un élément de structure au XForm du flux de contenu. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_4)(XImage) | Lier un élément de structure à l'XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/objrelement/tostring/)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir aussi

* classe [Element](../element/)
* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)