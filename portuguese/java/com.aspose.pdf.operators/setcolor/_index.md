---
title: "SetColor"
linktitle: "SetColor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe para o operador sc (define a cor para operações sem contorno)."
type: docs
weight: 550
url: /pt/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

Representa a classe para o operador sc (define a cor para operações sem contorno).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetColor](#SetColor--) | Inicializa o operador. |
| [SetColor](#SetColor-double-) | Definir cor para operadores de traçado para os espaços de cor DeviceGray, CalGray e Indexed. |
| [SetColor](#SetColor-double:A-) | Construtor que permite especificar os componentes de cor. |
| [SetColor](#SetColor-double-double-double-) | Definir cor para operador de traçado para os espaços de cor DeviceRGB, CalRGB e Lab. |
| [SetColor](#SetColor-double-double-double-double-) | Define a cor para operador não de traçado no espaço de cor CMYK |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | Inicializa o operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getB](#getB--) | Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0. |
| [getC](#getC--) | Obtém ou define o componente ciano. |
| [getColor](#getColor--) | Ainda não suportado. Retorna a cor especificada pelo operador. |
| [getG](#getG--) | Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0. |
| [getK](#getK--) | Obtém ou define o componente preto. |
| [getM](#getM--) | Obtém ou define o componente magenta. |
| [getR](#getR--) | Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0. |
| [getY](#getY--) | Obtém ou define o componente amarelo. |
| [setB](#setB-double-) | Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0. |
| [setC](#setC-double-) | Obtém ou define o componente ciano. |
| [setG](#setG-double-) | Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0. |
| [setK](#setK-double-) | Obtém ou define o componente preto. |
| [setM](#setM-double-) | Obtém ou define o componente magenta. |
| [setR](#setR-double-) | Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0. |
| [setY](#setY-double-) | Obtém ou define o componente amarelo. |
| [toString](#toString--) | Retorna a representação em string da cor. |

### SetColor {#SetColor--}
```
public SetColor()
```

Inicializa o operador.

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

Definir cor para operadores de traçado para os espaços de cor DeviceGray, CalGray e Indexed.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| g |  | Valor da cor. |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

Construtor que permite especificar os componentes de cor.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cor |  | Matriz de componentes de cor. |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

Definir cor para operador de traçado para os espaços de cor DeviceRGB, CalRGB e Lab.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| r |  | Componente vermelho. |
| g |  | Componente verde. |
| b |  | Componente azul. |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

Define a cor para operador não de traçado no espaço de cor CMYK

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| c |  | Componente ciano. |
| m |  | Componente magenta. |
| y |  | Componente amarelo. |
| k |  | Componente preto. |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
Inicializa o operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getB {#getB--}
```
public final double getB()
```

Obtém ou define o componente azul. Valor: O nível de azul de 0.0 a 1.0.

**Returns:**
valor realizável

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

Ainda não suportado. Retorna a cor especificada pelo operador.

**Returns:**
Cor do operador.

### getG {#getG--}
```
public final double getG()
```

Obtém ou define o componente verde. Valor: O nível de verde de 0.0 a 1.0.

**Returns:**
valor realizável

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

### getR {#getR--}
```
public final double getR()
```

Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0.

**Returns:**
valor realizável

### getY {#getY--}
```
public final double getY()
```

Obtém ou define o componente amarelo.

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

### setC {#setC-double-}
```
public final void setC(double value)
```

Obtém ou define o componente ciano.

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

### setR {#setR-double-}
```
public final void setR(double value)
```

Obtém ou define o componente vermelho. Valor: O nível de vermelho de 0.0 a 1.0.

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

### toString {#toString--}
```
public String toString()
```

Retorna a representação em string da cor.

**Returns:**
Representação em string da cor.
