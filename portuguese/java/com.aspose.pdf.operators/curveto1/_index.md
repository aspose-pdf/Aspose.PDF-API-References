---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador v (adicionar curva ao caminho, ponto inicial replicado)."
type: docs
weight: 160
url: /pt/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Classe que representa o operador v (adicionar curva ao caminho, ponto inicial replicado).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Inicializa o operador de curva. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita o seletor de operador. |
| [getPoints](#getPoints--) | Pontos da curva. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Inicializa o operador de curva.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x2 |  | Abscissa do segundo ponto. |
| y2 |  | Ordenada do segundo ponto. |
| x3 |  | Abscissa do terceiro ponto. |
| y3 |  | Ordenada do terceiro ponto. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita o seletor de operador.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Pontos da curva.

**Returns:**
array de instâncias de Point
