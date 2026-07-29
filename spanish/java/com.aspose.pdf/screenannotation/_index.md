---
title: "ScreenAnnotation"
linktitle: "ScreenAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una anotación de pantalla que especifica una región de una página en la que se pueden reproducir clips de medios."
type: docs
weight: 4470
url: /es/java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.ScreenAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class ScreenAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Una anotación de pantalla que especifica una región de una página en la que se pueden reproducir clips de medios.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ScreenAnnotation](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crea una nueva anotación Screen en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Representa el método accept |
| [getAction](#getAction--) | Obtiene una acción a realizar cuando la anotación se activa. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getTitle](#getTitle--) | Obtiene el título de la anotación screen. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Establece una acción a realizar cuando la anotación se activa. |
| [setTitle](#setTitle-java.lang.String-) | Establece el título de la anotación screen. |

### ScreenAnnotation {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crea una nueva anotación Screen en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Representa el método accept

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtiene una acción a realizar cuando la anotación se activa.

**Returns:**
Objeto PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtiene el título de la anotación screen.

**Returns:**
valor String

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Establece una acción a realizar cuando la anotación se activa.

### setTitle {#setTitle-java.lang.String-}
Establece el título de la anotación screen.
