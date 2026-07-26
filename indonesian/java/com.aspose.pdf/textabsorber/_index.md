---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili objek absorber teks. Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek {@code TextAbsorber.Text}. </p> <hr> <pre> Contoh."
type: docs
weight: 4900
url: /id/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Mewakili objek absorber teks. Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek {@code TextAbsorber.Text}. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Objek {@code TextAbsorber} digunakan untuk mengekstrak teks dari dokumen Pdf atau halaman dokumen tersebut. </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getErrors](#getErrors--) | Daftar objek {@code TextExtractionError}. Berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Mendapatkan opsi ekstraksi teks. </p> <hr> <pre> Contoh menunjukkan cara mengatur mode pemformatan teks Pure dan melakukan ekstraksi teks. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Memungkinkan untuk menentukan mode pemformatan teks {@code TextExtractionOptions} selama ekstraksi. Mode default adalah {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Mendapatkan teks yang diekstrak oleh {@code TextAbsorber} pada dokumen atau halaman PDF. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Mendapatkan opsi pencarian teks. Memungkinkan untuk menentukan persegi panjang yang membatasi teks yang diekstrak. Secara default persegi panjang kosong. Itu berarti batas halaman saja yang menentukan wilayah ekstraksi teks. |
| [hasErrors](#hasErrors--) | Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Mengatur opsi ekstraksi teks. </p> <hr> <pre> Contoh menunjukkan cara mengatur mode pemformatan teks Pure dan melakukan ekstraksi teks. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Memungkinkan untuk menentukan mode pemformatan teks {@code TextExtractionOptions} selama ekstraksi. Mode default adalah {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Mengatur opsi pencarian teks. Memungkinkan untuk menentukan persegi panjang yang membatasi teks yang diekstrak. Secara default persegi panjang kosong. Itu berarti batas halaman saja yang menentukan wilayah ekstraksi teks. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Ekstrak teks pada dokumen yang ditentukan </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Ekstrak teks pada halaman yang ditentukan </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Ekstrak teks pada XForm yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Menginisialisasi instance baru dari {@code TextAbsorber}. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Melakukan ekstraksi teks dan menyediakan akses ke teks yang diekstrak melalui objek {@code TextAbsorber.Text}. </p>

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

<p> Mendapatkan opsi ekstraksi teks. </p> <hr> <pre> Contoh menunjukkan cara mengatur mode pemformatan teks Pure dan melakukan ekstraksi teks. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Memungkinkan untuk menentukan mode pemformatan teks {@code TextExtractionOptions} selama ekstraksi. Mode default adalah {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
Nilai TextExtractionOptions

### getText {#getText--}
```
public String getText()
```

<p> Mendapatkan teks yang diekstrak oleh {@code TextAbsorber} pada dokumen atau halaman PDF. </p>

**Returns:**
String value <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks dari semua halaman dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Mendapatkan opsi pencarian teks. Memungkinkan untuk menentukan persegi panjang yang membatasi teks yang diekstrak. Secara default persegi panjang kosong. Itu berarti batas halaman saja yang menentukan wilayah ekstraksi teks.

**Returns:**
Nilai TextSearchOptions

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks. Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja.

**Returns:**
nilai boolean

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Mengatur opsi ekstraksi teks. </p> <hr> <pre> Contoh menunjukkan cara mengatur mode pemformatan teks Pure dan melakukan ekstraksi teks. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Memungkinkan untuk menentukan mode pemformatan teks {@code TextExtractionOptions} selama ekstraksi. Mode default adalah {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Mengatur opsi pencarian teks. Memungkinkan untuk menentukan persegi panjang yang membatasi teks yang diekstrak. Secara default persegi panjang kosong. Itu berarti batas halaman saja yang menentukan wilayah ekstraksi teks.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Ekstrak teks pada dokumen yang ditentukan </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Ekstrak teks pada halaman yang ditentukan </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Ekstrak teks pada XForm yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre>
