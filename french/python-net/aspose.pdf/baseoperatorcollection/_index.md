---
title: "BaseOperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente la classe de base pour la collection d'opérateurs."
type: docs
weight: 70
url: /fr/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Représente la classe de base pour la collection d'opérateurs.

Le type BaseOperatorCollection expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| is_fast_text_extraction_mode | Indique si la collection est limitée à l'extraction rapide de texte |
## Indexer
| Nom | Description |
| :- | :- |
| [index] | Obtient l'opérateur par son index. |
## Méthodes
| Nom | Description |
| :- | :- |
| suppress_update() | Supprime la mise à jour des données de contenu.<br/>            Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| resume_update() | Reprend la mise à jour du document.<br/>            Met à jour le flux de contenu s'il y a des modifications en attente. |
| insert(index, op) | Insère un opérateur dans la collection. |
| cancel_update() | Annule la dernière mise à jour.<br/>            Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

