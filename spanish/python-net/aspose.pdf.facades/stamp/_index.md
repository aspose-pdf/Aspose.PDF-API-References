---
title: "Stamp"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un sello."
type: docs
weight: 410
url: /es/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

Clase que representa un sello.

El tipo Stamp expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Stamp() | Inicializa una nueva instancia de la clase Stamp |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| stamp_id | Obtiene o establece el identificador del sello. |
| quality | Obtiene o establece la calidad del sello de imagen en porcentaje. Valores válidos 0..100%. |
| opacity | Obtiene o establece la opacidad del sello. |
| page_number | Obtiene o establece el número de página. |
| pages | Obtiene o establece una matriz con los números de páginas que serán afectadas por el sello. <br/>            Si Pages = null, todas las páginas del documento se ven afectadas. |
| rotation | Obtiene o establece la rotación del sello en grados. |
| is_background | Obtiene o establece el estado de fondo. Si es true, el sello se colocará como fondo de la página con sello.<br/>            Por defecto se establece en false. |
| blending_space | Obtiene o establece un valor BlendingColorSpace que define un espacio de color <br/>            que se utiliza para realizar operaciones de transparencia y mezcla en la página. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(pdf_file, page_number) | Establece el archivo PDF y el número de página que se utilizará como sello. |
| bind_pdf(pdf_stream, page_number) | Establece el archivo PDF y el número de página que se utilizará como sello. |
| bind_image(image_file) | Establece la imagen como sello. |
| bind_image(image) | Establece la imagen que se utilizará como sello. |
| bind_logo(formatted_text) | Establece el texto como sello. |
| bind_text_state(text_state) | Establece el estado de texto del sello. |
| set_origin(origin_x, origin_y) | Establece la posición en la página donde se colocará el sello. |
| set_image_size(width, height) | Establece el tamaño del sello de imagen. La imagen se escalará según los valores especificados. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

