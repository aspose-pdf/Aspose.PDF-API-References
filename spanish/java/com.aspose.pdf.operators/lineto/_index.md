---
title: "LineTo"
linktitle: "LineTo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador l (añadir una línea al trazado)."
type: docs
weight: 380
url: /es/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Clase que representa el operador l (añadir una línea al trazado).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Inicializa el operador de línea. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getX](#getX--) | Coordenada X del punto de la línea. |
| [getY](#getY--) | Coordenada Y del punto de la línea. |
| [setX](#setX-double-) | Coordenada X del punto de la línea. |
| [setY](#setY-double-) | Coordenada Y del punto de la línea. |
| [toString](#toString--) | Devuelve la representación textual del operador. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Inicializa el operador de línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Coordenada X. |
| y |  | Coordenada Y. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getX {#getX--}
```
public double getX()
```

Coordenada X del punto de la línea.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y del punto de la línea.

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X del punto de la línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y del punto de la línea.

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
