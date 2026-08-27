---
title: "AppearanceDictionary"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page."
type: docs
weight: 60
url: /fr/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page.

Le type AppearanceDictionary expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_fixed_size | Obtient une valeur indiquant si le dictionnaire a une taille fixe. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | Valeurs d'état D).state,<br/>            où N - apparence normale, R - apparence au survol, D - apparence enfoncée et state - le nom de l'état<br/>            (par ex. On, Off pour les cases à cocher). |
| values | Obtient la liste des valeurs du dictionnaire. <br/>            La collection de résultats contient la liste des objets XForm. |
| is_synchronized | Obtient une valeur indiquant si l'accès au dictionnaire est synchronisé (thread safe). |
| sync_root | Obtient un objet pouvant être utilisé pour synchroniser l'accès au dictionnaire. |
## Méthodes
| Nom | Description |
| :- | :- |
| add(key, value) | Ajoute un élément avec la clé et la valeur fournies. |
| add(key, value) | Ajoute un formulaire X pour la clé spécifiée. |
| copy_to(array, index) | Copie les éléments du dictionnaire dans un tableau, en commençant à un indice de tableau particulier. |
| contains_key(key) | Détermine si ce dictionnaire contient la clé spécifiée. |
| remove(key) | Supprime la clé du dictionnaire. |
| try_get_value(key, value) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

