---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la anotación Redact."
type: docs
weight: 4120
url: /es/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Representa la anotación Redact.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Constructor de RedactionAnnotation. Para usar en Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructor de RedactAnnotation. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [flatten](#flatten--) | Aplana la anotación, es decir, elimina la anotación y agrega su contenido |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getBorderColor](#getBorderColor--) | Obtiene el color del borde que se dibuja cuando la redacción no está activa. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtiene o establece la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [getFillColor](#getFillColor--) | Obtiene el color para rellenar la anotación. |
| [getFontSize](#getFontSize--) | Obtiene el tamaño de fuente para OverlayText. |
| [getOverlayText](#getOverlayText--) | Obtiene el texto para imprimir en la anotación de redacción. |
| [getQuadPoint](#getQuadPoint--) | Una matriz de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar. |
| [getQuadPoints](#getQuadPoints--) | Obtiene una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |
| [getTextAlignment](#getTextAlignment--) | Obtiene la alineación del Texto superpuesto. |
| [isRepeat](#isRepeat--) | Si es verdadero, el texto superpuesto se repetirá en la anotación. |
| [redact](#redact--) | Aplana la anotación y redacta el contenido de la página (es decir, elimina el texto y el contenido de imagen bajo la anotación redactada) |
| [redactExact](#redactExact--) | Aplana la anotación y redacta el contenido de la página (es decir, elimina el texto y el contenido de imagen exactamente bajo la anotación redactada) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Establece el color del borde que se dibuja cuando la redacción no está activa. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Obtiene o establece la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Establece el color para rellenar la anotación. |
| [setFontSize](#setFontSize-float-) | Establece el tamaño de fuente para OverlayText. El valor predeterminado es 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Establece el texto para imprimir en la anotación de redacción. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Una matriz de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Establece una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación. |
| [setRepeat](#setRepeat-boolean-) | Si es verdadero, el texto superpuesto se repetirá en la anotación. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación del Texto superpuesto. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Constructor de RedactionAnnotation. Para usar en Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructor de RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### flatten {#flatten--}
```
public void flatten()
```

Aplana la anotación, es decir, elimina la anotación y agrega su contenido

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Obtiene el color del borde que se dibuja cuando la redacción no está activa.

**Returns:**
Valor de color

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Obtiene o establece la cadena de apariencia predeterminada que se usará al formatear el texto.

**Returns:**
valor String

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Obtiene el color para rellenar la anotación.

**Returns:**
valor de color

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Obtiene el tamaño de fuente para OverlayText.

**Returns:**
valor int

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Obtiene el texto para imprimir en la anotación de redacción.

**Returns:**
valor de cadena

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Una matriz de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar.

**Returns:**
matriz de puntos

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Obtiene una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación.

**Returns:**
matriz de valores Point

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Obtiene la alineación del Texto superpuesto.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Si es verdadero, el texto superpuesto se repetirá en la anotación.

**Returns:**
valor booleano

### redact {#redact--}
```
public void redact()
```

Aplana la anotación y redacta el contenido de la página (es decir, elimina el texto y el contenido de imagen bajo la anotación redactada)

### redactExact {#redactExact--}
```
public void redactExact()
```

Aplana la anotación y redacta el contenido de la página (es decir, elimina el texto y el contenido de imagen exactamente bajo la anotación redactada)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Establece el color del borde que se dibuja cuando la redacción no está activa.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Obtiene o establece la cadena de apariencia predeterminada que se usará al formatear el texto.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Establece el color para rellenar la anotación.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Establece el tamaño de fuente para OverlayText. El valor predeterminado es 10.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSize |  | valor int |

### setOverlayText {#setOverlayText-java.lang.String-}
Establece el texto para imprimir en la anotación de redacción.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Una matriz de números 8xN que especifica las coordenadas de la región de contenido que se pretende eliminar.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Establece una matriz de puntos que especifica las coordenadas de n cuadriláteros. Cada cuadrilátero abarca una palabra o un grupo de palabras contiguas en el texto subyacente a la anotación.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Si es verdadero, el texto superpuesto se repetirá en la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación del Texto superpuesto.
