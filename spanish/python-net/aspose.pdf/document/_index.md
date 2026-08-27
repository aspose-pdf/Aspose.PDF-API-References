---
title: "Documento"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un documento PDF"
type: docs
weight: 230
url: /es/python-net/aspose.pdf/document/
---

## Document class

Clase que representa un documento PDF

El tipo Documento expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Document(input) | Inicializa una nueva instancia de la clase Documento |
| Document(input, password, is_managed_stream) | Inicializa una nueva instancia de la clase Documento |
| Document(input, is_managed_stream) | Inicializa una nueva instancia de la clase Documento |
| Document(filename) | Inicializa una nueva instancia de la clase Documento |
| Document(input, password) | Inicializa una nueva instancia de la clase Documento |
| Document() | Inicializa un documento vacío. |
| Document(filename, options) | Inicializa una nueva instancia de la clase Documento |
| Document(input, options) | Inicializa una nueva instancia de la clase Documento |
| Document(filename, password) | Inicializa una nueva instancia de la clase Documento |
| Document(filename, password, is_managed_stream) | Inicializa una nueva instancia de la clase Documento |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| java_script | Colección de JavaScript a nivel de documento. |
| is_licensed | Obtiene el estado de licencia del sistema. Devuelve true si el sistema funciona en modo con licencia y false en caso contrario. |
| page_info | Obtiene o establece la información de la página (solo para el generador, no se rellena al leer el documento). |
| enable_signature_sanitization | Obtiene o establece la bandera para gestionar la sanitización de campos de firma. Habilitado por defecto. |
| is_pdfa_compliant | Obtiene si el documento es compatible con PDF/A. |
| is_pdf_ua_compliant | Obtiene si el documento es compatible con PDF/UA. |
| is_xref_gaps_allowed | Obtiene o establece si el documento es compatible con PDF/A. |
| named_destinations | Colección de destinos nombrados en el documento. |
| destinations | Obtiene la colección de destinos.<br/>            Obsoleto. Por favor use NamedDestinations. |
| pdf_format | Obtiene el formato PDF |
| embed_standard_fonts | Propiedad que declara que el documento debe incrustar todas las fuentes estándar Type1 <br/>            que tienen la bandera IsEmbedded establecida en true. Todas las fuentes PDF pueden incrustarse <br/>            en el documento simplemente configurando la bandera IsEmbedded en true, pero las fuentes estándar PDF Type1 son una excepción a esta regla.<br/>            La incrustación de fuentes Type1 requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario<br/>            no solo establecer la bandera IsEmbedded en true para la fuente especificada, sino también establecer <br/>            una bandera adicional a nivel del documento - EmbedStandardFonts = true;<br/>            Esta propiedad solo puede establecerse una vez para todas las fuentes.<br/>            Por defecto false. |
| disable_font_license_verifications | Muchas operaciones con fuentes no pueden ejecutarse si estas operaciones están prohibidas por la licencia de la fuente. <br/>            Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de licencia deshabilitan la incrustación de esa fuente. <br/>            Esta bandera se utiliza para desactivar cualquier restricción de licencia para todas las fuentes en el documento PDF actual.<br/>            Tenga cuidado al usar esta bandera. Cuando está establecida significa que la persona que la establece, <br/>            asume toda la responsabilidad de posibles violaciones de licencia o ley. <br/>            Por lo tanto, lo hace bajo su propio riesgo. <br/>            Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo <br/>            la ley de derechos de autor. <br/>            Por defecto false. |
| font_utilities | Instancia de IDocumentFontUtilities |
| collection | Obtiene la colección del documento. |
| version | Obtiene una versión de PDF del encabezado del archivo PDF. |
| open_action | Obtiene o establece la acción realizada al abrir el documento. |
| hide_tool_bar | Obtiene o establece la bandera que indica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| hide_menubar | Obtiene o establece la bandera que indica si la barra de menús debe ocultarse cuando el documento está activo. |
| hide_window_ui | Obtiene o establece la bandera que indica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| fit_window | Obtiene o establece la bandera que indica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
| center_window | Obtiene o establece la bandera que indica si la posición de la ventana del documento se centrará en la pantalla. |
| display_doc_title | Obtiene o establece la bandera que indica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| pages | Obtiene o establece la colección de páginas del documento.<br/>            Note que las páginas están numeradas a partir de 1 en la colección. |
| outlines | Obtiene los contornos del documento. |
| acciones | Obtiene las acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer las acciones BeforClosing, BeforSaving, etc. |
| formulario | Obtiene Acro Form del documento. |
| embedded_files | Obtiene la colección de archivos incrustados en el documento. |
| direction | Obtiene o establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| page_mode | Obtiene o establece el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
| non_full_screen_page_mode | Obtiene o establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| page_layout | Obtiene o establece el diseño de página que se utilizará cuando se abra el documento. |
| duplex | Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| file_name | Nombre del archivo PDF que originó este documento |
| info | Obtiene la información del documento. |
| metadata | Metadatos del documento.<br/>            (Un documento PDF puede incluir información general,<br/>             como el título del documento, el autor y las fechas de creación y modificación.<br/>             Esta información global sobre el documento (a diferencia de su contenido o estructura) se llama metadatos<br/>             y está destinada a ayudar en la catalogación y búsqueda de documentos en bases de datos externas.) |
| logical_structure | Obtiene la estructura lógica del documento. |
| handle_signature_change | Lanzar excepción si el documento se guarda con cambios y tiene firma |
| crypto_algorithm | Obtiene la configuración de seguridad si el documento está cifrado. <br/>            Si el documento no está cifrado, se lanzará la excepción correspondiente en .net 1.1<br/>            o CryptoAlgorithm será nulo para otras versiones de .net. |
| is_linearized | Obtiene o establece un valor que indica si el documento está linealizado. |
| permissions | Obtiene los permisos del documento. |
| is_encrypted | Obtiene el estado de cifrado del documento. Verdadero si el documento está cifrado. |
| id | Obtiene el ID. |
| background | Obtiene o establece el color de fondo del documento. |
| optimize_size | Obtiene o establece la bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se<br/>            fusionan en un único objeto PDF si esta bandera está activada. <br/>            Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria.<br/>            Valor predeterminado: false. |
| allow_reuse_page_content | Permite fusionar el contenido de las páginas para optimizar el tamaño del documento. Si se usa, entonces páginas diferentes pero duplicadas pueden referenciar al <br/>            mismo objeto de contenido. Tenga en cuenta que este modo puede causar efectos secundarios como cambiar el contenido de una página cuando se modifica otra página. |
| ignore_corrupted_objects | Obtiene o establece la bandera de ignorar errores en los archivos de origen. <br/>            Cuando las páginas del documento de origen se copian al documento de destino, el proceso de copia se detiene con una excepción <br/>            si algunos objetos en los archivos de origen están corruptos cuando esta bandera es falsa. <br/>            ejemplo: dest.Pages.Add(src.Pages);<br/>            Si esta bandera se establece en verdadero, los objetos corruptos serán reemplazados por valores vacíos.<br/>            Por defecto: true. |
| page_labels | Obtiene las etiquetas de página en el documento. |
| enable_object_unload | Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria. <br/>            Esto permite reducir el uso de memoria pero puede tener un efecto negativo en el rendimiento. |
| tagged_content | Obtiene acceso al contenido de TaggedPdf. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| save(output) | Almacena el documento en un flujo. |
| save(output_file_name) | Guarda el documento en el archivo especificado. |
| save() | Almacena el documento en un flujo. |
| save(options) | Guarda el documento con opciones de guardado. |
| save(output_file_name, format) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| save(output_stream, format) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| save(output_file_name, options) | Guarda el documento con un nuevo nombre estableciendo sus opciones de guardado. |
| save(output_stream, options) | Guarda el documento en un flujo con opciones de guardado. |
| export_annotations_to_xfdf(file_name) | Exporta todas las anotaciones del documento a un archivo XFDF. |
| export_annotations_to_xfdf(stream) | Exporta todas las anotaciones del documento al flujo. |
| send_to(device, output) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| send_to(device, from_page, to_page, output) | Envía ciertas páginas del documento al dispositivo de documento para su procesamiento. |
| send_to(device, output_file_name) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| send_to(device, from_page, to_page, output_file_name) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| import_annotations_from_xfdf(file_name) | Importa anotaciones desde un archivo XFDF al documento. |
| import_annotations_from_xfdf(stream) | Importa anotaciones desde el flujo al documento. |
| validate(output_log_file_name, format) | Valida el documento en el archivo especificado. |
| validate(output_log_stream, format) | Valida el documento en el archivo especificado. |
| validate(options) | Valida el documento en el archivo especificado. |
| convert(output_log_file_name, format, action, transparency_action) | Convierte el documento y guarda los errores en el archivo especificado. |
| convert(output_log_stream, format, action, transparency_action) | Convierte el documento y guarda los errores en el archivo especificado. |
| convert(output_log_file_name, format, action) | Convierte el documento y guarda los errores en el archivo especificado. |
| convert(options) | Convierte el documento usando opciones de conversión especificadas |
| convert(output_log_stream, format, action) | Convierte el documento y guarda los errores en el archivo especificado. |
| convert(fixup, output_log, only_validation, parameters) | Convierte el documento aplicando el Fixup. |
| convert(fixup, output_log, only_validation, parameters) | Convierte el documento aplicando el Fixup. |
| convert(src_file_name, load_options, dst_file_name, save_options) | Convierte el archivo fuente en formato fuente en el archivo de destino en formato destino. |
| convert(src_stream, load_options, dst_file_name, save_options) | Convierte el flujo en formato fuente en el archivo de destino en formato destino. |
| convert(src_file_name, load_options, dst_stream, save_options) | Convierte el flujo en formato fuente en el archivo de destino en formato destino. |
| convert(src_stream, load_options, dst_stream, save_options) | Convierte el flujo en formato fuente en el archivo de destino en formato destino. |
| flatten() | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| flatten(flatten_settings) | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | Encripta el documento. Llama luego a Save para obtener la versión encriptada del documento. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | Encripta el documento. Llama luego a Save para obtener la versión encriptada del documento. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | Encripta el documento. Llama luego a Save para obtener la versión encriptada del documento. |
| optimize_resources() | Optimiza los recursos en el documento:<br/>            1. Los recursos que no se usan en las páginas del documento se eliminan;<br/>            2. Los recursos iguales se combinan en un solo objeto; <br/>            3. Los objetos no utilizados se borran. |
| optimize_resources(strategy) | Optimiza los recursos en el documento según la estrategia de optimización definida. |
| bind_xml(file) | Vincula xml al documento |
| bind_xml(xml_file, xsl_file) | Vincula xml al documento |
| bind_xml(xml_stream, xsl_stream) | Vincula xml/xsl al documento |
| bind_xml(stream) | Vincula xml/xsl al documento |
| remove_pdfa_compliance() | Elimina el cumplimiento pdfa del documento |
| remove_pdf_ua_compliance() | Elimina el cumplimiento pdfUa del documento |
| set_title(title) | Establecer título para documento PDF |
| process_paragraphs() | Procesar párrafos para el generador. |
| remove_metadata() | Elimina los metadatos del documento. |
| change_passwords(owner_password, new_user_password, new_owner_password) | Cambia las contraseñas del documento. Esta acción solo se puede realizar usando la contraseña del propietario. |
| decrypt() | Descifra el documento. Llama luego a Save para obtener la versión descifrada del documento. |
| optimize() | Linealizar el documento para<br/>            - abrir la primera página lo más rápido posible;<br/>            - mostrar la página siguiente o seguir el enlace a la página siguiente lo más rápido posible;<br/>            - mostrar la página de forma incremental a medida que llega cuando los datos de una página se entregan a través de un canal lento (mostrar primero los datos más útiles);<br/>            - permitir que la interacción del usuario, como seguir un enlace, se realice incluso antes de que la página completa haya sido recibida y mostrada.<br/>            Invocar este método no guarda realmente el documento. Por el contrario, el documento solo se prepara para tener una estructura optimizada,<br/>            luego llama a Save para obtener el documento optimizado. |
| get_catalog_value(key) | Devuelve el valor del elemento del diccionario del catálogo. |
| free_memory() | Libera la memoria |
| save_xml(file) | Guardar documento en XML. |
| get_object_by_id(id) | Obtiene un objeto con el ID especificado en el documento. |
| repair() | Repara el documento dañado. |
| get_xmp_metadata(stream) | Obtener metadatos XMP del documento. |
| set_xmp_metadata(stream) | Establecer metadatos XMP del documento. |
| check(do_repair) | Valida el documento. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | Organiza los nodos del árbol de páginas en un documento en un árbol balanceado.<br/>            Sólo si el documento tiene más de nodesNumInSubtrees objetos de página, de lo contrario no hace nada. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

