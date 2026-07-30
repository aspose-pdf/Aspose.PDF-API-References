---
title: "Classe OutlineCollection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.OutlineCollection. Représente la hiérarchie du plan du document"
type: docs
weight: 8140
url: /fr/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

Représente la hiérarchie du plan du document.

```csharp
public sealed class OutlineCollection : Outlines
```

## Propriétés

| Nom | Description |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Nombre d'éléments de la collection. Veuillez ne pas confondre avec VisibleCount : VisibleCount indique le nombre d'éléments de plan visibles à tous les niveaux. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Obtient un élément de plan représentant le premier élément de niveau supérieur du plan. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à cette collection est synchronisé (thread‑safe). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Obtient un élément de plan de la collection par indice. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Obtient un élément de plan représentant le dernier élément de niveau supérieur du plan. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Obtient un objet pouvant être utilisé pour synchroniser l'accès à cette collection. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Count est la somme du nombre d'éléments de plan descendants visibles à tous les niveaux. Remarque : veuillez ne pas confondre avec Count qui représente le nombre d'éléments dans la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Ajoute un élément d'outline à la collection. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Efface tous les éléments de la collection. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Vérifie si la collection contient l'élément donné. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Copie les éléments d'outline dans un System.Array, en commençant à un indice particulier du System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Supprime tous les éléments d'outline du document outline. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Supprime l'élément d'outline avec le titre spécifié du document outline. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Supprime l'élément par indice. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Lance toujours NotImplementedException. |

### Voir aussi

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


