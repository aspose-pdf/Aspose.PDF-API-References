---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa el estado de texto de un fragmento de texto. </p> <hr> <pre> El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con el objeto {@code TextState}. // Open. </pre>"
type: docs
weight: 5150
url: /es/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Representa el estado de texto de un fragmento de texto. </p> <hr> <pre> El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con el objeto {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: fuente ({@code TextFragmentState.Font} property) tamaño de fuente ({@code TextFragmentState.FontSize} property) estilo de fuente ({@code TextFragmentState.FontStyle} property) color de primer plano ({@code TextFragmentState.ForegroundColor} property) color de fondo ({@code TextFragmentState.BackgroundColor} property) </p> <p> Nota que cambiar las propiedades {@code TextFragmentState} puede cambiar la colección interna {@code TextFragment.Segments} porque TextFragment es un objeto agregado y puede reorganizar los segmentos internos o combinarlos en un solo segmento. Si su requisito es dejar la colección {@code TextFragment.Segments} sin cambios, por favor cambie los segmentos internos individualmente. </p> @see TextFragmentAbsorber @see IDocument

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Inicializa una nueva instancia del objeto {@code TextFragmentState} con el objeto {@code TextFragment} especificado. Esta inicialización de {@code TextFragmentState} no está soportada. TextFragmentState solo está disponible con la propiedad {@code TextFragment.TextState}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Aplica configuraciones de otro textState </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Aplica configuraciones de otro textState |
| [getBackgroundColor](#getBackgroundColor--) | Establece el color de fondo del texto, representado por el objeto {@code TextFragment} |
| [getCharacterSpacing](#getCharacterSpacing--) | Obtiene el espaciado de caracteres del texto, representado por el objeto {@code TextFragment}. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Obtiene la bandera de dibujo del borde del rectángulo de texto. |
| [getFont](#getFont--) | Obtiene la fuente del texto, representada por el objeto {@code TextFragment} |
| [getFontSize](#getFontSize--) | Obtiene el tamaño de fuente del texto, representado por el objeto {@code TextFragment} |
| [getFontStyle](#getFontStyle--) | Establece el estilo de fuente del texto, representado por el objeto {@code TextFragment} |
| [getForegroundColor](#getForegroundColor--) | Obtiene el color de primer plano del texto, representado por el objeto {@code TextFragment} |
| [getFormattingOptions](#getFormattingOptions--) | Obtiene o establece opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Obtiene la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextFragmentState.VerticalAlignment funciona solo en escenarios de generación de documentos nuevos. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Obtiene el escalado horizontal del texto, representado por el objeto {@code TextFragment}. |
| [getLineSpacing](#getLineSpacing--) | <p> Obtiene el interlineado del texto. </p> |
| [getRenderingMode](#getRenderingMode--) | Obtiene o establece el modo de renderizado del texto. |
| [getRotation](#getRotation--) | Obtiene o establece el ángulo de rotación en grados. |
| [getStrokingColor](#getStrokingColor--) | Obtiene o establece las operaciones de trazo de color del renderizado de {@code TextFragment} (texto con trazo, borde del rectángulo) |
| [getTabStops](#getTabStops--) | <p> Obtiene los tabuladores para el texto. </p> <hr> <p> Tenga en cuenta que la propiedad Tabstops funciona solo en escenarios de generación de documentos nuevos. Los tabuladores pueden añadirse durante la inicialización de {@code TextFragment}. Los tabuladores deben construirse antes del texto. </p> |
| [getTextHeight](#getTextHeight--) | Obtiene la altura del texto, representada por el objeto {@code TextFragment} |
| [getWordSpacing](#getWordSpacing--) | Obtiene el espaciado entre palabras del texto. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Comprueba si la cadena de entrada puede colocarse dentro del rectángulo definido. |
| [isInvisible](#isInvisible--) | Obtiene la invisibilidad del texto. |
| [isStrikeOut](#isStrikeOut--) | Obtiene o establece el tachado del texto, representado por el objeto {@link TextFragment} |
| [isSubscript](#isSubscript--) | Obtiene o establece el subíndice del texto, representado por el objeto {@code TextFragment}. |
| [isSuperscript](#isSuperscript--) | Obtiene o establece el superíndice del texto, representado por el objeto {@code TextFragment}. |
| [isUnderline](#isUnderline--) | Obtiene o establece el subrayado del texto, representado por el objeto {@link TextFragment} |
| [measureHeight](#measureHeight-char-) | Mide la altura del carácter. |
| [measureString](#measureString-java.lang.String-) | Mide la cadena. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Establece el color de fondo del texto, representado por el objeto TextFragment |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Establece el espaciado de caracteres del texto, representado por el objeto {@code TextFragment}. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Establece la bandera de dibujo del borde del rectángulo de texto. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Establece la fuente del texto, representada por el objeto {@code TextFragment} |
| [setFontSize](#setFontSize-float-) | Establece el tamaño de fuente del texto, representado por el objeto {@code TextFragment} |
| [setFontStyle](#setFontStyle-int-) | Establece el estilo de fuente del texto, representado por el objeto {@link TextFragment} |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Establece el color de primer plano del texto, representado por el objeto {@code TextFragment} |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Obtiene o establece opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Establece la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextFragmentState.VerticalAlignment funciona solo en escenarios de generación de documentos nuevos. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Establece el escalado horizontal del texto, representado por el objeto {@code TextFragment}. |
| [setInvisible](#setInvisible-boolean-) | Establece la invisibilidad del texto. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Establece el interlineado del texto. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Obtiene o establece el modo de renderizado del texto. |
| [setRotation](#setRotation-double-) | Obtiene o establece el ángulo de rotación en grados. |
| [setStrikeOut](#setStrikeOut-boolean-) | Establece el tachado del texto, representado por el objeto {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Obtiene o establece las operaciones de trazo de color del renderizado de {@code TextFragment} (texto con trazo, borde del rectángulo) |
| [setSubscript](#setSubscript-boolean-) | Obtiene o establece el subíndice del texto, representado por el objeto {@code TextFragment}. |
| [setSuperscript](#setSuperscript-boolean-) | Obtiene o establece el superíndice del texto, representado por el objeto {@code TextFragment}. |
| [setUnderline](#setUnderline-boolean-) | Establece el subrayado del texto, representado por el objeto {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Establece el espaciado entre palabras del texto. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Inicializa una nueva instancia del objeto {@code TextFragmentState} con el objeto {@code TextFragment} especificado. Esta inicialización de {@code TextFragmentState} no está soportada. TextFragmentState solo está disponible con la propiedad {@code TextFragment.TextState}.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Aplica configuraciones de otro textState </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Aplica configuraciones de otro textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Establece el color de fondo del texto, representado por el objeto {@code TextFragment}

**Returns:**
valor del objeto Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Obtiene el espaciado de caracteres del texto, representado por el objeto {@code TextFragment}.

**Returns:**
valor flotante

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto.

**Returns:**
elemento CoordinateOrigin

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Obtiene la bandera de dibujo del borde del rectángulo de texto.

**Returns:**
valor booleano

### getFont {#getFont--}
```
public Font getFont()
```

Obtiene la fuente del texto, representada por el objeto {@code TextFragment}

**Returns:**
Valor de fuente

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Obtiene el tamaño de fuente del texto, representado por el objeto {@code TextFragment}

**Returns:**
valor flotante

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Establece el estilo de fuente del texto, representado por el objeto {@code TextFragment}

**Returns:**
elemento FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Obtiene el color de primer plano del texto, representado por el objeto {@code TextFragment}

**Returns:**
Objeto Color

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Obtiene o establece opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador.

**Returns:**
instancia de TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Obtiene la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextFragmentState.VerticalAlignment funciona solo en escenarios de generación de documentos nuevos. </p>

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Obtiene el escalado horizontal del texto, representado por el objeto {@code TextFragment}.

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
elemento TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtiene o establece el ángulo de rotación en grados.

**Returns:**
valor double

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Obtiene o establece las operaciones de trazo de color del renderizado de {@code TextFragment} (texto con trazo, borde del rectángulo)

**Returns:**
Instancia de Color

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Obtiene los tabuladores para el texto. </p> <hr> <p> Tenga en cuenta que la propiedad Tabstops funciona solo en escenarios de generación de documentos nuevos. Los tabuladores pueden añadirse durante la inicialización de {@code TextFragment}. Los tabuladores deben construirse antes del texto. </p>

**Returns:**
objeto TabStops

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Obtiene la altura del texto, representada por el objeto {@code TextFragment}

**Returns:**
valor flotante

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Obtiene el espaciado entre palabras del texto.

**Returns:**
valor flotante

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Comprueba si la cadena de entrada puede colocarse dentro del rectángulo definido.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Obtiene la invisibilidad del texto.

**Returns:**
valor booleano

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Obtiene o establece el tachado del texto, representado por el objeto {@link TextFragment}

**Returns:**
valor booleano

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Obtiene o establece el subíndice del texto, representado por el objeto {@code TextFragment}.

**Returns:**
valor booleano

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Obtiene o establece el superíndice del texto, representado por el objeto {@code TextFragment}.

**Returns:**
valor booleano

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Obtiene o establece el subrayado del texto, representado por el objeto {@link TextFragment}

**Returns:**
valor booleano

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Establece el color de fondo del texto, representado por el objeto TextFragment

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Establece el espaciado de caracteres del texto, representado por el objeto {@code TextFragment}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor renderización del texto.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Establece la bandera de dibujo del borde del rectángulo de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFont {#setFont-com.aspose.pdf.Font-}
Establece la fuente del texto, representada por el objeto {@code TextFragment}

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Establece el tamaño de fuente del texto, representado por el objeto {@code TextFragment}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Establece el estilo de fuente del texto, representado por el objeto {@link TextFragment}

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Establece el color de primer plano del texto, representado por el objeto {@code TextFragment}

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Obtiene o establece opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Establece la alineación horizontal del texto. </p> <hr> <p> HorizontalAlignment.None es igual a HorizontalAlignment.Left. Tenga en cuenta que la propiedad TextFragmentState.VerticalAlignment funciona solo en escenarios de generación de documentos nuevos. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Establece el escalado horizontal del texto, representado por el objeto {@code TextFragment}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Establece la invisibilidad del texto.

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

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Obtiene o establece el ángulo de rotación en grados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

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
Obtiene o establece las operaciones de trazo de color del renderizado de {@code TextFragment} (texto con trazo, borde del rectángulo)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Obtiene o establece el subíndice del texto, representado por el objeto {@code TextFragment}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Obtiene o establece el superíndice del texto, representado por el objeto {@code TextFragment}.

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
