---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Das com.aspose.pdf.devices‑Paket stellt Klassen bereit, die zur Darstellung von Dokumenten als Bild(er) oder als Klartext verwendet werden."
type: docs
weight: 140
url: /de/java/com.aspose.pdf.devices/
---
Das com.aspose.pdf.devices‑Paket stellt Klassen bereit, die zur Darstellung von Dokumenten als Bild(er) oder als Klartext verwendet werden.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im BMP-Format hilft. |
| [Device](./device/) | Abstrakte Klasse für alle Gerätetypen. Das Gerät wird verwendet, um ein PDF-Dokument in einem bestimmten Format darzustellen. Beispielsweise kann eine Dokumentenseite als Bild oder Text dargestellt werden. |
| [DicomDevice](./dicomdevice/) | Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im DICOM-Format hilft. |
| [DocumentDevice](./documentdevice/) | Abstrakte Klasse für alle Geräte, die verwendet wird, um das gesamte PDF-Dokument zu verarbeiten. |
| [EmfDevice](./emfdevice/) | Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im EMF-Format hilft. |
| [FormPresentationMode](./formpresentationmode/) | Wird verwendet, um den Präsentationsmodus des Formulars beim Drucken oder Konvertieren in Bild-PDF-Dokumente festzulegen. |
| [GifDevice](./gifdevice/) | Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im GIF-Format hilft. |
| [GraphicsDevice](./graphicsdevice/) | Stellt ein Bildgerät dar, das beim Rendern von PDF-Dokumentseiten in Grafiken hilft. |
| [ImageDevice](./imagedevice/) | Eine abstrakte Klasse für Bildgeräte. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im JPEG-Format hilft. |
| [Margins](./margins/) | Diese Klasse stellt die Ränder eines Bildes dar. |
| [PageDevice](./pagedevice/) | Abstrakte Klasse für alle Geräte, die verwendet wird, um bestimmte Seiten des PDF-Dokuments zu verarbeiten. |
| [PngDevice](./pngdevice/) | Stellt ein Bildgerät dar, das beim Speichern von PDF-Dokumentseiten im PNG-Format hilft. |
| [Resolution](./resolution/) | Stellt eine Klasse dar, die die Bildauflösung hält. |
| [TextDevice](./textdevice/) | <p> Stellt eine Klasse zum Konvertieren von PDF-Dokumentseiten in Text dar. </p> <hr> <pre> Das Beispiel zeigt, wie man Text auf der ersten PDF-Dokumentseite extrahiert. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> Das {@code TextDevice}-Objekt wird im Wesentlichen verwendet, um Text aus einer PDF-Seite zu extrahieren. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Stellt ein Bildgerät dar, das PDF-Dokumentseiten in ein Miniaturbild speichert. |
| [TiffDevice](./tiffdevice/) | Diese Klasse hilft dabei, PDF-Dokumentseiten einzeln in ein einziges TIFF‑Bild zu speichern. |
| [TiffSettings](./tiffsettings/) | Diese Klasse repräsentiert Einstellungen für den Import von PDF nach TIFF. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Klasse, die indizierte Konvertierungstypen darstellt |
## Enums

| Enum | Beschreibung |
| --- | --- |
| [ColorDepth](./colordepth/) | Wird verwendet, um den Parameterwert an ein TIFF‑Bildgerät zu übergeben. |
| [CompressionType](./compressiontype/) | Wird verwendet, um den Parameterwert an ein TIFF‑Bildgerät zu übergeben. |
| [ShapeType](./shapetype/) | Dieses Aufzählungsfeld repräsentiert den Formtyp für die extrahierten Bilder. |
