---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador Td (move a posição do texto)."
type: docs
weight: 390
url: /pt/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Classe que representa o operador Td (move a posição do texto).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Inicializa o operador. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Inicializa o operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getX](#getX--) | Coordenada X da posição do texto. |
| [getY](#getY--) | Coordenada Y da posição do texto. |
| [setX](#setX-double-) | Coordenada X da posição do texto. |
| [setY](#setY-double-) | Coordenada Y da posição do texto. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Inicializa o operador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Coordenada X da posição do texto. |
| y |  | Coordenada Y da posição do texto. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Inicializa o operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getX {#getX--}
```
public double getX()
```

Coordenada X da posição do texto.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y da posição do texto.

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X da posição do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y da posição do texto.

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
Representação textual do operador.
