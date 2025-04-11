---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.FormEditor. Clase para editar formularios añadiendo/eliminando campos, etc.
type: docs
weight: 4330
url: /es/net/aspose.pdf.facades/formeditor/
---
## Clase FormEditor

Clase para editar formularios (añadiendo/eliminando campos, etc.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Constructor para FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Inicializa un nuevo objeto `FormEditor` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en el que se está trabajando. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Establece opciones para el cuadro combinado con valores de exportación. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Establece los atributos visuales del campo. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Establece los elementos que se agregarán a la lista o cuadro combinado recién creado. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Obtiene o establece el tamaño del elemento del botón de opción (cuando se agrega un nuevo campo de botón de opción). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | El miembro para registrar el espacio entre dos botones de opción vecinos en píxeles, el valor predeterminado es 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | La bandera para indicar si los botones de opción están dispuestos horizontal o verticalmente, el valor predeterminado es verdadero. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Establece las banderas de envío del botón de envío |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Agrega un campo del tipo especificado al formulario. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Agrega un campo del tipo especificado al formulario. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Agrega JavaScript para un campo PushButton. Si existe un evento antiguo, se agrega un nuevo evento después de él. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Agrega un nuevo elemento al cuadro de lista. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Agrega un nuevo elemento con valor de exportación al campo de cuadro de lista existente, solo para el campo de cuadro combinado AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Agrega un botón de envío al formulario. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Cierra la fachada. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Copia un campo existente a la misma posición en el número de página especificado. Se producirá un nuevo documento que contiene todo lo que tiene el documento fuente, excepto el campo copiado recientemente. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Copia un campo existente a una nueva posición especificada por el número de página y las coordenadas. Se producirá un nuevo documento que contiene todo lo que tiene el documento fuente, excepto el campo copiado recientemente. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Copia un campo existente de un documento PDF a otro documento con el número de página y las coordenadas originales. Nota: Solo para campos AcroForm (excluyendo el cuadro de opción). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las coordenadas originales. Nota: Solo para campos AcroForm (excluyendo el cuadro de opción). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las coordenadas. Nota: Solo para campos AcroForm (excluyendo el cuadro de opción). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Cambia los atributos visuales de todos los campos en el documento PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Cambia los atributos visuales de todos los campos con el tipo de campo especificado. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Cambia los atributos visuales del campo especificado. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Elimina un elemento del campo de lista. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Elimina la fachada. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Obtiene las banderas del campo. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Establece la nueva posición del campo. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Elimina el campo del formulario. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Elimina la acción de envío del campo. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Cambia el nombre del campo. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Restablece todos los atributos visuales a un valor vacío. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Restablece todos los atributos visuales de la fachada interna a un valor vacío. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Guarda el documento PDF en el archivo especificado. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Establece el estilo de alineación de un campo de texto. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Establece el estilo de alineación vertical de un campo de texto. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Establece las banderas del campo |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Establece los atributos del campo. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Establece el número de combinaciones para un campo de texto de una sola línea regular (el campo se divide automáticamente en tantas posiciones igualmente espaciadas, o combinaciones, como el valor del parámetro combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Establece el recuento máximo de caracteres del campo de texto. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Establece JavaScript para un campo PushButton. Si existía un JavaScript antiguo, será reemplazado por el nuevo. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Establece la bandera de envío del botón de envío. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Establece la URL del botón. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Cambia un campo de texto de una sola línea a uno de múltiples líneas. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../)