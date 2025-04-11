---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF for .NET API Reference
description: El espacio de nombres Aspose.Pdf.Facades proporciona clases que originalmente provienen de Aspose.Pdf.Kit. Estas clases se utilizan para manipular documentos realizando operaciones como concatenar, estampar, firmar, anotar, etc., pero a un nivel alto sin acceso a la estructura interna de un documento.
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/
---
El **Aspose.Pdf.Facades** espacio de nombres proporciona clases que originalmente provienen de Aspose.Pdf.Kit. Estas clases se utilizan para manipular documentos realizando operaciones como concatenar, estampar, firmar, anotar, etc., pero a un nivel alto sin acceso a la estructura interna de un documento.

## Clases

| Clase | Descripción |
| --- | --- |
| [AutoFiller](./autofiller/) | Representa una clase para recibir datos de una base de datos u otra fuente de datos, llenarlos en los campos diseñados del pdf de plantilla y, al final, generar un nuevo archivo o flujo pdf. Tiene dos modos de entrada de archivo de plantilla: entrada como un flujo o un archivo pdf. Tiene cuatro tipos de modos de salida: un flujo combinado, un archivo combinado, muchos pequeños flujos, muchos pequeños archivos. Puede recibir datos literales contenidos en un System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | Propiedades del operador BDC. |
| [Bookmark](./bookmark/) | Representa un marcador. |
| [Bookmarks](./bookmarks/) | Representa una colección de objetos [`Bookmark`](../aspose.pdf.facades/bookmark/). |
| [DocumentPrivilege](./documentprivilege/) | Representa los privilegios para acceder a un archivo Pdf. Consulte [`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). Hay 4 formas de usar esta clase: 1. Usando privilegios predefinidos directamente. 2. Basado en un privilegio predefinido y cambiar algunos permisos específicos. 3. Basado en un privilegio predefinido y cambiar algunas combinaciones de permisos específicos de Adobe Professional. 4. Mezcla la forma 2 y la forma 3. |
| [Facade](./facade/) | Clase base de fachada. |
| [FontColor](./fontcolor/) | Clase que representa el color del texto. |
| [Form](./form/) | Clase que representa un objeto de formulario Acro. |
| [FormattedText](./formattedtext/) | Clase que representa texto formateado. Contiene información sobre el texto y su color, tamaño, estilo. |
| [FormDataConverter](./formdataconverter/) | Representa una clase para convertir datos de un formato a otro. Puede convertir datos en fdf/xml/pdf/xfdf a OLEDB/OdbcDB. También puede convertir datos en OLEDB/OdbcDB a datos en fdf/xml/xfdf. Puede convertir fdf a xml con una etiqueta "hard-named". |
| [FormEditor](./formeditor/) | Clase para editar formularios (agregar/eliminar campos, etc.) |
| [FormFieldFacade](./formfieldfacade/) | Clase para representar propiedades de campo. |
| [LineInfo](./lineinfo/) | Representa la información de la línea. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Representa una clase para trabajar con anotaciones de documentos PDF (comentarios). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar. |
| [PdfContentEditor](./pdfcontenteditor/) | Representa una clase para editar el contenido de un archivo PDF. |
| [PdfConverter](./pdfconverter/) | Representa una clase para convertir cada página de un archivo pdf a imágenes, soportando BMP, JPEG, PNG y TIFF ahora. Contenido soportado en pdfs: imágenes, formularios, comentarios. |
| [PdfExtractor](./pdfextractor/) | Clase para extraer imágenes y texto de un documento PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implementa operaciones con archivos PDF: concatenación, división, extracción de páginas, creación de folleto, etc. |
| [PdfFileInfo](./pdffileinfo/) | Representa una clase para acceder a la información meta de un documento PDF. |
| [PdfFileMend](./pdffilemend/) | Representa una clase para agregar textos e imágenes en las páginas de un documento PDF existente. |
| [PdfFileSanitization](./pdffilesanitization/) | Representa la API de sanitización y recuperación. Úselo si no puede crear/abrir documentos de ninguna otra manera. |
| [PdfFileSecurity](./pdffilesecurity/) | Representa el cifrado o descifrado de un archivo Pdf con contraseña de propietario o usuario, cambiando la configuración de seguridad y la contraseña. |
| [PdfFileSignature](./pdffilesignature/) | Representa una clase para firmar un archivo pdf con un certificado. |
| [PdfFileStamp](./pdffilestamp/) | Clase para agregar sellos (marca de agua o fondo) a archivos PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Clase para eliminar todo el código Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | Representa una clase para editar la página del archivo PDF, incluyendo rotar la página, hacer zoom en la página, mover la posición y cambiar el tamaño de la página. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Representa un objeto que contiene la información de la página de impresión actual. |
| [PdfProducer](./pdfproducer/) | Representa una clase para producir PDF a partir de otros formatos. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Representa el método que maneja el evento [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) de un [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |
| [PdfViewer](./pdfviewer/) | Representa una clase para ver o imprimir un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Clase para manipular metadatos XMP. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Esta clase contiene parámetros que definen el comportamiento de PdfContentEditor cuando se realiza la operación ReplaceText. |
| [SaveableFacade](./saveablefacade/) | Clase base para todas las fachadas guardables. |
| [SignatureName](./signaturename/) | Representa una clase para un nombre de firma. |
| [Stamp](./stamp/) | Clase que representa un sello. |
| [StampInfo](./stampinfo/) | Clase que representa información del sello. |
| [TextProperties](./textproperties/) | Representa propiedades del texto como: tamaño del texto, color, estilo, etc. |
| [ViewerPreference](./viewerpreference/) | Describe preferencias del visor (modo de página, modo de página no de pantalla completa, diseño de página). |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IFacade](./ifacade/) | Interfaz de fachada general que define métodos comunes de fachadas. |
| [ISaveableFacade](./isaveablefacade/) | Interfaz de fachada que define métodos comunes para todas las fachadas guardables. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [Algorithm](./algorithm/) | Representa algoritmos que se pueden usar para cifrar documentos pdf. |
| [AutoRotateMode](./autorotatemode/) | Dirección de la rotación cuando se imprime el documento. |
| [BlendingColorSpace](./blendingcolorspace/) | Clase que representa el espacio de color de mezcla. |
| [DataType](./datatype/) | Enumera las definiciones de tipos de campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeración de propiedades XMP estándar. |
| [EncodingType](./encodingtype/) | Enumera los tipos de codificación del texto utilizado. |
| [FieldType](./fieldtype/) | Enumeración de posibles tipos de campo. |
| [FontStyle](./fontstyle/) | Enumera 14 tipos de fuente. |
| [ImageMergeMode](./imagemergemode/) | Representa modos para fusionar imágenes. |
| [KeySize](./keysize/) | Define diferentes tamaños de clave que se pueden usar para cifrar documentos pdf. |
| [PositioningMode](./positioningmode/) | Define el modo de posicionamiento. Los valores posibles incluyen Legacy (compatibilidad hacia atrás) y Current (método de cálculo de posición de texto actualizado) |
| [PropertyFlag](./propertyflag/) | Enumeración de posibles banderas de campo. |
| [StampType](./stamptype/) | Describe tipos de sellos. |
| [SubmitFormFlag](./submitformflag/) | Enumeración de posibles banderas de envío de formularios. |
| [WordWrapMode](./wordwrapmode/) | Define estrategias de ajuste de palabras |