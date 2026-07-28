---
title: "Guion"
linktitle: "Guion"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa el patrón de guiones de línea."
type: docs
weight: 910
url: /es/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Clase que representa el patrón de guiones de línea.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Dash](#Dash-int:A-) | Constructor de Dash. Define un patrón de guiones y espacios que se utilizará al dibujar un borde discontinuo. |
| [Dash](#Dash-int-int-) | Constructor de Dash. Define un borde discontinuo con el guion y el espacio especificados, que permanecen sin cambios en todo el borde discontinuo. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getOff](#getOff--) | Obtiene o establece la longitud del primer espacio entre guiones. |
| [getOn](#getOn--) | Obtiene o establece la longitud del primer guion. |
| [getPattern](#getPattern--) | Obtiene la matriz de guiones que define un patrón de guiones y espacios que se utilizará al dibujar un borde discontinuo. |
| [setOff](#setOff-int-) | Obtiene o establece la longitud del primer espacio entre guiones. |
| [setOn](#setOn-int-) | Obtiene o establece la longitud del primer guion. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Constructor de Dash. Define un patrón de guiones y espacios que se utilizará al dibujar un borde discontinuo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| patrón |  | Una matriz de guiones (de al menos dos valores) que define un patrón de guiones y espacios que se utilizará al dibujar un borde discontinuo. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Constructor de Dash. Define un borde discontinuo con el guion y el espacio especificados, que permanecen sin cambios en todo el borde discontinuo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| activado |  | Longitud del guion. |
| desactivado |  | Longitud del espacio. |

### getOff {#getOff--}
```
public final int getOff()
```

Obtiene o establece la longitud del primer espacio entre guiones.

**Returns:**
valor int

### getOn {#getOn--}
```
public final int getOn()
```

Obtiene o establece la longitud del primer guion.

**Returns:**
valor int

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Obtiene la matriz de guiones que define un patrón de guiones y espacios que se utilizará al dibujar un borde discontinuo.

**Returns:**
matriz de int

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Obtiene o establece la longitud del primer espacio entre guiones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Obtiene o establece la longitud del primer guion.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
