---
title: "Clase Aspose::Pdf::Stamp"
linktitle: "Stamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Stamp. Una clase abstracta para varios tipos de sellos que aparecen como descendientes en C++."
type: docs
weight: 17400
url: /es/cpp/aspose.pdf/stamp/
---
## Stamp class


Una clase abstracta para varios tipos de sellos que aparecen como descendientes.

```cpp
class Stamp : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Background](./get_background/)() const | Establece o obtiene un valor booleano que indica que el contenido está sellado como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [get_BottomMargin](./get_bottommargin/)() const | Obtiene el margen inferior del sello. |
| virtual [get_Height](./get_height/)() | Altura deseada del sello en la página. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Obtiene la alineación horizontal del sello en la página. |
| [get_LeftMargin](./get_leftmargin/)() const | Obtiene el margen izquierdo del sello. |
| [get_Opacity](./get_opacity/)() const | Obtiene un valor que indica la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [get_OutlineOpacity](./get_outlineopacity/)() const | Obtiene un valor que indica la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto, el valor es 1.0. |
| [get_OutlineWidth](./get_outlinewidth/)() const | Obtiene un valor del ancho del contorno del sello. Por defecto, el valor es 1.0. |
| [get_RightMargin](./get_rightmargin/)() const | Obtiene el margen derecho del sello. |
| [get_Rotate](./get_rotate/)() | Establece o obtiene la rotación del contenido del sello según los valores de [Rotation](../rotation/). [Note](../note/). Esta propiedad es para ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, la propiedad Rotate devuelve [Rotation.None](../rotation/). |
| [get_RotateAngle](./get_rotateangle/)() | Obtiene el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [get_TopMargin](./get_topmargin/)() const | Obtiene el margen superior del sello. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Obtiene la alineación vertical del sello en la página. |
| virtual [get_Width](./get_width/)() | Ancho deseado del sello en la página. |
| virtual [get_XIndent](./get_xindent/)() | Coordenada horizontal del sello, comenzando desde la izquierda. |
| virtual [get_YIndent](./get_yindent/)() | Coordenada vertical del sello, comenzando desde la parte inferior. |
| [get_Zoom](./get_zoom/)() const | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. La configuración de esta propiedad cambia tanto las propiedades ZoomX como ZoomY. Si ZoomX y ZoomY son diferentes, la propiedad Zoom devuelve el valor de ZoomX. |
| [get_ZoomX](./get_zoomx/)() const | Factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [get_ZoomY](./get_zoomy/)() const | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |
| [getStampId](./getstampid/)() | Devuelve el ID del sello. |
| virtual [Put](./put/)(System::SharedPtr\<Page\>) | Añade el sello en la página. |
| [set_Background](./set_background/)(bool) | Establece o obtiene un valor booleano que indica que el contenido está sellado como fondo. Si el valor es verdadero, el contenido del sello se coloca en la parte inferior. Por defecto, el valor es falso, el contenido del sello se coloca en la parte superior. |
| [set_BottomMargin](./set_bottommargin/)(double) | Establece el margen inferior del sello. |
| virtual [set_Height](./set_height/)(double) | Altura deseada del sello en la página. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Establece la alineación horizontal del sello en la página. |
| [set_LeftMargin](./set_leftmargin/)(double) | Establece el margen izquierdo del sello. |
| [set_Opacity](./set_opacity/)(double) | Establece un valor para indicar la opacidad del sello. El valor está entre 0.0 y 1.0. Por defecto el valor es 1.0. |
| [set_OutlineOpacity](./set_outlineopacity/)(double) | Establece un valor para indicar la opacidad del contorno del sello. El valor está entre 0.0 y 1.0. Por defecto el valor es 1.0. |
| [set_OutlineWidth](./set_outlinewidth/)(double) | Establece un valor del ancho del contorno del sello. Por defecto el valor es 1.0. |
| [set_RightMargin](./set_rightmargin/)(double) | Establece el margen derecho del sello. |
| [set_Rotate](./set_rotate/)(Rotation) | Establece o obtiene la rotación del contenido del sello según los valores de [Rotation](../rotation/). [Note](../note/). Esta propiedad es para ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados). Para establecer un ángulo arbitrario use la propiedad RotateAngle. Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, la propiedad Rotate devuelve [Rotation.None](../rotation/). |
| [set_RotateAngle](./set_rotateangle/)(double) | Establece el ángulo de rotación del sello en grados. Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| [set_TopMargin](./set_topmargin/)(double) | Establece el margen superior del sello. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Establece la alineación vertical del sello en la página. |
| virtual [set_Width](./set_width/)(double) | Ancho deseado del sello en la página. |
| virtual [set_XIndent](./set_xindent/)(double) | Coordenada horizontal del sello, comenzando desde la izquierda. |
| virtual [set_YIndent](./set_yindent/)(double) | Coordenada vertical del sello, comenzando desde la parte inferior. |
| [set_Zoom](./set_zoom/)(double) | Factor de zoom del sello. Permite escalar el sello. Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. La configuración de esta propiedad cambia tanto las propiedades ZoomX como ZoomY. Si ZoomX y ZoomY son diferentes, la propiedad Zoom devuelve el valor de ZoomX. |
| [set_ZoomX](./set_zoomx/)(double) | Factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| [set_ZoomY](./set_zoomy/)(double) | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |
| [setStampId](./setstampid/)(int32_t) | Establece el sello [Id](../id/). |
| [Stamp](./stamp/)() |  |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
