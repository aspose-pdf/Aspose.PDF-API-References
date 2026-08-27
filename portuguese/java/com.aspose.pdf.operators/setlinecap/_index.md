---
title: "SetLineCap"
linktitle: "SetLineCap"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador J (define o estilo de extremidade da linha)."
type: docs
weight: 670
url: /pt/java/com.aspose.pdf.operators/setlinecap/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineCap, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineCap

```
public class SetLineCap extends Operator
```

Classe que representa o operador J (define o estilo de extremidade da linha).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetLineCap](#SetLineCap-int-) |  |
| [SetLineCap](#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineCapStyle-) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getCap](#getCap--) | Obtém o estilo dos tampas de linha. |
| [setCap](#setCap-int-) | Define o estilo dos tampas de linha. |

### SetLineCap {#SetLineCap-int-}
```
public SetLineCap(int cap)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tampa |  |  |

### SetLineCap {#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineCapStyle-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getCap {#getCap--}
```
public final int getCap()
```

Obtém o estilo dos tampas de linha.

**Returns:**
valor int

### setCap {#setCap-int-}
```
public final void setCap(int value)
```

Define o estilo dos tampas de linha.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
