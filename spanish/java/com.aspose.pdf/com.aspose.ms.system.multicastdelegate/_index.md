---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa eventos"
type: docs
weight: 740
url: /es/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Clase que representa eventos

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-T-) | Agregar un delegado más. |
| [assign](#assign-T-) | Agregar solo el delegado actual, borrando los demás. |
| [clear](#clear--) | Borrar lista de delegados |
| [isEmpty](#isEmpty--) | Devuelve true si la lista de controladores está vacía |
| [remove](#remove-T-) | Eliminar delegado de la lista |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Agregar un delegado más.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| delegado |  | Objeto Handlers |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Agregar solo el delegado actual, borrando los demás.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| delegado |  | Objeto Handlers |

### clear {#clear--}
```
public final void clear()
```

Borrar lista de delegados

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Devuelve true si la lista de controladores está vacía

**Returns:**
valor booleano

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Eliminar delegado de la lista

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| delegado |  | Objeto Handlers |
