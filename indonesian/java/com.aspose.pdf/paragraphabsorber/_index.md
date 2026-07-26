---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili objek penyerap dari objek struktur halaman seperti bagian dan paragraf. Melakukan pencarian untuk bagian dan paragraf teks serta menyediakan akses untuk."
type: docs
weight: 3470
url: /id/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Mewakili objek absorber dari objek struktur halaman seperti bagian dan paragraf. Melakukan pencarian untuk bagian dan paragraf teks serta menyediakan akses ke persegi panjang dan poligon yang menggambarkannya dalam ruang koordinat teks. Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragments} yang dikelompokkan berdasarkan elemen struktur. </p> Contoh ini menunjukkan cara menemukan segmen teks pertama dari setiap paragraf pada halaman pertama dokumen PDF dan menyorotnya. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Ketika pencarian selesai, koleksi {@code ParagraphAbsorber.PageMarkups} akan berisi objek {@code PageMarkup} yang mewakili struktur halaman oleh koleksi {@code MarkupSection} dan {@code MarkupParagraph}. Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Mendapatkan koleksi {@code PageMarkup} yang diserap. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Mendapatkan ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Itu berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom). </p><hr> Meningkatkan nilai ini dapat menyebabkan penurunan kinerja minor tanpa perubahan yang terlihat pada hasil pencarian. Menurunkan nilai ini dapat menyebabkan penentuan paragraf yang tidak tepat dalam bagian. Kami tidak merekomendasikan untuk mengatur nilai lebih rendah dari default jika Anda tidak menginginkan hanya elemen 'kasar' dari struktur halaman. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Mendapatkan atau mengatur TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Mengatur ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Itu berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom). </p><hr> Meningkatkan nilai ini dapat menyebabkan penurunan kinerja minor tanpa perubahan yang terlihat pada hasil pencarian. Menurunkan nilai ini dapat menyebabkan penentuan paragraf yang tidak tepat dalam bagian. Kami tidak merekomendasikan untuk mengatur nilai lebih rendah dari default jika Anda tidak menginginkan hanya elemen 'kasar' dari struktur halaman. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Mendapatkan atau mengatur TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Melakukan pencarian untuk bagian dan paragraf pada {@link Document} yang ditentukan. |
| [visit](#visit-com.aspose.pdf.Page-) | Melakukan pencarian pada {@code Page} yang ditentukan. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sectionsSearchDepth |  | Jumlah pencarian berurutan untuk elemen struktur yang lebih halus yang akan dilakukan. <hr> Lihat properti {@code ParagraphAbsorber.SectionsSearchDepth} untuk petunjuk lebih lanjut tentang parameter ini. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Menginisialisasi instance baru dari {@code ParagraphAbsorber} yang melakukan pencarian untuk bagian/paragraf dari dokumen atau halaman.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Mendapatkan koleksi {@code PageMarkup} yang diserap.

**Returns:**
Daftar instance PageMarkup

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Mendapatkan ParagraphAbsorberOptions.

**Returns:**
Instance ParagraphAbsorberOptions

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Itu berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom). </p><hr> Meningkatkan nilai ini dapat menyebabkan penurunan kinerja minor tanpa perubahan yang terlihat pada hasil pencarian. Menurunkan nilai ini dapat menyebabkan penentuan paragraf yang tidak tepat dalam bagian. Kami tidak merekomendasikan untuk mengatur nilai lebih rendah dari default jika Anda tidak menginginkan hanya elemen 'kasar' dari struktur halaman.

**Returns:**
nilai int

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Mendapatkan atau mengatur TextReplaceOptions.

**Returns:**
Instansi TextReplaceOptions

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya.

**Returns:**
nilai boolean

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Mengatur ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan. Kedalaman pencarian default adalah 3. Itu berarti tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom). </p><hr> Meningkatkan nilai ini dapat menyebabkan penurunan kinerja minor tanpa perubahan yang terlihat pada hasil pencarian. Menurunkan nilai ini dapat menyebabkan penentuan paragraf yang tidak tepat dalam bagian. Kami tidak merekomendasikan untuk mengatur nilai lebih rendah dari default jika Anda tidak menginginkan hanya elemen 'kasar' dari struktur halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Mendapatkan atau mengatur TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Melakukan pencarian untuk bagian dan paragraf pada {@link Document} yang ditentukan.

### visit {#visit-com.aspose.pdf.Page-}
Melakukan pencarian pada {@code Page} yang ditentukan.
