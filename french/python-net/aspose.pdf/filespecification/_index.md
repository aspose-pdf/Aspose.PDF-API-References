---
title: "FileSpecification"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant le fichier intégré."
type: docs
weight: 360
url: /fr/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Classe représentant le fichier intégré.

Le type FileSpecification expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FileSpecification(file) | Initialise une nouvelle instance de la classe FileSpecification |
| FileSpecification(stream, name) | Initialise une nouvelle instance de la classe FileSpecification |
| FileSpecification(file, description) | Initialise une nouvelle instance de la classe FileSpecification |
| FileSpecification(stream, name, description) | Initialise une nouvelle instance de la classe FileSpecification |
| FileSpecification(file_name, annot) | Initialise une nouvelle instance de la classe FileSpecification |
| FileSpecification() | Crée une nouvelle spécification de fichier vide. |
## Propriétés
| Nom | Description |
| :- | :- |
| encodage | Obtient ou définit le format d'encodage.<br/>            Valeurs possibles : Zip - le fichier est compressé avec ZIP, <br/>            None - le fichier n'est pas compressé. |
| include_contents | Si vrai, le contenu du fichier sera inclus dans la spécification de fichier. |
| encrypted_payload | Obtient la charge utile chiffrée. |
| description | Obtient ou définit le texte associé à la spécification du fichier. |
| af_relationship | Relation de fichier associée. |
| stream_contents | Obtient le contenu du fichier sous forme de flux. <br/>            Le contenu n'est pas chargé en mémoire, ce qui permet de réduire l'utilisation de la mémoire.<br/>            Cependant, ce flux ne prend pas en charge le positionnement ni la propriété Length. Si vous avez besoin de ces fonctionnalités, veuillez utiliser la propriété Contents à la place. |
| contenu | Obtient ou définit le contenu du fichier. <br/>            Cette propriété renvoie des données chargées en mémoire, ce qui peut provoquer une exception Out of memory pour de grandes quantités de données.<br/>            Pour réduire l'utilisation de la mémoire, veuillez utiliser StreamContents. |
| params | Obtient les paramètres du fichier. |
| mime_type | Obtient le sous-type du fichier intégré |
| nom | Obtient ou définit le nom de la spécification du fichier. |
| unicode_name | Obtient ou définit le nom unicode de la spécification du fichier. |
| file_system | Obtient ou définit le nom du système de fichiers. |
## Méthodes
| Nom | Description |
| :- | :- |
| get_value(key) | Obtient le paramètre spécifique à l'application. |
| set_value(key, value) | Définit le paramètre spécifique à l'application. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

