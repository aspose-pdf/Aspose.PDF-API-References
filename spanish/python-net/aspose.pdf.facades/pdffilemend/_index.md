---
title: "PdfFileMend"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para añadir textos e imágenes en las páginas de un documento PDF existente."
type: docs
weight: 280
url: /es/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Representa una clase para añadir textos e imágenes en las páginas de un documento PDF existente.

El tipo PdfFileMend expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileMend() | Constructor. |
| PdfFileMend(input_file_name, output_file_name) | Inicializa una nueva instancia de la clase PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Inicializa una nueva instancia de la clase PdfFileMend |
| PdfFileMend(document) | Inicializa una nueva instancia de la clase PdfFileMend |
| PdfFileMend(document, output_file_name) | Inicializa una nueva instancia de la clase PdfFileMend |
| PdfFileMend(document, dest_stream) | Inicializa una nueva instancia de la clase PdfFileMend |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| input_stream | Establece el flujo de entrada. |
| output_stream | Establece el flujo de salida. |
| input_file | Establece el archivo de entrada. |
| output_file | Establece el archivo de salida. |
| wrap_mode | Establece o obtiene el algoritmo de ajuste de palabras. Ver WordWrapMode y IsWordWrap. |
| text_positioning_mode | Establece o obtiene la estrategia de posicionamiento de texto. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            El modo predeterminado es Legacy. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(dest_file) | Guarda el documento PDF en el archivo especificado. |
| save(dest_stream) | Guarda el documento PDF en el flujo especificado. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| add_text(text, page_num, lower_left_x, lower_left_y) | No implementado. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | No implementado. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | No implementado. |
| close() | Cierra el objeto PdfFileMend. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

