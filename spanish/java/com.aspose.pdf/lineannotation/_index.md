---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una anotación de línea."
type: docs
weight: 2710
url: /es/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Clase que representa una anotación de línea.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Constructor para usar con Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Crea una nueva anotación de línea en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un visitante para el procesamiento de anotaciones. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Actualiza los puntos de inicio y fin, de acuerdo con la transformación de la matriz. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getCaptionOffset](#getCaptionOffset--) | Obtiene el desplazamiento del texto del título desde su posición normal. |
| [getCaptionPosition](#getCaptionPosition--) | Obtiene la posición del título de la anotación. |
| [getEnding](#getEnding--) | Obtiene el punto final de la línea. |
| [getEndingStyle](#getEndingStyle--) | Obtiene el estilo de terminación para el punto final de la línea. |
| [getIntent](#getIntent--) | Obtiene la intención de la anotación de línea. |
| [getInteriorColor](#getInteriorColor--) | Obtiene el color interior de la anotación. |
| [getLeaderLine](#getLeaderLine--) | Obtiene la longitud de la línea guía. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Obtiene la longitud de la extensión de la línea guía. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Obtiene el desplazamiento de la línea guía. |
| [getMeasure](#getMeasure--) | Unidades de medida especificadas para esta anotación. |
| [getShowCaption](#getShowCaption--) | Obtiene la bandera booleana que determina si el contenido debe mostrarse como título. |
| [getStarting](#getStarting--) | Obtiene el punto de inicio de la línea. |
| [getStartingStyle](#getStartingStyle--) | Obtiene el estilo de terminación de línea para el punto de inicio de la línea. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Establece el desplazamiento del texto del título desde su posición normal. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Establece la posición del título de la anotación. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Establece el punto final de la línea. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Establece el estilo de terminación para el punto final de la línea. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Establece la intención de la anotación de línea. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Establece el color interior de la anotación. |
| [setLeaderLine](#setLeaderLine-double-) | Establece la longitud de la línea guía. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Establece la longitud de la extensión de la línea guía. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Establece el desplazamiento de la línea guía. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unidades de medida especificadas para esta anotación. |
| [setShowCaption](#setShowCaption-boolean-) | Establece la bandera booleana que determina si el contenido debe mostrarse como leyenda. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Establece el punto de inicio de la línea. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Establece el estilo de terminación de línea para el punto de inicio de la línea. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Constructor para usar con Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Crea una nueva anotación de línea en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un visitante para el procesamiento de anotaciones.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Actualiza los puntos de inicio y fin, de acuerdo con la transformación de la matriz.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Obtiene el desplazamiento del texto del título desde su posición normal.

**Returns:**
Objeto Point

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Obtiene la posición del título de la anotación.

**Returns:**
Elemento CaptionPosition @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Obtiene el punto final de la línea.

**Returns:**
Valor del punto

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtiene el estilo de terminación para el punto final de la línea.

**Returns:**
Elemento LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Obtiene la intención de la anotación de línea.

**Returns:**
Elemento LineIntent @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Obtiene el color interior de la anotación.

**Returns:**
Objeto Color

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Obtiene la longitud de la línea guía.

**Returns:**
valor double

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Obtiene la longitud de la extensión de la línea guía.

**Returns:**
valor double

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Obtiene el desplazamiento de la línea guía.

**Returns:**
valor double

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unidades de medida especificadas para esta anotación.

**Returns:**
Objeto Measure

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Obtiene la bandera booleana que determina si el contenido debe mostrarse como título.

**Returns:**
valor booleano

### getStarting {#getStarting--}
```
public Point getStarting()
```

Obtiene el punto de inicio de la línea.

**Returns:**
Valor del punto

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Obtiene el estilo de terminación de línea para el punto de inicio de la línea.

**Returns:**
Elemento LineEnding @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Establece el desplazamiento del texto del título desde su posición normal.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Establece la posición del título de la anotación.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Establece el punto final de la línea.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Establece el estilo de terminación para el punto final de la línea.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Establece la intención de la anotación de línea.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Establece el color interior de la anotación.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Establece la longitud de la línea guía.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Establece la longitud de la extensión de la línea guía.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Establece el desplazamiento de la línea guía.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unidades de medida especificadas para esta anotación.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Establece la bandera booleana que determina si el contenido debe mostrarse como leyenda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Establece el punto de inicio de la línea.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Establece el estilo de terminación de línea para el punto de inicio de la línea.
