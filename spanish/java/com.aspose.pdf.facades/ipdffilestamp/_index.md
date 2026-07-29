---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Interfaz para agregar sellos (marca de agua o fondo) a archivos PDF."
type: docs
weight: 320
url: /es/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

Interfaz para agregar sellos (marca de agua o fondo) a archivos PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posición inferior izquierda. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posición inferior central. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posición inferior derecha. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posición izquierda. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posición derecha. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posición superior izquierda. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posición media superior. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posición superior derecha. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Agrega pie de página a las páginas del documento. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Agrega pie de página a las páginas del documento. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Agrega imagen como pie de página de la página. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Agrega imagen como pie de página de la página. |
| [addFooter](#addFooter-java.lang.String-float-) | Agrega imagen como pie de página a las páginas del documento. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Agrega imagen como pie de página de las páginas. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Agrega encabezado a la página. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Agrega encabezado a las páginas del archivo. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Agrega imagen como encabezado en las páginas. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Agrega imagen en la parte superior de la página. |
| [addHeader](#addHeader-java.lang.String-float-) | Agrega imagen como encabezado a las páginas del archivo. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Agrega imagen como encabezado en las páginas. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Agrega número de página a la página. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Agrega número de página en la posición especificada de la página. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Agrega número de página a las páginas. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Agrega número de página a las páginas del documento. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Agregar número de página al archivo. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Agrega número de página en la posición especificada de la página. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Agrega número de página a las páginas. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Agrega número de página a las páginas del documento. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Agrega sello al archivo. |
| [close](#close--) | Cierra los archivos abiertos y guarda los cambios. |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [getContentDisposition](#getContentDisposition--) | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. |
| [getDocument](#getDocument--) | Obtiene el documento en el que trabaja PdfFileStamp. |
| [getInputFile](#getInputFile--) | Obtiene el nombre y la ruta del archivo de entrada. |
| [getInputStream](#getInputStream--) | Obtiene la secuencia de entrada. |
| [getKeepSecurity](#getKeepSecurity--) | Mantiene la seguridad si es verdadero. |
| [getOutputFile](#getOutputFile--) | Obtiene el nombre y la ruta del archivo de salida. |
| [getOutputStream](#getOutputStream--) | Obtiene la secuencia de salida. |
| [getPageHeight](#getPageHeight--) | Obtiene la altura de la primera página en el archivo fuente. |
| [getPageNumberRotation](#getPageNumberRotation--) | Obtiene la rotación del número de página. |
| [getPageWidth](#getPageWidth--) | Obtiene el ancho de la primera página en el archivo de entrada. |
| [getSaveOptions](#getSaveOptions--) | Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Obtiene o establece el número inicial para la primera página en el archivo de entrada. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Establece el nombre y la ruta del archivo de entrada. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Establece la secuencia de entrada. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Establecer Mantener Seguridad |
| [setOutputFile](#setOutputFile-java.lang.String-) | Establece el nombre y la ruta del archivo de salida. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Establece o establece la secuencia de salida. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Establece la rotación del número de página. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Establece el número inicial para la primera página en el archivo de entrada. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Posición inferior izquierda.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Posición inferior central.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Posición inferior derecha.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Posición izquierda.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Posición derecha.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Posición superior izquierda.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Posición media superior.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Posición superior derecha.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Agrega pie de página a las páginas del documento.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Agrega pie de página a las páginas del documento.

### addFooter {#addFooter-java.io.InputStream-float-}
Agrega imagen como pie de página de la página.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Agrega imagen como pie de página de la página.

### addFooter {#addFooter-java.lang.String-float-}
Agrega imagen como pie de página a las páginas del documento.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Agrega imagen como pie de página de las páginas.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Agrega encabezado a la página.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Agrega encabezado a las páginas del archivo.

### addHeader {#addHeader-java.io.InputStream-float-}
Agrega imagen como encabezado en las páginas.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Agrega imagen en la parte superior de la página.

### addHeader {#addHeader-java.lang.String-float-}
Agrega imagen como encabezado a las páginas del archivo.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Agrega imagen como encabezado en las páginas.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Agrega número de página a la página.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Agrega número de página en la posición especificada de la página.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Agrega número de página a las páginas.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Agrega número de página a las páginas del documento.

### addPageNumber {#addPageNumber-java.lang.String-}
Agregar número de página al archivo.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Agrega número de página en la posición especificada de la página.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Agrega número de página a las páginas.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Agrega número de página a las páginas del documento.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Agrega sello al archivo.

### close {#close--}
```
void close()
```

Cierra los archivos abiertos y guarda los cambios.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

**Returns:**
valor String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Obtiene el documento en el que trabaja PdfFileStamp.

**Returns:**
Objeto IDocument

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Obtiene el nombre y la ruta del archivo de entrada.

**Returns:**
Objeto String

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Obtiene la secuencia de entrada.

**Returns:**
Objeto InputStream

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Mantiene la seguridad si es verdadero.

**Returns:**
valor booleano

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Obtiene el nombre y la ruta del archivo de salida.

**Returns:**
Objeto String

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Obtiene la secuencia de salida.

**Returns:**
Objeto OutputStream

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Obtiene la altura de la primera página en el archivo fuente.

**Returns:**
valor flotante

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Obtiene la rotación del número de página.

**Returns:**
valor flotante

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Obtiene el ancho de la primera página en el archivo de entrada.

**Returns:**
valor flotante

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse.

**Returns:**
Objeto SaveOptions

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Obtiene o establece el número inicial para la primera página en el archivo de entrada.

**Returns:**
valor int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF.

### setInputFile {#setInputFile-java.lang.String-}
Establece el nombre y la ruta del archivo de entrada.

### setInputStream {#setInputStream-java.io.InputStream-}
Establece la secuencia de entrada.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Establecer Mantener Seguridad

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputFile {#setOutputFile-java.lang.String-}
Establece el nombre y la ruta del archivo de salida.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Establece o establece la secuencia de salida.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Establece la rotación del número de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Establece las opciones de guardado cuando el resultado se almacena como HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Establece el número inicial para la primera página en el archivo de entrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
