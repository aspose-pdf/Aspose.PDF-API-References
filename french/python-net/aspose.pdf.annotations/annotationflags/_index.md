---
title: "AnnotationFlags"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation."
type: docs
weight: 930
url: /fr/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation.

## Members
| Nom du membre | Description |
| :- | :- |
| DEFAULT | Valeur par défaut. |
| INVISIBLE | Si défini, ne pas afficher l'annotation si elle n'appartient pas à l'un des types d'annotation standard<br/>            et aucun gestionnaire d'annotation n'est disponible. Si désactivé, afficher une telle annotation inconnue<br/>            en utilisant un flux d'apparence spécifié par son dictionnaire d'apparence, le cas échéant. |
| HIDDEN | Si défini, ne pas afficher ou imprimer l'annotation ni permettre son interaction avec l'utilisateur,<br/>            quel que soit son type d'annotation ou la disponibilité d'un gestionnaire d'annotation.<br/>            Dans les cas où l'espace d'écran est limité, la capacité de masquer et d'afficher sélectivement les annotations<br/>            peut être utilisée en combinaison avec des flux d'apparence pour afficher des informations auxiliaires en pop‑up<br/>            similaires en fonction aux systèmes d'aide en ligne. |
| IMPRIMER | Si défini, imprimer l'annotation lors de l'impression de la page. Si désactivé, ne jamais imprimer l'annotation,<br/>            quel que soit son affichage à l'écran. Cela peut être utile, par exemple, pour les annotations<br/>            représentant des boutons poussoirs interactifs, qui n'auraient aucune utilité sur la page imprimée. |
| NO_ZOOM | Si défini, ne pas mettre à l'échelle l'apparence de l'annotation pour correspondre à l'agrandissement de la page.<br/>            L'emplacement de l'annotation sur la page (défini par le coin supérieur gauche de son rectangle d'annotation)<br/>            reste fixe, quel que soit l'agrandissement de la page. |
| NO_ROTATE | Si défini, ne pas faire pivoter l'apparence de l'annotation pour correspondre à la rotation de la page.<br/>            Le coin supérieur gauche du rectangle d'annotation reste à un emplacement fixe sur la page,<br/>            quel que soit la rotation de la page. |
| NO_VIEW | Si défini, ne pas afficher l'annotation à l'écran ni permettre son interaction avec l'utilisateur.<br/>            L'annotation peut être imprimée (selon le paramètre du drapeau Print)<br/>            mais doit être considérée comme masquée pour l'affichage à l'écran et l'interaction utilisateur. |
| READ_ONLY | Si défini, ne pas permettre à l'annotation d'interagir avec l'utilisateur. L'annotation peut être affichée<br/>            ou imprimée (selon les paramètres des drapeaux NoView et Print) mais ne doit pas répondre aux clics de souris<br/>            ni modifier son apparence en réponse aux mouvements de la souris. Ce drapeau est ignoré pour les annotations de type widget;<br/>            sa fonction est prise en charge par le drapeau ReadOnly du champ de formulaire associé. |
| LOCKED | Si défini, ne pas permettre la suppression de l'annotation ou la modification de ses propriétés (y compris la position et la taille)<br/>            par l'utilisateur. Cependant, ce drapeau ne restreint pas les modifications du contenu de l'annotation,<br/>            comme la valeur d'un champ de formulaire. |
| TOGGLE_NO_VIEW | Si défini, inverse l'interprétation du drapeau NoView pour certains événements.<br/>            Une utilisation typique consiste à avoir une annotation qui apparaît uniquement lorsque le curseur de la souris est maintenu dessus. |
| LOCKED_CONTENTS | Si défini, n'autorise pas l'utilisateur à modifier le contenu de l'annotation.<br/>            Ce drapeau ne restreint pas la suppression de l'annotation ou les modifications d'autres propriétés de l'annotation,<br/>            telles que la position et la taille. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

