---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El paquete com.aspose.pdf.devices proporciona clases que se utilizan para representar el documento como imagen(es) o texto plano."
type: docs
weight: 140
url: /es/java/com.aspose.pdf.devices/
---
El paquete com.aspose.pdf.devices proporciona clases que se utilizan para representar el documento como imagen(es) o texto plano.

## Clases

| Clase | Descripción |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en bmp. |
| [Device](./device/) | Clase abstracta para todo tipo de dispositivos. El dispositivo se utiliza para representar el documento pdf en algún formato. Por ejemplo, la página del documento puede representarse como imagen o texto. |
| [DicomDevice](./dicomdevice/) | Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en formato Dicom. |
| [DocumentDevice](./documentdevice/) | Clase abstracta para todos los dispositivos que se utiliza para procesar todo el documento pdf. |
| [EmfDevice](./emfdevice/) | Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en emf. |
| [FormPresentationMode](./formpresentationmode/) | Se utiliza para especificar el modo de presentación del formulario al imprimir o convertir documentos pdf a imagen. |
| [GifDevice](./gifdevice/) | Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en gif. |
| [GraphicsDevice](./graphicsdevice/) | Representa un dispositivo de imagen que ayuda a renderizar las páginas del documento pdf en gráficos. |
| [ImageDevice](./imagedevice/) | Una clase abstracta para dispositivos de imagen. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en jpeg. |
| [Margins](./margins/) | Esta clase representa los márgenes de una imagen. |
| [PageDevice](./pagedevice/) | Clase abstracta para todos los dispositivos que se utiliza para procesar una página determinada del documento pdf. |
| [PngDevice](./pngdevice/) | Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en png. |
| [Resolution](./resolution/) | Representa una clase para almacenar la resolución de la imagen. |
| [TextDevice](./textdevice/) | <p> Representa una clase para convertir páginas de documentos pdf a texto. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> El objeto {@code TextDevice} se utiliza básicamente para extraer texto de una página pdf. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Representa un dispositivo de imagen que guarda las páginas del documento pdf en una imagen en miniatura. |
| [TiffDevice](./tiffdevice/) | Esta clase ayuda a guardar el documento pdf página por página en una única imagen tiff. |
| [TiffSettings](./tiffsettings/) | Esta clase representa la configuración para importar pdf a Tiff. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Clase que representa tipos de conversión indexados |
## Enums

| Enum | Descripción |
| --- | --- |
| [ColorDepth](./colordepth/) | Se utiliza para especificar el valor del parámetro pasado a un dispositivo de imagen Tiff. |
| [CompressionType](./compressiontype/) | Se utiliza para especificar el valor del parámetro pasado a un dispositivo de imagen Tiff. |
| [ShapeType](./shapetype/) | Este enum representa el tipo de forma para las imágenes extraídas. |
