---
title: "SaveOptions.MarginPartStyle"
linktitle: "SaveOptions.MarginPartStyle"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa información de una parte del margen (superior, inferior, lado izquierdo o derecho)."
type: docs
weight: 4420
url: /es/java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

Representa información de una parte del margen (superior, inferior, lado izquierdo o derecho).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | Crea una instancia de la clase MarginPartStyle y inicializa su valor en puntos |
| [MarginPartStyle](#MarginPartStyle-int-) | Crea una instancia de la clase MarginPartStyle y establece su valor en puntos |

## Métodos

| Método | Descripción |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | Representa el margen en puntos. Debe ser un número mayor que cero. |
| [isAuto](#isAuto--) | Obtiene o establece un valor que indica si esta instancia es automática. Valor: {@code true} si esta instancia es automática; de lo contrario, {@code false}. |
| [setAuto](#setAuto-boolean-) | Obtiene o establece un valor que indica si esta instancia es automática. Valor: {@code true} si esta instancia es automática; de lo contrario, {@code false}. |
| [setValueInPoints](#setValueInPoints-int-) | Representa el margen en puntos. Debe ser un número mayor que cero. |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

Crea una instancia de la clase MarginPartStyle y inicializa su valor en puntos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isAuto |  | Marcar margen automático |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

Crea una instancia de la clase MarginPartStyle y establece su valor en puntos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valueInPoints |  | Valor entero en puntos |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

Representa el margen en puntos. Debe ser un número mayor que cero.

**Returns:**
valor int

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

Obtiene o establece un valor que indica si esta instancia es automática. Valor: {@code true} si esta instancia es automática; de lo contrario, {@code false}.

**Returns:**
valor booleano

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

Obtiene o establece un valor que indica si esta instancia es automática. Valor: {@code true} si esta instancia es automática; de lo contrario, {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

Representa el margen en puntos. Debe ser un número mayor que cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
