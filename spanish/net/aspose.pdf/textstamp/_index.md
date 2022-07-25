---
title: TextStamp
second_title: Referencia de API de Aspose.PDF para .NET
description: Vuelve a presentar el sello de texto.
type: docs
weight: 7240
url: /es/net/aspose.pdf/textstamp/
---
## TextStamp class

Vuelve a presentar el sello de texto.

```csharp
public class TextStamp : Stamp
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextStamp](textstamp#constructor)(FormattedText) | Inicializa una nueva instancia del[`TextStamp`](../textstamp) clase con formattedText object |
| [TextStamp](textstamp#constructor_1)(string) | Inicializa una nueva instancia del[`TextStamp`](../textstamp) clase. |
| [TextStamp](textstamp#constructor_2)(string, TextState) | Inicializa una nueva instancia del[`TextStamp`](../textstamp) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Establece u obtiene un valor bool que indica que el contenido está estampado como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. De forma predeterminada, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Obtiene o establece el margen inferior del sello. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | Esta propiedad determina cómo se dibuja el sello en la página. Si Dibujar = verdadero, el sello se dibuja como operadores gráficos y si dibujar = falso, el sello se dibuja como texto. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Altura deseada del sello en la página. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Obtiene o establece la alineación horizontal del sello en la página. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Define la justificación del texto. Si esta propiedad se establece en true, se alinean los bordes izquierdo y derecho del texto. Valor por defecto: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Obtiene o establece el margen izquierdo del sello. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Altura máxima de fila para la opción WordWrap. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Obtiene o establece un valor para indicar la opacidad del sello. El valor es de 0.0 a 1.0. Por defecto el valor es 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Obtiene o establece un valor para indicar la opacidad del contorno del sello. El valor es de 0.0 a 1.0. Por defecto el valor es 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Obtiene o establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Obtiene o establece el margen derecho del sello. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Establece u obtiene la rotación del contenido del sello según[`Rotation`](../rotation) valores. Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario, use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, la propiedad Rotar devuelve Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Obtiene o establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Define la escala del texto. Si esta propiedad se establece en verdadero y se especifica el valor de ancho, el texto se escalará para ajustarse al ancho especificado. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Alineación del texto dentro del sello. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Obtiene las propiedades de texto del sello. Ver[`TextState`](./textstate) para detalles. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Obtiene o establece el margen superior del sello. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Define el origen de las coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (predeterminado cuando Draw = true), el valor de YIndent se tratará como línea base de texto. Si TreatYIndentAsBaseLine = false (predeterminado cuando Draw = false), el valor de YIndent se tratará como inferior ( línea de descenso) de texto. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Obtiene o establece el valor de cadena que se utiliza como sello en la página. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Obtiene o establece la alineación vertical del sello en la página. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Ancho deseado del sello en la página. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Define el ajuste de línea. Si esta propiedad se establece en verdadero y se especifica el valor Ancho, el texto se dividirá en varias líneas para ajustarse al ancho especificado. Valor por defecto: false. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Coordenada horizontal del sello, empezando por la izquierda. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Coordenada de sello vertical, comenzando desde abajo. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. La configuración de esta propiedad cambia las propiedades de ZoomX y ZoomY. Si ZoomX y ZoomY son diferentes, la propiedad Zoom devuelve el valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Factor de zoom horizontal del sello. Permite escalar el sello en horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Devuelve el sello ID. |
| override [Put](../../aspose.pdf/textstamp/put)(Page) | Agrega un sello de texto en la página. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Establece el sello Id. |

### Ver también

* class [Stamp](../stamp)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
