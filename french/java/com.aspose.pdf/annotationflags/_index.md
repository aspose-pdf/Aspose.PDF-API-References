---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Drapeaux Un ensemble de drapeaux binaires spécifiant diverses caractéristiques de l'annotation."
type: docs
weight: 90
url: /fr/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Drapeaux Un ensemble de drapeaux binaires spécifiant diverses caractéristiques de l'annotation.

## Champs

| Champ | Description |
| --- | --- |
| [Default](#Default) | Valeur par défaut. |
| [Hidden](#Hidden) | Si elle est définie, ne pas afficher ou imprimer l'annotation ni permettre son interaction avec l'utilisateur, quel que soit son type d'annotation ou la disponibilité d'un gestionnaire d'annotation. Dans les cas où l'espace d'écran est limité, la possibilité de masquer et d'afficher sélectivement les annotations peut être utilisée en combinaison avec des flux d'apparence pour afficher des informations auxiliaires contextuelles similaires à des systèmes d'aide en ligne. |
| [Invisible](#Invisible) | Si elle est définie, ne pas afficher l'annotation si elle n'appartient pas à l'un des types d'annotation standard et qu'aucun gestionnaire d'annotation n'est disponible. Si elle est désactivée, afficher une telle annotation inconnue en utilisant un flux d'apparence spécifié par son dictionnaire d'apparence, le cas échéant. |
| [Locked](#Locked) | Si défini, ne pas autoriser la suppression de l'annotation ou la modification de ses propriétés (y compris la position et la taille) par l'utilisateur. Cependant, ce drapeau ne restreint pas les changements du contenu de l'annotation, comme la valeur d'un champ de formulaire. |
| [LockedContents](#LockedContents) | Si défini, ne pas autoriser la modification du contenu de l'annotation par l'utilisateur. Ce drapeau ne restreint pas la suppression de l'annotation ni les changements d'autres propriétés de l'annotation, telles que la position et la taille. |
| [NoRotate](#NoRotate) | Si défini, ne pas faire pivoter l'apparence de l'annotation pour correspondre à la rotation de la page. Le coin supérieur gauche du rectangle de l'annotation reste à un emplacement fixe sur la page, quel que soit la rotation de la page. |
| [NoView](#NoView) | Si défini, ne pas afficher l'annotation à l'écran ni permettre son interaction avec l'utilisateur. L'annotation peut être imprimée (selon le paramètre du drapeau Print) mais doit être considérée comme cachée pour l'affichage à l'écran et l'interaction utilisateur. |
| [NoZoom](#NoZoom) | Si défini, ne pas mettre à l'échelle l'apparence de l'annotation pour correspondre à l'agrandissement de la page. L'emplacement de l'annotation sur la page (défini par le coin supérieur gauche de son rectangle d'annotation) reste fixe, quel que soit l'agrandissement de la page. |
| [Print](#Print) | Si défini, imprimer l'annotation lorsque la page est imprimée. Si désactivé, ne jamais imprimer l'annotation, quel que soit son affichage à l'écran. Cela peut être utile, par exemple, pour les annotations représentant des boutons poussoirs interactifs, qui n'auraient aucune utilité sur la page imprimée. |
| [ReadOnly](#ReadOnly) | Si défini, ne pas autoriser l'annotation à interagir avec l'utilisateur. L'annotation peut être affichée ou imprimée (selon les paramètres des drapeaux NoView et Print) mais ne doit pas répondre aux clics de souris ni changer d'apparence en réponse aux mouvements de la souris. Ce drapeau est ignoré pour les annotations widget ; sa fonction est prise en charge par le drapeau ReadOnly du champ de formulaire associé. |
| [ToggleNoView](#ToggleNoView) | Si défini, inverser l'interprétation du drapeau NoView pour certains événements. Une utilisation typique consiste à avoir une annotation qui apparaît uniquement lorsque le curseur de la souris est maintenu dessus. |

### Default {#Default}
```
public static final int Default
```

Valeur par défaut.

### Hidden {#Hidden}
```
public static final int Hidden
```

Si elle est définie, ne pas afficher ou imprimer l'annotation ni permettre son interaction avec l'utilisateur, quel que soit son type d'annotation ou la disponibilité d'un gestionnaire d'annotation. Dans les cas où l'espace d'écran est limité, la possibilité de masquer et d'afficher sélectivement les annotations peut être utilisée en combinaison avec des flux d'apparence pour afficher des informations auxiliaires contextuelles similaires à des systèmes d'aide en ligne.

### Invisible {#Invisible}
```
public static final int Invisible
```

Si elle est définie, ne pas afficher l'annotation si elle n'appartient pas à l'un des types d'annotation standard et qu'aucun gestionnaire d'annotation n'est disponible. Si elle est désactivée, afficher une telle annotation inconnue en utilisant un flux d'apparence spécifié par son dictionnaire d'apparence, le cas échéant.

### Locked {#Locked}
```
public static final int Locked
```

Si défini, ne pas autoriser la suppression de l'annotation ou la modification de ses propriétés (y compris la position et la taille) par l'utilisateur. Cependant, ce drapeau ne restreint pas les changements du contenu de l'annotation, comme la valeur d'un champ de formulaire.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Si défini, ne pas autoriser la modification du contenu de l'annotation par l'utilisateur. Ce drapeau ne restreint pas la suppression de l'annotation ni les changements d'autres propriétés de l'annotation, telles que la position et la taille.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Si défini, ne pas faire pivoter l'apparence de l'annotation pour correspondre à la rotation de la page. Le coin supérieur gauche du rectangle de l'annotation reste à un emplacement fixe sur la page, quel que soit la rotation de la page.

### NoView {#NoView}
```
public static final int NoView
```

Si défini, ne pas afficher l'annotation à l'écran ni permettre son interaction avec l'utilisateur. L'annotation peut être imprimée (selon le paramètre du drapeau Print) mais doit être considérée comme cachée pour l'affichage à l'écran et l'interaction utilisateur.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Si défini, ne pas mettre à l'échelle l'apparence de l'annotation pour correspondre à l'agrandissement de la page. L'emplacement de l'annotation sur la page (défini par le coin supérieur gauche de son rectangle d'annotation) reste fixe, quel que soit l'agrandissement de la page.

### Print {#Print}
```
public static final int Print
```

Si défini, imprimer l'annotation lorsque la page est imprimée. Si désactivé, ne jamais imprimer l'annotation, quel que soit son affichage à l'écran. Cela peut être utile, par exemple, pour les annotations représentant des boutons poussoirs interactifs, qui n'auraient aucune utilité sur la page imprimée.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Si défini, ne pas autoriser l'annotation à interagir avec l'utilisateur. L'annotation peut être affichée ou imprimée (selon les paramètres des drapeaux NoView et Print) mais ne doit pas répondre aux clics de souris ni changer d'apparence en réponse aux mouvements de la souris. Ce drapeau est ignoré pour les annotations widget ; sa fonction est prise en charge par le drapeau ReadOnly du champ de formulaire associé.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Si défini, inverser l'interprétation du drapeau NoView pour certains événements. Une utilisation typique consiste à avoir une annotation qui apparaît uniquement lorsque le curseur de la souris est maintenu dessus.
