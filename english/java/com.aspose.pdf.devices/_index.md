---
title: com.aspose.pdf.devices
linktitle: com.aspose.pdf.devices
second_title: Aspose.PDF for Java API Reference
description: The com.aspose.pdf.devices package provides classes which are used for representing document as image(s) or a plain text.
type: docs
weight: 140
url: /java/com.aspose.pdf.devices/
---
The com.aspose.pdf.devices package provides classes which are used for representing document as image(s) or a plain text.

## Classes

| Class | Description |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Represents image device that helps to save pdf document pages into bmp. |
| [Device](./device/) | Abstract class for all types of devices. Device is used to represent pdf document in some format. For example, document page can be represented as image or text. |
| [DicomDevice](./dicomdevice/) | Represents image device that helps to save pdf document pages into Dicom format. |
| [DocumentDevice](./documentdevice/) | Abstract class for all devices which is used to process the whole pdf document. |
| [EmfDevice](./emfdevice/) | Represents image device that helps to save pdf document pages into emf. |
| [FormPresentationMode](./formpresentationmode/) | Used to specify the form presentation mode when printing or converting to image pdf documents. |
| [GifDevice](./gifdevice/) | Represents image device that helps to save pdf document pages into gif. |
| [GraphicsDevice](./graphicsdevice/) | Represents image device that helps to render pdf document pages into graphics. |
| [ImageDevice](./imagedevice/) | An abstract class for image devices. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Represents image device that helps to save pdf document pages into jpeg. |
| [Margins](./margins/) | This class represents margins of an image. |
| [PageDevice](./pagedevice/) | Abstract class for all devices which is used to process certain page the pdf document. |
| [PngDevice](./pngdevice/) | Represents image device that helps to save pdf document pages into png. |
| [Resolution](./resolution/) | Represents class for holding image resolution. |
| [TextDevice](./textdevice/) | <p> Represents class for converting pdf document pages into text. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> The {@code TextDevice} object is basically used to extract text from pdf page. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Represents image device that save pdf document pages into Thumbnail image. |
| [TiffDevice](./tiffdevice/) | This class helps to save pdf document page by page into the one tiff image. |
| [TiffSettings](./tiffsettings/) | This class represents settings for importing pdf to Tiff. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Class represented indexed conversion types |
## Enums

| Enum | Description |
| --- | --- |
| [ColorDepth](./colordepth/) | Used to specify the parameter value passed to a Tiff image device. |
| [CompressionType](./compressiontype/) | Used to specify the parameter value passed to a Tiff image device. |
| [ShapeType](./shapetype/) | This enum represents shape type for the extracted images. |
