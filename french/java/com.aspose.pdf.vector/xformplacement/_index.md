---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le placement du XForm. Si le XForm est affiché sur la page plus d'une fois, tous les XformPlacements associés à ce XForm auront des éléments graphiques communs, mais."
type: docs
weight: 70
url: /fr/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Représente le placement XForm. Si le XForm est affiché sur la page plus d'une fois, tous les XformPlacements associés à ce XForm partageront les mêmes éléments graphiques, mais auront des états graphiques différents.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il vaut mieux utiliser Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Obtient les éléments graphiques à l'intérieur de ce XForm. |
| [getName](#getName--) | Obtient le nom du XForm. |
| [getRectangle](#getRectangle--) | Obtient le rectangle englobant du GraphicElement. |
| [getXForm](#getXForm--) | Obtient le XForm associé à ce XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Obtient ou définit la position dans l'espace de coordonnées actuel. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il vaut mieux utiliser Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Obtient les éléments graphiques à l'intérieur de ce XForm.

**Returns:**
Instance de GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

Obtient le nom du XForm.

**Returns:**
valeur String

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle englobant du GraphicElement.

**Returns:**
Instance de Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Obtient le XForm associé à ce XFormPlacement.

**Returns:**
Instance de XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
Obtient ou définit la position dans l'espace de coordonnées actuel.
