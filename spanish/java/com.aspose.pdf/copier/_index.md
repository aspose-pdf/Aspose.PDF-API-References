---
title: "Copier"
linktitle: "Copier"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para copiar objetos."
type: docs
weight: 850
url: /es/java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

Clase para copiar objetos.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Crea una instancia de la clase Copier. |

## Métodos

| Método | Descripción |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Duplica IPdfPrimitive |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Crea una copia del objeto con todos los objetos dependientes. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | obtener Allow Reuse Page Content |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | obtener Ignore Corrupted Objects |
| [getRestrictedKeys](#getRestrictedKeys--) | obtener Restricted Keys |
| [getReuseStreams](#getReuseStreams--) | obtener Reuse Streams |
| [getUseStubs](#getUseStubs--) | Indica si se deben usar stubs durante el proceso de duplicación. Si la opción está activada, los streams se copiarán; de lo contrario, se utilizará un enlace al stream de origen. Esto no permitirá cerrar el documento copiado, pero ahorra en el proceso de copia y en la memoria. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | establecer Allow Reuse Page Content |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Establecer Ignore Corrupted Objects |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | establecer Restricted Keys |
| [setReuseStreams](#setReuseStreams-boolean-) | establecer Reuse Streams |
| [setUseStubs](#setUseStubs-boolean-) | Indica si se deben usar stubs durante el proceso de duplicación. Si la opción está activada, los streams se copiarán; de lo contrario, se utilizará un enlace al stream de origen. Esto no permitirá cerrar el documento copiado, pero ahorra en el proceso de copia y en la memoria. |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
Crea una instancia de la clase Copier.

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
Duplica IPdfPrimitive

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
Crea una copia del objeto con todos los objetos dependientes.

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

obtener Allow Reuse Page Content

**Returns:**
valor booleano

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

obtener Ignore Corrupted Objects

**Returns:**
valor booleano

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

obtener Restricted Keys

**Returns:**
String[] array

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

obtener Reuse Streams

**Returns:**
valor booleano

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

Indica si se deben usar stubs durante el proceso de duplicación. Si la opción está activada, los streams se copiarán; de lo contrario, se utilizará un enlace al stream de origen. Esto no permitirá cerrar el documento copiado, pero ahorra en el proceso de copia y en la memoria.

**Returns:**
valor booleano

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

establecer Allow Reuse Page Content

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Establecer Ignore Corrupted Objects

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
establecer Restricted Keys

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

establecer Reuse Streams

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

Indica si se deben usar stubs durante el proceso de duplicación. Si la opción está activada, los streams se copiarán; de lo contrario, se utilizará un enlace al stream de origen. Esto no permitirá cerrar el documento copiado, pero ahorra en el proceso de copia y en la memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
