---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un campo de botón de opción."
type: docs
weight: 4080
url: /es/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Clase que representa un campo de botón de opción.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Constructor para RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Constructor para RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Establece el campo de botón de radio. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Añade un nuevo campo de opción al campo RadioButton. |
| [addOption](#addOption-java.lang.String-) | Agregar opción al botón de radio. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Agregar a la opción del botón de radio con un rectángulo especificado. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Obtiene o establece la bandera que permite que el botón de opción no tenga un valor seleccionado. Si {@code }, exactamente un botón de opción debe estar seleccionado en todo momento; seleccionar el botón actualmente seleccionado no tiene efecto. Si {@code }, al hacer clic en el botón seleccionado se deselecciona, dejando ningún botón seleccionado. </p> <hr> Algunos lectores de PDF (incluido Adobe Acrobat) pueden ignorar el estado de la bandera. |
| [getOptions](#getOptions--) | Obtiene la colección de opciones del botón de radio. |
| [getPageIndex](#getPageIndex--) | Obtiene el índice de la página que contiene este campo RadioButton. |
| [getSelected](#getSelected--) | Obtiene el índice del elemento seleccionado. La numeración de los elementos comienza en 1. |
| [getStyle](#getStyle--) | Estilo del cuadro de campo. |
| [getValue](#getValue--) | Obtiene el valor del campo. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Obtiene o establece la bandera que permite que el botón de opción no tenga un valor seleccionado. Si {@code }, exactamente un botón de opción debe estar seleccionado en todo momento; seleccionar el botón actualmente seleccionado no tiene efecto. Si {@code }, al hacer clic en el botón seleccionado se deselecciona, dejando ningún botón seleccionado. </p> <hr> Algunos lectores de PDF (incluido Adobe Acrobat) pueden ignorar el estado de la bandera. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Mueve todos los subelementos del botón de radio a las posiciones especificadas en la página. |
| [setSelected](#setSelected-int-) | Establece el índice del elemento seleccionado. La numeración de los elementos comienza en 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Estilo del cuadro de campo. |
| [setValue](#setValue-java.lang.String-) | Establece el valor del campo. |
| [updateAppearances](#updateAppearances--) | Actualiza el valor de apariencias. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Constructor para RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Constructor para RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Establece el campo de botón de radio.

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Añade un nuevo campo de opción al campo RadioButton.

### addOption {#addOption-java.lang.String-}
Agregar opción al botón de radio.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Agregar a la opción del botón de radio con un rectángulo especificado.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Obtiene o establece la bandera que permite que el botón de opción no tenga un valor seleccionado. Si {@code }, exactamente un botón de opción debe estar seleccionado en todo momento; seleccionar el botón actualmente seleccionado no tiene efecto. Si {@code }, al hacer clic en el botón seleccionado se deselecciona, dejando ningún botón seleccionado. </p> <hr> Algunos lectores de PDF (incluido Adobe Acrobat) pueden ignorar el estado de la bandera.

**Returns:**
valor booleano

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Obtiene la colección de opciones del botón de radio.

**Returns:**
Objeto OptionCollection

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtiene el índice de la página que contiene este campo RadioButton.

**Returns:**
valor int

### getSelected {#getSelected--}
```
public int getSelected()
```

Obtiene el índice del elemento seleccionado. La numeración de los elementos comienza en 1.

**Returns:**
valor int

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Estilo del cuadro de campo.

**Returns:**
Valor de BoxStyle @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Obtiene el valor del campo.

**Returns:**
valor String

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Obtiene o establece la bandera que permite que el botón de opción no tenga un valor seleccionado. Si {@code }, exactamente un botón de opción debe estar seleccionado en todo momento; seleccionar el botón actualmente seleccionado no tiene efecto. Si {@code }, al hacer clic en el botón seleccionado se deselecciona, dejando ningún botón seleccionado. </p> <hr> Algunos lectores de PDF (incluido Adobe Acrobat) pueden ignorar el estado de la bandera.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Mueve todos los subelementos del botón de radio a las posiciones especificadas en la página.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Establece el índice del elemento seleccionado. La numeración de los elementos comienza en 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Estilo del cuadro de campo.

### setValue {#setValue-java.lang.String-}
Establece el valor del campo.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Actualiza el valor de apariencias.
