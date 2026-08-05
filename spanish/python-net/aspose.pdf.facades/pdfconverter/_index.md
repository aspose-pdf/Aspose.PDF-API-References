---
title: "PdfConverter"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando ahora BMP, JPEG, PNG y TIFF.<br/> Contenido soportado en pdfs: imágenes, formularios, comentarios."
type: docs
weight: 200
url: /es/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando ahora BMP, JPEG, PNG y TIFF.<br/>            Contenido soportado en los pdfs: imágenes, formularios, comentarios.

El tipo PdfConverter expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfConverter() | Inicializa un nuevo objeto [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/). |
| PdfConverter(document) | Inicializa una nueva instancia de la clase PdfConverter |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| coordinate_type | Obtiene o establece el tipo de coordenadas de la página (cajas Media/Crop). El valor CropBox se usa por defecto. |
| show_hidden_areas | Obtiene o establece la bandera que controla la visibilidad de áreas ocultas en la página. |
| rendering_options | Obtiene o establece las opciones de renderizado. |
| form_presentation_mode | Obtiene o establece el modo de presentación del formulario. |
| resolution | Obtiene o establece la resolución durante la conversión. Cuanto mayor sea la resolución, más lenta será la velocidad de conversión. El valor predeterminado es 150. |
| start_page | Obtiene o establece la posición inicial que desea convertir. El valor mínimo es 1. |
| end_page | Obtiene o establece la posición final que desea convertir. |
| password | Obtiene o establece la OwnerPassword del documento. |
| user_password | Obtiene o establece la UserPassword del documento. |
| page_count | Obtiene el recuento de páginas. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(input_file) | Asocia un archivo Pdf para convertir. |
| bind_pdf(input_stream) | Asocia un flujo Pdf para convertir. |
| bind_pdf(src_doc) | Inicializa la fachada. |
| save_as_tiff(output_file) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, compression_type) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, image_width, image_height) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, page_size) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, page_size, settings) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_stream) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo ClassF TIFF. |
| save_as_tiff(output_stream, compression_type) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_stream, page_size) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo ClassF TIFF. |
| save_as_tiff(output_stream, page_size, settings) | Convierte cada página de un documento pdf en imágenes con el tamaño de página y guarda las imágenes en un único flujo TIFF. |
| save_as_tiff(output_stream, image_width, image_height) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo ClassF TIFF. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| save_as_tiff(output_file, settings) | Convierte cada página de un documento pdf a imágenes con tamaño de página y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_file, settings, converter) | Convierte cada página de un documento pdf a imágenes con dimensiones y guarda las imágenes en un único archivo TIFF. |
| save_as_tiff(output_stream, settings) | Convierte cada página de un documento pdf en imágenes con el tamaño de página y guarda las imágenes en un único flujo TIFF. |
| save_as_tiff(output_stream, settings, converter) | Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un único flujo TIFF. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| save_as_tiff_class_f(output_file, page_size) | Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo ClassF TIFF. |
| save_as_tiff_class_f(output_stream, page_size) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo ClassF TIFF. |
| save_as_tiff_class_f(output_file) | Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un único archivo TIFF ClassF. |
| save_as_tiff_class_f(output_stream) | Convierte cada página de un documento pdf a imágenes y guarda las imágenes en un único flujo ClassF TIFF. |
| get_next_image(output_file) | Guarda la imagen en un archivo con el formato de imagen predeterminado: jpeg. |
| get_next_image(output_file, page_size) | Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado: jpeg. |
| get_next_image(output_file, format) | Guarda la imagen en un archivo con el formato de imagen proporcionado. |
| get_next_image(output_file, page_size, format) | Guarda la imagen en un archivo con el tamaño de página y el formato de imagen especificados. |
| get_next_image(output_stream) | Guarda la imagen en el flujo con el formato de imagen predeterminado - jpeg. |
| get_next_image(output_stream, page_size) | Guarda la imagen en el flujo con el tamaño de página especificado. |
| get_next_image(output_stream, format) | Guarda la imagen en el flujo con el formato de imagen especificado. |
| get_next_image(output_stream, page_size, format) | Guarda la imagen en el flujo con el tamaño de página especificado. |
| get_next_image(output_file, format, image_width, image_height, quality) | Guarda la imagen en el archivo con el formato de imagen, dimensiones y calidad especificados. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Guarda la imagen en el flujo con el formato de imagen, dimensiones y calidad especificados. |
| get_next_image(output_file, format, image_width, image_height, quality) | Guarda la imagen en el archivo con el formato de imagen, tamaño de imagen y calidad especificados. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Guarda la imagen en el flujo con el formato de imagen, tamaño y calidad especificados. |
| get_next_image(output_file, format, image_width, image_height) | Guarda la imagen en el archivo con el formato de imagen, dimensiones y calidad especificados. |
| get_next_image(output_stream, format, image_width, image_height) | Guarda la imagen en el flujo con el formato de imagen, dimensiones y calidad especificados. |
| get_next_image(output_stream, format, quality) | Guarda la imagen en el flujo con el formato de imagen, dimensiones y calidad especificados. |
| get_next_image(output_stream, page_size, format, quality) | Guarda la imagen en el flujo con el tamaño de página, formato de imagen y calidad especificados. |
| get_next_image(output_file, format, quality) | Guarda la imagen en el archivo con el formato de imagen, dimensiones y calidad especificados. |
| get_next_image(output_file, page_size, format, quality) | Guarda la imagen en el archivo con el tamaño de página, formato de imagen y calidad especificados. |
| close() | Cierra la instancia de PdfConverter y libera los recursos. |
| do_convert() | Realiza algunos trabajos iniciales para convertir un documento pdf a imágenes. |
| has_next_image() | Indica si el archivo pdf tiene más imágenes o no. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Ninguno |
| merge_images_as_tiff(input_images_streams) | Fusiona una lista de flujos tiff como un único flujo tiff de varios fotogramas. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

