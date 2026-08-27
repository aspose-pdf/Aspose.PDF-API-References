---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador i (define a tolerância de planicidade)."
type: docs
weight: 620
url: /pt/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Classe que representa o operador i (define a tolerância de planicidade).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Inicializa o operador. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita um objeto visitante para processar o operador. |
| [getFlatness](#getFlatness--) | Obtém a planicidade. |
| [setFlatness](#setFlatness-double-) | Define a planicidade. |
| [toCommand](#toCommand--) | Somente para uso interno! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Inicializa o operador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| planicidade |  | O valor da planicidade. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita um objeto visitante para processar o operador.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Obtém a planicidade.

**Returns:**
valor double

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Define a planicidade.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Somente para uso interno!

**Returns:**
valor ICommand objeto ICommand
