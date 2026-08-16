---
title: "IForm"
linktitle: "IForm"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un objeto de formulario Acro."
type: docs
weight: 250
url: /es/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Clase que representa un objeto de formulario Acro.

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Cierra los archivos abiertos sin realizar cambios. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporta el contenido de los campos del pdf al flujo fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporta el contenido de los campos del pdf al flujo xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporta el contenido de los campos del pdf al flujo xml. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Rellena un campo de código de barras según su nombre de campo totalmente calificado. |
| [fillField](#fillField-java.lang.String-boolean-) | Rellena el campo de casilla de verificación con un valor booleano. |
| [fillField](#fillField-java.lang.String-int-) | Rellena el campo de opción con un valor de índice válido según un nombre de campo totalmente calificado. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Rellena el campo con un valor válido según un nombre de campo totalmente calificado. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Rellena un campo con selecciones múltiples. Nota: solo para el campo de lista AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Sobrecarga la función FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado. |
| [flattenAllFields](#flattenAllFields--) | Aplana todos los campos. |
| [flattenField](#flattenField-java.lang.String-) | Aplana un campo especificado con el nombre de campo totalmente calificado. |
| [getAttachmentName](#getAttachmentName--) | Obtiene o establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Devuelve el valor actual de los campos de opción de botón de radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. |
| [getContentDisposition](#getContentDisposition--) | Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obtiene el nombre del archivo de destino. |
| [getDestStream](#getDestStream--) | Obtiene el flujo de destino. |
| [getDocument](#getDocument--) | Obtiene el formulario del documento en el que está trabajando. |
| [getField](#getField-java.lang.String-) | Obtiene el valor del campo según su nombre. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Devuelve el objeto FrohmFieldFacade que contiene todos los atributos de apariencia. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Devuelve los indicadores del campo. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Obtiene la limitación del campo de texto. |
| [getFieldNames](#getFieldNames--) | Obtiene la lista de nombres de campos del formulario. |
| [getFieldType](#getFieldType-java.lang.String-) | Devuelve el tipo de campo. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Obtiene todos los nombres de los botones de envío del formulario. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Obtiene el nombre completo del campo según su nombre corto. |
| [getRichText](#getRichText-java.lang.String-) | Obtiene el valor de un campo Rich Text, incluida la información de formato de cada carácter. |
| [getSaveOptions](#getSaveOptions--) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obtiene el nombre del archivo fuente. |
| [getSrcStream](#getSrcStream--) | Obtiene el flujo de origen. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Devuelve los indicadores de envío del botón de envío. |
| [importFdf](#importFdf-java.io.InputStream-) | Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf. |
| [importXml](#importXml-java.io.InputStream-) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renombra un campo. |
| [save](#save--) | Guarda el valor de los campos completados y cierra el documento Pdf abierto. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Establece el nombre del archivo de destino. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obtiene el flujo de destino. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Establece el nombre del archivo de origen. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Obtiene el flujo de origen. |

### close {#close--}
```
void close()
```

Cierra los archivos abiertos sin realizar cambios.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporta el contenido de los campos del pdf al flujo fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporta el contenido de los campos del pdf al flujo xml.

### exportXml {#exportXml-java.io.OutputStream-}
Exporta el contenido de los campos del pdf al flujo xml.

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Rellena un campo de código de barras según su nombre de campo totalmente calificado.

### fillField {#fillField-java.lang.String-boolean-}
Rellena el campo de casilla de verificación con un valor booleano.

### fillField {#fillField-java.lang.String-int-}
Rellena el campo de opción con un valor de índice válido según un nombre de campo totalmente calificado.

### fillField {#fillField-java.lang.String-java.lang.String-}
Rellena el campo con un valor válido según un nombre de campo totalmente calificado.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Rellena un campo con selecciones múltiples. Nota: solo para el campo de lista AcroForm.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Sobrecarga la función FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Aplana todos los campos.

### flattenField {#flattenField-java.lang.String-}
Aplana un campo especificado con el nombre de campo totalmente calificado.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtiene o establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

**Returns:**
objeto string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Devuelve el valor actual de los campos de opción de botón de radio.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo.

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Obtiene el nombre del archivo de destino.

**Returns:**
Objeto String

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

Obtiene el formulario del documento en el que está trabajando.

**Returns:**
Objeto IDocument

### getField {#getField-java.lang.String-}
Obtiene el valor del campo según su nombre.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Devuelve el objeto FrohmFieldFacade que contiene todos los atributos de apariencia.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Devuelve los indicadores del campo.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Obtiene la limitación del campo de texto.

### getFieldNames {#getFieldNames--}
```
String [] getFieldNames()
```

Obtiene la lista de nombres de campos del formulario.

**Returns:**
Objeto String[]

### getFieldType {#getFieldType-java.lang.String-}
Devuelve el tipo de campo.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Obtiene todos los nombres de los botones de envío del formulario.

**Returns:**
Objeto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Obtiene el nombre completo del campo según su nombre corto.

### getRichText {#getRichText-java.lang.String-}
Obtiene el valor de un campo Rich Text, incluida la información de formato de cada carácter.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Obtiene el nombre del archivo fuente.

**Returns:**
Objeto String

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Obtiene el flujo de origen.

**Returns:**
Objeto InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Devuelve los indicadores de envío del botón de envío.

### importFdf {#importFdf-java.io.InputStream-}
Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf.

### importXfdf {#importXfdf-java.io.InputStream-}
Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf.

### importXml {#importXml-java.io.InputStream-}
Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf.

### importXml {#importXml-java.io.InputStream-boolean-}
Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf.

### renameField {#renameField-java.lang.String-java.lang.String-}
Renombra un campo.

### save {#save--}
```
void save()
```

Guarda el valor de los campos completados y cierra el documento Pdf abierto.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Establece el nombre del archivo de destino.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obtiene el flujo de destino.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Establece el nombre del archivo de origen.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Obtiene el flujo de origen.
