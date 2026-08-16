---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un segmento de texto PDF. </p> <hr> <pre> El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con el objeto {@code TextState} de {@code."
type: docs
weight: 5300
url: /es/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Representa un segmento de texto PDF. </p> <hr> <pre> El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con el objeto {@code TextState} del objeto {@code TextSegment}. // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Crear objeto TextFragmentAbsorber para encontrar todas las apariciones del texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceptar el absorber para la primera página doc.getPages().get(1).accept(absorber); // Cambiar el color de primer plano del primer segmento de texto de la primera aparición del texto absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Cambiar el tamaño de fuente del primer segmento de texto de la primera aparición del texto absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Guardar documento doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> En pocas palabras, los objetos {@code TextSegment} son hijos del objeto {@code TextFragment}. En detalle: El texto del documento PDF en {@code Aspose.Pdf} está representado por dos objetos básicos: {@code TextFragment} y {@code TextSegment} Las diferencias entre ellos dependen mayormente del contexto. Consideremos el siguiente escenario. El usuario busca el texto "hello world" para operar con él, cambiar sus propiedades, verlo, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); La representación física del texto PDF es muy compleja. El texto "hello world" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto Aspose.PDF establece básicamente que el objeto {@code TextFragment} proporciona un conjunto de operaciones lógicas único sobre el conjunto de objetos {@code TextSegment} físicos que representan la consulta del usuario. En el escenario de búsqueda de texto, {@code TextFragment} es la representación lógica del texto "hello world", y la colección de objetos {@code TextSegment} representa todos los segmentos físicos que construyen el objeto de texto "hello world". Así, {@code TextFragment} está cerca de la representación lógica del texto. Y {@code TextSegment} está cerca de la representación física del texto. Obviamente, cada objeto {@code TextSegment} puede tener su propia fuente, coloración y propiedades de posicionamiento. {@code TextFragment} ofrece una forma sencilla de cambiar el texto con sus propiedades: establecer fuente, establecer tamaño de fuente, establecer color de fuente, etc. Mientras tanto, los objetos {@code TextSegment} son accesibles y los usuarios pueden operar con los objetos {@code TextSegment} de forma independiente. </pre> </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Crea un objeto TextSegment. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Crea un objeto TextSegment. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Obtiene la posición del texto, representada con el objeto {@code TextSegment}. El YIndent de la estructura Position representa la coordenada de la línea base del segmento de texto. |
| [getCharacters](#getCharacters--) | Obtiene la colección de objetos CharInfo que representan información sobre los caracteres en el segmento de texto. |
| [getEndCharIndex](#getEndCharIndex--) | Obtiene el índice del carácter final del segmento actual en el operador de visualización de texto (Tj, TJ). |
| [getHyperlink](#getHyperlink--) | Obtiene o establece el hipervínculo del segmento (para el generador de pdf). |
| [getPosition](#getPosition--) | Obtiene la posición del texto, representada con el objeto {@code TextSegment}. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo del TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | Obtiene el índice del carácter inicial del segmento actual en el operador de visualización de texto (Tj, TJ). |
| [getText](#getText--) | Obtiene el objeto de texto {@code string} que representa el objeto {@code TextSegment}. |
| [getTextEditOptions](#getTextEditOptions--) | Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente. |
| [getTextState](#getTextState--) | <p> Obtiene o establece el estado del texto para el texto que representa el objeto {@code TextSegment}. </p> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Establece la posición del texto, representada con el objeto {@code TextSegment}. El YIndent de la estructura Position representa la coordenada de la línea base del segmento de texto. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Obtiene o establece el hipervínculo del segmento (para el generador de pdf). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Establece la posición del texto, representada con el objeto {@code TextSegment}. |
| [setText](#setText-java.lang.String-) | Establece el objeto de texto {@code string} que representa el objeto {@code TextSegment}. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Establece el estado del texto para el texto que representa el objeto {@code TextSegment}. </p> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Establece el objeto de texto {@code string} que representa el objeto {@code TextSegment} con actualización suprimida. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Crea un objeto TextSegment. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Crea un objeto TextSegment. </p> <hr> <pre> El ejemplo muestra cómo crear un objeto fragmento de texto, agregar un segmento de texto a la colección de fragmentos de texto y adjuntarlo a la página Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Obtiene la posición del texto, representada con el objeto {@code TextSegment}. El YIndent de la estructura Position representa la coordenada de la línea base del segmento de texto.

**Returns:**
Valor de posición

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Obtiene la colección de objetos CharInfo que representan información sobre los caracteres en el segmento de texto.

**Returns:**
Objeto CharInfoCollection

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Obtiene el índice del carácter final del segmento actual en el operador de visualización de texto (Tj, TJ).

**Returns:**
valor int

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Obtiene o establece el hipervínculo del segmento (para el generador de pdf).

**Returns:**
Objeto Hyperlink

### getPosition {#getPosition--}
```
public Position getPosition()
```

Obtiene la posición del texto, representada con el objeto {@code TextSegment}.

**Returns:**
Valor de posición

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo del TextSegment

**Returns:**
objeto Rectangle

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Obtiene el índice del carácter inicial del segmento actual en el operador de visualización de texto (Tj, TJ).

**Returns:**
valor int

### getText {#getText--}
```
public String getText()
```

Obtiene el objeto de texto {@code string} que representa el objeto {@code TextSegment}.

**Returns:**
valor String

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtiene las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente.

**Returns:**
Valor TextEditOptions

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Obtiene o establece el estado del texto para el texto que representa el objeto {@code TextSegment}. </p> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
Valor TextState

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Establece la posición del texto, representada con el objeto {@code TextSegment}. El YIndent de la estructura Position representa la coordenada de la línea base del segmento de texto.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Obtiene o establece el hipervínculo del segmento (para el generador de pdf).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Establece la posición del texto, representada con el objeto {@code TextSegment}.

### setText {#setText-java.lang.String-}
Establece el objeto de texto {@code string} que representa el objeto {@code TextSegment}.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Establece el estado del texto para el texto que representa el objeto {@code TextSegment}. </p> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Establece el objeto de texto {@code string} que representa el objeto {@code TextSegment} con actualización suprimida.
