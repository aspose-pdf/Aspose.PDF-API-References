---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfFileEditor. Implementa operaciones con archivos PDF como concatenación, división, extracción de páginas, creación de folletos, etc.
type: docs
weight: 4460
url: /es/net/aspose.pdf.facades/pdffileeditor/
---
## Clase PdfFileEditor

Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folletos, etc.

```csharp
public sealed class PdfFileEditor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Si se establece en verdadero, los flujos se cierran después de la operación. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Número de documentos concatenados antes de que se realice una nueva actualización incremental durante la concatenación cuando UseDiskBuffer está establecido en verdadero. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Obtiene el registro del proceso de conversión. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Establece el formato del archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Si es verdadero, la estructura lógica del archivo se copia cuando se realiza la concatenación. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Si es verdadero, se copiarán los contornos. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo corrupto. Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array de problemas encontrados cuando se realizó la concatenación. Para cada documento corrupto pasado a la función Concatenate(), se crea una nueva entrada CorruptedItem. Esta propiedad solo se puede usar cuando CorruptedFileAction es ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Si es verdadero, se realizan actualizaciones incrementales durante la concatenación. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Si es verdadero, las acciones se copiarán de los documentos de origen. Valor predeterminado: verdadero. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Si es verdadero, los nombres de los campos serán únicos cuando se concatenen formularios. Se agregarán sufijos a los nombres de los campos, el formato del sufijo se puede especificar en la propiedad UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Obtiene la última excepción ocurrida. Puede usarse para verificar la razón del fallo. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | El contenido opcional de los documentos concatenados con nombres iguales se fusionará en una capa en el documento resultante si esta propiedad es verdadera. De lo contrario, las capas con nombres iguales se guardarán como diferentes capas en el documento resultante. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Si es verdadero, se fusionan los contornos duplicados. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Obtiene o establece la bandera de optimización. Los flujos de recursos iguales en el archivo resultante se fusionan en un objeto PDF si esta bandera está establecida. Esto permite reducir el tamaño del archivo resultante, pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: falso. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Establece la contraseña del propietario si el archivo PDF de entrada fuente está encriptado. Esta propiedad aún no está implementada. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. Los derechos de usuario de todos los demás documentos se ignoran. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Si es verdadero, se eliminarán todas las firmas de los campos (los campos permanecerán); de lo contrario, puede obtener firmas inválidas. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Formato del sufijo que se agrega al nombre del campo para hacerlo único cuando se concatenan formularios. Esta cadena debe contener la subcadena %NUM% que será reemplazada por números. Por ejemplo, si UniqueSuffix = "ABC%NUM%", entonces para el campo "fieldName" los nombres serán: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Si se utiliza esta opción, el documento de destino se guardará en el disco periódicamente y la concatenación posterior se aplicará a él como actualizaciones incrementales. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Agrega saltos de página en las páginas del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Agrega saltos de página en las páginas del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Agrega saltos de página en las páginas del documento. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Agrega páginas, que se eligen del portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Agrega páginas, que se eligen de un array de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos portStreams en el rango de startPage a endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Agrega páginas, que se eligen del portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Agrega páginas, que se eligen de documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango de startPage a endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Concatenar documentos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Concatenar archivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Concatenar archivos en un solo archivo. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Concatenar dos archivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Concatenar dos archivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Fusiona dos documentos PDF en un nuevo documento PDF con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. por ejemplo: document1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos PDF producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Fusiona dos documentos PDF en un nuevo documento PDF con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. por ejemplo: document1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos PDF producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Elimina las páginas especificadas por el array de números del archivo de entrada, guarda como un nuevo archivo PDF. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Elimina las páginas especificadas por el array de números del archivo de entrada, guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extrae las páginas especificadas por el array de números, guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extrae las páginas especificadas por el array de números, guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo PDF. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Inserta páginas de otro archivo en el archivo PDF en una posición. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Crea un folleto desde el InputStream al outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Crea un folleto desde el flujo de entrada y guarda el resultado en el flujo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Crea un folleto personalizado desde el InputStream al outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Crea un folleto personalizado desde el archivo de entrada al archivo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crea un folleto desde el InputStream al outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Crea un folleto personalizado desde el archivo de entrada al archivo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Crea un documento N-Up a partir de los dos flujos PDF de entrada al outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Crea un documento N-Up a partir de los múltiples flujos PDF de entrada al outputStream. Cada página del outputStream contendrá múltiples páginas, que son combinaciones de páginas en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Crea un documento N-Up a partir de los dos archivos PDF de entrada al outputFile. Cada página del outputFile contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas se apilan horizontalmente. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Crea un documento N-Up a partir de los múltiples archivos PDF de entrada al outputFile. Cada página del outputFile contendrá múltiples páginas, que son combinaciones de páginas en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Crea un documento N-Up desde el archivo de entrada al outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Crea un documento N-Up desde el primer flujo de entrada al flujo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Crea un documento N-Up desde el archivo de entrada al outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Redimensiona las páginas del documento. Se agregan márgenes en blanco alrededor de la página reducida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Redimensiona las páginas del documento. Se agregan márgenes en blanco alrededor de la página reducida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensiona el contenido de las páginas del documento. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Divide desde el inicio hasta la ubicación especificada y guarda la parte delantera en el flujo de salida. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Divide el archivo PDF desde la primera página hasta la ubicación especificada y guarda la parte delantera como un nuevo archivo. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Divide desde la ubicación especificada y guarda la parte trasera como un nuevo flujo de archivo. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Divide desde la ubicación y guarda la parte trasera como un nuevo archivo. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Divide el archivo PDF en documentos de una sola página. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Divide el archivo PDF en documentos de una sola página. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Divide el archivo PDF en documentos de una sola página y los guarda en la ruta especificada. La ruta se especifica mediante la plantilla del nombre del campo. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Divide el archivo PDF en documentos de una sola página y los guarda en la ruta especificada. La ruta se especifica mediante la plantilla del nombre del campo. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Agrega páginas, que se eligen de un array de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos portStreams en el rango de startPage a endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Agrega páginas, que se eligen de documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango de startPage a endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Concatenar documentos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Concatenar archivos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Concatenar archivos en un solo archivo. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Concatenar dos archivos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Fusiona dos documentos PDF en un nuevo documento PDF con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. por ejemplo: document1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos PDF producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Fusiona dos documentos PDF en un nuevo documento PDF con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. por ejemplo: document1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos PDF producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Elimina las páginas especificadas por el array de números del archivo de entrada, guarda como un nuevo archivo PDF. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Elimina las páginas especificadas por el array de números del archivo de entrada, guarda como un nuevo archivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extrae las páginas especificadas por el array de números, guarda como un nuevo archivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extrae las páginas especificadas por el array de números, guarda como un nuevo archivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extrae páginas del archivo de entrada, guarda como un nuevo archivo PDF. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Inserta páginas de otro archivo en el archivo PDF de entrada. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Crea un folleto desde el InputStream al outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Crea un folleto desde el flujo de entrada y guarda el resultado en el flujo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Crea un folleto desde el archivo de entrada al archivo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Crea un folleto personalizado desde el InputStream al outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Crea un folleto personalizado desde el archivo de entrada al archivo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crea un folleto desde el InputStream al outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Crea un folleto personalizado desde el archivo de entrada al archivo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Crea un documento N-Up a partir de los dos flujos PDF de entrada al outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Crea un documento N-Up a partir de los múltiples flujos PDF de entrada al outputStream. Cada página del outputStream contendrá múltiples páginas, que son combinaciones de páginas en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Crea un documento N-Up a partir de los dos archivos PDF de entrada al outputFile. Cada página del outputFile contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas se apilan horizontalmente. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Crea un documento N-Up a partir de los múltiples archivos PDF de entrada al outputFile. Cada página del outputFile contendrá múltiples páginas, que son combinaciones de páginas en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Crea un documento N-Up desde el archivo de entrada al outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Crea un documento N-Up desde el primer flujo de entrada al flujo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Crea un documento N-Up desde el archivo de entrada al outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensiona el contenido de las páginas del documento. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Divide desde el inicio hasta la ubicación especificada y guarda la parte delantera en el flujo de salida. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Divide el archivo PDF desde la primera página hasta la ubicación especificada y guarda la parte delantera como un nuevo archivo. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Divide desde la ubicación especificada y guarda la parte trasera como un nuevo flujo de archivo. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Divide desde la ubicación y guarda la parte trasera como un nuevo archivo. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Acción realizada cuando se encuentra un archivo corrupto en el proceso de concatenación. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Clase para especificar parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño inicial de las páginas; Márgenes izquierdo, superior, inferior y derecho en unidades de espacio predeterminadas o en porcentajes del tamaño inicial de la página; Algunos valores pueden dejarse nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores explícitamente especificados. Por ejemplo: si el ancho de la página = 100 y el nuevo ancho de la página especificado es de 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se utiliza en el método ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Valor de margen o tamaño de contenido especificado en porcentajes de unidades de espacio predeterminadas. Esta clase se utiliza en ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Clase que proporciona información sobre archivos corruptos en el momento de la concatenación. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Datos de la posición del salto de página. |

### Ver También

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)