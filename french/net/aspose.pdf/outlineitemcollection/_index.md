---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OutlineItemCollection. Représente une entrée de plan dans la hiérarchie de plan du document PDF
type: docs
weight: 8010
url: /fr/net/aspose.pdf/outlineitemcollection/
---
## Classe OutlineItemCollection

Représente une entrée de plan dans la hiérarchie de plan du document PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Initialise une instance d'élément de plan en utilisant l'objet de hiérarchie racine. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Obtient ou définit l'action pour cet élément de plan. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Obtient ou définit le drapeau gras pour le texte du titre de cet élément de plan |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Obtient ou définit la couleur pour le texte du titre de cet élément de plan. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Nombre d'éléments dans la collection. Ne pas confondre avec VisibleCount : VisibleCount obtient le nombre d'éléments de plan visibles à tous les niveaux. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Obtient ou définit la destination pour cet élément de plan. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Obtient l'élément de plan représentant le premier élément de niveau supérieur dans la hiérarchie de plan. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Vérifie si l'élément de plan représentant l'élément suivant par rapport à cet élément dans la hiérarchie de plan. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Obtient la valeur indiquant si l'accès à cette collection est synchronisé (sécurisé pour les threads). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Obtient ou définit le drapeau italique pour le texte du titre de cet élément de plan |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Obtient l'élément de plan de la collection en utilisant l'index. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Obtient l'élément de plan représentant le dernier élément de niveau supérieur dans la hiérarchie de plan. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Obtient le niveau de hiérarchie de l'élément de plan. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Obtient l'élément de plan représentant l'élément suivant par rapport à cet élément dans la hiérarchie de plan. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Obtient ou définit l'état ouvert (vrai/faux) pour l'élément de plan. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Obtient l'objet parent de cet élément de plan dans la hiérarchie de plan. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Obtient l'élément de plan représentant l'élément précédent par rapport à cet élément dans la hiérarchie de plan. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Obtient l'objet qui peut être utilisé pour synchroniser l'accès à cette collection. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Obtient ou définit le titre pour cet élément de plan. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Obtient le nombre total d'éléments de plan à tous les niveaux dans la hiérarchie de plan du document. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Ajoute un élément de plan à la collection. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Efface tous les éléments de la collection. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Vérifie si la collection contient l'élément donné. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Copie les entrées de plan dans un System.Array, en commençant à un index particulier de System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Supprime cet élément de plan de la hiérarchie de plan du document. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Supprime l'entrée de plan avec le nom spécifié de la hiérarchie de plan du document. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Renvoie un énumérateur qui itère à travers la collection. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Insère l'élément de plan dans la collection à l'endroit spécifié. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Supprime l'élément par index. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Supprime l'élément de collection de plan. |

### Voir aussi

* classe [Outlines](../outlines/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)