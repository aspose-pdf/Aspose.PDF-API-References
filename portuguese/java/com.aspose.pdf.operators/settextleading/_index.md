---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador TL (define o espaçamento entre linhas de texto)."
type: docs
weight: 740
url: /pt/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Classe que representa o operador TL (define o espaçamento entre linhas de texto).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Construtor para o operador de avanço de texto. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getLeading](#getLeading--) | Obtém o avanço do texto. |
| [setLeading](#setLeading-double-) | Define o avanço do texto. |
| [toString](#toString--) | Produz o código de texto do operador. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Construtor para o operador de avanço de texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| leading |  | Avanço de texto. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getLeading {#getLeading--}
```
public double getLeading()
```

Obtém o avanço do texto.

**Returns:**
valor double

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Define o avanço do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Produz o código de texto do operador.

**Returns:**
Representação textual do operador.
