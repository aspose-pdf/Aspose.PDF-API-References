---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa el borde para elementos gráficos."
type: docs
weight: 370
url: /es/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Esta clase representa el borde para elementos gráficos.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Inicializa una nueva instancia de la clase {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | Inicializa una nueva instancia de la clase {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Inicializa una nueva instancia de la clase {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | Inicializa una nueva instancia de la clase {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Inicializa una nueva instancia de la clase {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Inicializa una nueva instancia de la clase {@code BorderInfo}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona un nuevo objeto BorderInfo. |
| [getBottom](#getBottom--) | Obtiene el objeto que indica la parte inferior del borde. |
| [getLeft](#getLeft--) | Obtiene el objeto {@code GraphInfo} que indica la izquierda del borde. |
| [getRight](#getRight--) | Obtiene el objeto {@code GraphInfo} que indica la derecha del borde. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Obtiene el radio redondeado del borde. |
| [getTop](#getTop--) | Obtiene el objeto {@code GraphInfo} que indica la parte superior del borde. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Establece el objeto que indica la parte inferior del borde. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Establece el objeto {@code GraphInfo} que indica la izquierda del borde. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Establece el objeto {@code GraphInfo} que indica la derecha del borde. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Establece el radio redondeado del borde. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Establece el objeto {@code GraphInfo} que indica la parte superior del borde. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Inicializa una nueva instancia de la clase {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Inicializa una nueva instancia de la clase {@code BorderInfo}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| borderSide |  | Indica la información de los lados del borde. Por ejemplo: (BorderSide.Left \\ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Inicializa una nueva instancia de la clase {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Inicializa una nueva instancia de la clase {@code BorderInfo}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| borderSide |  | Indica la información de los lados del borde. Por ejemplo: (BorderSide.Left \\ | BorderSide.Top). |
| borderWidth |  | El ancho del borde. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Inicializa una nueva instancia de la clase {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Inicializa una nueva instancia de la clase {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona un nuevo objeto BorderInfo.

**Returns:**
El nuevo objeto BorderInfo.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Obtiene el objeto que indica la parte inferior del borde.

**Returns:**
inferior

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Obtiene el objeto {@code GraphInfo} que indica la izquierda del borde.

**Returns:**
objeto que indica el lado izquierdo del borde.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Obtiene el objeto {@code GraphInfo} que indica la derecha del borde.

**Returns:**
objeto que indica el lado derecho del borde.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Obtiene el radio redondeado del borde.

**Returns:**
valor

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Obtiene el objeto {@code GraphInfo} que indica la parte superior del borde.

**Returns:**
objeto que indica el borde superior

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Establece el objeto que indica la parte inferior del borde.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Establece el objeto {@code GraphInfo} que indica la izquierda del borde.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Establece el objeto {@code GraphInfo} que indica la derecha del borde.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Establece el radio redondeado del borde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Establece el objeto {@code GraphInfo} que indica la parte superior del borde.
