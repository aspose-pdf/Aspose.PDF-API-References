---
title: "Sello"
linktitle: "Sello"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase abstracta para varios tipos de sellos que aparecen como descendientes."
type: docs
weight: 4620
url: /es/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Una clase abstracta para varios tipos de sellos que aparecen como descendientes.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Obtiene el margen inferior del sello. |
| [getHeight](#getHeight--) | Obtiene la altura deseada del sello en la página. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene la alineación horizontal del sello en la página. |
| [getLeftMargin](#getLeftMargin--) | Obtiene el margen izquierdo del sello. |
| [getOpacity](#getOpacity--) | Obtiene un valor que indica la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Obtiene un valor que indica la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Obtiene un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [getRightMargin](#getRightMargin--) | Obtiene el margen derecho del sello. |
| [getRotate](#getRotate--) | Obtiene la rotación del contenido del sello según los valores {@code Rotation}. Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90 entonces la propiedad Rotate devuelve Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Obtiene el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [getStampId](#getStampId--) | Obtiene el ID del sello. |
| [getTopMargin](#getTopMargin--) | Obtiene el margen superior del sello. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene la alineación vertical del sello en la página. |
| [getWidth](#getWidth--) | Obtiene el ancho deseado del sello en la página. |
| [getXIndent](#getXIndent--) | Obtiene la coordenada horizontal del sello, comenzando desde la izquierda. |
| [getYIndent](#getYIndent--) | Obtiene la coordenada vertical del sello, comenzando desde la parte inferior. |
| [getZoom](#getZoom--) | Obtiene el factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. Configurar esta propiedad cambia ambas propiedades ZoomX y ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX. |
| [getZoomX](#getZoomX--) | Obtiene el factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [getZoomY](#getZoomY--) | Obtiene el factor de zoom vertical del sello. Permite escalar el sello verticalmente. |
| [isBackground](#isBackground--) | Obtiene un valor bool que indica que el contenido está estampado como fondo. Si el valor es true, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es false, el contenido del sello se coloca en la parte superior. |
| [put](#put-com.aspose.pdf.Page-) | Agrega un sello en la página. |
| [setBackground](#setBackground-boolean-) | Establece un valor bool que indica que el contenido está estampado como fondo. Si el valor es true, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es false, el contenido del sello se coloca en la parte superior. |
| [setBottomMargin](#setBottomMargin-double-) | Establece el margen inferior del sello. |
| [setHeight](#setHeight-double-) | Establece la altura deseada del sello en la página. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación horizontal del sello en la página. |
| [setLeftMargin](#setLeftMargin-double-) | Establece el margen izquierdo del sello. |
| [setOpacity](#setOpacity-double-) | Establece un valor para indicar la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Establece un valor para indicar la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [setRightMargin](#setRightMargin-double-) | Establece el margen derecho del sello. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Establece la rotación del contenido del sello según los valores {@code Rotation}. Nota: Esta propiedad es para ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, entonces la propiedad Rotate devuelve Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [setStampId](#setStampId-int-) | Establece el Id del sello. |
| [setTopMargin](#setTopMargin-double-) | Establece el margen superior del sello. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece la alineación vertical del sello en la página. |
| [setWidth](#setWidth-double-) | Establece el ancho deseado del sello en la página. |
| [setXIndent](#setXIndent-double-) | Establece la coordenada horizontal del sello, comenzando desde la izquierda. |
| [setYIndent](#setYIndent-double-) | Establece la coordenada vertical del sello, comenzando desde la parte inferior. |
| [setZoom](#setZoom-double-) | Obtiene el factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. Configurar esta propiedad cambia ambas propiedades ZoomX y ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX. |
| [setZoomX](#setZoomX-double-) | Establece el factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [setZoomY](#setZoomY-double-) | Establece el factor de zoom vertical del sello. Permite escalar el sello verticalmente. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Obtiene el margen inferior del sello.

**Returns:**
valor double

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtiene la altura deseada del sello en la página.

**Returns:**
valor double

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtiene la alineación horizontal del sello en la página.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Obtiene el margen izquierdo del sello.

**Returns:**
valor double

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtiene un valor que indica la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0.

**Returns:**
valor double

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Obtiene un valor que indica la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0.

**Returns:**
valor double

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Obtiene un valor del ancho del contorno del sello. Por defecto, el valor es 1.0.

**Returns:**
valor double

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Obtiene el margen derecho del sello.

**Returns:**
valor double

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Obtiene la rotación del contenido del sello según los valores {@code Rotation}. Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90 entonces la propiedad Rotate devuelve Rotation.None.

**Returns:**
Valor de rotación @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Obtiene el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario.

**Returns:**
valor double

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtiene el ID del sello.

**Returns:**
Identificador del sello.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Obtiene el margen superior del sello.

**Returns:**
valor double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtiene la alineación vertical del sello en la página.

**Returns:**
Valor de VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho deseado del sello en la página.

**Returns:**
valor double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtiene la coordenada horizontal del sello, comenzando desde la izquierda.

**Returns:**
valor double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtiene la coordenada vertical del sello, comenzando desde la parte inferior.

**Returns:**
valor double

### getZoom {#getZoom--}
```
public double getZoom()
```

Obtiene el factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. Configurar esta propiedad cambia ambas propiedades ZoomX y ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX.

**Returns:**
valor double

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Obtiene el factor de zoom horizontal del sello. Permite escalar el sello horizontalmente.

**Returns:**
valor double

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Obtiene el factor de zoom vertical del sello. Permite escalar el sello verticalmente.

**Returns:**
valor double

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Obtiene un valor bool que indica que el contenido está estampado como fondo. Si el valor es true, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es false, el contenido del sello se coloca en la parte superior.

**Returns:**
valor booleano

### put {#put-com.aspose.pdf.Page-}
Agrega un sello en la página.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Establece un valor bool que indica que el contenido está estampado como fondo. Si el valor es true, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es false, el contenido del sello se coloca en la parte superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Establece el margen inferior del sello.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Establece la altura deseada del sello en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación horizontal del sello en la página.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Establece el margen izquierdo del sello.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Establece un valor para indicar la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Establece un valor para indicar la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Establece el margen derecho del sello.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Establece la rotación del contenido del sello según los valores {@code Rotation}. Nota: Esta propiedad es para ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, entonces la propiedad Rotate devuelve Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | ángulo de rotación |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Establece el Id del sello.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Nuevo valor del ID del sello. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Establece el margen superior del sello.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece la alineación vertical del sello en la página.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece el ancho deseado del sello en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Establece la coordenada horizontal del sello, comenzando desde la izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Establece la coordenada vertical del sello, comenzando desde la parte inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Obtiene el factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. Configurar esta propiedad cambia ambas propiedades ZoomX y ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Establece el factor de zoom horizontal del sello. Permite escalar el sello horizontalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Establece el factor de zoom vertical del sello. Permite escalar el sello verticalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |
