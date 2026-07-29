---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una anotación de widget."
type: docs
weight: 5540
url: /es/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Clase que representa una anotación de widget.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Crear anotación (usado para Generator) |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta visitante. |
| [getAnnotationActions](#getAnnotationActions--) | Obtiene las acciones de la anotación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getCheckedStateName](#getCheckedStateName--) | Devuelve el nombre del estado "checked" según los nombres de estado existentes. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtiene la apariencia predeterminada del campo. |
| [getExportable](#getExportable--) | Obtiene la bandera exportable del campo. |
| [getHighlighting](#getHighlighting--) | Modo de resaltado de la anotación. |
| [getOnActivated](#getOnActivated--) | Obtiene una acción que se debe ejecutar cuando la anotación se activa. |
| [getParent](#getParent--) | Obtiene el elemento padre de la anotación. |
| [getReadOnly](#getReadOnly--) | Obtiene el estado de solo lectura del campo. |
| [getRequired](#getRequired--) | Obtiene el estado requerido del campo. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Establece la apariencia predeterminada del campo. |
| [setExportable](#setExportable-boolean-) | Establece el estado de solo lectura del campo. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Modo de resaltado de la anotación. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Establece una acción que se debe ejecutar cuando la anotación se activa. |
| [setReadOnly](#setReadOnly-boolean-) | Establece el estado de solo lectura del campo. |
| [setRequired](#setRequired-boolean-) | Establece el estado de solo lectura del campo. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Crear anotación (usado para Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta visitante.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Obtiene las acciones de la anotación.

**Returns:**
Objeto AnnotationActionCollection

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Devuelve el nombre del estado "checked" según los nombres de estado existentes.

**Returns:**
El nombre del estado "checked" para esta anotación.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Obtiene la apariencia predeterminada del campo.

**Returns:**
objeto DefaultAppearance

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Obtiene la bandera exportable del campo.

**Returns:**
valor booleano

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Modo de resaltado de la anotación.

**Returns:**
Valor HighlightingMode @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Obtiene una acción que se debe ejecutar cuando la anotación se activa.

**Returns:**
Objeto PdfAction

### getParent {#getParent--}
```
public Field getParent()
```

Obtiene el elemento padre de la anotación.

**Returns:**
Objeto Field

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Obtiene el estado de solo lectura del campo.

**Returns:**
valor booleano

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Obtiene el estado requerido del campo.

**Returns:**
valor booleano

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Establece la apariencia predeterminada del campo.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Establece el estado de solo lectura del campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Modo de resaltado de la anotación.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Establece una acción que se debe ejecutar cuando la anotación se activa.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Establece el estado de solo lectura del campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Establece el estado de solo lectura del campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
