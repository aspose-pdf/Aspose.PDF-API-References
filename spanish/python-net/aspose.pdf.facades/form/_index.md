---
title: "Form"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un objeto de formulario Acro."
type: docs
weight: 80
url: /es/python-net/aspose.pdf.facades/form/
---

## Form class

Clase que representa un objeto de formulario Acro.

El tipo Form expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Form(src_stream, dest_stream) | Inicializa una nueva instancia de la clase Form |
| Form() | Constructor de Form sin parámetros. |
| Form(src_file_name) | Inicializa una nueva instancia de la clase Form |
| Form(src_stream) | Inicializa una nueva instancia de la clase Form |
| Form(src_file_name, dest_file_name) | Inicializa una nueva instancia de la clase Form |
| Form(src_file_name, dest_stream) | Inicializa una nueva instancia de la clase Form |
| Form(src_stream, dest_file_name) | Inicializa una nueva instancia de la clase Form |
| Form(document) | Inicializa una nueva instancia de la clase Form |
| Form(document, dest_file_name) | Inicializa una nueva instancia de la clase Form |
| Form(document, dest_stream) | Inicializa una nueva instancia de la clase Form |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| import_result | Resultado de la última operación de importación. Matriz de objetos que describen el resultado de la importación para cada campo. |
| src_file_name | Obtiene o establece el nombre del archivo de origen. |
| dest_file_name | Obtiene o establece el nombre del archivo de destino. |
| src_stream | Obtiene o establece el flujo de origen. |
| dest_stream | Obtiene o establece el flujo de destino. |
| field_names | Obtiene la lista de nombres de campos del formulario. |
| form_submit_button_names | Obtiene todos los nombres de los botones de envío del formulario. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save() | Guarda el valor de los campos completados y cierra el documento Pdf abierto. |
| save(dest_file) | Guarda el documento en el archivo especificado. |
| save(dest_stream) | Guarda el documento en el flujo especificado. |
| fill_field(field_name, field_value) | Rellena el campo con un valor válido según un nombre de campo totalmente calificado.<br/>            Antes de rellenar los campos, se deben conocer todos los nombres de los campos y sus valores válidos correspondientes.<br/>            Tanto el nombre del campo como los valores son sensibles a mayúsculas y minúsculas.<br/>            Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres parciales <br/>            en contraste con Aspose.Pdf.Kit;<br/>            Por ejemplo, si el campo tiene el nombre completo "Form.Subform.TextField" debe especificar el nombre completo y no "TextField". <br/>            Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| fill_field(field_name, index) | Rellena el campo de caja de radio con un valor de índice válido según un nombre de campo totalmente calificado.<br/>            Antes de rellenar los campos, solo se debe conocer el nombre del campo. Mientras que el valor puede especificarse por su índice.<br/>            Aviso: Solo se aplica a campos de Caja de Radio, Caja Combo y Caja de Lista.<br/>            Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres parciales <br/>            en contraste con Aspose.Pdf.Kit;<br/>            Por ejemplo, si el campo tiene el nombre completo "Form.Subform.ListBoxField" debe especificar el nombre completo y no "ListBoxField". <br/>            Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| fill_field(field_name, be_checked) | Rellena el campo de casilla de verificación con un valor booleano.<br/>            Aviso: Solo se aplica a Casilla de Verificación.<br/>            Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres parciales <br/>            en contraste con Aspose.Pdf.Kit;<br/>            Por ejemplo, si el campo tiene el nombre completo "Form.Subform.CheckBoxField" debe especificar el nombre completo y no "CheckBoxField". <br/>            Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| fill_field(field_name, field_values) | Rellena los campos de cuadro de texto con valores de texto y guarda el documento.<br/>            Relevante para documentos firmados.<br/>            Aviso: Solo se aplica a Cuadro de Texto.<br/>            Tanto el nombre del campo como los valores son sensibles a mayúsculas y minúsculas. |
| fill_field(field_name, value, fit_font_size) | Rellena el campo de casilla de verificación con un valor booleano.<br/>            Aviso: Solo se aplica a Casilla de Verificación.<br/>            Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres parciales <br/>            en contraste con Aspose.Pdf.Kit;<br/>            Por ejemplo, si el campo tiene el nombre completo "Form.Subform.CheckBoxField" debe especificar el nombre completo y no "CheckBoxField". <br/>            Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| import_xml(input_xml_stream) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| fill_image_field(field_name, image_file_name) | Pega una imagen en el campo de botón existente como su apariencia según <br/>            su nombre de campo totalmente calificado. |
| fill_image_field(field_name, image_stream) | Sobrecarga la función de FillImageField.<br/>            La entrada es un flujo de imagen. |
| close() | Cierra archivos abiertos sin ningún cambio. |
| get_field_facade(field_name) | Devuelve el objeto FrogmFieldFacade que contiene todos los atributos de apariencia. |
| fill_fields(field_names, field_values, output) | Rellena los campos de cuadro de texto con valores de texto y guarda el documento.<br/>            Relevante para documentos firmados.<br/>            Aviso: Solo se aplica a Cuadro de Texto.<br/>            Tanto el nombre del campo como los valores son sensibles a mayúsculas y minúsculas. |
| get_button_option_current_value(field_name) | Devuelve el valor actual de los campos de opción de botón de radio. |
| get_field(field_name) | Devuelve el objeto FrogmFieldFacade que contiene todos los atributos de apariencia. |
| get_full_field_name(field_name) | Obtiene el nombre completo del campo según su nombre corto. |
| get_field_limit(field_name) | Obtén la limitación del campo de texto. |
| flatten_all_fields() | Aplana todos los campos. |
| flatten_field(field_name) | Aplana un campo especificado con el nombre de campo totalmente calificado.<br/>            Cualquier otro campo permanecerá sin cambios. Si el fieldName es inválido, <br/>            todos los campos permanecerán sin cambios. |
| fill_barcode_field(field_name, data) | Rellena un campo de código de barras según su nombre de campo totalmente calificado. |
| import_fdf(input_fdf_stream) | Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf. |
| export_fdf(output_fdf_stream) | Exporta el contenido de los campos del pdf al flujo fdf. |
| export_xml(output_xml_stream) | Exporta el contenido de los campos del pdf al flujo xml.<br/>            El valor del campo de botón no será exportado. |
| extract_xfa_data(output_xml_stream) | Extrae el paquete de datos XFA |
| set_xfa_data(input_xml_stream) | Reemplaza los datos XFA con el paquete de datos especificado. El paquete de datos puede extraerse usando ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | Importa el contenido de los campos del archivo xfdf(xml) y lo coloca en el nuevo pdf. |
| export_xfdf(output_xfdf_stream) | Exporta el contenido de los campos del pdf al flujo xml.<br/>            El valor del campo de botón no será exportado. |
| rename_field(field_name, new_field_name) | Renombra un campo. Tanto un campo AcroForm como un campo XFA son válidos. |
| get_rich_text(field_name) | Obtiene el valor de un campo de texto enriquecido, incluyendo la información de formato de cada carácter. |
| get_submit_flags(field_name) | Devuelve las banderas de envío del botón de envío |
| get_field_type(field_name) | Devuelve el tipo de campo. |
| is_required_field(field_name) | Determina si el campo es obligatorio o no. |
| get_field_flag(field_name) | Devuelve las banderas del campo. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

