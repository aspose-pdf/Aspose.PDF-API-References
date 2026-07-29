---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa {@code operators.m} (move para e inicia um novo subcaminho)."
type: docs
weight: 410
url: /pt/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Classe que representa {@code operators.m} (move para e inicia um novo subcaminho).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Inicializa novo {@code Operator.m} (move to) operador. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getX](#getX--) | Coordenada X |
| [getY](#getY--) | Coordenada Y |
| [setX](#setX-double-) | Coordenada X |
| [setY](#setY-double-) | Coordenada Y |
| [toString](#toString--) | Retorna a representação textual do operador. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Inicializa novo {@code Operator.m} (move to) operador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | A coordenada x. |
| y |  | A coordenada y. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getX {#getX--}
```
public double getX()
```

Coordenada X

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y

**Returns:**
valor double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y

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
