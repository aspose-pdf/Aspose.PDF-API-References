---
title: "Re"
linktitle: "Re"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador re (adiciona retângulo ao caminho)."
type: docs
weight: 460
url: /pt/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Classe que representa o operador re (adiciona retângulo ao caminho).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Re](#Re--) | Construtor para extração de metas. |
| [Re](#Re-double-double-double-double-) | Construtor para programa de escrita. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Construtor para extração de metas. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getHeight](#getHeight--) | Altura do retângulo. |
| [getWidth](#getWidth--) | Obtém a largura do retângulo. |
| [getX](#getX--) | Coordenada X do lado mais à esquerda do retângulo. |
| [getY](#getY--) | Coordenada Y do lado inferior do retângulo. |
| [setHeight](#setHeight-double-) | Altura do retângulo. |
| [setWidth](#setWidth-double-) | Define a largura do retângulo. |
| [setX](#setX-double-) | Coordenada X do lado mais à esquerda do retângulo. |
| [setY](#setY-double-) | Coordenada Y do lado inferior do retângulo. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### Re {#Re--}
```
public Re()
```

Construtor para extração de metas.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Construtor para programa de escrita.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | A coordenada x do canto inferior esquerdo do retângulo. |
| y |  | A coordenada y do canto inferior esquerdo do retângulo. |
| largura |  | A largura do retângulo. |
| altura |  | A altura do retângulo. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Construtor para extração de metas.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getHeight {#getHeight--}
```
public double getHeight()
```

Altura do retângulo.

**Returns:**
Altura do retângulo.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura do retângulo.

**Returns:**
largura do retângulo.

### getX {#getX--}
```
public double getX()
```

Coordenada X do lado mais à esquerda do retângulo.

**Returns:**
valor double

### getY {#getY--}
```
public double getY()
```

Coordenada Y do lado inferior do retângulo.

**Returns:**
valor double

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Altura do retângulo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Altura do retângulo. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define a largura do retângulo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | largura do retângulo. |

### setX {#setX-double-}
```
public void setX(double value)
```

Coordenada X do lado mais à esquerda do retângulo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordenada Y do lado inferior do retângulo.

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
