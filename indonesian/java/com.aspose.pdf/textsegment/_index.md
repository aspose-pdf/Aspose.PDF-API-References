---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili segmen teks Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek {@code TextState} dari objek {@code TextSegment}. // Buka dokumen Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Buat objek TextFragmentAbsorber untuk menemukan semua \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Terima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Ubah warna latar depan segmen teks pertama dari kemunculan teks pertama absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Ubah ukuran font segmen teks pertama dari kemunculan teks pertama absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Simpan dokumen doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>"
type: docs
weight: 5300
url: /id/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Representasi fisik teks pdf sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.PDF pada dasarnya menetapkan bahwa {@code TextFragment} objek menyediakan satu set operasi logika atas kumpulan {@code TextSegment} fisik yang mewakili kueri pengguna. Dalam skenario pencarian teks, {@code TextFragment} adalah representasi teks "hello world" secara logis, dan koleksi objek {@code TextSegment} mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, {@code TextFragment} mendekati representasi teks logis. Dan {@code TextSegment} mendekati representasi teks fisik. Jelas setiap objek {@code TextSegment} dapat memiliki font, warna, properti posisi masing-masing. {@code TextFragment} menyediakan cara sederhana untuk mengubah teks dengan propertinya: mengatur font, mengatur ukuran font, mengatur warna font, dll. Sementara objek {@code TextSegment} dapat diakses dan pengguna dapat beroperasi dengan objek {@code TextSegment} secara independen. </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Membuat objek TextSegment. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks, dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Membuat objek TextSegment. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks, dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}. YIndent dari struktur Position mewakili koordinat garis dasar segmen teks. |
| [getCharacters](#getCharacters--) | Mendapatkan koleksi objek CharInfo yang merepresentasikan informasi tentang karakter dalam segmen teks. |
| [getEndCharIndex](#getEndCharIndex--) | Mendapatkan indeks karakter akhir dari segmen saat ini dalam operator tampilkan teks (Tj, TJ). |
| [getHyperlink](#getHyperlink--) | Mendapatkan atau mengatur hyperlink segmen (untuk pembuat pdf). |
| [getPosition](#getPosition--) | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang dari TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | Mendapatkan indeks karakter awal dari segmen saat ini dalam operator tampilkan teks (Tj, TJ). |
| [getText](#getText--) | Mendapatkan objek teks {@code string} yang direpresentasikan oleh objek {@code TextSegment}. |
| [getTextEditOptions](#getTextEditOptions--) | Mendapatkan opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [getTextState](#getTextState--) | <p> Mendapatkan atau mengatur keadaan teks untuk teks yang direpresentasikan oleh objek {@code TextSegment}. </p> <hr> <p> Menyediakan cara untuk mengubah properti teks berikut: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Mengatur posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}. YIndent dari struktur Position mewakili koordinat garis dasar segmen teks. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Mendapatkan atau mengatur hyperlink segmen (untuk pembuat pdf). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Mengatur posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}. |
| [setText](#setText-java.lang.String-) | Mengatur objek teks {@code string} yang direpresentasikan oleh objek {@code TextSegment}. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Mengatur opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Mengatur keadaan teks untuk teks yang direpresentasikan oleh objek {@code TextSegment}. </p> <hr> <p> Menyediakan cara untuk mengubah properti teks berikut: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Mengatur objek teks {@code string} yang direpresentasikan oleh objek {@code TextSegment} dengan pembaruan yang ditekan. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Membuat objek TextSegment. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks, dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Membuat objek TextSegment. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek fragmen teks, menambahkan segmen teks ke koleksi fragmen teks, dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}. YIndent dari struktur Position mewakili koordinat garis dasar segmen teks.

**Returns:**
Nilai posisi

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Mendapatkan koleksi objek CharInfo yang merepresentasikan informasi tentang karakter dalam segmen teks.

**Returns:**
Objek CharInfoCollection

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Mendapatkan indeks karakter akhir dari segmen saat ini dalam operator tampilkan teks (Tj, TJ).

**Returns:**
nilai int

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Mendapatkan atau mengatur hyperlink segmen (untuk pembuat pdf).

**Returns:**
Objek Hyperlink

### getPosition {#getPosition--}
```
public Position getPosition()
```

Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}.

**Returns:**
Nilai posisi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang dari TextSegment

**Returns:**
objek Rectangle

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Mendapatkan indeks karakter awal dari segmen saat ini dalam operator tampilkan teks (Tj, TJ).

**Returns:**
nilai int

### getText {#getText--}
```
public String getText()
```

Mendapatkan objek teks {@code string} yang direpresentasikan oleh objek {@code TextSegment}.

**Returns:**
nilai String

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Mendapatkan opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font.

**Returns:**
Nilai TextEditOptions

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Mendapatkan atau mengatur keadaan teks untuk teks yang direpresentasikan oleh objek {@code TextSegment}. </p> <hr> <p> Menyediakan cara untuk mengubah properti teks berikut: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
Nilai TextState

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Mengatur posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}. YIndent dari struktur Position mewakili koordinat garis dasar segmen teks.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Mendapatkan atau mengatur hyperlink segmen (untuk pembuat pdf).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Mengatur posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextSegment}.

### setText {#setText-java.lang.String-}
Mengatur objek teks {@code string} yang direpresentasikan oleh objek {@code TextSegment}.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Mengatur opsi penyuntingan teks. Opsi-opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Mengatur keadaan teks untuk teks yang direpresentasikan oleh objek {@code TextSegment}. </p> <hr> <p> Menyediakan cara untuk mengubah properti teks berikut: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Mengatur objek teks {@code string} yang direpresentasikan oleh objek {@code TextSegment} dengan pembaruan yang ditekan.
