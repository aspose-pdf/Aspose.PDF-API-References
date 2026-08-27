---
title: "Classe PageCollection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PageCollection. Collection de Page de Document PDF"
type: docs
weight: 8220
url: /fr/net/aspose.pdf/pagecollection/
---
## PageCollection class

Collection de pages de document PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Obtient le nombre de Page du Document. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Obtient la valeur indiquant que la collection est en lecture seule. Retourne toujours false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Renvoie true si l'objet est synchronisé. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Obtient la Page par indice. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Obtient l'objet de synchronisation de la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Accepte l'objet visiteur [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) qui fournit des fonctionnalités pour travailler avec les Annotation. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Accepte l'objet visiteur [`ImagePlacementAbsorber`](../imageplacementabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de placement d'image. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Accepte l'objet visiteur [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Accepte l'objet visiteur [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Ajoute une Page vide. Si le Document contient déjà des Page de tailles différentes, la taille de la Page la plus fréquente sera sélectionnée. Dans le cas où il n'y a que deux Page différentes, la taille de la première Page sera utilisée. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Ajoute à la collection toutes les Page de la liste. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Ajoute une Page à la collection. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Ajoute à la collection toutes les Page du tableau. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Efface la collection de Page. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Détermine si cette instance contient l'objet. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Copie les Page dans le Document. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Supprime toutes les Page de la collection. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Supprime la Page spécifiée. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Supprime les pages spécifiées dont les numéros sont indiqués dans le tableau. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Supprime tous les champs situés sur les pages et place leurs valeurs à la place. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Efface les données en cache |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Renvoie l'énumérateur des pages. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Renvoie l'index de la page spécifiée. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Insère une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Insère les pages de la collection dans le document. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Insère une page dans la collection de pages à l'emplacement spécifié. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Insère les pages du tableau dans le document. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Supprime l'élément spécifié, lève NotSupportedException. |

### Voir aussi

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


