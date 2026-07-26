---
title: "Font"
linktitle: "Font"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili objek font. </p> <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mengubah font pada kemunculan pencarian pertama. // Open document Document doc.</pre>"
type: docs
weight: 1650
url: /id/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Mewakili objek font. </p> <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mengubah font pada kemunculan pencarian pertama. // Buka dokumen Document doc = new Document(\"input.pdf\"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Buat font dan tandai agar disematkan Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Simpan dokumen doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Metode

| Metode | Deskripsi |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Menentukan apakah font berisi karakter yang ditentukan |
| [getActualFontName](#getActualFontName--) | <p> Mendapatkan nama font aktual dari objek {@code Font} jika sudah diinisialisasi. Bahkan ketika font diganti atau memiliki nama internal untuk pdf. Atau string kosong jika font belum diinisialisasi. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Mengukur Titik Ascent maksimum. |
| [getBaseFont](#getBaseFont--) | Mendapatkan nilai BaseFont dari objek font PDF. Juga dikenal sebagai nama PostScript font. |
| [getDecodedFontName](#getDecodedFontName--) | Kadang-kadang font PDF (biasanya font Cina/Jepang/Korea) dapat memiliki nama font yang khusus. Nama ini adalah nilai properti font PDF "BaseFont" dan kadang properti ini dapat direpresentasikan dalam bentuk heksadesimal. Jika membaca nama ini secara langsung, dapat muncul dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, diperlukan mendekode nama font dengan aturan khusus untuk font ini. Properti ini mengembalikan nama font yang telah didekode, jadi gunakan untuk kasus ketika Anda menemui {@code FontName} yang tidak dapat dibaca. Jika properti {@code FontName} memiliki bentuk yang dapat dibaca, properti ini akan sama dengan {@code FontName}, sehingga Anda dapat menggunakan properti ini untuk semua kasus ketika Anda perlu mendapatkan nama font dalam bentuk yang dapat dibaca. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Mengukur Titik Descent maksimum. |
| [getFontName](#getFontName--) | <p> Mendapatkan nama font dari objek {@code Font}. </p> |
| [getFontOptions](#getFontOptions--) | Properti berguna untuk menyesuaikan perilaku Font |
| [getIFont](#getIFont--) | <p> Objek font sistem. </p> <hr> <p> Hanya untuk penggunaan internal </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Objek font PDF. </p> <hr> <p> Hanya untuk penggunaan internal </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Tujuan metode ini - mengembalikan deskripsi kesalahan jika upaya menyematkan font gagal. Jika tidak ada kasus kesalahan, metode ini mengembalikan string kosong. |
| [getType](#getType--) | Nama Tipe Font |
| [isAccessible](#isAccessible--) | <p> Mendapatkan indikasi apakah font hadir (terpasang) di sistem. </p> |
| [isEmbedded](#isEmbedded--) | <p> Mendapatkan nilai yang menunjukkan apakah font disematkan. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan </p> <hr> <pre> Contoh berikut menunjukkan cara menemukan font, menandainya sebagai disematkan, mencari teks pada halaman dokumen, dan mengganti font teks. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Mendapatkan nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan </p> <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mendapatkan nilai yang menunjukkan apakah font merupakan subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Mengukur string. |
| [save](#save-java.io.OutputStream-) | Menyimpan font ke dalam stream. Perhatikan bahwa font disimpan dalam format TTF menengah yang dimaksudkan hanya untuk digunakan dalam salinan dokumen asli yang telah dikonversi. File font tidak dimaksudkan untuk digunakan di luar konteks dokumen asli. |
| [setEmbedded](#setEmbedded-boolean-) | Mengatur nilai yang menunjukkan apakah font disematkan. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan |
| [setSubset](#setSubset-boolean-) | Mengatur nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Menentukan apakah font berisi karakter yang ditentukan

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Mendapatkan nama font aktual dari objek {@code Font} jika sudah diinisialisasi. Bahkan ketika font diganti atau memiliki nama internal untuk pdf. Atau string kosong jika font belum diinisialisasi. </p>

**Returns:**
Nilai string <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan melihat nama font aktual dari kemunculan teks pertama. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Mengukur Titik Ascent maksimum.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Mendapatkan nilai BaseFont dari objek font PDF. Juga dikenal sebagai nama PostScript font.

**Returns:**
nilai String

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Kadang-kadang font PDF (biasanya font Cina/Jepang/Korea) dapat memiliki nama font yang khusus. Nama ini adalah nilai properti font PDF "BaseFont" dan kadang properti ini dapat direpresentasikan dalam bentuk heksadesimal. Jika membaca nama ini secara langsung, dapat muncul dalam bentuk yang tidak dapat dibaca. Untuk mendapatkan bentuk yang dapat dibaca, diperlukan mendekode nama font dengan aturan khusus untuk font ini. Properti ini mengembalikan nama font yang telah didekode, jadi gunakan untuk kasus ketika Anda menemui {@code FontName} yang tidak dapat dibaca. Jika properti {@code FontName} memiliki bentuk yang dapat dibaca, properti ini akan sama dengan {@code FontName}, sehingga Anda dapat menggunakan properti ini untuk semua kasus ketika Anda perlu mendapatkan nama font dalam bentuk yang dapat dibaca.

**Returns:**
nilai String

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Mengukur Titik Descent maksimum.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Mendapatkan nama font dari objek {@code Font}. </p>

**Returns:**
Nilai string <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan melihat nama font dari kemunculan teks pertama. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Properti berguna untuk menyesuaikan perilaku Font

**Returns:**
objek IFontOptions

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Objek font sistem. </p> <hr> <p> Hanya untuk penggunaan internal </p>

**Returns:**
objek IFont

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Objek font PDF. </p> <hr> <p> Hanya untuk penggunaan internal </p>

**Returns:**
objek IPdfFont

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Tujuan metode ini - mengembalikan deskripsi kesalahan jika upaya menyematkan font gagal. Jika tidak ada kasus kesalahan, metode ini mengembalikan string kosong.

**Returns:**
Deskripsi kesalahan

### getType {#getType--}
```
public String getType()
```

Nama Tipe Font

**Returns:**
Objek String

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Mendapatkan indikasi apakah font hadir (terpasang) di sistem. </p>

**Returns:**
nilai boolean <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mendapatkan nilai yang menunjukkan apakah font terpasang di sistem. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("the font is installed in the system"); </pre> <hr> <p> Beberapa operasi tidak tersedia untuk font yang tidak dapat ditemukan di sistem. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Mendapatkan nilai yang menunjukkan apakah font disematkan. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan </p> <hr> <pre> Contoh berikut menunjukkan cara menemukan font, menandainya sebagai disematkan, mencari teks pada halaman dokumen, dan mengganti font teks. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
nilai boolean @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Mendapatkan nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan </p> <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mendapatkan nilai yang menunjukkan apakah font merupakan subset. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre>

**Returns:**
nilai boolean @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Mengukur string.

### save {#save-java.io.OutputStream-}
Menyimpan font ke dalam stream. Perhatikan bahwa font disimpan dalam format TTF menengah yang dimaksudkan hanya untuk digunakan dalam salinan dokumen asli yang telah dikonversi. File font tidak dimaksudkan untuk digunakan di luar konteks dokumen asli.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Mengatur nilai yang menunjukkan apakah font disematkan. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Mengatur nilai yang menunjukkan apakah font merupakan subset. Font berbasis IFont akan secara otomatis menjadi subset dan disematkan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
