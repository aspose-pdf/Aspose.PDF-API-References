---
title: "Énumération AnnotationFlags"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.Annotations.AnnotationFlags. Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation."
type: docs
weight: 1530
url: /fr/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation.

```csharp
[Flags]
public enum AnnotationFlags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | `0` | Valeur par défaut. |
| Invisible | `1` | Si activé, ne pas afficher l'annotation si elle n'appartient pas à l'un des types d'annotation standard et qu'aucun gestionnaire d'annotation n'est disponible. Si désactivé, afficher une telle annotation inconnue en utilisant un flux d'apparence spécifié par son dictionnaire d'apparence, le cas échéant. |
| Hidden | `2` | Si activé, ne pas afficher ou imprimer l'annotation ni permettre son interaction avec l'utilisateur, quel que soit son type d'annotation ou la disponibilité d'un gestionnaire d'annotation. Dans les cas où l'espace écran est limité, la possibilité de masquer et d'afficher sélectivement les annotations peut être utilisée en combinaison avec des flux d'apparence pour afficher des informations auxiliaires contextuelles similaires aux systèmes d'aide en ligne. |
| Print | `4` | Si activé, imprimer l'annotation lors de l'impression de la page. Si désactivé, ne jamais imprimer l'annotation, quel que soit son affichage à l'écran. Cela peut être utile, par exemple, pour les annotations représentant des boutons poussoirs interactifs, qui n'auraient aucune utilité sur la page imprimée. |
| NoZoom | `8` | Si activé, ne pas mettre à l'échelle l'apparence de l'annotation pour correspondre à l'agrandissement de la page. La position de l'annotation sur la page (définie par le coin supérieur gauche de son rectangle d'annotation) reste fixe, quel que soit l'agrandissement de la page. |
| NoRotate | `10` | Si activé, ne pas faire pivoter l'apparence de l'annotation pour correspondre à la rotation de la page. Le coin supérieur gauche du rectangle d'annotation reste à une position fixe sur la page, quelle que soit la rotation de la page. |
| NoView | `20` | Si activé, ne pas afficher l'annotation à l'écran ni permettre son interaction avec l'utilisateur. L'annotation peut être imprimée (selon le paramètre du drapeau Print) mais doit être considérée comme cachée pour l'affichage à l'écran et l'interaction utilisateur. |
| ReadOnly | `40` | Si activé, ne pas permettre à l'annotation d'interagir avec l'utilisateur. L'annotation peut être affichée ou imprimée (selon les paramètres des drapeaux NoView et Print) mais ne doit pas répondre aux clics de souris ni modifier son apparence en réponse aux mouvements de la souris. Ce drapeau est ignoré pour les annotations de type widget ; sa fonction est prise en charge par le drapeau ReadOnly du champ de formulaire associé. |
| Locked | `80` | Si activé, ne pas autoriser la suppression de l'annotation ou la modification de ses propriétés (y compris la position et la taille) par l'utilisateur. Cependant, ce drapeau ne restreint pas les modifications du contenu de l'annotation, comme la valeur d'un champ de formulaire. |
| ToggleNoView | `100` | Si activé, inverser l'interprétation du drapeau NoView pour certains événements. Une utilisation typique consiste à avoir une annotation qui n'apparaît que lorsque le curseur de la souris est maintenu au-dessus. |
| LockedContents | `200` | Si activé, ne pas autoriser la modification du contenu de l'annotation par l'utilisateur. Ce drapeau ne restreint pas la suppression de l'annotation ou les modifications d'autres propriétés de l'annotation, telles que la position et la taille. |

### Voir aussi

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


