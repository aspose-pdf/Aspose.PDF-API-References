---
title: "TextState"
linktitle: "TextState"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el estado de un texto"
type: docs
weight: 5340
url: /es/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Representa el estado de un texto

## Campos

| Campo | Descripción |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Valor predeterminado de tabulación en los anchos del carácter de espacio de la fuente predeterminada. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextState](#TextState--) | Crea un objeto de estado de texto. |
| [TextState](#TextState-java.awt.Color-) | Crea un objeto de estado de texto. |
| [TextState](#TextState-java.awt.Color-double-) | Crea un objeto de estado de texto. |
| [TextState](#TextState-double-) | Crea un objeto de estado de texto con especificación de tamaño de fuente. |
| [TextState](#TextState-java.lang.String-) | Crea un objeto de estado de texto. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Crea un objeto de estado de texto. |
| [TextState](#TextState-java.lang.String-double-) | Crea un objeto de estado de texto. |

## Métodos

| Método | Descripción |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Aplica configuraciones de otro textState </p> <hr> <p> Sólo se copiarán aquellas propiedades que fueron modificadas explícitamente. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Calcula el tamaño de fuente para el rectángulo. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Obtiene el color de fondo del texto. </p> <hr> <p> Tenga en cuenta que el valor no se conserva como una característica del texto dentro del documento. El getter de la propiedad BackgroundColor funciona para un objeto en caso de que haya sido establecido explícitamente previamente con el setter BackgroundColor para ese objeto. La propiedad es utilizada por el tiempo de ejecución en el contexto del proceso actual de generación/modificación. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtiene el espaciado de caracteres del texto. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto. |
| [getFont](#getFont--) | Obtiene la fuente del texto. |
| [getfontSize](#getfontSize--) | Representa el método getfontSize |
| [getFontSize](#getFontSize--) | Obtiene el tamaño de fuente del texto. |
| [getFontStyle](#getFontStyle--) | Establece el estilo de fuente del texto. |
| [getForegroundColor](#getForegroundColor--) | Obtiene el color de primer plano del texto. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Obtiene la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextState.HorizontalAlignment funciona solo en escenarios de generación de documentos nuevos. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtiene el escalado horizontal del texto. |
| [getLineSpacing](#getLineSpacing--) | <p> Obtiene el interlineado del texto. </p> |
| [getRenderingMode](#getRenderingMode--) | Obtiene o establece el modo de renderizado del texto. |
| [getStrokingColor](#getStrokingColor--) | Obtiene o establece el color de primer plano del texto. |
| [getTabTag](#getTabTag--) | <p> Puedes colocar esta etiqueta en el texto para declarar tabulación. </p> <hr> <p> Tiene efecto solo en combinación con {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Obtiene la altura del texto. |
| [getWordSpacing](#getWordSpacing--) | Obtiene el espaciado entre palabras del texto. |
| [isInvisible](#isInvisible--) | Obtiene la invisibilidad del texto. Esto básicamente refleja el estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), excepto en algunos casos especiales (como recorte). |
| [isStrikeOut](#isStrikeOut--) | Obtiene el tachado del texto, representado por el objeto {@code TextFragment} |
| [isSubscript](#isSubscript--) | Obtiene o establece el subíndice del texto. |
| [isSuperscript](#isSuperscript--) | Obtiene el superíndice del texto. |
| [isUnderline](#isUnderline--) | Obtiene el subrayado del texto, representado por el objeto {@code TextFragment} |
| [measureHeight](#measureHeight-char-) | Mide la altura del carácter. |
| [measureString](#measureString-java.lang.String-) | Mide la cadena. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Mide la cadena. </p> <hr> <p> insideLine indica que la cadena no termina. En caso de que se mida solo una parte de la cadena completa, insideLine debe ser true. En caso de que se mida la cadena completa, insideLine debe ser false. En otras palabras: cuando insideLine = true solo se tienen en cuenta los anchos de los caracteres. No se consideran transformaciones adicionales cuando insideLine = false. El final de la cadena se maneja correctamente: se tiene en cuenta la transformación en cursiva. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Establece el color de fondo del texto. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Establece el espaciado de caracteres del texto. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Obtiene la fuente del texto. |
| [setFontSize](#setFontSize-float-) | Establece el tamaño de fuente del texto. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Establece el tamaño de fuente del texto con actualización suprimida. |
| [setFontStyle](#setFontStyle-int-) | Establece el estilo de fuente del texto. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Obtiene la fuente del texto con actualización suprimida. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Establece el color de primer plano del texto. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Establece la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextState.HorizontalAlignment funciona solo en escenarios de generación de documentos nuevos. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Establece el escalado horizontal del texto. |
| [setInvisible](#setInvisible-boolean-) | Establece la invisibilidad del texto. Esto básicamente refleja el estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), excepto en algunos casos especiales (como el recorte). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Establece el interlineado del texto. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Obtiene o establece el modo de renderizado del texto. |
| [setStrikeOut](#setStrikeOut-boolean-) | Establece el tachado del texto, representado por el objeto {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Obtiene o establece el color de primer plano del texto. |
| [setSubscript](#setSubscript-boolean-) | Obtiene o establece el subíndice del texto. |
| [setSuperscript](#setSuperscript-boolean-) | Establece el superíndice del texto. |
| [setUnderline](#setUnderline-boolean-) | Establece el subrayado del texto, representado por el objeto {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Establece el espaciado entre palabras del texto. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Valor predeterminado de tabulación en los anchos del carácter de espacio de la fuente predeterminada.

### TextState {#TextState--}
```
public TextState()
```

Crea un objeto de estado de texto.

### TextState {#TextState-java.awt.Color-}
Crea un objeto de estado de texto.

### TextState {#TextState-java.awt.Color-double-}
Crea un objeto de estado de texto.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Crea un objeto de estado de texto con especificación de tamaño de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSize |  | Tamaño de fuente. |

### TextState {#TextState-java.lang.String-}
Crea un objeto de estado de texto.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Crea un objeto de estado de texto.

### TextState {#TextState-java.lang.String-double-}
Crea un objeto de estado de texto.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Aplica configuraciones de otro textState </p> <hr> <p> Sólo se copiarán aquellas propiedades que fueron modificadas explícitamente. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Calcula el tamaño de fuente para el rectángulo.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Obtiene el color de fondo del texto. </p> <hr> <p> Tenga en cuenta que el valor no se conserva como una característica del texto dentro del documento. El getter de la propiedad BackgroundColor funciona para un objeto en caso de que haya sido establecido explícitamente previamente con el setter BackgroundColor para ese objeto. La propiedad es utilizada por el tiempo de ejecución en el contexto del proceso actual de generación/modificación. </p>

**Returns:**
Valor de color

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Obtiene el espaciado de caracteres del texto.

**Returns:**
valor flotante

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto.

**Returns:**
elemento CoordinateOrigin

### getFont {#getFont--}
```
public Font getFont()
```

Obtiene la fuente del texto.

**Returns:**
objeto Font

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Representa el método getfontSize

**Returns:**
valor flotante

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Obtiene el tamaño de fuente del texto.

**Returns:**
valor flotante

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Establece el estilo de fuente del texto.

**Returns:**
elemento FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Obtiene el color de primer plano del texto.

**Returns:**
Valor de color

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Obtiene la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextState.HorizontalAlignment funciona solo en escenarios de generación de documentos nuevos. </p>

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Obtiene el escalado horizontal del texto.

**Returns:**
valor flotante

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Obtiene el interlineado del texto. </p>

**Returns:**
valor flotante <hr> <p> Tenga en cuenta que el valor no se conserva como una característica de texto dentro del documento. El getter de la propiedad LineSpacing funciona para un objeto en caso de que haya sido establecido explícitamente previamente con el setter LineSpacing para esos objetos. La propiedad es utilizada por el tiempo de ejecución en el contexto del proceso actual de generación/modificación. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Obtiene o establece el modo de renderizado del texto.

**Returns:**
elemento TextRenderingMode @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Obtiene o establece el color de primer plano del texto.

**Returns:**
Instancia de Color

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Puedes colocar esta etiqueta en el texto para declarar tabulación. </p> <hr> <p> Tiene efecto solo en combinación con {@code TabStops}. </p>

**Returns:**
valor de cadena "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Obtiene la altura del texto.

**Returns:**
valor flotante

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Obtiene el espaciado entre palabras del texto.

**Returns:**
valor flotante

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Obtiene la invisibilidad del texto. Esto básicamente refleja el estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), excepto en algunos casos especiales (como recorte).

**Returns:**
valor booleano

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Obtiene el tachado del texto, representado por el objeto {@code TextFragment}

**Returns:**
valor booleano

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Obtiene o establece el subíndice del texto.

**Returns:**
valor booleano

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Obtiene el superíndice del texto.

**Returns:**
valor booleano

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Obtiene el subrayado del texto, representado por el objeto {@code TextFragment}

**Returns:**
valor booleano

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Mide la altura del carácter.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| carácter |  | Carácter a medir. |

**Returns:**
Altura del carácter si se puede obtener de la fuente; de lo contrario 0.

### measureString {#measureString-java.lang.String-}
Mide la cadena.

### measureString {#measureString-java.lang.String-boolean-}
<p> Mide la cadena. </p> <hr> <p> insideLine indica que la cadena no termina. En caso de que se mida solo una parte de la cadena completa, insideLine debe ser true. En caso de que se mida la cadena completa, insideLine debe ser false. En otras palabras: cuando insideLine = true solo se tienen en cuenta los anchos de los caracteres. No se consideran transformaciones adicionales cuando insideLine = false. El final de la cadena se maneja correctamente: se tiene en cuenta la transformación en cursiva. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Establece el color de fondo del texto.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Establece el espaciado de caracteres del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto.

### setFont {#setFont-com.aspose.pdf.Font-}
Obtiene la fuente del texto.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Establece el tamaño de fuente del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Establece el tamaño de fuente del texto con actualización suprimida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Establece el estilo de fuente del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor FontStyles @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Obtiene la fuente del texto con actualización suprimida.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Establece el color de primer plano del texto.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Establece la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextState.HorizontalAlignment funciona solo en escenarios de generación de documentos nuevos. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Establece el escalado horizontal del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Establece la invisibilidad del texto. Esto básicamente refleja el estado {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), excepto en algunos casos especiales (como el recorte).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Establece el interlineado del texto. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante <hr> <p> Tenga en cuenta que el valor no se conserva como una característica de texto dentro del documento. El getter de la propiedad LineSpacing funciona para un objeto en caso de que haya sido establecido explícitamente previamente con el setter LineSpacing para esos objetos. La propiedad es utilizada por el tiempo de ejecución en el contexto del proceso actual de generación/modificación. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Obtiene o establece el modo de renderizado del texto.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Establece el tachado del texto, representado por el objeto {@code TextFragment}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Obtiene o establece el color de primer plano del texto.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Obtiene o establece el subíndice del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Establece el superíndice del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Establece el subrayado del texto, representado por el objeto {@code TextFragment}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Establece el espaciado entre palabras del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |
