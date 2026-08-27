---
title: "PdfFileInfo"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para acceder a la metainformación de un documento PDF."
type: docs
weight: 270
url: /es/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Representa una clase para acceder a la metainformación de un documento PDF.

El tipo PdfFileInfo expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfFileInfo() | Inicializa una nueva instancia de la clase **Aspose.Pdf.Facades.PdfFileInfo** con valores predeterminados. |
| PdfFileInfo(input_stream) | Inicializa una nueva instancia de la clase **PdfFileInfo**. |
| PdfFileInfo(input_stream, password) | Inicializa una nueva instancia de la clase **PdfFileInfo**. |
| PdfFileInfo(input_file) | Inicializa una nueva instancia de la clase **PdfFileInfo**. |
| PdfFileInfo(input_file, password) | Inicializa una nueva instancia de la clase **PdfFileInfo**. |
| PdfFileInfo(document) | Inicializa una nueva instancia de la clase **PdfFileInfo**. |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| author | Obtiene o establece la información del Autor del documento PDF. |
| is_encrypted | Comprueba si el documento PDF está encriptado. |
| is_pdf_file | Comprueba si la entrada de origen es un archivo PDF válido. |
| use_strict_validation | Utiliza reglas de validación estrictas mediante el uso de la propiedad [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Obtiene o establece la información de **CreationDate** del documento PDF. |
| creator | Obtiene o establece la información del Creador del documento PDF. |
| has_collection | Devuelve true si el archivo de entrada actual es un archivo 'Portfolio' que contiene una colección de archivos PDF. |
| input_file | Obtiene o establece el archivo de entrada. |
| input_stream | Obtiene o establece el flujo de entrada. |
| keywords | Obtiene o establece la información de Keywords del documento PDF. |
| mod_date | Obtiene o establece la información de fecha ModDate del documento PDF. |
| number_of_pages | Obtiene el número de páginas del documento. |
| producer | Obtiene la información del Producer del documento PDF. |
| subject | Obtiene o establece la información del Subject del documento PDF. |
| title | Obtiene o establece la información del Title del documento PDF. |
| password_type | Devuelve el tipo de contraseña que se pasó al crear la instancia PdfFileInfo. Consulte los valores posibles en [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Tenga en cuenta que el documento pdf puede abrirse usando tanto la contraseña de usuario (o apertura) como la contraseña de propietario (o permisos, edición). |
| has_open_password | Devuelve true si se necesita una contraseña para abrir un documento pdf protegido con contraseña. |
| has_edit_password | Devuelve true si se necesita una contraseña para modificar permisos o la propiedad de seguridad del documento.<br/>            Tenga en cuenta que esta propiedad solo puede leerse si se proporcionó una contraseña válida en el constructor [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            En caso de que PasswordType sea Inaccessible (significa que se proporcionó una contraseña inválida) la lectura de esta propiedad fallará con [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_doc) | Inicializa la fachada. |
| bind_pdf(src_file) | Inicializa la fachada. |
| bind_pdf(src_stream) | Inicializa la fachada. |
| save(dest_stream) | Guarda el documento PDF actualizado en el flujo especificado. |
| save(dest_file) | Guarda el documento PDF actualizado en el archivo especificado. |
| save_new_info(output_stream) | Guarda el documento PDF actualizado en el flujo especificado. |
| save_new_info(output_file) | Guarda el documento PDF actualizado en el archivo especificado. |
| close() | Desinicializa la instancia. |
| clear_info() | Borra toda la información meta del documento PDF. |
| get_document_privilege() | Obtiene la configuración de privilegios del documento PDF. |
| get_meta_info(name) | Obtiene la información personalizada del documento PDF con el nombre de la propiedad. Si no hay ninguna propiedad que coincida con el nombre, devolverá una cadena vacía. |
| get_page_height(page_num) | Obtiene la altura de la página especificada. |
| get_page_rotation(page_num) | Obtiene la rotación de la página especificada. |
| get_page_width(page_num) | Obtiene el ancho de la página especificada. |
| get_page_x_offset(page_num) | Obtiene el desplazamiento horizontal del área de visualización de la página especificada. |
| get_page_y_offset(page_num) | Obtiene el desplazamiento vertical del área de visualización de la página especificada. |
| get_pdf_version() | Obtiene la información de versión del documento PDF. |
| set_meta_info(name, value) | Establece información personalizada del documento PDF. |
| save_new_info_with_xmp(output_file_name) | Cambia las propiedades especificadas explícitamente al establecer la información del archivo, las demás propiedades permanecen. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

