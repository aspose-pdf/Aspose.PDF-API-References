---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador RG (define a cor RGB para operadores de traçado)."
type: docs
weight: 720
url: /pt/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

Classe que representa o operador RG (define a cor RGB para operadores de traçado).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Inicializa o operador com cor. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Construtor para programa de escrita. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getB](#getB--) | Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0. |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Retorna a cor especificada pelo operador. |
| [getG](#getG--) | Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0. |
| [getR](#getR--) | Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0. |
| [setB](#setB-double-) | Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0. |
| [setG](#setG-double-) | Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0. |
| [setR](#setR-double-) | Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0. |
| [toString](#toString--) | Retorna a representação textual do operador. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Inicializa o operador com cor.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Construtor para programa de escrita.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| r |  | O nível de vermelho de 0.0 a 1.0 |
| g |  | O nível de verde de 0.0 a 1.0 |
| b |  | O nível de azul de 0.0 a 1.0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getB {#getB--}
```
public final double getB()
```

Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0.

**Returns:**
valor realizável

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Retorna a cor especificada pelo operador.

**Returns:**
Cor especificada pelo operador.

### getG {#getG--}
```
public final double getG()
```

Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0.

**Returns:**
valor realizável

### getR {#getR--}
```
public final double getR()
```

Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0.

**Returns:**
valor realizável

### setB {#setB-double-}
```
public final void setB(double value)
```

Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |

### setG {#setG-double-}
```
public final void setG(double value)
```

Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |

### setR {#setR-double-}
```
public final void setR(double value)
```

Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual do operador.

**Returns:**
Representação textual do operador.
