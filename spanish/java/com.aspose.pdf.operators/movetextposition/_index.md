---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador Td (mover la posición del texto)."
type: docs
weight: 390
url: /es/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Clase que representa el operador Td (mover la posición del texto).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Inicializa el operador. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Inicializa el operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getX](#getX--) | Coordenada X de la posición del texto. |
| [getY](#getY--) | Coordenada Y de la posición del texto. |
| [setX](#setX-double-) | Coordenada X de la posición del texto. |
| [setY](#setY-double-) | Coordenada Y de la posición del texto. |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Inicializa el operador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Coordenada X de la posición del texto. |
| y |  | Coordenada Y de la posición del texto. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Inicializa el operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getX {#getX--}
```
public double getX()
```

Coordenada X de la posición del texto.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y de la posición del texto.

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X de la posición del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y de la posición del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
