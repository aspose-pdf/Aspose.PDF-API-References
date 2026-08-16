---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un campo de casilla de verificación"
type: docs
weight: 580
url: /es/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Clase que representa un campo de casilla de verificación

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc) |

## Métodos

| Método | Descripción |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Agrega una nueva casilla de verificación a un grupo de casillas de verificación, en el que como máximo una de las casillas puede estar marcada en cualquier momento. La nueva casilla se agrega al final del grupo. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Agrega una nueva casilla de verificación a un grupo de casillas de verificación, en el que como máximo una de las casillas puede estar marcada en cualquier momento. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Agrega una nueva casilla de verificación a un grupo de casillas de verificación, en el que como máximo una de las casillas puede estar marcada en cualquier momento. |
| [deepClone](#deepClone--) | Clonar la casilla de verificación. |
| [getActiveState](#getActiveState--) | Obtiene el estado actual de apariencia de la anotación. |
| [getAllowedStates](#getAllowedStates--) | Devuelve una lista de estados permitidos. |
| [getChecked](#getChecked--) | Obtiene el estado del cuadro de verificación. |
| [getExportValue](#getExportValue--) | Obtiene o establece el valor de exportación del campo CheckBox. |
| [getNormalCaption](#getNormalCaption--) | Obtiene el título normal del campo. |
| [getOnState](#getOnState--) | Devuelve el nombre del estado que corresponde al estado "Checked" del checkbox. Es "Yes" si está presente o cualquier otro valor distinto de "Off" y "No"; |
| [getStyle](#getStyle--) | Obtiene el estilo del cuadro de verificación. |
| [getValue](#getValue--) | Obtiene el valor del campo del cuadro de verificación. |
| [setActiveState](#setActiveState-java.lang.String-) | Establece el estado actual de la apariencia de la anotación. |
| [setChecked](#setChecked-boolean-) | Establece el estado del cuadro de verificación. |
| [setExportValue](#setExportValue-java.lang.String-) | Obtiene o establece el valor de exportación del campo CheckBox. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Establece el estilo del cuadro de verificación. |
| [setValue](#setValue-java.lang.String-) | Establece el valor del campo del cuadro de verificación. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crear instancia de CheckboxField. @deprecated Para la funcionalidad completa del campo, se requiere una vinculación al documento - use CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Agrega una nueva casilla de verificación a un grupo de casillas de verificación, en el que como máximo una de las casillas puede estar marcada en cualquier momento. La nueva casilla se agrega al final del grupo.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Agrega una nueva casilla de verificación a un grupo de casillas de verificación, en el que como máximo una de las casillas puede estar marcada en cualquier momento.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Agrega una nueva casilla de verificación a un grupo de casillas de verificación, en el que como máximo una de las casillas puede estar marcada en cualquier momento.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clonar la casilla de verificación.

**Returns:**
El objeto clonado

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Obtiene el estado actual de apariencia de la anotación.

**Returns:**
valor String

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Devuelve una lista de estados permitidos.

**Returns:**
lista de valores String

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Obtiene el estado del cuadro de verificación.

**Returns:**
valor booleano

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Obtiene o establece el valor de exportación del campo CheckBox.

**Returns:**
valor String

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Obtiene el título normal del campo.

**Returns:**
valor String

### getOnState {#getOnState--}
```
public String getOnState()
```

Devuelve el nombre del estado que corresponde al estado "Checked" del checkbox. Es "Yes" si está presente o cualquier otro valor distinto de "Off" y "No";

**Returns:**
valor String

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Obtiene el estilo del cuadro de verificación.

**Returns:**
estilo del cuadro de verificación. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Obtiene el valor del campo del cuadro de verificación.

**Returns:**
valor String

### setActiveState {#setActiveState-java.lang.String-}
Establece el estado actual de la apariencia de la anotación.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Establece el estado del cuadro de verificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setExportValue {#setExportValue-java.lang.String-}
Obtiene o establece el valor de exportación del campo CheckBox.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Establece el estilo del cuadro de verificación.

### setValue {#setValue-java.lang.String-}
Establece el valor del campo del cuadro de verificación.
