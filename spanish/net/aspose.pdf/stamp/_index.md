---
title: Stamp
second_title: Referencia de API de Aspose.PDF para .NET
description: Una clase abstracta para varios tipos de sellos que vienen como descendientes.
type: docs
weight: 6370
url: /es/net/aspose.pdf/stamp/
---
## Stamp class

Una clase abstracta para varios tipos de sellos que vienen como descendientes.

```csharp
public abstract class Stamp
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Establece u obtiene un valor bool que indica que el contenido está estampado como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. De forma predeterminada, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Obtiene o establece el margen inferior del sello. |
| virtual [Height](../../aspose.pdf/stamp/height) { get; set; } | Altura deseada del sello en la página. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Obtiene o establece la alineación horizontal del sello en la página. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Obtiene o establece el margen izquierdo del sello. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Obtiene o establece un valor para indicar la opacidad del sello. El valor es de 0.0 a 1.0. Por defecto el valor es 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Obtiene o establece un valor para indicar la opacidad del contorno del sello. El valor es de 0.0 a 1.0. Por defecto el valor es 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Obtiene o establece un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Obtiene o establece el margen derecho del sello. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Establece u obtiene la rotación del contenido del sello según[`Rotation`](../rotation) valores. Nota. Esta propiedad es para establecer ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario, use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, la propiedad Rotar devuelve Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Obtiene o establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Obtiene o establece el margen superior del sello. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Obtiene o establece la alineación vertical del sello en la página. |
| virtual [Width](../../aspose.pdf/stamp/width) { get; set; } | Ancho deseado del sello en la página. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Coordenada horizontal del sello, empezando por la izquierda. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Coordenada de sello vertical, comenzando desde abajo. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. La configuración de esta propiedad cambia las propiedades de ZoomX y ZoomY. Si ZoomX y ZoomY son diferentes, la propiedad Zoom devuelve el valor de ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Factor de zoom horizontal del sello. Permite escalar el sello en horizontal. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Devuelve el sello ID. |
| abstract [Put](../../aspose.pdf/stamp/put)(Page) | Añade sello en la página. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Establece el sello Id. |

### Ver también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->