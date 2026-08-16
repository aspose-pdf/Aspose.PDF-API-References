---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un FloatingBox en un documento PDF. FloatingBox está posicionado de forma personalizada."
type: docs
weight: 1610
url: /es/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Representa un FloatingBox en un documento PDF. FloatingBox está posicionado de forma personalizada.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Inicializa una nueva instancia de la clase {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | Inicializa una nueva instancia de la clase {@code FloatingBox} con ancho y altura especificados. |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona un nuevo objeto {@code FloatingBox}. Los párrafos en la caja flotante no se clonan. |
| [getBackgroundColor](#getBackgroundColor--) | Obtiene un objeto que indica el color de fondo del cuadro flotante. |
| [getBackgroundImage](#getBackgroundImage--) | Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento). |
| [getBorder](#getBorder--) | Obtiene un objeto que indica la información del borde del cuadro flotante. |
| [getColumnInfo](#getColumnInfo--) | Obtiene la información de una columna |
| [getHeight](#getHeight--) | Obtiene un valor flotante que indica la altura del cuadro flotante. |
| [getLeft](#getLeft--) | Obtiene la coordenada izquierda de la tabla. |
| [getPadding](#getPadding--) | Obtiene un objeto que indica el relleno del cuadro flotante. |
| [getParagraphs](#getParagraphs--) | Obtiene una colección que indica todos los párrafos en la celda. |
| [getPositioningMode](#getPositioningMode--) | Especifica la variante para determinar la ubicación del FloatingBox en la página. |
| [getTop](#getTop--) | Obtiene la coordenada superior de la tabla. |
| [getWidth](#getWidth--) | Obtiene un valor flotante que indica el ancho del cuadro flotante. |
| [isNeedRepeating](#isNeedRepeating--) | Obtiene un valor booleano que indica si el párrafo debe repetirse en la página siguiente. El valor predeterminado es true. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que su ReferenceParagraphID hace referencia están incluidos en RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Establece un objeto que indica el color de fondo del cuadro flotante. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Establece un objeto que indica la información del borde del cuadro flotante. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Establece la información de una columna |
| [setHeight](#setHeight-double-) | Establece un valor flotante que indica la altura del cuadro flotante. |
| [setLeft](#setLeft-double-) | Establece la coordenada izquierda de la tabla. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Establece un valor booleano que indica si el párrafo debe repetirse en la página siguiente. El valor predeterminado es true. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que su ReferenceParagraphID hace referencia están incluidos en RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Establece un objeto que indica el relleno del cuadro flotante. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Establece una colección que indica todos los párrafos en la celda. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Especifica la variante para determinar la ubicación del FloatingBox en la página. |
| [setTop](#setTop-double-) | Establece la coordenada superior de la tabla. |
| [setWidth](#setWidth-double-) | Establece un valor flotante que indica el ancho del cuadro flotante. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Inicializa una nueva instancia de la clase {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Inicializa una nueva instancia de la clase {@code FloatingBox} con ancho y altura especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | El ancho del cuadro. |
| altura |  | La altura del cuadro. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona un nuevo objeto {@code FloatingBox}. Los párrafos en la caja flotante no se clonan.

**Returns:**
El nuevo objeto {@code FloatingBox}.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtiene un objeto que indica el color de fondo del cuadro flotante.

**Returns:**
objeto que indica el color de fondo.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento).

**Returns:**
Instancia de imagen

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtiene un objeto que indica la información del borde del cuadro flotante.

**Returns:**
objeto que indica la información del borde.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Obtiene la información de una columna

**Returns:**
objeto ColumnInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtiene un valor flotante que indica la altura del cuadro flotante.

**Returns:**
valor que indica la altura.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtiene la coordenada izquierda de la tabla.

**Returns:**
coordenada izquierda de la tabla.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Obtiene un objeto que indica el relleno del cuadro flotante.

**Returns:**
objeto que indica el relleno.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtiene una colección que indica todos los párrafos en la celda.

**Returns:**
colección que indica todos los párrafos.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Especifica la variante para determinar la ubicación del FloatingBox en la página.

**Returns:**
elemento ParagraphPositioningMode

### getTop {#getTop--}
```
public double getTop()
```

Obtiene la coordenada superior de la tabla.

**Returns:**
coordenada superior de la tabla.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene un valor flotante que indica el ancho del cuadro flotante.

**Returns:**
valor double

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Obtiene un valor booleano que indica si el párrafo debe repetirse en la página siguiente. El valor predeterminado es true. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que su ReferenceParagraphID hace referencia están incluidos en RepeatingRows.

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Establece un objeto que indica el color de fondo del cuadro flotante.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtiene o establece la imagen de fondo para la página (solo para el generador, no se completa al leer el documento).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Establece un objeto que indica la información del borde del cuadro flotante.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Establece la información de una columna

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Establece un valor flotante que indica la altura del cuadro flotante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor que indica la altura. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Establece la coordenada izquierda de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | coordenada izquierda de la tabla. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Establece un valor booleano que indica si el párrafo debe repetirse en la página siguiente. El valor predeterminado es true. El atributo solo es válido cuando tanto el propio párrafo como el objeto al que su ReferenceParagraphID hace referencia están incluidos en RepeatingRows.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Establece un objeto que indica el relleno del cuadro flotante.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Establece una colección que indica todos los párrafos en la celda.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Especifica la variante para determinar la ubicación del FloatingBox en la página.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Establece la coordenada superior de la tabla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | coordenada superior de la tabla. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece un valor flotante que indica el ancho del cuadro flotante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |
