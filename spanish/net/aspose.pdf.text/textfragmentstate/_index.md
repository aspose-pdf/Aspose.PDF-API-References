---
title: TextFragmentState
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa un estado de texto de un fragmento de texto.
type: docs
weight: 7130
url: /es/net/aspose.pdf.text/textfragmentstate/
---
## TextFragmentState class

Representa un estado de texto de un fragmento de texto.

```csharp
public sealed class TextFragmentState : TextState
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextFragmentState](textfragmentstate)(TextFragment) | Inicializa una nueva instancia del[`TextFragmentState`](../textfragmentstate) objeto con especificado[`TextFragment`](../textfragment) objeto. Este[`TextFragmentState`](../textfragmentstate) la inicialización no es compatible. TextFragmentState solo está disponible con[`TextState`](../textfragment/textstate) propiedad. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [BackgroundColor](../../aspose.pdf.text/textfragmentstate/backgroundcolor) { get; set; } | Establece el color de fondo del texto, representado por el[`TextFragment`](../textfragment) objeto |
| override [CharacterSpacing](../../aspose.pdf.text/textfragmentstate/characterspacing) { get; set; } | Obtiene o establece el espaciado entre caracteres del texto, representado por el[`TextFragment`](../textfragment) objeto. |
| [DrawTextRectangleBorder](../../aspose.pdf.text/textfragmentstate/drawtextrectangleborder) { get; set; } | Obtiene o establece si el borde del rectángulo de texto marca dibujado. |
| override [Font](../../aspose.pdf.text/textfragmentstate/font) { get; set; } | Obtiene o establece la fuente del texto, representada por el[`TextFragment`](../textfragment) objeto |
| override [FontSize](../../aspose.pdf.text/textfragmentstate/fontsize) { get; set; } | Obtiene o establece el tamaño de fuente del texto, representado por el[`TextFragment`](../textfragment) objeto |
| override [FontStyle](../../aspose.pdf.text/textfragmentstate/fontstyle) { get; set; } | Establece el estilo de fuente del texto, representado por el[`TextFragment`](../textfragment) objeto |
| override [ForegroundColor](../../aspose.pdf.text/textfragmentstate/foregroundcolor) { get; set; } | Obtiene o establece el color de primer plano del texto, representado por el[`TextFragment`](../textfragment) objeto |
| [FormattingOptions](../../aspose.pdf.text/textfragmentstate/formattingoptions) { get; set; } | Obtiene o establece opciones de formato. La configuración de las opciones solo será efectiva en escenarios de generador. |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragmentstate/horizontalalignment) { get; set; } | Obtiene o establece la alineación horizontal del texto. |
| override [HorizontalScaling](../../aspose.pdf.text/textfragmentstate/horizontalscaling) { get; set; } | Obtiene o establece la escala horizontal del texto, representada por el[`TextFragment`](../textfragment) objeto. |
| override [Invisible](../../aspose.pdf.text/textfragmentstate/invisible) { get; set; } | Obtiene o establece la invisibilidad del texto. |
| override [LineSpacing](../../aspose.pdf.text/textfragmentstate/linespacing) { get; set; } | Obtiene o establece el interlineado del texto. |
| override [RenderingMode](../../aspose.pdf.text/textfragmentstate/renderingmode) { get; set; } | Obtiene o establece el modo de representación del texto. |
| [Rotation](../../aspose.pdf.text/textfragmentstate/rotation) { get; set; } | Obtiene o establece el ángulo de rotación en grados. |
| override [StrikeOut](../../aspose.pdf.text/textfragmentstate/strikeout) { set; } | Establece el tachado del texto, representado por el[`TextFragment`](../textfragment) objeto |
| override [StrokingColor](../../aspose.pdf.text/textfragmentstate/strokingcolor) { get; set; } | Obtiene o establece operaciones de trazo de color de[`TextFragment`](../textfragment) representación (texto de trazo, borde de rectángulo) |
| override [Subscript](../../aspose.pdf.text/textfragmentstate/subscript) { get; set; } | Obtiene o establece el subíndice del texto, representado por el[`TextFragment`](../textfragment) objeto. |
| override [Superscript](../../aspose.pdf.text/textfragmentstate/superscript) { get; set; } | Obtiene o establece el superíndice del texto, representado por el[`TextFragment`](../textfragment) objeto. |
| [TabStops](../../aspose.pdf.text/textfragmentstate/tabstops) { get; } | Obtiene tabulaciones para el texto. |
| override [Underline](../../aspose.pdf.text/textfragmentstate/underline) { get; set; } | Obtiene o establece el subrayado del texto, representado por el[`TextFragment`](../textfragment) objeto |
| override [WordSpacing](../../aspose.pdf.text/textfragmentstate/wordspacing) { get; set; } | Obtiene o establece el espaciado entre palabras del texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ApplyChangesFrom](../../aspose.pdf.text/textfragmentstate/applychangesfrom)(TextState) | Aplica la configuración de otro estado de texto. |
| override [MeasureString](../../aspose.pdf.text/textfragmentstate/measurestring)(string) | Mide la cuerda. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue) | Valor predeterminado de tabulación en anchos de carácter de espacio de fuente predeterminada. |
| readonly [TabTag](../../aspose.pdf.text/textstate/tabtag) | Puede colocar esta etiqueta en el texto para declarar la tabulación. |

### Observaciones

Proporciona una forma de cambiar las siguientes propiedades del texto: fuente ([`Font`](./font) propiedad) tamaño de fuente ([`FontSize`](./fontsize) propiedad) estilo de fuente ([`FontStyle`](./fontstyle) propiedad) color de primer plano ([`ForegroundColor`](./foregroundcolor) propiedad) color de fondo ([`BackgroundColor`](./backgroundcolor) propiedad) Tenga en cuenta que cambiar[`TextFragmentState`](../textfragmentstate) las propiedades pueden cambiar internas[`Segments`](../textfragment/segments) colección porque TextFragment es un objeto agregado y puede reorganizar segmentos internos o fusionarlos en un solo segmento. Si su requisito es dejar el[`Segments`](../textfragment/segments) colección sin cambios, cambie los segmentos internos individualmente.

### Ejemplos

El ejemplo muestra cómo cambiar el color del texto y el tamaño de fuente del texto con[`TextState`](../textstate) objeto.

```csharp
// Abrir documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crear objeto TextFragmentAbsorber para encontrar todas las apariciones de texto "hola mundo"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Aceptar el absorbedor para la primera página
doc.Pages[1].Accept(absorber);

// Cambiar el color de primer plano de la primera aparición de texto
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Cambiar el tamaño de fuente de la primera aparición de texto
absorber.TextFragments[1].TextState.FontSize = 15;

// Guardar documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver también

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* class [TextState](../textstate)
* espacio de nombres [Aspose.Pdf.Text](../../aspose.pdf.text)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
