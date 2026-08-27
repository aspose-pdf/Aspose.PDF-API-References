---
title: "SubPath"
linktitle: "SubPath"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un objet graphique vectoriel sur la page. Fondamentalement, les objets graphiques vectoriels sont représentés par deux groupes de SubPaths. L'un d'eux est représenté par un ensemble de lignes et."
type: docs
weight: 60
url: /fr/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Représente un objet graphique vectoriel sur la page. En principe, les objets graphiques vectoriels sont représentés par deux groupes de SubPaths. L'un d'eux est représenté par un ensemble de lignes et de courbes. Les autres sont présentés sous forme de rectangles et peuvent parfois prêter à confusion. Habituellement, il s'agit d'une zone rectangulaire qui possède une couleur, mais très souvent ce rectangle est placé au début de la page et définit tout l'espace de la page en blanc. Ainsi vous obtenez le SubPath, mais visuellement vous ne voyez que le texte sur la page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRectangle](#getRectangle--) | Obtient le rectangle englobant du GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle englobant du GraphicElement.

**Returns:**
Instance de Rectangle
