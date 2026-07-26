---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili objek absorber dari fragmen teks. Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p>"
type: docs
weight: 5120
url: /id/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Mewakili objek absorber dari fragmen teks. Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Objek {@code TextFragmentAbsorber} pada dasarnya digunakan dalam skenario pencarian teks. Ketika pencarian selesai, kemunculan tersebut direpresentasikan dengan objek {@code TextFragment} yang terdapat dalam koleksi {@code TextFragmentAbsorber.TextFragments}. Objek {@code TextFragment} menyediakan akses ke teks kemunculan pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Inisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Menerapkan ukuran font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan iterasi melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya serupa dengan iterasi. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Menerapkan font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan iterasi melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya serupa dengan iterasi. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Menerapkan font dan ukuran untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan iterasi melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya serupa dengan iterasi. |
| [getErrors](#getErrors--) | Daftar objek {@code TextExtractionError}. Berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| [getExtractionOptions](#getExtractionOptions--) | Mendapatkan opsi ekstraksi teks. |
| [getPhrase](#getPhrase--) | <p> Mendapatkan frasa yang dicari oleh {@code TextFragmentAbsorber} pada dokumen PDF atau halaman. </p> |
| [getRegexResults](#getRegexResults--) | Mendapatkan kamus dari kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan {@link TextFragment} sebagai nilai. Contoh ini menunjukkan cara menemukan teks dengan array ekspresi reguler pada halaman pertama dokumen PDF. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Mendapatkan teks yang diekstrak yang {@code TextAbsorber} ekstrak pada dokumen atau halaman PDF. |
| [getTextEditOptions](#getTextEditOptions--) | Mendapatkan opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [getTextFragments](#getTextFragments--) | <p> Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek {@code TextFragment}. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Mendapatkan opsi pencarian. Opsi-opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Menghapus semua teks dari dokumen. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Menghapus semua teks dari halaman yang ditentukan. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Menghapus teks di dalam persegi panjang yang ditentukan dari halaman yang ditentukan. |
| [reset](#reset--) | Menghapus koleksi TextFragments dari objek {@code TextFragmentAbsorber} ini. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Mengatur opsi ekstraksi teks. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Mengatur frasa yang {@code TextFragmentAbsorber} cari pada dokumen atau halaman PDF. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Mengatur opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Mengatur koleksi kejadian pencarian yang disajikan dengan objek {@code TextFragment}. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Mengatur opsi penggantian teks. Opsi-opsi tersebut mendefinisikan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Mengatur opsi pencarian. Opsi-opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Melakukan pencarian pada dokumen yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada dokumen PDF dan mengganti teks dari semua kejadian pencarian. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Melakukan pencarian pada halaman yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Melakukan pencarian pada objek form yang ditentukan. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Menginisialisasi instance baru dari {@code TextFragmentAbsorber} yang melakukan pencarian semua segmen teks dari dokumen atau halaman. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Mengatur absorber untuk mencari semua "hello world" text occurrences absorber.setPhrase ( "hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}.</p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Menerapkan ukuran font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan iterasi melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya serupa dengan iterasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSize |  | Ukuran font teks. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Menerapkan font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan iterasi melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya serupa dengan iterasi.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Menerapkan font dan ukuran untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan iterasi melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya serupa dengan iterasi.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Daftar objek {@code TextExtractionError}. Berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja.

**Returns:**
Daftar objek TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

Mendapatkan opsi ekstraksi teks.

**Returns:**
Objek TextExtractionOptions

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Mendapatkan frasa yang dicari oleh {@code TextFragmentAbsorber} pada dokumen PDF atau halaman. </p>

**Returns:**
Nilai string <hr> <pre> Contoh ini menunjukkan cara melakukan pencarian teks beberapa kali dan melakukan penggantian teks. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Membuat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // mencari kata lain dan menggantinya absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Mendapatkan kamus dari kejadian pencarian yang disajikan dengan kelas System.Text.RegularExpressions.Regex sebagai kunci dan {@link TextFragment} sebagai nilai. Contoh ini menunjukkan cara menemukan teks dengan array ekspresi reguler pada halaman pertama dokumen PDF. // Open document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Instansi Dictionary

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Mendapatkan teks yang diekstrak yang {@code TextAbsorber} ekstrak pada dokumen atau halaman PDF.

**Returns:**
Nilai string Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // membuka dokumen Document doc = new Document(inFile); // membuat objek TextAbsorber untuk mengekstrak teks TextAbsorber absorber = new TextAbsorber(); // menerima absorber untuk semua halaman dokumen doc.getPages().accept(absorber); // mendapatkan teks yang diekstrak String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Mendapatkan opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font.

**Returns:**
Objek TextEditOptions

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Mendapatkan koleksi kejadian pencarian yang disajikan dengan objek {@code TextFragment}. </p>

**Returns:**
Objek TextFragmentCollection <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti semua kemunculan pencarian dengan teks baru. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Menemukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Membuat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Menerima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Mengubah teks pada semua kemunculan pencarian for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang.

**Returns:**
Nilai TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Mendapatkan opsi pencarian. Opsi-opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler. </p>

**Returns:**
Objek TextSearchOptions <hr> <pre> Contoh ini menunjukkan cara melakukan pencarian teks menggunakan ekspresi reguler. // Membuka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Membuat objek TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // mengatur absorber untuk mencari semua kata yang dimulai dengan 'h' dan diakhiri dengan 'o' menggunakan ekspresi reguler. absorber.setPhrase ( "h\w*?o"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // kita harus menemukan kata "hello" dan menggantinya dengan "Hi" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // Menyimpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja.

**Returns:**
nilai boolean

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Menghapus semua teks dari dokumen.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Menghapus semua teks dari halaman yang ditentukan.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Menghapus teks di dalam persegi panjang yang ditentukan dari halaman yang ditentukan.

### reset {#reset--}
```
public void reset()
```

Menghapus koleksi TextFragments dari objek {@code TextFragmentAbsorber} ini.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Mengatur opsi ekstraksi teks.

### setPhrase {#setPhrase-java.lang.String-}
<p> Mengatur frasa yang {@code TextFragmentAbsorber} cari pada dokumen atau halaman PDF. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Mengatur opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Mengatur koleksi kejadian pencarian yang disajikan dengan objek {@code TextFragment}. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Mengatur opsi penggantian teks. Opsi-opsi tersebut mendefinisikan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Mengatur opsi pencarian. Opsi-opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Melakukan pencarian pada dokumen yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada dokumen PDF dan mengganti teks pada semua temuan pencarian. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Melakukan pencarian pada halaman yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks tersebut. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( \"hi world\"); } // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Melakukan pencarian pada objek form yang ditentukan.
