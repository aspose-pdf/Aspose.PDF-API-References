---
title: "SetGray"
linktitle: "SetGray"
second_title: "Referência da API Aspose.PDF para Java"
description: "Define o nível de cinza para operações sem traçado."
type: docs
weight: 640
url: /pt/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Define o nível de cinza para operações sem traçado.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetGray](#SetGray-double-) | Construtor para programa de escrita. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getColor](#getColor--) | Retorna a cor especificada pelo operador. |
| [getGray](#getGray--) | Obtém ou define o nível de valor de cinza. |
| [setGray](#setGray-double-) | Obtém ou define o nível de valor de cinza. |
| [toString](#toString--) | Retorna a representação em string do operador. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Construtor para programa de escrita.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cinza |  | O nível de valor de cinza. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
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

Retorna a representação em string do operador.

**Returns:**
Representação em string do operador.
