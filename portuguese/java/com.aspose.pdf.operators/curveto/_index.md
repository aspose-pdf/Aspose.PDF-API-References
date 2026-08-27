---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador c (adicionar curva ao caminho)."
type: docs
weight: 150
url: /pt/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Classe que representa o operador c (adicionar curva ao caminho).

## Campos

| Campo | Descrição |
| --- | --- |
| [X1](#X1) | Obtém ou define a coordenada X1. |
| [X2](#X2) | Obtém ou define a coordenada X2. |
| [X3](#X3) | Obtém ou define a coordenada X3. |
| [Y1](#Y1) | Obtém ou define a coordenada Y1. |
| [Y2](#Y2) | Obtém ou define a coordenada Y2. |
| [Y3](#Y3) | Obtém ou define a coordenada Y3. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Inicializa o operador de curva. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Retorna a representação textual do operador. |

### X1 {#X1}
```
public double X1
```

Obtém ou define a coordenada X1.

### X2 {#X2}
```
public double X2
```

Obtém ou define a coordenada X2.

### X3 {#X3}
```
public double X3
```

Obtém ou define a coordenada X3.

### Y1 {#Y1}
```
public double Y1
```

Obtém ou define a coordenada Y1.

### Y2 {#Y2}
```
public double Y2
```

Obtém ou define a coordenada Y2.

### Y3 {#Y3}
```
public double Y3
```

Obtém ou define a coordenada Y3.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Inicializa o operador de curva.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 |  | Abscissa do primeiro ponto. |
| y1 |  | Ordenada do primeiro ponto. |
| x2 |  | Abscissa do segundo ponto. |
| y2 |  | Ordenada do segundo ponto. |
| x3 |  | Abscissa do terceiro ponto. |
| y3 |  | Ordenada do terceiro ponto. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Somente para uso interno!

**Returns:**
valor ICommand objeto ICommand

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual do operador.
