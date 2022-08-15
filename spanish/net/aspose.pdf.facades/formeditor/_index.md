---
title: FormEditor
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase para editar formularios agregar/eliminar campo etc.
type: docs
weight: 2340
url: /es/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Clase para editar formularios (agregar/eliminar campo, etc.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FormEditor](formeditor#constructor)() | Constructor para FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | Inicializa nuevo[`FormEditor`](../formeditor) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | Obtiene o establece el nombre del archivo adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como archivo adjunto. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. Valor posible: en línea / archivo adjunto. Valor predeterminado: en línea. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | Establece el formato de archivo PDF. El archivo de resultados se guardará en el formato de archivo especificado. Si no se especifica esta propiedad, el archivo se guardará en formato PDF predeterminado sin conversión. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Establece opciones para el cuadro combinado con valores de exportación. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Establece atributos visuales del campo. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Establece los elementos que se agregarán al cuadro de lista o cuadro combinado recién creado. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Obtiene o establece el tamaño del elemento del botón de opción (cuando se agrega un nuevo campo de botón de opción). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | El miembro para registrar la brecha entre dos botones de radio vecinos en píxeles, el valor predeterminado es 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | El indicador para indicar si las radios están dispuestas horizontal o verticalmente, el valor predeterminado es verdadero. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | Obtiene o establece el objeto Respuesta donde se almacenará el resultado de la operación. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Obtiene o establece opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Establecer las banderas de envío del botón Enviar |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Agregar campo del tipo especificado al formulario. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Agregar campo del tipo especificado al formulario. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Agregue JavaScript para un campo PushButton. Si existe un evento anterior, se agrega un evento nuevo después de él. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Agrega un nuevo elemento al cuadro de lista. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Agregar un nuevo elemento con Valor de exportación al campo de cuadro de lista existente, solo para el campo de cuadro combinado de AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Agregar botón de envío en el formulario. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inicializa la fachada. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Cierra la fachada. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Copia un campo existente en la misma posición en el número de página especificado. Se producirá un nuevo documento, que contiene todo lo que tiene el documento de origen excepto el campo recién copiado. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Copia un campo existente en una nueva posición especificada tanto por el número de página como por las ordenadas. Se producirá un nuevo documento, que contiene todo lo que tiene el documento de origen excepto el campo recién copiado. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Copia un campo existente de un documento PDF a otro documento con el número de página original y las ordenadas. Aviso: solo para campos de AcroForm (excepto cuadro de radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las ordenadas originales. Aviso: solo para campos de AcroForm (excepto el cuadro de radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Copia un campo existente de un documento PDF a otro documento con el número de página y las ordenadas especificados. Aviso: solo para campos de AcroForm (excepto cuadro de opción). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | Cambia los atributos visuales de todos los campos del documento PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Cambia los atributos visuales de todos los campos con el tipo de campo especificado. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Cambia los atributos visuales del campo especificado. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Eliminar elemento del campo de lista. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Obtener banderas de campo. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Establecer nueva posición de campo. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Eliminar campo del formulario. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Eliminar acción de envío del campo. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Cambiar nombre del campo. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Restablece todos los atributos visuales a un valor vacío. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | Restablece todos los atributos visuales de la fachada interior a un valor vacío. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Guarda el documento PDF en el archivo especificado. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Establecer el estilo de alineación de un campo de texto. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Establecer el estilo de alineación vertical de un campo de texto. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Establecer banderas de campo |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Establecer atributos de campo. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Establece el número de peines para un campo de texto regular de una sola línea (el campo se se divide automáticamente en tantas posiciones o peines igualmente espaciados como el valor del parámetro combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Establece el número máximo de caracteres del campo de texto. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | Establecer JavaScript para un campo PushButton. Si existía JavaScript antiguo, será reemplazado por el nuevo. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Establece el indicador de envío del botón de envío. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Establece la URL del botón. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Cambiar un campo de texto de una sola línea a uno de varias líneas. |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
