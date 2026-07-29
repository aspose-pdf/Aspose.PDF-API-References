---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un campo de cuadro de texto."
type: docs
weight: 4930
url: /es/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Clase que representa un campo de cuadro de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc) |

## Métodos

| Método | Descripción |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Agrega código de barras 128 al campo. El valor del campo se cambiará al código y el campo se volverá de solo lectura. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Agrega una imagen a los recursos del campo y la dibuja. |
| [getForceCombs](#getForceCombs--) | Obtiene la bandera que indica si el campo está dividido en posiciones espaciadas. |
| [getMaxLen](#getMaxLen--) | Obtiene la longitud máxima del texto en el campo. |
| [getMultiline](#getMultiline--) | Obtiene la bandera multilínea del campo. Si Multiline es verdadero, el campo puede contener varias líneas de texto. |
| [getScrollable](#getScrollable--) | Obtiene la bandera desplazable del campo. Si es verdadero, el campo puede desplazarse. |
| [getSpellCheck](#getSpellCheck--) | Obtiene la bandera de corrección ortográfica para el campo. Si es verdadero, el campo será revisado ortográficamente. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Obtiene o establece la alineación vertical del texto para la anotación. |
| [getValue](#getValue--) | Obtiene el valor del campo. |
| [setForceCombs](#setForceCombs-boolean-) | Establece la bandera que indica si el campo está dividido en posiciones espaciadas. |
| [setJustification](#setJustification-boolean-) | Establece la justificación |
| [setMaxLen](#setMaxLen-int-) | Establece la longitud máxima del texto en el campo. |
| [setMultiline](#setMultiline-boolean-) | Establece la bandera de varias líneas del campo. Si Multiline es verdadero, el campo puede contener múltiples líneas de texto. |
| [setScrollable](#setScrollable-boolean-) | Establece la bandera de desplazamiento del campo. Si es verdadero, el campo puede desplazarse. |
| [setSpellCheck](#setSpellCheck-boolean-) | Establece la bandera de corrección ortográfica para el campo. Si es verdadero, el campo será revisado ortográficamente. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtiene o establece la alineación vertical del texto para la anotación. |
| [setValue](#setValue-java.lang.String-) | Establece el valor del campo. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Crear instancia de TextBoxField. @deprecated Para la funcionalidad completa del campo, se requiere un enlace al documento - use TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Agrega código de barras 128 al campo. El valor del campo se cambiará al código y el campo se volverá de solo lectura.

### addImage {#addImage-java.awt.image.BufferedImage-}
Agrega una imagen a los recursos del campo y la dibuja.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Obtiene la bandera que indica si el campo está dividido en posiciones espaciadas.

**Returns:**
valor booleano

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Obtiene la longitud máxima del texto en el campo.

**Returns:**
valor int

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Obtiene la bandera multilínea del campo. Si Multiline es verdadero, el campo puede contener varias líneas de texto.

**Returns:**
valor booleano

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Obtiene la bandera desplazable del campo. Si es verdadero, el campo puede desplazarse.

**Returns:**
valor booleano

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Obtiene la bandera de corrección ortográfica para el campo. Si es verdadero, el campo será revisado ortográficamente.

**Returns:**
valor booleano

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Obtiene o establece la alineación vertical del texto para la anotación.

**Returns:**
Elemento VerticalAlignment

### getValue {#getValue--}
```
public String getValue()
```

Obtiene el valor del campo.

**Returns:**
valor String

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Establece la bandera que indica si el campo está dividido en posiciones espaciadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Establece la justificación

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Establece la longitud máxima del texto en el campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Establece la bandera de varias líneas del campo. Si Multiline es verdadero, el campo puede contener múltiples líneas de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Establece la bandera de desplazamiento del campo. Si es verdadero, el campo puede desplazarse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Establece la bandera de corrección ortográfica para el campo. Si es verdadero, el campo será revisado ortográficamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtiene o establece la alineación vertical del texto para la anotación.

### setValue {#setValue-java.lang.String-}
Establece el valor del campo.
