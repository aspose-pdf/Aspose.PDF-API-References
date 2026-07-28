---
title: "Path"
linktitle: "Path"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un arco."
type: docs
weight: 100
url: /es/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

Representa un arco.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Path](#Path--) | Inicializa una nueva instancia de la clase {@code Path}. |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | Inicializa una nueva instancia de la clase {@code Path}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive). |
| [getShapes](#getShapes--) | <p> Obtiene o establece la colección de formas. </p> |
| [getShapesInternal](#getShapesInternal--) | Obtiene o establece la colección de formas. |

### Path {#Path--}
```
public Path()
```

Inicializa una nueva instancia de la clase {@code Path}.

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
Inicializa una nueva instancia de la clase {@code Path}.

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Comprueba si el elemento cabe dentro de las dimensiones del contenedor dadas (inclusive).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Verdadero si cabe; de lo contrario, falso.

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> Obtiene o establece la colección de formas. </p>

**Returns:**
{@code java.util.List<Shape> }objeto

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

Obtiene o establece la colección de formas.

**Returns:**
objeto interno
