---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador SC (establece el color para operadores de color con trazo)."
type: docs
weight: 600
url: /es/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

Clase que representa el operador SC (establece el color para operadores de color con trazo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Inicializa el operador. |
| [SetColorStroke](#SetColorStroke-double-) | Establecer color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed. |
| [SetColorStroke](#SetColorStroke-double:A-) | Constructor que permite establecer componentes de color. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | Establecer color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab. |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | Establecer color para el operador de trazo para el espacio de color CMYK. |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Inicializa el operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getB](#getB--) | Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0. |
| [getC](#getC--) | Obtiene o establece el componente cian. |
| [getColor](#getColor--) | Devuelve el color especificado por el operador. |
| [getG](#getG--) | Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0. |
| [getK](#getK--) | Obtiene o establece el componente negro. |
| [getM](#getM--) | Obtiene o establece el componente magenta. |
| [getR](#getR--) | Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0. |
| [getY](#getY--) | Obtiene o establece el componente amarillo. |
| [setB](#setB-double-) | Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0. |
| [setC](#setC-double-) | Obtiene o establece el componente cian. |
| [setG](#setG-double-) | Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0. |
| [setK](#setK-double-) | Obtiene o establece el componente negro. |
| [setM](#setM-double-) | Obtiene o establece el componente magenta. |
| [setR](#setR-double-) | Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0. |
| [setY](#setY-double-) | Obtiene o establece el componente amarillo. |

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Inicializa el operador.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

Establecer color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g |  | Valor de color. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Constructor que permite establecer componentes de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color |  | Arreglo de componentes de color. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

Establecer color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r |  | Componente rojo. |
| g |  | Componente verde. |
| b |  | Componente azul. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

Establecer color para el operador de trazo para el espacio de color CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c |  | Componente cian. |
| m |  | Componente magenta. |
| y |  | Componente amarillo. |
| k |  | Componente negro. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
Inicializa el operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getB {#getB--}
```
public final double getB()
```

Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0.

**Returns:**
valor realizable

### getC {#getC--}
```
public final double getC()
```

Obtiene o establece el componente cian.

**Returns:**
valor realizable

### getColor {#getColor--}
```
public Color getColor()
```

Devuelve el color especificado por el operador.

**Returns:**
Color especificado por el operador.

### getG {#getG--}
```
public final double getG()
```

Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0.

**Returns:**
valor realizable

### getK {#getK--}
```
public final double getK()
```

Obtiene o establece el componente negro.

**Returns:**
valor realizable

### getM {#getM--}
```
public final double getM()
```

Obtiene o establece el componente magenta.

**Returns:**
valor realizable

### getR {#getR--}
```
public final double getR()
```

Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0.

**Returns:**
valor realizable

### getY {#getY--}
```
public final double getY()
```

Obtiene o establece el componente amarillo.

**Returns:**
valor realizable

### setB {#setB-double-}
```
public final void setB(double value)
```

Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |

### setC {#setC-double-}
```
public final void setC(double value)
```

Obtiene o establece el componente cian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |

### setG {#setG-double-}
```
public final void setG(double value)
```

Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setK {#setK-double-}
```
public final void setK(double value)
```

Obtiene o establece el componente negro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |

### setM {#setM-double-}
```
public final void setM(double value)
```

Obtiene o establece el componente magenta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |

### setR {#setR-double-}
```
public final void setR(double value)
```

Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |

### setY {#setY-double-}
```
public final void setY(double value)
```

Obtiene o establece el componente amarillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |
