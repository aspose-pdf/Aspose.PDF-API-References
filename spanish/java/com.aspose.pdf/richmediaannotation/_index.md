---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que describe RichMediaAnnotation, que permite incrustar datos de video/audio en un documento PDF."
type: docs
weight: 4260
url: /es/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Clase que describe RichMediaAnnotation, que permite incrustar datos de video/audio en un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa RichMediaAnnotation. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta visitante para esta anotación. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Agregar datos con nombre personalizado (por ejemplo, requeridos para el script flash). |
| [getActivateOn](#getActivateOn--) | Evento que activa la aplicación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getContent](#getContent--) | Datos del contenido Rich Media. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Establece o obtiene variables flash que se pasan al reproductor. |
| [getCustomPlayer](#getCustomPlayer--) | Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio. |
| [getType](#getType--) | Obtiene o establece el tipo de contenido. Valores posibles: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Evento que activa la aplicación. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Establecer flujo de contenido. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Establece o obtiene variables flash que se pasan al reproductor. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio. |
| [setPoster](#setPoster-java.io.InputStream-) | Establecer póster de la anotación. |
| [setType](#setType-int-) | Obtiene o establece el tipo de contenido. Valores posibles: Audio, Video. |
| [update](#update--) | Actualiza los datos con los parámetros especificados. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta visitante para esta anotación.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Agregar datos con nombre personalizado (por ejemplo, requeridos para el script flash).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Evento que activa la aplicación.

**Returns:**
Elemento ActivationEvent

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Datos del contenido Rich Media.

**Returns:**
Objeto InputStream

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Establece o obtiene variables flash que se pasan al reproductor.

**Returns:**
Objeto String

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio.

**Returns:**
Objeto InputStream

### getType {#getType--}
```
public int getType()
```

Obtiene o establece el tipo de contenido. Valores posibles: Audio, Video.

**Returns:**
Valor ContentType @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Evento que activa la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ActivationEvent |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Establecer flujo de contenido.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Establece o obtiene variables flash que se pasan al reproductor.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio.

### setPoster {#setPoster-java.io.InputStream-}
Establecer póster de la anotación.

### setType {#setType-int-}
```
public void setType(int value)
```

Obtiene o establece el tipo de contenido. Valores posibles: Audio, Video.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ContentType |

### update {#update--}
```
public void update()
```

Actualiza los datos con los parámetros especificados.
