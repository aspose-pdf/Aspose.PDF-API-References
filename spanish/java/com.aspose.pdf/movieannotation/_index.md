---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una anotación de película que contiene gráficos animados y sonido para presentarse en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, el."
type: docs
weight: 3090
url: /es/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Representa una anotación de película que contiene gráficos animados y sonido para ser presentados en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Constructor para usar con Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crea una nueva anotación de sonido en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getAspect](#getAspect--) | Obtiene o establece el ancho y la altura del cuadro delimitador de la película, en píxeles. |
| [getFile](#getFile--) | Obtiene una especificación de archivo que identifica un archivo de película auto-descriptivo. |
| [getPoster](#getPoster--) | Obtiene o establece una bandera o flujo que especifica si y cómo se debe mostrar una imagen de póster que representa la película. Si es true, la imagen del póster se obtendrá del archivo de la película; si es false, no se mostrará ningún póster. |
| [getRotate](#getRotate--) | Obtiene o establece el número de grados en que la película debe rotarse en sentido horario respecto a la página. El valor debe ser un múltiplo de 90. |
| [getTitle](#getTitle--) | Obtiene el título de la anotación de la película. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Obtiene o establece el ancho y la altura del cuadro delimitador de la película, en píxeles. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Establece una especificación de archivo que identifica un archivo de película auto-descriptivo. |
| [setPoster](#setPoster-boolean-) | Obtiene o establece una bandera o flujo que especifica si y cómo se debe mostrar una imagen de póster que representa la película. Si es true, la imagen del póster se obtendrá del archivo de la película; si es false, no se mostrará ningún póster. |
| [setRotate](#setRotate-int-) | Obtiene o establece el número de grados en que la película debe rotarse en sentido horario respecto a la página. El valor debe ser un múltiplo de 90. |
| [setTitle](#setTitle-java.lang.String-) | Establece el título de la anotación de la película. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Constructor para usar con Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crea una nueva anotación de sonido en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType como valor int @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Obtiene o establece el ancho y la altura del cuadro delimitador de la película, en píxeles.

**Returns:**
Instancia de Point

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Obtiene una especificación de archivo que identifica un archivo de película auto-descriptivo.

**Returns:**
Valor FileSpecification

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Obtiene o establece una bandera o flujo que especifica si y cómo se debe mostrar una imagen de póster que representa la película. Si es true, la imagen del póster se obtendrá del archivo de la película; si es false, no se mostrará ningún póster.

**Returns:**
valor booleano

### getRotate {#getRotate--}
```
public final int getRotate()
```

Obtiene o establece el número de grados en que la película debe rotarse en sentido horario respecto a la página. El valor debe ser un múltiplo de 90.

**Returns:**
valor int

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtiene el título de la anotación de la película.

**Returns:**
valor String

### setAspect {#setAspect-com.aspose.pdf.Point-}
Obtiene o establece el ancho y la altura del cuadro delimitador de la película, en píxeles.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Establece una especificación de archivo que identifica un archivo de película auto-descriptivo.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Obtiene o establece una bandera o flujo que especifica si y cómo se debe mostrar una imagen de póster que representa la película. Si es true, la imagen del póster se obtendrá del archivo de la película; si es false, no se mostrará ningún póster.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Obtiene o establece el número de grados en que la película debe rotarse en sentido horario respecto a la página. El valor debe ser un múltiplo de 90.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setTitle {#setTitle-java.lang.String-}
Establece el título de la anotación de la película.
