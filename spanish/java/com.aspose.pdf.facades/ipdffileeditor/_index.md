---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc."
type: docs
weight: 290
url: /es/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc.

## Métodos

| Método | Descripción |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Añade páginas, que se eligen de una matriz de documentos en portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Añade páginas,que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Añade páginas, que se eligen de los documentos portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Añade páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documentos. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatena archivos |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatena dos archivos. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatena archivos en un solo archivo. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatena dos archivos. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | es Allow Concatenate Exceptions |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Si se establece en true, los flujos se cierran después de la operación. |
| [getContentDisposition](#getContentDisposition--) | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Obtiene el registro del proceso de conversión. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Si es true, se realizan actualizaciones incrementales durante la concatenación. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen. |
| [getLastException](#getLastException--) | Obtiene la última excepción ocurrida. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Si es true, los outlines duplicados se fusionan. |
| [getOwnerPassword](#getOwnerPassword--) | Obtiene la contraseña del propietario si el archivo PDF de entrada está cifrado. |
| [getPreserveUserRights](#getPreserveUserRights--) | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. |
| [getRemoveSignatures](#getRemoveSignatures--) | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [getSaveOptions](#getSaveOptions--) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtiene el formato del sufijo que se agrega al nombre de campo para hacerlo único cuando los formularios se concatenen. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserta páginas de otro archivo en el archivo PDF en una posición. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Crea un folleto desde el InputStream al outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Crea un folleto personalizado desde el firstInputStream al outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Crea un folleto desde el flujo de entrada y guarda el resultado en el flujo de salida. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un folleto desde el firstInputStream al outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Crea un folleto personalizado desde el firstInputFile al outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Crea un folleto desde el inputFile al outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un folleto personalizado desde el firstInputFile al outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Crea un documento N-Up desde los flujos PDF de entrada múltiples al outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Crea un documento N-Up desde los dos flujos PDF de entrada al outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Crea un documento N-Up desde el flujo de entrada y guarda el resultado en el flujo de salida. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up desde el primer flujo de entrada al flujo de salida. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Crea un documento N-Up desde los archivos PDF de entrada múltiples al outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Crea un documento N-Up desde el firstInputFile al outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up desde el archivo de entrada al outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Crea un documento N-Up desde los dos archivos PDF de entrada al outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Si se establece en true, se lanzan excepciones si ocurre un error. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Si se establece en true, los flujos se cierran después de la operación. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Si es true, se realizan actualizaciones incrementales durante la concatenación. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Si es true, los outlines duplicados se fusionan. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Establece la contraseña del propietario si el archivo Pdf de entrada está cifrado. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Establece el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un archivo nuevo. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Divide desde la ubicación y guarda la parte posterior como un archivo nuevo. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide el archivo PDF en documentos de una sola página. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. |
| [splitToPages](#splitToPages-java.lang.String-) | Divide el archivo PDF en documentos de una sola página. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Añade páginas, que se eligen de una matriz de documentos en portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Añade páginas,que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Añade páginas, que se eligen de los documentos portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Añade páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documentos.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatena archivos

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatena dos archivos.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatena archivos en un solo archivo.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatena dos archivos.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

es Allow Concatenate Exceptions

**Returns:**
valor booleano

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto.

**Returns:**
valor de cadena

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Si se establece en true, los flujos se cierran después de la operación.

**Returns:**
valor booleano

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse.

**Returns:**
Elemento ContentDisposition

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Obtiene el registro del proceso de conversión.

**Returns:**
valor de cadena

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto.

**Returns:**
Elemento ConcatenateCorruptedFileAction

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Si es true, se realizan actualizaciones incrementales durante la concatenación.

**Returns:**
valor booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen.

**Returns:**
valor booleano

### getLastException {#getLastException--}
```
Exception getLastException()
```

Obtiene la última excepción ocurrida.

**Returns:**
objeto java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true.

**Returns:**
valor booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Si es true, los outlines duplicados se fusionan.

**Returns:**
valor booleano

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Obtiene la contraseña del propietario si el archivo PDF de entrada está cifrado.

**Returns:**
valor de cadena

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado.

**Returns:**
valor booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse.

**Returns:**
Objeto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Obtiene el formato del sufijo que se agrega al nombre de campo para hacerlo único cuando los formularios se concatenen.

**Returns:**
valor de cadena

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Inserta páginas de otro archivo en el archivo PDF de entrada.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Inserta páginas de otro archivo en el archivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Inserta páginas de otro archivo en el archivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Inserta páginas de otro archivo en el archivo PDF en una posición.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Crea un folleto desde el InputStream al outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Crea un folleto personalizado desde el firstInputStream al outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Crea un folleto desde el flujo de entrada y guarda el resultado en el flujo de salida.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Crea un folleto desde el firstInputStream al outputStream.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Crea un folleto desde el archivo de entrada al archivo de salida.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Crea un folleto personalizado desde el firstInputFile al outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Crea un folleto desde el inputFile al outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Crea un folleto personalizado desde el firstInputFile al outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Crea un documento N-Up desde los flujos PDF de entrada múltiples al outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Crea un documento N-Up desde los dos flujos PDF de entrada al outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Crea un documento N-Up desde el flujo de entrada y guarda el resultado en el flujo de salida.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up desde el primer flujo de entrada al flujo de salida.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Crea un documento N-Up desde los archivos PDF de entrada múltiples al outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Crea un documento N-Up desde el firstInputFile al outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up desde el archivo de entrada al outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Crea un documento N-Up desde los dos archivos PDF de entrada al outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Si se establece en true, se lanzan excepciones si ocurre un error.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Si se establece en true, los flujos se cierran después de la operación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ConcatenateCorruptedFileAction |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Si es true, se realizan actualizaciones incrementales durante la concatenación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Si es true, los outlines duplicados se fusionan.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Establece la contraseña del propietario si el archivo Pdf de entrada está cifrado.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Establece el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un archivo nuevo.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Divide desde la ubicación y guarda la parte posterior como un archivo nuevo.

### splitToPages {#splitToPages-java.io.InputStream-}
Divide el archivo PDF en documentos de una sola página.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada.

### splitToPages {#splitToPages-java.lang.String-}
Divide el archivo PDF en documentos de una sola página.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada.
