---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OutlineCollection. Représente la hiérarchie des contours du document
type: docs
weight: 8000
url: /fr/net/aspose.pdf/outlinecollection/
---
## Classe OutlineCollection

Représente la hiérarchie des contours du document.

```csharp
public sealed class OutlineCollection : Outlines
```

## Propriétés

| Nom | Description |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Nombre d'éléments dans la collection. Veuillez ne pas confondre avec VisibleCount : VisibleCount obtient le nombre d'éléments de contour visibles à tous les niveaux. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Obtient un élément de contour représentant le premier élément de niveau supérieur dans le contour. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à cette collection est synchronisé (sécurisé pour les threads). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Obtient un élément de contour de la collection par index. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Obtient un élément de contour représentant le dernier élément de niveau supérieur dans le contour. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à cette collection. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Le compte est la somme du nombre d'éléments de contour descendants visibles à tous les niveaux. Remarque : veuillez ne pas confondre avec Count qui est le nombre d'éléments dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Ajoute un élément de contour à la collection. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Efface tous les éléments de la collection. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Vérifie si la collection contient l'élément donné. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Copie les éléments de contour dans un System.Array, en commençant à un index particulier de System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Supprime tous les éléments de contour de la hiérarchie du document. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Supprime l'élément de contour avec le titre spécifié de la hiérarchie du document. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Renvoie un énumérateur qui itère à travers la collection. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Supprime un élément par index. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Lance toujours NotImplementedException |

### Voir aussi

* classe [Outlines](../outlines/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)