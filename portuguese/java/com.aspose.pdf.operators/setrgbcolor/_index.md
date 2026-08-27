---
title: "SetRGBColor"
linktitle: "SetRGBColor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador rg (define a cor RGB para operadores sem traçado)."
type: docs
weight: 710
url: /pt/java/com.aspose.pdf.operators/setrgbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColor

```
public class SetRGBColor extends SetColorOperator
```

Classe que representa o operador rg (define a cor RGB para operadores sem traçado).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetRGBColor](#SetRGBColor-java.awt.Color-) | Inicializa o operador com cor. |
| [SetRGBColor](#SetRGBColor-double-double-double-) | Construtor para programa de escrita. |
| [SetRGBColor](#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-) | Construtor da classe operador. |

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

### SetRGBColor {#SetRGBColor-java.awt.Color-}
Inicializa o operador com cor.

### SetRGBColor {#SetRGBColor-double-double-double-}
```
public SetRGBColor(double r, double g, double b)
```

Construtor para programa de escrita.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| r |  | O nível de vermelho de 0.0 a 1.0 |
| g |  | O nível de verde de 0.0 a 1.0 |
| b |  | O nível de azul de 0.0 a 1.0 |

### SetRGBColor {#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-}
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
