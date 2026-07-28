---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa párrafos de texto como objeto de texto multilínea. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de párrafo de texto y añadirlo a la página Pdf. Document doc."
type: docs
weight: 5200
url: /es/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Representa párrafos de texto como un objeto de texto multilínea. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto de párrafo de texto y añadirlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // crear párrafo de texto TextParagraph paragraph = new TextParagraph(); // establecer el rectángulo del párrafo paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // establecer opciones de ajuste de palabras paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // añadir líneas de cadena paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // añadir el párrafo a la página Pdf con el TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // guardar documento Pdf doc.save(outFile); </pre>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Crea el objeto {@code TextParagraph}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Añade una línea de texto |
| [appendLine](#appendLine-java.lang.String-float-) | Añade una línea de texto. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Añade una línea de texto con parámetros de estado de texto. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Añade una línea de texto con parámetros de estado de texto. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Añade una línea de texto con parámetros de estado de texto. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Añade una línea de texto con parámetros de estado de texto. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Añade una línea de texto con parámetros de estado de texto. |
| [beginEdit](#beginEdit--) | Inicia la edición del TextParagraph. <p> Mejora el rendimiento de la población de TextParagraph. Cualquier cálculo de diseño se suspende hasta que se invoque el método EndEdit. <p> Tenga en cuenta que la invocación del método no puede estar anidada. </p> |
| [endEdit](#endEdit--) | Finaliza la edición del TextParagraph. <p> Mejora el rendimiento de la población de TextParagraph. Cualquier cálculo de diseño se suspende hasta que se invoque el método EndEdit. <p> Tenga en cuenta que la invocación del método no puede estar anidada. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Obtiene o establece el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | Obtiene opciones de formato. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene la alineación horizontal del texto dentro del Rectangle del paragrph's. HorizontalAlignment.None es igual a HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Obtiene el símbolo de guión que se usa en el proceso de guionado. El símbolo de guionado es \"-\" por defecto. Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste) establezca una cadena vacía string.Empty para HyphenSymbol. |
| [getMargin](#getMargin--) | Obtiene el relleno. |
| [getPosition](#getPosition--) | Obtiene la posición del párrafo. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo del párrafo. |
| [getRotation](#getRotation--) | Obtiene o establece el ángulo de rotación en grados. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Obtiene el valor de sangría de líneas subsiguientes. |
| [getTextRectangle](#getTextRectangle--) | Obtiene el rectángulo del texto colocado en el párrafo. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Obtiene la alineación vertical del texto dentro del {@code Rectangle} del paragrph's. </p> |
| [isJustify](#isJustify--) | Obtiene el valor que indica si el texto está justificado. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Establece el color de fondo para el párrafo de texto. |
| [setBackgroundMode](#setBackgroundMode-int-) | Establece el modo de fondo para el párrafo de texto |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Obtiene o establece el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Establece opciones de formato. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece la alineación horizontal del texto dentro del Rectangle del paragrph's. HorizontalAlignment.None es igual a HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Establece el símbolo de guión que se usa en el proceso de guionado. El símbolo de guionado es \"-\" por defecto. Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste) establezca una cadena vacía string.Empty para HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Establece el valor que indica si el texto está justificado. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Establece el relleno. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Establece la rotación del párrafo. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Establece el modo de compatibilidad con código antiguo |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Establece la posición del párrafo. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Establece el rectángulo del párrafo. |
| [setRotation](#setRotation-double-) | Obtiene o establece el ángulo de rotación en grados. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Establece el valor de sangría de líneas subsiguientes. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece la alineación vertical del texto dentro del {@code Rectangle} del paragrph's. VerticalAlignment.None es igual a VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Crea el objeto {@code TextParagraph}.

### appendLine {#appendLine-java.lang.String-}
Añade una línea de texto

### appendLine {#appendLine-java.lang.String-float-}
Añade una línea de texto.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Añade una línea de texto con parámetros de estado de texto.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Añade una línea de texto con parámetros de estado de texto.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Añade una línea de texto con parámetros de estado de texto.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Añade una línea de texto con parámetros de estado de texto.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Añade una línea de texto con parámetros de estado de texto.

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Inicia la edición del TextParagraph. <p> Mejora el rendimiento de la población de TextParagraph. Cualquier cálculo de diseño se suspende hasta que se invoque el método EndEdit. <p> Tenga en cuenta que la invocación del método no puede estar anidada. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Finaliza la edición del TextParagraph. <p> Mejora el rendimiento de la población de TextParagraph. Cualquier cálculo de diseño se suspende hasta que se invoque el método EndEdit. <p> Tenga en cuenta que la invocación del método no puede estar anidada. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Obtiene o establece el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent.

**Returns:**
valor flotante

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Obtiene opciones de formato.

**Returns:**
Objeto TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtiene la alineación horizontal del texto dentro del Rectangle del paragrph's. HorizontalAlignment.None es igual a HorizontalAlignment.Left.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Obtiene el símbolo de guión que se usa en el proceso de guionado. El símbolo de guionado es \"-\" por defecto. Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste) establezca una cadena vacía string.Empty para HyphenSymbol.

**Returns:**
valor String

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtiene el relleno.

**Returns:**
valor MarginInfo

### getPosition {#getPosition--}
```
public Position getPosition()
```

Obtiene la posición del párrafo.

**Returns:**
Valor de posición

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo del párrafo.

**Returns:**
objeto Rectangle

### getRotation {#getRotation--}
```
public double getRotation()
```

Obtiene o establece el ángulo de rotación en grados.

**Returns:**
valor double

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Obtiene el valor de sangría de líneas subsiguientes.

**Returns:**
valor flotante

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Obtiene el rectángulo del texto colocado en el párrafo.

**Returns:**
objeto Rectangle

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Obtiene la alineación vertical del texto dentro del {@code Rectangle} del paragrph's. </p>

**Returns:**
Valor de VerticalAlignment @see VerticalAlignment <hr> <p> VerticalAlignment.None es igual a VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Obtiene el valor que indica si el texto está justificado.

**Returns:**
valor booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Establece el color de fondo para el párrafo de texto.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Establece el modo de fondo para el párrafo de texto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor int @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Obtiene o establece el valor de sangría de líneas subsiguientes. Si se establece en un valor distinto de cero, tiene una ventaja sobre el valor FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Establece opciones de formato.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece la alineación horizontal del texto dentro del Rectangle del paragrph's. HorizontalAlignment.None es igual a HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Establece el símbolo de guión que se usa en el proceso de guionado. El símbolo de guionado es \"-\" por defecto. Para eliminar el dibujo del guión (manteniendo el procedimiento de ajuste) establezca una cadena vacía string.Empty para HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Establece el valor que indica si el texto está justificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Establece el relleno.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Establece la rotación del párrafo.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Establece el modo de compatibilidad con código antiguo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Establece la posición del párrafo.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Establece el rectángulo del párrafo.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Obtiene o establece el ángulo de rotación en grados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Establece el valor de sangría de líneas subsiguientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece la alineación vertical del texto dentro del {@code Rectangle} del paragrph's. VerticalAlignment.None es igual a VerticalAlignment.Bottom.
