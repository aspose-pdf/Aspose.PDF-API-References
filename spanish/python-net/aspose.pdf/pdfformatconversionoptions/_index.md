---
title: "PdfFormatConversionOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "representa un conjunto de opciones para convertir documentos PDF"
type: docs
weight: 1220
url: /es/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

representa un conjunto de opciones para convertir documentos PDF

El tipo PdfFormatConversionOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Inicializa una nueva instancia de la clase PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Inicializa una nueva instancia de la clase PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Inicializa una nueva instancia de la clase PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Inicializa una nueva instancia de la clase PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Inicializa una nueva instancia de la clase PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Inicializa una nueva instancia de la clase PdfFormatConversionOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_async_image_streams_conversion_mode | Obtiene/establece la ejecución de flujos de imágenes en modo asíncrono. |
| is_low_memory_mode | Indica si el modo de conversión de bajo consumo de memoria está habilitado |
| formato | Formato PDF. |
| log_file_name | Ruta al archivo donde se almacenarán los comentarios. |
| log_stream | Flujo donde se almacenarán los comentarios. |
| error_action | Acción para objetos que no pueden ser convertidos |
| transparency_action | Acción para objetos de imagen enmascarados |
| convert_soft_mask_action | Acción para imágenes con máscara suave. |
| predeterminado | Obtiene el objeto PdfFormatConversionOptions con parámetros predeterminados |
| non_specification_cases | Mantiene banderas para controlar el proceso de conversión PDF/A en casos en que el documento fuente<br/>            no corresponde a la especificación PDF/A. |
| symbolic_font_encoding_strategy | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica<br/>            tiene más de una subtabla de codificación. |
| align_text | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión del documento <br/>            no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes<br/>            provoca superposición de texto o espacios extra en el documento convertido. Cuando esta bandera está establecida<br/>            se realizarán operaciones especiales de alineación. Esta bandera debe establecerse solo para documentos<br/>            que tengan problemas con texto superpuesto o espacios de texto extra, ya que el uso de esta bandera disminuye<br/>            el rendimiento y, en algunos casos, podría corromper el contenido del texto. |
| pua_text_processing_strategy | Estrategia para procesar símbolos del Área de Uso Privado (PUA) Unicode. |
| optimize_file_size | Obtiene o establece una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido.<br/>            Ahora esta bandera afecta la optimización de fuentes usadas en el documento PDF, posiblemente, en el futuro, esta bandera <br/>            también se usará para activar la optimización de otras estructuras de datos, como gráficos.  <br/>            El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría<br/>            disminuir significativamente el rendimiento de la conversión. |
| exclude_fonts_strategy | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. <br/>            Este parámetro tiene sentido solo cuando la bandera [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) está establecida en true.<br/>            Por defecto se usa la combinación de estrategias [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) y<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/). |
| font_embedding_options | Opciones para los casos en que no es posible incrustar algunas fuentes en el documento PDF. |
| unicode_processing_rules | Reglas para resolver problemas con el mapeo Unicode. Puede ser nulo. |
| icc_profile_file_name | Obtiene o establece el nombre de archivo del perfil ICC. En caso de ser nulo, se utiliza el perfil ICC predeterminado. |
| not_accessible_fonts | Esta propiedad es de salida. Contiene todas las fuentes (nombres de fuentes) que no se encontraron en el equipo <br/>            en la última conversión PDF/A. |
| is_transfer_info | Obtiene o establece si se deben pasar datos de Info a Metadata al convertir a PDF 2.0. Verdadero por defecto. |
| align_strategy | Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) está establecida en true. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

