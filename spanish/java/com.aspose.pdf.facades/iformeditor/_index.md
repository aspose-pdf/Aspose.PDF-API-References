---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para editar formularios (agregar/eliminar campos, etc.)"
type: docs
weight: 260
url: /es/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Clase para editar formularios (agregar/eliminar campos, etc.)

## Métodos

| Método | Descripción |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Agregar campo del tipo especificado al formulario. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Agregar campo del tipo especificado al formulario. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Agrega un nuevo elemento al cuadro de lista. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Agrega un nuevo elemento con valor Export al campo de cuadro de lista existente, solo para el campo de cuadro combinado AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Agrega un botón de envío al formulario. |
| [close](#close--) | Cierra el objeto |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copia un campo existente a la misma posición en el número de página especificado. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copia un campo existente a una nueva posición especificada por el número de página y las coordenadas. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas originales. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las coordenadas originales. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas especificados. |
| [decorateField](#decorateField--) | Cambia los atributos visuales de todos los campos en el documento PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Cambia los atributos visuales de todos los campos con el tipo de campo especificado. |
| [decorateField](#decorateField-java.lang.String-) | Cambia los atributos visuales del campo especificado. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Elimina el elemento del campo de lista. |
| [dispose](#dispose--) | Cierra el objeto |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [getContentDisposition](#getContentDisposition--) | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obtiene el nombre del archivo de destino. |
| [getDestStream](#getDestStream--) | Obtiene el flujo de destino. |
| [getDocument](#getDocument--) | Obtiene el documento en el que trabaja FormEditor. |
| [getExportItems](#getExportItems--) | Obtiene opciones para el cuadro combinado con valores de exportación. |
| [getFacade](#getFacade--) | Obtiene los atributos visuales del campo. |
| [getItems](#getItems--) | Devuelve la matriz de elementos |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtiene o establece el tamaño del elemento de botón de opción (cuando se agrega un nuevo campo de botón de opción). |
| [getRadioGap](#getRadioGap--) | Obtiene el miembro que registra la separación entre dos botones de opción vecinos en píxeles, el valor predeterminado es 50. |
| [getRadioHoriz](#getRadioHoriz--) | Obtenga la bandera que indica si los botones de opción se organizan horizontalmente o verticalmente, el valor predeterminado es verdadero. |
| [getSaveOptions](#getSaveOptions--) | Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obtiene el nombre del archivo de origen. |
| [getSrcStream](#getSrcStream--) | Obtiene el flujo de origen. |
| [getSubmitFlag](#getSubmitFlag--) | Obtiene los indicadores de envío del botón de envío |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Establece la nueva posición del campo. |
| [removeField](#removeField-java.lang.String-) | Elimina el campo del formulario. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Elimina la acción de envío del campo. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Cambia el nombre del campo. |
| [resetFacade](#resetFacade--) | Restablece todos los atributos visuales a un valor vacío. |
| [resetInnerFacade](#resetInnerFacade--) | Restablece todos los atributos visuales de la fachada interna a un valor vacío. |
| [save](#save--) | Guarda los cambios en el archivo de destino. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Establece el nombre del archivo de destino. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Establece el flujo de destino. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Establece opciones para el cuadro combinado con valores de exportación. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Establece los atributos visuales del campo. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Establece el estilo de alineación de un campo de texto. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Establece el estilo de alineación vertical de un campo de texto. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Establece las banderas del campo |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Establece los atributos del campo. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Establece el número de divisiones (combs) para un campo de texto de una sola línea regular (el campo se divide automáticamente en tantas posiciones equidistantes, o combs, como el valor del parámetro combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Establece el recuento máximo de caracteres del campo de texto. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Establece JavaScript para un campo PushButton. |
| [setItems](#setItems-java.lang.String:A-) | Establece los elementos que se agregarán al cuadro de lista o cuadro combinado recién creado. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Obtiene o establece el tamaño del elemento de botón de opción (cuando se agrega un nuevo campo de botón de opción). |
| [setRadioGap](#setRadioGap-float-) | Establece el miembro para registrar el espacio entre dos botones de opción vecinos en píxeles, el valor predeterminado es 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Establece la bandera que indica si los botones de opción se organizan horizontalmente o verticalmente, el valor predeterminado es verdadero. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Establece el nombre del archivo fuente. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Establece el flujo de origen. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Establece la bandera de envío del botón de envío. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Establezca las banderas de envío del botón de envío |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Establece la URL del botón. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Cambia un campo de texto de una sola línea a uno de varias líneas. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Agregar campo del tipo especificado al formulario.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Agregar campo del tipo especificado al formulario.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Agrega un nuevo elemento al cuadro de lista.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Agrega un nuevo elemento con valor Export al campo de cuadro de lista existente, solo para el campo de cuadro combinado AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Agrega un botón de envío al formulario.

### close {#close--}
```
void close()
```

Cierra el objeto

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copia un campo existente a la misma posición en el número de página especificado.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copia un campo existente a una nueva posición especificada por el número de página y las coordenadas.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas originales.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las coordenadas originales.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copia un campo existente de un documento PDF a otro documento con el número de página y coordenadas especificados.

### decorateField {#decorateField--}
```
void decorateField()
```

Cambia los atributos visuales de todos los campos en el documento PDF.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Cambia los atributos visuales de todos los campos con el tipo de campo especificado.

### decorateField {#decorateField-java.lang.String-}
Cambia los atributos visuales del campo especificado.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Elimina el elemento del campo de lista.

### dispose {#dispose--}
```
void dispose()
```

Cierra el objeto

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

**Returns:**
Objeto String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Obtiene el nombre del archivo de destino.

**Returns:**
valor de cadena

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Obtiene el flujo de destino.

**Returns:**
Objeto OutputStream

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Obtiene el documento en el que trabaja FormEditor.

**Returns:**
Objeto IDocument

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Obtiene opciones para el cuadro combinado con valores de exportación.

**Returns:**
Objeto String[][]

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Obtiene los atributos visuales del campo.

**Returns:**
Objeto FormFieldFacade

### getItems {#getItems--}
```
String [] getItems()
```

Devuelve la matriz de elementos

**Returns:**
Objeto String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Obtiene o establece el tamaño del elemento de botón de opción (cuando se agrega un nuevo campo de botón de opción).

**Returns:**
valor booleano

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

Obtiene el miembro que registra la separación entre dos botones de opción vecinos en píxeles, el valor predeterminado es 50.

**Returns:**
valor flotante

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Obtenga la bandera que indica si los botones de opción se organizan horizontalmente o verticalmente, el valor predeterminado es verdadero.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Obtiene el nombre del archivo de origen.

**Returns:**
valor de cadena

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Obtiene el flujo de origen.

**Returns:**
Objeto InputStream

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
```

Obtiene los indicadores de envío del botón de envío

**Returns:**
Elemento SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
Establece la nueva posición del campo.

### removeField {#removeField-java.lang.String-}
Elimina el campo del formulario.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Elimina la acción de envío del campo.

### renameField {#renameField-java.lang.String-java.lang.String-}
Cambia el nombre del campo.

### resetFacade {#resetFacade--}
```
void resetFacade()
```

Restablece todos los atributos visuales a un valor vacío.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

Restablece todos los atributos visuales de la fachada interna a un valor vacío.

### save {#save--}
```
void save()
```

Guarda los cambios en el archivo de destino.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Establece el nombre del archivo de destino.

### setDestStream {#setDestStream-java.io.OutputStream-}
Establece el flujo de destino.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Establece opciones para el cuadro combinado con valores de exportación.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Establece los atributos visuales del campo.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Establece el estilo de alineación de un campo de texto.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Establece el estilo de alineación vertical de un campo de texto.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Establece las banderas del campo

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Establece los atributos del campo.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Establece el número de divisiones (combs) para un campo de texto de una sola línea regular (el campo se divide automáticamente en tantas posiciones equidistantes, o combs, como el valor del parámetro combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Establece el recuento máximo de caracteres del campo de texto.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Establece JavaScript para un campo PushButton.

### setItems {#setItems-java.lang.String:A-}
Establece los elementos que se agregarán al cuadro de lista o cuadro combinado recién creado.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
void setRadioButtonItemSize(double value)
```

Obtiene o establece el tamaño del elemento de botón de opción (cuando se agrega un nuevo campo de botón de opción).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

Establece el miembro para registrar el espacio entre dos botones de opción vecinos en píxeles, el valor predeterminado es 50.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Establece la bandera que indica si los botones de opción se organizan horizontalmente o verticalmente, el valor predeterminado es verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Establece las opciones de guardado cuando el resultado se almacena como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Establece el nombre del archivo fuente.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Establece el flujo de origen.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Establece la bandera de envío del botón de envío.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Establezca las banderas de envío del botón de envío

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Establece la URL del botón.

### single2Multiple {#single2Multiple-java.lang.String-}
Cambia un campo de texto de una sola línea a uno de varias líneas.
