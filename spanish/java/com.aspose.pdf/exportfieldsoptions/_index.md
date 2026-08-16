---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase base de opciones para exportar campos de formulario."
type: docs
weight: 1310
url: /es/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Representa la clase base de opciones para exportar campos de formulario.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Obtiene o establece un valor que indica si el valor de la contraseña debe exportarse. Valor: {@code true} si el valor de la contraseña debe exportarse; de lo contrario, {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Obtiene un delegado que determina si un campo particular debe exportarse. Si el delegado es {@code null}, todos los campos se exportan (comportamiento predeterminado). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Obtiene o establece un valor que indica si el valor de la contraseña debe exportarse. Valor: {@code true} si el valor de la contraseña debe exportarse; de lo contrario, {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Establece un delegado que determina si un campo particular debe exportarse. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Obtiene o establece un valor que indica si el valor de la contraseña debe exportarse. Valor: {@code true} si el valor de la contraseña debe exportarse; de lo contrario, {@code false}.

**Returns:**
valor booleano

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Obtiene un delegado que determina si un campo particular debe exportarse. Si el delegado es {@code null}, todos los campos se exportan (comportamiento predeterminado).

**Returns:**
un delegado que determina si un campo particular debe exportarse.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Obtiene o establece un valor que indica si el valor de la contraseña debe exportarse. Valor: {@code true} si el valor de la contraseña debe exportarse; de lo contrario, {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Establece un delegado que determina si un campo particular debe exportarse.
