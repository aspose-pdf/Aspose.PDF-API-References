---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador v (añade una curva a la ruta, replicando el punto inicial)."
type: docs
weight: 160
url: /es/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Clase que representa el operador v (añade una curva a la ruta, replicando el punto inicial).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Inicializa el operador de curva. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta el selector de operador. |
| [getPoints](#getPoints--) | Puntos de la curva. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Inicializa el operador de curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x2 |  | Abscisa del segundo punto. |
| y2 |  | Ordenada del segundo punto. |
| x3 |  | Abscisa del tercer punto. |
| y3 |  | Ordenada del tercer punto. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta el selector de operador.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Puntos de la curva.

**Returns:**
matriz de instancias de Point
