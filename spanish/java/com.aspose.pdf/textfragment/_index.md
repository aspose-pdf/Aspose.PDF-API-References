---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un fragmento de texto PDF. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente. // Open document."
type: docs
weight: 5110
url: /es/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Representa un fragmento de texto PDF. </p> <hr> <pre> El ejemplo muestra cómo encontrar texto en la primera página del documento PDF y reemplazar el texto y su fuente. // Open document Document doc = new Document(\"input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"output.pdf\"); </pre> <hr> <pre> En pocas palabras, el objeto {@code TextFragment} contiene una lista de objetos {@code TextSegment}. En detalle: el texto del documento PDF en {@code com.aspose.pdf} está representado por dos objetos básicos: {@code TextFragment} y {@code TextSegment}. Las diferencias entre ellos son mayormente dependientes del contexto. Consideremos el siguiente escenario. El usuario busca el texto \"hello world\" para operar con él, cambiar sus propiedades, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); doc.getPages().get(1).accept(absorber); </pre> La representación física del texto PDF es muy compleja. El texto \"hello world\" puede consistir en varios segmentos de texto físicamente independientes. El modelo de texto de Aspose.Pdf establece básicamente que el objeto {@code TextFragment} proporciona un conjunto de operaciones lógicas único sobre el conjunto de objetos {@code TextSegment} físicos que representan la consulta del usuario. En el escenario de búsqueda de texto, {@code TextFragment} es la representación lógica del texto \"hello world\", y la colección de objetos {@code TextSegment} representa todos los segmentos físicos que construyen el objeto de texto \"hello world\". Así, {@code TextFragment} se acerca a la representación lógica del texto. Y {@code TextSegment} se acerca a la representación física del texto. Obviamente, cada objeto {@code TextSegment} puede tener su propia fuente, coloración y propiedades de posicionamiento. {@code TextFragment} proporciona una forma sencilla de cambiar el texto con sus propiedades: establecer la fuente, el tamaño de fuente, el color de fuente, etc. Mientras tanto, los objetos {@code TextSegment} son accesibles y los usuarios pueden operar con los objetos {@code TextSegment} de forma independiente. <p> Tenga en cuenta que cambiar las propiedades de TextFragment puede modificar la colección interna {@code Segments} porque TextFragment es un objeto agregado y puede reorganizar los segmentos internos o fusionarlos en un solo segmento. Si su requisito es dejar la colección {@code Segments} sin cambios, por favor modifique los segmentos internos individualmente. </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextFragment](#TextFragment--) | Inicializa una nueva instancia del objeto {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-) | Inicializa una nueva instancia del objeto {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Inicializa una nueva instancia del objeto {@code TextFragment}. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Inicializa una nueva instancia del objeto {@code TextFragment}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clona el fragmento con todos los segmentos. |
| [deepClone](#deepClone--) | Clona el fragmento. |
| [getBaselinePosition](#getBaselinePosition--) | Obtiene la posición del texto para el texto, representado con el objeto {@code TextFragment}. El YIndent de la estructura Position representa la coordenada de la línea base del fragmento de texto. |
| [getEndNote](#getEndNote--) | Obtiene la nota final del párrafo.(solo para generación de PDF) |
| [getFootNote](#getFootNote--) | Obtiene la nota al pie del párrafo.(solo para generación de PDF) |
| [getForm](#getForm--) | Obtiene el objeto de formulario que contiene el TextFragment. El valor puede ser nulo en caso de que el objeto TextFragment no pertenezca a un formulario. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene una alineación horizontal del fragmento de texto. |
| [getPage](#getPage--) | Obtiene la página que contiene el TextFragment. El valor puede ser nulo en caso de que el objeto TextFragment no pertenezca a ninguna página. |
| [getPosition](#getPosition--) | <p> Obtiene la posición del texto para el texto, representado con el objeto {@code TextFragment}. </p> |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo del TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| [getSegments](#getSegments--) | <p> Obtiene los segmentos de texto para el {@code TextFragment} actual. </p> |
| [getText](#getText--) | <p> Obtiene el objeto de texto {@code string} que representa el objeto {@code TextFragment}. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [getTextState](#getTextState--) | <p> Obtiene o establece el estado del texto para el texto que representa el objeto {@code TextFragment}. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene una alineación vertical del fragmento de texto. |
| [getWrapLinesCount](#getWrapLinesCount--) | Obtiene el recuento de líneas de ajuste para este párrafo(solo para generación de PDF) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Obtiene {@code TextSegment}(s) que representan la parte especificada del texto {@code TextFragment}. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Establece la posición del texto para el texto, representado con el objeto {@code TextFragment}. El YIndent de la estructura Position representa la coordenada de la línea base del fragmento de texto. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Establece la nota final del párrafo.(solo para generación de PDF) |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Establece la nota al pie del párrafo.(solo para generación de PDF) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece una alineación horizontal del fragmento de texto. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Establece el hipervínculo del fragmento |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Establece la posición del texto para el texto, representado con el objeto {@code TextFragment}. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Obtiene el rectángulo del TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Representar el método setSegments |
| [setText](#setText-java.lang.String-) | <p> Establece el objeto de texto {@code string} que representa el objeto {@code TextFragment}. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece una alineación vertical del fragmento de texto. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Establece el número de líneas de ajuste para este párrafo (solo para generación de PDF) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Inicializa una nueva instancia del objeto {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-}
Inicializa una nueva instancia del objeto {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Inicializa una nueva instancia del objeto {@code TextFragment}.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Inicializa una nueva instancia del objeto {@code TextFragment}.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clona el fragmento con todos los segmentos.

**Returns:**
El objeto clonado

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona el fragmento.

**Returns:**
El objeto clonado

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Obtiene la posición del texto para el texto, representado con el objeto {@code TextFragment}. El YIndent de la estructura Position representa la coordenada de la línea base del fragmento de texto.

**Returns:**
Valor de posición

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Obtiene la nota final del párrafo.(solo para generación de PDF)

**Returns:**
Valor de nota

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Obtiene la nota al pie del párrafo.(solo para generación de PDF)

**Returns:**
Valor de nota

### getForm {#getForm--}
```
public XForm getForm()
```

Obtiene el objeto de formulario que contiene el TextFragment. El valor puede ser nulo en caso de que el objeto TextFragment no pertenezca a un formulario.

**Returns:**
Valor XForm

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtiene una alineación horizontal del fragmento de texto.

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Obtiene la página que contiene el TextFragment. El valor puede ser nulo en caso de que el objeto TextFragment no pertenezca a ninguna página.

**Returns:**
objeto Page

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Obtiene la posición del texto para el texto, representado con el objeto {@code TextFragment}. </p>

**Returns:**
Valor de posición <hr> <pre> El ejemplo muestra cómo visualizar la ubicación de un texto, representado por el objeto {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo del TextFragment

**Returns:**
objeto Rectangle

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo.

**Returns:**
Instancia de TextReplaceOptions

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Obtiene los segmentos de texto para el {@code TextFragment} actual. </p>

**Returns:**
Valor de TextSegmentCollection <hr> <pre> El ejemplo muestra cómo navegar todos los objetos {@code TextSegment} dentro del {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> En pocas palabras, los objetos {@code TextSegment} son hijos del objeto {@code TextFragment}. Los usuarios avanzados pueden acceder a los segmentos directamente para realizar escenarios de edición de texto más complejos. Para más detalles, consulte la descripción del objeto {@code TextFragment}. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Obtiene el objeto de texto {@code string} que representa el objeto {@code TextFragment}. </p>

**Returns:**
Valor de cadena <hr> <pre> El ejemplo muestra cómo buscar un texto y reemplazar la primera aparición representada con el objeto {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente.

**Returns:**
Instancia de TextEditOptions

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Obtiene o establece el estado del texto para el texto que representa el objeto {@code TextFragment}. </p>

**Returns:**
Objeto TextFragmentState <hr> <pre> El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con el objeto {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Proporciona una forma de cambiar las siguientes propiedades del texto: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtiene una alineación vertical del fragmento de texto.

**Returns:**
valor int @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Obtiene el recuento de líneas de ajuste para este párrafo(solo para generación de PDF)

**Returns:**
valor int

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Obtiene {@code TextSegment}(s) que representan la parte especificada del texto {@code TextFragment}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex |  | Posición en el texto desde la cual comenzarán los nuevos {@code TextSegment}(s). |
| longitud |  | Longitud del texto que se aislará en {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} que contiene segmentos de texto que representan una subcadena de texto que comienza en una posición especificada y tiene una longitud determinada.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Establece la posición del texto para el texto, representado con el objeto {@code TextFragment}. El YIndent de la estructura Position representa la coordenada de la línea base del fragmento de texto.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Establece la nota final del párrafo.(solo para generación de PDF)

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Establece la nota al pie del párrafo.(solo para generación de PDF)

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece una alineación horizontal del fragmento de texto.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Establece el hipervínculo del fragmento

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Establece la posición del texto para el texto, representado con el objeto {@code TextFragment}. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Obtiene el rectángulo del TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Representar el método setSegments

### setText {#setText-java.lang.String-}
<p> Establece el objeto de texto {@code string} que representa el objeto {@code TextFragment}. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede ser escrito con la fuente.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece una alineación vertical del fragmento de texto.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Establece el número de líneas de ajuste para este párrafo (solo para generación de PDF)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
