---
title: "Clase Aspose::Pdf::Facades::Form"
linktitle: "Form"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::Form. Clase que representa un objeto de formulario Acro en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.facades/form/
---
## Form class


Clase que representa el objeto de formulario Acro.

```cpp
class Form : public Aspose::Pdf::Facades::SaveableFacade
```

## Nested classes

* Class [FormImportResult](./formimportresult/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [ImportStatus](./importstatus/) | Estado del campo importado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cierra los archivos abiertos sin realizar cambios. |
| [ExportFdf](./exportfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporta el contenido de los campos del pdf al flujo fdf. |
| [ExportXfdf](./exportxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporta el contenido de los campos del pdf al flujo xml. No se exportará el valor del campo de botón. |
| [ExportXml](./exportxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporta el contenido de los campos del pdf al flujo xml. No se exportará el valor del campo de botón. |
| [ExtractXfaData](./extractxfadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Extrae el paquete de datos XFA. |
| [FillBarcodeField](./fillbarcodefield/)(const System::String\&, const System::String\&) | Rellena un campo de código de barras según su nombre de campo totalmente calificado. |
| [FillField](./fillfield/)(const System::String\&, const System::String\&) | Rellena el campo con un valor válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, se deben conocer los nombres de todos los campos y sus valores válidos correspondientes. Tanto el nombre del campo como los valores distinguen entre mayúsculas y minúsculas. Tenga en cuenta que [Aspose.Pdf.Facades](../) solo admite nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo "Form.Subform.TextField" debe especificar el nombre completo y no "TextField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](./fillfield/)(const System::String\&, int32_t) | Rellena el campo de caja de radio con un valor de índice válido según un nombre de campo totalmente calificado. Antes de rellenar los campos, solo se debe conocer el nombre del campo. El valor puede especificarse por su índice. Aviso: Solo se aplica a campos de Caja de Radio, Caja Combo y Caja de Lista. Tenga en cuenta que [Aspose.Pdf.Facades](../) solo admite nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo "Form.Subform.ListBoxField" debe especificar el nombre completo y no "ListBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](./fillfield/)(const System::String\&, bool) | Rellena el campo de casilla de verificación con un valor booleano. Aviso: Solo se aplica a Casilla de Verificación. Tenga en cuenta que [Aspose.Pdf.Facades](../) solo admite nombres de campo completos y no funciona con nombres de campo parciales, a diferencia de Aspose.Pdf.Kit; por ejemplo, si el campo tiene el nombre completo "Form.Subform.CheckBoxField" debe especificar el nombre completo y no "CheckBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](./fillfield/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Rellena un campo con múltiples selecciones. Nota: solo para el campo de Caja de Lista AcroForm. |
| [FillField](./fillfield/)(const System::String\&, const System::String\&, bool) | Rellena el campo con el valor especificado. |
| [FillFields](./fillfields/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<System::String\>\&, System::SharedPtr\<System::IO::Stream\>\&) | Rellena los campos de cuadro de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Aviso: Solo se aplica al cuadro [Text](../../aspose.pdf.text/). Tanto el nombre de los campos como los valores distinguen entre mayúsculas y minúsculas. |
| [FillImageField](./fillimagefield/)(const System::String\&, const System::String\&) | Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado. |
| [FillImageField](./fillimagefield/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Sobrecarga la función FillImageField. La entrada es un flujo de imagen. |
| [FlattenAllFields](./flattenallfields/)() | Aplana todos los campos. |
| [FlattenField](./flattenfield/)(const System::String\&) | Aplana un campo especificado con el nombre de campo totalmente calificado. Cualquier otro campo permanecerá inalterable. Si el fieldName es inválido, todos los campos permanecerán inalterables. |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor de [Form](./) con dos parámetros de flujo. Especifique el mismo flujo de origen y destino para la actualización incremental. |
| [Form](./form/)() | Constructor de [Form](./) sin parámetros. |
| [Form](./form/)(const System::String\&) | Constructor de [Form](./). |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&) | Constructor para el formulario. |
| [Form](./form/)(const System::String\&, const System::String\&) | Constructor de la clase [Form](./). Especifique el mismo nombre de archivo de origen y el nombre de archivo de destino para realizar una actualización incremental. |
| [Form](./form/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor de [Form](./). |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Constructor de [Form](./). |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [Form](./) basado en el *documento*. |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Inicializa un nuevo objeto [Form](./) basado en el *documento*. |
| [Form](./form/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa un nuevo objeto [Form](./) basado en el *documento*. |
| [Form](./form/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Crea un formulario que guardará el resultado en un objeto HttpResponse. |
| [Form](./form/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Crea un formulario que guardará el resultado en un objeto HttpResponse. |
| [get_AttachmentName](./get_attachmentname/)() const | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [get_DestFileName](./get_destfilename/)() const | Obtiene el nombre del archivo de destino. |
| [get_DestStream](./get_deststream/)() const | Obtiene el flujo de destino. |
| [get_FieldNames](./get_fieldnames/)() | Obtiene la lista de nombres de campos del formulario. |
| [get_FormSubmitButtonNames](./get_formsubmitbuttonnames/)() | Obtiene todos los nombres de los botones de envío del formulario. |
| [get_ImportResult](./get_importresult/)() | Resultado de la última operación de importación. Matriz de objetos que describen el resultado de la importación para cada campo. |
| [get_Response](./get_response/)() const | Obtiene el objeto Response donde se almacenará el resultado de la operación. |
| [get_SaveOptions](./get_saveoptions/)() const | Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Obtiene el nombre del archivo fuente. |
| [get_SrcStream](./get_srcstream/)() const | Obtiene el flujo de origen. |
| [GetButtonOptionCurrentValue](./getbuttonoptioncurrentvalue/)(const System::String\&) | Devuelve el valor actual de los campos de opción de botón de radio. |
| [GetButtonOptionValues](./getbuttonoptionvalues/)(const System::String\&) | Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. Este método tiene sentido para grupos de botones de radio. |
| [GetField](./getfield/)(const System::String\&) | Obtiene el valor del campo según su nombre. |
| [GetFieldFacade](./getfieldfacade/)(const System::String\&) | Devuelve el objeto FrofmFieldFacade que contiene todos los atributos de apariencia. |
| [GetFieldFlag](./getfieldflag/)(const System::String\&) | Devuelve los indicadores del campo. |
| [GetFieldLimit](./getfieldlimit/)(const System::String\&) | Obtiene la limitación del campo de texto. |
| [GetFieldType](./getfieldtype/)(const System::String\&) | Devuelve el tipo de campo. |
| [GetFullFieldName](./getfullfieldname/)(const System::String\&) | Obtiene el nombre completo del campo según su nombre corto. |
| [GetRichText](./getrichtext/)(const System::String\&) | Obtiene el valor de un campo Rich [Text](../../aspose.pdf.text/), incluyendo la información de formato de cada carácter. |
| [GetSubmitFlags](./getsubmitflags/)(const System::String\&) | Devuelve los indicadores de envío del botón de envío. |
| [ImportFdf](./importfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf. |
| [ImportXfdf](./importxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf. |
| [ImportXml](./importxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [ImportXml](./importxml/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [IsRequiredField](./isrequiredfield/)(const System::String\&) | Determina si el campo es obligatorio o no. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Renombra un campo. Ya sea un campo AcroForm o XFA está bien. |
| [Save](./save/)() | Guarda el valor de los campos completados y cierra el documento [Pdf](../../aspose.pdf/) abierto. |
| [Save](./save/)(System::String) override | Guarda el documento en el archivo especificado. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el documento en el flujo especificado. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Establece el nombre del archivo de destino. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de destino. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Establece el objeto Response donde se almacenará el resultado de la operación. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Establece el nombre del archivo fuente. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de origen. |
| [SetXfaData](./setxfadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Reemplaza los datos XFA con el paquete de datos especificado. El paquete de datos puede extraerse usando ExtractXfaData. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
