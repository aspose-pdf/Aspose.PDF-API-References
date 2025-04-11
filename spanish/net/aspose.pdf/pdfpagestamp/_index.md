---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PdfPageStamp. Clase que representa un sello que utiliza una página PDF como sello
type: docs
weight: 8420
url: /es/net/aspose.pdf/pdfpagestamp/
---
## Clase PdfPageStamp

Clase que representa un sello que utiliza una página PDF como sello.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Constructor de PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Crea un sello de página PDF de la página especificada en el documento desde el flujo. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Crea un sello de página PDF de la página especificada del documento en el archivo especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Establece o obtiene un valor booleano que indica si el contenido se estampa como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtiene o establece el margen inferior del sello. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Altura deseada del sello en la página. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal del sello en la página. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtiene o establece el margen izquierdo del sello. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtiene o establece un valor para indicar la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtiene o establece un valor para indicar la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtiene o establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Obtiene o establece la página que se utilizará como sello. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtiene o establece el margen derecho del sello. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Establece o obtiene la rotación del contenido del sello de acuerdo con los valores de [`Rotation`](../rotation/). Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario, utiliza la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, entonces la propiedad Rotate devuelve Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtiene o establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtiene o establece el margen superior del sello. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtiene o establece la alineación vertical del sello en la página. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Ancho deseado del sello en la página. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Coordenada horizontal del sello, comenzando desde la izquierda. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Coordenada vertical del sello, comenzando desde la parte inferior. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. El establecimiento de esta propiedad cambia tanto las propiedades ZoomX como ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Devuelve el ID del sello. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Coloca el sello en la página especificada. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Establece el ID del sello. |

### Ver También

* clase [Stamp](../stamp/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)