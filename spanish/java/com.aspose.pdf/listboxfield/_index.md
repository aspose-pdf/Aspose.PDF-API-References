---
title: "ListBoxField"
linktitle: "ListBoxField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "La clase representa el campo ListBox."
type: docs
weight: 2770
url: /es/java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.ChoiceField, com.aspose.pdf.ListBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class ListBoxField extends ChoiceField
```

La clase representa el campo ListBox.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ListBoxField](#ListBoxField--) | Constructor para ListBoxField que se usará en Generator. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructor para ListBoxField que se usará en Generator. |
| [ListBoxField](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor para ListBoxField que se usará en Generator. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getTopIndex](#getTopIndex--) | Obtiene el índice del elemento visible superior de la lista. |
| [setSelected](#setSelected-int-) | Obtiene el índice del elemento seleccionado. Los elementos se numeran a partir de 1. |
| [setSelectedItems](#setSelectedItems-int:A-) | Establece la matriz de los elementos seleccionados en la lista de selección múltiple. Para la lista de selección única devuelve una matriz con un solo elemento. |
| [setTopIndex](#setTopIndex-int-) | Establece el índice del elemento visible superior de la lista. |

### ListBoxField {#ListBoxField--}
```
public ListBoxField()
```

Constructor para ListBoxField que se usará en Generator.

### ListBoxField {#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructor para ListBoxField que se usará en Generator.

### ListBoxField {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor para ListBoxField que se usará en Generator.

### getTopIndex {#getTopIndex--}
```
public int getTopIndex()
```

Obtiene el índice del elemento visible superior de la lista.

**Returns:**
valor int

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Obtiene el índice del elemento seleccionado. Los elementos se numeran a partir de 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Establece la matriz de los elementos seleccionados en la lista de selección múltiple. Para la lista de selección única devuelve una matriz con un solo elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de valores int |

### setTopIndex {#setTopIndex-int-}
```
public void setTopIndex(int value)
```

Establece el índice del elemento visible superior de la lista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
