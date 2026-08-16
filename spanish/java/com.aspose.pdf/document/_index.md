---
title: "Documento"
linktitle: "Documento"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un documento PDF."
type: docs
weight: 1060
url: /es/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

Clase que representa un documento PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Ocurre cuando una fuente reemplaza a otra fuente en el documento. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Document](#Document--) | Inicializa un documento vacío. |
| [Document](#Document-byte:A-) | Inicializa una nueva instancia de Document a partir del arreglo de bytes {@code input}. |
| [Document](#Document-java.io.InputStream-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-boolean-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-java.lang.String-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa un documento vacío. |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa un documento vacío. |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | Inicializa un documento vacío. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | Inicializa un documento vacío. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | Inicializa un documento vacío. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Inicializa un documento vacío. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa un documento vacío. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-boolean-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-java.lang.String-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa un documento vacío. |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa un documento vacío. |

## Métodos

| Método | Descripción |
| --- | --- |
| [afterImport](#afterImport--) | Enumere todas las anotaciones registradas y llame a AfterImport para cada una de ellas. |
| [bindXml](#bindXml-java.io.InputStream-) | Vincular xml al documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Vincular xml/xsl al documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Vincular xml/xsl al documento |
| [bindXml](#bindXml-java.lang.String-) | Vincular xml al documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Vincular xml/xsl al documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Cambia las contraseñas del documento. Esta acción solo se puede realizar usando la contraseña del propietario. |
| [check](#check-boolean-) | Valida el documento. |
| [close](#close--) | Cierra todos los recursos utilizados por este documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Reconoce imágenes dentro del documento y agrega cadenas hocr sobre él. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Convierte el documento aplicando el Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Convierte el documento aplicando el Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Convierte el documento aplicando el Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Convierte el documento aplicando el Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Convierte el flujo del formato de origen al formato de destino. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Convierte el flujo del formato de origen en un archivo de destino en el formato de destino. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convierte el documento y guarda los errores en el flujo especificado. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convertir el documento usando opciones de conversión especificadas |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Convierte el archivo de origen del formato de origen en un flujo del formato de destino. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Convierte el archivo de origen del formato de origen en un archivo de destino en el formato de destino. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convierte el documento y guarda los errores en el flujo especificado. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Convierte la página a PNG para el flujo de imagen DSR, OMR, OCR. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos. |
| [decrypt](#decrypt--) | Descifra el documento. Luego llama a Save para obtener la versión descifrada del documento. |
| [dispose](#dispose--) | Cierra todos los recursos utilizados por este documento. Este método está obsoleto, usa close() en su lugar. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Encripta el documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Cifra el documento. Luego llama a Save para obtener la versión cifrada del documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Encripta el documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Cifra el documento. Luego llama a Save para obtener la versión cifrada del documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Cifra el documento. Luego llama a Save para obtener la versión cifrada del documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Encripta el documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporta todas las anotaciones del documento al flujo. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporta todas las anotaciones del documento a un archivo XFDF |
| [flatten](#flatten--) | Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar. |
| [flattenTransparency](#flattenTransparency--) | Reemplaza el contenido transparente con gráficos raster y vectoriales no transparentes. |
| [freeMemory](#freeMemory--) | Limpia la memoria |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Notificación sobre fuentes faltantes al procesar documentos. |
| [getActions](#getActions--) | <p> Obtiene acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones BeforClosing, BeforSaving, etc. </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Permite combinar el contenido de las páginas para optimizar el tamaño del documento. |
| [getBackground](#getBackground--) | Obtiene el color de fondo del documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Devuelve el valor del elemento del diccionario del catálogo. |
| [getCollection](#getCollection--) | Obtiene la colección del documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtiene la configuración de seguridad si el documento está cifrado. Si el documento no está cifrado, entonces se lanzará la excepción correspondiente en .net 1.1 o CryptoAlgorithm será nulo para otras versiones de .net. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtiene un controlador de seguridad personalizado. |
| [getDefaultCopier](#getDefaultCopier--) | Devuelve el copiado usado para copiar páginas a este documento. |
| [getDestinations](#getDestinations--) | Obtiene la colección de destinos. |
| [getDirection](#getDirection--) | Obtiene el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [getDuplex](#getDuplex--) | Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtiene la colección de archivos incrustados en el documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtiene o establece el indicador para gestionar la sanitización de campos de firma. |
| [getEngineDoc](#getEngineDoc--) | Instancia de IPdfDocument usada para acceder a la estructura interna del documento. Solo interno |
| [getFileName](#getFileName--) | Nombre del archivo PDF que causó este documento |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Obtén y establece el límite de tamaño de archivo para cargar un archivo completo en memoria. |
| [getFontUtilities](#getFontUtilities--) | Instancia de IDocumentFontUtilities |
| [getForm](#getForm--) | Obtiene el Acro Form del documento. |
| [getId](#getId--) | Obtiene el ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtiene o establece la bandera de ignorar errores en los archivos de origen. Cuando las páginas del documento de origen se copian al documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos de origen están corruptos cuando esta bandera es falsa. ejemplo: dest.Pages.Add(src.Pages); Si esta bandera se establece en true, los objetos corruptos se reemplazarán con valores vacíos. Por defecto: true. |
| [getInfo](#getInfo--) | Obtiene la información del documento. |
| [getJavaScript](#getJavaScript--) | Colección de JavaScript a nivel de documento. |
| [getLogicalStructure](#getLogicalStructure--) | Obtiene la estructura lógica del documento. |
| [getMetadata](#getMetadata--) | Metadatos del documento. (Un documento PDF puede incluir información general, como el título del documento, el autor y las fechas de creación y modificación. Esta información global sobre el documento (en contraposición a su contenido o estructura) se llama metadatos y tiene como objetivo ayudar en la catalogación y búsqueda de documentos en bases de datos externas.) |
| [getMetadataStream](#getMetadataStream--) | Devuelve el flujo de metadatos sin procesar |
| [getNamedDestinations](#getNamedDestinations--) | Colección de Destinos nombrados en el documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtiene el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtiene un objeto con el ID especificado en el documento. |
| [getOpenAction](#getOpenAction--) | <p> Obtiene la acción realizada al abrir el documento. </p> <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | Obtiene la bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se combinan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [getOutlines](#getOutlines--) | Obtiene los contornos del documento. |
| [getOutputIntents](#getOutputIntents--) | Obtiene la colección de intenciones de salida en el documento. |
| [getPageInfo](#getPageInfo--) | Obtiene la información de la página.(solo para generador, no se completa al leer el documento) |
| [getPageLabels](#getPageLabels--) | Obtiene las etiquetas de página en el documento. |
| [getPageLayout](#getPageLayout--) | Obtiene el diseño de página que se utilizará cuando se abra el documento. |
| [getPageMode](#getPageMode--) | Obtiene el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
| [getPages](#getPages--) | <p> Obtiene la colección de páginas del documento. Note que las páginas se numeran a partir de 1 en la colección. </p> |
| [getPdfFormat](#getPdfFormat--) | Obtiene el formato PDF/A |
| [getPermissions](#getPermissions--) | Obtiene los permisos del documento. |
| [getPrintScaling](#getPrintScaling--) | Obtiene la opción de manejo de escala de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [getTaggedContent](#getTaggedContent--) | Obtiene acceso al contenido TaggedPdf. El ejemplo muestra cómo usar contenido etiquetado para crear un nuevo documento con encabezado, párrafos e imágenes. // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage("en-US"); // Set title for PDF document taggedContent.setTitle("Example document"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("The Header"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("The text of paragraph."); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figure 1"); figure1.setTitle("Image 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Save document document.save("example.pdf"); |
| [getVersion](#getVersion--) | Obtiene una versión de PDF del encabezado del archivo PDF. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtener metadatos XMP del documento. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Comprueba si el documento PDF actual se ha guardado con actualizaciones incrementales. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importa anotaciones desde el flujo al documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa anotaciones del archivo XFDF al documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Bandera que indica la sustitución de fuentes faltantes. |
| [isCenterWindow](#isCenterWindow--) | <p> Obtiene la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla. </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> Obtiene la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Obtiene o establece un valor que indica si se debe habilitar el registro de notificaciones. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria. |
| [isEncrypted](#isEncrypted--) | Obtiene el estado de cifrado del documento. Verdadero si el documento está cifrado. |
| [isFitWindow](#isFitWindow--) | <p> Obtiene la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Lanza una excepción si el documento se guarda con cambios y tiene firma |
| [isHideMenubar](#isHideMenubar--) | <p> Obtiene la bandera que especifica si la barra de menús debe ocultarse cuando el documento está activo. </p> |
| [isHideToolBar](#isHideToolBar--) | <p> Obtiene la bandera que especifica si la barra de herramientas debe ocultarse cuando el documento está activo. </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> Obtiene la bandera que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. </p> |
| [isLicensed](#isLicensed--) | Obtiene el estado de licencia del sistema. |
| [isLinearized](#isLinearized--) | Obtiene un valor que indica si el documento está linealizado. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después de que se llame al método save si este parámetro ManualDispose está habilitado. |
| [isPdfaCompliant](#isPdfaCompliant--) | Obtiene si el documento es compatible con PDF/A. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Obtiene si el documento es compatible con pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Obtiene una bandera que indica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Comprueba si el documento requiere una llamada al método Repair. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Por defecto, el proceso de validación PDF/A es necesario para actualizar o eliminar datos compatibles con PDF/A si se violaron algunas reglas. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Obtiene o establece si el documento es compatible con pdfa. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Carga un archivo, convirtiéndolo a PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Fusiona documentos. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Fusiona documentos. |
| [merge](#merge-com.aspose.pdf.Document...-) | Fusiona documentos. |
| [merge](#merge-java.lang.String...-) | Fusiona archivos PDF. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Fusiona documentos. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Fusiona documentos. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Fusiona documentos. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Fusiona archivos PDF. |
| [optimize](#optimize--) | Linealiza el documento con el fin de - abrir la primera página lo más rápido posible; - mostrar la página siguiente o seguir el enlace a la página siguiente lo más rápido posible; - mostrar la página de forma incremental a medida que llega, cuando los datos de una página se entregan a través de un canal lento (mostrar primero los datos más útiles); - permitir que la interacción del usuario, como seguir un enlace, se realice incluso antes de que se haya recibido y mostrado la página completa. Invocar este método no guarda realmente el documento. Por el contrario, el documento solo se prepara para tener una estructura optimizada; luego llame a Save para obtener el documento optimizado. |
| [optimizeResources](#optimizeResources--) | Optimiza los recursos en el documento: 1. Los recursos que no se utilizan en las páginas del documento se eliminan; 2. Los recursos iguales se combinan en un solo objeto; 3. Los objetos no utilizados se borran. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimiza los recursos en el documento: 1. Los recursos que no se utilizan en las páginas del documento se eliminan; 2. Los recursos iguales se combinan en un solo objeto; 3. Los objetos no utilizados se borran. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. Solo si el documento tiene más objetos de página que nodesNumInSubtrees, de lo contrario no hace nada. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. Solo si el documento tiene más objetos de página que nodesNumInSubtrees, de lo contrario no hace nada. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Método interno |
| [processParagraphs](#processParagraphs--) | Almacena el documento en un flujo. |
| [removeMetadata](#removeMetadata--) | Elimina los metadatos del documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Elimina la compatibilidad pdfa del documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Elimina la compatibilidad pdfUa del documento |
| [repair](#repair--) | Repara el documento dañado. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Repara el documento dañado. |
| [resumeUpdate](#resumeUpdate--) | reanuda la actualización del documento |
| [save](#save--) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-java.io.OutputStream-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-java.lang.String-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Guarda de forma incremental el Documento PDF en el flujo especificado. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Guarda de forma incremental el Documento PDF en el flujo especificado. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Guarda de forma incremental el Documento PDF en el flujo especificado. |
| [saveXml](#saveXml-java.lang.String-) | Guardar documento en XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envía ciertas páginas del documento al dispositivo de documento para su procesamiento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notificación sobre fuentes faltantes al procesar documentos. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Estableciendo la bandera para establecer la fuente determinada por el programa en caso de ausencia de fuente. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Permite combinar el contenido de las páginas para optimizar el tamaño del documento. |
| [setBackground](#setBackground-java.awt.Color-) | Establece el color de fondo del documento. |
| [setCenterWindow](#setCenterWindow-boolean-) | Establece la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Establece la colección del documento. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Obtiene el parámetro de conversión para el convertidor pdf/ua (Convierte solo Metadatos y Catálogo del Documento si se establece en verdadero). |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Establece el límite de tamaño de archivo para cargar un archivo completo en memoria al valor predeterminado de 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Establece la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [setDuplex](#setDuplex-int-) | Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Obtiene o establece un valor que indica si se debe habilitar el registro de notificaciones. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Obtiene o establece el indicador para gestionar la sanitización de campos de firma. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Obtén y establece el límite de tamaño de archivo para cargar un archivo completo en memoria. |
| [setFitWindow](#setFitWindow-boolean-) | Establece la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Lanza una excepción si el documento se guarda con cambios y tiene firma |
| [setHideMenubar](#setHideMenubar-boolean-) | Establece la bandera que especifica si la barra de menú debe ocultarse cuando el documento está activo. |
| [setHideToolBar](#setHideToolBar-boolean-) | Establece la bandera que especifica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Establece la bandera que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Obtiene o establece la bandera de ignorar errores en los archivos de origen. Cuando las páginas del documento de origen se copian al documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos de origen están corruptos cuando esta bandera es falsa. ejemplo: dest.Pages.Add(src.Pages); Si esta bandera se establece en true, los objetos corruptos se reemplazarán con valores vacíos. Por defecto: true. |
| [setLinearized](#setLinearized-boolean-) | Establece un valor que indica si el documento está linealizado. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después de que se llame al método save si este parámetro ManualDispose está habilitado. Pero se recomienda encarecidamente llamar al método dispose cuando la instancia de Document ya no sea necesaria. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> Establece la acción que se ejecuta al abrir el documento. <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Establece la bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se combinan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante, pero puede provocar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Establece la información de la página (solo para generador, no se completa al leer el documento). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Establece el diseño de página que se utilizará cuando se abra el documento. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Establece una bandera que especifica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada. |
| [setPrintScaling](#setPrintScaling-int-) | Establece la opción de manejo de escalado de impresión que se usará al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Por defecto, el proceso de validación PDF/A es necesario para actualizar o eliminar PDF/A si se violaron algunas reglas. |
| [setTitle](#setTitle-java.lang.String-) | Establecer título para el documento PDF |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Establecer metadatos XMP del documento. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Obtiene o establece si el documento es compatible con pdfa. |
| [suppressUpdate](#suppressUpdate--) | Suprime la actualización de los datos de contenido para todas las páginas. El contenido no se actualiza hasta que se llama a ResumeUpdate. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validar el documento en el archivo especificado. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Validar el documento en el archivo especificado. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validar el documento en el archivo especificado. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Ocurre cuando una fuente reemplaza a otra fuente en el documento.

### Document {#Document--}
```
public Document()
```

Inicializa un documento vacío.

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

Inicializa una nueva instancia de Document a partir del arreglo de bytes {@code input}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entrada |  | matriz de bytes con documento PDF. |

### Document {#Document-java.io.InputStream-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-boolean-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-java.lang.String-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa un documento vacío.

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa un documento vacío.

### Document {#Document-com.aspose.pdf.PdfVersion-}
Inicializa un documento vacío.

### Document {#Document-com.aspose.ms.System.IO.Stream-}
Inicializa un documento vacío.

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
Inicializa un documento vacío.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
Inicializa un documento vacío.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa un documento vacío.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-boolean-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-java.lang.String-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-java.lang.String-boolean-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa un documento vacío.

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa un documento vacío.

### afterImport {#afterImport--}
```
public void afterImport()
```

Enumere todas las anotaciones registradas y llame a AfterImport para cada una de ellas.

### bindXml {#bindXml-java.io.InputStream-}
Vincular xml al documento

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Vincular xml/xsl al documento

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Vincular xml/xsl al documento

### bindXml {#bindXml-java.lang.String-}
Vincular xml al documento

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Vincular xml/xsl al documento

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Cambia las contraseñas del documento. Esta acción solo se puede realizar usando la contraseña del propietario.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Valida el documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| doRepair |  | Si true, los problemas encontrados serán reparados. |

**Returns:**
valor booleano

### close {#close--}
```
public void close()
```

Cierra todos los recursos utilizados por este documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Reconoce imágenes dentro del documento y agrega cadenas hocr sobre él.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Convierte el documento aplicando el Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Convierte el documento aplicando el Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Convierte el documento aplicando el Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Convierte el documento aplicando el Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Convierte el flujo del formato de origen al formato de destino.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Convierte el flujo del formato de origen en un archivo de destino en el formato de destino.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convierte el documento y guarda los errores en el flujo especificado.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Convertir el documento usando opciones de conversión especificadas

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Convierte el archivo de origen del formato de origen en un flujo del formato de destino.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Convierte el archivo de origen del formato de origen en un archivo de destino en el formato de destino.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convertir el documento y guardar los errores en el archivo especificado.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convierte el documento y guarda los errores en el flujo especificado.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Convierte la página a PNG para el flujo de imagen DSR, OMR, OCR.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos.

### decrypt {#decrypt--}
```
public void decrypt()
```

Descifra el documento. Luego llama a Save para obtener la versión descifrada del documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Cierra todos los recursos utilizados por este documento. Este método está obsoleto, usa close() en su lugar.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Encripta el documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Cifra el documento. Luego llama a Save para obtener la versión cifrada del documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Encripta el documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Cifra el documento. Luego llama a Save para obtener la versión cifrada del documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Cifra el documento. Luego llama a Save para obtener la versión cifrada del documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Encripta el documento.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exporta todas las anotaciones del documento al flujo.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporta todas las anotaciones del documento a un archivo XFDF

### flatten {#flatten--}
```
public void flatten()
```

Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Reemplaza el contenido transparente con gráficos raster y vectoriales no transparentes.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Limpia la memoria

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Notificación sobre fuentes faltantes al procesar documentos.

**Returns:**
ADocument.AbsentFontHandler instance

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> Obtiene acciones del documento. Esta propiedad es una instancia de la clase DocumentActions que permite obtener/establecer acciones BeforClosing, BeforSaving, etc. </p>

**Returns:**
Objeto DocumentActionCollection <hr> <pre> Este ejemplo muestra cómo obtener la acción después de abrir del documento: Document document = new Document(\"PdfWithOpenAction.pdf\"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Permite combinar el contenido de las páginas para optimizar el tamaño del documento.

**Returns:**
valor booleano

### getBackground {#getBackground--}
```
public Color getBackground()
```

Obtiene el color de fondo del documento.

**Returns:**
Objeto Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
Devuelve el valor del elemento del diccionario del catálogo.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Obtiene la colección del documento.

**Returns:**
Collection objeto

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Obtiene la configuración de seguridad si el documento está cifrado. Si el documento no está cifrado, entonces se lanzará la excepción correspondiente en .net 1.1 o CryptoAlgorithm será nulo para otras versiones de .net.

**Returns:**
Elemento CryptoAlgorithm @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Obtiene un controlador de seguridad personalizado.

**Returns:**
ICustomSecurityHandler instancia

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Devuelve el copiado usado para copiar páginas a este documento.

**Returns:**
Copier objeto

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

Obtiene la colección de destinos.

**Returns:**
Elemento DestinationCollection

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Obtiene el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda).

**Returns:**
Elemento Direction @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión.

**Returns:**
PrintDuplex elemento

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Obtiene la colección de archivos incrustados en el documento.

**Returns:**
EmbeddedFileCollection objeto

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero.

**Returns:**
valor booleano

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Obtiene o establece el indicador para gestionar la sanitización de campos de firma.

**Returns:**
valor booleano

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instancia de IPdfDocument usada para acceder a la estructura interna del documento. Solo interno

**Returns:**
IPdfDocument objeto

### getFileName {#getFileName--}
```
public String getFileName()
```

Nombre del archivo PDF que causó este documento

**Returns:**
Objeto String

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Obtén y establece el límite de tamaño de archivo para cargar un archivo completo en memoria.

**Returns:**
valor int

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

Instancia de IDocumentFontUtilities

**Returns:**
Instancia de IDocumentFontUtilities

### getForm {#getForm--}
```
public Form getForm()
```

Obtiene el Acro Form del documento.

**Returns:**
Form objeto

### getId {#getId--}
```
public Id getId()
```

Obtiene el ID.

**Returns:**
Id objeto

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Obtiene o establece la bandera de ignorar errores en los archivos de origen. Cuando las páginas del documento de origen se copian al documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos de origen están corruptos cuando esta bandera es falsa. ejemplo: dest.Pages.Add(src.Pages); Si esta bandera se establece en true, los objetos corruptos se reemplazarán con valores vacíos. Por defecto: true.

**Returns:**
valor booleano

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Obtiene la información del documento.

**Returns:**
DocumentInfo objeto

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Colección de JavaScript a nivel de documento.

**Returns:**
Objeto JavaScriptCollection

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Obtiene la estructura lógica del documento.

**Returns:**
RootElement objeto

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Metadatos del documento. (Un documento PDF puede incluir información general, como el título del documento, el autor y las fechas de creación y modificación. Esta información global sobre el documento (en contraposición a su contenido o estructura) se llama metadatos y tiene como objetivo ayudar en la catalogación y búsqueda de documentos en bases de datos externas.)

**Returns:**
Metadata objeto

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Devuelve el flujo de metadatos sin procesar

**Returns:**
IPdfStreamAccessor objeto

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Colección de Destinos nombrados en el documento.

**Returns:**
NamedDestinationCollection instancia

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Obtiene el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa.

**Returns:**
Elemento PageMode @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
Obtiene un objeto con el ID especificado en el documento.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> Obtiene la acción realizada al abrir el documento. </p> <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment objeto

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtiene la bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se combinan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false.

**Returns:**
valor booleano

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Obtiene los contornos del documento.

**Returns:**
Objeto OutlineCollection

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Obtiene la colección de intenciones de salida en el documento.

**Returns:**
Instancia OutputIntents

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtiene la información de la página.(solo para generador, no se completa al leer el documento)

**Returns:**
La información de la página.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Obtiene las etiquetas de página en el documento.

**Returns:**
Objeto PageLabelCollection

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Obtiene el diseño de página que se utilizará cuando se abra el documento.

**Returns:**
Elemento PageLayout @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Obtiene el modo de página, especificando cómo debe mostrarse el documento al abrirse.

**Returns:**
Elemento PageMode @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> Obtiene la colección de páginas del documento. Note que las páginas se numeran a partir de 1 en la colección. </p>

**Returns:**
Objeto PageCollection <hr> <pre> El siguiente ejemplo muestra cómo operar con las páginas del documento: Cómo obtener el número de páginas y cómo obtener el rectángulo de la página inicial del documento. Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Obtiene el formato PDF/A

**Returns:**
Elemento PdfFormat @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Obtiene los permisos del documento.

**Returns:**
valor int

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Obtiene la opción de manejo de escala de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión.

**Returns:**
Elemento PrintScaling

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

Obtiene acceso al contenido TaggedPdf. El ejemplo muestra cómo usar contenido etiquetado para crear un nuevo documento con encabezado, párrafos e imágenes. // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage("en-US"); // Set title for PDF document taggedContent.setTitle("Example document"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("The Header"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("The text of paragraph."); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figure 1"); figure1.setTitle("Image 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Save document document.save("example.pdf");

**Returns:**
Instancia ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

Obtiene una versión de PDF del encabezado del archivo PDF.

**Returns:**
valor String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Obtener metadatos XMP del documento.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Comprueba si el documento PDF actual se ha guardado con actualizaciones incrementales.

**Returns:**
true si el documento PDF tiene actualizaciones incrementales; de lo contrario, false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Importa anotaciones desde el flujo al documento.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importa anotaciones del archivo XFDF al documento.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Bandera que indica la sustitución de fuentes faltantes.

**Returns:**
valor booleano

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> Obtiene la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo obtener la bandera CenterWindow: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente.

**Returns:**
Valor booleano por defecto falso.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> Obtiene la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo obtener la bandera DisplayDocTitle: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Obtiene o establece un valor que indica si se debe habilitar el registro de notificaciones.

**Returns:**
valor booleano

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria.

**Returns:**
valor booleano

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Obtiene el estado de cifrado del documento. Verdadero si el documento está cifrado.

**Returns:**
valor booleano

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> Obtiene la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo obtener la bandera FitWindow: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Lanza una excepción si el documento se guarda con cambios y tiene firma

**Returns:**
valor booleano

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> Obtiene la bandera que especifica si la barra de menús debe ocultarse cuando el documento está activo. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo obtener la bandera HideMenubar: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> Obtiene la bandera que especifica si la barra de herramientas debe ocultarse cuando el documento está activo. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo obtener la bandera HideToolBar: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> Obtiene la bandera que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. </p>

**Returns:**
valor booleano <hr> <pre> El ejemplo muestra cómo obtener la bandera HideWindowUI: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Obtiene el estado de licencia del sistema.

**Returns:**
valor booleano

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Obtiene un valor que indica si el documento está linealizado.

**Returns:**
valor booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después de que se llame al método save si este parámetro ManualDispose está habilitado.

**Returns:**
Valor booleano. (Valor predeterminado == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Obtiene si el documento es compatible con PDF/A.

**Returns:**
valor booleano

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Obtiene si el documento es compatible con pdfua.

**Returns:**
valor booleano

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Obtiene una bandera que indica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada.

**Returns:**
valor booleano

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Comprueba si el documento requiere una llamada al método Repair.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Por defecto, el proceso de validación PDF/A es necesario para actualizar o eliminar datos compatibles con PDF/A si se violaron algunas reglas.

**Returns:**
valor booleano

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Obtiene o establece si el documento es compatible con pdfa.

**Returns:**
valor booleano

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Carga un archivo, convirtiéndolo a PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Fusiona documentos.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Fusiona documentos.

### merge {#merge-com.aspose.pdf.Document...-}
Fusiona documentos.

### merge {#merge-java.lang.String...-}
Fusiona archivos PDF.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Fusiona documentos.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Fusiona documentos.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Fusiona documentos.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Fusiona archivos PDF.

### optimize {#optimize--}
```
public void optimize()
```

Linealiza el documento con el fin de - abrir la primera página lo más rápido posible; - mostrar la página siguiente o seguir el enlace a la página siguiente lo más rápido posible; - mostrar la página de forma incremental a medida que llega, cuando los datos de una página se entregan a través de un canal lento (mostrar primero los datos más útiles); - permitir que la interacción del usuario, como seguir un enlace, se realice incluso antes de que se haya recibido y mostrado la página completa. Invocar este método no guarda realmente el documento. Por el contrario, el documento solo se prepara para tener una estructura optimizada; luego llame a Save para obtener el documento optimizado.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Optimiza los recursos en el documento: 1. Los recursos que no se utilizan en las páginas del documento se eliminan; 2. Los recursos iguales se combinan en un solo objeto; 3. Los objetos no utilizados se borran.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimiza los recursos en el documento: 1. Los recursos que no se utilizan en las páginas del documento se eliminan; 2. Los recursos iguales se combinan en un solo objeto; 3. Los objetos no utilizados se borran.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. Solo si el documento tiene más objetos de página que nodesNumInSubtrees, de lo contrario no hace nada.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. Solo si el documento tiene más objetos de página que nodesNumInSubtrees, de lo contrario no hace nada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodesNumInSubtrees |  | Número deseado de subnodos. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Método interno

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Almacena el documento en un flujo.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Elimina los metadatos del documento.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Elimina la compatibilidad pdfa del documento

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Elimina la compatibilidad pdfUa del documento

### repair {#repair--}
```
public void repair()
```

Repara el documento dañado.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Repara el documento dañado.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

reanuda la actualización del documento

### save {#save--}
```
public void save()
```

<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-java.io.OutputStream-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-com.aspose.pdf.SaveOptions-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-java.lang.String-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> Guardar el documento de forma incremental (es decir, usando la técnica de actualización incremental). </p> <hr> <p> Para guardar el documento de forma incremental debemos abrir el archivo del documento para escritura. Por lo tanto, Document no debe inicializarse con InputStream sino con la ruta al archivo, como en el siguiente fragmento de código: Document doc = new Document(\"document.pdf\"); // make some changes and save the document incrementally doc.save(); </p> En caso de que el documento se haya inicializado con InputStream, escribir en InputStream es imposible, por lo que recomendamos usar los métodos separados \"save\" para guardar el documento o \"saveIncrementally\" para guardarlo de forma incremental.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Guarda de forma incremental el Documento PDF en el flujo especificado.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Guarda de forma incremental el Documento PDF en el flujo especificado.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Guarda de forma incremental el Documento PDF en el flujo especificado.

### saveXml {#saveXml-java.lang.String-}
Guardar documento en XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Envía ciertas páginas del documento al dispositivo de documento para su procesamiento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Envía todo el documento al dispositivo de documento para su procesamiento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Envía todo el documento al dispositivo de documento para su procesamiento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Envía todo el documento al dispositivo de documento para su procesamiento.

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Notificación sobre fuentes faltantes al procesar documentos.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Estableciendo la bandera para establecer la fuente determinada por el programa en caso de ausencia de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Permite combinar el contenido de las páginas para optimizar el tamaño del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBackground {#setBackground-java.awt.Color-}
Establece el color de fondo del documento.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Establece la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Establece la colección del documento.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Obtiene el parámetro de conversión para el convertidor pdf/ua (Convierte solo Metadatos y Catálogo del Documento si se establece en verdadero).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Establece el límite de tamaño de archivo para cargar un archivo completo en memoria al valor predeterminado de 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor booleano por defecto falso. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Establece la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | PrintDuplex elemento |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Obtiene o establece un valor que indica si se debe habilitar el registro de notificaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Obtiene o establece la bandera que permite que el documento se descargue parcialmente de la memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Obtiene o establece el indicador para gestionar la sanitización de campos de firma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Obtén y establece el límite de tamaño de archivo para cargar un archivo completo en memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Establece la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Lanza una excepción si el documento se guarda con cambios y tiene firma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Establece la bandera que especifica si la barra de menú debe ocultarse cuando el documento está activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Establece la bandera que especifica si la barra de herramientas debe ocultarse cuando el documento está activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Establece la bandera que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Obtiene o establece la bandera de ignorar errores en los archivos de origen. Cuando las páginas del documento de origen se copian al documento de destino, el proceso de copia se detiene con una excepción si algunos objetos en los archivos de origen están corruptos cuando esta bandera es falsa. ejemplo: dest.Pages.Add(src.Pages); Si esta bandera se establece en true, los objetos corruptos se reemplazarán con valores vacíos. Por defecto: true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Establece un valor que indica si el documento está linealizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después de que se llame al método save si este parámetro ManualDispose está habilitado. Pero se recomienda encarecidamente llamar al método dispose cuando la instancia de Document ya no sea necesaria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| manualDisposeEnabled |  | Valor booleano. (Valor predeterminado == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> Establece la acción que se ejecuta al abrir el documento. <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Establece la bandera de optimización. Cuando se añaden páginas al documento, los flujos de recursos iguales en el archivo resultante se combinan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante, pero puede provocar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Establece la información de la página (solo para generador, no se completa al leer el documento).

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Establece el diseño de página que se utilizará cuando se abra el documento.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

Establece una bandera que especifica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Establece la opción de manejo de escalado de impresión que se usará al imprimir el archivo desde el cuadro de diálogo de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | PrintDuplex elemento |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Por defecto, el proceso de validación PDF/A es necesario para actualizar o eliminar PDF/A si se violaron algunas reglas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | valor booleano |

### setTitle {#setTitle-java.lang.String-}
Establecer título para el documento PDF

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Establecer metadatos XMP del documento.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Obtiene o establece si el documento es compatible con pdfa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suprime la actualización de los datos de contenido para todas las páginas. El contenido no se actualiza hasta que se llama a ResumeUpdate.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validar el documento en el archivo especificado.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Validar el documento en el archivo especificado.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validar el documento en el archivo especificado.
