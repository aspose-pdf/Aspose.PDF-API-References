---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Aspose.PDF för Java API-referens"
description: "com.aspose.pdf.devices‑paketet tillhandahåller klasser som används för att representera ett dokument som bild(er) eller som vanlig text."
type: docs
weight: 140
url: /sv/java/com.aspose.pdf.devices/
---
com.aspose.pdf.devices‑paketet tillhandahåller klasser som används för att representera ett dokument som bild(er) eller som vanlig text.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som BMP. |
| [Device](./device/) | Abstrakt klass för alla typer av enheter. Enhet används för att representera PDF-dokument i något format. Till exempel kan dokumentets sida representeras som en bild eller text. |
| [DicomDevice](./dicomdevice/) | Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor i DICOM-format. |
| [DocumentDevice](./documentdevice/) | Abstrakt klass för alla enheter som används för att bearbeta hela PDF-dokumentet. |
| [EmfDevice](./emfdevice/) | Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som EMF. |
| [FormPresentationMode](./formpresentationmode/) | Används för att ange formulärets presentationsläge vid utskrift eller konvertering till bild-PDF-dokument. |
| [GifDevice](./gifdevice/) | Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som GIF. |
| [GraphicsDevice](./graphicsdevice/) | Representerar en bildenhet som hjälper till att rendera PDF-dokumentets sidor till grafik. |
| [ImageDevice](./imagedevice/) | En abstrakt klass för bildenheter. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som JPEG. |
| [Margins](./margins/) | Denna klass representerar marginaler för en bild. |
| [PageDevice](./pagedevice/) | Abstrakt klass för alla enheter som används för att bearbeta en viss sida i PDF-dokumentet. |
| [PngDevice](./pngdevice/) | Representerar en bildenhet som hjälper till att spara PDF-dokumentets sidor som PNG. |
| [Resolution](./resolution/) | Representerar en klass för att hålla bildens upplösning. |
| [TextDevice](./textdevice/) | <p> Representerar en klass för att konvertera PDF-dokumentets sidor till text. </p> <hr> <pre> Exemplet visar hur man extraherar text på den första PDF-dokumentets sida. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // skapa textenhet TextDevice device = new TextDevice(); // konvertera sidan och spara text till strömmen device.process(doc.getPages().get_Item(1), ms); // använd den extraherade texten extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> Objektet {@code TextDevice} används i princip för att extrahera text från en PDF-sida. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Representerar en bildenhet som sparar PDF-dokumentets sidor som miniatyrbild. |
| [TiffDevice](./tiffdevice/) | Denna klass hjälper till att spara pdf-dokument sida för sida i en enda tiff-bild. |
| [TiffSettings](./tiffsettings/) | Denna klass representerar inställningar för att importera pdf till Tiff. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Klassen representerade indexerade konverteringstyper |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [ColorDepth](./colordepth/) | Används för att ange parametervärdet som skickas till en Tiff-bildenhet. |
| [CompressionType](./compressiontype/) | Används för att ange parametervärdet som skickas till en Tiff-bildenhet. |
| [ShapeType](./shapetype/) | Denna enum representerar formtyp för de extraherade bilderna. |
