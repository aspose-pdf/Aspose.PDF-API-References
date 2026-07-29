---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk mengakses meta informasi dokumen PDF."
type: docs
weight: 490
url: /id/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Mewakili kelas untuk mengakses meta informasi dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Menginisialisasi facade. |
| [clearInfo](#clearInfo--) | Menghapus semua meta informasi dari dokumen PDF. |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [dispose](#dispose--) | Menutup semua sumber daya yang digunakan oleh instance ini. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [getAuthor](#getAuthor--) | Mendapatkan informasi Author dari dokumen PDF. |
| [getCreationDate](#getCreationDate--) | Mendapatkan informasi CreationDate dari dokumen PDF. |
| [getCreator](#getCreator--) | Mendapatkan informasi Creator dari dokumen PDF. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Mendapatkan pengaturan hak istimewa dokumen PDF. |
| [getHeader](#getHeader--) | <p> Mendapatkan informasi yang disesuaikan dari dokumen PDF. </p> |
| [getInputFile](#getInputFile--) | Mendapatkan file input. |
| [getInputStream](#getInputStream--) | Mendapatkan aliran input. |
| [getKeywords](#getKeywords--) | Mendapatkan informasi Kata Kunci dari dokumen PDF. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Mendapatkan informasi yang disesuaikan dari dokumen PDF dengan nama properti. Jika tidak ada properti yang cocok dengan nama tersebut, akan mengembalikan string kosong. |
| [getModDate](#getModDate--) | Mendapatkan informasi tanggal ModDate dari dokumen PDF. |
| [getNumberOfPages](#getNumberOfPages--) | Mendapatkan jumlah halaman dokumen. |
| [getPageHeight](#getPageHeight-int-) | Mendapatkan tinggi halaman yang ditentukan. |
| [getPageRotation](#getPageRotation-int-) | Mendapatkan rotasi halaman yang ditentukan. |
| [getPageWidth](#getPageWidth-int-) | Mendapatkan lebar halaman yang ditentukan. |
| [getPageXOffset](#getPageXOffset-int-) | Mendapatkan offset horizontal dari area tampilan halaman yang ditentukan. |
| [getPageYOffset](#getPageYOffset-int-) | Mendapatkan offset vertikal dari area tampilan halaman yang ditentukan. |
| [getPasswordType](#getPasswordType--) | Mengembalikan jenis kata sandi yang diberikan untuk membuat instance PdfFileInfo. Lihat nilai yang mungkin di {@code PasswordType}. Perhatikan bahwa dokumen pdf dapat dibuka menggunakan kata sandi pengguna (atau buka) dan kata sandi pemilik (atau izin, edit). |
| [getPdfVersion](#getPdfVersion--) | Mendapatkan informasi versi dokumen PDF. |
| [getProducer](#getProducer--) | Mendapatkan informasi Produsen dokumen PDF. |
| [getSubject](#getSubject--) | Mendapatkan informasi Subjek dokumen PDF. |
| [getTitle](#getTitle--) | Mendapatkan informasi Judul dokumen PDF. |
| [getUseStrictValidation](#getUseStrictValidation--) | Menggunakan aturan validasi ketat melalui properti {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | Mengembalikan true jika file input saat ini adalah file 'Portfolio' yang berisi kumpulan file PDF di dalamnya. |
| [hasEditPassword](#hasEditPassword--) | Mengembalikan true jika kata sandi diperlukan untuk mengubah izin atau properti keamanan dokumen. Perhatikan bahwa properti ini hanya dapat dibaca jika kata sandi yang valid diberikan dalam konstruktor {@code PdfFileInfo}. Jika PasswordType adalah Inaccessible (artinya kata sandi tidak valid diberikan) pembacaan properti ini akan gagal dengan {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Mengembalikan true jika kata sandi diperlukan untuk membuka dokumen pdf yang dilindungi kata sandi. |
| [isEncrypted](#isEncrypted--) | Memeriksa apakah dokumen PDF terenkripsi. |
| [isPdfFile](#isPdfFile--) | Memeriksa apakah input sumber adalah file PDF yang valid. |
| [save](#save-java.io.OutputStream-) | Menyimpan dokumen PDF ke file yang ditentukan. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Simpan dokumen PDF yang diperbarui ke aliran yang ditentukan. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Simpan dokumen PDF yang diperbarui ke file yang ditentukan. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Mengubah properti yang ditentukan secara eksplisit dengan mengatur informasi file, properti lainnya tetap. |
| [setAuthor](#setAuthor-java.lang.String-) | Mengatur informasi Penulis dokumen PDF. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Mengatur informasi CreationDate dokumen PDF. |
| [setCreator](#setCreator-java.lang.String-) | Mengatur informasi Creator dokumen PDF. |
| [setHeader](#setHeader-java.util.Map-) | Mengatur informasi yang disesuaikan dari dokumen PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Mengatur file input. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Mengatur aliran input. |
| [setKeywords](#setKeywords-java.lang.String-) | Mengatur informasi Kata Kunci dokumen PDF. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Mengatur informasi yang disesuaikan dokumen PDF. |
| [setModDate](#setModDate-java.lang.String-) | Mengatur informasi tanggal ModDate dokumen PDF. |
| [setSubject](#setSubject-java.lang.String-) | Mengatur informasi Subjek dokumen PDF. |
| [setTitle](#setTitle-java.lang.String-) | Mengatur informasi Judul dokumen PDF. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Menggunakan aturan validasi ketat melalui properti {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Menginisialisasi instance baru dari kelas com.aspose.pdf.facades.PdfFileInfo dengan nilai default.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Menginisialisasi facade.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Menghapus semua meta informasi dari dokumen PDF.

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Menutup semua sumber daya yang digunakan oleh instance ini. Metode ini sudah usang, gunakan close() sebagai gantinya.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Mendapatkan informasi Author dari dokumen PDF.

**Returns:**
nilai String

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Mendapatkan informasi CreationDate dari dokumen PDF.

**Returns:**
nilai String

### getCreator {#getCreator--}
```
public String getCreator()
```

Mendapatkan informasi Creator dari dokumen PDF.

**Returns:**
nilai String

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Mendapatkan pengaturan hak istimewa dokumen PDF.

**Returns:**
Pengaturan hak istimewa dokumen PDF.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Mendapatkan informasi yang disesuaikan dari dokumen PDF. </p>

**Returns:**
{@code Map<String, String>} objek

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Mendapatkan file input.

**Returns:**
nilai String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Mendapatkan aliran input.

**Returns:**
Objek InputStream

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Mendapatkan informasi Kata Kunci dari dokumen PDF.

**Returns:**
nilai String

### getMetaInfo {#getMetaInfo-java.lang.String-}
Mendapatkan informasi yang disesuaikan dari dokumen PDF dengan nama properti. Jika tidak ada properti yang cocok dengan nama tersebut, akan mengembalikan string kosong.

### getModDate {#getModDate--}
```
public String getModDate()
```

Mendapatkan informasi tanggal ModDate dari dokumen PDF.

**Returns:**
nilai String

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Mendapatkan jumlah halaman dokumen.

**Returns:**
nilai int

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Mendapatkan tinggi halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNum |  | Nomor halaman. |

**Returns:**
Tinggi halaman.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Mendapatkan rotasi halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNum |  | Nomor halaman. |

**Returns:**
Rotasi halaman. Nilainya dapat 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Mendapatkan lebar halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNum |  | Nomor halaman. |

**Returns:**
Lebar halaman.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Mendapatkan offset horizontal dari area tampilan halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNum |  | Nomor halaman. |

**Returns:**
Offset horizontal dari sisi kiri halaman.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Mendapatkan offset vertikal dari area tampilan halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNum |  | Nomor halaman. |

**Returns:**
Offset vertikal area tampilan halaman.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Mengembalikan jenis kata sandi yang diberikan untuk membuat instance PdfFileInfo. Lihat nilai yang mungkin di {@code PasswordType}. Perhatikan bahwa dokumen pdf dapat dibuka menggunakan kata sandi pengguna (atau buka) dan kata sandi pemilik (atau izin, edit).

**Returns:**
Elemen PasswordType @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Mendapatkan informasi versi dokumen PDF.

**Returns:**
String versi.

### getProducer {#getProducer--}
```
public String getProducer()
```

Mendapatkan informasi Produsen dokumen PDF.

**Returns:**
nilai String

### getSubject {#getSubject--}
```
public String getSubject()
```

Mendapatkan informasi Subjek dokumen PDF.

**Returns:**
nilai String

### getTitle {#getTitle--}
```
public String getTitle()
```

Mendapatkan informasi Judul dokumen PDF.

**Returns:**
nilai String

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Menggunakan aturan validasi ketat melalui properti {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
nilai boolean

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Mengembalikan true jika file input saat ini adalah file 'Portfolio' yang berisi kumpulan file PDF di dalamnya.

**Returns:**
nilai boolean

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Mengembalikan true jika kata sandi diperlukan untuk mengubah izin atau properti keamanan dokumen. Perhatikan bahwa properti ini hanya dapat dibaca jika kata sandi yang valid diberikan dalam konstruktor {@code PdfFileInfo}. Jika PasswordType adalah Inaccessible (artinya kata sandi tidak valid diberikan) pembacaan properti ini akan gagal dengan {@code InvalidPasswordException}.

**Returns:**
nilai boolean

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Mengembalikan true jika kata sandi diperlukan untuk membuka dokumen pdf yang dilindungi kata sandi.

**Returns:**
nilai boolean

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Memeriksa apakah dokumen PDF terenkripsi.

**Returns:**
nilai boolean

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Memeriksa apakah input sumber adalah file PDF yang valid.

**Returns:**
nilai boolean

### save {#save-java.io.OutputStream-}
Menyimpan dokumen PDF ke file yang ditentukan.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Simpan dokumen PDF yang diperbarui ke aliran yang ditentukan.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Simpan dokumen PDF yang diperbarui ke file yang ditentukan.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Mengubah properti yang ditentukan secara eksplisit dengan mengatur informasi file, properti lainnya tetap.

### setAuthor {#setAuthor-java.lang.String-}
Mengatur informasi Penulis dokumen PDF.

### setCreationDate {#setCreationDate-java.lang.String-}
Mengatur informasi CreationDate dokumen PDF.

### setCreator {#setCreator-java.lang.String-}
Mengatur informasi Creator dokumen PDF.

### setHeader {#setHeader-java.util.Map-}
Mengatur informasi yang disesuaikan dari dokumen PDF.

### setInputFile {#setInputFile-java.lang.String-}
Mengatur file input.

### setInputStream {#setInputStream-java.io.InputStream-}
Mengatur aliran input.

### setKeywords {#setKeywords-java.lang.String-}
Mengatur informasi Kata Kunci dokumen PDF.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Mengatur informasi yang disesuaikan dokumen PDF.

### setModDate {#setModDate-java.lang.String-}
Mengatur informasi tanggal ModDate dokumen PDF.

### setSubject {#setSubject-java.lang.String-}
Mengatur informasi Subjek dokumen PDF.

### setTitle {#setTitle-java.lang.String-}
Mengatur informasi Judul dokumen PDF.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Menggunakan aturan validasi ketat melalui properti {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
