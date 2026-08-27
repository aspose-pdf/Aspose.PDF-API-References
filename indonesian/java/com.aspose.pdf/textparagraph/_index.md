---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili paragraf teks sebagai objek teks multiline. </p> <hr> <pre> Contoh menunjukkan cara membuat objek paragraf teks dan menambahkannya ke halaman Pdf. Document doc.</pre>"
type: docs
weight: 5200
url: /id/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Mewakili paragraf teks sebagai objek teks multiline. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek paragraf teks dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // buat paragraf teks TextParagraph paragraph = new TextParagraph(); // atur persegi panjang paragraf paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // atur opsi pembungkus kata paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // tambahkan baris string paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // tambahkan paragraf ke halaman Pdf dengan TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // simpan dokumen Pdf doc.save(outFile); </pre>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Membuat objek {@code TextParagraph}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Menambahkan baris teks |
| [appendLine](#appendLine-java.lang.String-float-) | Menambahkan baris teks. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Menambahkan baris teks dengan parameter keadaan teks. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Menambahkan baris teks dengan parameter keadaan teks |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Menambahkan baris teks dengan parameter keadaan teks. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Menambahkan baris teks dengan parameter keadaan teks. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Menambahkan baris teks dengan parameter keadaan teks |
| [beginEdit](#beginEdit--) | Memulai penyuntingan TextParagraph. <p> Meningkatkan kinerja populasi TextParagraph. Semua perhitungan tata letak ditangguhkan sampai metode EndEdit dipanggil. <p> Catatan bahwa pemanggilan metode tidak dapat bersarang. </p> |
| [endEdit](#endEdit--) | Mengakhiri penyuntingan TextParagraph. <p> Meningkatkan kinerja populasi TextParagraph. Semua perhitungan tata letak ditangguhkan sampai metode EndEdit dipanggil. <p> Catatan bahwa pemanggilan metode tidak dapat bersarang. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Mendapatkan atau mengatur nilai indentasi baris berikutnya. Jika diatur ke nilai non-zero, ini memiliki keunggulan dibandingkan nilai FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | Mendapatkan opsi format. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan perataan horizontal untuk teks di dalam Rectangle paragrph's. HorizontalAlignment.None sama dengan HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Mendapatkan simbol hyphen yang digunakan dalam proses hyphenation. Simbol hyphenation adalah "-" secara default. Untuk menghilangkan gambar hyphen (dengan prosedur pembungkusan tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol. |
| [getMargin](#getMargin--) | Mendapatkan padding. |
| [getPosition](#getPosition--) | Mendapatkan posisi paragraf. |
| [getRectangle](#getRectangle--) | Mendapatkan rectangle paragraf. |
| [getRotation](#getRotation--) | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Mendapatkan nilai indentasi baris berikutnya. |
| [getTextRectangle](#getTextRectangle--) | Mendapatkan rectangle teks yang ditempatkan pada paragraf. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Mendapatkan perataan vertikal untuk teks di dalam {@code Rectangle} paragrph's. </p> |
| [isJustify](#isJustify--) | Mendapatkan nilai apakah teks diratakan. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mengatur warna latar belakang untuk paragraf teks. |
| [setBackgroundMode](#setBackgroundMode-int-) | Atur mode latar belakang untuk paragraf teks |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Mendapatkan atau mengatur nilai indentasi baris berikutnya. Jika diatur ke nilai non-zero, ini memiliki keunggulan dibandingkan nilai FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Mengatur opsi format. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan horizontal untuk teks di dalam Rectangle paragrph's. HorizontalAlignment.None sama dengan HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Mengatur simbol hyphen yang digunakan dalam proses hyphenation. Simbol hyphenation adalah "-" secara default. Untuk menghilangkan gambar hyphen (dengan prosedur pembungkusan tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Mengatur nilai apakah teks diratakan. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Mengatur padding. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Mengatur Rotasi paragraf. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Atur mode kompatibilitas kode lama |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Mengatur posisi paragraf. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Mengatur rectangle paragraf. |
| [setRotation](#setRotation-double-) | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Mengatur nilai indentasi baris berikutnya. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur perataan vertikal untuk teks di dalam {@code Rectangle} paragrph's. VerticalAlignment.None sama dengan VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Membuat objek {@code TextParagraph}.

### appendLine {#appendLine-java.lang.String-}
Menambahkan baris teks

### appendLine {#appendLine-java.lang.String-float-}
Menambahkan baris teks.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Menambahkan baris teks dengan parameter keadaan teks.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Menambahkan baris teks dengan parameter keadaan teks

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Menambahkan baris teks dengan parameter keadaan teks.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Menambahkan baris teks dengan parameter keadaan teks.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Menambahkan baris teks dengan parameter keadaan teks

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Memulai penyuntingan TextParagraph. <p> Meningkatkan kinerja populasi TextParagraph. Semua perhitungan tata letak ditangguhkan sampai metode EndEdit dipanggil. <p> Catatan bahwa pemanggilan metode tidak dapat bersarang. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Mengakhiri penyuntingan TextParagraph. <p> Meningkatkan kinerja populasi TextParagraph. Semua perhitungan tata letak ditangguhkan sampai metode EndEdit dipanggil. <p> Catatan bahwa pemanggilan metode tidak dapat bersarang. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Mendapatkan atau mengatur nilai indentasi baris berikutnya. Jika diatur ke nilai non-zero, ini memiliki keunggulan dibandingkan nilai FormattingOptions.SubsequentLinesIndent.

**Returns:**
nilai float

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Mendapatkan opsi format.

**Returns:**
objek TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Mendapatkan perataan horizontal untuk teks di dalam Rectangle paragrph's. HorizontalAlignment.None sama dengan HorizontalAlignment.Left.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Mendapatkan simbol hyphen yang digunakan dalam proses hyphenation. Simbol hyphenation adalah "-" secara default. Untuk menghilangkan gambar hyphen (dengan prosedur pembungkusan tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol.

**Returns:**
nilai String

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Mendapatkan padding.

**Returns:**
nilai MarginInfo

### getPosition {#getPosition--}
```
public Position getPosition()
```

Mendapatkan posisi paragraf.

**Returns:**
Nilai posisi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan rectangle paragraf.

**Returns:**
objek Rectangle

### getRotation {#getRotation--}
```
public double getRotation()
```

Mendapatkan atau mengatur sudut rotasi dalam derajat.

**Returns:**
nilai double

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Mendapatkan nilai indentasi baris berikutnya.

**Returns:**
nilai float

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Mendapatkan rectangle teks yang ditempatkan pada paragraf.

**Returns:**
objek Rectangle

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Mendapatkan perataan vertikal untuk teks di dalam {@code Rectangle} paragrph's. </p>

**Returns:**
nilai VerticalAlignment @see VerticalAlignment <hr> <p> VerticalAlignment.None sama dengan VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Mendapatkan nilai apakah teks diratakan.

**Returns:**
nilai boolean

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mengatur warna latar belakang untuk paragraf teks.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Atur mode latar belakang untuk paragraf teks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Mendapatkan atau mengatur nilai indentasi baris berikutnya. Jika diatur ke nilai non-zero, ini memiliki keunggulan dibandingkan nilai FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Mengatur opsi format.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan horizontal untuk teks di dalam Rectangle paragrph's. HorizontalAlignment.None sama dengan HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Mengatur simbol hyphen yang digunakan dalam proses hyphenation. Simbol hyphenation adalah "-" secara default. Untuk menghilangkan gambar hyphen (dengan prosedur pembungkusan tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Mengatur nilai apakah teks diratakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Mengatur padding.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Mengatur Rotasi paragraf.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Atur mode kompatibilitas kode lama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Mengatur posisi paragraf.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Mengatur rectangle paragraf.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Mendapatkan atau mengatur sudut rotasi dalam derajat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Mengatur nilai indentasi baris berikutnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur perataan vertikal untuk teks di dalam {@code Rectangle} paragrph's. VerticalAlignment.None sama dengan VerticalAlignment.Bottom.
