---
title: "XImage"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant l'objet image X-Object."
type: docs
weight: 1680
url: /fr/python-net/aspose.pdf/ximage/
---

## XImage class

Classe représentant l'objet image X-Object.

Le type XImage expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| contains_transparency | Si l'image contient de la transparence, retourne vrai ; sinon, faux. |
| grayscaled | Obtient la version en niveaux de gris de l'image. |
| filter_type | Obtient le type de filtre d'image. |
| largeur | Obtient la largeur de l'image. |
| hauteur | Obtient la hauteur de l'image. |
| nom | Obtient ou définit le nom de l'image. Veuillez noter que si vous changez le nom de l'image qui possède des références dans le contenu des pages, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas. |
| metadata | Métadonnées de l'image. |
## Méthodes
| Nom | Description |
| :- | :- |
| save(stream) | Enregistre les données de l'image dans le flux au format JPEG. |
| save(stream, format) | Enregistre l'image dans le flux avec le format demandé. |
| save(stream, resolution) | Enregistre les données de l'image dans le flux au format JPEG avec la résolution spécifiée. |
| save(stream, format, resolution) | Enregistre l'image dans le flux avec le format demandé et la résolution spécifiée. |
| rename(name) | Renomme l'image et remplace toutes les références à l'image par le nouveau nom. |
| get_color_type() | Renvoie le type de couleur de l'image. |
| detect_color_type(bmp) | Renvoie le type de couleur de l'image. |
| is_the_same_object(image) | Renvoie true si les deux images font référence au même objet. |
| get_name_in_collection() | Renvoie le nom de l'image dans la collection ints. |
| to_stream() | Renvoie le flux d'image original. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

