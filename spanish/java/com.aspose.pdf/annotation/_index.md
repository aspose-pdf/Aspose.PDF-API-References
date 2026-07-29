---
title: "Annotation"
linktitle: "Annotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un objeto de anotación."
type: docs
weight: 60
url: /es/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Clase que representa un objeto de anotación.

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta visitante para el procesamiento de anotaciones. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Actualiza los parámetros y la apariencia, según la transformación de la matriz. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Solo para uso interno |
| [flatten](#flatten--) | Coloca el contenido de la anotación directamente en la página, el objeto de anotación será eliminado. |
| [getActiveState](#getActiveState--) | Obtiene el estado actual de apariencia de la anotación. |
| [getAlignment](#getAlignment--) | ff / * / * Devuelve el nombre del estado "checked" según los nombres de estado existentes. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getAppearance](#getAppearance--) | Obtiene el diccionario de apariencia de la anotación. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Obtiene el índice de página (basado en 1) donde debe aparecer la anotación. |
| [getBorder](#getBorder--) | Obtiene las características del borde de la anotación. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Obtiene las características de la anotación. |
| [getColor](#getColor--) | Obtiene el color de la anotación. |
| [getContents](#getContents--) | Obtiene el texto de la anotación. |
| [getEngineDict](#getEngineDict--) | Solo interno |
| [getEngineObj](#getEngineObj--) | Solo para uso interno |
| [getFlags](#getFlags--) | Obtiene los indicadores de la anotación. |
| [getFullName](#getFullName--) | Obtiene el nombre totalmente calificado de la anotación. |
| [getHeight](#getHeight--) | Obtiene la altura de la anotación. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Obtiene o establece la alineación del texto para la anotación. |
| [getModified](#getModified--) | Obtiene la fecha y hora en que la anotación fue modificada recientemente. |
| [getModifiedInternal](#getModifiedInternal--) | Obtiene la fecha y hora en que la anotación fue modificada recientemente. |
| [getName](#getName--) | Obtiene el nombre de la anotación en la página. |
| [getNormalAppearance](#getNormalAppearance--) | Obtiene la apariencia normal. |
| [getPage](#getPage--) | Obtiene el objeto de página con el que está asociada esta anotación. |
| [getPageIndex](#getPageIndex--) | Obtiene el índice de la página que contiene la anotación. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Obtiene el índice de la página que contiene la anotación. |
| [getPdfActions](#getPdfActions--) | Obtiene la lista de acciones de la anotación. |
| [getRect](#getRect--) | Obtiene el rectángulo de la anotación. |
| [getRectangle](#getRectangle-boolean-) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| [getStates](#getStates--) | Obtiene el diccionario de apariencia de la anotación. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Obtiene la alineación del texto para la anotación. |
| [getWidth](#getWidth--) | Obtiene el ancho de la anotación. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Inicialización de instancia |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PDF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo. |
| [isUseFontSubset](#isUseFontSubset--) | Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero. |
| [setActiveState](#setActiveState-java.lang.String-) | Establece el estado actual de la apariencia de la anotación. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Alineación de la anotación. Esta propiedad está obsoleta. Use getHorizontalAlignment_Annotation_New en su lugar. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Establece el índice de página (basado en uno) donde debe aparecer la anotación. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Establece las características del borde de la anotación. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Establece el color de la anotación. |
| [setContents](#setContents-java.lang.String-) | Establece el texto de la anotación. |
| [setFlags](#setFlags-int-) | Establece los indicadores de la anotación. |
| [setHeight](#setHeight-double-) | Establece la altura de la anotación. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Obtiene o establece la alineación del texto para la anotación. |
| [setModified](#setModified-java.util.Date-) | Establece la fecha y hora en que la anotación fue modificada recientemente. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Establece la fecha y hora en que la anotación fue modificada recientemente. |
| [setName](#setName-java.lang.String-) | Establece el nombre de la anotación en la página. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Establece el rectángulo de la anotación. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación del texto para la anotación. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PDF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero. |
| [setWidth](#setWidth-double-) | Establece el ancho de la anotación. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta visitante para el procesamiento de anotaciones.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Actualiza los parámetros y la apariencia, según la transformación de la matriz.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Solo para uso interno

### flatten {#flatten--}
```
public void flatten()
```

Coloca el contenido de la anotación directamente en la página, el objeto de anotación será eliminado.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Obtiene el estado actual de apariencia de la anotación.

**Returns:**
valor String

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Devuelve el nombre del estado "checked" según los nombres de estado existentes. / * / * / *

**Returns:**
Valor de cadena /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
valor entero @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Obtiene el diccionario de apariencia de la anotación.

**Returns:**
Objeto AppearanceDictionary

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Obtiene el índice de página (basado en 1) donde debe aparecer la anotación.

**Returns:**
el índice de página (basado en uno) donde debe aparecer la anotación.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Obtiene las características del borde de la anotación. {@code Border}

**Returns:**
Objeto Border

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Obtiene las características de la anotación.

**Returns:**
Objeto Characteristics

### getColor {#getColor--}
```
public Color getColor()
```

Obtiene el color de la anotación.

**Returns:**
Objeto Color

### getContents {#getContents--}
```
public String getContents()
```

Obtiene el texto de la anotación.

**Returns:**
valor String

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Solo interno

**Returns:**
Objeto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo para uso interno

**Returns:**
Objeto interno

### getFlags {#getFlags--}
```
public int getFlags()
```

Obtiene los indicadores de la anotación.

**Returns:**
Banderas de la anotación @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Obtiene el nombre totalmente calificado de la anotación.

**Returns:**
valor String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtiene la altura de la anotación.

**Returns:**
altura de la anotación

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Obtiene o establece la alineación del texto para la anotación.

**Returns:**
alineación de texto para la anotación. @see HorizontalAlignment @deprecated Utilice la propiedad TextHorizontalAlignment

### getModified {#getModified--}
```
public Date getModified()
```

Obtiene la fecha y hora en que la anotación fue modificada recientemente.

**Returns:**
fecha y hora en que la anotación fue modificada recientemente.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Obtiene la fecha y hora en que la anotación fue modificada recientemente.

**Returns:**
objeto DateTime

### getName {#getName--}
```
public String getName()
```

Obtiene el nombre de la anotación en la página.

**Returns:**
valor String

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Obtiene la apariencia normal.

**Returns:**
objeto XForm

### getPage {#getPage--}
```
public Page getPage()
```

Obtiene el objeto de página con el que está asociada esta anotación.

**Returns:**
objeto Page

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtiene el índice de la página que contiene la anotación.

**Returns:**
valor int

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Obtiene el índice de la página que contiene la anotación.

**Returns:**
valor int

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Obtiene la lista de acciones de la anotación.

**Returns:**
instancia PdfActionCollection

### getRect {#getRect--}
```
public Rectangle getRect()
```

Obtiene el rectángulo de la anotación.

**Returns:**
objeto Rectangle

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| considerRotation |  | Si es verdadero, se tiene en cuenta la rotación de la página. |

**Returns:**
objeto Rectangle

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Obtiene el diccionario de apariencia de la anotación.

**Returns:**
Objeto AppearanceDictionary

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Obtiene la alineación del texto para la anotación.

**Returns:**
alineación de texto para la anotación. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho de la anotación.

**Returns:**
valor double, ancho de la anotación.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Inicialización de instancia

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PDF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo.

**Returns:**
valor booleano

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero.

**Returns:**
valor booleano

### setActiveState {#setActiveState-java.lang.String-}
Establece el estado actual de la apariencia de la anotación.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Alineación de la anotación. Esta propiedad está obsoleta. Use getHorizontalAlignment_Annotation_New en su lugar.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Establece el índice de página (basado en uno) donde debe aparecer la anotación.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Establece las características del borde de la anotación. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Establece el color de la anotación.

### setContents {#setContents-java.lang.String-}
Establece el texto de la anotación.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Establece los indicadores de la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | banderas de la anotación @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Establece la altura de la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | altura de la anotación |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Obtiene o establece la alineación del texto para la anotación.

### setModified {#setModified-java.util.Date-}
Establece la fecha y hora en que la anotación fue modificada recientemente.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Establece la fecha y hora en que la anotación fue modificada recientemente.

### setName {#setName-java.lang.String-}
Establece el nombre de la anotación en la página.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Establece el rectángulo de la anotación.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación del texto para la anotación.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PDF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece el ancho de la anotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | ancho de la anotación. |
