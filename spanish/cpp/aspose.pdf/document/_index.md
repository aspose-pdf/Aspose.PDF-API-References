---
title: "Clase Aspose::Pdf::Document"
linktitle: "Document"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Document. Clase que representa un documento PDF en C++."
type: docs
weight: 3900
url: /es/cpp/aspose.pdf/document/
---
## Document class


Clase que representa un documento PDF.

```cpp
class Document : public System::IDisposable,
                 public Aspose::Pdf::ISupportsMemoryCleanup,
                 public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Nested classes

* Class [IDocumentFontUtilities](./idocumentfontutilities/)
* Class [MergeOptions](./mergeoptions/)
* Class [OptimizationOptions](./optimizationoptions/)
* Class [RepairOptions](./repairoptions/)
## Métodos

| Método | Descripción |
| --- | --- |
| [BindXml](./bindxml/)(System::String) | Vincula xml al documento. |
| [BindXml](./bindxml/)(const System::String\&, const System::String\&) | Vincula xml/xsl al documento. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Vincula xml/xsl al documento. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Xml::XmlReaderSettings\>\&) | Vincula xml/xsl al documento. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Vincula xml al documento. |
| [ChangePasswords](./changepasswords/)(const System::String\&, const System::String\&, const System::String\&) | Cambia las contraseñas del documento. Esta acción solo se puede realizar usando la contraseña del propietario. |
| [Check](./check/)(bool) | Valida el documento. |
| [Convert](./convert/)(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convierte el documento y guarda los errores en el archivo especificado. |
| [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convierte el documento y guarda los errores en el archivo especificado. |
| [Convert](./convert/)(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Convierte el documento y guarda los errores en el archivo especificado. |
| [Convert](./convert/)(const System::SharedPtr\<PdfFormatConversionOptions\>\&) | Convierte el documento usando las opciones de conversión especificadas. |
| [Convert](./convert/)(Document::CallBackGetHocrWithPage, bool) | Reconoce imágenes dentro del documento y agrega cadenas hocr sobre él. |
| [Convert](./convert/)(Document::CallBackGetHocr, bool) | Reconoce imágenes dentro del documento y agrega cadenas hocr sobre él. |
| [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Convierte el documento y guarda los errores en el flujo especificado. |
| [Convert](./convert/)(Fixup, const System::SharedPtr\<System::IO::Stream\>\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Convierte el documento aplicando el [Fixup](../fixup/). |
| [Convert](./convert/)(Fixup, const System::String\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Convierte el documento aplicando el [Fixup](../fixup/). |
| static [Convert](./convert/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) | Convierte el archivo de origen en formato origen al archivo de destino en formato destino. |
| static [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) | Convierte el flujo en formato origen al archivo de destino en formato destino. |
| static [Convert](./convert/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) | Convierte el archivo de origen en formato origen al flujo en formato destino. |
| static [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) | Convierte el flujo en formato origen al flujo en formato destino. |
| [ConvertPageToPNGMemoryStream](./convertpagetopngmemorystream/)(const System::SharedPtr\<Page\>\&) | Convierte la página a PNG para el flujo de imágenes DSR, OMR, OCR. |
| [Decrypt](./decrypt/)() | Desencripta el documento. Llama a Save después para obtener la versión desencriptada del documento. |
| [Dispose](./dispose/)() override | Cierra todos los recursos utilizados por este documento. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) | Inicializa una nueva instancia de la clase [Document](./) para trabajar con un documento encriptado. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) | Inicializa una nueva instancia de la clase [Document](./) para trabajar con un documento encriptado. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Inicializa una nueva instancia de [Document](./) a partir del flujo *input*. |
| [Document](./document/)(const System::String\&) | Simplemente inicializa [Document](./) usando *filename*. Lo mismo que [Document(Stream)](../). |
| [Document](./document/)(const System::String\&, bool) | Simplemente inicializa [Document](./) usando *filename*. Lo mismo que [Document(Stream)](../). |
| [Document](./document/)(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Inicializa una nueva instancia de la clase [Document](./) para trabajar con un documento encriptado. |
| [Document](./document/)(const System::String\&, const System::String\&) | Inicializa una nueva instancia de la clase [Document](./) para trabajar con un documento encriptado. |
| [Document](./document/)(const System::String\&, const System::String\&, bool) | Inicializa una nueva instancia de la clase [Document](./) para trabajar con un documento encriptado. |
| [Document](./document/)(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Inicializa una nueva instancia de la clase [Document](./) para trabajar con un documento encriptado. |
| [Document](./document/)() | Inicializa un documento vacío. |
| [Document](./document/)(PdfVersion) | Inicializa un documento vacío por versión. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Abre un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento pdf. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) | Abre un documento existente desde un flujo proporcionando la conversión necesaria para obtener un documento pdf. |
| [Encrypt](./encrypt/)(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\&) | Encripta el documento. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Encripta el documento. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Encripta el documento. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm, bool) | Encripta el documento. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) | Encripta el documento. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) | Encripta el documento. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::String\&) | Exporta todas las anotaciones del documento a un archivo XFDF. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporta todas las anotaciones del documento a un flujo. |
| [Flatten](./flatten/)() | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| [Flatten](./flatten/)(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) | Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar. |
| [FlattenTransparency](./flattentransparency/)() | Reemplaza el contenido transparente con gráficos raster y vectoriales no transparentes. |
| [FreeMemory](./freememory/)() override | Limpia la memoria. |
| [get_Actions](./get_actions/)() | Obtiene las acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones como BeforClosing, BeforSaving, etc. |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() | Permite combinar el contenido de las páginas para optimizar el tamaño del documento. Si se usa, entonces páginas diferentes pero duplicadas pueden referenciar al mismo objeto de contenido. Tenga en cuenta que este modo puede causar efectos secundarios, como cambiar el contenido de una página cuando se modifica otra página. |
| [get_Background](./get_background/)() | Obtiene el color de fondo del documento. |
| [get_CenterWindow](./get_centerwindow/)() | Obtiene la bandera que indica si la posición de la ventana del documento se centrará en la pantalla. |
| [get_Collection](./get_collection/)() | Obtiene la colección del documento. |
| [get_CryptoAlgorithm](./get_cryptoalgorithm/)() | Obtiene la configuración de seguridad si el documento está cifrado. Si el documento no está cifrado, entonces se lanzará la excepción correspondiente en .net 1.1 o [CryptoAlgorithm](../cryptoalgorithm/) será nulo para otras versiones de .net. |
| [get_CustomSecurityHandler](./get_customsecurityhandler/)() const | Obtiene un manejador de seguridad personalizado. |
| [get_Destinations](./get_destinations/)() | Obtiene la colección de destinos. Obsoleto. Por favor, use NamedDestinations. |
| [get_Direction](./get_direction/)() | Obtiene el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Muchas operaciones con fuentes no pueden ejecutarse si están prohibidas por la licencia de esa fuente. Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación para esa fuente. Esta bandera se utiliza para desactivar cualquier restricción de licencia para todas las fuentes en el documento PDF actual. Tenga cuidado al usar esta bandera. Cuando está activada, significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. Por defecto, false. |
| [get_DisplayDocTitle](./get_displaydoctitle/)() | Obtiene la bandera que indica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [get_Duplex](./get_duplex/)() | Obtiene la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [get_EmbeddedFiles](./get_embeddedfiles/)() | Obtiene la colección de archivos incrustados en el documento. |
| [get_EmbedStandardFonts](./get_embedstandardfonts/)() const | Propiedad que declara que el documento debe incrustar todas las fuentes estándar Type1 que tengan la bandera IsEmbedded establecida en true. Todas las fuentes PDF pueden incrustarse en el documento simplemente configurando la bandera IsEmbedded en true, pero las fuentes estándar Type1 del PDF son una excepción a esta regla. La incrustación de fuentes Type1 estándar requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer la bandera IsEmbedded en true para la fuente especificada, sino también establecer una bandera adicional a nivel del documento: EmbedStandardFonts = true; Esta propiedad solo puede establecerse una vez para todas las fuentes. Por defecto, false. |
| [get_EnableNotificationLogging](./get_enablenotificationlogging/)() const | Obtiene un valor que indica si se debe habilitar el registro de notificaciones. |
| [get_EnableObjectUnload](./get_enableobjectunload/)() | Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria. Esto permite reducir el uso de memoria pero puede tener un efecto negativo en el rendimiento. |
| [get_EnableSignatureSanitization](./get_enablesignaturesanitization/)() const | Obtiene la bandera para gestionar la sanitización de los campos de firma. Habilitado por defecto. |
| [get_FileName](./get_filename/)() | Nombre del archivo PDF que causó este documento. |
| static [get_FileSizeLimitToMemoryLoading](./get_filesizelimittomemoryloading/)() | Obtenga y establezca el límite de tamaño de archivo para cargar un archivo completo en memoria. El valor se establece en megabytes. El valor predeterminado es 210 Mb. |
| [get_FitWindow](./get_fitwindow/)() | Obtiene la bandera que indica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
| [get_FontUtilities](./get_fontutilities/)() | Instancia de [IDocumentFontUtilities](./idocumentfontutilities/). |
| [get_Form](./get_form/)() | Obtiene el Acro Form del documento. |
| [get_HandleSignatureChange](./get_handlesignaturechange/)() const | Lanza una excepción si el documento se guarda con cambios y tiene una firma. |
| [get_HideMenubar](./get_hidemenubar/)() | Obtiene la bandera que indica si la barra de menús debe ocultarse cuando el documento está activo. |
| [get_HideToolBar](./get_hidetoolbar/)() | Obtiene la bandera que indica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| [get_HideWindowUI](./get_hidewindowui/)() | Obtiene la bandera que indica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| [get_Id](./get_id/)() | Obtiene el ID. |
| [get_IgnoreCorruptedObjects](./get_ignorecorruptedobjects/)() | Obtiene la bandera de ignorar errores en los archivos fuente. Cuando las páginas del documento fuente se copian al documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos fuente están corruptos cuando esta bandera es falsa. ejemplo: dest.Pages.Add(src.Pages); Si esta bandera se establece en true, los objetos corruptos se reemplazarán con valores vacíos. Por defecto: true. |
| [get_Info](./get_info/)() | Obtiene la información del documento. |
| [get_IsEncrypted](./get_isencrypted/)() | Obtiene el estado de cifrado del documento. True si el documento está cifrado. |
| static [get_IsLicensed](./get_islicensed/)() | Obtiene el estado de licencia del sistema. Devuelve true si el sistema funciona en modo con licencia y false en caso contrario. |
| [get_IsLinearized](./get_islinearized/)() | Obtiene un valor que indica si el documento está linealizado. |
| [get_IsPdfaCompliant](./get_ispdfacompliant/)() | Obtiene si el documento cumple con PDF/A. |
| [get_IsPdfUaCompliant](./get_ispdfuacompliant/)() | Obtiene si el documento cumple con PDF/UA. |
| [get_IsXrefGapsAllowed](./get_isxrefgapsallowed/)() | Obtiene si el documento cumple con PDF/A. |
| [get_JavaScript](./get_javascript/)() | [Collection](../collection/) de JavaScript a nivel de documento. |
| [get_LogicalStructure](./get_logicalstructure/)() | Obtiene la estructura lógica del documento. |
| [get_Metadata](./get_metadata/)() | [Document](./) metadatos. (Un documento PDF puede incluir información general, como el título del documento, el autor y las fechas de creación y modificación. Esa información global sobre el documento (a diferencia de su contenido o estructura) se llama metadatos y está destinada a ayudar en la catalogación y búsqueda de documentos en bases de datos externas.) |
| [get_NamedDestinations](./get_nameddestinations/)() | [Collection](../collection/) de Destinos nombrados en el documento. |
| [get_NonFullScreenPageMode](./get_nonfullscreenpagemode/)() | Obtiene el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [get_OpenAction](./get_openaction/)() | Obtiene la acción realizada al abrir el documento. |
| [get_OptimizeSize](./get_optimizesize/)() | Obtiene la bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se fusionan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [get_Outlines](./get_outlines/)() | Obtiene los contornos del documento. |
| [get_OutputIntents](./get_outputintents/)() | Obtiene la colección de intenciones de salida en el documento. |
| [get_PageInfo](./get_pageinfo/)() | Obtiene la información de la página. (solo para generador, no se rellena al leer el documento) |
| [get_PageLabels](./get_pagelabels/)() | Obtiene las etiquetas de página en el documento. |
| [get_PageLayout](./get_pagelayout/)() | Obtiene el diseño de página que se debe usar cuando se abre el documento. |
| [get_PageMode](./get_pagemode/)() | Obtiene el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
| [get_Pages](./get_pages/)() | Obtiene la colección de páginas del documento. [Note](../note/) que las páginas se numeran a partir de 1 en la colección. |
| [get_PdfFormat](./get_pdfformat/)() | Obtiene el formato PDF. |
| [get_Permissions](./get_permissions/)() | Obtiene los permisos del documento. |
| [get_PickTrayByPdfSize](./get_picktraybypdfsize/)() | Obtiene una bandera que especifica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada. |
| [get_PrintScaling](./get_printscaling/)() | Obtiene la opción de escalado de página que se debe seleccionar cuando se muestra un cuadro de diálogo de impresión para este documento. |
| [get_TaggedContent](./get_taggedcontent/)() |  |
| [get_Version](./get_version/)() | Obtiene una versión de [Pdf](../) del encabezado del archivo [Pdf](../). |
| [GetCatalogValue](./getcatalogvalue/)(const System::String\&) | Devuelve el valor del elemento del diccionario del catálogo. |
| [GetObjectById](./getobjectbyid/)(const System::String\&) | Obtiene un objeto con el ID especificado en el documento. |
| [GetXmpMetadata](./getxmpmetadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Obtiene los metadatos XMP del documento. |
| [HasIncrementalUpdate](./hasincrementalupdate/)() | Comprueba si el documento PDF actual se ha guardado con actualizaciones incrementales. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::String\&) | Importa anotaciones desde un archivo XFDF al documento. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa anotaciones desde un flujo al documento. |
| [IsRepairNeeded](./isrepairneeded/)(System::SharedPtr\<Document::RepairOptions\>\&) | Comprueba si el documento requiere la llamada al método Repair. |
| [LoadFrom](./loadfrom/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Carga un archivo, convirtiéndolo a PDF. |
| [Merge](./merge/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Fusiona documentos. |
| [Merge](./merge/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::String\>\&) | Fusiona documentos. |
| [Merge](./merge/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Fusiona documentos. |
| [Merge](./merge/)(const System::ArrayPtr\<System::String\>\&) | Fusiona archivos pdf. |
| static [MergeDocuments](./mergedocuments/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::String\>\&) | Fusiona documentos. |
| static [MergeDocuments](./mergedocuments/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Fusiona documentos. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::String\>\&) | Fusiona archivos pdf. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Fusiona documentos. |
| [Optimize](./optimize/)() | Linealiza el documento con el objetivo de. |
| [OptimizeResources](./optimizeresources/)() | Optimiza los recursos en el documento: |
| [OptimizeResources](./optimizeresources/)(const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\&) | Optimiza los recursos en el documento según la estrategia de optimización definida. |
| [PageNodesToBalancedTree](./pagenodestobalancedtree/)(uint8_t) | Organiza los nodos del árbol de páginas en un documento en un árbol equilibrado. Solo si el documento tiene más de nodesNumInSubtrees objetos de página, de lo contrario no hace nada. No llame a este método mientras itera sobre los elementos Pages, ya que puede producir resultados impredecibles. |
| [ProcessParagraphs](./processparagraphs/)() | Procesa párrafos para el generador. |
| [RemoveMetadata](./removemetadata/)() | Elimina los metadatos del documento. |
| [RemovePdfaCompliance](./removepdfacompliance/)() | Elimina el cumplimiento pdfa del documento. |
| [RemovePdfUaCompliance](./removepdfuacompliance/)() | Elimina el cumplimiento pdfUa del documento. |
| [Repair](./repair/)(System::SharedPtr\<Document::RepairOptions\>) | Repara el documento dañado. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Almacena el documento en un flujo. |
| [Save](./save/)(const System::String\&) | Guarda el documento en el archivo especificado. |
| [Save](./save/)() | Guarda el documento de forma incremental (es decir, usando la técnica de actualización incremental). |
| [Save](./save/)(const System::SharedPtr\<SaveOptions\>\&) | Guarda el documento con opciones de guardado. |
| [Save](./save/)(const System::String\&, SaveFormat) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) | Guarda el documento con un nuevo nombre junto con un formato de archivo. |
| [Save](./save/)(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) | Guarda el documento con un nuevo nombre estableciendo sus opciones de guardado. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) | Guarda el documento en un flujo con opciones de guardado. |
| [Save](./save/)(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) | Guarda el documento en un flujo de respuesta con opciones de guardado. |
| [SaveXml](./savexml/)(System::String) | Guardar documento en XML. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) | Envía ciertas páginas del documento al dispositivo de documento para su procesamiento. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Permite combinar el contenido de las páginas para optimizar el tamaño del documento. Si se usa, entonces páginas diferentes pero duplicadas pueden referenciar al mismo objeto de contenido. Tenga en cuenta que este modo puede causar efectos secundarios, como cambiar el contenido de una página cuando se modifica otra página. |
| [set_Background](./set_background/)(const System::SharedPtr\<Color\>\&) | Establece el color de fondo del documento. |
| [set_CenterWindow](./set_centerwindow/)(bool) | Establece una bandera que indica si la posición de la ventana del documento se centrará en la pantalla. |
| [set_Collection](./set_collection/)(const System::SharedPtr\<Aspose::Pdf::Collection\>\&) | Obtiene la colección del documento. |
| [set_Direction](./set_direction/)(Aspose::Pdf::Direction) | Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Muchas operaciones con fuentes no pueden ejecutarse si están prohibidas por la licencia de esa fuente. Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación para esa fuente. Esta bandera se utiliza para desactivar cualquier restricción de licencia para todas las fuentes en el documento PDF actual. Tenga cuidado al usar esta bandera. Cuando está activada, significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. Por defecto, false. |
| [set_DisplayDocTitle](./set_displaydoctitle/)(bool) | Establece una bandera que indica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [set_Duplex](./set_duplex/)(PrintDuplex) | Establece la opción de manejo del modo dúplex de impresión a usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [set_EmbedStandardFonts](./set_embedstandardfonts/)(bool) | Propiedad que declara que el documento debe incrustar todas las fuentes estándar Type1 que tengan la bandera IsEmbedded establecida en true. Todas las fuentes PDF pueden incrustarse en el documento simplemente configurando la bandera IsEmbedded en true, pero las fuentes estándar Type1 del PDF son una excepción a esta regla. La incrustación de fuentes Type1 estándar requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer la bandera IsEmbedded en true para la fuente especificada, sino también establecer una bandera adicional a nivel del documento: EmbedStandardFonts = true; Esta propiedad solo puede establecerse una vez para todas las fuentes. Por defecto, false. |
| [set_EnableNotificationLogging](./set_enablenotificationlogging/)(bool) | Establece un valor que indica si se debe habilitar el registro de notificaciones. |
| [set_EnableObjectUnload](./set_enableobjectunload/)(bool) | Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria. Esto permite reducir el uso de memoria pero puede tener un efecto negativo en el rendimiento. |
| [set_EnableSignatureSanitization](./set_enablesignaturesanitization/)(bool) | Establece una bandera para gestionar la sanitización de campos de firma. Habilitado por defecto. |
| static [set_FileSizeLimitToMemoryLoading](./set_filesizelimittomemoryloading/)(int32_t) | Obtenga y establezca el límite de tamaño de archivo para cargar un archivo completo en memoria. El valor se establece en megabytes. El valor predeterminado es 210 Mb. |
| [set_FitWindow](./set_fitwindow/)(bool) | Establece una bandera que indica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
| [set_HandleSignatureChange](./set_handlesignaturechange/)(bool) | Lanza una excepción si el documento se guarda con cambios y tiene una firma. |
| [set_HideMenubar](./set_hidemenubar/)(bool) | Establece una bandera que indica si la barra de menús debe ocultarse cuando el documento está activo. |
| [set_HideToolBar](./set_hidetoolbar/)(bool) | Establece una bandera que indica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| [set_HideWindowUI](./set_hidewindowui/)(bool) | Establece una bandera que indica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| [set_IgnoreCorruptedObjects](./set_ignorecorruptedobjects/)(bool) | Establece una bandera para ignorar errores en archivos fuente. Cuando las páginas del documento fuente se copian al documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos fuente están corruptos y esta bandera es falsa. ejemplo: dest.Pages.Add(src.Pages); Si esta bandera se establece en verdadero, los objetos corruptos se reemplazarán por valores vacíos. Por defecto: true. |
| [set_IsLinearized](./set_islinearized/)(bool) | Establece un valor que indica si el documento está linealizado. |
| [set_IsXrefGapsAllowed](./set_isxrefgapsallowed/)(bool) | Establece si el documento cumple con PDF/A. |
| [set_NonFullScreenPageMode](./set_nonfullscreenpagemode/)(Aspose::Pdf::PageMode) | Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [set_OpenAction](./set_openaction/)(const System::SharedPtr\<Annotations::IAppointment\>\&) | Establece la acción que se realiza al abrir el documento. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Establece una bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se combinan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Establece la información de página. (solo para generador, no se llena al leer el documento) |
| [set_PageLayout](./set_pagelayout/)(Aspose::Pdf::PageLayout) | Establece el diseño de página que se usará cuando se abra el documento. |
| [set_PageMode](./set_pagemode/)(Aspose::Pdf::PageMode) | Establece el modo de página, especificando cómo se debe mostrar el documento al abrirse. |
| [set_PickTrayByPdfSize](./set_picktraybypdfsize/)(bool) | Establece una bandera que indica si se debe usar el tamaño de página PDF para seleccionar la bandeja de papel de entrada. |
| [set_PrintScaling](./set_printscaling/)(Aspose::Pdf::PrintScaling) | Establece la opción de escalado de página que se seleccionará cuando se muestre un cuadro de diálogo de impresión para este documento. |
| static [SetDefaultFileSizeLimitToMemoryLoading](./setdefaultfilesizelimittomemoryloading/)() | Establece el límite de tamaño de archivo para cargar un archivo completo en memoria al valor predeterminado, que es 210 Mb. |
| [SetTitle](./settitle/)(const System::String\&) | Establecer título para [Pdf](../)[Document](./). |
| [SetXmpMetadata](./setxmpmetadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establecer los metadatos XMP del documento. |
| [Validate](./validate/)(const System::String\&, Aspose::Pdf::PdfFormat) | Validar el documento en el archivo especificado. |
| [Validate](./validate/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) | Validar el documento en el archivo especificado. |
| [Validate](./validate/)(const System::SharedPtr\<PdfFormatConversionOptions\>\&) | Validar el documento en el archivo especificado. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultNodesNumInSubtrees](./defaultnodesnuminsubtrees/) |  |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [CallBackGetHocr](./callbackgethocr/) | El procedimiento de devolución de llamada para el reconocimiento hocr. |
| [CallBackGetHocrWithPage](./callbackgethocrwithpage/) | El procedimiento de devolución de llamada para el reconocimiento hocr. |
| [FontSubstitutionHandler](./fontsubstitutionhandler/) | Representa el método que manejará el evento FontSubstitution. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
