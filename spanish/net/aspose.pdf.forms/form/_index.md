---
title: Form
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase que representa el objeto de formulario.
type: docs
weight: 3020
url: /es/net/aspose.pdf.forms/form/
---
## Form class

Clase que representa el objeto de formulario.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Si se establece, todos los campos del formulario se volverán a calcular cuando se cambie cualquier campo. El valor predeterminado es verdadero. Establézcalo en falso para aumentar el rendimiento al completar un formulario con una gran cantidad de campos calculados. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Si se establece, los campos de formulario ausentes se crearán automáticamente si se presentan en las anotaciones. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Permite establecer el orden de cálculo de los campos. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Obtiene el número de campos de este formulario. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Obtiene o establece la apariencia predeterminada del formulario (objeto que describe la fuente, el tamaño del texto y el color predeterminados para los campos del formulario). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Obtiene los recursos predeterminados colocados en este formulario. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Si esta propiedad es verdadera, se dibujarán rectángulos de límite rojos adicionales para los contenedores de elementos Xfa exclGroup requeridos Esta propiedad se introdujo debido a la ausencia de análogos para exclGroup durante la conversión de la representación Xfa de formularios a estándar. Es falso por defecto. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Obtiene una lista de todos los campos en el nivel más bajo de forma jerárquica. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Si esta propiedad es verdadera, el valor de la clave NeedsRendering se ignorará durante la conversión Formulario XFA a formulario estándar. Es falso por defecto. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Devuelve verdadero si el objeto es seguro para subprocesos. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Obtiene el campo del formulario por nombre de campo. Lanza una excepción si no se encuentra el campo. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Si esta propiedad es verdadera, el diccionario "Perms" se eliminará del documento pdf después de la conversión de documentos dinámicos a estándar. El diccionario "Perms" puede contener reglas que perturban la visualización de la selección de campos obligatorios en Adobe Acrobat Reader. Es falso por defecto. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Si se establece, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que altera su contenido anterior, a diferencia de una actualización incremental. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Si se establece, el documento contiene al menos un campo de firma. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Devuelve el objeto de sincronización. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Obtiene el tipo del formulario. Los valores posibles son: Estándar, Estático, Dinámico. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Obtiene datos XFA del formulario (si está presente). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Agrega campo en el formulario. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Agrega campo en el formulario. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Agrega un nuevo campo al formulario; Si este campo ya está colocado en otro o en este formulario, se crea la copia del campo. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Agrega una apariencia adicional del campo a la página especificada del documento en la ubicación especificada. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Establece XFA del formulario al valor especificado. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Copia los campos colocados en el formulario en array. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Eliminar campo del formulario. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Elimina campo del formulario por su nombre. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Elimina todos los campos del formulario y coloca sus valores directamente en la página. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Obtiene la enumeración de los campos del formulario. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Devuelve campos dentro del rectángulo especificado. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Comprobar si el formulario ya tiene el campo especificado. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Determina si el campo con el nombre especificado ya se agregó al Formulario. |

## Campos

| Nombre | Descripción |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Los formularios pueden contener información de firma, es decir, pueden estar firmados o no firmados. Y la vista del formulario a veces debe depender de si el formulario está firmado o no. debe representarse como firmado o sin firmar. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Clase que describe la configuración para el procedimiento de acoplamiento de formularios. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Los formularios pueden contener información de firma y pueden estar firmados o sin firmar. A veces, la vista de los formularios en el visor debe depender de si el formulario está firmado o no. Esta enumeración enumera los posibles modos de representación durante la conversión del tipo de formulario con respecto al signo. |

### Ver también

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* espacio de nombres [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
