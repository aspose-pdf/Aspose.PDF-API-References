---
title: Form
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase que representa el objeto de formulario Acro.
type: docs
weight: 2300
url: /es/net/aspose.pdf.facades/form/
---
## Form class

Clase que representa el objeto de formulario Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Form](form#constructor)() | Constructor de Formulario sin parametros. |
| [Form](form#constructor_1)(Document) | Inicializa nuevo[`Form`](../form) objeto sobre la base de la*document* . |
| [Form](form#constructor_4)(Stream) | Constructor para form. |
| [Form](form#constructor_8)(string) | Constructor de Form. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | Obtiene o establece el nombre del archivo adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como archivo adjunto. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. Valor posible: en línea / archivo adjunto. Valor predeterminado: en línea. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | Establece el formato de archivo PDF. El archivo de resultados se guardará en el formato de archivo especificado. Si no se especifica esta propiedad, el archivo se guardará en formato PDF predeterminado sin conversión. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Obtiene la lista de nombres de campo en el formulario. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Obtiene todos los nombres de los botones de envío de formularios. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Resultado de la última operación de importación. Matriz de objetos que describen el resultado de la importación para cada campo. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | Obtiene o establece el objeto Respuesta donde se almacenará el resultado de la operación. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Obtiene o establece opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inicializa la fachada. |
| override [Close](../../aspose.pdf.facades/form/close)() | Cierra los archivos abiertos sin cambios. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | Exporta el contenido de los campos del pdf al flujo fdf. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | Exporta el contenido de los campos del pdf al flujo xml. El valor del campo del botón no se exportará. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | Exporta el contenido de los campos del pdf al flujo xml. El valor del campo del botón no se exportará. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | Extrae el paquete de datos XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Rellene un campo de código de barras según su nombre de campo completo. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Rellena el campo de la casilla de verificación con un valor booleano. Aviso: solo se aplica a la casilla de verificación. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf .Kit; Por ejemplo, si el campo tiene el nombre completo "Formulario.Subformulario.CheckBoxField", debe especificar el nombre completo y no "CheckBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Rellena el campo de cuadro de radio con un valor de índice válido según un nombre de campo completo. Antes de rellenar los campos, solo se debe conocer el nombre del campo. Si bien el valor se puede especificar por su índice. Aviso: solo se aplica a los campos Radio Box, Combo Box y List Box. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.ListBoxField", debe especificar el nombre completo y no "ListBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Rellena el campo con un valor válido según un nombre de campo completo. Antes de rellenar los campos, se deben conocer los nombres de cada campo y sus correspondientes valores válidos. Tanto el nombre como los valores de los campos distinguen entre mayúsculas y minúsculas. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.TextField", debe especificar el nombre completo y no "Campo de texto". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Rellene un campo con varias selecciones. Nota: solo para el campo de cuadro de lista de AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Rellena el campo con el valor especificado. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Rellena los campos del cuadro de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Aviso: solo se aplica al cuadro de texto. Tanto el nombre como los valores de los campos distinguen entre mayúsculas y minúsculas. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | Sobrecarga la función de FillImageField. La entrada es un flujo de imágenes. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Pega una imagen en el campo de botón existente según su apariencia de acuerdo con su nombre de campo completo. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Aplana todos los campos. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Aplana un campo especificado con el nombre de campo completo. Cualquier otro campo permanecerá inalterable. Si el nombre del campo no es válido, todos los campos permanecerán inalterables. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Devuelve el valor actual para los campos de opción de botón de radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Obtiene los campos de opción del botón de opción y los valores relacionados según el nombre del campo. Este método tiene significado para los grupos de botones de opción. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Obtiene el valor del campo según su nombre de campo. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Devuelve el objeto FrofmFieldFacade que contiene todos los atributos de apariencia. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Devuelve banderas del campo. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Obtener la limitación del campo de texto. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Devuelve el tipo de campo. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Obtiene el nombre de campo completo según su nombre de campo abreviado. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Obtenga el valor de un campo de texto enriquecido, incluida la información de formato de cada carácter. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Devuelve las banderas de envío del botón de envío |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Importa el contenido de los campos del archivo fdf y los pone en el nuevo pdf. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Importa el contenido de los campos del archivo xml y los pone en el nuevo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Importa el contenido de los campos del archivo xml y los pone en el nuevo pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Determina si el campo es obligatorio o no. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Cambia el nombre de un campo. El campo AcroForm o el campo XFA está bien. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Guarda el documento en el flujo especificado. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Guarda el documento en el archivo especificado. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | Reemplaza los datos XFA con el paquete de datos especificado. El paquete de datos se puede extraer utilizando ExtractXfaData. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Clase que describe el resultado de la importación de campos. |
| enum [ImportStatus](form.importstatus) | Estado del campo importado |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
