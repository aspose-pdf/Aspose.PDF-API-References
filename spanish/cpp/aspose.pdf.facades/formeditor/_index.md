---
title: "Clase Aspose::Pdf::Facades::FormEditor"
linktitle: "FormEditor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::FormEditor. Clase para editar formularios (agregar/eliminar campos, etc.) en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf.facades/formeditor/
---
## FormEditor class


Clase para editar formularios (agregar/eliminar campos, etc.)

```cpp
class FormEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddField](./addfield/)(FieldType, const System::String\&, int32_t, float, float, float, float) | Agregar campo del tipo especificado al formulario. |
| [AddField](./addfield/)(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) | Agregar campo del tipo especificado al formulario. |
| [AddFieldScript](./addfieldscript/)(const System::String\&, const System::String\&) | Agregar JavaScript a un campo PushButton. Si existe un evento antiguo, el nuevo evento se agrega después de él. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::String\&) | Agrega un nuevo elemento al cuadro de lista. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Agregar un nuevo elemento con valor Export al campo de cuadro de lista existente, solo para el campo combo box de AcroForm. |
| [AddSubmitBtn](./addsubmitbtn/)(const System::String\&, int32_t, const System::String\&, const System::String\&, float, float, float, float) | Agregar botón de envío al formulario. |
| [Close](./close/)() override | Cierra la fachada. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t) | Copia un campo existente a la misma posición en el número de página especificado. Se producirá un nuevo documento que contiene todo lo que tiene el documento original, excepto el campo recién copiado. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Copia un campo existente a una nueva posición especificada por el número de página y las coordenadas. Se producirá un nuevo documento que contiene todo lo que tiene el documento original, excepto el campo recién copiado. |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&) | Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas originales. Aviso: Solo para campos AcroForm (excluyendo botones de opción). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t) | Copia un campo existente de un documento PDF a otro documento con el número de página especificado y coordenadas originales. Aviso: Solo para campos AcroForm (excluyendo botones de opción). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas especificados. Aviso: Solo para campos AcroForm (excluyendo botones de opción). |
| [DecorateField](./decoratefield/)(const System::String\&) | Cambia los atributos visuales del campo especificado. |
| [DecorateField](./decoratefield/)(FieldType) | Cambia los atributos visuales de todos los campos con el tipo de campo especificado. |
| [DecorateField](./decoratefield/)() | Cambia los atributos visuales de todos los campos en el documento PDF. |
| [DelListItem](./dellistitem/)(const System::String\&, const System::String\&) | Elimina el elemento del campo de lista. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor para [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::String\&, const System::String\&) | Constructor para [FormEditor](./). |
| [FormEditor](./formeditor/)() | Constructor para [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [FormEditor](./) basado en el *documento* . |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Inicializa un nuevo objeto [FormEditor](./) basado en el *documento* . |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa un nuevo objeto [FormEditor](./) basado en el *documento* . |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Crea [FormEditor](./) que guardará el resultado en un objeto HttpResponse. |
| [FormEditor](./formeditor/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Crea [FormEditor](./) que guardará el resultado en un objeto HttpResponse. |
| [get_AttachmentName](./get_attachmentname/)() const | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [get_DestFileName](./get_destfilename/)() const | Obtiene el nombre del archivo de destino. |
| [get_DestStream](./get_deststream/)() const | Obtiene el flujo de destino. |
| [get_ExportItems](./get_exportitems/)() const | Establece opciones para el cuadro combinado con valores de exportación. |
| [get_Facade](./get_facade/)() const | Establece los atributos visuales del campo. |
| [get_Items](./get_items/)() const | Establece los elementos que se agregarán a un cuadro de lista o combo recién creado. |
| [get_RadioButtonItemSize](./get_radiobuttonitemsize/)() const | Obtiene el tamaño del elemento del botón de radio (cuando se agrega un nuevo campo de botón de radio). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [get_RadioGap](./get_radiogap/)() | El miembro para registrar la separación entre dos botones de radio vecinos en píxeles, el valor predeterminado es 50. |
| [get_RadioHoriz](./get_radiohoriz/)() const | La bandera que indica si los botones de radio se disponen horizontalmente o verticalmente, el valor predeterminado es true. |
| [get_Response](./get_response/)() const | Obtiene el objeto Response donde se almacenará el resultado de la operación. |
| [get_SaveOptions](./get_saveoptions/)() const | Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Obtiene el nombre del archivo de origen. |
| [get_SrcStream](./get_srcstream/)() const | Obtiene el flujo de origen. |
| [get_SubmitFlag](./get_submitflag/)() const | Establece las banderas de envío del botón de envío. |
| [GetFieldAppearance](./getfieldappearance/)(const System::String\&) | Obtiene las banderas del campo. |
| [MoveField](./movefield/)(const System::String\&, float, float, float, float) | Establece la nueva posición del campo. |
| [RemoveField](./removefield/)(const System::String\&) | Elimina el campo del formulario. |
| [RemoveFieldAction](./removefieldaction/)(const System::String\&) | Elimina la acción de envío del campo. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Cambiar el nombre del campo. |
| [ResetFacade](./resetfacade/)() | Restablecer todos los atributos visuales a valor vacío. |
| [ResetInnerFacade](./resetinnerfacade/)() | Restablecer todos los atributos visuales de la fachada interna a valor vacío. |
| [Save](./save/)() | Guarda los cambios en el archivo de destino. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Establece el nombre del archivo de destino. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de destino. |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Establece opciones para el cuadro combinado con valores de exportación. |
| [set_Facade](./set_facade/)(const System::SharedPtr\<FormFieldFacade\>\&) | Establece los atributos visuales del campo. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | Establece los elementos que se agregarán a un cuadro de lista o combo recién creado. |
| [set_RadioButtonItemSize](./set_radiobuttonitemsize/)(double) | Establece el tamaño del elemento de botón de opción (cuando se agrega un nuevo campo de botón de opción). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [set_RadioGap](./set_radiogap/)(float) | El miembro para registrar la separación entre dos botones de radio vecinos en píxeles, el valor predeterminado es 50. |
| [set_RadioHoriz](./set_radiohoriz/)(bool) | La bandera que indica si los botones de radio se disponen horizontalmente o verticalmente, el valor predeterminado es true. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Establece el objeto Response donde se almacenará el resultado de la operación. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Establece el nombre del archivo de origen. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de origen. |
| [set_SubmitFlag](./set_submitflag/)(SubmitFormFlag) | Establece las banderas de envío del botón de envío. |
| [SetFieldAlignment](./setfieldalignment/)(const System::String\&, int32_t) | Establece el estilo de alineación de un campo de texto. |
| [SetFieldAlignmentV](./setfieldalignmentv/)(const System::String\&, int32_t) | Establece el estilo de alineación vertical de un campo de texto. |
| [SetFieldAppearance](./setfieldappearance/)(const System::String\&, Annotations::AnnotationFlags) | Establece los indicadores del campo. |
| [SetFieldAttribute](./setfieldattribute/)(const System::String\&, PropertyFlag) | Establece los atributos del campo. |
| [SetFieldCombNumber](./setfieldcombnumber/)(const System::String\&, int32_t) | Establece el número de divisiones (combs) para un campo de texto de una sola línea regular (el campo se divide automáticamente en tantas posiciones equidistantes, o combs, como indica el parámetro combNumber). |
| [SetFieldLimit](./setfieldlimit/)(const System::String\&, int32_t) | Establece el recuento máximo de caracteres del campo de texto. |
| [SetFieldScript](./setfieldscript/)(const System::String\&, const System::String\&) | Establece JavaScript para un campo PushButton. Si existía JavaScript anterior, será reemplazado por el nuevo. |
| [SetSubmitFlag](./setsubmitflag/)(const System::String\&, SubmitFormFlag) | Establece el indicador de envío del botón de envío. |
| [SetSubmitUrl](./setsubmiturl/)(const System::String\&, const System::String\&) | Establece la URL del botón. |
| [Single2Multiple](./single2multiple/)(const System::String\&) | Cambiar un campo de texto de una sola línea a uno de varias líneas. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
