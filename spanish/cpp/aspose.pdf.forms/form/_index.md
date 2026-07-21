---
title: "Aspose::Pdf::Forms::Form clase"
linktitle: "Form"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Forms::Form clase. Clase que representa un objeto de formulario en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf.forms/form/
---
## Form class


Clase que representa un objeto de formulario.

```cpp
class Form : public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Nested classes

* Class [FlattenSettings](./flattensettings/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [SignDependentElementsRenderingModes](./signdependentelementsrenderingmodes/) | [Forms](../) puede contener información de firma y puede estar firmado o no firmado. A veces la vista de los formularios en el visor debe depender de si el formulario está firmado o no. Este enum enumera los posibles modos de renderizado durante la conversión del tipo de formulario en relación con la firma. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Field\>\&, int32_t) | Añade un campo al formulario. |
| [Add](./add/)(const System::SharedPtr\<Field\>\&) | Añade un campo al formulario. |
| [Add](./add/)(System::SharedPtr\<Field\>, const System::String\&, int32_t) | Añade un nuevo campo al formulario; si este campo ya está colocado en otro formulario o en este, se crea una copia del campo. |
| [AddFieldAppearance](./addfieldappearance/)(const System::SharedPtr\<Field\>\&, int32_t, const System::SharedPtr\<Rectangle\>\&) | Añade una apariencia adicional del campo a la página especificada del documento en la ubicación especificada. |
| [AssignXfa](./assignxfa/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&) | Establece [XFA](../xfa/) del formulario al valor especificado. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<Field\>\>\&, int32_t) | Copia los campos colocados en el formulario a una matriz. |
| [Delete](./delete/)(const System::SharedPtr\<Field\>\&) | Eliminar campo del formulario. |
| [Delete](./delete/)(const System::String\&) | Elimina el campo del formulario por su nombre. |
| [Flatten](./flatten/)() | Elimina todos los campos del formulario y coloca sus valores directamente en la página. |
| [get_AutoRecalculate](./get_autorecalculate/)() const | Si está activado, todos los campos del formulario se recalcularán cuando cualquier campo sea modificado. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados. |
| [get_AutoRestoreForm](./get_autorestoreform/)() const | Si está activado, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones. |
| [get_Count](./get_count/)() const override | Obtiene el número de campos en este formulario. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Obtiene la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño de texto y el color para los campos del formulario). |
| [get_DefaultResources](./get_defaultresources/)() | Obtiene los recursos predeterminados colocados en este formulario. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales alrededor de los contenedores de elementos exclGroup requeridos de Xfa. Esta propiedad se introdujo debido a la ausencia de análogos para el exclGroup durante la conversión de la representación Xfa de los formularios a estándar. Es falsa por defecto. |
| [get_Fields](./get_fields/)() | Obtiene la lista de todos los campos en el nivel más bajo del formulario jerárquico. |
| [get_HasXfa](./get_hasxfa/)() | Obtiene un valor que indica si el documento contiene un formulario [XFA](../xfa/). Esta propiedad se introdujo para determinar si se debe usar [IgnoreNeedsRendering](../) para eliminar el formulario [XFA](../xfa/) en los casos en que el formulario [XFA](../xfa/) está presente y [NeedsRendering](../) es falso. |
| [get_IgnoreNeedsRendering](./get_ignoreneedsrendering/)() const | Si esta propiedad es verdadera, el valor de la clave NeedsRendering será ignorado durante la conversión del formulario [XFA](../xfa/) a formulario Estándar. Es falso por defecto. |
| [get_IsSynchronized](./get_issynchronized/)() | Devuelve verdadero si el objeto es seguro para subprocesos. |
| [get_NeedsRendering](./get_needsrendering/)() | Obtiene un valor que indica si el documento requiere la eliminación del formulario dinámico [XFA](../xfa/). Esta propiedad se introdujo para determinar si se debe usar [IgnoreNeedsRendering](../) para eliminar el formulario [XFA](../xfa/) en los casos en que el formulario [XFA](../xfa/) está presente y [NeedsRendering](../) es falso. |
| [get_RemovePermission](./get_removepermission/)() const | Si esta propiedad es verdadera, el diccionario "Perms" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario "Perms" puede contener reglas que perturban la visualización de la selección de campos obligatorios en el lector Adobe Acrobat. Es falso por defecto. |
| [get_SignaturesAppendOnly](./get_signaturesappendonly/)() | Si está configurado, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que altera su contenido previo, en lugar de una actualización incremental. |
| [get_SignaturesExist](./get_signaturesexist/)() | Si está configurado, el documento contiene al menos un campo de firma. |
| [get_SyncRoot](./get_syncroot/)() const | Devuelve el objeto de sincronización. |
| [get_Type](./get_type/)() | Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic. |
| [get_XFA](./get_xfa/)() const | Obtiene los datos [XFA](../xfa/) del formulario (si están presentes). |
| [GetEnumerator](./getenumerator/)() override | Obtiene la enumeración de los campos del formulario. |
| [GetFieldsInRect](./getfieldsinrect/)(const System::SharedPtr\<Rectangle\>\&) | Devuelve los campos dentro del rectángulo especificado. |
| [HasField](./hasfield/)(const System::SharedPtr\<Field\>\&) | Comprueba si el formulario ya tiene el campo especificado. |
| [HasField](./hasfield/)(const System::String\&) | Determina si el campo con el nombre especificado ya se ha añadido al [Form](./). |
| [HasField](./hasfield/)(const System::String\&, bool) | Determina si el campo con el nombre especificado ya se ha añadido al [Form](./), con la capacidad de buscar en la jerarquía de hijos de los campos. |
| [idx_get](./idx_get/)(const System::String\&) | Obtiene el campo del formulario por nombre de campo. Lanza una excepción si no se encuentra el campo. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el campo del formulario por índice de campo. |
| [MakeFormAnnotationsIndependent](./makeformannotationsindependent/)(const System::SharedPtr\<Page\>\&) | Hace que las anotaciones de los campos del formulario sean independientes. |
| [RemoveFieldAppearance](./removefieldappearance/)(const System::SharedPtr\<Field\>\&, int32_t) | Elimina la apariencia del campo en el índice especificado. Si solo queda una apariencia hija, el método la incorpora al campo. |
| [set_AutoRecalculate](./set_autorecalculate/)(bool) | Si está activado, todos los campos del formulario se recalcularán cuando cualquier campo sea modificado. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados. |
| [set_AutoRestoreForm](./set_autorestoreform/)(bool) | Si está activado, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones. |
| [set_CalculatedFields](./set_calculatedfields/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<Field\>\>\>\&) | Permite establecer el orden de cálculo de los campos. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Establece la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño de texto y el color para los campos del formulario). |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | Si esta propiedad es verdadera, se dibujarán rectángulos rojos adicionales alrededor de los contenedores de elementos exclGroup requeridos de Xfa. Esta propiedad se introdujo debido a la ausencia de análogos para el exclGroup durante la conversión de la representación Xfa de los formularios a estándar. Es falsa por defecto. |
| [set_IgnoreNeedsRendering](./set_ignoreneedsrendering/)(bool) | Si esta propiedad es verdadera, el valor de la clave NeedsRendering será ignorado durante la conversión del formulario [XFA](../xfa/) a formulario Estándar. Es falso por defecto. |
| [set_RemovePermission](./set_removepermission/)(bool) | Si esta propiedad es verdadera, el diccionario "Perms" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario "Perms" puede contener reglas que perturban la visualización de la selección de campos obligatorios en el lector Adobe Acrobat. Es falso por defecto. |
| [set_SignaturesAppendOnly](./set_signaturesappendonly/)(bool) | Si está configurado, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que altera su contenido previo, en lugar de una actualización incremental. |
| [set_SignaturesExist](./set_signaturesexist/)(bool) | Si está configurado, el documento contiene al menos un campo de firma. |
| [set_Type](./set_type/)(FormType) | Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic. |
## Ver también

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
