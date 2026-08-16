---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una anotación de sonido que contiene audio grabado desde el micrófono del ordenador o importado desde un archivo."
type: docs
weight: 4530
url: /es/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Representa una anotación de sonido que contiene audio grabado desde el micrófono del ordenador o importado desde un archivo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crea una nueva anotación de sonido en la página especificada. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Crea una nueva anotación de sonido en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getIcon](#getIcon--) | Obtiene un ícono que se usará al mostrar la anotación. |
| [getSoundData](#getSoundData--) | Obtiene un objeto de sonido que define el sonido que se reproducirá cuando se active la anotación. |
| [setIcon](#setIcon-int-) | Establece un ícono que se usará al mostrar la anotación. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crea una nueva anotación de sonido en la página especificada.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Crea una nueva anotación de sonido en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Valor de AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Obtiene un ícono que se usará al mostrar la anotación.

**Returns:**
Valor de SoundIcon @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Obtiene un objeto de sonido que define el sonido que se reproducirá cuando se active la anotación.

**Returns:**
Valor de SoundData

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Establece un ícono que se usará al mostrar la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor de SoundIcon @see SoundIcon |
