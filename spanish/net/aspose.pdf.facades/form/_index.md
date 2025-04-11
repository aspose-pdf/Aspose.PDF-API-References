---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.Form. Clase que representa el objeto Acro form
type: docs
weight: 4290
url: /es/net/aspose.pdf.facades/form/
---
## Clase Form

Clase que representa el objeto Acro form.

```csharp
public sealed class Form : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Form](form/#constructor)() | Constructor de Form sin parámetros. |
| [Form](form/#constructor_1)(Document) | Inicializa un nuevo objeto `Form` basado en el *documento*. |
| [Form](form/#constructor_4)(Stream) | Constructor para el formulario. |
| [Form](form/#constructor_7)(string) | Constructor de Form. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en el que está trabajando. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Obtiene la lista de nombres de campos en el formulario. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Obtiene todos los nombres de botones de envío del formulario. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Resultado de la última operación de importación. Array de objetos que describen el resultado de la importación para cada campo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Cierra los archivos abiertos sin ningún cambio. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desecha la fachada. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exporta el contenido de los campos del pdf al flujo fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exporta el contenido de todos los campos en el documento a un flujo JSON. Los valores de los campos de botón no se exportan. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no se exportará. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no se exportará. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extrae el paquete de datos XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Rellena un campo de código de barras de acuerdo con su nombre de campo completamente calificado. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Rellena el campo de casilla de verificación con un valor booleano. Nota: Solo se aplica a la casilla de verificación. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.CheckBoxField", debe especificar el nombre completo y no "CheckBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Rellena el campo de botón de opción con un valor de índice válido de acuerdo con un nombre de campo completamente calificado. Antes de llenar los campos, solo debe conocerse el nombre del campo. Mientras que el valor puede especificarse por su índice. Nota: Solo se aplica a los campos de botón de opción, cuadro combinado y cuadro de lista. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.ListBoxField", debe especificar el nombre completo y no "ListBoxField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Rellena el campo con un valor válido de acuerdo con un nombre de campo completamente calificado. Antes de llenar los campos, deben conocerse los nombres de todos los campos y sus valores válidos correspondientes. Tanto los nombres de los campos como los valores son sensibles a mayúsculas y minúsculas. Tenga en cuenta que Aspose.Pdf.Facades solo admite nombres de campo completos y no funciona con nombres de campo parciales en contraste con Aspose.Pdf.Kit; Por ejemplo, si el campo tiene el nombre completo "Form.Subform.TextField", debe especificar el nombre completo y no "TextField". Puede usar la propiedad FieldNames para explorar los nombres de campo existentes y buscar el campo requerido por su nombre parcial. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Rellena un campo con múltiples selecciones. Nota: solo para el campo de cuadro de lista AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Rellena el campo con el valor especificado. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Rellena los campos de cuadro de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Nota: Solo se aplica a los cuadros de texto. Tanto los nombres de los campos como los valores son sensibles a mayúsculas y minúsculas. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Sobrecarga la función de FillImageField. La entrada es un flujo de imagen. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Pega una imagen en el campo de botón existente como su apariencia de acuerdo con su nombre de campo completamente calificado. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Aplana todos los campos. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Aplana un campo especificado con el nombre de campo completamente calificado. Cualquier otro campo permanecerá inalterado. Si el nombre del campo es inválido, todos los campos permanecerán inalterados. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Devuelve el valor actual para los campos de opción de botón de radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. Este método tiene significado para grupos de botones de radio. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Obtiene el valor del campo de acuerdo con su nombre de campo. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Devuelve el objeto FrofmFieldFacade que contiene todos los atributos de apariencia. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Devuelve las banderas del campo. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Obtiene la limitación del campo de texto. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Devuelve el tipo de campo. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Obtiene el nombre completo del campo de acuerdo con su nombre de campo corto. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Obtiene el valor de un campo de texto enriquecido, incluyendo la información de formato de cada carácter. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Devuelve las banderas de envío del botón de envío |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importa el contenido de los campos desde el archivo fdf y los coloca en el nuevo pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importa todos los datos de campo desde un flujo JSON a los campos del documento, emparejando los campos por sus nombres completos. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importa el contenido de los campos desde el archivo xfdf(xml) y los coloca en el nuevo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importa el contenido de los campos desde el archivo xml y los coloca en el nuevo pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importa el contenido de los campos desde el archivo xml y los coloca en el nuevo pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Determina si el campo es obligatorio o no. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Cambia el nombre de un campo. Tanto el campo AcroForm como el campo XFA son válidos. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Guarda el documento en el flujo especificado. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Guarda el documento en el archivo especificado. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Reemplaza los datos XFA con el paquete de datos especificado. El paquete de datos puede ser extraído usando ExtractXfaData. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Clase que describe el resultado de la importación de campo. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Estado del campo importado |

### Ver También

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)