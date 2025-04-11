---
title: Class TextFragmentState
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TextFragmentState. Representa un estado de texto de un fragmento de texto
type: docs
weight: 10970
url: /es/net/aspose.pdf.text/textfragmentstate/
---
## Clase TextFragmentState

Representa un estado de texto de un fragmento de texto.

```csharp
public sealed class TextFragmentState : TextState
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFragmentState](textfragmentstate/)(TextFragment) | Inicializa una nueva instancia del objeto `TextFragmentState` con el objeto [`TextFragment`](../textfragment/) especificado. Esta inicialización de `TextFragmentState` no es compatible. TextFragmentState solo está disponible con la propiedad [`TextState`](../textfragment/textstate/). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor/) { get; set; } | Establece el color de fondo del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing/) { get; set; } | Obtiene o establece el espaciado de caracteres del texto, representado por el objeto [`TextFragment`](../textfragment/). |
| override [CoordinateOrigin](../../aspose.pdf.text/textfragmentstate/coordinateorigin/) { get; set; } | Obtiene o establece el CoordinateOrigin del texto. Si CoordinateOrigin es Descender, la coordenada Y del texto corresponde al punto más bajo de la fuente. Si CoordinateOrigin es BaseLine, la coordenada Y del texto corresponde a la línea base de la fuente. El valor predeterminado es Descender. Si el valor de Descent de la fuente es demasiado grande, el texto puede renderizarse más alto que otras fuentes. En este caso, se puede seleccionar CoordinateOrigin BaseLine para una mejor representación del texto. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder/) { get; set; } | Obtiene o establece si se dibuja el borde del rectángulo de texto. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font/) { get; set; } | Obtiene o establece la fuente del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize/) { get; set; } | Obtiene o establece el tamaño de la fuente del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle/) { get; set; } | Establece el estilo de la fuente del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor/) { get; set; } | Obtiene o establece el color de primer plano del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions/) { get; set; } | Obtiene o establece las opciones de formato. La configuración de las opciones será efectiva solo en escenarios de generador. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal para el texto. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling/) { get; set; } | Obtiene o establece la escala horizontal del texto, representado por el objeto [`TextFragment`](../textfragment/). |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible/) { get; set; } | Obtiene o establece la invisibilidad del texto. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing/) { get; set; } | Obtiene o establece el espaciado de líneas del texto. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode/) { get; set; } | Obtiene o establece el modo de renderizado del texto. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation/) { get; set; } | Obtiene o establece el ángulo de rotación en grados. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout/) { get; set; } | Obtiene o establece el tachado para el texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor/) { get; set; } | Obtiene o establece el color de las operaciones de trazado de [`TextFragment`](../textfragment/) (texto de trazo, borde de rectángulo) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript/) { get; set; } | Obtiene o establece el subíndice del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript/) { get; set; } | Obtiene o establece el superíndice del texto, representado por el objeto [`TextFragment`](../textfragment/) |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops/) { get; } | Obtiene los tabuladores para el texto. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline/) { get; set; } | Obtiene o establece el subrayado para el texto, representado por el objeto [`TextFragment`](../textfragment/) |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing/) { get; set; } | Obtiene o establece el espaciado de palabras del texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom/)(TextState) | Aplica configuraciones de otro textState. |
| [IsFitRectangle](../../aspose.pdf.text/textfragmentstate/isfitrectangle/)(string, Rectangle) | Verifica si la cadena de entrada podría colocarse dentro del rectángulo definido. |
| [MeasureHeight](../../aspose.pdf.text/textfragmentstate/measureheight/#measureheight)(char) | Mide la altura del carácter. (2 métodos) |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring/)(string) | Mide la cadena. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Valor predeterminado de tabulación en los anchos del carácter de espacio de la fuente predeterminada. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag/) | Puede colocar esta etiqueta en el texto para declarar la tabulación. |

## Observaciones

Proporciona una forma de cambiar las siguientes propiedades del texto: fuente ([`Font`](./font/) propiedad) tamaño de fuente ([`FontSize`](./fontsize/) propiedad) estilo de fuente ([`FontStyle`](./fontstyle/) propiedad) color de primer plano ([`ForegroundColor`](./foregroundcolor/) propiedad) color de fondo ([`BackgroundColor`](./backgroundcolor/) propiedad) Tenga en cuenta que cambiar las propiedades de `TextFragmentState` puede cambiar la colección interna de [`Segments`](../textfragment/segments/) porque TextFragment es un objeto agregado y puede reorganizar segmentos internos o fusionarlos en un solo segmento. Si su requisito es dejar la colección de [`Segments`](../textfragment/segments/) sin cambios, cambie los segmentos internos individualmente.

## Ejemplos

El ejemplo demuestra cómo cambiar el color del texto y el tamaño de la fuente del texto con el objeto [`TextState`](../textstate/).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* clase [TextFragmentAbsorber](../textfragmentabsorber/)
* clase [Document](../../aspose.pdf/document/)
* clase [TextState](../textstate/)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../)