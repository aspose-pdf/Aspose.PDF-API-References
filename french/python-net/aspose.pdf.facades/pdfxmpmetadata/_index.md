---
title: "PdfXmpMetadata"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe pour la manipulation des métadonnées XMP."
type: docs
weight: 380
url: /fr/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Classe pour la manipulation des métadonnées XMP.

Le type PdfXmpMetadata expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PdfXmpMetadata() | Constructeur pour PdfXmpMetadata. |
| PdfXmpMetadata(document) | Initialise une nouvelle instance de la classe PdfXmpMetadata |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| keys | Obtient les clés du dictionnaire. |
| values | Obtient la collection des valeurs du dictionnaire. |
| is_fixed_size | Renvoie true si la collection a une taille fixe. |
| is_synchronized | Renvoie true si la collection est synchronisée. |
| sync_root | Obtient l'objet de synchronisation de la collection. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save(dest_file) | Enregistre le document PDF dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document PDF dans le flux spécifié. |
| add(key, value) | Ajoute la valeur aux métadonnées XMP. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Ajoute un champ d'extension aux métadonnées. |
| add(key, value) | Ajoute un nouvel élément à l'objet dictionnaire. |
| add(key, value) | Ajoute un champ d'extension aux métadonnées. |
| remove(key) | Supprime l'élément avec la clé spécifiée. |
| remove(key) | Supprime la clé du dictionnaire. |
| contains(key) | Vérifie si le dictionnaire contient la clé spécifiée. |
| contains(property) | Vérifie si le dictionnaire contient la propriété spécifiée. |
| get_xmp_metadata() | Obtient le XmpMetadata du PDF d'entrée au format XML. |
| get_xmp_metadata(name) | Obtenez une partie du XmpMetadata du PDF d'entrée selon un nom de métadonnée. |
| close() | Libère toutes les ressources associées à la façade actuelle. |
| register_namespace_uri(prefix, namespace_uri) | Enregistre l'URI d'espace de noms. |
| get_namespace_uri_by_prefix(prefix) | Obtient l'URI d'espace de noms par préfixe. |
| get_prefix_by_namespace_uri(namespace_uri) | Obtient le préfixe par l'URI d'espace de noms. |
| contains_key(key) | Détermine si ce dictionnaire contient la clé spécifiée. |
| try_get_value(key, value) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

