---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada."
type: docs
weight: 500
url: /id/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konstruktor. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Konstruktor. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Tidak diimplementasikan. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Tidak diimplementasikan. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Tidak diimplementasikan. |
| [close](#close--) | Menutup objek PdfFileMend. |
| [dispose](#dispose--) | Menutup objek PdfFileMend. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [getDocument](#getDocument--) | Mendapatkan dokumen {@code PdfFileMend} yang sedang diproses. |
| [getInputFile](#getInputFile--) | Mendapatkan file input. |
| [getInputStream](#getInputStream--) | Mendapatkan aliran input. |
| [getOutputFile](#getOutputFile--) | Mendapatkan file output. |
| [getOutputStream](#getOutputStream--) | Mendapatkan aliran output. |
| [getTextPositioningMode](#getTextPositioningMode--) | Mendapatkan strategi penempatan teks. {@code PositioningMode} Mode default adalah Legacy. |
| [getWrapMode](#getWrapMode--) | Mendapatkan algoritma pembungkus kata. |
| [save](#save-java.io.OutputStream-) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [save](#save-java.lang.String-) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [setInputFile](#setInputFile-java.lang.String-) | Usang. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Mengatur aliran input. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Mengatur file output. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Metode ini sudah tidak direkomendasikan. Gunakan metode Save(outputStream) untuk mendapatkan hasil facade. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Mengatur strategi penempatan teks. {@code PositioningMode} Mode default adalah Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Mengatur nilai boolean yang menunjukkan pembungkus kata dalam metode AddText. Jika nilai true, teks dalam FormattedText akan dibungkus. Secara default, nilai adalah false. |
| [setWrapMode](#setWrapMode-int-) | Mengatur algoritma pembungkus kata. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktor.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Konstruktor.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Konstruktor.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Konstruktor.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Menambahkan gambar ke halaman tertentu dari dokumen PDF pada koordinat yang ditentukan. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Tidak diimplementasikan.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Tidak diimplementasikan.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Tidak diimplementasikan.

### close {#close--}
```
public void close()
```

Menutup objek PdfFileMend.

### dispose {#dispose--}
```
public void dispose()
```

Menutup objek PdfFileMend. Metode ini sudah usang, gunakan close() sebagai gantinya.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Mendapatkan dokumen {@code PdfFileMend} yang sedang diproses.

**Returns:**
objek IDocument

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Mendapatkan file input.

**Returns:**
nilai String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Mendapatkan aliran input.

**Returns:**
aliran input.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Mendapatkan file output.

**Returns:**
nilai String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Mendapatkan aliran output.

**Returns:**
aliran output.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Mendapatkan strategi penempatan teks. {@code PositioningMode} Mode default adalah Legacy.

**Returns:**
Elemen PositioningMode @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Mendapatkan algoritma pembungkus kata.

**Returns:**
nilai WordWrapMode @see WordWrapMode

### save {#save-java.io.OutputStream-}
Menyimpan dokumen PDF ke file yang ditentukan.

### save {#save-java.lang.String-}
Menyimpan dokumen PDF ke file yang ditentukan.

### setInputFile {#setInputFile-java.lang.String-}
Usang.

### setInputStream {#setInputStream-java.io.InputStream-}
Mengatur aliran input.

### setOutputFile {#setOutputFile-java.lang.String-}
Mengatur file output.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Metode ini sudah tidak direkomendasikan. Gunakan metode Save(outputStream) untuk mendapatkan hasil facade.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Mengatur strategi penempatan teks. {@code PositioningMode} Mode default adalah Legacy.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen PositioningMode @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Mengatur nilai boolean yang menunjukkan pembungkus kata dalam metode AddText. Jika nilai true, teks dalam FormattedText akan dibungkus. Secara default, nilai adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Mengatur algoritma pembungkus kata.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen WordWrapMode @see WordWrapMode |
