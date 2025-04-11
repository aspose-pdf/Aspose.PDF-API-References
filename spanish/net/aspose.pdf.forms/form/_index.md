---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Forms.Form. Clase que representa el objeto formulario
type: docs
weight: 5070
url: /es/net/aspose.pdf.forms/form/
---
## Clase Form

Clase que representa el objeto formulario.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Si se establece, todos los campos del formulario se recalcularán cuando se cambie cualquier campo. El valor predeterminado es verdadero. Establezca en falso para aumentar el rendimiento al llenar el formulario con una gran cantidad de campos calculados. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Si se establece, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Permite establecer el orden de cálculo de los campos. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Obtiene el número de campos en este formulario. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Obtiene o establece la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño del texto y el color para los campos en el formulario). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Obtiene los recursos predeterminados colocados en este formulario. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Si esta propiedad es verdadera, se dibujarán rectángulos de límite rojo adicionales para los contenedores de elementos exclGroup requeridos de Xfa. Esta propiedad se introdujo debido a la ausencia de análogos para el exclGroup durante la conversión de la representación Xfa de formularios a estándar. Es falso por defecto. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Obtiene la lista de todos los campos en el nivel más bajo del formulario jerárquico. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Si esta propiedad es verdadera, el valor de la clave NeedsRendering se ignorará durante la conversión del formulario XFA al formulario estándar. Es falso por defecto. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Devuelve verdadero si el objeto es seguro para subprocesos. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Obtiene el campo del formulario por nombre de campo. Lanza una excepción si no se encuentra el campo. (2 indexadores) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Si esta propiedad es verdadera, el diccionario "Perms" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario "Perms" puede contener reglas que interfieren con la visualización de la selección de campos obligatorios en Adobe Acrobat Reader. Es falso por defecto. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Si se establece, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escrito) de una manera que altera su contenido anterior, a diferencia de una actualización incremental. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Si se establece, el documento contiene al menos un campo de firma. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Devuelve el objeto de sincronización. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Obtiene el tipo del formulario. Los valores posibles son: Estándar, Estático, Dinámico. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Obtiene los datos XFA del formulario (si están presentes). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Agrega un campo al formulario. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Agrega un campo al formulario. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Agrega un nuevo campo al formulario; si este campo ya está colocado en otro formulario o en este, se crea una copia del campo. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Agrega una apariencia adicional del campo a la página especificada del documento en la ubicación especificada. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Establece el XFA del formulario al valor especificado. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Copia los campos colocados en el formulario a un array. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Elimina un campo del formulario. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Elimina un campo del formulario por su nombre. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Exporta los campos del formulario PDF a formato JSON y escribe el resultado en el flujo proporcionado. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Exporta los campos del formulario PDF a formato JSON y escribe el resultado en el archivo especificado. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Elimina todos los campos del formulario y coloca sus valores directamente en la página. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Obtiene la enumeración de los campos del formulario. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Devuelve los campos dentro del rectángulo especificado. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Verifica si el formulario ya tiene el campo especificado. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Determina si el campo con el nombre especificado ya se ha agregado al formulario. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Determina si el campo con el nombre especificado ya se ha agregado al formulario, con la capacidad de buscar en la jerarquía de campos hijos. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importa los campos del formulario PDF desde el formato JSON proporcionado en el flujo. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importa los campos del formulario PDF desde el formato JSON proporcionado en el archivo especificado. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Hace que las anotaciones de los campos del formulario sean independientes. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Elimina la apariencia del campo en el índice especificado. Si solo queda una apariencia hija, el método la incrusta en el campo. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Los formularios pueden contener información de firma, es decir, pueden estar firmados o no firmados. Y la vista del formulario a veces debe depender de si el formulario está firmado o no. Esta propiedad indica al convertidor del formulario (por ejemplo, durante la conversión del formulario XFA al formulario estándar) si el formulario resultante debe renderizarse como firmado o no firmado. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Clase que describe la configuración para el procedimiento de aplanamiento del formulario. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Los formularios pueden contener información de firma y pueden estar firmados o no firmados. A veces, la vista de los formularios en el visor debe depender de si el formulario está firmado o no. Este enum enumera los posibles modos de renderización durante la conversión del tipo de formulario en relación con la firma. |

### Véase También

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)