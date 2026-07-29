---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. Document doc = new."
type: docs
weight: 190
url: /id/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> Mewakili kelas untuk mengonversi halaman dokumen pdf menjadi teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> Objek {@code TextDevice} pada dasarnya digunakan untuk mengekstrak teks dari halaman pdf. </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextDevice](#TextDevice--) | Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode. |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode. |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> Mendapatkan enkoding teks yang diekstrak. </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> Mendapatkan enkoding teks yang diekstrak. </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> Mendapatkan opsi ekstraksi teks. </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> Mengonversi halaman dan menyimpannya sebagai aliran teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // buat perangkat teks TextDevice device = new TextDevice(); // konversi halaman dan simpan teks ke aliran device.process(doc.getPages().get_Item(1), ms); // gunakan teks yang diekstrak extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Mengonversi halaman dan menyimpannya sebagai aliran teks. |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | Mengatur enkoding teks yang diekstrak. |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> Mengatur enkoding teks yang diekstrak. </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Mengatur opsi ekstraksi teks. </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode.

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode.

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Menginisialisasi sebuah instance baru dari {@code TextDevice} dengan mode pemformatan teks Raw dan enkoding teks Unicode.

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> Mendapatkan enkoding teks yang diekstrak. </p>

**Returns:**
Charset element <hr> <pre> Contoh ini menunjukkan cara merepresentasikan teks yang diekstrak dalam enkoding UTF-8. Document doc = new Document(inFile); String extractedText; // buat perangkat teks TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // konversi halaman dan simpan teks ke aliran device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> Mendapatkan enkoding teks yang diekstrak. </p>

**Returns:**
TextEncodingInternal element <hr> <pre> Contoh ini menunjukkan cara merepresentasikan teks yang diekstrak dalam enkoding UTF-8. Document doc = new Document(inFile); String extractedText; // buat perangkat teks TextDevice device = new TextDevice(java.nio.charset.Charset.forName("UTF-8")); // konversi halaman dan simpan teks ke aliran device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Mendapatkan opsi ekstraksi teks. </p>

**Returns:**
TextExtractionOptions element <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks dalam urutan mentah. Document doc = new Document(inFile); String extractedText; // buat perangkat teks TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // konversi halaman dan simpan teks ke aliran device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> Mengonversi halaman dan menyimpannya sebagai aliran teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // buat perangkat teks TextDevice device = new TextDevice(); // konversi halaman dan simpan teks ke aliran device.process(doc.getPages().get_Item(1), ms); // gunakan teks yang diekstrak extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Mengonversi halaman dan menyimpannya sebagai aliran teks.

### setEncoding {#setEncoding-java.nio.charset.Charset-}
Mengatur enkoding teks yang diekstrak.

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> Mengatur enkoding teks yang diekstrak. </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Mengatur opsi ekstraksi teks. </p>
