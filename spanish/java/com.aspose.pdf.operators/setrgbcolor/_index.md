---
title: "SetRGBColor"
linktitle: "SetRGBColor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador rg (establece el color RGB para operadores sin trazo)."
type: docs
weight: 710
url: /es/java/com.aspose.pdf.operators/setrgbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColor

```
public class SetRGBColor extends SetColorOperator
```

Clase que representa el operador rg (establece el color RGB para operadores sin trazo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetRGBColor](#SetRGBColor-java.awt.Color-) | Inicializa el operador con color. |
| [SetRGBColor](#SetRGBColor-double-double-double-) | Constructor para programa de escritura. |
| [SetRGBColor](#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-) | Constructor de la clase operador. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getB](#getB--) | Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0. |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Devuelve el color especificado por el operador. |
| [getG](#getG--) | Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0. |
| [getR](#getR--) | Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0. |
| [setB](#setB-double-) | Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0. |
| [setG](#setG-double-) | Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0. |
| [setR](#setR-double-) | Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0. |
| [toString](#toString--) | Devuelve la representación textual del operador. |

### SetRGBColor {#SetRGBColor-java.awt.Color-}
Inicializa el operador con color.

### SetRGBColor {#SetRGBColor-double-double-double-}
```
public SetRGBColor(double r, double g, double b)
```

Constructor para programa de escritura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r |  | El nivel de rojo de 0.0 a 1.0 |
| g |  | El nivel de verde de 0.0 a 1.0 |
| b |  | El nivel de azul de 0.0 a 1.0 |

### SetRGBColor {#SetRGBColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBNonstrokingColor-}
Constructor de la clase operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

### getB {#getB--}
```
public final double getB()
```

Obtiene o establece el componente azul. Valor: El nivel de azul de 0.0 a 1.0.

**Returns:**
valor realizable

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

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

### getR {#getR--}
```
public final double getR()
```

Obtiene o establece el componente rojo. Valor: El nivel de rojo de 0.0 a 1.0.

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

### setG {#setG-double-}
```
public final void setG(double value)
```

Obtiene o establece el componente verde. Valor: El nivel de verde de 0.0 a 1.0.

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

### toString {#toString--}
```
public String toString()
```

Devuelve la representación textual del operador.

**Returns:**
Representación textual del operador.
