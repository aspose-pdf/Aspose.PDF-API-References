---
title: "XImageCollection"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant la collection XImage."
type: docs
weight: 1690
url: /fr/python-net/aspose.pdf/ximagecollection/
---

## XImageCollection class

Classe représentant la collection XImage.

Le type XImageCollection expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_synchronized | Renvoie vrai si l'objet est synchronisé. |
| sync_root | Renvoie l'objet de synchronisation. |
| names | Obtient le tableau des noms d'images. |
## Indexer
| Nom | Description |
| :- | :- |
| [index] | Obtient l'image de la collection par son indice. |
## Méthodes
| Nom | Description |
| :- | :- |
| add(image) | Ajoute une nouvelle image à la liste d'Images. Cette méthode ajoute l'image en tant que référence au même PdfObject (ce qui permet de réduire la taille du fichier) |
| add(image) | Ajoute l'entité à la fin de la collection, de sorte que l'entité puisse être accédée par le dernier indice. |
| add(image, filter_type) | Ajoute l'entité à la fin de la collection, de sorte que l'entité puisse être accédée par le dernier indice. |
| add(image, quality) | Ajoute l'entité à la fin de la collection, de sorte que l'entité puisse être accédée par le dernier indice. |
| delete(index) | Supprime l'index de la collection par index. |
| delete(index, action) | Supprime l'image de la collection par index en exécutant l'action spécifiée par le paramètre action. |
| delete(name) | Supprime l'élément de la collection par nom. |
| delete(name, action) | Supprime l'élément de la collection par nom. |
| delete() | Supprime l'index de la collection par index. |
| replace(index, stream) | Remplace l'image dans la collection par une autre image. |
| replace(index, stream, quality, is_black_and_white) | Remplace l'image dans la collection par une autre image. |
| replace(index, stream, quality) | Remplace l'image dans la collection par une autre image. |
| get_image_name(image) | Renvoie le nom dans la liste d'images qui est la clé de l'image donnée. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

