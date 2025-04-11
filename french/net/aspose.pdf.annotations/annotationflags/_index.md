---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Enum AnnotationFlags d'Aspose.Pdf.Annotations. Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation
type: docs
weight: 1440
url: /fr/net/aspose.pdf.annotations/annotationflags/
---
## Énumération AnnotationFlags

Un ensemble de drapeaux spécifiant diverses caractéristiques de l'annotation.

```csharp
[Flags]
public enum AnnotationFlags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | `0` | Valeur par défaut. |
| Invisible | `1` | Si défini, ne pas afficher l'annotation si elle n'appartient pas à l'un des types d'annotation standard et qu'aucun gestionnaire d'annotation n'est disponible. Si effacé, afficher une telle annotation inconnue en utilisant un flux d'apparence spécifié par son dictionnaire d'apparence, le cas échéant. |
| Hidden | `2` | Si défini, ne pas afficher ou imprimer l'annotation ou permettre son interaction avec l'utilisateur, indépendamment de son type d'annotation ou de la disponibilité d'un gestionnaire d'annotation. Dans les cas où l'espace à l'écran est limité, la capacité de masquer et d'afficher les annotations de manière sélective peut être utilisée en combinaison avec des flux d'apparence pour afficher des informations contextuelles auxiliaires similaires en fonction aux systèmes d'aide en ligne. |
| Print | `4` | Si défini, imprimer l'annotation lorsque la page est imprimée. Si effacé, ne jamais imprimer l'annotation, indépendamment de son affichage à l'écran. Cela peut être utile, par exemple, pour des annotations représentant des boutons-poussoirs interactifs, qui n'auraient aucune utilité significative sur la page imprimée. |
| NoZoom | `8` | Si défini, ne pas mettre à l'échelle l'apparence de l'annotation pour correspondre à la magnification de la page. L'emplacement de l'annotation sur la page (défini par le coin supérieur gauche de son rectangle d'annotation) reste fixe, indépendamment de la magnification de la page. |
| NoRotate | `10` | Si défini, ne pas faire pivoter l'apparence de l'annotation pour correspondre à la rotation de la page. Le coin supérieur gauche du rectangle d'annotation reste à un emplacement fixe sur la page, indépendamment de la rotation de la page. |
| NoView | `20` | Si défini, ne pas afficher l'annotation à l'écran ou permettre son interaction avec l'utilisateur. L'annotation peut être imprimée (selon le paramètre du drapeau Print) mais doit être considérée comme cachée aux fins d'affichage à l'écran et d'interaction avec l'utilisateur. |
| ReadOnly | `40` | Si défini, ne pas permettre à l'annotation d'interagir avec l'utilisateur. L'annotation peut être affichée ou imprimée (selon les paramètres des drapeaux NoView et Print) mais ne doit pas répondre aux clics de souris ou changer son apparence en réponse aux mouvements de souris. Ce drapeau est ignoré pour les annotations de widget ; sa fonction est englobée par le drapeau ReadOnly du champ de formulaire associé. |
| Locked | `80` | Si défini, ne pas permettre à l'annotation d'être supprimée ou à ses propriétés (y compris la position et la taille) d'être modifiées par l'utilisateur. Cependant, ce drapeau ne restreint pas les modifications du contenu de l'annotation, comme la valeur d'un champ de formulaire. |
| ToggleNoView | `100` | Si défini, inverser l'interprétation du drapeau NoView pour certains événements. Une utilisation typique est d'avoir une annotation qui apparaît uniquement lorsqu'un curseur de souris est maintenu au-dessus. |
| LockedContents | `200` | Si défini, ne pas permettre à l'utilisateur de modifier le contenu de l'annotation. Ce drapeau ne restreint pas la suppression de l'annotation ou les modifications d'autres propriétés d'annotation, telles que la position et la taille. |

### Voir aussi

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)