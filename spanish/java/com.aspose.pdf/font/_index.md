---
title: "Fuente"
linktitle: "Fuente"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un objeto de fuente. </p> <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y cambiar la fuente de la primera coincidencia encontrada. // Open document Document doc."
type: docs
weight: 1650
url: /es/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Representa un objeto de fuente. </p> <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y cambiar la fuente de la primera aparición encontrada. // Abrir documento Document doc = new Document(\"input.pdf\"); // Crear objeto TextFragmentAbsorber para encontrar todas las ocurrencias de texto \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Aceptar el absorber para la primera página doc.getPages().get_Item(1).accept(absorber); // Crear fuente y marcarla para incrustarla Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Cambiar la fuente de la primera aparición de texto absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Guardar documento doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Métodos

| Método | Descripción |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Determina si la fuente contiene los caracteres especificados |
| [getActualFontName](#getActualFontName--) | <p> Obtiene el nombre real de la fuente del objeto {@code Font} si está inicializado. Incluso cuando la fuente está sustituida o tiene un nombre interno para pdf. O cadena vacía si la fuente no está inicializada. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Mide el punto máximo de ascenso. |
| [getBaseFont](#getBaseFont--) | Obtiene el valor BaseFont del objeto de fuente PDF. También conocido como el nombre PostScript de la fuente. |
| [getDecodedFontName](#getDecodedFontName--) | A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad "BaseFont" de la fuente PDF y a veces esta propiedad puede representarse en forma hexadecimal. Si se lee este nombre directamente, podría aparecer en forma no legible. Para obtener una forma legible es necesario decodificar el nombre de la fuente siguiendo reglas específicas para esa fuente. Esta propiedad devuelve el nombre de fuente decodificado, por lo que debe usarse en casos en los que se encuentre con un {@code FontName} no legible. Si la propiedad {@code FontName} tiene una forma legible, esta propiedad será la misma que {@code FontName}, por lo que puede usarla en cualquier caso en que necesite obtener el nombre de la fuente en una forma legible. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Mide el punto máximo de descenso. |
| [getFontName](#getFontName--) | <p> Obtiene el nombre de la fuente del objeto {@code Font}. </p> |
| [getFontOptions](#getFontOptions--) | Propiedades útiles para ajustar el comportamiento de la fuente |
| [getIFont](#getIFont--) | <p> Objeto de fuente del sistema. </p> <hr> <p> Solo para uso interno </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Objeto de fuente PDF. </p> <hr> <p> Solo para uso interno </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | El objetivo de este método es devolver la descripción del error si un intento de incrustar la fuente falló. Si no hay casos de error, devuelve una cadena vacía. |
| [getType](#getType--) | Nombre del tipo de fuente |
| [isAccessible](#isAccessible--) | <p> Obtiene indicando si la fuente está presente (instalada) en el sistema. </p> |
| [isEmbedded](#isEmbedded--) | <p> Obtiene un valor que indica si la fuente está incrustada. Una fuente basada en IFont se subestablecerá y se incrustará automáticamente </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Obtiene un valor que indica si la fuente es un subconjunto. Una fuente basada en IFont se subestablecerá y se incrustará automáticamente </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Mide la cadena. |
| [save](#save-java.io.OutputStream-) | Guarda la fuente en el flujo. Tenga en cuenta que la fuente se guarda en formato TTF intermedio destinado a usarse solo en una copia convertida del documento original. El archivo de fuente no está destinado a usarse fuera del contexto del documento original. |
| [setEmbedded](#setEmbedded-boolean-) | Establece un valor que indica si la fuente está incrustada. Una fuente basada en IFont se subestablecerá y se incrustará automáticamente |
| [setSubset](#setSubset-boolean-) | Establece un valor que indica si la fuente es un subconjunto. Una fuente basada en IFont se subestablecerá y se incrustará automáticamente |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Determina si la fuente contiene los caracteres especificados

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Obtiene el nombre real de la fuente del objeto {@code Font} si está inicializado. Incluso cuando la fuente está sustituida o tiene un nombre interno para pdf. O cadena vacía si la fuente no está inicializada. </p>

**Returns:**
Valor de cadena <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y ver el nombre real de la fuente de la primera aparición de texto. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Mide el punto máximo de ascenso.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Obtiene el valor BaseFont del objeto de fuente PDF. También conocido como el nombre PostScript de la fuente.

**Returns:**
valor String

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad "BaseFont" de la fuente PDF y a veces esta propiedad puede representarse en forma hexadecimal. Si se lee este nombre directamente, podría aparecer en forma no legible. Para obtener una forma legible es necesario decodificar el nombre de la fuente siguiendo reglas específicas para esa fuente. Esta propiedad devuelve el nombre de fuente decodificado, por lo que debe usarse en casos en los que se encuentre con un {@code FontName} no legible. Si la propiedad {@code FontName} tiene una forma legible, esta propiedad será la misma que {@code FontName}, por lo que puede usarla en cualquier caso en que necesite obtener el nombre de la fuente en una forma legible.

**Returns:**
valor String

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Mide el punto máximo de descenso.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Obtiene el nombre de la fuente del objeto {@code Font}. </p>

**Returns:**
Valor de cadena <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y ver el nombre de la fuente de la primera aparición de texto. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Propiedades útiles para ajustar el comportamiento de la fuente

**Returns:**
objeto IFontOptions

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Objeto de fuente del sistema. </p> <hr> <p> Solo para uso interno </p>

**Returns:**
objeto IFont

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Objeto de fuente PDF. </p> <hr> <p> Solo para uso interno </p>

**Returns:**
objeto IPdfFont

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

El objetivo de este método es devolver la descripción del error si un intento de incrustar la fuente falló. Si no hay casos de error, devuelve una cadena vacía.

**Returns:**
Descripción del error

### getType {#getType--}
```
public String getType()
```

Nombre del tipo de fuente

**Returns:**
Objeto String

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Obtiene indicando si la fuente está presente (instalada) en el sistema. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y obtener el valor que indica si la fuente está instalada en el sistema. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println(\"the font is installed in the system\"); </pre> <hr> <p> Algunas operaciones no están disponibles con fuentes que no se pudieron encontrar en el sistema. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Obtiene un valor que indica si la fuente está incrustada. La fuente basada en IFont se subestablecerá e incrustará automáticamente. </p> <hr> <pre> El siguiente ejemplo muestra cómo encontrar una fuente, marcarla como incrustada, buscar texto en la página del documento y reemplazar la fuente del texto. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Arial\"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document(\"D:\\\\Tests\\\\input.pdf\"); // create TextFragmentAbsorber object to find all \"hello world\" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber(\"hello world\"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

**Returns:**
valor booleano @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Obtiene un valor que indica si la fuente es un subconjunto. La fuente basada en IFont se subestablecerá e incrustará automáticamente. </p> <hr> <pre> El ejemplo muestra cómo buscar texto en la primera página y obtener el valor que indica si la fuente es un subconjunto. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println(\"the font is a subset\"); </pre>

**Returns:**
valor booleano @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Mide la cadena.

### save {#save-java.io.OutputStream-}
Guarda la fuente en el flujo. Tenga en cuenta que la fuente se guarda en formato TTF intermedio destinado a usarse solo en una copia convertida del documento original. El archivo de fuente no está destinado a usarse fuera del contexto del documento original.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Establece un valor que indica si la fuente está incrustada. Una fuente basada en IFont se subestablecerá y se incrustará automáticamente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Establece un valor que indica si la fuente es un subconjunto. Una fuente basada en IFont se subestablecerá y se incrustará automáticamente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
