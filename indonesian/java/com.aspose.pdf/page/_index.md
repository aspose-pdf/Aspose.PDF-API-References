---
title: "Page"
linktitle: "Page"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili halaman dokumen PDF."
type: docs
weight: 3310
url: /id/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Kelas yang mewakili halaman dokumen PDF.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek pengunjung {@code AnnotationSelector} yang menyediakan fungsionalitas untuk bekerja dengan anotasi. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Menerima objek pengunjung {@code ImagePlacementAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Menerima objek pengunjung {@code TextAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Menerima objek pengunjung {@code TextFragmentAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Menambahkan grafik ke halaman. Bekerja lebih cepat daripada menambahkan elemen satu per satu dengan metode GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Menambahkan grafik ke halaman. Bekerja lebih cepat daripada menambahkan elemen satu per satu dengan metode GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Menempatkan stempel ke halaman. Stempel dapat berupa nomor halaman, gambar, atau teks sederhana, misalnya logo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Mengonversi halaman saat ini menjadi bitmap BMP dan kemudian mengembalikan array byte. |
| [asXml](#asXml--) | Mengonversi halaman saat ini menjadi XML dengan enkoding UTF-8. |
| [calculateContentBBox](#calculateContentBBox--) | Menghitung nilai bbox - persegi panjang yang berisi konten tanpa margin yang terlihat. |
| [clearContents](#clearContents--) | Hanya untuk penggunaan internal |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Mengonversi halaman ke PNG untuk aliran gambar DSR, OMR, OCR. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Menghapus grafik dari halaman. Bekerja lebih cepat daripada menghapus elemen satu per satu dengan metode {@link GraphicElement#remove}. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Mebebaskan memori. Metode ini usang, gunakan close() sebagai gantinya. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Mengembalikan daftar operator yang menggunakan sumber daya dengan nama yang ditentukan. |
| [findReferences](#findReferences-java.lang.String-) | <p> Temukan referensi </p> |
| [flatten](#flatten--) | Menghapus semua bidang statis yang berada di halaman dan menempatkan nilai mereka sebagai gantinya. |
| [freeMemory](#freeMemory--) | Menghapus data yang di-cache |
| [getActions](#getActions--) | Mendapatkan koleksi properti halaman. |
| [getAnnotations](#getAnnotations--) | Mendapatkan koleksi anotasi halaman. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Mendapatkan art box halaman. </p> |
| [getArtifacts](#getArtifacts--) | Mendapatkan koleksi artefak pada halaman. |
| [getBackground](#getBackground--) | Mendapatkan warna latar belakang halaman. |
| [getBackgroundImage](#getBackgroundImage--) | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [getBleedBox](#getBleedBox--) | <p> Mendapatkan kotak bleed halaman. </p> |
| [getColorType](#getColorType--) | Mendapatkan tipe warna halaman berdasarkan informasi yang diperoleh dari operator SetColor, gambar, dan formulir. |
| [getContents](#getContents--) | <p> Mendapatkan koleksi operator dalam aliran konten halaman. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Mendapatkan appender konten saat ini. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Mendapatkan kotak crop halaman. </p> |
| [getDocument](#getDocument--) | Dapatkan dokumen |
| [getDuration](#getDuration--) | <p> Mendapatkan durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak didefinisikan. </p> <hr> Contoh menunjukkan cara mendapatkan durasi halaman <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Hanya untuk penggunaan internal |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Mendapatkan daftar objek Field dalam urutan Tab pada halaman ini. |
| [getFooter](#getFooter--) | Mendapatkan Footer halaman. |
| [getGroup](#getGroup--) | Mendapatkan kelas atribut grup yang menentukan atribut grup halaman untuk digunakan dalam model pencitraan transparan. |
| [getHeader](#getHeader--) | Mendapatkan header halaman. |
| [getLayers](#getLayers--) | Mendapatkan koleksi lapisan. |
| [getMediaBox](#getMediaBox--) | <p> Mendapatkan kotak media halaman. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Mendapatkan gaya garis untuk catatan. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [getNotifications](#getNotifications--) | Mengembalikan notifikasi tentang operasi internal dengan konten halaman. (Saat ini hanya notifikasi tentang peristiwa paragraf dalam skenario penambahan teks yang didukung.) |
| [getNumber](#getNumber--) | Dapatkan nomor halaman. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Acara untuk menyesuaikan header dan footer. |
| [getPageInfo](#getPageInfo--) | Mendapatkan info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [getPageRect](#getPageRect-boolean-) | Mengembalikan persegi panjang halaman sesuai dengan CropBox-nya (atau MediaBox jika CropBox null). |
| [getParagraphs](#getParagraphs--) | Mendapatkan paragraf. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Mengembalikan persegi panjang halaman sesuai dengan CropBox dan MediaBox; </p> Internal |
| [getRect](#getRect--) | <p> Mengembalikan persegi panjang halaman sesuai dengan CropBox dan MediaBox; Untuk get: kotak crop halaman dikembalikan jika ditentukan, jika tidak kotak media halaman dikembalikan. Untuk set: kotak media halaman selalu diatur. </p> |
| [getResources](#getResources--) | Mengambil sumber daya yang terkait dengan halaman. |
| [getResourcesField](#getResourcesField--) | <p> Mendapatkan sumber daya halaman. Objek Resources berisi koleksi gambar, formulir, dan font. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Mendapatkan rotasi halaman. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Mendapatkan matriks transformasi untuk halaman. |
| [getTabOrder](#getTabOrder--) | Mendapatkan urutan tab halaman. Nilai yang mungkin: Row, Column. Default, Manual |
| [getTocInfo](#getTocInfo--) | Mendapatkan informasi daftar isi. |
| [getTrimBox](#getTrimBox--) | <p> Mendapatkan kotak potong halaman. </p> |
| [getUserUnit](#getUserUnit--) | Mendapatkan atau mengatur nilai UserUnit. Angka positif yang memberikan ukuran satuan ruang pengguna default, dalam kelipatan 1 / 72 inci. Nilai default adalah 1. Silakan atur nilai nol atau negatif untuk menghapus entri ini pada halaman. |
| [getWatermark](#getWatermark--) | Mendapatkan watermark halaman. |
| [hasVectorGraphics](#hasVectorGraphics--) | Mendeteksi keberadaan grafik vektor, jika ada pada halaman. |
| [intToRotation](#intToRotation-int-) | Menerjemahkan nilai integer ke anggota enumerasi rotasi yang sesuai. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Mendapatkan atau mengatur penambahan paragraf setelah paragraf terakhir halaman. Nilai: Nilai menunjukkan apakah paragraf akan ditambahkan setelah paragraf terakhir halaman. Paragraf akan ditambahkan setelah paragraf terakhir halaman jika nilai bernilai true. |
| [isBlank](#isBlank-double-) | Mendapatkan flag apakah halaman kosong atau tidak. |
| [isBlank](#isBlank-double-boolean-) | Mendapatkan flag apakah halaman kosong atau tidak. |
| [makeGrayscale](#makeGrayscale--) | Mengonversi halaman ke skala abu-abu. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan dan Id grup konten opsional. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Hapus referensi objek |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Hapus referensi ke XObject dari konten halaman (misalnya semua operator Do yang menggunakan nama objek). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Mengubah ukuran halaman. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Menerjemahkan anggota enumerasi rotasi ke nilai integer. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Mendapatkan atau mengatur penambahan paragraf setelah paragraf terakhir halaman. Nilai: Nilai menunjukkan apakah paragraf akan ditambahkan setelah paragraf terakhir halaman. Paragraf akan ditambahkan setelah paragraf terakhir halaman jika nilai bernilai true. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Mengatur art box halaman. |
| [setBackground](#setBackground-java.awt.Color-) | Mengatur warna latar belakang halaman. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Mengatur warna latar belakang halaman. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Mengatur bleed box halaman. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Mengatur kotak pangkas halaman. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Mengatur durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak didefinisikan. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Hanya untuk penggunaan internal |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Mengatur Footer halaman. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Mengatur kelas atribut grup yang menentukan atribut grup halaman untuk digunakan dalam model pencitraan transparan. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Mengatur header halaman. |
| [setLayers](#setLayers-java.util.ArrayList-) | Mengatur koleksi lapisan. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Mengatur koleksi lapisan. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Mengatur media box halaman. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Mengatur gaya garis untuk catatan.(hanya untuk generator, tidak diisi saat membaca dokumen) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Mengatur info halaman.(hanya untuk generator, tidak diisi saat membaca dokumen). |
| [setPageSize](#setPageSize-double-double-) | Mengatur ukuran halaman. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Mengatur paragraf. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Mendapatkan atau mengatur persegi panjang halaman. Untuk mendapatkan: crop box halaman dikembalikan jika ditentukan, jika tidak media box halaman yang dikembalikan. Untuk mengatur: media box halaman selalu diatur. Harap dicatat bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, gunakan ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Mengatur rotasi halaman. |
| [setTabOrder](#setTabOrder-int-) | Mengatur urutan tab halaman. Nilai yang mungkin: Row, Column. Default, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Mengatur info daftar isi. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Atur transisi |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Mengatur trim box halaman. |
| [setUserUnit](#setUserUnit-double-) | Mendapatkan atau mengatur nilai UserUnit. Angka positif yang memberikan ukuran satuan ruang pengguna default, dalam kelipatan 1 / 72 inci. Nilai default adalah 1. Silakan atur nilai nol atau negatif untuk menghapus entri ini pada halaman. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Mengatur watermark halaman. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Mencoba menyimpan grafik vektor jika ada pada halaman. Format penyimpanan adalah SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek pengunjung {@code AnnotationSelector} yang menyediakan fungsionalitas untuk bekerja dengan anotasi.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Menerima objek pengunjung {@code ImagePlacementAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek penempatan gambar.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Menerima objek pengunjung {@code TextAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Menerima objek pengunjung {@code TextFragmentAbsorber} yang menyediakan fungsionalitas untuk bekerja dengan objek teks.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Menambahkan grafik ke halaman. Bekerja lebih cepat daripada menambahkan elemen satu per satu dengan metode GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Menambahkan grafik ke halaman. Bekerja lebih cepat daripada menambahkan elemen satu per satu dengan metode GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Menambahkan gambar yang dapat dicari ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Menambahkan gambar ke halaman dan menempatkannya di tengah persegi panjang yang ditentukan sambil mempertahankan proporsi gambar.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Menempatkan stempel ke halaman. Stempel dapat berupa nomor halaman, gambar, atau teks sederhana, misalnya logo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Mengonversi halaman saat ini menjadi bitmap BMP dan kemudian mengembalikan array byte.

### asXml {#asXml--}
```
public String asXml()
```

Mengonversi halaman saat ini menjadi XML dengan enkoding UTF-8.

**Returns:**
String XML yang dikonversi.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Menghitung nilai bbox - persegi panjang yang berisi konten tanpa margin yang terlihat.

**Returns:**
Nilai Bbox - persegi panjang yang berisi konten tanpa margin yang terlihat

### clearContents {#clearContents--}
```
public void clearContents()
```

Hanya untuk penggunaan internal

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Mengonversi halaman ke PNG untuk aliran gambar DSR, OMR, OCR.

**Returns:**
Aliran gambar dalam array byte[].

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Menghapus grafik dari halaman. Bekerja lebih cepat daripada menghapus elemen satu per satu dengan metode {@link GraphicElement#remove}.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Mebebaskan memori. Metode ini usang, gunakan close() sebagai gantinya.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Mengembalikan daftar operator yang menggunakan sumber daya dengan nama yang ditentukan.

### findReferences {#findReferences-java.lang.String-}
<p> Temukan referensi </p>

### flatten {#flatten--}
```
public void flatten()
```

Menghapus semua bidang statis yang berada di halaman dan menempatkan nilai mereka sebagai gantinya.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Menghapus data yang di-cache

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Mendapatkan koleksi properti halaman.

**Returns:**
Nilai PageActionCollection

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Mendapatkan koleksi anotasi halaman. {@code Annotations}

**Returns:**
Nilai AnnotationCollection

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Mendapatkan art box halaman. </p>

**Returns:**
Nilai Rectangle <hr> <pre> Contoh menunjukkan cara mendapatkan art box halaman: Document document = new Document(\"sample.pdf\"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Mendapatkan koleksi artefak pada halaman.

**Returns:**
Nilai ArtifactCollection

### getBackground {#getBackground--}
```
public Color getBackground()
```

Mendapatkan warna latar belakang halaman.

**Returns:**
Nilai warna

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen).

**Returns:**
Instansi gambar

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Mendapatkan kotak bleed halaman. </p>

**Returns:**
Nilai Rectangle <hr> <pre> Contoh menunjukkan cara mendapatkan bleed box halaman: Document document = new Document(\"sample.pdf\"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Mendapatkan tipe warna halaman berdasarkan informasi yang diperoleh dari operator SetColor, gambar, dan formulir.

**Returns:**
Elemen ColorType @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Mendapatkan koleksi operator dalam aliran konten halaman. {@code OperatorCollection} </p>

**Returns:**
Objek OperatorCollection <hr> <pre> Contoh menunjukkan cara memindai aliran operator halaman. Document document = new Document(\"sample.pdf\"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Mendapatkan appender konten saat ini. {@code ContentsAppender}

**Returns:**
ContentsAppender nilai

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Mendapatkan kotak crop halaman. </p>

**Returns:**
Rectangle nilai <hr> <pre> Contoh menunjukkan cara mendapatkan crop box halaman: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Dapatkan dokumen

**Returns:**
objek IDocument

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Mendapatkan durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak didefinisikan. </p> <hr> Contoh menunjukkan cara mendapatkan durasi halaman <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
nilai double

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Hanya untuk penggunaan internal

**Returns:**
instansi internal

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Mendapatkan daftar objek Field dalam urutan Tab pada halaman ini.

**Returns:**
Daftar objek field

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Mendapatkan Footer halaman.

**Returns:**
Footer halaman.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Mendapatkan kelas atribut grup yang menentukan atribut grup halaman untuk digunakan dalam model pencitraan transparan.

**Returns:**
Group nilai

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Mendapatkan header halaman.

**Returns:**
Header halaman.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Mendapatkan koleksi lapisan.

**Returns:**
Nilai: koleksi lapisan.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Mendapatkan kotak media halaman. </p>

**Returns:**
Rectangle nilai <hr> <pre> Contoh menunjukkan cara mendapatkan media box halaman: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Mendapatkan gaya garis untuk catatan. (hanya untuk generator, tidak diisi saat membaca dokumen)

**Returns:**
GraphInfo nilai

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Mengembalikan notifikasi tentang operasi internal dengan konten halaman. (Saat ini hanya notifikasi tentang peristiwa paragraf dalam skenario penambahan teks yang didukung.)

**Returns:**
String yang mewakili notifikasi tentang operasi internal dengan konten halaman.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Dapatkan nomor halaman.

**Returns:**
nilai int

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Acara untuk menyesuaikan header dan footer.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instansi}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Mendapatkan info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen).

**Returns:**
Informasi halaman.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Mengembalikan persegi panjang halaman sesuai dengan CropBox-nya (atau MediaBox jika CropBox null).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| considerRotation |  | Jika true maka rotasi halaman akan dipertimbangkan dalam perhitungan rect. |

**Returns:**
Rectangle halaman.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Mendapatkan paragraf.

**Returns:**
Paragraf.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Mengembalikan persegi panjang halaman sesuai dengan CropBox dan MediaBox; </p> Internal

**Returns:**
Rectangle nilai <hr> <pre> Contoh menunjukkan cara mendapatkan rectangle halaman: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Mengembalikan persegi panjang halaman sesuai dengan CropBox dan MediaBox; Untuk get: kotak crop halaman dikembalikan jika ditentukan, jika tidak kotak media halaman dikembalikan. Untuk set: kotak media halaman selalu diatur. </p>

**Returns:**
Rectangle nilai <hr> <pre> Contoh menunjukkan cara mendapatkan rectangle halaman: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Mengambil sumber daya yang terkait dengan halaman.

**Returns:**
Sebuah {@code Resources}({@link #getResources()}) objek yang mewakili sumber daya halaman.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Mendapatkan sumber daya halaman. Objek Resources berisi koleksi gambar, formulir, dan font. {@code Resources} </p>

**Returns:**
Resources nilai <hr> <pre> Contoh menunjukkan pemindaian gambar halaman: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Mendapatkan rotasi halaman. </p>

**Returns:**
Elemen Rotation <hr> <pre> Contoh menunjukkan cara menentukan rotasi halaman. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Mendapatkan matriks transformasi untuk halaman.

**Returns:**
Matrix nilai

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Mendapatkan urutan tab halaman. Nilai yang mungkin: Row, Column. Default, Manual

**Returns:**
TabOrder nilai @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Mendapatkan informasi daftar isi.

**Returns:**
Info daftar isi - default null. Jika diatur, halaman ini akan berisi daftar isi.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Mendapatkan kotak potong halaman. </p>

**Returns:**
Rectangle nilai <hr> <pre> Contoh menunjukkan cara mendapatkan trim box halaman: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Mendapatkan atau mengatur nilai UserUnit. Angka positif yang memberikan ukuran satuan ruang pengguna default, dalam kelipatan 1 / 72 inci. Nilai default adalah 1. Silakan atur nilai nol atau negatif untuk menghapus entri ini pada halaman.

**Returns:**
nilai double

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Mendapatkan watermark halaman.

**Returns:**
Watermark nilai

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Mendeteksi keberadaan grafik vektor, jika ada pada halaman.

**Returns:**
True jika halaman berisi operator konstruksi path; jika tidak, False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Menerjemahkan nilai integer ke anggota enumerasi rotasi yang sesuai.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotasi |  | Nilai integer untuk dikonversi |

**Returns:**
Anggota enumerasi Rotation @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Mendapatkan atau mengatur penambahan paragraf setelah paragraf terakhir halaman. Nilai: Nilai menunjukkan apakah paragraf akan ditambahkan setelah paragraf terakhir halaman. Paragraf akan ditambahkan setelah paragraf terakhir halaman jika nilai bernilai true.

**Returns:**
nilai boolean

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Mendapatkan flag apakah halaman kosong atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillThresholdFactor |  | Nilai ambang pengisian yang mengatur sensitivitas deteksi. Harus berada dalam rentang [0..1). Untuk menentukan apakah sebuah halaman kosong atau tidak, rasio ruang yang terisi terhadap total ruang halaman dihitung. Rasio ini dibandingkan dengan parameter fillThresholdFactor dan jika lebih kecil, halaman dianggap kosong. |

**Returns:**
nilai boolean True - jika halaman kosong; jika tidak, false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Mendapatkan flag apakah halaman kosong atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillThresholdFactor |  | Nilai ambang pengisian yang mengatur sensitivitas deteksi. Harus sama dengan atau lebih besar dari 0.01. |
| parseWhiteContent |  | True untuk pemindaian halaman lengkap dengan analisis konten putih, False (default) - algoritma cepat, di mana grafik putih dihitung sebagai halaman tidak kosong. |

**Returns:**
nilai boolean True - jika halaman kosong; jika tidak, false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Mengonversi halaman ke skala abu-abu.

### mergeLayers {#mergeLayers-java.lang.String-}
Menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Menggabungkan semua lapisan pada halaman menjadi satu lapisan dengan nama lapisan baru yang ditentukan dan Id grup konten opsional.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Hapus referensi objek

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Hapus referensi ke XObject dari konten halaman (misalnya semua operator Do yang menggunakan nama objek).

### resize {#resize-com.aspose.pdf.PageSize-}
Mengubah ukuran halaman.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Menerjemahkan anggota enumerasi rotasi ke nilai integer.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Mengirim halaman untuk diproses dengan perangkat halaman yang diberikan.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Mendapatkan atau mengatur penambahan paragraf setelah paragraf terakhir halaman. Nilai: Nilai menunjukkan apakah paragraf akan ditambahkan setelah paragraf terakhir halaman. Paragraf akan ditambahkan setelah paragraf terakhir halaman jika nilai bernilai true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Mengatur art box halaman.

### setBackground {#setBackground-java.awt.Color-}
Mengatur warna latar belakang halaman.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Mengatur warna latar belakang halaman.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Mengatur bleed box halaman.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Mengatur kotak pangkas halaman. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Mengatur durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak didefinisikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | durasi tampilan halaman. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Hanya untuk penggunaan internal

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Mengatur Footer halaman.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Mengatur kelas atribut grup yang menentukan atribut grup halaman untuk digunakan dalam model pencitraan transparan.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Mengatur header halaman.

### setLayers {#setLayers-java.util.ArrayList-}
Mengatur koleksi lapisan.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Mengatur koleksi lapisan.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Mengatur media box halaman.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Mengatur gaya garis untuk catatan.(hanya untuk generator, tidak diisi saat membaca dokumen)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Mengatur info halaman.(hanya untuk generator, tidak diisi saat membaca dokumen).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Mengatur ukuran halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar halaman. |
| tinggi |  | Ukuran halaman. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Mengatur paragraf.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Mendapatkan atau mengatur persegi panjang halaman. Untuk mendapatkan: crop box halaman dikembalikan jika ditentukan, jika tidak media box halaman yang dikembalikan. Untuk mengatur: media box halaman selalu diatur. Harap dicatat bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, gunakan ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Mengatur rotasi halaman.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Mengatur urutan tab halaman. Nilai yang mungkin: Row, Column. Default, Manual

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Objek TabOrder @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Mengatur info daftar isi.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Atur transisi

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Mengatur trim box halaman.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Mendapatkan atau mengatur nilai UserUnit. Angka positif yang memberikan ukuran satuan ruang pengguna default, dalam kelipatan 1 / 72 inci. Nilai default adalah 1. Silakan atur nilai nol atau negatif untuk menghapus entri ini pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Mengatur watermark halaman.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Mencoba menyimpan grafik vektor jika ada pada halaman. Format penyimpanan adalah SVG.
