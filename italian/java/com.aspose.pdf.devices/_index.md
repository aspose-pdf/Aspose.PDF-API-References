---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il pacchetto com.aspose.pdf.devices fornisce classi utilizzate per rappresentare il documento come immagini o testo semplice."
type: docs
weight: 140
url: /it/java/com.aspose.pdf.devices/
---
Il pacchetto com.aspose.pdf.devices fornisce classi utilizzate per rappresentare il documento come immagini o testo semplice.

## Classi

| Classe | Descrizione |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Rappresenta un dispositivo immagine che aiuta a salvare le pagine di un documento PDF in BMP. |
| [Device](./device/) | Classe astratta per tutti i tipi di dispositivi. Il dispositivo è usato per rappresentare un documento PDF in qualche formato. Ad esempio, la pagina del documento può essere rappresentata come immagine o testo. |
| [DicomDevice](./dicomdevice/) | Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in formato Dicom. |
| [DocumentDevice](./documentdevice/) | Classe astratta per tutti i dispositivi utilizzata per elaborare l'intero documento pdf. |
| [EmfDevice](./emfdevice/) | Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in emf. |
| [FormPresentationMode](./formpresentationmode/) | Utilizzato per specificare la modalità di presentazione del modulo durante la stampa o la conversione in documenti pdf immagine. |
| [GifDevice](./gifdevice/) | Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in gif. |
| [GraphicsDevice](./graphicsdevice/) | Rappresenta un dispositivo immagine che aiuta a renderizzare le pagine del documento pdf in grafica. |
| [ImageDevice](./imagedevice/) | Una classe astratta per dispositivi immagine. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in jpeg. |
| [Margins](./margins/) | Questa classe rappresenta i margini di un'immagine. |
| [PageDevice](./pagedevice/) | Classe astratta per tutti i dispositivi utilizzata per elaborare una determinata pagina del documento pdf. |
| [PngDevice](./pngdevice/) | Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in png. |
| [Resolution](./resolution/) | Rappresenta una classe per contenere la risoluzione dell'immagine. |
| [TextDevice](./textdevice/) | <p> Rappresenta una classe per convertire le pagine del documento pdf in testo. </p> <hr> <pre> L'esempio dimostra come estrarre il testo dalla prima pagina del documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> L'oggetto {@code TextDevice} è fondamentalmente usato per estrarre il testo dalla pagina pdf. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Rappresenta un dispositivo immagine che salva le pagine del documento pdf in un'immagine Thumbnail. |
| [TiffDevice](./tiffdevice/) | Questa classe aiuta a salvare le pagine del documento pdf una per una in un'unica immagine tiff. |
| [TiffSettings](./tiffsettings/) | Questa classe rappresenta le impostazioni per l'importazione di pdf in Tiff. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Classe che rappresenta i tipi di conversione indicizzati |
## Enums

| Enum | Descrizione |
| --- | --- |
| [ColorDepth](./colordepth/) | Utilizzato per specificare il valore del parametro passato a un dispositivo immagine Tiff. |
| [CompressionType](./compressiontype/) | Utilizzato per specificare il valore del parametro passato a un dispositivo immagine Tiff. |
| [ShapeType](./shapetype/) | Questo enum rappresenta il tipo di forma per le immagini estratte. |
