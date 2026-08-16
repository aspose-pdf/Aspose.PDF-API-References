---
title: "SetCMYKColor"
linktitle: "SetCMYKColor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el operador k (establecer el color CMYK para operaciones sin trazo)."
type: docs
weight: 530
url: /es/java/com.aspose.pdf.operators/setcmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColor

```
public class SetCMYKColor extends SetColorOperator
```

Clase que representa el operador k (establecer el color CMYK para operaciones sin trazo).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SetCMYKColor](#SetCMYKColor-double-double-double-double-) | Inicializa el operador. |
| [SetCMYKColor](#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Acepta un objeto visitante para procesar el operador. |
| [getC](#getC--) | Obtiene o establece el componente cian. |
| [getColor](#getColor--) | Devuelve el color. |
| [getK](#getK--) | Obtiene o establece el componente negro. |
| [getM](#getM--) | Obtiene o establece el componente magenta. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Obtiene o establece el componente amarillo. |
| [setC](#setC-double-) | Obtiene o establece el componente cian. |
| [setK](#setK-double-) | Obtiene o establece el componente negro. |
| [setM](#setM-double-) | Obtiene o establece el componente magenta. |
| [setY](#setY-double-) | Obtiene o establece el componente amarillo. |

### SetCMYKColor {#SetCMYKColor-double-double-double-double-}
```
public SetCMYKColor(double c, double m, double y, double k)
```

Inicializa el operador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c |  | El nivel de cian de 0.0 a 1.0 |
| m |  | El nivel de magenta de 0.0 a 1.0 |
| y |  | El nivel de amarillo de 0.0 a 1.0 |
| k |  | El nivel de negro de 0.0 a 1.0 |

### SetCMYKColor {#SetCMYKColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKNonstrokingColor-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Acepta un objeto visitante para procesar el operador.

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

Devuelve el color.

**Returns:**
Color especificado por el operador.

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Obtiene o establece el componente amarillo.

**Returns:**
valor realizable

### setC {#setC-double-}
```
public final void setC(double value)
```

Obtiene o establece el componente cian.

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

### setY {#setY-double-}
```
public final void setY(double value)
```

Obtiene o establece el componente amarillo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor realizable |
