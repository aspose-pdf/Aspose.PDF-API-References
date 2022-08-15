---
title: Document
second_title: Referencia de API de Aspose.PDF para .NET
description: Clase que representa el documento PDF
type: docs
weight: 1870
url: /es/net/aspose.pdf/document/
---
## Document class

Clase que representa el documento PDF

```csharp
public sealed class Document : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Document](document#constructor)() | Inicializa documento vacío. |
| [Document](document#constructor_1)(Stream) | Inicializar nueva instancia de Documento desde el*input* flujo. |
| [Document](document#constructor_6)(string) | Simplemente inicie el documento usando*filename* . Lo mismo que[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Inicializar nueva instancia de Documento desde el*input* flujo. |
| [Document](document#constructor_2)(Stream, LoadOptions) | Abre un documento existente de una secuencia que proporciona la conversión necesaria para obtener el documento pdf. |
| [Document](document#constructor_4)(Stream, string) | Inicializar nueva instancia de Documento desde el*input* flujo. |
| [Document](document#constructor_7)(string, LoadOptions) | Abre un documento existente de un archivo que proporciona las opciones de conversión necesarias para obtener un documento pdf. |
| [Document](document#constructor_8)(string, string) | Inicializa una nueva instancia del[`Document`](../document) clase para trabajar con documento encriptado. |
| [Document](document#constructor_5)(Stream, string, bool) | Inicializar nueva instancia de Documento desde el*input* flujo. |
| [Document](document#constructor_9)(string, string, bool) | Inicializa una nueva instancia del[`Document`](../document) clase para trabajar con documento encriptado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Obtiene las acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones BeforClosing, BeforSaving, etc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Permite fusionar contenidos de página para optimizar el tamaño del documento. Si se usa, las páginas diferentes pero duplicadas pueden hacer referencia al mismo objeto de contenido . Tenga en cuenta que este modo puede causar efectos secundarios como cambiar el contenido de la página cuando se cambia otra página. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Obtiene o establece el color de fondo del documento. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Obtiene o establece un indicador que especifica si la posición de la ventana del documento se centrará en la pantalla. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Obtiene la colección de documentos. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Obtiene la configuración de seguridad si el documento está encriptado. Si el documento no está encriptado, se generará la excepción correspondiente en .net 1.1 o CryptoAlgorithm será nulo para otras versiones de .net. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Obtiene la colección de destinos. Obsoleto. Utilice NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Obtiene o establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | Muchas operaciones con la fuente no se pueden ejecutar si estas operaciones están prohibidas por la licencia de esta fuente. Por ejemplo, algunas fuentes no se pueden incrustar en un documento PDF si las reglas de licencia deshabilitan la incrustación de esta fuente. Este indicador se usa para deshabilitar cualquier restricción de licencia para todas las fuentes en el documento PDF actual. Tenga cuidado al usar este indicador. Cuando se establece, significa que la persona que establece este indicador, , asume toda la responsabilidad de las posibles infracciones de licencia/ley sobre sí mismo. Así que lo toma bajo su propio riesgo. Se recomienda enfáticamente usar esta marca solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. Por defecto false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Obtiene o establece un indicador que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Obtiene o establece la opción de manejo del modo de impresión dúplex para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Obtiene una colección de archivos incrustados en el documento. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar que tiene el indicador IsEmbedded establecido en verdadero. Todas las fuentes PDF se pueden incrustar en el documento simplemente configurando el indicador IsEmbedded en verdadero, pero las fuentes PDF estándar Type1 son una excepción a esta regla. IsEmbedded en true para la fuente especificada, pero también establece una marca adicional en el nivel del documento - EmbedStandardFonts = true; Esta propiedad se puede establecer solo una vez para todas las fuentes. De forma predeterminada, false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Obtiene o establece un indicador que permite que el documento se descargue parcialmente de la memoria. Esto permite disminuir el uso de la memoria pero puede tener un efecto negativo en el rendimiento. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | Obtiene o establece un indicador para administrar la desinfección de campos de firma. Habilitado por defecto. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Nombre del archivo PDF que generó este documento |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Obtiene o establece un indicador que especifica si se debe cambiar el tamaño de la ventana del documento para que se ajuste a la primera página mostrada. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | IDocumentFontUtilities instancia |
| [Form](../../aspose.pdf/document/form) { get; } | Obtiene Acro Form del documento. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Lanzar excepción si el documento se guardará con cambios y tendrá firma |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Obtiene o establece un indicador que especifica si la barra de menú debe ocultarse cuando el documento está activo. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Obtiene o establece un indicador que especifica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Obtiene o establece un indicador que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| [Id](../../aspose.pdf/document/id) { get; } | Obtiene el ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Obtiene o establece el indicador de ignorar errores en los archivos de origen. Cuando las páginas del documento de origen se copian en el documento de destino, el proceso de copia se detiene con la excepción si algunos objetos en los archivos de origen están dañados cuando este indicador es falso. ejemplo: dest.Pages.Add(src.Pages); Si este indicador se establece en verdadero, los objetos dañados se reemplazarán con valores vacíos. De forma predeterminada: verdadero. |
| [Info](../../aspose.pdf/document/info) { get; } | Obtiene la información del documento. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Obtiene el estado cifrado del documento. Verdadero si el documento está encriptado. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Obtiene o establece un valor que indica si el documento está linealizado. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | Obtiene el documento compatible con pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | Obtiene el documento compatible con pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | Obtiene o establece si el documento es compatible con pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Colección de JavaScript de nivel de documento. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Obtiene la estructura lógica del documento. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Metadatos del documento. (Un documento PDF puede incluir información general, como el título del documento, el autor y las fechas de creación y modificación. Esta información global sobre el documento (a diferencia de su contenido o estructura) se denomina metadatos y se destinado a ayudar en la catalogación y búsqueda de documentos en bases de datos externas.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Colección de destino designado en el documento. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Obtiene o establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Obtiene o establece la acción realizada en la apertura del documento. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Obtiene o establece el indicador de optimización. Cuando se agregan páginas al documento, los flujos de recursos iguales en el archivo resultante se fusionan en un objeto PDF si se establece esta marca. Esto permite disminuir el tamaño del archivo resultante, pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: falso. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Obtiene los contornos del documento. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Obtiene o establece la información de la página (solo para el generador) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Obtiene etiquetas de página en el documento. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Obtiene o establece el diseño de página que se utilizará cuando se abra el documento. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Obtiene o establece el modo de página, especificando cómo se debe mostrar el documento cuando se abre. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Obtiene o establece la colección de páginas del documento. Tenga en cuenta que las páginas están numeradas desde 1 en la colección. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | Obtiene formato PDF |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Obtiene los permisos del documento. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | Obtiene acceso al contenido de TaggedPdf. |
| [Version](../../aspose.pdf/document/version) { get; } | Obtiene una versión de Pdf del encabezado del archivo Pdf. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Obtiene el estado de licencia del sistema. Devuelve verdadero si el sistema funciona en modo con licencia y falso en caso contrario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | Vincular xml a documento |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | Vincular xml a documento |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | Vincular xml/xsl a documento |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | Vincular xml/xsl a documento |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | Vincular xml/xsl a documento |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Cambia las contraseñas de los documentos. Esta acción solo se puede realizar con la contraseña de propietario. |
| [Check](../../aspose.pdf/document/check)(bool) | Valida documento. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Convierte el documento y guarda los errores en el archivo especificado. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Convertir documento utilizando opciones de conversión especificadas |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Convierta el documento y guarde los errores en la secuencia especificada. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Convierte el documento y guarda los errores en el archivo especificado. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Convertir documento aplicando Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Convertir documento aplicando Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convierte el documento y guarda los errores en el archivo especificado. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convierte el documento y guarda los errores en el archivo especificado. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | Convertir página a PNG para flujo de imágenes DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Descifra el documento. Llame y luego guarde para obtener la versión descifrada del documento. |
| [Dispose](../../aspose.pdf/document/dispose)() | Cierra todos los recursos usados por este documento. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Cifra el documento. Llame y luego guarde para obtener la versión encriptada del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Cifra el documento. Llame y luego guarde para obtener la versión encriptada del documento. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Cifra el documento. Llame y luego guarde para obtener la versión encriptada del documento. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Exportar todas las anotaciones del documento a stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Exporta todas las anotaciones del documento a un archivo XFDF |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Borra la memoria |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Devuelve el valor del artículo del diccionario del catálogo. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Obtiene un objeto con la ID especificada en el documento. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | Obtener metadatos XMP del documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importa anotaciones de flujo a documento. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importa anotaciones del archivo XFDF al documento. |
| [Optimize](../../aspose.pdf/document/optimize)() | Linealizar el documento para : abrir la primera página lo más rápido posible; : mostrar la página siguiente o seguir por enlace a la página siguiente lo más rápido posible; : mostrar la página de forma incremental a medida que llega cuando se entregan los datos de una página a través de un canal lento (muestra primero los datos más útiles); : permite que la interacción del usuario, como seguir un enlace, se realice incluso antes de que se haya recibido y mostrado toda la página. Invocar este método en realidad no guarda el documento . Por el contrario, el documento solo está preparado para tener una estructura optimizada, llame y luego Guardar para obtener el documento optimizado. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Optimizar recursos en el documento: 1. Los recursos que no se utilizan en las páginas del documento se eliminan; 2. Los recursos iguales se unen en un objeto; 3. Los objetos no utilizados se eliminan. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Optimizar recursos en el documento según la estrategia de optimización definida. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Procesar párrafos para generador. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Elimina los metadatos del documento. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | Eliminar el cumplimiento de pdfa del documento |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | Eliminar el cumplimiento de pdfUa del documento |
| [Repair](../../aspose.pdf/document/repair)() | Repara documento roto. |
| [Save](../../aspose.pdf/document/save#save)() | Guarde el documento de forma incremental (es decir, utilizando la técnica de actualización incremental). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Guarda el documento con opciones de guardado. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Almacena el documento en stream. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Guarda el documento en el archivo especificado. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Guarda el documento en una secuencia con opciones de guardado. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Guarda el documento con un nuevo nombre configurando sus opciones de guardado. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Guarda el documento en un flujo de respuesta con opciones de guardado. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Guardar documento en XML. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Envía el documento completo al dispositivo de documentos para su procesamiento. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Envía el documento completo al dispositivo de documentos para su procesamiento. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Envía determinadas páginas del documento al dispositivo de documentos para su procesamiento. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Envía el documento completo al dispositivo de documentos para su procesamiento. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Establecer título para documento PDF |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | Establecer metadatos XMP del documento. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Validar documento en el archivo especificado. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Validar documento en el archivo especificado. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Validar documento en el archivo especificado. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Convierte flujo en formato de origen en flujo en formato de destino. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Convierte el flujo en formato de origen en un archivo de destino en formato de destino. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Convierte el archivo de origen en formato de origen en flujo en formato de destino. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Convierte el archivo de origen en formato de origen en un archivo de destino en formato de destino. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | El procedimiento de devolución de llamada para reconocimiento de hocr. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | Representa el método que manejará el evento FontSubstitution. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Tiene funcionalidad para ajustar fuentes |

### Ver también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
