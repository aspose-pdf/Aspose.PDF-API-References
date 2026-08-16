---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El paquete com.aspose.pdf.facades proporciona clases que originalmente provienen de Aspose.Pdf.Kit."
type: docs
weight: 180
url: /es/java/com.aspose.pdf.facades/
---
El paquete com.aspose.pdf.facades proporciona clases que originalmente provienen de Aspose.Pdf.Kit.

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IFacade](./ifacade/) | Interfaz de fachada general que define métodos comunes de fachadas. |
| [IForm](./iform/) | Clase que representa un objeto de formulario Acro. |
| [IFormEditor](./iformeditor/) | Clase para editar formularios (agregar/eliminar campos, etc.) |
| [IPdfFileEditor](./ipdffileeditor/) | Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc. |
| [IPdfFileStamp](./ipdffilestamp/) | Interfaz para agregar sellos (marca de agua o fondo) a archivos PDF. |
| [ISaveableFacade](./isaveablefacade/) | Interfaz de fachada que define métodos comunes para todas las fachadas guardables. |
## Clases

| Clase | Descripción |
| --- | --- |
| [AlignmentType](./alignmenttype/) | La clase contiene posibles tipos de alineación. Use HorizontalAlignment en su lugar |
| [AutoRotateMode](./autorotatemode/) | Dirección de la rotación cuando el documento se imprime. |
| [BDCProperties](./bdcproperties/) | Propiedades del operador BDC. |
| [Bookmark](./bookmark/) | Representa un marcador. |
| [Bookmarks](./bookmarks/) | Representa una colección de objetos {@code Bookmark}. |
| [CgmPdfProducer](./cgmpdfproducer/) | Representa una clase para generar PDF a partir del formato Computer Graphics Metafile (CGM). |
| [DataType](./datatype/) | Enumera definiciones de tipos de campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeración de propiedades XMP estándar. |
| [DocumentPrivilege](./documentprivilege/) | Representa los privilegios para acceder a un archivo Pdf. Consulte {@code PdfFileSecurity}. Hay 4 formas de usar esta clase: 1.Usar un privilegio predefinido directamente. 2.Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3.Basado en un privilegio predefinido y cambiar una combinación específica de permisos de Adobe Professional. 4.Mezcla la forma 2 y la forma 3. //Way1: Usando privilegio predefinido directamente. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Basado en un privilegio predefinido y cambiar algunos permisos específicos. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Basado en un privilegio predefinido y cambiar una combinación específica de permisos de Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mezcla la forma 2 y la forma 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Enumera los tipos de codificación del texto utilizado. |
| [Facade](./facade/) | Clase fachada base. |
| [FontColor](./fontcolor/) | Clase que representa el color del texto. |
| [Form](./form/) | Clase que representa un objeto de formulario Acro. |
| [Form.ImportStatus](./form.importstatus/) | Estado del campo importado |
| [FormattedText](./formattedtext/) | Clase que representa texto formateado. Contiene información sobre el texto y su color, tamaño, estilo. |
| [FormEditor](./formeditor/) | Clase para editar formularios (agregar/eliminar campos, etc.) |
| [FormEditorWeb](./formeditorweb/) | Clase para editar formularios (añadir/eliminar campos, etc.) |
| [FormFieldFacade](./formfieldfacade/) | Clase para representar propiedades del campo. |
| [FormWeb](./formweb/) | Representando la interfaz de formulario Acro. |
| [InternalHelper](./internalhelper/) | Clase de ayuda |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Clase para especificar los parámetros de redimensionamiento de página. Permite establecer los siguientes parámetros: Tamaño de la página resultante (ancho, alto) en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; márgenes izquierdo, superior, inferior y derecho en unidades de espacio predeterminadas o en porcentajes del tamaño de la página inicial; Algunos valores pueden dejarse nulos para cálculo automático. Estos valores se calcularán a partir del resto del tamaño de la página después de calcular los valores especificados explícitamente. Por ejemplo: si el ancho de la página = 100 y el nuevo ancho de página especificado es 60 unidades, entonces los márgenes izquierdo y derecho se calculan automáticamente: (100 - 60) / 2 = 15. Esta clase se usa en el método ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Valor del margen o del tamaño del contenido especificado en porcentajes de unidades de espacio predeterminadas. Esta clase se usa en ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Representa la información de la línea. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar. |
| [PdfContentEditor](./pdfcontenteditor/) | Representa una clase para editar el contenido de archivos PDF. |
| [PdfConverter](./pdfconverter/) | Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando ahora BMP, JPEG, PNG y TIFF. Contenido soportado en PDFs: imágenes, formularios, comentarios. |
| [PdfExtractor](./pdfextractor/) | Clase para extraer imágenes y texto de documentos PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Acción realizada cuando se encontró un archivo corrupto en el proceso de concatenación. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Representa una clase con un método abstracto que normalmente es proporcionado por la parte que llama y maneja los eventos de progreso que provienen de la concatenación. Usualmente dicho manejador suministrado por el cliente puede usarse para mostrar el progreso total de la concatenación en la consola o en una barra de progreso. Representa información sobre el evento de progreso ocurrido. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Clase que proporciona información sobre archivos corruptos durante la concatenación. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Datos de la posición del salto de página. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Esta clase representa información sobre el progreso de la concatenación que puede ser utilizada en una aplicación externa. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Este enumerado describe los posibles tipos de eventos de progreso que pueden ocurrir durante la concatenación |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Representa la clase PdfFileEditorWeb. Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc. |
| [PdfFileInfo](./pdffileinfo/) | Representa una clase para acceder a la meta información de un documento PDF. |
| [PdfFileMend](./pdffilemend/) | Representa una clase para añadir textos e imágenes en las páginas de un documento PDF existente. |
| [PdfFileSanitization](./pdffilesanitization/) | Representa la API de sanitización y recuperación. Úsala si no puedes crear/abrir documentos de otra manera. |
| [PdfFileSecurity](./pdffilesecurity/) | Representa el cifrado o descifrado de un archivo PDF con contraseña de propietario o de usuario, cambiando la configuración de seguridad y la contraseña. |
| [PdfFileSignature](./pdffilesignature/) | Representa una clase para firmar un archivo PDF con un certificado. |
| [PdfFileStamp](./pdffilestamp/) | Clase para añadir sellos (marca de agua o fondo) a archivos PDF. |
| [PdfFileStampWeb](./pdffilestampweb/) | Clase para añadir sellos (marca de agua o fondo) a archivos PDF. Habilita el trabajo con HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Clase para eliminar todo el código JavaScript. |
| [PdfPageEditor](./pdfpageeditor/) | Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom, mover la posición y cambiar el tamaño de la página. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Representa un objeto que contiene la información de la página de impresión actual. |
| [PdfProducer](./pdfproducer/) | <p> Representa una clase para generar PDF a partir de otros formatos. </p> <hr> <pre>Este ejemplo muestra cómo generar un archivo Pdf a partir de un archivo CGM. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Archivo pdf generado con éxito. } catch (Exception e) { // Hacer algo... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Representa el método que maneja el evento QueryPageSettings de un PrintDocument. |
| [PdfViewer](./pdfviewer/) | Representa una clase para visualizar o imprimir un PDF. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Clase para manipular metadatos XMP. |
| [PositioningMode](./positioningmode/) | Define el modo de posicionamiento. Los valores posibles incluyen Legacy (compatibilidad hacia atrás) y Current (método actualizado de cálculo de posición de texto). |
| [PropertyFlag](./propertyflag/) | Enumeración de posibles banderas de campo. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Esta clase contiene parámetros que definen el comportamiento de PdfContentEditor cuando se realiza la operación ReplaceText. |
| [SaveableFacade](./saveablefacade/) | <p> Clase base para todas las fachadas guardables. |
| [SignatureName](./signaturename/) | Representa una clase para un nombre de firma. Representa un nombre de firma más preciso. Se usa en lugar de nombres de cadena. Permite presentar firmas con los mismos nombres de cadena. |
| [Stamp](./stamp/) | Clase que representa un sello. |
| [StampInfo](./stampinfo/) | Clase que representa información de sello. |
| [TextProperties](./textproperties/) | Representa propiedades de texto como: tamaño del texto, color, estilo, etc. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Clase que representa los posibles valores de alineación vertical. Use VerticalAlignment en su lugar |
| [ViewerPreference](./viewerpreference/) | Describe las preferencias del visor (modo de página, modo de página sin pantalla completa, diseño de página). |
| [WordWrapMode](./wordwrapmode/) | Define estrategias de ajuste de palabras |
## Enums

| Enum | Descripción |
| --- | --- |
| [Algorithm](./algorithm/) | Representa algoritmos que pueden usarse para encriptar documentos PDF. |
| [BlendingColorSpace](./blendingcolorspace/) | Clase que representa el espacio de color de mezcla. |
| [FieldType](./fieldtype/) | Enumeración de los posibles tipos de campo. |
| [FontStyle](./fontstyle/) | Enumera 14 tipos de fuente. |
| [ImageMergeMode](./imagemergemode/) | Representa modos para combinar imágenes. |
| [KeySize](./keysize/) | Define diferentes tamaños de clave que pueden usarse para encriptar documentos PDF. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Acción a realizar si la fuente no contiene el carácter requerido |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Ámbito donde se aplica la operación de reemplazar texto REPLACE_FIRST por defecto |
| [StampType](./stamptype/) | Describe los tipos de sello. |
| [SubmitFormFlag](./submitformflag/) | Enumeración de las posibles banderas de envío de formulario. |
