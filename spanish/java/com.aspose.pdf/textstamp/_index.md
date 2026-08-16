---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un sello textual."
type: docs
weight: 5320
url: /es/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Representa un sello textual.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Inicializa una nueva instancia de la clase {@code TextStamp} con el objeto formattedText |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Inicializa una nueva instancia de la clase {@code TextStamp} con el objeto formattedText |
| [TextStamp](#TextStamp-java.lang.String-) | Inicializa una nueva instancia de la clase {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Inicializa una nueva instancia de la clase TextStamp. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Ajusta automáticamente la precisión del tamaño de fuente. Valor predeterminado: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Si está habilitado, el tamaño de fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) y {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). El ancho y alto predeterminados se derivan del rectángulo de la página. |
| [getDefaultFont](#getDefaultFont--) | Devuelve la fuente predeterminada |
| [getDefaultFontSize](#getDefaultFontSize--) | Tamaño de fuente predeterminado |
| [getDraw](#getDraw--) | Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, el sello se dibuja como texto. |
| [getFontSize](#getFontSize--) | Tamaño de fuente real después de que el sello se haya colocado. (Puede diferir del tamaño de fuente inicial proporcionado a través del constructor si la opción 'AutoAdjustFontSizeToFitStampRectangle' está habilitada.) |
| [getHeight](#getHeight--) | Altura deseada del sello en la página. |
| [getMaxRowWidth](#getMaxRowWidth--) | Altura máxima de fila para la opción WordWrap. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Obtiene o establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [getReplacementFont](#getReplacementFont--) | Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido. |
| [getTextAlignment](#getTextAlignment--) | Alineación del texto dentro del sello. |
| [getTextState](#getTextState--) | Obtiene las propiedades de texto del sello. Consulte {@code TextState} para obtener más detalles. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (valor predeterminado cuando Draw = true), el valor YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (valor predeterminado cuando Draw = false), el valor YIndent se tratará como la parte inferior (línea de descenso) del texto. |
| [getValue](#getValue--) | Obtiene el valor de cadena que se utiliza como sello en la página. |
| [getWidth](#getWidth--) | Ancho deseado del sello en la página. |
| [getWordWrapMode](#getWordWrapMode--) | Obtiene o establece el modo de ajuste de línea para la renderización de texto. |
| [isJustify](#isJustify--) | Define la justificación del texto. Si esta propiedad se establece en true, ambos bordes izquierdo y derecho del texto se alinean. Valor predeterminado: false. |
| [isScale](#isScale--) | Define el escalado del texto. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se escalará para ajustarse al ancho especificado. |
| [isWordWrap](#isWordWrap--) | Define el ajuste de línea. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor predeterminado: false. |
| [put](#put-com.aspose.pdf.Page-) | Agrega un sello textual en la página. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Ajusta automáticamente la precisión del tamaño de fuente. Valor predeterminado: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Si está habilitado, el tamaño de fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) y {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). El ancho y alto predeterminados se derivan del rectángulo de la página. |
| [setDraw](#setDraw-boolean-) | Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, el sello se dibuja como texto. |
| [setHeight](#setHeight-double-) | Altura deseada del sello en la página. |
| [setJustify](#setJustify-boolean-) | Define la justificación del texto. Si esta propiedad se establece en true, ambos bordes izquierdo y derecho del texto se alinean. Valor predeterminado: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Altura máxima de fila para la opción WordWrap. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Obtiene o establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido. |
| [setScale](#setScale-boolean-) | Define el escalado del texto. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se escalará para ajustarse al ancho especificado. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Alineación del texto dentro del sello. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (valor predeterminado cuando Draw = true), el valor YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (valor predeterminado cuando Draw = false), el valor YIndent se tratará como la parte inferior (línea de descenso) del texto. |
| [setValue](#setValue-java.lang.String-) | Establece el valor de cadena que se utiliza como sello en la página. |
| [setWidth](#setWidth-double-) | Ancho deseado del sello en la página. |
| [setWordWrap](#setWordWrap-boolean-) | Define el ajuste de línea. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor predeterminado: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Obtiene o establece el modo de ajuste de línea para la renderización de texto. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Inicializa una nueva instancia de la clase {@code TextStamp} con el objeto formattedText

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Inicializa una nueva instancia de la clase {@code TextStamp} con el objeto formattedText

### TextStamp {#TextStamp-java.lang.String-}
Inicializa una nueva instancia de la clase {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Inicializa una nueva instancia de la clase TextStamp.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Ajusta automáticamente la precisión del tamaño de fuente. Valor predeterminado: 0.1;

**Returns:**
valor flotante

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Si está habilitado, el tamaño de fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) y {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). El ancho y alto predeterminados se derivan del rectángulo de la página.

**Returns:**
valor booleano

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Devuelve la fuente predeterminada

**Returns:**
objeto com.aspose.pdf.Font

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Tamaño de fuente predeterminado

**Returns:**
valor flotante

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, el sello se dibuja como texto.

**Returns:**
valor booleano

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Tamaño de fuente real después de que el sello se haya colocado. (Puede diferir del tamaño de fuente inicial proporcionado a través del constructor si la opción 'AutoAdjustFontSizeToFitStampRectangle' está habilitada.)

**Returns:**
valor flotante

### getHeight {#getHeight--}
```
public double getHeight()
```

Altura deseada del sello en la página.

**Returns:**
valor double

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Altura máxima de fila para la opción WordWrap.

**Returns:**
valor double

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Obtiene o establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados.

**Returns:**
NoCharacterAction elemento

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido.

**Returns:**
Instancia de Font

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Alineación del texto dentro del sello.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Obtiene las propiedades de texto del sello. Consulte {@code TextState} para obtener más detalles.

**Returns:**
TextState elemento

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (valor predeterminado cuando Draw = true), el valor YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (valor predeterminado cuando Draw = false), el valor YIndent se tratará como la parte inferior (línea de descenso) del texto.

**Returns:**
valor booleano

### getValue {#getValue--}
```
public String getValue()
```

Obtiene el valor de cadena que se utiliza como sello en la página.

**Returns:**
valor String

### getWidth {#getWidth--}
```
public double getWidth()
```

Ancho deseado del sello en la página.

**Returns:**
valor double

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Obtiene o establece el modo de ajuste de línea para la renderización de texto.

**Returns:**
WordWrapMode elemento

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Define la justificación del texto. Si esta propiedad se establece en true, ambos bordes izquierdo y derecho del texto se alinean. Valor predeterminado: false.

**Returns:**
valor booleano

### isScale {#isScale--}
```
public boolean isScale()
```

Define el escalado del texto. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se escalará para ajustarse al ancho especificado.

**Returns:**
valor booleano

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Define el ajuste de línea. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor predeterminado: false.

**Returns:**
valor booleano @deprecated "Utilice WordWrapMode en su lugar."

### put {#put-com.aspose.pdf.Page-}
Agrega un sello textual en la página.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Ajusta automáticamente la precisión del tamaño de fuente. Valor predeterminado: 0.1;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Si está habilitado, el tamaño de fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) y {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). El ancho y alto predeterminados se derivan del rectángulo de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, el sello se dibuja como texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Altura deseada del sello en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Define la justificación del texto. Si esta propiedad se establece en true, ambos bordes izquierdo y derecho del texto se alinean. Valor predeterminado: false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Altura máxima de fila para la opción WordWrap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Obtiene o establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | NoCharacterAction elemento |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Define el escalado del texto. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se escalará para ajustarse al ancho especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Alineación del texto dentro del sello.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (valor predeterminado cuando Draw = true), el valor YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (valor predeterminado cuando Draw = false), el valor YIndent se tratará como la parte inferior (línea de descenso) del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setValue {#setValue-java.lang.String-}
Establece el valor de cadena que se utiliza como sello en la página.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ancho deseado del sello en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Define el ajuste de línea. Si esta propiedad se establece en true y se especifica un valor de Width, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor predeterminado: false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano @deprecated "Utilice WordWrapMode en su lugar." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Obtiene o establece el modo de ajuste de línea para la renderización de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | WordWrapMode elemento @see WordWrapMode |
