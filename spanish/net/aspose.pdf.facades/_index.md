---
title: Aspose.Pdf.Facades
second_title: Referencia de API de Aspose.PDF para .NET
description: El Aspose.Pdf.FachadasEl espacio de nombres proporciona clases que provienen originalmente de Aspose.Pdf.Kit. Estas clases se utilizan para manipular documentos realizar operaciones como concatenar sellar firmar anotar etc. pero en un nivel alto sin acceso a la estructura interna de un documento.
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/
---
El **Aspose.Pdf.Fachadas**El espacio de nombres proporciona clases que provienen originalmente de Aspose.Pdf.Kit. Estas clases se utilizan para manipular documentos realizar operaciones como concatenar, sellar, firmar, anotar, etc. pero en un nivel alto sin acceso a la estructura interna de un documento.

## Clases

| Clase | Descripción |
| --- | --- |
| [AutoFiller](./autofiller) | Representa una clase para recibir datos de la base de datos u otra fuente de datos, los llena en los campos diseñados de la plantilla pdf y, por último, genera un nuevo archivo pdf o secuencia. Tiene dos modos de entrada de archivo de plantilla: entrada como secuencia o archivo pdf . Tiene cuatro tipos de modos de salida: un flujo fusionado, un archivo fusionado, muchos flujos pequeños, muchos archivos pequeños. Puede recibir datos literales contenidos en un System.Data.DataTable. |
| [Bookmark](./bookmark) | Representa un marcador. |
| [Bookmarks](./bookmarks) | Representa una colección de[`Bookmark`](../aspose.pdf.facades/bookmark) objetos. |
| [DocumentPrivilege](./documentprivilege) | Representa los privilegios para acceder al archivo PDF. Referirse a[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity) . Hay 4 formas de usar esta clase: 1.Usar privilegios predefinidos directamente. 2.Basarse en un privilegio predefinido y cambiar algunos permisos específicos. 3.Basarse en un privilegio predefinido y cambiar alguna combinación de permisos específicos de Adobe Professional. 4.Mezcla way2 y way3. |
| [Facade](./facade) | Clase fachada base. |
| [FontColor](./fontcolor) | Clase que representa el color del texto. |
| [Form](./form) | Clase que representa el objeto de formulario Acro. |
| [FormattedText](./formattedtext) | Clase que representa texto formateado. Contiene información sobre el texto y su color, tamaño, estilo. |
| [FormDataConverter](./formdataconverter) | Representa una clase para convertir datos de un formato a otro formato. Puede convertir los datos en fdf/xml/pdf/xfdf a OLEDB/OdbcDB. También puede convertir los datos en OLEDB/OdbcDB a los datos en fdf/xml/xfdf. Puede convertir el fdf al xml con la etiqueta "hard-named". |
| [FormEditor](./formeditor) | Clase para editar formularios (agregar/eliminar campo, etc.) |
| [FormFieldFacade](./formfieldfacade) | Clase para representar propiedades de campo. |
| [LineInfo](./lineinfo) | Representa la información de la línea. |
| [PdfAnnotationEditor](./pdfannotationeditor) | Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF. |
| [PdfBookmarkEditor](./pdfbookmarkeditor) | Representa una clase para trabajar con marcadores de archivos PDF, incluidos crear, modificar, exportar, importar y eliminar. |
| [PdfContentEditor](./pdfcontenteditor) | Representa una clase para editar el contenido del archivo PDF. |
| [PdfConverter](./pdfconverter) | Representa una clase para convertir cada página de un archivo PDF en imágenes, compatible con BMP, JPEG, PNG y TIFF ahora. Contenido admitido en archivos PDF: imágenes, formularios, comentarios. |
| [PdfExtractor](./pdfextractor) | Clase para extraer imágenes y texto de un documento PDF. |
| [PdfFileEditor](./pdffileeditor) | Implementa operaciones con archivo PDF: concatenación, división, extracción de páginas, elaboración de cuadernillo, etc. |
| [PdfFileInfo](./pdffileinfo) | Representa una clase para acceder a la metainformación del documento PDF. |
| [PdfFileMend](./pdffilemend) | Representa una clase para agregar textos e imágenes en las páginas de un documento PDF existente. |
| [PdfFileSanitization](./pdffilesanitization) | Representa la API de sanitización y recuperación. Úsela si no puede crear/abrir documentos de otra forma. |
| [PdfFileSecurity](./pdffilesecurity) | Representa el cifrado o descifrado de un archivo PDF con propietario o contraseña de usuario, cambiando la configuración de seguridad y la contraseña. |
| [PdfFileSignature](./pdffilesignature) | Representa una clase para firmar un archivo pdf con un certificado. |
| [PdfFileStamp](./pdffilestamp) | Clase para agregar sellos (marca de agua o fondo) a archivos PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper) | Clase para eliminar todo el código Java Script. |
| [PdfPageEditor](./pdfpageeditor) | Representa una clase para editar la página del archivo PDF, incluida la rotación de página, el zoom de página, el movimiento de posición y el cambio de tamaño de página. |
| [PdfPrintPageInfo](./pdfprintpageinfo) | Representa un objeto que contiene información de la página de impresión actual. |
| [PdfProducer](./pdfproducer) | Representa una clase para producir PDF desde otros formatos.  Este ejemplo muestra cómo producir un archivo PDF a partir de un archivo CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler) | Representa el método que maneja el evento QueryPageSettings de PrintDocument. |
| [PdfViewer](./pdfviewer) | Representa una clase para ver o imprimir un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata) | Clase para manipulación con metadatos XMP. |
| [ReplaceTextStrategy](./replacetextstrategy) | Esta clase contiene parámetros que definen el comportamiento de PdfContentEditor cuando se realiza la operación de ReemplazarTexto. |
| [SaveableFacade](./saveablefacade) | Clase base para todas las fachadas salvables. |
| [Stamp](./stamp) | Sello representativo de clase. |
| [StampInfo](./stampinfo) | Clase que representa la información del sello. |
| [TextProperties](./textproperties) | Representa propiedades de texto como: tamaño de texto, color, estilo, etc. |
| [ViewerPreference](./viewerpreference) | Describe las preferencias del espectador (modo de página, modo de página sin pantalla completa, diseño de página). |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IFacade](./ifacade) | Interfaz de fachada general que define métodos comunes de fachadas. |
| [ISaveableFacade](./isaveablefacade) | Interfaz de fachada que define métodos comunes para todas las fachadas salvables. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [Algorithm](./algorithm) | Representa algoritmos que se pueden usar para cifrar documentos pdf. |
| [AutoRotateMode](./autorotatemode) | Dirección de la rotación cuando se imprime el documento. |
| [BlendingColorSpace](./blendingcolorspace) | La clase representa el espacio de color de fusión. |
| [DataType](./datatype) | Enumera definiciones de tipos de campo. |
| [DefaultMetadataProperties](./defaultmetadataproperties) | Enumeración de propiedades XMP estándar. |
| [EncodingType](./encodingtype) | Enumera los tipos de codificación del texto usando. |
| [FieldType](./fieldtype) | Enumeración de posibles tipos de campos. |
| [FontStyle](./fontstyle) | Enumera 14 tipos de fuente. |
| [ImageMergeMode](./imagemergemode) | Representa modos para fusionar imágenes. |
| [KeySize](./keysize) | Define diferentes tamaños de clave que se pueden usar para cifrar documentos pdf. |
| [PositioningMode](./positioningmode) | Define el modo de posicionamiento. Los valores posibles incluyen Legacy (compatibilidad con versiones anteriores) y Current (método de cálculo de posición de texto actualizado) |
| [PropertyFlag](./propertyflag) | Enumeración de posibles indicadores de campo. |
| [StampType](./stamptype) | Describe los tipos de sellos. |
| [SubmitFormFlag](./submitformflag) | Enumeración de posibles indicadores de formulario de envío. |
| [WordWrapMode](./wordwrapmode) | Define estrategias de ajuste de palabras |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
