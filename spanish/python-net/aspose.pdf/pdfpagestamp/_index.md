---
title: "PdfPageStamp"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un sello que utiliza una página PDF como sello."
type: docs
weight: 1230
url: /es/python-net/aspose.pdf/pdfpagestamp/
---

## PdfPageStamp class

Clase que representa un sello que utiliza una página PDF como sello.

El tipo PdfPageStamp expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfPageStamp(pdf_page) | Inicializa una nueva instancia de la clase PdfPageStamp |
| PdfPageStamp(file_name, page_index) | Inicializa una nueva instancia de la clase PdfPageStamp |
| PdfPageStamp(stream, page_index) | Inicializa una nueva instancia de la clase PdfPageStamp |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| background | Establece o obtiene un valor booleano que indica que el contenido está estampado como fondo.<br/>            Si el valor es true, el contenido del sello se coloca en la parte inferior.<br/>            Por defecto, el valor es false, el contenido del sello se coloca en la parte superior. |
| opacity | Obtiene o establece un valor que indica la opacidad del sello. El valor está entre 0.0 y 1.0.<br/>            Por defecto el valor es 1.0. |
| outline_opacity | Obtiene o establece un valor que indica la opacidad del contorno del sello. El valor está entre 0.0 y 1.0.<br/>            Por defecto el valor es 1.0. |
| outline_width | Obtiene o establece un valor del ancho del contorno del sello.<br/>            Por defecto el valor es 1.0. |
| rotate | Establece o obtiene la rotación del contenido del sello según los valores de [Rotation](/pdf/python-net/aspose.pdf/rotation/).<br/>            Nota. Esta propiedad es para ángulos que son múltiplos de 90 grados (0, 90, 180, 270 grados).<br/>            Para establecer un ángulo arbitrario use la propiedad RotateAngle. <br/>            Si el ángulo establecido por ArbitraryAngle no es múltiplo de 90, entonces la propiedad Rotate devuelve Rotation.None. |
| x_indent | Coordenada horizontal del sello, comenzando desde la izquierda. |
| y_indent | Coordenada vertical del sello, comenzando desde la parte inferior. |
| horizontal_alignment | Obtiene o establece la alineación horizontal del sello en la página. |
| vertical_alignment | Obtiene o establece la alineación vertical del sello en la página. |
| left_margin | Obtiene o establece el margen izquierdo del sello. |
| right_margin | Obtiene o establece el margen derecho del sello. |
| bottom_margin | Obtiene o establece el margen inferior del sello. |
| top_margin | Obtiene o establece el margen superior del sello. |
| zoom_x | Factor de zoom horizontal del sello. Permite escalar el sello horizontalmente. |
| ancho | Ancho deseado del sello en la página. |
| alto | Altura deseada del sello en la página. |
| zoom_y | Factor de zoom vertical del sello. Permite escalar el sello verticalmente. |
| zoom | Factor de zoom del sello. Permite escalar el sello.<br/>            Tenga en cuenta que el par de propiedades ZoomX y ZoomY permite establecer el factor de zoom para cada eje por separado. <br/>            La configuración de esta propiedad cambia ambas propiedades ZoomX y ZoomY. <br/>            Si ZoomX y ZoomY son diferentes, entonces la propiedad Zoom devuelve el valor de ZoomX. |
| rotate_angle | Obtiene o establece el ángulo de rotación del sello en grados.<br/>            Esta propiedad permite establecer un ángulo de rotación arbitrario. |
| pdf_page | Obtiene o establece la página que se utilizará como sello. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| put(page) | Coloca el sello en la página especificada. |
| set_stamp_id(value) | Establece el Id del sello. |
| get_stamp_id() | Devuelve el ID del sello. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

