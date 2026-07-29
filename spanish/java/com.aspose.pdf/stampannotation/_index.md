---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa una anotación de sello de goma. Este tipo de anotación muestra texto o gráficos que pretenden parecer como si estuvieran estampados en la página con un sello de goma. </p> <hr>."
type: docs
weight: 4630
url: /es/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Representa la anotación de sello de goma. Este tipo de anotación muestra texto o gráficos diseñados para parecer como si estuvieran estampados en la página con un sello de goma. </p> <hr> <pre> El siguiente fragmento de código demuestra cómo agregar 2 sellos en la primera página del documento PDF. El documento de entrada proviene de inFile y los cambios se guardan en outFile. El primer sello tiene el ícono NotForPublicRelease y el segundo proviene de la imagen rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Constructor |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nueva anotación de sello en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta el visitante {@code AnnotationSelector} al explorar la colección de anotaciones. |
| [clear](#clear--) | Borrar instancias estáticas |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getIcon](#getIcon--) | Obtiene el ícono para el sello de goma. |
| [getImage](#getImage--) | Obtiene la imagen de la anotación. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Establece la imagen SVG de la anotación en una cadena Base64. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Establece el ícono para el sello de goma. |
| [setImage](#setImage-java.io.InputStream-) | Establece la imagen de la anotación. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Constructor

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nueva anotación de sello en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta el visitante {@code AnnotationSelector} al explorar la colección de anotaciones.

### clear {#clear--}
```
public static void clear()
```

Borrar instancias estáticas

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Obtiene el ícono para el sello de goma.

**Returns:**
Valor de StampIcon

### getImage {#getImage--}
```
public InputStream getImage()
```

Obtiene la imagen de la anotación.

**Returns:**
Objeto InputStream

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Establece la imagen SVG de la anotación en una cadena Base64.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Establece el ícono para el sello de goma.

### setImage {#setImage-java.io.InputStream-}
Establece la imagen de la anotación.
