---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Paket com.aspose.pdf.devices menyediakan kelas yang digunakan untuk merepresentasikan dokumen sebagai gambar atau teks biasa."
type: docs
weight: 140
url: /id/java/com.aspose.pdf.devices/
---
Paket com.aspose.pdf.devices menyediakan kelas yang digunakan untuk merepresentasikan dokumen sebagai gambar atau teks biasa.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke dalam format bmp. |
| [Device](./device/) | Kelas abstrak untuk semua jenis perangkat. Perangkat digunakan untuk merepresentasikan dokumen pdf dalam beberapa format. Misalnya, halaman dokumen dapat direpresentasikan sebagai gambar atau teks. |
| [DicomDevice](./dicomdevice/) | Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke format Dicom. |
| [DocumentDevice](./documentdevice/) | Kelas abstrak untuk semua perangkat yang digunakan untuk memproses seluruh dokumen pdf. |
| [EmfDevice](./emfdevice/) | Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke emf. |
| [FormPresentationMode](./formpresentationmode/) | Digunakan untuk menentukan mode presentasi formulir saat mencetak atau mengonversi dokumen pdf menjadi gambar. |
| [GifDevice](./gifdevice/) | Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke gif. |
| [GraphicsDevice](./graphicsdevice/) | Mewakili perangkat gambar yang membantu merender halaman dokumen pdf ke grafik. |
| [ImageDevice](./imagedevice/) | Kelas abstrak untuk perangkat gambar. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke jpeg. |
| [Margins](./margins/) | Kelas ini mewakili margin sebuah gambar. |
| [PageDevice](./pagedevice/) | Kelas abstrak untuk semua perangkat yang digunakan untuk memproses halaman tertentu dari dokumen pdf. |
| [PngDevice](./pngdevice/) | Mewakili perangkat gambar yang membantu menyimpan halaman dokumen pdf ke png. |
| [Resolution](./resolution/) | Mewakili kelas untuk menyimpan resolusi gambar. |
| [TextDevice](./textdevice/) | <p> Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> Objek {@code TextDevice} pada dasarnya digunakan untuk mengekstrak teks dari halaman pdf. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Mewakili perangkat gambar yang menyimpan halaman dokumen pdf ke gambar Thumbnail. |
| [TiffDevice](./tiffdevice/) | Kelas ini membantu menyimpan halaman dokumen pdf satu per satu ke dalam satu gambar tiff. |
| [TiffSettings](./tiffsettings/) | Kelas ini mewakili pengaturan untuk mengimpor pdf ke Tiff. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Kelas yang mewakili tipe konversi terindeks |
## Enums

| Enum | Deskripsi |
| --- | --- |
| [ColorDepth](./colordepth/) | Digunakan untuk menentukan nilai parameter yang diteruskan ke perangkat gambar Tiff. |
| [CompressionType](./compressiontype/) | Digunakan untuk menentukan nilai parameter yang diteruskan ke perangkat gambar Tiff. |
| [ShapeType](./shapetype/) | Enum ini mewakili tipe bentuk untuk gambar yang diekstrak. |
