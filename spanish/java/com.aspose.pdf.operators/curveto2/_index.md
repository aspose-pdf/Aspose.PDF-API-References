---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador y (añade una curva a la ruta, replicando el punto final)."
type: docs
weight: 170
url: /es/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Clase que representa el operador y (añade una curva a la ruta, replicando el punto final).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Inicializa el operador de curva. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getPoints](#getPoints--) | Puntos de la curva. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Inicializa el operador de curva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 |  | Abscisa del segundo punto. |
| y1 |  | Ordenada del segundo punto. |
| x3 |  | Abscisa del tercer punto. |
| y3 |  | Ordenada del tercer punto. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Puntos de la curva.

**Returns:**
matriz de instancias de Point
