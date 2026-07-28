---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representando la interfaz de formulario Acro."
type: docs
weight: 230
url: /es/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Representando la interfaz de formulario Acro.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa la fachada. |
| [close](#close--) | Cierra todos los recursos abiertos utilizados por este documento. |
| [dispose](#dispose--) | Obsoleto. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporta el contenido de los campos del pdf al flujo fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporta el contenido de los campos del pdf al flujo xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporta el contenido de los campos del pdf al flujo xml. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrae el paquete de datos XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Rellena un campo de código de barras según su nombre de campo totalmente calificado. |
| [fillField](#fillField-java.lang.String-boolean-) | Rellena el campo de casilla de verificación con un valor booleano. |
| [fillField](#fillField-java.lang.String-int-) | Rellena el campo de opción con un valor de índice válido según un nombre de campo totalmente calificado. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Rellena el campo con un valor válido según un nombre de campo totalmente calificado. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Rellena un campo con selecciones múltiples. Nota: solo para el campo de lista AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Rellena el campo con el valor especificado. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Rellena los campos de cuadro de texto con valores de texto y guarda el documento. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Sobrecarga la función FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado. |
| [flattenAllFields](#flattenAllFields--) | Aplana todos los campos. |
| [flattenField](#flattenField-java.lang.String-) | Aplana un campo especificado con el nombre de campo totalmente calificado. |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Devuelve el valor actual de los campos de opción de botón de radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Obtiene los campos de opción de botón de radio y los valores relacionados según el nombre del campo. |
| [getContentDisposition](#getContentDisposition--) | El contenido de Getshow se almacenará cuando el resultado de la operación se guarde en el objeto HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsoleto. |
| [getDestStream](#getDestStream--) | Obsoleto. |
| [getField](#getField-java.lang.String-) | Obtiene el valor del campo según su nombre. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Devuelve el objeto FrohmFieldFacade que contiene todos los atributos de apariencia. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Devuelve los indicadores del campo. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Obtiene la limitación del campo de texto. |
| [getFieldNames](#getFieldNames--) | Obtiene la lista de nombres de campos del formulario. |
| [getFieldType](#getFieldType-java.lang.String-) | Devuelve el tipo de campo. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Obtiene todos los nombres de los botones de envío del formulario. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Obtiene el nombre completo del campo según su nombre corto. |
| [getImportResult](#getImportResult--) | Resultado de la última operación de importación. |
| [getResponse](#getResponse--) | Obtiene o establece el objeto Response donde se almacenará el resultado de la operación. |
| [getRichText](#getRichText-java.lang.String-) | Obtiene el valor de un campo Rich Text, incluida la información de formato de cada carácter. |
| [getSaveOptions](#getSaveOptions--) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsoleto. |
| [getSrcStream](#getSrcStream--) | Obtiene el flujo de origen. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Devuelve los indicadores de envío del botón de envío. |
| [importFdf](#importFdf-java.io.InputStream-) | Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf. |
| [importXml](#importXml-java.io.InputStream-) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [importXml](#importXml-java.lang.String-) | Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determina si el campo es obligatorio o no. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renombra un campo. |
| [save](#save--) | <p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsoleto. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obsoleto. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Obtiene o establece el objeto Response donde se almacenará el resultado de la operación. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsoleto. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Obtiene el flujo de origen. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Reemplaza los datos XFA con el paquete de datos especificado. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Constructor de FormWeb sin parámetros. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa la fachada.

### close {#close--}
```
public void close()
```

Cierra todos los recursos abiertos utilizados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporta el contenido de los campos del pdf al flujo fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporta el contenido de los campos del pdf al flujo xml.

### exportXml {#exportXml-java.io.OutputStream-}
Exporta el contenido de los campos del pdf al flujo xml.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrae el paquete de datos XFA

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
Rellena el campo con el valor especificado.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Rellena los campos de cuadro de texto con valores de texto y guarda el documento.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Sobrecarga la función FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Pega una imagen en el campo de botón existente como su apariencia según su nombre de campo totalmente calificado.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Aplana todos los campos.

### flattenField {#flattenField-java.lang.String-}
Aplana un campo especificado con el nombre de campo totalmente calificado.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

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
public ContentDisposition getContentDisposition()
```

El contenido de Getshow se almacenará cuando el resultado de la operación se guarde en el objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsoleto.

**Returns:**
Objeto String

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obsoleto.

**Returns:**
Objeto OutputStream

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
public String [] getFieldNames()
```

Obtiene la lista de nombres de campos del formulario.

**Returns:**
Objeto String[]

### getFieldType {#getFieldType-java.lang.String-}
Devuelve el tipo de campo.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Obtiene todos los nombres de los botones de envío del formulario.

**Returns:**
Objeto String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Obtiene el nombre completo del campo según su nombre corto.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Resultado de la última operación de importación.

**Returns:**
Matriz FormImportResult[]

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Obtiene o establece el objeto Response donde se almacenará el resultado de la operación.

**Returns:**
Objeto HttpServletResponse

### getRichText {#getRichText-java.lang.String-}
Obtiene el valor de un campo Rich Text, incluida la información de formato de cada carácter.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse.

**Returns:**
Objeto SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsoleto.

**Returns:**
Objeto String

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
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

### importXml {#importXml-java.lang.String-}
Importa el contenido de los campos del archivo xml y los coloca en el nuevo pdf.

### isRequiredField {#isRequiredField-java.lang.String-}
Determina si el campo es obligatorio o no.

### renameField {#renameField-java.lang.String-java.lang.String-}
Renombra un campo.

### save {#save--}
```
public void save()
```

<p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Guarda el valor de los campos rellenados y cierra el documento PDF abierto. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsoleto.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obsoleto.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Obtiene o establece el objeto Response donde se almacenará el resultado de la operación.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsoleto.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Obtiene el flujo de origen.

### setXfaData {#setXfaData-java.io.InputStream-}
Reemplaza los datos XFA con el paquete de datos especificado.
