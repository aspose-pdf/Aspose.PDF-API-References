---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc."
type: docs
weight: 410
url: /es/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | Constructor de PdfFileEditor. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Agrega saltos de página en las páginas del documento. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Agrega páginas, que se eligen de una matriz de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Agrega páginas, que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Agrega páginas, que se eligen de los documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Agrega páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documentos. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Concatena archivos </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Concatena dos archivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Concatena archivos en un solo archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Concatena dos archivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Elimina páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Elimina páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Extrae páginas especificadas por una matriz de números, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Extrae páginas del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Extrae páginas especificadas por una matriz de números, y guarda como un nuevo archivo PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract(\"input.pdf\", new int[] { 3, 5, 7 }, \"output.pdf\"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Extrae páginas del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract(\"input.pdf\", 3, 7, \"output.pdf\"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Si se establece en true, se lanzan excepciones si ocurre un error. De lo contrario, no se lanzan excepciones y los métodos devuelven false si fallan. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Si se establece en true, los flujos se cierran después de la operación. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true. |
| [getContentDisposition](#getContentDisposition--) | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpServletResponse. Valores posibles: inline / attachment. Predeterminado: inline. |
| [getConversionLog](#getConversionLog--) | Obtiene el registro del proceso de conversión. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Si es true, la estructura lógica del archivo se copia cuando se realiza la concatenación. |
| [getCopyOutlines](#getCopyOutlines--) | Si es true, los outlines se copiarán. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo corrupto. Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Matriz de problemas encontrados cuando se realizó la concatenación. Para cada documento corrupto pasado a la función Concatenate() se crea una nueva entrada CorruptedItem. Esta propiedad solo puede usarse cuando CorruptedFileAction es ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PPdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ \" reason: \" + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representación del procesador interno de eventos de progreso que funciona durante la concatenación y traduce los eventos de concatenación de las etapas internas de concatenación al código externo del cliente. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Si es true, se realizan actualizaciones incrementales durante la concatenación. |
| [getKeepActions](#getKeepActions--) | Si es true, las acciones se copiarán de los documentos de origen. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Si es true, los nombres de los campos se harán únicos cuando los formularios se concatenen. Se agregarán sufijos a los nombres de los campos; la plantilla de sufijo puede especificarse en la propiedad UniqueSuffix. |
| [getLastException](#getLastException--) | Obtiene la última excepción ocurrida. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Si es true, los outlines duplicados se fusionan. |
| [getOptimizeSize](#getOptimizeSize--) | Obtiene o establece la bandera de optimización. |
| [getOwnerPassword](#getOwnerPassword--) | Obtiene la contraseña del propietario si el archivo Pdf de entrada está cifrado. Esta propiedad aún no está implementada. |
| [getPreserveUserRights](#getPreserveUserRights--) | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. |
| [getRemoveSignatures](#getRemoveSignatures--) | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [getSaveOptions](#getSaveOptions--) | Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. Valor predeterminado: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtenga el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan. Esta cadena debe contener la subcadena %NUM% que será reemplazada por números. Por ejemplo, si UniqueSuffix = "ABC%NUM%" entonces para el campo "fieldName" los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Inserta páginas de otro archivo en el archivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Inserta páginas de otro archivo en el archivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Inserta páginas de otro archivo en el archivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Inserta páginas de otro archivo en el archivo Pdf en una posición. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | A veces los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Crea un folleto a partir del InputStream hacia outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Crea un folleto personalizado a partir del firstInputStream hacia outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Crea un folleto a partir del firstInputStream hacia outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Crea un folleto a partir del archivo de entrada hacia el archivo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Crea un folleto personalizado a partir del firstInputFile hacia outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Crea un folleto a partir del inputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Crea un folleto personalizado a partir del firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Crea un documento N-Up a partir de los flujos PDF de entrada múltiple al outputStream. Cada página del outputStream contendrá múltiples páginas, que son una combinación con las páginas en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Crea un documento N-Up a partir de los dos flujos PDF de entrada al outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Crea un documento N-Up a partir del primer flujo de entrada al flujo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Crea un documento N-Up a partir de los archivos PDF de entrada múltiple al outputFile. Cada página del outputFile contendrá múltiples páginas, que son una combinación con las páginas en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Crea un documento N-Up a partir del firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Crea un documento N-Up a partir del archivo de entrada al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Crea un documento N-Up a partir de los dos archivos PDF de entrada al outputFile. Cada página del outputFile contendrá dos páginas, una página proviene del primer archivo de entrada y otra del segundo archivo de entrada. Las dos páginas se apilan horizontalmente. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona el contenido de las páginas del documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona las páginas del documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Si se establece en true, se lanzan excepciones si ocurre un error. De lo contrario, no se lanzan excepciones y los métodos devuelven false si fallan. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Si se establece en true, los flujos se cierran después de la operación. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpServletResponse. Valores posibles: inline / attachment. Predeterminado: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Si es true, la estructura lógica del archivo se copia cuando se realiza la concatenación. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Si es true, los outlines se copiarán. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo corrupto. Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representación del procesador interno de eventos de progreso que funciona durante la concatenación y traduce los eventos de concatenación de las etapas internas de concatenación al código externo del cliente. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Si es true, se realizan actualizaciones incrementales durante la concatenación. |
| [setKeepActions](#setKeepActions-boolean-) | Si es true, las acciones se copiarán de los documentos de origen. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Si es true, los nombres de los campos se harán únicos cuando los formularios se concatenen. Se agregarán sufijos a los nombres de los campos; la plantilla de sufijo puede especificarse en la propiedad UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa única en el documento resultante si esta propiedad es true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Si es true, los outlines duplicados se fusionan. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtiene o establece la bandera de optimización. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Establece la contraseña del propietario si el archivo PDF de entrada está cifrado. Esta propiedad aún no está implementada. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. Valor predeterminado: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | A veces los PDFs contienen imágenes de fondo (de páginas o celdas de tabla) construidas a partir de varias imágenes de fondo de mosaico idénticas colocadas una junto a otra. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Establece el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan. Esta cadena debe contener la subcadena %NUM% que será reemplazada por números. Por ejemplo, si UniqueSuffix = "ABC%NUM%" entonces para el campo "fieldName" los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Los flujos NO se cierran después de esta operación. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Divide el archivo PDF desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Los flujos NO se cierran después de esta operación a menos que se especifique CloseConcatedStreams. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Divide desde la ubicación y guarda la parte posterior como un nuevo archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide el archivo PDF en documentos de una sola página. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. |
| [splitToPages](#splitToPages-java.lang.String-) | Divide el archivo PDF en documentos de una sola página. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

Constructor de PdfFileEditor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Agrega saltos de página en las páginas del documento.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Agrega páginas, que se eligen de una matriz de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Agrega páginas, que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Agrega páginas, que se eligen de los documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Agrega páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documentos.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Concatena archivos </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Concatena dos archivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Concatena archivos en un solo archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Concatena dos archivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de forma alterna y rellena los espacios en blanco con páginas en blanco. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Elimina páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Elimina páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Extrae páginas especificadas por una matriz de números, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Extrae páginas del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Extrae páginas especificadas por una matriz de números, y guarda como un nuevo archivo PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract(\"input.pdf\", new int[] { 3, 5, 7 }, \"output.pdf\"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Extrae páginas del archivo de entrada, y guarda como un nuevo archivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract(\"input.pdf\", 3, 7, \"output.pdf\"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Si se establece en true, se lanzan excepciones si ocurre un error. De lo contrario, no se lanzan excepciones y los métodos devuelven false si fallan. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
valor booleano @deprecated Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto.

**Returns:**
valor String

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

Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacena en un objeto HttpServletResponse. Valores posibles: inline / attachment. Predeterminado: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

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

Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo corrupto. Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted.

**Returns:**
Elemento ConcatenateCorruptedFileAction @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Matriz de problemas encontrados cuando se realizó la concatenación. Para cada documento corrupto pasado a la función Concatenate() se crea una nueva entrada CorruptedItem. Esta propiedad solo puede usarse cuando CorruptedFileAction es ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PPdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ \" reason: \" + item.getException()); } } </pre>

**Returns:**
matriz de PdfFileEditor.CorruptedItem

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

Si es true, los nombres de los campos se harán únicos cuando los formularios se concatenen. Se agregarán sufijos a los nombres de los campos; la plantilla de sufijo puede especificarse en la propiedad UniqueSuffix.

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

Obtiene la contraseña del propietario si el archivo Pdf de entrada está cifrado. Esta propiedad aún no está implementada.

**Returns:**
valor String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado.

**Returns:**
valor booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtiene o establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. Valor predeterminado: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Obtenga el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan. Esta cadena debe contener la subcadena %NUM% que será reemplazada por números. Por ejemplo, si UniqueSuffix = "ABC%NUM%" entonces para el campo "fieldName" los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.

**Returns:**
valor String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Inserta páginas de otro archivo en el archivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Inserta páginas de otro archivo en el archivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Inserta páginas de otro archivo en el archivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Inserta páginas de otro archivo en el archivo Pdf en una posición. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> Crea un folleto a partir del InputStream hacia outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Crea un folleto personalizado a partir del firstInputStream hacia outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Crea un folleto a partir del firstInputStream hacia outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Crea un folleto a partir del archivo de entrada hacia el archivo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Crea un folleto personalizado a partir del firstInputFile hacia outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Crea un folleto a partir del inputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Crea un folleto personalizado a partir del firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Crea un documento N-Up a partir de los flujos PDF de entrada múltiple al outputStream. Cada página del outputStream contendrá múltiples páginas, que son una combinación con las páginas en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Crea un documento N-Up a partir de los dos flujos PDF de entrada al outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Crea un documento N-Up a partir del primer flujo de entrada al flujo de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Crea un documento N-Up a partir de los archivos PDF de entrada múltiple al outputFile. Cada página del outputFile contendrá múltiples páginas, que son una combinación con las páginas en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Crea un documento N-Up a partir del firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Crea un documento N-Up a partir del archivo de entrada al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Crea un documento N-Up a partir de los dos archivos PDF de entrada al outputFile. Cada página del outputFile contendrá dos páginas, una página proviene del primer archivo de entrada y otra del segundo archivo de entrada. Las dos páginas se apilan horizontalmente. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona el contenido de las páginas del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona el contenido de las páginas del documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona las páginas del documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Si se establece en true, se lanzan excepciones si ocurre un error. De lo contrario, no se lanzan excepciones y los métodos devuelven false si fallan. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Esta propiedad está obsoleta y no puede usarse para permitir lanzar excepciones. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpServletResponse como adjunto.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Si se establece en true, los flujos se cierran después de la operación. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpServletResponse. Valores posibles: inline / attachment. Predeterminado: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión.

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

Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo corrupto. Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor entero @see ConcatenateCorruptedFileAction |

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

Si es true, los nombres de los campos se harán únicos cuando los formularios se concatenen. Se agregarán sufijos a los nombres de los campos; la plantilla de sufijo puede especificarse en la propiedad UniqueSuffix.

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
Establece la contraseña del propietario si el archivo PDF de entrada está cifrado. Esta propiedad aún no está implementada.

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
public final void setRemoveSignatures(boolean value)
```

Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Establece las opciones de guardado cuando el resultado se almacena como HttpServletResponse. Valor predeterminado: PdfSaveOptions.

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
<p> Establece el formato del sufijo que se agrega al nombre del campo para hacerlo único cuando los formularios se concatenan. Esta cadena debe contener la subcadena %NUM% que será reemplazada por números. Por ejemplo, si UniqueSuffix = "ABC%NUM%" entonces para el campo "fieldName" los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Si se usa esta opción, el documento de destino se guardará en disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el Stream de salida. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Los flujos NO se cierran después de esta operación.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Divide el archivo PDF desde la primera página hasta la ubicación especificada y guarda la parte frontal como un nuevo archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Divide desde la ubicación especificada y guarda la parte posterior como un nuevo Stream de archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Los flujos NO se cierran después de esta operación a menos que se especifique CloseConcatedStreams.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Divide desde la ubicación y guarda la parte posterior como un nuevo archivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Divide el archivo PDF en documentos de una sola página.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada.

### splitToPages {#splitToPages-java.lang.String-}
Divide el archivo PDF en documentos de una sola página.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Divide el archivo Pdf en documentos de una sola página y lo guarda en la ruta especificada.
