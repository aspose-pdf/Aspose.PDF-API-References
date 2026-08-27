---
title: "Metadata"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Fournit l'accès au flux de métadonnées XMP."
type: docs
weight: 930
url: /fr/python-net/aspose.pdf/metadata/
---

## Metadata class

Fournit l'accès au flux de métadonnées XMP.

Le type Metadata expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_fixed_size | Vérifie si la collection a une taille fixe. |
| keys | Obtient la collection des clés de métadonnées. |
| values | Obtient les valeurs dans les métadonnées. |
| is_synchronized | Vérifie si la collection est synchronisée. |
| sync_root | Obtient l'objet de synchronisation de la collection. |
## Méthodes
| Nom | Description |
| :- | :- |
| register_namespace_uri(prefix, namespace_uri) | Enregistre l'URI d'espace de noms. |
| register_namespace_uri(prefix, namespace_uri, schema_description) | Enregistre l'URI d'espace de noms. |
| add(key, value) | Ajoute une valeur aux métadonnées. |
| add(key, value) | Ajoute une valeur aux métadonnées. |
| add(prefix, value) | Ajoute l'extension pdf aux métadonnées. |
| get_namespace_uri_by_prefix(prefix) | Renvoie l'URI d'espace de noms par préfixe. |
| get_prefix_by_namespace_uri(namespace_uri) | Renvoie le préfixe par URI d'espace de noms. |
| contains(key) | Vérifie si la clé est contenue dans les métadonnées. |
| remove(key) | Supprime l'entrée des métadonnées. |
| contains_key(key) | Détermine si ce dictionnaire contient la clé spécifiée. |
| try_get_value(key, value) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

