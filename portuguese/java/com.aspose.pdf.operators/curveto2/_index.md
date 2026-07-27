---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador y (adicionar curva ao caminho, ponto final replicado)."
type: docs
weight: 170
url: /pt/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Classe que representa o operador y (adicionar curva ao caminho, ponto final replicado).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Inicializa o operador de curva. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getPoints](#getPoints--) | Pontos da curva. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Inicializa o operador de curva.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 |  | Abscissa do segundo ponto. |
| y1 |  | Ordenada do segundo ponto. |
| x3 |  | Abscissa do terceiro ponto. |
| y3 |  | Ordenada do terceiro ponto. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Pontos da curva.

**Returns:**
array de instâncias de Point
