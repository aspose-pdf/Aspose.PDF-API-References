---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Melakukan pencarian font. Mencari dalam font yang terpasang di sistem dan font Pdf standar. Juga menyediakan fungsi untuk membuka font khusus. </p> <hr> <pre> Contoh menunjukkan.</pre>"
type: docs
weight: 1690
url: /id/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Melakukan pencarian font. Mencari dalam font yang terpasang di sistem dan font Pdf standar. Juga menyediakan fungsi untuk membuka font khusus. </p> <hr> <pre> Contoh menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Tambahkan satu jalur lagi ke font. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Tambahkan font sistem dengan font yang ditentukan. </p> <hr> <pre> Contoh menunjukkan cara menambahkan font sistem. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Mencari dan mengembalikan font dengan nama font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial"); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Mencari dan mengembalikan font dengan nama font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Salinan daftar dengan direktori font yang sebenarnya. |
| [getSources](#getSources--) | Mendapatkan koleksi sumber font. |
| [getSubstitutions](#getSubstitutions--) | Mendapatkan koleksi strategi substitusi font. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Jika font tidak ditemukan, akan diganti dengan font standar. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Mengembalikan status konfigurasi penyimpanan Sumber Font. <br> Jika true, digunakan ThreadStatic dan setiap thread memiliki Sumber Font masing-masing. <br> Jika false, digunakan konfigurasi statis global untuk semua thread. </p> <hr> Nilai default adalah True. |
| [loadFonts](#loadFonts--) | Mengimpor font yang terpasang di sistem dan font Pdf standar. Metode ini dirancang untuk mempercepat proses pemuatan font. Secara default, font dimuat pada permintaan pertama untuk font apa pun. Penggunaan metode ini memuat font sistem dan font Pdf standar segera sebelum dokumen Pdf apa pun dibuka. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Membuka font dengan aliran font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara membuka font dan mengganti font teks pada halaman pertama. // Buka font InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Membuka font dengan jalur file font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara membuka font dan mengganti font teks pada halaman pertama. // Buka font Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Membuka font dengan jalur file font dan jalur file metrik yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara membuka font Type1 dengan metrik dan mengganti font teks pada halaman pertama. // Buka font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Buka dokumen Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Simpan dokumen doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Memuat ulang semua font yang ditentukan oleh properti {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Mengembalikan daftar untuk direktori font standar secara default. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Menetapkan daftar pengguna dengan jalur font |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Setel TRUE jika perlu mengganti font yang tidak ditemukan dengan font default. Nilai default adalah false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Opsi untuk mengatur konfigurasi penyimpanan Sumber Font. Jika true, menggunakan ThreadStatic dan setiap thread memiliki Sumber Font masing‑masing. Jika false, menggunakan konfigurasi statis global untuk semua thread. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Tambahkan satu jalur lagi ke font.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Tambahkan font sistem dengan font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menambahkan font sistem. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Mencari dan mengembalikan font dengan nama font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial"); // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Mencari dan mengembalikan font dengan nama font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua teks "hello world" occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua teks "hello world" occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua teks "hello world" occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Salinan daftar dengan direktori font yang sebenarnya.

**Returns:**
daftar String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Mendapatkan koleksi sumber font.

**Returns:**
objek FontSourceCollection

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Mendapatkan koleksi strategi substitusi font.

**Returns:**
objek FontSubstitutionCollection

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Jika font tidak ditemukan, akan diganti dengan font standar.

**Returns:**
nilai boolean

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Mengembalikan status konfigurasi penyimpanan Sumber Font. <br> Jika true, digunakan ThreadStatic dan setiap thread memiliki Sumber Font masing-masing. <br> Jika false, digunakan konfigurasi statis global untuk semua thread. </p> <hr> Nilai default adalah True.

**Returns:**
nilai boolean

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Mengimpor font yang terpasang di sistem dan font Pdf standar. Metode ini dirancang untuk mempercepat proses pemuatan font. Secara default, font dimuat pada permintaan pertama untuk font apa pun. Penggunaan metode ini memuat font sistem dan font Pdf standar segera sebelum dokumen Pdf apa pun dibuka.

### openFont {#openFont-java.io.InputStream-int-}
<p> Membuka font dengan aliran font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara membuka font dan mengganti font teks pada halaman pertama. // Buka font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua teks "hello world" occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Membuka font dengan jalur file font yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara membuka font dan mengganti font teks pada halaman pertama. // Buka font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TextFragmentAbsorber untuk menemukan semua teks "hello world" occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Membuka font dengan jalur file font yang ditentukan dan jalur file metrik. </p> <hr> <pre> Contoh ini menunjukkan cara membuka font Type1 dengan metrik dan mengganti font teks pada halaman pertama. // Open font Font font = FontRepository.openFont(\"courier.pfb\", \"courier.afm\"); // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Memuat ulang semua font yang ditentukan oleh properti {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Mengembalikan daftar untuk direktori font standar secara default.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Menetapkan daftar pengguna dengan jalur font

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Setel TRUE jika perlu mengganti font yang tidak ditemukan dengan font default. Nilai default adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Opsi untuk mengatur konfigurasi penyimpanan Sumber Font. Jika true, menggunakan ThreadStatic dan setiap thread memiliki Sumber Font masing‑masing. Jika false, menggunakan konfigurasi statis global untuk semua thread.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isTheadLocal |  | nilai boolean |
