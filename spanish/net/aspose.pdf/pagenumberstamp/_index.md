---
title: Class PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PageNumberStamp. Representa un sello de número de página y se utiliza para numerar páginas
type: docs
weight: 8230
url: /es/net/aspose.pdf/pagenumberstamp/
---
## Clase PageNumberStamp

Representa un sello de número de página y se utiliza para numerar páginas.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PageNumberStamp](pagenumberstamp/#constructor)() | Inicializa una nueva instancia de la clase `PageNumberStamp`. El formato se establece en "#". |
| [PageNumberStamp](pagenumberstamp/#constructor_1)(FormattedText) | Crea PageNumberStamp mediante texto formateado. |
| [PageNumberStamp](pagenumberstamp/#constructor_2)(string) | Inicializa una nueva instancia de la clase `PageNumberStamp`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Ajusta automáticamente la precisión del tamaño de la fuente. Valor predeterminado: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | Si está habilitado, el tamaño de la fuente se ajustará automáticamente para encajar en el rectángulo del sello de tamaño: [`Width`](../textstamp/width/) y [`Height`](../textstamp/height/). El ancho y la altura predeterminados se derivan del rectángulo de la página. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Establece o obtiene un valor booleano que indica que el contenido se estampa como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtiene o establece el margen inferior del sello. |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | Esta propiedad determina cómo se dibuja el sello en la página. Si Draw = true, el sello se dibuja como operadores gráficos y si draw = false, entonces el sello se dibuja como texto. |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Tamaño de fuente real después de que se ha colocado el sello. (Puede diferir del tamaño de fuente inicial proporcionado a través del constructor si la opción 'AutoAdjustFontSizeToFitStampRectangle' está habilitada.) |
| [Format](../../aspose.pdf/pagenumberstamp/format/) { get; set; } | Valor de cadena para estampar números de página. El valor debe incluir el carácter '#' que se reemplaza con el número de página en el proceso de estampado. |
| override [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Altura deseada del sello en la página. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal del sello en la página. |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Define la justificación del texto. Si esta propiedad se establece en verdadero, ambos bordes izquierdo y derecho del texto están alineados. Valor predeterminado: falso. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtiene o establece el margen izquierdo del sello. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Altura máxima de fila para la opción WordWrap. |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Obtiene o establece el modo que define el comportamiento en caso de que las fuentes no contengan los caracteres solicitados. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle/) { get; set; } | Estilo de numeración que utiliza este sello. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtiene o establece un valor para indicar la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtiene o establece un valor para indicar la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtiene o establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Obtiene o establece la fuente utilizada para reemplazar si la fuente del usuario no contiene el carácter requerido. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtiene o establece el margen derecho del sello. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Establece o obtiene la rotación del contenido del sello según los valores de [`Rotation`](../rotation/). Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario, use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, entonces la propiedad Rotate devuelve Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtiene o establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Define la escala del texto. Si esta propiedad se establece en verdadero y se especifica un valor de Width, el texto se escalará para ajustarse al ancho especificado. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber/) { get; set; } | Obtiene o establece el valor del número de la página inicial. Otras páginas se numerarán a partir de este valor. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Alineación del texto dentro del sello. |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Obtiene las propiedades del texto del sello. Consulte [`TextState`](../textstamp/textstate/) para más detalles. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtiene o establece el margen superior del sello. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Define el origen de coordenadas para colocar el texto. Si TreatYIndentAsBaseLine = true (predeterminado cuando Draw = true), el valor de YIndent se tratará como la línea base del texto. Si TreatYIndentAsBaseLine = false (predeterminado cuando Draw = false), el valor de YIndent se tratará como la parte inferior (línea de descenso) del texto. |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Obtiene o establece el valor de cadena que se utiliza como sello en la página. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtiene o establece la alineación vertical del sello en la página. |
| override [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Ancho deseado del sello en la página. |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Obtiene o establece el modo de ajuste de palabras para el renderizado de texto. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordenada horizontal del sello, comenzando desde la izquierda. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordenada vertical del sello, comenzando desde la parte inferior. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. El establecimiento de esta propiedad cambia tanto las propiedades ZoomX como ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Devuelve el ID del sello. |
| override [Put](../../aspose.pdf/pagenumberstamp/put/)(Page) | Agrega el número de página. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Establece el ID del sello. |

### Ver También

* clase [TextStamp](../textstamp/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)