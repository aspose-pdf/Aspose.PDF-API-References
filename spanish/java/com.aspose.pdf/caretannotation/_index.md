---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una anotación de cursor."
type: docs
weight: 470
url: /es/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Clase que representa una anotación de cursor.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Constructor para usar en Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nueva anotación Caret en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getFrame](#getFrame--) | Obtiene el rectángulo del caret. |
| [getSymbol](#getSymbol--) | Obtiene el símbolo asociado con el caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Establece el rectángulo del caret. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Establece el tamaño de página de salida para la importación. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Constructor para usar en Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nueva anotación Caret en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Obtiene el rectángulo del caret.

**Returns:**
rectángulo del caret.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Obtiene el símbolo asociado con el caret. {@code CaretSymbol}

**Returns:**
Elemento CaretSymbol @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Establece el rectángulo del caret.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Establece el tamaño de página de salida para la importación.
