---
title: "OperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "La classe représente une collection d'opérateurs"
type: docs
weight: 1010
url: /fr/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

La classe représente une collection d'opérateurs

Le type OperatorCollection expose les membres suivants :
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
| insert(index, op) | Insère un opérateur dans la collection. |
| insert(at, ops) | Insère des opérateurs à la position donnée. |
| insert(at, ops) | Insère un opérateur dans la collection. |
| delete(index) | Supprime l'opérateur de la collection. |
| delete(ops) | Supprime des opérateurs de la collection. |
| delete(list) | Aucun |
| add(ops) | Ajoute des opérateurs à la fin des opérateurs de contenu. |
| add(ops) | Ajoute un nouvel opérateur dans la collection. |
| suppress_update() | Supprime la mise à jour des données de contenu.<br/>            Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| resume_update() | Reprend la mise à jour du document.<br/>            Met à jour le flux de contenu s'il y a des modifications en attente. |
| cancel_update() | Annule la dernière mise à jour.<br/>            Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu. |
| accept(visitor) | Accepte un objet visiteur IOperatorSelector pour traiter les opérateurs. |
| replace(operators) | Remplacez les opérateurs dans la collection par d'autres opérateurs. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

