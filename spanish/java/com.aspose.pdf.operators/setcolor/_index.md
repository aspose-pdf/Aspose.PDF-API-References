---
title: "SetColor"
linktitle: "SetColor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase para el operador sc (establecer el color para operaciones sin trazo)."
type: docs
weight: 550
url: /es/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

Representa la clase para el operador sc (establecer el color para operaciones sin trazo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetColor](#SetColor--) | Inicializa el operador. |
| [SetColor](#SetColor-double-) | Establecer color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed. |
| [SetColor](#SetColor-double:A-) | Constructor que permite especificar los componentes de color. |
| [SetColor](#SetColor-double-double-double-) | Establecer color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab. |
| [SetColor](#SetColor-double-double-double-double-) | Establecer color para el operador sin trazo en espacio de color CMYK |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | Inicializa el operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getB](#getB--) | Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0. |
| [getC](#getC--) | Obtiene o establece el componente cian. |
| [getColor](#getColor--) | Aún no soportado. Devuelve el color especificado por el operador. |
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
| [toString](#toString--) | Devuelve la representación en cadena del color. |

### SetColor {#SetColor--}
```
public SetColor()
```

Inicializa el operador.

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

Establecer color para los operadores de trazo para los espacios de color DeviceGray, CalGray e Indexed.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| g |  | Valor de color. |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

Constructor que permite especificar los componentes de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color |  | Arreglo de componentes de color. |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

Establecer color para el operador de trazo para los espacios de color DeviceRGB, CalRGB y Lab.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r |  | Componente rojo. |
| g |  | Componente verde. |
| b |  | Componente azul. |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

Establecer color para el operador sin trazo en espacio de color CMYK

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c |  | Componente cian. |
| m |  | Componente magenta. |
| y |  | Componente amarillo. |
| k |  | Componente negro. |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
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

Aún no soportado. Devuelve el color especificado por el operador.

**Returns:**
Color del operador.

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
| valor |  | valor realizable |

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

### toString {#toString--}
```
public String toString()
```

Devuelve la representación en cadena del color.

**Returns:**
Representación en cadena del color.
