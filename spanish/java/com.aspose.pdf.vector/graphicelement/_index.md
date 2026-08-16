---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase base para el objeto gráfico en la página."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Representa la clase base para el objeto gráfico en la página.

## Métodos

| Método | Descripción |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Libera todos los recursos utilizados por la clase {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Obtiene la matriz del elemento gráfico. La matriz se establece cuando se crea el elemento. Cambia cuando se llama a SetPosition(). |
| [getOperators](#getOperators--) | Obtiene una colección de operadores que representan el elemento. |
| [getParent](#getParent--) | Obtiene el {@link XFormPlacement} actual en el que se encuentra el elemento. |
| [getPosition](#getPosition--) | Obtiene o establece la posición en el espacio de coordenadas actual. Si Parent #getParent/#setParent(XFormPlacement) no es nulo, entonces el elemento tiene espacio de coordenadas xForm. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo delimitador del {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Obtiene la página de la que se extrae el elemento gráfico. |
| [remove](#remove--) | Elimina el elemento actual de la página. Si hay muchos elementos para eliminar, es mejor usar Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Convierte el elemento en una única imagen SVG. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Convierte el elemento en una única imagen SVG. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Obtiene o establece la posición en el espacio de coordenadas actual. Si Parent #getParent/#setParent(XFormPlacement) no es nulo, entonces el elemento tiene espacio de coordenadas xForm. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Agrega el elemento actual en la página. Si hay muchos elementos para agregar, es mejor usar Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Libera todos los recursos utilizados por la clase {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Obtiene la matriz del elemento gráfico. La matriz se establece cuando se crea el elemento. Cambia cuando se llama a SetPosition().

**Returns:**
Instancia de matriz

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Obtiene una colección de operadores que representan el elemento.

**Returns:**
Lista de instancias de Operator

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Obtiene el {@link XFormPlacement} actual en el que se encuentra el elemento.

**Returns:**
Instancia de XFormPlacement

### getPosition {#getPosition--}
```
public Point getPosition()
```

Obtiene o establece la posición en el espacio de coordenadas actual. Si Parent #getParent/#setParent(XFormPlacement) no es nulo, entonces el elemento tiene espacio de coordenadas xForm.

**Returns:**
Instancia de Point

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Obtiene el rectángulo delimitador del {@link GraphicElement}.

**Returns:**
Instancia de Rectangle

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Obtiene la página de la que se extrae el elemento gráfico.

**Returns:**
Instancia de página

### remove {#remove--}
```
public final void remove()
```

Elimina el elemento actual de la página. Si hay muchos elementos para eliminar, es mejor usar Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Convierte el elemento en una única imagen SVG.

**Returns:**
La cadena SVG.

### saveToSvg {#saveToSvg-java.lang.String-}
Convierte el elemento en una única imagen SVG.

**Returns:**
La cadena SVG.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Obtiene o establece la posición en el espacio de coordenadas actual. Si Parent #getParent/#setParent(XFormPlacement) no es nulo, entonces el elemento tiene espacio de coordenadas xForm.
