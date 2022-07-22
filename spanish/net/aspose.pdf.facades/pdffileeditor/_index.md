---
title: PdfFileEditor
second_title: Referencia de API de Aspose.PDF para .NET
description: Implementa operaciones con archivo PDF concatenación división extracción de páginas elaboración de cuadernillo etc.
type: docs
weight: 2470
url: /es/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Implementa operaciones con archivo PDF: concatenación, división, extracción de páginas, elaboración de cuadernillo, etc.

```csharp
public sealed class PdfFileEditor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | Obtiene o establece el nombre del archivo adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como archivo adjunto. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | Si se establece en verdadero, los flujos se cierran después de la operación. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | Número de documentos concatenados antes de que se realizara una nueva actualización incremental durante la concatenación cuando UseDiskBuffer se establece en verdadero. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | Obtiene o establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en el objeto HttpResponse. Valor posible: en línea / archivo adjunto. Valor predeterminado: en línea. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Obtiene el registro del proceso de conversión. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | Establece el formato de archivo PDF. El archivo de resultados se guardará en el formato de archivo especificado. Si no se especifica esta propiedad, el archivo se guardará en formato PDF predeterminado sin conversión. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Si es verdadero, la estructura lógica del archivo se copia cuando se realiza la concatenación. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Si es verdadero, se copiarán los contornos. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Esta propiedad define el comportamiento cuando el proceso de concatenación encuentra un archivo dañado. Los valores posibles son: StopWithError y ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | Matriz de problemas encontrados cuando se realizó la concatenación. Por cada documento dañado que se pasa a la función Concatenate() , se crea una nueva entrada CorruptedItem. Esta propiedad solo se puede usar cuando CorruptedFileAction es ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | Si es verdadero, se realizan actualizaciones incrementales durante la concatenación. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Si es cierto, las acciones se copiarán de los documentos de origen. Valor predeterminado: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | Si es verdadero, los nombres de los campos serán únicos cuando se concatenen los formularios. Se agregarán sufijos a los nombres de los campos, la plantilla de sufijos se puede especificar en la propiedad UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | Obtiene la última excepción que ocurrió. Se puede utilizar para comprobar el motivo de la falla. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | Los contenidos opcionales de los documentos concatenados con nombres iguales se fusionarán en una capa en el documento resultante si esta propiedad es verdadera. De lo contrario, las capas con nombres iguales se guardarán como capas diferentes en el documento resultante. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Si es verdadero, se fusionan los contornos duplicados. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Obtiene o establece el indicador de optimización. Los flujos de recursos iguales en el archivo resultante se fusionan en un objeto PDF si se establece esta marca. Esto permite disminuir el tamaño del archivo resultante, pero puede provocar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Establece la contraseña del propietario si el archivo Pdf de entrada de origen está encriptado. Esta propiedad aún no está implementada. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Si es verdadero, los derechos de usuario del primer documento se aplican al documento concatenado. Los derechos de usuario de todos los demás documentos se ignoran. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Si es verdadero, todas las firmas se eliminarán de los campos (los campos permanecerán); de lo contrario, puede obtener firmas no válidas. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Obtiene o establece opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Formato del sufijo que se agrega al nombre del campo para que sea único cuando se concatenan formularios. Esta cadena debe contener %NUM% subcadena que se reemplazará con números. Por ejemplo, si UniqueSuffix = "ABC%NUM%", entonces para los nombres del campo "fieldName" serán: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Si se usa esta opción, el documento de destino se guardará en el disco periódicamente y se le aplicará una concatenación adicional como actualizaciones incrementales. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Cambia el tamaño del contenido de la página y agrega los márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Cambia el tamaño del contenido de la página y agrega los márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Cambia el tamaño del contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño de página inicial. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Cambia el tamaño del contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño de página inicial. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Agrega saltos de página en las páginas del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Agrega saltos de página en las páginas del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Agrega saltos de página en las páginas del documento. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | Agrega páginas, que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Agrega documentos al documento de origen y guarda el resultado en el objeto de respuesta. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | Agrega páginas, que se eligen de una matriz de documentos en portStreams. El documento de resultado incluye firstInputFile y todas las páginas de documentos de portStreams en el rango startPage a endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | Agrega páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Agrega documentos al documento de origen y guarda el resultado en el objeto HttpResponse. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | Agrega páginas, que se eligen de los documentos portFiles. El documento de resultados incluye firstInputFile y todas las páginas de documentos portFiles en el rango startPage a endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Concatena documentos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Concatena archivos y almacena el resultado en el objeto HttpResponse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Concatena archivos |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Concatena archivos y guarda el resultado en el objeto HttpResposnse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Concatena archivos en un solo archivo. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | Concatena dos archivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | Concatena dos archivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | Combina dos documentos PDF en un nuevo documento PDF con páginas de forma alternativa y llena los espacios en blanco con páginas en blanco. p. ej.: el documento 1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. La fusión de los dos documentos PDF producirá el documento de resultado con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | Combina dos documentos PDF en un nuevo documento PDF con páginas de forma alternativa y llena los espacios en blanco con páginas en blanco. p. ej.: el documento 1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. La fusión de los dos documentos PDF producirá el documento de resultado con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Elimina páginas específicas del documento y guarda el resultado en el objeto HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Elimina las páginas especificadas por la matriz de números del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Elimina páginas específicas del documento y almacena el resultado en el objeto HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Elimina las páginas especificadas por la matriz de números del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Extrae páginas del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Extrae páginas del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Inserta un documento en otro documento y almacena el resultado en el objeto de respuesta. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Inserta el contenido del archivo en el archivo de origen y almacena el resultado en el objeto HttpResponse. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Inserta páginas de otro archivo en el archivo PDF en una posición. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | Hace un folleto desde InputStream hasta outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Hace un folleto desde el archivo de entrada hasta el archivo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Crea un folleto a partir del archivo de origen y almacena el resultado en HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | Crea un folleto desde el archivo de entrada hasta el archivo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | Crea un folleto personalizado desde el primer flujo de entrada hasta el flujo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Crea un folleto a partir de un archivo PDF y lo almacena en HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Crea un folleto desde el primer flujo de entrada hasta el flujo de salida. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | Crea un documento N-Up desde los dos flujos de PDF de entrada a outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Crea un documento N-Up desde los flujos de PDF de múltiples entradas a outputStream. Cada página de outputStream contendrá varias páginas, que se combinan con las páginas en los flujos de entrada del mismo número de página. Las páginas múltiples se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | Crea un documento N-Up a partir de los dos archivos PDF de entrada en el archivo de salida. Cada página de archivo de salida contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas se apilan horizontalmente. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Hace un documento N-Up desde los archivos PDF de entrada múltiple a archivo de salida. Cada página de archivo de salida contendrá varias páginas, que se combinan con las páginas en los archivos de entrada del mismo número de página. Las páginas múltiples se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | Crea un documento N-up y almacena el resultado en HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | Crea un documento N-up y almacena el resultado en HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | Crea un documento N-Up desde el primer archivo de entrada hasta el archivo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | Crea un documento N-Up desde el primer flujo de entrada hasta el flujo de salida. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Crea un documento N-Up desde el archivo de entrada hasta el archivo de salida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Cambia el tamaño de las páginas del documento. Se agregan márgenes en blanco alrededor de la página reducida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Cambia el tamaño de las páginas del documento. Se agregan márgenes en blanco alrededor de la página reducida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Cambia el tamaño del contenido de las páginas del documento. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en el objeto HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Se divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el flujo de salida. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Divide el documento desde la primera página hasta la ubicación y guarda el resultado en objetos HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Divide el archivo PDF desde la primera página a la ubicación especificada y guarda la parte frontal como un nuevo archivo. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Divide el archivo PDF en varios documentos. Los documentos pueden ser de una sola página o de varias páginas. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Se divide desde la ubicación especificada y guarda la parte trasera en el objeto HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Se divide desde la ubicación especificada y guarda la parte trasera como un nuevo archivo Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Se divide desde la ubicación especificada y guarda la parte trasera en el objeto HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Se separa de la ubicación y guarda la parte trasera como un archivo nuevo. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Divide el archivo PDF en documentos de una sola página. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | Divide el archivo PDF en documentos de una sola página. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Divide el archivo PDF en documentos de una sola página y lo guarda en la ruta especificada. La ruta se especifica por nombre de campo temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Divide el archivo PDF en documentos de una sola página y lo guarda en la ruta especificada. La ruta se especifica por nombre de campo temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Agrega documentos al documento de origen y guarda el resultado en el objeto de respuesta. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | Agrega páginas, que se eligen de una matriz de documentos en portStreams. El documento de resultado incluye firstInputFile y todas las páginas de documentos de portStreams en el rango startPage a endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Agrega documentos al documento de origen y guarda el resultado en el objeto HttpResponse. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | Agrega páginas, que se eligen de los documentos portFiles. El documento de resultados incluye firstInputFile y todas las páginas de documentos portFiles en el rango startPage a endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Concatena documentos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Concatena archivos y almacena el resultado en el objeto HttpResponse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Concatena archivos |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Concatena archivos y guarda el resultado en el objeto HttpResposnse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Concatena archivos en un solo archivo. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | Concatena dos archivos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Combina dos documentos PDF en un nuevo documento PDF con páginas de forma alternativa y llena los espacios en blanco con páginas en blanco. p. ej.: el documento 1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. La fusión de los dos documentos PDF producirá el documento de resultado con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | Combina dos documentos PDF en un nuevo documento PDF con páginas de forma alternativa y llena los espacios en blanco con páginas en blanco. p. ej.: el documento 1 tiene 5 páginas: p1, p2, p3, p4, p5. document2 tiene 3 páginas: p1', p2', p3'. La fusión de los dos documentos PDF producirá el documento de resultado con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Elimina páginas específicas del documento y guarda el resultado en el objeto HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Elimina las páginas especificadas por la matriz de números del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Elimina páginas específicas del documento y almacena el resultado en el objeto HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Elimina las páginas especificadas por la matriz de números del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Extrae páginas del archivo de entrada, las guarda como un nuevo archivo PDF. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Inserta un documento en otro documento y almacena el resultado en el objeto de respuesta. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Inserta el contenido del archivo en el archivo de origen y almacena el resultado en el objeto HttpResponse. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Inserta páginas de otro archivo en el archivo Pdf de entrada. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | Hace un folleto desde InputStream hasta outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Hace un folleto desde el archivo de entrada hasta el archivo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Crea un folleto a partir del archivo de origen y almacena el resultado en HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | Crea un folleto desde el archivo de entrada hasta el archivo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | Crea un folleto personalizado desde el primer flujo de entrada hasta el flujo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Crea un folleto a partir de un archivo PDF y lo almacena en HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Crea un folleto desde el primer flujo de entrada hasta el flujo de salida. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | Crea un documento N-Up desde los dos flujos de PDF de entrada a outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Crea un documento N-Up desde los flujos de PDF de múltiples entradas a outputStream. Cada página de outputStream contendrá varias páginas, que se combinan con las páginas en los flujos de entrada del mismo número de página. Las páginas múltiples se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | Crea un documento N-Up a partir de los dos archivos PDF de entrada en el archivo de salida. Cada página de archivo de salida contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas se apilan horizontalmente. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Hace un documento N-Up desde los archivos PDF de entrada múltiple a archivo de salida. Cada página de archivo de salida contendrá varias páginas, que se combinan con las páginas en los archivos de entrada del mismo número de página. Las páginas múltiples se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | Crea un documento N-up y almacena el resultado en HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | Crea un documento N-up y almacena el resultado en HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | Crea un documento N-Up desde el primer archivo de entrada hasta el archivo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | Crea un documento N-Up desde el primer flujo de entrada hasta el flujo de salida. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | Crea un documento N-up y almacena el resultado en el objeto HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Crea un documento N-Up desde el archivo de entrada hasta el archivo de salida. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Cambia el tamaño del contenido de las páginas del documento. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Divide el documento desde el inicio hasta la ubicación especificada y almacena el resultado en el objeto HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Se divide desde el inicio hasta la ubicación especificada y guarda la parte frontal en el flujo de salida. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Divide el documento desde la primera página hasta la ubicación y guarda el resultado en objetos HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Divide el archivo PDF desde la primera página a la ubicación especificada y guarda la parte frontal como un nuevo archivo. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Se divide desde la ubicación especificada y guarda la parte trasera en el objeto HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Se divide desde la ubicación especificada y guarda la parte trasera como un nuevo archivo Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Se divide desde la ubicación especificada y guarda la parte trasera en el objeto HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Se separa de la ubicación y guarda la parte trasera como un archivo nuevo. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Acción realizada cuando se encontró un archivo dañado en el proceso de concatenación. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Clase para especificar parámetros de cambio de tamaño de página. Permite establecer los siguientes parámetros: Tamaño de la página de resultados (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de las páginas iniciales; Márgenes izquierdo, superior, inferior y derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de página inicial; Algunos valores pueden dejarse nulos para el cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores explícitamente especificados. Por ejemplo: si el ancho de página = 100 y el nuevo ancho de página especificado 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se usa en el método ResizeContents. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Valor del margen o tamaño del contenido especificado en porcentajes de unidades de espacio predeterminadas. Esta clase se usa en ContentsResizeParameters. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Clase que proporciona información sobre archivos dañados en el momento de la concatenación. |
| class [PageBreak](pdffileeditor.pagebreak) | Datos de posición de salto de página. |

### Ver también

* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
