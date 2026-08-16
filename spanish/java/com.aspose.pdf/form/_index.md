---
title: "Formulario"
linktitle: "Formulario"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un objeto de formulario."
type: docs
weight: 1740
url: /es/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Clase que representa un objeto de formulario.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Añade un campo al formulario. |
| [add](#add-com.aspose.pdf.Field-int-) | Añade un campo al formulario. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Añade un nuevo campo al formulario; si este campo ya está colocado en otro formulario o en este, se crea una copia del campo. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Añade un campo al formulario. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Añade una apariencia adicional del campo a la página especificada del documento en la ubicación especificada. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Añade una apariencia adicional del campo a la página especificada del documento. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Establece XFA del formulario al valor especificado. |
| [clear](#clear--) | Elimina todos los campos del formulario. No soportado. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Determina si el campo está presente en el formulario.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copia los campos colocados en el formulario a una matriz. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Copia los campos del formulario a una matriz. |
| [delete](#delete-com.aspose.pdf.Field-) | Elimina el campo del formulario. |
| [delete](#delete-java.lang.String-) | Elimina el campo del formulario por su nombre. |
| [flatten](#flatten--) | Elimina todos los campos de formulario estáticos y coloca sus valores directamente en la página. |
| [get_Item](#get_Item-int-) | Obtiene el campo del formulario por índice de campo. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene el campo del formulario por nombre de campo. Lanza una excepción si no se encuentra el campo. |
| [get_xfa](#get_xfa--) | Solo para uso interno |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Busca el campo por nombre de campo. Devuelve null si no se encuentra el campo. |
| [getAutoRecalculate](#getAutoRecalculate--) | Si está activado, todos los campos del formulario se recalcularán cuando cualquier campo cambie. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Si está activado, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtiene la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño del texto y el color para los campos del formulario). |
| [getDefaultResources](#getDefaultResources--) | Obtiene los recursos predeterminados colocados en este formulario. |
| [getDocument](#getDocument--) | Solo para uso interno |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Si esta propiedad es true entonces se dibujarán rectángulos rojos adicionales para los contenedores de elementos requeridos exclGroup de Xfa. Esta propiedad se introdujo porque existen ausencias de analogías para exclGroup durante la conversión de la representación Xfa de formularios a estándar. Es false por defecto. |
| [getFields](#getFields--) | Obtiene la lista de todos los campos en el nivel más bajo del formulario jerárquico. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Devuelve los campos dentro del rectángulo especificado. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Si esta propiedad es true, el valor de la clave NeedsRendering será ignorado durante la conversión del formulario XFA a formulario estándar. Es false por defecto. |
| [getNeedsRendering](#getNeedsRendering--) | Obtiene un valor que indica si el documento requiere la eliminación del formulario XFA dinámico. Esta propiedad se introdujo para determinar si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debe usarse para eliminar el formulario XFA en casos donde el formulario XFA está presente y {@code NeedsRendering}({@link #getNeedsRendering}) es false. |
| [getRemovePermission](#getRemovePermission--) | Si esta propiedad es true, el diccionario \"Perms\" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario \"Perms\" puede contener reglas que alteren la visualización y selección de campos obligatorios en Adobe Acrobat Reader. Es false por defecto. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Si está configurado, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que modifica su contenido anterior, en lugar de una actualización incremental. |
| [getSignaturesExist](#getSignaturesExist--) | Si está configurado, el documento contiene al menos un campo de firma. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Los formularios pueden contener información de firma, es decir, pueden estar firmados o sin firmar. Y la vista del formulario a veces debe depender de si el formulario está firmado o no. Esta propiedad indica al convertidor del formulario (p. ej., durante la conversión de formulario XFA a formulario Standard) si el formulario resultante debe renderizarse como firmado o como no firmado. |
| [getSyncRoot](#getSyncRoot--) | Devuelve el objeto de sincronización. |
| [getType](#getType--) | Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Obtiene los datos XFA del formulario (si está presente). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Comprueba si el formulario ya tiene el campo especificado. |
| [hasField](#hasField-java.lang.String-) | Determina si el campo con el nombre especificado ya se ha añadido al Formulario. |
| [hasField](#hasField-java.lang.String-boolean-) | Determina si el campo con el nombre especificado ya se ha añadido al Formulario, con la capacidad de explorar la jerarquía de campos hijos. |
| [hasXfa](#hasXfa--) | Obtiene un valor que indica si el documento contiene un formulario XFA. Esta propiedad se introdujo para determinar si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debe usarse para eliminar el formulario XFA en casos donde el formulario XFA está presente y {@code NeedsRendering}({@link #getNeedsRendering}) es false. |
| [isReadOnly](#isReadOnly--) | Determina si la colección es de solo lectura. Siempre devuelve false. |
| [isSynchronized](#isSynchronized--) | Devuelve true si el objeto es seguro para subprocesos. |
| [iterator](#iterator--) | Obtiene la enumeración de los campos del formulario. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Exporta los campos del formulario PDF al formato JSON y escribe el resultado en el flujo proporcionado. / * / * Document document = new Document(\"PdfDoc.pdf\"); / * FileStream fs = new FileStream(\"export.json\", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Elimina el campo del formulario. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Elimina la apariencia del campo en el índice especificado. Si solo queda una apariencia hija, el método la incrusta en el campo. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Si está activado, todos los campos del formulario se recalcularán cuando cualquier campo cambie. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Si está activado, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Permite establecer el orden de cálculo de los campos. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Establece la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño del texto y el color para los campos del formulario). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Si esta propiedad es true entonces se dibujarán rectángulos rojos adicionales para los contenedores de elementos requeridos exclGroup de Xfa. Esta propiedad se introdujo porque existen ausencias de analogías para exclGroup durante la conversión de la representación Xfa de formularios a estándar. Es false por defecto. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Si esta propiedad es true, el valor de la clave NeedsRendering será ignorado durante la conversión del formulario XFA a formulario estándar. Es false por defecto. |
| [setRemovePermission](#setRemovePermission-boolean-) | Si esta propiedad es true, el diccionario \"Perms\" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario \"Perms\" puede contener reglas que alteren la visualización y selección de campos obligatorios en Adobe Acrobat Reader. Es false por defecto. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Si está configurado, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que modifica su contenido anterior, en lugar de una actualización incremental. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Si está configurado, el documento contiene al menos un campo de firma. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Los formularios pueden contener información de firma, es decir, pueden estar firmados o sin firmar. Y la vista del formulario a veces debe depender de si el formulario está firmado o no. Esta propiedad indica al convertidor del formulario (p. ej., durante la conversión de formulario XFA a formulario Standard) si el formulario resultante debe renderizarse como firmado o como no firmado. |
| [setType](#setType-com.aspose.pdf.FormType-) | Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic. |
| [size](#size--) | Obtiene el número de campos en este formulario. |

### Form {#Form-com.aspose.pdf.IDocument-}
Constructor

### add {#add-com.aspose.pdf.Field-}
Añade un campo al formulario.

### add {#add-com.aspose.pdf.Field-int-}
Añade un campo al formulario.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Añade un nuevo campo al formulario; si este campo ya está colocado en otro formulario o en este, se crea una copia del campo.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Añade un campo al formulario.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Añade una apariencia adicional del campo a la página especificada del documento en la ubicación especificada.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Añade una apariencia adicional del campo a la página especificada del documento.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Establece XFA del formulario al valor especificado.

### clear {#clear--}
```
public void clear()
```

Elimina todos los campos del formulario. No soportado.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Determina si el campo está presente en el formulario..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copia los campos colocados en el formulario a una matriz.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Copia los campos del formulario a una matriz.

### delete {#delete-com.aspose.pdf.Field-}
Elimina el campo del formulario.

### delete {#delete-java.lang.String-}
Elimina el campo del formulario por su nombre.

### flatten {#flatten--}
```
public void flatten()
```

Elimina todos los campos de formulario estáticos y coloca sus valores directamente en la página.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Obtiene el campo del formulario por índice de campo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice del campo. |

**Returns:**
Campo recuperado.

### get_Item {#get_Item-java.lang.String-}
Obtiene el campo del formulario por nombre de campo. Lanza una excepción si no se encuentra el campo.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Solo para uso interno

**Returns:**
Objeto XFA

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Busca el campo por nombre de campo. Devuelve null si no se encuentra el campo.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Si está activado, todos los campos del formulario se recalcularán cuando cualquier campo cambie. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados.

**Returns:**
valor booleano

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Si está activado, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones.

**Returns:**
valor booleano

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Obtiene la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño del texto y el color para los campos del formulario).

**Returns:**
objeto DefaultAppearance

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Obtiene los recursos predeterminados colocados en este formulario.

**Returns:**
Valor de Resources

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Solo para uso interno

**Returns:**
Objeto IDocument

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Si esta propiedad es true entonces se dibujarán rectángulos rojos adicionales para los contenedores de elementos requeridos exclGroup de Xfa. Esta propiedad se introdujo porque existen ausencias de analogías para exclGroup durante la conversión de la representación Xfa de formularios a estándar. Es false por defecto.

**Returns:**
valor booleano

### getFields {#getFields--}
```
public Field [] getFields()
```

Obtiene la lista de todos los campos en el nivel más bajo del formulario jerárquico.

**Returns:**
Arreglo con campos encontrados.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Devuelve los campos dentro del rectángulo especificado.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Si esta propiedad es true, el valor de la clave NeedsRendering será ignorado durante la conversión del formulario XFA a formulario estándar. Es false por defecto.

**Returns:**
valor booleano

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Obtiene un valor que indica si el documento requiere la eliminación del formulario XFA dinámico. Esta propiedad se introdujo para determinar si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debe usarse para eliminar el formulario XFA en casos donde el formulario XFA está presente y {@code NeedsRendering}({@link #getNeedsRendering}) es false.

**Returns:**
valor booleano

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Si esta propiedad es true, el diccionario \"Perms\" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario \"Perms\" puede contener reglas que alteren la visualización y selección de campos obligatorios en Adobe Acrobat Reader. Es false por defecto.

**Returns:**
valor booleano

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Si está configurado, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que modifica su contenido anterior, en lugar de una actualización incremental.

**Returns:**
valor booleano

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Si está configurado, el documento contiene al menos un campo de firma.

**Returns:**
valor booleano

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Los formularios pueden contener información de firma, es decir, pueden estar firmados o sin firmar. Y la vista del formulario a veces debe depender de si el formulario está firmado o no. Esta propiedad indica al convertidor del formulario (p. ej., durante la conversión de formulario XFA a formulario Standard) si el formulario resultante debe renderizarse como firmado o como no firmado.

**Returns:**
Elemento SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Devuelve el objeto de sincronización.

**Returns:**
Objeto para sincronización

### getType {#getType--}
```
public FormType getType()
```

Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic.

**Returns:**
Valor FormType @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Obtiene los datos XFA del formulario (si está presente).

**Returns:**
Valor XFA

### hasField {#hasField-com.aspose.pdf.Field-}
Comprueba si el formulario ya tiene el campo especificado.

### hasField {#hasField-java.lang.String-}
Determina si el campo con el nombre especificado ya se ha añadido al Formulario.

### hasField {#hasField-java.lang.String-boolean-}
Determina si el campo con el nombre especificado ya se ha añadido al Formulario, con la capacidad de explorar la jerarquía de campos hijos.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Obtiene un valor que indica si el documento contiene un formulario XFA. Esta propiedad se introdujo para determinar si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) debe usarse para eliminar el formulario XFA en casos donde el formulario XFA está presente y {@code NeedsRendering}({@link #getNeedsRendering}) es false.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determina si la colección es de solo lectura. Siempre devuelve false.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Devuelve true si el objeto es seguro para subprocesos.

**Returns:**
valor booleano

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Obtiene la enumeración de los campos del formulario.

**Returns:**
Enumerador de campos.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Exporta los campos del formulario PDF al formato JSON y escribe el resultado en el flujo proporcionado. / * / * Document document = new Document(\"PdfDoc.pdf\"); / * FileStream fs = new FileStream(\"export.json\", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Elimina el campo del formulario.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Elimina la apariencia del campo en el índice especificado. Si solo queda una apariencia hija, el método la incrusta en el campo.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Si está activado, todos los campos del formulario se recalcularán cuando cualquier campo cambie. El valor predeterminado es true. Establézcalo en false para aumentar el rendimiento al rellenar el formulario con una gran cantidad de campos calculados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Si está activado, los campos de formulario ausentes se crearán automáticamente si están presentes en las anotaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Permite establecer el orden de cálculo de los campos.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Establece la apariencia predeterminada del formulario (objeto que describe la fuente predeterminada, el tamaño del texto y el color para los campos del formulario).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Si esta propiedad es true entonces se dibujarán rectángulos rojos adicionales para los contenedores de elementos requeridos exclGroup de Xfa. Esta propiedad se introdujo porque existen ausencias de analogías para exclGroup durante la conversión de la representación Xfa de formularios a estándar. Es false por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Si esta propiedad es true, el valor de la clave NeedsRendering será ignorado durante la conversión del formulario XFA a formulario estándar. Es false por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Si esta propiedad es true, el diccionario \"Perms\" se eliminará del documento pdf después de convertir documentos dinámicos a estándar. El diccionario \"Perms\" puede contener reglas que alteren la visualización y selección de campos obligatorios en Adobe Acrobat Reader. Es false por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Si está configurado, el documento contiene firmas que pueden invalidarse si el archivo se guarda (escribe) de una manera que modifica su contenido anterior, en lugar de una actualización incremental.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Si está configurado, el documento contiene al menos un campo de firma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Los formularios pueden contener información de firma, es decir, pueden estar firmados o sin firmar. Y la vista del formulario a veces debe depender de si el formulario está firmado o no. Esta propiedad indica al convertidor del formulario (p. ej., durante la conversión de formulario XFA a formulario Standard) si el formulario resultante debe renderizarse como firmado o como no firmado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | Elemento SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Obtiene el tipo del formulario. Los valores posibles son: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Obtiene el número de campos en este formulario.

**Returns:**
valor int
