---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El tipo SaveOptions mantiene el nivel de abstracción sobre opciones de guardado individuales."
type: docs
weight: 4370
url: /es/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

El tipo SaveOptions mantiene el nivel de abstracción sobre opciones de guardado individuales.

## Métodos

| Método | Descripción |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Formato de guardado de datos. |
| [getWarningHandler](#getWarningHandler--) | Función de devolución de llamada para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa; sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse. |
| [isCacheGlyphs](#isCacheGlyphs--) | Obtiene o establece el valor booleano que indica si los glifos de fuente se almacenarán en caché mientras se preparan las páginas APS. Mejora el rendimiento de la conversión de PDF a otros formatos pero incrementa el consumo de memoria. |
| [isCloseResponse](#isCloseResponse--) | Obtiene el valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Obtiene o establece el valor booleano que indica si los glifos de fuente se almacenarán en caché mientras se preparan las páginas APS. Mejora el rendimiento de la conversión de PDF a otros formatos pero incrementa el consumo de memoria. |
| [setCloseResponse](#setCloseResponse-boolean-) | Establece el valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Función de devolución de llamada para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa; sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Formato de guardado de datos.

**Returns:**
Valor SaveFormat @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Función de devolución de llamada para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa; sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse.

**Returns:**
Valor IWarningCallback

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Obtiene o establece el valor booleano que indica si los glifos de fuente se almacenarán en caché mientras se preparan las páginas APS. Mejora el rendimiento de la conversión de PDF a otros formatos pero incrementa el consumo de memoria.

**Returns:**
valor booleano

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Obtiene el valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta.

**Returns:**
valor booleano

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Obtiene o establece el valor booleano que indica si los glifos de fuente se almacenarán en caché mientras se preparan las páginas APS. Mejora el rendimiento de la conversión de PDF a otros formatos pero incrementa el consumo de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Establece el valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Función de devolución de llamada para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de Guardado continúa; sin embargo, el usuario también puede devolver Abort, en cuyo caso la operación de Guardado debe detenerse.
