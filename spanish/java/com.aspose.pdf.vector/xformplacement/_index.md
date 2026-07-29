---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la ubicación de XForm. Si el XForm se muestra en la página más de una vez, todas las XformPlacements asociadas con este XForm tendrán elementos gráficos comunes, pero."
type: docs
weight: 70
url: /es/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Representa la ubicación del XForm. Si el XForm se muestra en la página más de una vez, todas las XformPlacements asociadas con este XForm tendrán elementos gráficos comunes, pero estados gráficos diferentes.

## Métodos

| Método | Descripción |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Obtiene los elementos gráficos dentro de este XForm. |
| [getName](#getName--) | Obtiene el nombre del XForm. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo delimitador del GraphicElement. |
| [getXForm](#getXForm--) | Obtiene el XForm asociado con este XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Obtiene o establece la posición en el espacio de coordenadas actual. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Obtiene los elementos gráficos dentro de este XForm.

**Returns:**
Instancia de GraphicElementCollection

### getName {#getName--}
```
public final String getName()
```

Obtiene el nombre del XForm.

**Returns:**
valor String

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo delimitador del GraphicElement.

**Returns:**
Instancia de Rectangle

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Obtiene el XForm asociado con este XFormPlacement.

**Returns:**
Instancia de XForm

### setPosition {#setPosition-com.aspose.pdf.Point-}
Obtiene o establece la posición en el espacio de coordenadas actual.
