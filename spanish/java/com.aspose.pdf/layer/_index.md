---
title: "Layer"
linktitle: "Layer"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una capa dentro de una página PDF."
type: docs
weight: 2640
url: /es/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

Representa una capa dentro de una página PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase {@code Layer}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [delete](#delete--) | Elimina la capa actual del documento PDF. |
| [flatten](#flatten-boolean-) | Aplana la capa especificada. |
| [getContents](#getContents--) | <p> Obtiene el contenido de la capa. </p> |
| [getDefaultState](#getDefaultState--) | Obtiene el estado predeterminado de la capa PDF. |
| [getId](#getId--) | Obtiene el id de la capa. |
| [getLocked](#getLocked--) | Obtiene un valor que indica si la capa está bloqueada. |
| [getName](#getName--) | Obtiene el nombre de la capa. |
| [lock](#lock--) | Bloquea la capa. |
| [save](#save-java.io.OutputStream-) | Guarda la capa actual en un documento PDF. |
| [save](#save-java.lang.String-) | Guarda la capa actual en un documento PDF. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | Establece el estado predeterminado de la capa PDF. |
| [unlock](#unlock--) | Desbloquea la capa. |

### Layer {#Layer-java.lang.String-java.lang.String-}
Inicializa una nueva instancia de la clase {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

Elimina la capa actual del documento PDF.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Aplana la capa especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cleanupContentStream |  | Especifica si se deben eliminar los marcadores de grupo de contenido opcional del flujo de contenido. Establecer el parámetro {@code cleanupContentStream} a false acelera el proceso de aplanado. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Obtiene el contenido de la capa. </p>

**Returns:**
objeto {@code List<Operator>}

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

Obtiene el estado predeterminado de la capa PDF.

**Returns:**
el estado predeterminado de la capa PDF.

### getId {#getId--}
```
public String getId()
```

Obtiene el id de la capa.

**Returns:**
valor String

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Obtiene un valor que indica si la capa está bloqueada.

**Returns:**
valor booleano

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre de la capa.

**Returns:**
valor String

### lock {#lock--}
```
public final void lock()
```

Bloquea la capa.

### save {#save-java.io.OutputStream-}
Guarda la capa actual en un documento PDF.

### save {#save-java.lang.String-}
Guarda la capa actual en un documento PDF.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
Establece el estado predeterminado de la capa PDF.

### unlock {#unlock--}
```
public final void unlock()
```

Desbloquea la capa.
