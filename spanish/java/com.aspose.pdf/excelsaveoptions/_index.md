---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato Excel"
type: docs
weight: 1260
url: /es/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Opciones de guardado para exportar al formato Excel

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Obtiene o establece el factor que se aplicará al tamaño de fuente de escala (virtual) durante la conversión a tabla de Excel en / * motor heredado. Establecer un valor menor facilita la búsqueda de columnas y evita su fusión en algunos / * documentos. Valor predeterminado es 0.9; Establecer el valor a cero permite que el algoritmo elija la escala automáticamente. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Establezca true si necesita minimizar el número de hojas de cálculo en el libro de trabajo resultante. El valor predeterminado es false; significa guardar cada página PDF como hoja de cálculo separada. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Establezca false si necesita suprimir la inserción de una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es true; significa que se insertará una columna en blanco. |
| [isUniformWorksheets](#isUniformWorksheets--) | Establezca true para usar una división uniforme de columnas en todo el documento. El valor predeterminado es false; significa que la división de columnas será independiente para cada página. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Formato de salida |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Establezca false si necesita suprimir la inserción de una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es true; significa que se insertará una columna en blanco. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Establezca true si necesita minimizar el número de hojas de cálculo en el libro de trabajo resultante. El valor predeterminado es false; significa guardar cada página PDF como hoja de cálculo separada. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Define el motor de conversión que se utilizará para la conversión |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Constructor

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Obtiene o establece el factor que se aplicará al tamaño de fuente de escala (virtual) durante la conversión a tabla de Excel en / * motor heredado. Establecer un valor menor facilita la búsqueda de columnas y evita su fusión en algunos / * documentos. Valor predeterminado es 0.9; Establecer el valor a cero permite que el algoritmo elija la escala automáticamente. / * / * / *

**Returns:**
valor double /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Establezca true si necesita minimizar el número de hojas de cálculo en el libro de trabajo resultante. El valor predeterminado es false; significa guardar cada página PDF como hoja de cálculo separada.

**Returns:**
valor booleano

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Establezca false si necesita suprimir la inserción de una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es true; significa que se insertará una columna en blanco.

**Returns:**
valor booleano

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Establezca true para usar una división uniforme de columnas en todo el documento. El valor predeterminado es false; significa que la división de columnas será independiente para cada página.

**Returns:**
valor booleano

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Formato de salida

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Establezca false si necesita suprimir la inserción de una columna en blanco como la primera columna de la hoja de cálculo. El valor predeterminado es true; significa que se insertará una columna en blanco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Establezca true si necesita minimizar el número de hojas de cálculo en el libro de trabajo resultante. El valor predeterminado es false; significa guardar cada página PDF como hoja de cálculo separada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Define el motor de conversión que se utilizará para la conversión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |
