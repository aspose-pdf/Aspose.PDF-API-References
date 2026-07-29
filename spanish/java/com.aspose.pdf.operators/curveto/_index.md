---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador c (añade una curva a la ruta)."
type: docs
weight: 150
url: /es/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Clase que representa el operador c (añade una curva a la ruta).

## Campos

| Campo | Descripción |
| --- | --- |
| [X1](#X1) | Obtiene o establece la coordenada X1. |
| [X2](#X2) | Obtiene o establece la coordenada X2. |
| [X3](#X3) | Obtiene o establece la coordenada X3. |
| [Y1](#Y1) | Obtiene o establece la coordenada Y1. |
| [Y2](#Y2) | Obtiene o establece la coordenada Y2. |
| [Y3](#Y3) | Obtiene o establece la coordenada Y3. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Inicializa el operador de curva. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [toCommand](#toCommand--) | ¡Solo para uso interno! |
| [toString](#toString--) | Devuelve la representación de texto del operador. |

### X1 {#X1}
```
public double X1
```

Obtiene o establece la coordenada X1.

### X2 {#X2}
```
public double X2
```

Obtiene o establece la coordenada X2.

### X3 {#X3}
```
public double X3
```

Obtiene o establece la coordenada X3.

### Y1 {#Y1}
```
public double Y1
```

Obtiene o establece la coordenada Y1.

### Y2 {#Y2}
```
public double Y2
```

Obtiene o establece la coordenada Y2.

### Y3 {#Y3}
```
public double Y3
```

Obtiene o establece la coordenada Y3.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Inicializa el operador de curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 |  | Abscisa del primer punto. |
| y1 |  | Ordenada del primer punto. |
| x2 |  | Abscisa del segundo punto. |
| y2 |  | Ordenada del segundo punto. |
| x3 |  | Abscisa del tercer punto. |
| y3 |  | Ordenada del tercer punto. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

¡Solo para uso interno!

**Returns:**
Valor ICommand objeto ICommand

### toString {#toString--}
```
public String toString()
```

Devuelve la representación de texto del operador.

**Returns:**
Representación textual del operador.
