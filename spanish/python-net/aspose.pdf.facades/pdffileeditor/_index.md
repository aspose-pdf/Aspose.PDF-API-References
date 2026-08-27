---
title: "PdfFileEditor"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Implementa operaciones con concatenación de archivos PDF, división, extracción de páginas, creación de folleto, etc."
type: docs
weight: 220
url: /es/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc.

El tipo PdfFileEditor expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileEditor() | Inicializa una nueva instancia de la clase PdfFileEditor |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| conversion_log | Obtiene el registro del proceso de conversión. |
| merge_duplicate_layers | El contenido opcional de los documentos concatenados con nombres iguales se fusionará en una sola capa en el documento resultante si esta propiedad es verdadera. <br/>            De lo contrario, las capas con nombres iguales se guardarán como capas diferentes en el documento resultante. |
| copy_outlines | Si es verdadero, los contornos se copiarán. |
| copy_logical_structure | Si es verdadero, la estructura lógica del archivo se copiará cuando se realice la concatenación. |
| merge_duplicate_outlines | Si es verdadero, los contornos duplicados se fusionan. |
| preserve_user_rights | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. Los derechos de usuario de los demás documentos se ignoran. |
| incremental_updates | Si es verdadero, se realizan actualizaciones incrementales durante la concatenación. |
| optimize_size | Obtiene o establece la bandera de optimización. Los flujos de recursos iguales en el archivo resultante se combinan en un único objeto PDF si esta bandera está activada. <br/>            Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria.<br/>            Valor predeterminado: false. |
| corrupted_items | Matriz de problemas encontrados cuando se realizó la concatenación. Por cada documento corrupto pasado a Concatenate() <br/>            se crea una nueva entrada CorruptedItem.<br/>            Esta propiedad solo puede usarse cuando CorruptedFileAction es ConcatenateIgnoringCorrupted. |
| corrupted_file_action | Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo corrupto.<br/>            Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted. |
| owner_password | Establece la contraseña del propietario si el archivo Pdf de entrada fuente está cifrado.<br/>            Esta propiedad aún no está implementada. |
| allow_concatenate_exceptions | Si se establece en true, se lanzan excepciones si ocurre un error. De lo contrario, no se lanzan excepciones y los métodos devuelven false si fallan. |
| close_concatenated_streams | Si se establece en true, los flujos se cierran después de la operación. |
| unique_suffix | Formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan.<br/>            Esta cadena debe contener la subcadena %NUM% que será reemplazada por números.<br/>            Por ejemplo, si UniqueSuffix = "ABC%NUM%" entonces para el campo "fieldName" los nombres serán:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| keep_actions | Si es true, las acciones se copiarán de los documentos fuente. Valor predeterminado: true. |
| keep_fields_unique | Si es true, los nombres de los campos se harán únicos cuando los formularios se concatenen.<br/>            Se agregarán sufijos a los nombres de los campos; la plantilla de sufijo puede especificarse en la propiedad UniqueSuffix. |
| remove_signatures | Si es true, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, podrías obtener firmas inválidas. |
| use_disk_buffer | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. |
| concatenation_packet_size | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | Concatena dos archivos. |
| try_concatenate(src, dest) | Concatena documentos. |
| try_concatenate(input_files, output_file) | Concatena archivos en un solo archivo. |
| try_concatenate(input_stream, output_stream) | Concatena archivos |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatena dos archivos. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatena archivos |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | Añade páginas, que se eligen de una matriz de documentos en portStreams.<br/>            El documento resultante incluye firstInputFile y todas las páginas de los documentos portStreams en el rango startPage a endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | Añade páginas, que se eligen de los documentos portFiles. <br/>            El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango startPage a endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| try_delete(input_file, page_number, output_file) | Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf. |
| try_delete(input_stream, page_number, output_stream) | Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf. |
| try_extract(input_file, start_page, end_page, output_file) | Extrae páginas del archivo de entrada,guarda como un nuevo archivo Pdf. |
| try_extract(input_file, page_number, output_file) | Extrae páginas especificadas por una matriz de números, guarda como un nuevo archivo PDF. |
| try_extract(input_stream, page_number, output_stream) | Extrae páginas especificadas por una matriz de números, guarda como un nuevo archivo Pdf. |
| try_split_from_first(input_file, location, output_file) | Divide el archivo Pdf desde la primera página hasta la ubicación especificada, y guarda la parte frontal como un nuevo archivo. |
| try_split_from_first(input_stream, location, output_stream) | Divide desde el inicio hasta la ubicación especificada, y guarda la parte frontal en el Stream de salida. |
| try_split_to_end(input_file, location, output_file) | Divide desde la ubicación, y guarda la parte posterior como un nuevo archivo. |
| try_split_to_end(input_stream, location, output_stream) | Divide desde la ubicación especificada y guarda la parte posterior como un nuevo flujo de archivo Stream. |
| try_make_booklet(input_file, output_file) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| try_make_booklet(input_stream, output_stream) | Crea un folleto desde el InputStream al outputStream. |
| try_make_booklet(input_file, output_file, page_size) | Crea un folleto desde el inputFile al outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | Crea un folleto desde el input stream y guarda el resultado en el output stream. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | Crea un folleto personalizado desde el firstInputFile al outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | Crea un folleto personalizado desde el firstInputStream al outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Crea un folleto personalizado desde el firstInputFile al outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Crea un folleto desde el firstInputStream al outputStream. |
| try_make_n_up(input_file, output_file, x, y) | Crea un documento N-Up desde el firstInputFile al outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | Crea un documento N-Up desde el input stream y guarda el resultado en el output stream. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | Crea un documento N-Up desde el primer flujo de entrada al output stream. |
| try_make_n_up(first_input_file, second_input_file, output_file) | Crea un documento N-Up desde el firstInputFile al outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | Crea un documento N-Up desde el input stream y guarda el resultado en el output stream. |
| try_make_n_up(input_files, output_file, is_sidewise) | Crea un documento N-Up a partir de los archivos PDF de entrada múltiples hacia outputFile. <br/>            Cada página de outputFile contendrá múltiples páginas, que son una combinación con las páginas <br/>            en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente <br/>            si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | Crea un documento N-Up a partir de los flujos PDF de entrada múltiples hacia outputStream.<br/>            Cada página de outputStream contendrá múltiples páginas, que son una combinación con las páginas <br/>            en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente <br/>            si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| try_make_n_up(input_file, output_file, x, y, page_size) | Crea un documento N-Up a partir del archivo de entrada hacia outputFile. |
| try_resize_contents(source, destination, pages, parameters) | Redimensiona el contenido de las páginas del documento. |
| try_resize_contents(source, destination, pages, new_width, new_height) | Redimensiona el contenido de las páginas del documento. <br/>            Reduce el contenido de la página y agrega márgenes.<br/>            El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| try_resize_contents(source, destination, pages, parameters) | Redimensiona el contenido de las páginas del documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página. |
| concatenate(first_input_file, sec_input_file, output_file) | Concatena archivos y guarda el resultado en el objeto HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | Concatena archivos y almacena el resultado en el objeto HttpResponse. |
| concatenate(src, dest) | Concatena documentos. |
| concatenate(input_files, output_file) | Concatena archivos y guarda el resultado en el objeto HttpResposnse. |
| concatenate(input_stream, output_stream) | Concatena archivos y almacena el resultado en el objeto HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | Concatena archivos y guarda el resultado en el objeto HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | Concatena archivos y almacena el resultado en el objeto HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | Añade documentos al documento origen y guarda el resultado en el objeto response. |
| append(input_file, port_files, start_page, end_page, output_file) | Añade documentos al documento origen y guarda el resultado en el objeto HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | Añade documentos al documento origen y guarda el resultado en el objeto HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | Añade documentos al documento origen y guarda el resultado en el objeto response. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | Inserta el contenido del archivo en el archivo fuente y almacena el resultado en el objeto HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | Inserta el documento en otro documento y almacena el resultado en el objeto de respuesta. |
| insert(input_file, insert_location, port_file, page_number, output_file) | Inserta el contenido del archivo en el archivo fuente y almacena el resultado en el objeto HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | Inserta el documento en otro documento y almacena el resultado en el objeto de respuesta. |
| delete(input_file, page_number, output_file) | Elimina las páginas especificadas del documento y almacena el resultado en el objeto HttpResponse. |
| delete(input_stream, page_number, output_stream) | Elimina las páginas especificadas del documento y guarda el resultado en el objeto HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | Extrae las páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse. |
| extract(input_file, page_number, output_file) | Extrae las páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | Extrae las páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse. |
| extract(input_stream, page_number, output_stream) | Extrae las páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse. |
| split_from_first(input_file, location, output_file) | Divide el documento desde la primera página hasta la ubicación y guarda el resultado en los objetos HttpResponse. |
| split_from_first(input_stream, location, output_stream) | Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en el objeto HttpResponse. |
| split_to_end(input_file, location, output_file) | Divide desde la ubicación especificada y guarda la parte posterior en el objeto HttpResponse. |
| split_to_end(input_stream, location, output_stream) | Divide desde la ubicación especificada y guarda la parte posterior en el objeto HttpResponse. |
| make_booklet(input_file, output_file) | Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpResponse. |
| make_booklet(input_stream, output_stream) | Crear folleto a partir de un archivo PDF y lo almacena en HttpResponse. |
| make_booklet(input_file, output_file, page_size) | Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | Crear folleto a partir de un archivo PDF y lo almacena en HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | Crear folleto a partir de un archivo PDF y lo almacena en HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | Crear folleto a partir de un archivo PDF y lo almacena en HttpResponse. |
| make_n_up(input_file, output_file, x, y) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | Crea un documento N-Up a partir de los archivos PDF de entrada múltiples hacia outputFile. <br/>            Cada página de outputFile contendrá múltiples páginas, que son una combinación con las páginas <br/>            en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente <br/>            si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| make_n_up(input_streams, output_stream, is_sidewise) | Crea un documento N-Up a partir de los flujos PDF de entrada múltiples hacia outputStream.<br/>            Cada página de outputStream contendrá múltiples páginas, que son una combinación con las páginas <br/>            en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente <br/>            si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| make_n_up(input_file, output_file, x, y, page_size) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| split_to_pages(input_file, file_name_template) | Divide el archivo PDF en documentos de una sola página. |
| split_to_pages(input_stream, file_name_template) | Divide el archivo PDF en documentos de una sola página y lo guarda en la ruta especificada. La ruta se define mediante la plantilla de nombre de campo. |
| resize_contents(source, destination, pages, parameters) | Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | Redimensiona el contenido de las páginas del documento. <br/>            Reduce el contenido de la página y agrega márgenes.<br/>            El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| resize_contents(source, destination, pages, new_width, new_height) | Redimensiona el contenido de las páginas del documento. <br/>            Reduce el contenido de la página y agrega márgenes.<br/>            El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| resize_contents(source, destination, pages, parameters) | Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse. |
| resize_contents(source, pages, parameters) | Redimensiona las páginas del documento. Se añaden márgenes en blanco alrededor de la página reducida. |
| resize_contents(source, parameters) | Redimensiona las páginas del documento. Se añaden márgenes en blanco alrededor de la página reducida. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Redimensiona el contenido de las páginas del documento.<br/>            Reduce el contenido de la página y añade márgenes.<br/>            El nuevo tamaño del contenido se especifica en porcentajes. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | Redimensiona el contenido de las páginas del documento.<br/>            Reduce el contenido de la página y añade márgenes.<br/>            El nuevo tamaño del contenido se especifica en porcentajes. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona el contenido de la página y añade los márgenes especificados. <br/>            Los márgenes se especifican en unidades de espacio predeterminadas. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona el contenido de la página y añade los márgenes especificados. <br/>            Los márgenes se especifican en unidades de espacio predeterminadas. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona el contenido de la página y añade los márgenes especificados.<br/>            Los márgenes se especifican en porcentajes del tamaño inicial de la página. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | Redimensiona el contenido de la página y añade los márgenes especificados.<br/>            Los márgenes se especifican en porcentajes del tamaño inicial de la página. |
| add_page_break(src, dest, page_breaks) | Añade saltos de página en las páginas del documento. |
| add_page_break(src, dest, page_breaks) | Añade saltos de página en las páginas del documento. |
| add_page_break(src, dest, page_breaks) | Añade saltos de página en las páginas del documento. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

