---
title: "Campo"
linktitle: "Campo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase base para campos de formulario acro."
type: docs
weight: 1380
url: /es/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Clase base para campos de formulario acro.

## Campos

| Campo | Descripción |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Crea un campo para usar en Generator. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Copia los subcampos de este campo en una matriz comenzando desde el índice especificado. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copia los subcampos de este campo en una matriz comenzando desde el índice especificado. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Ejecuta una acción JavaScript especificada para el campo. |
| [flatten](#flatten--) | Elimina este campo y coloca su valor directamente en la página. |
| [get_Item](#get_Item-int-) | Obtiene el subcampo contenido en este campo por índice. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene el subcampo contenido en este campo por el nombre del subcampo. |
| [getAlternateName](#getAlternateName--) | Obtiene el nombre alternativo del campo (Un nombre de campo alternativo que se debe usar en lugar del nombre real del campo dondequiera que el campo sea identificado en la interfaz de usuario). El nombre alternativo se usa como información sobre herramientas del campo en Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Obtiene el índice de esta anotación en la página. |
| [getMappingName](#getMappingName--) | Obtiene el nombre de mapeo del campo que se debe usar al exportar datos de campos de formulario interactivo del documento. |
| [getMaxFontSize](#getMaxFontSize--) | Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| [getMinFontSize](#getMinFontSize--) | Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| [getPageIndex](#getPageIndex--) | Obtiene el índice de la página que contiene este campo. |
| [getPartialName](#getPartialName--) | Obtiene el nombre parcial del campo. |
| [getRect](#getRect--) | Obtiene el rectángulo del campo. |
| [getSyncRoot](#getSyncRoot--) | Objeto de sincronización. |
| [getTabOrder](#getTabOrder--) | Obtiene o establece el orden de tabulación del campo. |
| [getValue](#getValue--) | Obtiene el valor del campo. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado. |
| [isGroup](#isGroup--) | Obtiene el valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Propiedad para el soporte de Generator. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| [isSynchronized](#isSynchronized--) | Devuelve verdadero si el diccionario está sincronizado. |
| [iterator](#iterator--) | Devuelve el enumerador de los campos contenidos. |
| [recalculate](#recalculate--) | Recalcula todos los campos calculados en el formulario. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Establece el nombre alternativo del campo (Un nombre de campo alternativo que se usará en lugar del nombre real del campo dondequiera que el campo deba identificarse en la interfaz de usuario). El nombre alternativo se utiliza como información sobre herramientas del campo en Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Establece el índice de esta anotación en la página. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado. |
| [setMappingName](#setMappingName-java.lang.String-) | Establece el nombre de mapeo del campo que se utilizará al exportar los datos de los campos de formulario interactivo del documento. |
| [setMaxFontSize](#setMaxFontSize-double-) | Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| [setMinFontSize](#setMinFontSize-double-) | Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| [setPartialName](#setPartialName-java.lang.String-) | Establece el nombre parcial del campo. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Establece la posición del campo. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Establece el rectángulo del campo. |
| [setSharedField](#setSharedField-boolean-) | Propiedad para el soporte de Generator. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| [setTabOrder](#setTabOrder-int-) | Obtiene o establece el orden de tabulación del campo. |
| [setValue](#setValue-java.lang.String-) | Establece el valor. |
| [size](#size--) | Obtiene el número de subcampos en este campo. (Por ejemplo, el número de elementos en un campo de botón de opción). |
| [updateAppearances](#updateAppearances--) | Actualiza el valor de apariencias. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Crea un campo para usar en Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Copia los subcampos de este campo en una matriz comenzando desde el índice especificado.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copia los subcampos de este campo en una matriz comenzando desde el índice especificado.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Ejecuta una acción JavaScript especificada para el campo.

### flatten {#flatten--}
```
public void flatten()
```

Elimina este campo y coloca su valor directamente en la página.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Obtiene el subcampo contenido en este campo por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del subcampo solicitado. |

**Returns:**
Instancia del campo.

### get_Item {#get_Item-java.lang.String-}
Obtiene el subcampo contenido en este campo por el nombre del subcampo.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Obtiene el nombre alternativo del campo (Un nombre de campo alternativo que se debe usar en lugar del nombre real del campo dondequiera que el campo sea identificado en la interfaz de usuario). El nombre alternativo se usa como información sobre herramientas del campo en Adobe Acrobat.

**Returns:**
valor String

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Obtiene el índice de esta anotación en la página.

**Returns:**
valor int

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Obtiene el nombre de mapeo del campo que se debe usar al exportar datos de campos de formulario interactivo del documento.

**Returns:**
valor String

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño.

**Returns:**
valor double

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño.

**Returns:**
valor double

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtiene el índice de la página que contiene este campo.

**Returns:**
valor int

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Obtiene el nombre parcial del campo.

**Returns:**
valor String

### getRect {#getRect--}
```
public Rectangle getRect()
```

Obtiene el rectángulo del campo.

**Returns:**
el rectángulo del campo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objeto de sincronización.

**Returns:**
valor del objeto

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Obtiene o establece el orden de tabulación del campo.

**Returns:**
valor int

### getValue {#getValue--}
```
public String getValue()
```

Obtiene el valor del campo.

**Returns:**
valor String

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado.

**Returns:**
valor booleano

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Obtiene el valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Propiedad para el soporte de Generator. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Devuelve verdadero si el diccionario está sincronizado.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Devuelve el enumerador de los campos contenidos.

**Returns:**
Objeto enumerador.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Recalcula todos los campos calculados en el formulario.

**Returns:**
true si el valor del campo se cambió durante la recalculación.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Establece el nombre alternativo del campo (Un nombre de campo alternativo que se usará en lugar del nombre real del campo dondequiera que el campo deba identificarse en la interfaz de usuario). El nombre alternativo se utiliza como información sobre herramientas del campo en Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Establece el índice de esta anotación en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMappingName {#setMappingName-java.lang.String-}
Establece el nombre de mapeo del campo que se utilizará al exportar los datos de los campos de formulario interactivo del documento.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setPartialName {#setPartialName-java.lang.String-}
Establece el nombre parcial del campo.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Establece la posición del campo.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Establece el rectángulo del campo.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Propiedad para el soporte de Generator. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Obtiene o establece el orden de tabulación del campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setValue {#setValue-java.lang.String-}
Establece el valor.

### size {#size--}
```
public int size()
```

Obtiene el número de subcampos en este campo. (Por ejemplo, el número de elementos en un campo de botón de opción).

**Returns:**
valor int

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Actualiza el valor de apariencias.
