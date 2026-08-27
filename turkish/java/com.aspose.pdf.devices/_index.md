---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu com.aspose.pdf.devices paketi, belgeyi görüntü(ler) veya düz metin olarak temsil etmek için kullanılan sınıflar sağlar."
type: docs
weight: 140
url: /tr/java/com.aspose.pdf.devices/
---
Bu com.aspose.pdf.devices paketi, belgeyi görüntü(ler) veya düz metin olarak temsil etmek için kullanılan sınıflar sağlar.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [BmpDevice](./bmpdevice/) | PDF belge sayfalarını bmp formatına kaydetmeye yardımcı olan görüntü cihazını temsil eder. |
| [Device](./device/) | Tüm cihaz türleri için soyut sınıf. Cihaz, PDF belgesini bir formatta temsil etmek için kullanılır. Örneğin, belge sayfası görüntü veya metin olarak temsil edilebilir. |
| [DicomDevice](./dicomdevice/) | Pdf belge sayfalarını Dicom formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder. |
| [DocumentDevice](./documentdevice/) | Tüm cihazlar için, bütün pdf belgesini işlemek için kullanılan soyut sınıf. |
| [EmfDevice](./emfdevice/) | Pdf belge sayfalarını emf formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder. |
| [FormPresentationMode](./formpresentationmode/) | Pdf belgelerini yazdırırken veya görüntüye dönüştürürken form sunum modunu belirtmek için kullanılır. |
| [GifDevice](./gifdevice/) | Pdf belge sayfalarını gif formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder. |
| [GraphicsDevice](./graphicsdevice/) | Pdf belge sayfalarını grafiklere render etmeye yardımcı olan görüntü cihazını temsil eder. |
| [ImageDevice](./imagedevice/) | Görüntü cihazları için soyut bir sınıf. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Pdf belge sayfalarını jpeg formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder. |
| [Margins](./margins/) | Bu sınıf bir görüntünün kenar boşluklarını temsil eder. |
| [PageDevice](./pagedevice/) | Pdf belgesinin belirli bir sayfasını işlemek için kullanılan tüm cihazlar için soyut sınıf. |
| [PngDevice](./pngdevice/) | Pdf belge sayfalarını png formatında kaydetmeye yardımcı olan görüntü cihazını temsil eder. |
| [Resolution](./resolution/) | Bu sınıf görüntü çözünürlüğünü tutmak için temsil eder. |
| [TextDevice](./textdevice/) | <p> Pdf belge sayfalarını metne dönüştürmek için sınıfı temsil eder. </p> <hr> <pre> The example demonstrates how to extract text on the first PDF document page. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> The {@code TextDevice} object is basically used to extract text from pdf page. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Pdf belge sayfalarını Küçük Resim (Thumbnail) görüntüsüne kaydeden görüntü cihazını temsil eder. |
| [TiffDevice](./tiffdevice/) | Bu sınıf, pdf belge sayfalarını tek bir tiff görüntüsüne sayfa sayfa kaydetmeye yardımcı olur. |
| [TiffSettings](./tiffsettings/) | Bu sınıf, pdf'yi Tiff'e aktarmak için ayarları temsil eder. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Sınıf, indeksli dönüşüm türlerini temsil eder. |
## Enums

| Enum | Açıklama |
| --- | --- |
| [ColorDepth](./colordepth/) | Tiff görüntü cihazına geçirilen parametre değerini belirtmek için kullanılır. |
| [CompressionType](./compressiontype/) | Tiff görüntü cihazına geçirilen parametre değerini belirtmek için kullanılır. |
| [ShapeType](./shapetype/) | Bu enum, çıkarılan görüntüler için şekil tipini temsil eder. |
