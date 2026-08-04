---
title: "SetDash"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant l'opérateur d (définit le motif de tirets de ligne)."
type: docs
weight: 580
url: /fr/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

Classe représentant l'opérateur d (définit le motif de tirets de ligne).

Le type SetDash expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| SetDash(pattern, phase) | Initialise une nouvelle instance de la classe SetDash |
## Propriétés
| Nom | Description |
| :- | :- |
| index | Indice de l'opérateur dans la liste des opérateurs de la page. |
| pattern | Modèle de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets et des espaces alternés.<br/>            Dans le cas d'un tableau à un seul élément, les longueurs du tiret et de l'espace sont égales. |
| phase | Phase de tiret. Avant de commencer à tracer un chemin, le tableau de tirets doit être parcouru, en additionnant les longueurs des tirets et des espaces.<br/>            Lorsque la longueur accumulée est égale à la valeur spécifiée par la phase de tiret, le traçage du chemin commence,<br/>            et le tableau de tirets est utilisé de manière cyclique à partir de ce point. |
## Méthodes
| Nom | Description |
| :- | :- |
| accept(visitor) | Accepte un objet visiteur pour traiter l'opérateur. |
| is_text_show_operator(op) | Détermine si l'opérateur est celui responsable de la sortie du texte (Tj, TJ, etc.) |

### Voir aussi

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

