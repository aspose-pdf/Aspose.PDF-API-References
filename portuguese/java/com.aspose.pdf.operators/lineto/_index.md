---
title: "LineTo"
linktitle: "LineTo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador l (adiciona linha ao caminho)."
type: docs
weight: 380
url: /pt/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Classe que representa o operador l (adiciona linha ao caminho).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Inicializa o operador de linha. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getX](#getX--) | Coordenada X do ponto da linha. |
| [getY](#getY--) | Coordenada Y do ponto da linha. |
| [setX](#setX-double-) | Coordenada X do ponto da linha. |
| [setY](#setY-double-) | Coordenada Y do ponto da linha. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Inicializa o operador de linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Coordenada X. |
| y |  | Coordenada Y. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getX {#getX--}
```
public double getX()
```

Coordenada X do ponto da linha.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y do ponto da linha.

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X do ponto da linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y do ponto da linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação de texto do operador.
