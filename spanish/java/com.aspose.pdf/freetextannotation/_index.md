---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en su lugar."
type: docs
weight: 1790
url: /es/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Constructor para usar con Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Crea una nueva anotación FreeText en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getCallout](#getCallout--) | Arreglo de puntos que especifica la línea de llamada. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtiene la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Objeto que representa la apariencia predeterminada de la anotación FreeText. |
| [getDefaultStyle](#getDefaultStyle--) | Obtiene una cadena de estilo predeterminada. |
| [getEndingStyle](#getEndingStyle--) | Obtiene el estilo de terminación de línea para el punto final de la línea. |
| [getIntent](#getIntent--) | Obtiene la intención de la anotación de texto libre. |
| [getJustification](#getJustification--) | Obtiene un código que especifica la forma de justificación (quadding) que se usará al mostrar el texto de la anotación. |
| [getRotate](#getRotate--) | Ángulo de rotación de la anotación. |
| [getStartingStyle](#getStartingStyle--) | Obtiene o establece el estilo de terminación de línea para el punto final de la línea. Esta propiedad está obsoleta, por favor use EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Rectángulo que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación. |
| [getTextStyle](#getTextStyle--) | Obtiene o establece el estilo del texto en la apariencia. Cuando el estilo del texto cambia, la apariencia del texto se actualiza. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Arreglo de puntos que especifica la línea de llamada. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Establece la cadena de apariencia predeterminada que se usará al formatear el texto. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Establece una cadena de estilo predeterminada. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Establece el estilo de terminación de línea para el punto final de la línea. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Establece la intención de la anotación de texto libre. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Establece un código que especifica la forma de justificación (quadding) que se usará al mostrar el texto de la anotación. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Ángulo de rotación de la anotación. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Obtiene o establece el estilo de terminación de línea para el punto final de la línea. Esta propiedad está obsoleta, por favor use EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rectángulo que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación. |
| [setTextStyle](#setTextStyle-int-int-int-) | Establece el formato determinado por el parámetro textStyle para un fragmento de texto desde el índice fromInd hasta el índice toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Establece el formato determinado por el parámetro textStyle para todo el texto de la anotación. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Establece el estilo del texto en la apariencia. Cuando el estilo del texto cambia, la apariencia del texto se actualiza. |
| [updateAppearance](#updateAppearance--) | Actualiza la Apariencia, después de que el texto haya sido cambiado/movido. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Constructor para usar con Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Crea una nueva anotación FreeText en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
valor int

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Arreglo de puntos que especifica la línea de llamada.

**Returns:**
matriz de Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Obtiene la cadena de apariencia predeterminada que se usará al formatear el texto.

**Returns:**
valor String

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Objeto que representa la apariencia predeterminada de la anotación FreeText.

**Returns:**
objeto DefaultAppearance

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Obtiene una cadena de estilo predeterminada.

**Returns:**
valor String

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtiene el estilo de terminación de línea para el punto final de la línea.

**Returns:**
valor LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Obtiene la intención de la anotación de texto libre.

**Returns:**
valor int @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Obtiene un código que especifica la forma de justificación (quadding) que se usará al mostrar el texto de la anotación.

**Returns:**
valor int @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Ángulo de rotación de la anotación.

**Returns:**
elemento Rotation @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Obtiene o establece el estilo de terminación de línea para el punto final de la línea. Esta propiedad está obsoleta, por favor use EndingStyle.

**Returns:**
elemento LineEnding

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Rectángulo que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación.

**Returns:**
Instancia de Rectangle

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Obtiene o establece el estilo del texto en la apariencia. Cuando el estilo del texto cambia, la apariencia del texto se actualiza.

**Returns:**
valor TextStyle

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Arreglo de puntos que especifica la línea de llamada.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Establece la cadena de apariencia predeterminada que se usará al formatear el texto.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Establece una cadena de estilo predeterminada.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Establece el estilo de terminación de línea para el punto final de la línea.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Establece la intención de la anotación de texto libre.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Establece un código que especifica la forma de justificación (quadding) que se usará al mostrar el texto de la anotación.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Ángulo de rotación de la anotación.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Obtiene o establece el estilo de terminación de línea para el punto final de la línea. Esta propiedad está obsoleta, por favor use EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Rectángulo que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Establece el formato determinado por el parámetro textStyle para un fragmento de texto desde el índice fromInd hasta el índice toInd.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fromInd |  | Índice inicial del fragmento de texto (desde 0). |
| toInd |  | Índice final del fragmento de texto (contando desde 0, este no está incluido). |
| textStyles |  | Estilo(s) aplicado(s) al fragmento de texto. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Establece el formato determinado por el parámetro textStyle para todo el texto de la anotación.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Establece el estilo del texto en la apariencia. Cuando el estilo del texto cambia, la apariencia del texto se actualiza.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Actualiza la Apariencia, después de que el texto haya sido cambiado/movido.
