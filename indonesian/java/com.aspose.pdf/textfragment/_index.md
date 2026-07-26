---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili fragmen teks Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya. // Open document."
type: docs
weight: 5110
url: /id/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Mewakili fragmen teks Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya. // Buka dokumen Document doc = new Document("input.pdf"); // Temukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Ubah teks dan font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("output.pdf"); </pre> <hr> <pre> Secara singkat, objek {@code TextFragment} berisi daftar objek {@code TextSegment}. Secara rinci: Teks dokumen pdf dalam {@code com.aspose.pdf} direpresentasikan oleh dua objek dasar: {@code TextFragment} dan {@code TextSegment} Perbedaan di antara keduanya sebagian besar bergantung pada konteks. Mari pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk beroperasi dengannya, mengubah propertinya, melihat dll. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> Representasi fisik teks pdf sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.Pdf pada dasarnya menetapkan bahwa objek {@code TextFragment} menyediakan satu set operasi logika atas kumpulan objek {@code TextSegment} fisik yang mewakili kueri pengguna. Dalam skenario pencarian teks, {@code TextFragment} adalah representasi teks "hello world" secara logis, dan koleksi objek {@code TextSegment} mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, {@code TextFragment} mendekati representasi teks logis. Dan {@code TextSegment} mendekati representasi teks fisik. Jelas setiap objek {@code TextSegment} dapat memiliki font, warna, properti penempatan masing-masing. {@code TextFragment} menyediakan cara sederhana untuk mengubah teks beserta propertinya: mengatur font, mengatur ukuran font, mengatur warna font, dll. Sementara itu, objek {@code TextSegment} dapat diakses dan pengguna dapat beroperasi dengan objek {@code TextSegment} secara independen. <p> Perhatikan bahwa mengubah properti TextFragment dapat mengubah koleksi {@code Segments} internal karena TextFragment adalah objek agregat dan dapat menyusun ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah membiarkan koleksi {@code Segments} tidak berubah, silakan ubah segmen internal satu per satu. </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextFragment](#TextFragment--) | Menginisialisasi instance baru dari objek {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-) | Menginisialisasi instance baru dari objek {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Menginisialisasi instance baru dari objek {@code TextFragment}. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Menginisialisasi instance baru dari objek {@code TextFragment}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Duplikat fragmen dengan semua segmen. |
| [deepClone](#deepClone--) | Duplikat fragmen. |
| [getBaselinePosition](#getBaselinePosition--) | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks. |
| [getEndNote](#getEndNote--) | Mendapatkan catatan akhir paragraf.(hanya untuk pembuatan pdf) |
| [getFootNote](#getFootNote--) | Mendapatkan catatan kaki paragraf.(hanya untuk pembuatan pdf) |
| [getForm](#getForm--) | Mendapatkan objek form yang berisi TextFragment. Nilainya dapat null jika objek TextFragment tidak termasuk dalam form. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan perataan horizontal dari fragmen teks. |
| [getPage](#getPage--) | Mendapatkan halaman yang berisi TextFragment. Nilainya dapat null jika objek TextFragment tidak termasuk dalam halaman mana pun. |
| [getPosition](#getPosition--) | <p> Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. </p> |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang dari TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| [getSegments](#getSegments--) | <p> Mendapatkan segmen teks untuk {@code TextFragment} saat ini. </p> |
| [getText](#getText--) | <p> Mendapatkan objek teks {@code string} yang direpresentasikan oleh objek {@code TextFragment}. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [getTextState](#getTextState--) | <p> Mendapatkan atau mengatur status teks untuk teks yang direpresentasikan oleh objek {@code TextFragment}. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan perataan vertikal dari fragmen teks. |
| [getWrapLinesCount](#getWrapLinesCount--) | Mendapatkan jumlah baris pembungkus untuk paragraf ini(hanya untuk pembuatan pdf) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Mendapatkan {@code TextSegment}(s) yang merepresentasikan bagian tertentu dari teks {@code TextFragment}. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Menetapkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Menetapkan catatan akhir paragraf.(hanya untuk pembuatan pdf) |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Menetapkan catatan kaki paragraf.(hanya untuk pembuatan pdf) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Menetapkan perataan horizontal dari fragmen teks. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Menetapkan hyperlink fragmen |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Menetapkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Mendapatkan persegi panjang dari TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Mewakili metode setSegments |
| [setText](#setText-java.lang.String-) | <p> Mengatur objek teks {@code string} yang direpresentasikan oleh objek {@code TextFragment}. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal fragmen teks. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Mengatur jumlah baris pembungkus untuk paragraf ini (hanya untuk pembuatan pdf) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Menginisialisasi instance baru dari objek {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-}
Menginisialisasi instance baru dari objek {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Menginisialisasi instance baru dari objek {@code TextFragment}.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Menginisialisasi instance baru dari objek {@code TextFragment}.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Duplikat fragmen dengan semua segmen.

**Returns:**
Objek yang diklon.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Duplikat fragmen.

**Returns:**
Objek yang diklon.

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks.

**Returns:**
Nilai posisi

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Mendapatkan catatan akhir paragraf.(hanya untuk pembuatan pdf)

**Returns:**
Nilai catatan

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Mendapatkan catatan kaki paragraf.(hanya untuk pembuatan pdf)

**Returns:**
Nilai catatan

### getForm {#getForm--}
```
public XForm getForm()
```

Mendapatkan objek form yang berisi TextFragment. Nilainya dapat null jika objek TextFragment tidak termasuk dalam form.

**Returns:**
Nilai XForm

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Mendapatkan perataan horizontal dari fragmen teks.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Mendapatkan halaman yang berisi TextFragment. Nilainya dapat null jika objek TextFragment tidak termasuk dalam halaman mana pun.

**Returns:**
objek Page

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. </p>

**Returns:**
Nilai posisi <hr> <pre> Contoh ini menunjukkan cara melihat penempatan teks, yang direpresentasikan oleh objek {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang dari TextFragment

**Returns:**
objek Rectangle

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang.

**Returns:**
Instansi TextReplaceOptions

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Mendapatkan segmen teks untuk {@code TextFragment} saat ini. </p>

**Returns:**
Nilai TextSegmentCollection <hr> <pre> Contoh ini menunjukkan cara menavigasi semua objek {@code TextSegment} di dalam {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and output their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> Dalam beberapa kata, objek {@code TextSegment} adalah anak dari objek {@code TextFragment}. Pengguna lanjutan dapat mengakses segmen secara langsung untuk melakukan skenario pengeditan teks yang lebih kompleks. Untuk detail, silakan lihat deskripsi objek {@code TextFragment}. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Mendapatkan objek teks {@code string} yang direpresentasikan oleh objek {@code TextFragment}. </p>

**Returns:**
Nilai String <hr> <pre> Contoh ini menunjukkan cara mencari teks dan mengganti kemunculan pertama yang direpresentasikan dengan objek {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font.

**Returns:**
Instansi TextEditOptions

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Mendapatkan atau mengatur status teks untuk teks yang direpresentasikan oleh objek {@code TextFragment}. </p>

**Returns:**
Objek TextFragmentState <hr> <pre> Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Ubah warna latar depan pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Ubah ukuran font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Menyediakan cara untuk mengubah properti teks berikut: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Mendapatkan perataan vertikal dari fragmen teks.

**Returns:**
nilai int @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Mendapatkan jumlah baris pembungkus untuk paragraf ini(hanya untuk pembuatan pdf)

**Returns:**
nilai int

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Mendapatkan {@code TextSegment}(s) yang merepresentasikan bagian tertentu dari teks {@code TextFragment}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex |  | Posisi dalam teks dari mana {@code TextSegment}(s) baru akan dimulai. |
| panjang |  | Panjang teks yang akan diisolasi menjadi {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} yang berisi segmen teks yang mewakili substring teks yang dimulai pada posisi tertentu dan memiliki panjang yang ditentukan.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Menetapkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. YIndent dari struktur Position mewakili koordinat baseline dari fragmen teks.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Menetapkan catatan akhir paragraf.(hanya untuk pembuatan pdf)

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Menetapkan catatan kaki paragraf.(hanya untuk pembuatan pdf)

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Menetapkan perataan horizontal dari fragmen teks.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Menetapkan hyperlink fragmen

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Menetapkan posisi teks untuk teks, yang direpresentasikan dengan objek {@code TextFragment}. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Mendapatkan persegi panjang dari TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Mewakili metode setSegments

### setText {#setText-java.lang.String-}
<p> Mengatur objek teks {@code string} yang direpresentasikan oleh objek {@code TextFragment}. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Mendapatkan atau mengatur opsi penyuntingan teks. Opsi-opsi tersebut menentukan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal fragmen teks.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Mengatur jumlah baris pembungkus untuk paragraf ini (hanya untuk pembuatan pdf)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
