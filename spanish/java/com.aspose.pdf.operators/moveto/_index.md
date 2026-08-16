---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa {@code operators.m} (moverse y comenzar un nuevo subtrazado)."
type: docs
weight: 410
url: /es/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Clase que representa {@code operators.m} (moverse y comenzar un nuevo subtrazado).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Inicializa un nuevo {@code Operator.m} (move to) operator. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getX](#getX--) | Coordenada X |
| [getY](#getY--) | Coordenada Y |
| [setX](#setX-double-) | Coordenada X |
| [setY](#setY-double-) | Coordenada Y |
| [toString](#toString--) | Devuelve la representación textual del operador. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Inicializa un nuevo {@code Operator.m} (move to) operator.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | La coordenada x. |
| y |  | La coordenada y. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getX {#getX--}
```
public double getX()
```

Coordenada X

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Devuelve la representación textual del operador.

**Returns:**
Representación de texto del operador.
