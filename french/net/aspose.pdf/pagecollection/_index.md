---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PageCollection. Collection de pages de documents PDF
type: docs
weight: 8080
url: /fr/net/aspose.pdf/pagecollection/
---
## Classe PageCollection

Collection de pages de documents PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Obtient le nombre de pages dans le document. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Obtient la valeur indiquant si la collection est en lecture seule. Renvoie toujours false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Renvoie true si l'objet est synchronisé. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Obtient la page par index. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Obtient l'objet de synchronisation de la collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Accepte l'objet visiteur [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) qui fournit des fonctionnalités pour travailler avec les annotations. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Accepte l'objet visiteur [`ImagePlacementAbsorber`](../imageplacementabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de placement d'image. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Accepte l'objet visiteur [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de texte. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Accepte l'objet visiteur [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de texte. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Ajoute une page vide. Si le document contient déjà des pages de tailles variées, la taille de la page la plus fréquemment rencontrée sera sélectionnée. Dans le cas où il n'y a que deux pages différentes, la taille de la première page sera utilisée. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Ajoute à la collection toutes les pages de la liste. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Ajoute une page à la collection. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Ajoute à la collection toutes les pages du tableau. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Efface la collection de pages. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Détermine si cette instance contient l'objet. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Copie les pages dans le document. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Supprime toutes les pages de la collection. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Supprime la page spécifiée. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Supprime les pages spécifiées dont les numéros sont indiqués dans le tableau. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Supprime tous les champs situés sur les pages et place leurs valeurs à la place. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Efface les données mises en cache. |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Renvoie l'énumérateur des pages. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Renvoie l'index de la page spécifiée. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Insère une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles variées, la taille de la page la plus fréquemment rencontrée sera sélectionnée. Dans le cas où il n'y a que deux pages différentes, la taille de la première page sera utilisée. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Insère des pages de la collection dans le document. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Insère une page dans la collection de pages à l'endroit spécifié. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Insère les pages du tableau dans le document. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Supprime l'élément spécifié, lance NotSupportedException. |

### Voir aussi

* classe [Page](../page/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)