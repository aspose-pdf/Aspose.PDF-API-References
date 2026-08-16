---
title: "TabStop"
linktitle: "TabStop"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una posición personalizada de parada de pestaña en un párrafo."
type: docs
weight: 4840
url: /es/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Representa una posición personalizada de parada de pestaña en un párrafo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TabStop](#TabStop--) | Inicializa una nueva instancia de la clase {@code TabStop}. |
| [TabStop](#TabStop-float-) | Inicializa una nueva instancia de la clase {@code TabStop} con la posición especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Obtiene o establece una enumeración {@code AlignmentType} que indica el tipo de alineación de la tabulación. |
| [getLeaderType](#getLeaderType--) | Obtiene o establece una enumeración {@code TabLeaderType} que indica el tipo de líder de tabulación. |
| [getPosition](#getPosition--) | Obtiene o establece un valor flotante que indica la posición del tabulador. |
| [isReadOnly](#isReadOnly--) | Obtiene el valor que indica que esta instancia {@code TabStop} ya está adjunta a {@code TextFragment} y se volvió de solo lectura. |
| [setAlignmentType](#setAlignmentType-int-) | Obtiene o establece una enumeración {@code AlignmentType} que indica el tipo de alineación de la tabulación. |
| [setLeaderType](#setLeaderType-int-) | Obtiene o establece una enumeración {@code TabLeaderType} que indica el tipo de líder de tabulación. |
| [setPosition](#setPosition-float-) | Establece un valor flotante que indica la posición del tabulador. |

### TabStop {#TabStop--}
```
public TabStop()
```

Inicializa una nueva instancia de la clase {@code TabStop}.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Inicializa una nueva instancia de la clase {@code TabStop} con la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posición |  | La posición del tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Obtiene o establece una enumeración {@code AlignmentType} que indica el tipo de alineación de la tabulación.

**Returns:**
Elemento TabAlignmentType @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Obtiene o establece una enumeración {@code TabLeaderType} que indica el tipo de líder de tabulación.

**Returns:**
Elemento TabLeaderType @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Obtiene o establece un valor flotante que indica la posición del tabulador.

**Returns:**
valor flotante

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene el valor que indica que esta instancia {@code TabStop} ya está adjunta a {@code TextFragment} y se volvió de solo lectura.

**Returns:**
valor booleano

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Obtiene o establece una enumeración {@code AlignmentType} que indica el tipo de alineación de la tabulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento TabAlignmentType @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Obtiene o establece una enumeración {@code TabLeaderType} que indica el tipo de líder de tabulación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento TabLeaderType @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Establece un valor flotante que indica la posición del tabulador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |
