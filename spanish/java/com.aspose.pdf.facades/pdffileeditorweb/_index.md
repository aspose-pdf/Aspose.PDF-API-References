---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase PdfFileEditorWeb. Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc."
type: docs
weight: 480
url: /es/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Representa la clase PdfFileEditorWeb. Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | Constructor de PdfFileEditorWeb. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensiona el contenido de la página y agrega márgenes especificados. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Añade documentos al documento fuente y guarda el resultado en el objeto de respuesta. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Añade páginas, que se eligen de una matriz de documentos en portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Añade páginas,que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Añade documentos al documento fuente y guarda el resultado en el objeto HttpServletResponse. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Añade páginas, que se eligen de los documentos portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Añade páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documentos. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Concatena archivos y almacena el resultado en el objeto HttpServletResponse. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatena archivos |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatena dos archivos. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Concatena archivos y guarda el resultado en el objeto HttpResposnse. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatena archivos en un solo archivo. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatena dos archivos. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Elimina páginas especificadas del documento y guarda el resultado en el objeto HttpServletResponse. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Elimina páginas especificadas del documento y almacena el resultado en el objeto HttpServletResponse. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpServletResponse. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpServletResponse. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Obsoleto. Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones. |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Si se establece en true, los flujos se cierran después de la operación. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true. |
| [getContentDisposition](#getContentDisposition--) | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Obtiene el registro del proceso de conversión. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Si es true, la estructura lógica del archivo se copia cuando se realiza la concatenación. |
| [getCopyOutlines](#getCopyOutlines--) | Si es true, los outlines se copiarán. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto. |
| [getCorruptedItems](#getCorruptedItems--) | Matriz de problemas encontrados cuando se realizó la concatenación. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representación del procesador interno de eventos de progreso que funciona durante la concatenación y traduce los eventos de concatenación de las etapas internas de concatenación al código externo del cliente. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Si es true, se realizan actualizaciones incrementales durante la concatenación. |
| [getKeepActions](#getKeepActions--) | Si es true, las acciones se copiarán de los documentos de origen. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen. |
| [getLastException](#getLastException--) | Obtiene la última excepción ocurrida. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Si es true, los outlines duplicados se fusionan. |
| [getOptimizeSize](#getOptimizeSize--) | Obtiene o establece la bandera de optimización. |
| [getOwnerPassword](#getOwnerPassword--) | Obtiene la contraseña del propietario si el archivo PDF de entrada está cifrado. |
| [getPreserveUserRights](#getPreserveUserRights--) | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. |
| [getRemoveSignatures](#getRemoveSignatures--) | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [getSaveOptions](#getSaveOptions--) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtiene el formato del sufijo que se agrega al nombre de campo para hacerlo único cuando los formularios se concatenen. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Inserta el documento en otro documento y almacena el resultado en el objeto response. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Inserta el contenido del archivo en el archivo fuente y almacena el resultado en el objeto HttpServletResponse. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserta páginas de otro archivo en el archivo PDF en una posición. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | A veces los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Crea un folleto desde el InputStream al outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Crea un folleto personalizado desde el firstInputStream al outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Crea un folleto desde el flujo de entrada y guarda el resultado en el flujo de salida. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un folleto desde el firstInputStream al outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un folleto a partir del archivo fuente y almacena el resultado en HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Crea un folleto a partir del archivo PDF y lo almacena en HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Crea un folleto personalizado desde el firstInputFile al outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Crea un folleto desde el inputFile al outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un folleto personalizado desde el firstInputFile al outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Crea un documento N-Up desde los flujos PDF de entrada múltiples al outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Crea un documento N-Up desde los dos flujos PDF de entrada al outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up y almacena el resultado en HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up y almacena el resultado en el objeto HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Crea un documento N-Up desde el flujo de entrada y guarda el resultado en el flujo de salida. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up desde el primer flujo de entrada al flujo de salida. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Crea un documento N-Up desde los archivos PDF de entrada múltiples al outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up y almacena el resultado en HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up y almacena el resultado en el objeto HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Crea un documento N-Up desde el firstInputFile al outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up desde el archivo de entrada al outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Crea un documento N-Up desde los dos archivos PDF de entrada al outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Obsoleto. Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Si se establece en true, los flujos se cierran después de la operación. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Si es true, la estructura lógica del archivo se copia cuando se realiza la concatenación. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Si es true, los outlines se copiarán. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representación del procesador interno de eventos de progreso que funciona durante la concatenación y traduce los eventos de concatenación de las etapas internas de concatenación al código externo del cliente. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Si es true, se realizan actualizaciones incrementales durante la concatenación. |
| [setKeepActions](#setKeepActions-boolean-) | Si es true, las acciones se copiarán de los documentos de origen. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Si es true, los outlines duplicados se fusionan. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtiene o establece la bandera de optimización. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Establece la contraseña del propietario si el archivo Pdf de entrada está cifrado. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | A veces los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Establece el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en el objeto HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divide el documento desde la primera página hasta la ubicación y guarda el resultado en los objetos HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un archivo nuevo. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divide desde la ubicación especificada y guarda la parte posterior en el objeto HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divide desde la ubicación especificada y guarda la parte posterior en el objeto HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Divide desde la ubicación y guarda la parte posterior como un archivo nuevo. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide el archivo PDF en documentos de una sola página. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. |
| [splitToPages](#splitToPages-java.lang.String-) | Divide el archivo PDF en documentos de una sola página. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

Constructor de PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensiona el contenido de la página y agrega márgenes especificados.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Añade documentos al documento fuente y guarda el resultado en el objeto de respuesta.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Añade páginas, que se eligen de una matriz de documentos en portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Añade páginas,que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Añade documentos al documento fuente y guarda el resultado en el objeto HttpServletResponse.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Añade páginas, que se eligen de los documentos portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Añade páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documentos.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Concatena archivos y almacena el resultado en el objeto HttpServletResponse.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatena archivos

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatena dos archivos.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Concatena archivos y guarda el resultado en el objeto HttpResposnse.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatena archivos en un solo archivo.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatena dos archivos.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Elimina páginas especificadas del documento y guarda el resultado en el objeto HttpServletResponse.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Elimina páginas especificadas del documento y almacena el resultado en el objeto HttpServletResponse.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Elimina páginas especificadas por una matriz de números del archivo de entrada, y lo guarda como un nuevo archivo Pdf.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpServletResponse.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpServletResponse.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrae páginas del archivo de entrada, guarda como un nuevo archivo Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Obsoleto. Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones.

**Returns:**
Valor booleano

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto.

**Returns:**
valor de cadena

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Si se establece en true, los flujos se cierran después de la operación.

**Returns:**
valor booleano

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true.

**Returns:**
valor int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse.

**Returns:**
Elemento ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Obtiene el registro del proceso de conversión.

**Returns:**
valor de cadena

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Si es true, la estructura lógica del archivo se copia cuando se realiza la concatenación.

**Returns:**
valor booleano

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Si es true, los outlines se copiarán.

**Returns:**
valor booleano

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto.

**Returns:**
Elemento ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Matriz de problemas encontrados cuando se realizó la concatenación.

**Returns:**
PdfFileEditor.CorruptedItem matriz

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Representación del procesador interno de eventos de progreso que funciona durante la concatenación y traduce los eventos de concatenación de las etapas internas de concatenación al código externo del cliente.

**Returns:**
instancia de ConcatenationProgressHandler

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Si es true, se realizan actualizaciones incrementales durante la concatenación.

**Returns:**
valor booleano

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Si es true, las acciones se copiarán de los documentos de origen.

**Returns:**
valor booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen.

**Returns:**
valor booleano

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Obtiene la última excepción ocurrida.

**Returns:**
objeto java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true.

**Returns:**
valor booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Si es true, los outlines duplicados se fusionan.

**Returns:**
valor booleano

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtiene o establece la bandera de optimización.

**Returns:**
valor booleano

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Obtiene la contraseña del propietario si el archivo PDF de entrada está cifrado.

**Returns:**
Objeto String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado.

**Returns:**
valor booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse.

**Returns:**
Objeto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Obtiene el formato del sufijo que se agrega al nombre de campo para hacerlo único cuando los formularios se concatenen.

**Returns:**
Objeto String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Inserta el documento en otro documento y almacena el resultado en el objeto response.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Inserta páginas de otro archivo en el archivo PDF de entrada.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Inserta páginas de otro archivo en el archivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Inserta el contenido del archivo en el archivo fuente y almacena el resultado en el objeto HttpServletResponse.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Inserta páginas de otro archivo en el archivo PDF de entrada.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Inserta páginas de otro archivo en el archivo PDF en una posición.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

A veces los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra.

**Returns:**
valor booleano

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales.

**Returns:**
valor booleano

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Crea un folleto desde el InputStream al outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Crea un folleto personalizado desde el firstInputStream al outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Crea un folleto desde el flujo de entrada y guarda el resultado en el flujo de salida.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Crea un folleto desde el firstInputStream al outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un folleto a partir del archivo fuente y almacena el resultado en HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Crea un folleto a partir del archivo PDF y lo almacena en HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Crea un folleto a partir del archivo fuente y almacena el resultado en los objetos HttpServletResponse.

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

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up y almacena el resultado en HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up y almacena el resultado en el objeto HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Crea un documento N-Up desde el flujo de entrada y guarda el resultado en el flujo de salida.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up desde el primer flujo de entrada al flujo de salida.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Crea un documento N-Up desde los archivos PDF de entrada múltiples al outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up y almacena el resultado en HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up y almacena el resultado en el objeto HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Crea un documento N-Up desde el firstInputFile al outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up desde el archivo de entrada al outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Crea un documento N-Up desde los dos archivos PDF de entrada al outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona el contenido de las páginas del documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Redimensiona el contenido de las páginas del documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Obsoleto. Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor booleano |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Si se establece en true, los flujos se cierran después de la operación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Si es true, la estructura lógica del archivo se copia cuando se realiza la concatenación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Si es true, los outlines se copiarán.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Esta propiedad define el comportamiento cuando el proceso de concatenación encontró un archivo corrupto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Representación del procesador interno de eventos de progreso que funciona durante la concatenación y traduce los eventos de concatenación de las etapas internas de concatenación al código externo del cliente.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Si es true, se realizan actualizaciones incrementales durante la concatenación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Si es true, las acciones se copiarán de los documentos de origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Si es verdadero, los nombres de campo se harán únicos cuando los formularios se concatenen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Si es true, los outlines duplicados se fusionan.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtiene o establece la bandera de optimización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Establece la contraseña del propietario si el archivo Pdf de entrada está cifrado.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

A veces los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valor booleano |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Establece el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en el objeto HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divide el documento desde la primera página hasta la ubicación y guarda el resultado en los objetos HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Divide el archivo Pdf desde la primera página hasta la ubicación especificada y guarda la parte frontal como un archivo nuevo.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divide desde la ubicación especificada y guarda la parte posterior en el objeto HttpServletResponse.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divide desde la ubicación especificada y guarda la parte posterior en el objeto HttpServletResponse.

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
