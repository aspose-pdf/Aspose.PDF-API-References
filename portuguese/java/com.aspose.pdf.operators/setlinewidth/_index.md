---
title: "SetLineWidth"
linktitle: "SetLineWidth"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador w (define a largura da linha)."
type: docs
weight: 690
url: /pt/java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

Classe que representa o operador w (define a largura da linha).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | Inicializa o operador com o valor da largura. |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getWidth](#getWidth--) | Obtém a largura da linha. |
| [setWidth](#setWidth-double-) | Define a largura da linha. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

Inicializa o operador com o valor da largura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| largura |  | Valor da largura. |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura da linha.

**Returns:**
largura da linha.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Define a largura da linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | largura da linha. |

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual do operador.
