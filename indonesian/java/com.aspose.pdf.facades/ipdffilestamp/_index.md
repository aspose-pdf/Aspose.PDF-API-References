---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Antarmuka untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF."
type: docs
weight: 320
url: /id/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

Antarmuka untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF.

## Fields

| Field | Deskripsi |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posisi kiri bawah. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posisi tengah bawah. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posisi kanan bawah. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posisi kiri. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posisi kanan. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posisi kiri atas. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posisi tengah atas. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posisi kanan atas. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Menambahkan footer ke halaman dokumen. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Menambahkan footer ke halaman dokumen. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Menambahkan gambar sebagai footer halaman. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Menambahkan gambar sebagai footer halaman. |
| [addFooter](#addFooter-java.lang.String-float-) | Menambahkan gambar sebagai footer ke halaman dokumen. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Menambahkan gambar sebagai footer halaman. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Menambahkan header ke halaman. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Menambahkan header ke halaman file. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Menambahkan gambar sebagai header pada halaman. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Menambahkan gambar di bagian atas halaman. |
| [addHeader](#addHeader-java.lang.String-float-) | Menambahkan gambar sebagai header ke halaman file. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Menambahkan gambar sebagai header pada halaman. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Menambahkan nomor halaman ke halaman. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Menambahkan nomor halaman pada posisi yang ditentukan di halaman. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Menambahkan nomor halaman ke halaman. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Menambahkan nomor halaman ke halaman dokumen. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Menambahkan nomor halaman ke file. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Menambahkan nomor halaman pada posisi yang ditentukan di halaman. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Menambahkan nomor halaman ke halaman. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Menambahkan nomor halaman ke halaman dokumen. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Menambahkan stempel ke file. |
| [close](#close--) | Menutup file yang dibuka dan menyimpan perubahan. |
| [dispose](#dispose--) | Usang. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [getDocument](#getDocument--) | Mendapatkan dokumen yang sedang dikerjakan oleh PdfFileStamp. |
| [getInputFile](#getInputFile--) | Mendapatkan nama dan jalur file input. |
| [getInputStream](#getInputStream--) | Mendapatkan aliran masukan. |
| [getKeepSecurity](#getKeepSecurity--) | Menjaga keamanan jika benar. |
| [getOutputFile](#getOutputFile--) | Mendapatkan nama dan jalur file keluaran. |
| [getOutputStream](#getOutputStream--) | Mendapatkan aliran keluaran. |
| [getPageHeight](#getPageHeight--) | Mendapatkan tinggi halaman pertama dalam file sumber. |
| [getPageNumberRotation](#getPageNumberRotation--) | Mendapatkan rotasi nomor halaman. |
| [getPageWidth](#getPageWidth--) | Mendapatkan lebar halaman pertama dalam file masukan. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Mendapatkan atau mengatur nomor awal untuk halaman pertama dalam file masukan. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Mengatur nama dan jalur file masukan. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Mengatur aliran masukan. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Atur Jaga Keamanan |
| [setOutputFile](#setOutputFile-java.lang.String-) | Mengatur nama dan jalur file keluaran. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Mengatur atau mengatur aliran keluaran. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Mengatur rotasi nomor halaman. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Mengatur nomor awal untuk halaman pertama dalam file masukan. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Posisi kiri bawah.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Posisi tengah bawah.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Posisi kanan bawah.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Posisi kiri.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Posisi kanan.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Posisi kiri atas.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Posisi tengah atas.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Posisi kanan atas.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Menambahkan footer ke halaman dokumen.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Menambahkan footer ke halaman dokumen.

### addFooter {#addFooter-java.io.InputStream-float-}
Menambahkan gambar sebagai footer halaman.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Menambahkan gambar sebagai footer halaman.

### addFooter {#addFooter-java.lang.String-float-}
Menambahkan gambar sebagai footer ke halaman dokumen.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Menambahkan gambar sebagai footer halaman.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Menambahkan header ke halaman.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Menambahkan header ke halaman file.

### addHeader {#addHeader-java.io.InputStream-float-}
Menambahkan gambar sebagai header pada halaman.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Menambahkan gambar di bagian atas halaman.

### addHeader {#addHeader-java.lang.String-float-}
Menambahkan gambar sebagai header ke halaman file.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Menambahkan gambar sebagai header pada halaman.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Menambahkan nomor halaman ke halaman.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Menambahkan nomor halaman pada posisi yang ditentukan di halaman.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Menambahkan nomor halaman ke halaman.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Menambahkan nomor halaman ke halaman dokumen.

### addPageNumber {#addPageNumber-java.lang.String-}
Menambahkan nomor halaman ke file.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Menambahkan nomor halaman pada posisi yang ditentukan di halaman.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Menambahkan nomor halaman ke halaman.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Menambahkan nomor halaman ke halaman dokumen.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Menambahkan stempel ke file.

### close {#close--}
```
void close()
```

Menutup file yang dibuka dan menyimpan perubahan.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Usang.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

**Returns:**
nilai String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

**Returns:**
Elemen ContentDisposition

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Mendapatkan dokumen yang sedang dikerjakan oleh PdfFileStamp.

**Returns:**
objek IDocument

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Mendapatkan nama dan jalur file input.

**Returns:**
Objek String

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Mendapatkan aliran masukan.

**Returns:**
Objek InputStream

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Menjaga keamanan jika benar.

**Returns:**
nilai boolean

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Mendapatkan nama dan jalur file keluaran.

**Returns:**
Objek String

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Mendapatkan aliran keluaran.

**Returns:**
objek OutputStream

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Mendapatkan tinggi halaman pertama dalam file sumber.

**Returns:**
nilai float

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Mendapatkan rotasi nomor halaman.

**Returns:**
nilai float

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Mendapatkan lebar halaman pertama dalam file masukan.

**Returns:**
nilai float

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

**Returns:**
Objek SaveOptions

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Mendapatkan atau mengatur nomor awal untuk halaman pertama dalam file masukan.

**Returns:**
nilai int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Mengatur bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF.

### setInputFile {#setInputFile-java.lang.String-}
Mengatur nama dan jalur file masukan.

### setInputStream {#setInputStream-java.io.InputStream-}
Mengatur aliran masukan.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Atur Jaga Keamanan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOutputFile {#setOutputFile-java.lang.String-}
Mengatur nama dan jalur file keluaran.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Mengatur atau mengatur aliran keluaran.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Mengatur rotasi nomor halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Mengatur nomor awal untuk halaman pertama dalam file masukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
