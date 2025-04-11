---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Document. Clase que representa un documento PDF
type: docs
weight: 3780
url: /es/net/aspose.pdf/document/
---
## Clase Document

Clase que representa un documento PDF.

```csharp
public sealed class Document : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Document](document/#constructor)() | Inicializa un documento vacío. |
| [Document](document/#constructor_1)(PdfVersion) | Inicializa un documento vacío por versión. |
| [Document](document/#constructor_2)(Stream) | Inicializa una nueva instancia de Document desde el *stream* de entrada. |
| [Document](document/#constructor_7)(string) | Solo inicializa Document usando *filename*. Lo mismo que [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Inicializa una nueva instancia de Document desde el *stream* de entrada. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Abre un documento existente desde un stream proporcionando la conversión necesaria para obtener el documento PDF. |
| [Document](document/#constructor_5)(Stream, string) | Inicializa una nueva instancia de Document desde el *stream* de entrada. |
| [Document](document/#constructor_9)(string, bool) | Solo inicializa Document usando *filename*. Lo mismo que [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Abre un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener el documento PDF. |
| [Document](document/#constructor_10)(string, string) | Inicializa una nueva instancia de la clase `Document` para trabajar con documentos encriptados. |
| [Document](document/#constructor_6)(Stream, string, bool) | Inicializa una nueva instancia de Document desde el *stream* de entrada. |
| [Document](document/#constructor_11)(string, string, bool) | Inicializa una nueva instancia de la clase `Document` para trabajar con documentos encriptados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Obtiene las acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones como BeforClosing, BeforSaving, etc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Permite fusionar contenidos de página para optimizar el tamaño del documento. Si se usa, entonces páginas diferentes pero duplicadas pueden hacer referencia al mismo objeto de contenido. Tenga en cuenta que este modo puede causar efectos secundarios como cambiar el contenido de la página cuando se cambia otra página. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Obtiene o establece el color de fondo del documento. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Obtiene o establece un indicador que especifica si la posición de la ventana del documento estará centrada en la pantalla. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Obtiene la colección del documento. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Obtiene la configuración de seguridad si el documento está encriptado. Si el documento no está encriptado, se generará la excepción correspondiente en .net 1.1 o CryptoAlgorithm será nulo para otras versiones de .net. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Obtiene la colección de destinos. Obsoleto. Por favor, use NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Obtiene o establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Muchas operaciones con fuentes no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente. Por ejemplo, algunas fuentes no pueden ser incrustadas en un documento PDF si las reglas de licencia deshabilitan la incrustación para esta fuente. Este indicador se utiliza para deshabilitar cualquier restricción de licencia para todas las fuentes en el documento PDF actual. Tenga cuidado al usar este indicador. Cuando se establece, significa que la persona que establece este indicador asume toda la responsabilidad de posibles violaciones de licencia/ley. Por lo tanto, lo asume bajo su propio riesgo. Se recomienda encarecidamente usar este indicador solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. Por defecto, falso. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Obtiene o establece un indicador que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Obtiene o establece la opción de manejo del modo de impresión dúplex a utilizar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Obtiene la colección de archivos incrustados en el documento. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Propiedad que declara que el documento debe incrustar todas las fuentes estándar Type1 que tienen el indicador IsEmbedded establecido en verdadero. Todas las fuentes PDF pueden ser incrustadas en el documento simplemente configurando el indicador IsEmbedded en verdadero, pero las fuentes estándar Type1 de PDF son una excepción a esta regla. La incrustación de fuentes estándar Type1 requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer el indicador IsEmbedded en verdadero para la fuente especificada, sino también establecer un indicador adicional a nivel de documento: EmbedStandardFonts = true; Esta propiedad solo se puede establecer una vez para todas las fuentes. Por defecto, falso. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Obtiene o establece un indicador que permite que el documento se descargue parcialmente de la memoria. Esto permite disminuir el uso de memoria, pero puede tener un efecto negativo en el rendimiento. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Obtiene o establece un indicador para gestionar la sanitización de campos de firma. Habilitado por defecto. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nombre del archivo PDF que causó este documento |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Obtiene o establece un indicador que especifica si la ventana del documento debe ser redimensionada para ajustarse a la primera página mostrada. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instancia de IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Obtiene el Acro Form del documento. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Lanza una excepción si el documento se guarda con cambios y tiene firma |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Obtiene o establece un indicador que especifica si la barra de menú debe estar oculta cuando el documento está activo. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Obtiene o establece un indicador que especifica si la barra de herramientas debe estar oculta cuando el documento está activo. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Obtiene o establece un indicador que especifica si los elementos de la interfaz de usuario deben estar ocultos cuando el documento está activo. |
| [Id](../../aspose.pdf/document/id/) { get; } | Obtiene el ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Obtiene o establece un indicador para ignorar errores en archivos fuente. Cuando las páginas del documento fuente se copian en el documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos fuente están corruptos cuando este indicador es falso. ejemplo: dest.Pages.Add(src.Pages); Si este indicador se establece en verdadero, entonces los objetos corruptos serán reemplazados por valores vacíos. Por defecto: verdadero. |
| [Info](../../aspose.pdf/document/info/) { get; } | Obtiene la información del documento. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Obtiene el estado de encriptación del documento. Verdadero si el documento está encriptado. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Obtiene o establece un valor que indica si el documento está linealizado. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Obtiene si el documento es compatible con pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Obtiene si el documento es compatible con pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Obtiene o establece si el documento es compatible con pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Colección de JavaScript a nivel de documento. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Obtiene la estructura lógica del documento. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Metadatos del documento. (Un documento PDF puede incluir información general, como el título del documento, autor y fechas de creación y modificación. Tal información global sobre el documento (en oposición a su contenido o estructura) se llama metadatos y está destinada a ayudar en la catalogación y búsqueda de documentos en bases de datos externas.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Colección de Destinos Nombrados en el documento. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Obtiene o establece el modo de página, especificando cómo se debe mostrar el documento al salir del modo de pantalla completa. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Obtiene o establece la acción realizada al abrir el documento. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Obtiene o establece el indicador de optimización. Cuando se agregan páginas al documento, los flujos de recursos iguales en el archivo resultante se fusionan en un objeto PDF si este indicador está establecido. Esto permite disminuir el tamaño del archivo resultante, pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: falso. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Obtiene los contornos del documento. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Obtiene la colección de Intenciones de Salida en el documento. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Obtiene o establece la información de la página. (solo para generador, no se llena al leer el documento) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Obtiene las etiquetas de página en el documento. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Obtiene o establece el diseño de página que se utilizará al abrir el documento. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Obtiene o establece el modo de página, especificando cómo se debe mostrar el documento al abrirse. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Obtiene o establece la colección de páginas del documento. Tenga en cuenta que las páginas están numeradas desde 1 en la colección. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Obtiene el formato PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Obtiene los permisos del documento. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Obtiene o establece un indicador que especifica si el tamaño de página PDF debe utilizarse para seleccionar la bandeja de papel de entrada. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Obtiene o establece la opción de escalado de página que se seleccionará cuando se muestre un cuadro de diálogo de impresión para este documento. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Obtiene acceso al contenido TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Obtiene una versión de Pdf del encabezado del archivo Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Obtiene y establece el límite de tamaño de archivo para cargar un archivo completo en memoria. El valor se establece en megabytes. El valor predeterminado es 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Obtiene el estado de licencia del sistema. Devuelve verdadero si el sistema funciona en modo licenciado y falso en caso contrario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Fusiona documentos. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Fusiona archivos pdf. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Fusiona documentos. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Fusiona documentos. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Vincula xml al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Vincula xml al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Vincula xml/xsl al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Vincula xml/xsl al documento |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Vincula xml/xsl al documento |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Cambia las contraseñas del documento. Esta acción solo se puede realizar utilizando la contraseña del propietario. |
| [Check](../../aspose.pdf/document/check/)(bool) | Valida el documento. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Convierte el documento utilizando las opciones de conversión especificadas |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Reconoce imágenes dentro del documento y agrega cadenas hocr sobre ellas. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Reconoce imágenes dentro del documento y agrega cadenas hocr sobre ellas. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Convierte el documento y guarda errores en el stream especificado. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Convierte el documento y guarda errores en el archivo especificado. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Convierte el documento aplicando el Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Convierte el documento aplicando el Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convierte el documento y guarda errores en el archivo especificado. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convierte el documento y guarda errores en el archivo especificado. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Convierte la página a PNG para DSR, OMR, flujo de imagen OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Desencripta el documento. Llame luego a Save para obtener la versión desencriptada del documento. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Cierra todos los recursos utilizados por este documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Encripta el documento. Llame luego a Save para obtener la versión encriptada del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Encripta el documento. Llame luego a Save para obtener la versión encriptada del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Encripta el documento. Llame luego a Save para obtener la versión encriptada del documento. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exporta todas las anotaciones del documento al stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exporta todas las anotaciones del documento a un archivo XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Reemplaza el contenido transparente con gráficos raster y vectoriales no transparentes. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Limpia la memoria |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Devuelve el valor del elemento del diccionario del catálogo. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Obtiene un objeto con el ID especificado en el documento. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Obtiene metadatos XMP del documento. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Verifica si el documento PDF actual ha sido guardado con actualizaciones incrementales. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importa anotaciones desde el stream al documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importa anotaciones desde un archivo XFDF al documento. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Verifica si el documento requiere una llamada al método Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Carga un archivo, convirtiéndolo a PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Fusiona documentos. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Fusiona archivos pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Fusiona documentos. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Fusiona documentos. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linealiza el documento para - abrir la primera página lo más rápido posible; - mostrar la siguiente página o seguir un enlace a la siguiente página lo más rápido posible; - mostrar la página de manera incremental a medida que llega cuando los datos de una página se entregan a través de un canal lento (mostrar los datos más útiles primero); - permitir la interacción del usuario, como seguir un enlace, que se realice incluso antes de que se haya recibido y mostrado toda la página. Invocar este método no guarda realmente el documento. Por el contrario, el documento solo se prepara para tener una estructura optimizada, llame luego a Save para obtener el documento optimizado. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimiza los recursos en el documento: 1. Se eliminan los recursos que no se utilizan en las páginas del documento; 2. Los recursos iguales se unen en un objeto; 3. Se eliminan los objetos no utilizados. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimiza los recursos en el documento de acuerdo con la estrategia de optimización definida. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organiza los nodos del árbol de páginas en un documento en un árbol equilibrado. Solo si el documento tiene más de nodesNumInSubtrees objetos de página, de lo contrario no hace nada. No llame a este método mientras itera sobre los elementos de Pages, puede dar resultados impredecibles |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Procesa párrafos para el generador. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Elimina metadatos del documento. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Elimina la conformidad pdfa del documento |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Elimina la conformidad pdfUa del documento |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Repara el documento dañado. |
| [Save](../../aspose.pdf/document/save/#save)() | Guarda el documento de manera incremental (es decir, utilizando la técnica de actualización incremental). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Guarda el documento con opciones de guardado. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Almacena el documento en el stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Guarda el documento en el archivo especificado. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Guarda el documento en un stream con opciones de guardado. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Guarda el documento con un nuevo nombre estableciendo sus opciones de guardado. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Guarda el documento de manera incremental (es decir, utilizando la técnica de actualización incremental). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Guarda el documento con opciones de guardado. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Almacena el documento en el stream. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Guarda el documento en el archivo especificado. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Guarda el documento en un stream con opciones de guardado. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Guarda el documento con un nuevo nombre estableciendo sus opciones de guardado. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Guarda el documento en XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Envía ciertas páginas del documento al dispositivo de documento para su procesamiento. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Establece el Título para el Documento Pdf |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Establece los metadatos XMP del documento. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Valida el documento en el archivo especificado. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Valida el documento en el archivo especificado. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Valida el documento en el archivo especificado. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Convierte el stream en formato fuente en un stream en formato de destino. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Convierte el stream en formato fuente en un archivo de destino en formato de destino. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Convierte el archivo fuente en formato fuente en un stream en formato de destino. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Convierte el archivo fuente en formato fuente en un archivo de destino en formato de destino. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Establece el límite de tamaño de archivo para cargar un archivo completo en memoria al valor predeterminado que equivale a 210 Mb. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Ocurre cuando una fuente reemplaza a otra fuente en el documento. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Representa el método que manejará el evento FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Contiene funcionalidad para ajustar fuentes |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Representa las opciones para los métodos de fusión. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Representa opciones para reparar un documento PDF. |

### Véase También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)