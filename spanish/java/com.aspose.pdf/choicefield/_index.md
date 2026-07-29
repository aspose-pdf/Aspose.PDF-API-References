---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase base para campos de opción."
type: docs
weight: 590
url: /es/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Representa la clase base para campos de opción.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Crea un campo de elección (para Generator) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor para ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor para ChoiceField. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Agrega una nueva opción con el nombre especificado. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Agrega una nueva opción con el valor de exportación y el nombre especificados. |
| [deleteOption](#deleteOption-java.lang.String-) | Elimina la opción por su nombre. |
| [getCommitImmediately](#getCommitImmediately--) | Obtiene la bandera de confirmación al cambiar la selección. |
| [getMultiSelect](#getMultiSelect--) | Obtiene la bandera de selección múltiple. |
| [getOptions](#getOptions--) | Obtiene la colección de opciones de elección. |
| [getSelected](#getSelected--) | Obtiene el índice de la opción seleccionada. Esta propiedad permite cambiar la selección. |
| [getSelectedItems](#getSelectedItems--) | Establece la matriz de elementos seleccionados. Para una lista de selección múltiple, la matriz contiene más de un elemento. Para una lista de selección única, contiene un solo elemento. |
| [getValue](#getValue--) | Obtiene el valor del campo. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Establece la bandera de confirmación al cambiar la selección. |
| [setMultiSelect](#setMultiSelect-boolean-) | Establece la bandera de selección múltiple. |
| [setOptions](#setOptions-java.util.List-) | Reemplaza las opciones disponibles con aquellas cuyos nombres se proporcionan en el parámetro options. |
| [setSelected](#setSelected-int-) | Establece el índice de la opción seleccionada. Esta propiedad permite cambiar la selección. |
| [setSelectedItems](#setSelectedItems-int:A-) | Establece la matriz de elementos seleccionados. Para una lista de selección múltiple, la matriz contiene más de un elemento. Para una lista de selección única, contiene un solo elemento. |
| [setValue](#setValue-java.lang.String-) | Establece el valor del campo. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Crea un campo de elección (para Generator)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructor para ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor para ChoiceField.

### addOption {#addOption-java.lang.String-}
Agrega una nueva opción con el nombre especificado.

### addOption {#addOption-java.lang.String-java.lang.String-}
Agrega una nueva opción con el valor de exportación y el nombre especificados.

### deleteOption {#deleteOption-java.lang.String-}
Elimina la opción por su nombre.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Obtiene la bandera de confirmación al cambiar la selección.

**Returns:**
valor booleano

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Obtiene la bandera de selección múltiple.

**Returns:**
valor booleano

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Obtiene la colección de opciones de elección.

**Returns:**
Objeto OptionCollection

### getSelected {#getSelected--}
```
public int getSelected()
```

Obtiene el índice de la opción seleccionada. Esta propiedad permite cambiar la selección.

**Returns:**
valor int

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Establece la matriz de elementos seleccionados. Para una lista de selección múltiple, la matriz contiene más de un elemento. Para una lista de selección única, contiene un solo elemento.

**Returns:**
matriz de valores int

### getValue {#getValue--}
```
public String getValue()
```

Obtiene el valor del campo.

**Returns:**
valor String

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Establece la bandera de confirmación al cambiar la selección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Establece la bandera de selección múltiple.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptions {#setOptions-java.util.List-}
Reemplaza las opciones disponibles con aquellas cuyos nombres se proporcionan en el parámetro options.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Establece el índice de la opción seleccionada. Esta propiedad permite cambiar la selección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Establece la matriz de elementos seleccionados. Para una lista de selección múltiple, la matriz contiene más de un elemento. Para una lista de selección única, contiene un solo elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de valores int |

### setValue {#setValue-java.lang.String-}
Establece el valor del campo.
