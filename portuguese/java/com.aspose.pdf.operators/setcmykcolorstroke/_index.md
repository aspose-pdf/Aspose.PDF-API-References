---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador K (define a cor CMYK para operações de contorno)."
type: docs
weight: 540
url: /pt/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

Classe que representa o operador K (define a cor CMYK para operações de contorno).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Inicializa o operador. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getC](#getC--) | Obtém ou define o componente ciano. |
| [getColor](#getColor--) | Retorna a cor RGB |
| [getK](#getK--) | Obtém ou define o componente preto. |
| [getM](#getM--) | Obtém ou define o componente magenta. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Obtém ou define o componente amarelo. |
| [setC](#setC-double-) | Obtém ou define o componente ciano. |
| [setK](#setK-double-) | Obtém ou define o componente preto. |
| [setM](#setM-double-) | Obtém ou define o componente magenta. |
| [setY](#setY-double-) | Obtém ou define o componente amarelo. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Inicializa o operador.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c |  | O nível de ciano de 0.0 a 1.0 |
| m |  | O nível de magenta de 0.0 a 1.0 |
| y |  | O nível de amarelo de 0.0 a 1.0 |
| k |  | O nível de preto de 0.0 a 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getC {#getC--}
```
public final double getC()
```

Obtém ou define o componente ciano.

**Returns:**
valor realizável

### getColor {#getColor--}
```
public Color getColor()
```

Retorna a cor RGB

**Returns:**
Cor especificada pelo operador.

### getK {#getK--}
```
public final double getK()
```

Obtém ou define o componente preto.

**Returns:**
valor realizável

### getM {#getM--}
```
public final double getM()
```

Obtém ou define o componente magenta.

**Returns:**
valor realizável

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Obtém ou define o componente amarelo.

**Returns:**
valor realizável

### setC {#setC-double-}
```
public final void setC(double value)
```

Obtém ou define o componente ciano.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |

### setK {#setK-double-}
```
public final void setK(double value)
```

Obtém ou define o componente preto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |

### setM {#setM-double-}
```
public final void setM(double value)
```

Obtém ou define o componente magenta.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |

### setY {#setY-double-}
```
public final void setY(double value)
```

Obtém ou define o componente amarelo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor realizável |
