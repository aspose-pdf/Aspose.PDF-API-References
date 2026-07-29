---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El tipo LoadOptions mantiene un nivel de abstracción en opciones de carga individuales."
type: docs
weight: 2790
url: /es/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

El tipo LoadOptions mantiene un nivel de abstracción en opciones de carga individuales.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Representa el formato de archivo que {@code LoadOptions} describe. |
| [getWarningHandler](#getWarningHandler--) | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de carga debe detenerse. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Obtiene o establece la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando {@code }, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación de esa fuente. Por defecto {@code }. Tenga cuidado al usar esta bandera. Cuando está establecida significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Obtiene o establece la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando {@code }, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación de esa fuente. Por defecto {@code }. Tenga cuidado al usar esta bandera. Cuando está establecida significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de carga debe detenerse. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Representa el formato de archivo que {@code LoadOptions} describe.

**Returns:**
Elemento LoadFormat @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de carga debe detenerse.

**Returns:**
Valor IWarningCallback

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Obtiene o establece la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando {@code }, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación de esa fuente. Por defecto {@code }. Tenga cuidado al usar esta bandera. Cuando está establecida significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor.

**Returns:**
valor booleano

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Obtiene o establece la bandera para desactivar cualquier restricción de licencia para todas las fuentes al cargar el archivo. Cuando {@code }, permite ejecutar operaciones con una fuente que están prohibidas por la licencia de esa fuente, por ejemplo permite incrustar una fuente en un documento PDF incluso si las reglas de licencia deshabilitan la incrustación de esa fuente. Por defecto {@code }. Tenga cuidado al usar esta bandera. Cuando está establecida significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback para manejar cualquier advertencia generada. El WarningHandler devuelve el elemento de enumeración ReturnAction que especifica Continuar o Abort. Continuar es la acción predeterminada y la operación de carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de carga debe detenerse.
