---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o nível de cinza para operações de traçado."
type: docs
weight: 650
url: /pt/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Classe que representa o nível de cinza para operações de traçado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Inicializa o operador com a cor especificada. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getColor](#getColor--) | Retorna a cor especificada pelo operador. |
| [getGray](#getGray--) | Obtém ou define o nível de valor de cinza. |
| [setGray](#setGray-double-) | Obtém ou define o nível de valor de cinza. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Inicializa o operador com a cor especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cinza |  | O nível de valor de cinza. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getColor {#getColor--}
```
public Color getColor()
```

Retorna a cor especificada pelo operador.

**Returns:**
Cor especificada pelo operador.

### getGray {#getGray--}
```
public final double getGray()
```

Obtém ou define o nível de valor de cinza.

**Returns:**
valor double

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Obtém ou define o nível de valor de cinza.

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
