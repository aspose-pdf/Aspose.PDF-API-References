---
title: "PageCollection"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Collection de pages du document PDF."
type: docs
weight: 1100
url: /fr/python-net/aspose.pdf/pagecollection/
---

## PageCollection class

Collection de pages du document PDF.

Le type PageCollection expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_synchronized | Renvoie vrai si l'objet est synchronisé. |
| sync_root | Obtient l'objet de synchronisation de la collection. |
## Indexer
| Nom | Description |
| :- | :- |
| [index] | Obtient la page par indice. |
## Méthodes
| Nom | Description |
| :- | :- |
| add(entity) | Ajoute la page à la collection. |
| add() | Ajoute la page à la collection. |
| add(pages) | Ajoute à la collection toutes les pages de la liste. |
| add(pages) | Ajoute à la collection toutes les pages du tableau. |
| delete(index) | Supprime la page spécifiée. |
| delete() | Supprime la page spécifiée. |
| delete(pages) | Supprime les pages dont les numéros sont spécifiés dans le tableau. |
| accept(visitor) | Accepte l'objet visiteur [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) qui fournit des fonctionnalités pour travailler avec les annotations. |
| accept(visitor) | Accepte l'objet visiteur [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de placement d'image. |
| accept(visitor) | Accepte l'objet visiteur [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| accept(visitor) | Accepte l'objet visiteur [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| insert(page_number) | Insère une page vide dans la collection à la position spécifiée. |
| insert(page_number, entity) | Insère une page vide dans la collection à la position spécifiée. |
| insert(page_number, pages) | Insère les pages de la collection dans le document. |
| insert(page_number, pages) | Insère les pages du tableau dans le document. |
| index_of(entity) | Renvoie l'index de la page spécifiée. |
| flatten() | Supprime tous les champs situés sur les pages et place leurs valeurs à la place. |
| free_memory() | Efface les données en cache |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

