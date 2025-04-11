---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.ImageStamp. Representa un sello gráfico
type: docs
weight: 5930
url: /es/net/aspose.pdf/imagestamp/
---
## Clase ImageStamp

Representa un sello gráfico.

```csharp
public sealed class ImageStamp : Stamp
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Inicializa una nueva instancia de la clase `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Crea un sello de imagen a partir de la imagen en el archivo especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Obtiene o establece el texto alternativo para el sello de imagen. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Establece o obtiene un valor booleano que indica si el contenido se estampa como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Obtiene o establece el margen inferior del sello. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Obtiene o establece la altura de la imagen. Establecer esta imagen permite escalar la imagen verticalmente. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Obtiene o establece la alineación horizontal del sello en la página. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Obtiene el flujo de imagen utilizado para el estampado. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Obtiene o establece el margen izquierdo del sello. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Obtiene o establece un valor para indicar la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Obtiene o establece un valor para indicar la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Obtiene o establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Obtiene o establece la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Obtiene o establece el margen derecho del sello. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Establece o obtiene la rotación del contenido del sello según los valores de [`Rotation`](../rotation/). Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario, utiliza la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, entonces la propiedad Rotate devuelve Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Obtiene o establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Obtiene o establece el margen superior del sello. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Obtiene o establece la alineación vertical del sello en la página. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Obtiene o establece el ancho de la imagen. Establecer esta propiedad permite escalar la imagen horizontalmente. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. Establecer esta propiedad cambia tanto las propiedades ZoomX como ZoomY. Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Devuelve el ID del sello. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Agrega un sello gráfico en la página. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Establece el ID del sello. |

### Ver También

* clase [Stamp](../stamp/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)