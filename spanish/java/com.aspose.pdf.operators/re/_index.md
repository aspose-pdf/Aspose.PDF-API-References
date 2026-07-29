---
title: "Re"
linktitle: "Re"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador re (añadir un rectángulo al trazado)."
type: docs
weight: 460
url: /es/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Clase que representa el operador re (añadir un rectángulo al trazado).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Re](#Re--) | Constructor para extraer objetivos. |
| [Re](#Re-double-double-double-double-) | Constructor para programa de escritura. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Constructor para extraer objetivos. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getHeight](#getHeight--) | Altura del rectángulo. |
| [getWidth](#getWidth--) | Obtiene el ancho del rectángulo. |
| [getX](#getX--) | Coordenada X del lado más izquierdo del rectángulo. |
| [getY](#getY--) | Coordenada Y del lado inferior del rectángulo. |
| [setHeight](#setHeight-double-) | Altura del rectángulo. |
| [setWidth](#setWidth-double-) | Establece el ancho del rectángulo. |
| [setX](#setX-double-) | Coordenada X del lado más izquierdo del rectángulo. |
| [setY](#setY-double-) | Coordenada Y del lado inferior del rectángulo. |
| [toString](#toString--) | Devuelve la representación textual del operador. |

### Re {#Re--}
```
public Re()
```

Constructor para extraer objetivos.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Constructor para programa de escritura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | La coordenada x de la esquina inferior izquierda del rectángulo. |
| y |  | La coordenada y de la esquina inferior izquierda del rectángulo. |
| ancho |  | El ancho del rectángulo. |
| altura |  | La altura del rectángulo. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Constructor para extraer objetivos.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getHeight {#getHeight--}
```
public double getHeight()
```

Altura del rectángulo.

**Returns:**
Altura del rectángulo.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho del rectángulo.

**Returns:**
ancho del rectángulo.

### getX {#getX--}
```
public double getX()
```

Coordenada X del lado más izquierdo del rectángulo.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y del lado inferior del rectángulo.

**Returns:**
valor double

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Altura del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Altura del rectángulo. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece el ancho del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | ancho del rectángulo. |

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X del lado más izquierdo del rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y del lado inferior del rectángulo.

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
