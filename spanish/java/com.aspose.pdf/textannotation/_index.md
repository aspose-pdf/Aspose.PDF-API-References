---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una anotación de texto que es una \\\"sticky note\\\" adjunta a un punto en el documento PDF."
type: docs
weight: 4920
url: /es/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Representa una anotación de texto que es una \"nota adhesiva\" adjunta a un punto en el documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Crear instancia de TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Crear instancia de TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crear instancia de TextAnnotation |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Sobrescribe la definición en la clase base con un cuerpo vacío. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getIcon](#getIcon--) | Obtiene un ícono que se usará al mostrar la anotación. |
| [getOpen](#getOpen--) | Obtiene una bandera que especifica si la anotación debe mostrarse inicialmente abierta. |
| [setIcon](#setIcon-int-) | Establece un ícono que se usará al mostrar la anotación. |
| [setOpen](#setOpen-boolean-) | Establece una bandera que especifica si la anotación debe mostrarse inicialmente abierta. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Crear instancia de TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Crear instancia de TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crear instancia de TextAnnotation

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Sobrescribe la definición en la clase base con un cuerpo vacío.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Valor de AnnotationType @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Obtiene un ícono que se usará al mostrar la anotación.

**Returns:**
Valor de TextIcon @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtiene una bandera que especifica si la anotación debe mostrarse inicialmente abierta.

**Returns:**
valor booleano

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Establece un ícono que se usará al mostrar la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor de TextIcon @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Establece una bandera que especifica si la anotación debe mostrarse inicialmente abierta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
