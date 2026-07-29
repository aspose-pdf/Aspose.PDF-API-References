---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili keadaan teks dari sebuah fragmen teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek {@code TextState}. // Open."
type: docs
weight: 5150
url: /id/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Mewakili keadaan teks dari sebuah fragmen teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Menyediakan cara untuk mengubah properti teks berikut: font ({@code TextFragmentState.Font} property) ukuran font ({@code TextFragmentState.FontSize} property) gaya font ({@code TextFragmentState.FontStyle} property) warna latar depan ({@code TextFragmentState.ForegroundColor} property) warna latar belakang ({@code TextFragmentState.BackgroundColor} property) </p> <p> Catatan bahwa mengubah properti {@code TextFragmentState} dapat mengubah koleksi {@code TextFragment.Segments} internal karena TextFragment adalah objek agregat dan dapat menyusun ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah membiarkan koleksi {@code TextFragment.Segments} tidak berubah, silakan ubah segmen internal secara individual. </p> @see TextFragmentAbsorber @see IDocument

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Menginisialisasi instance baru dari objek {@code TextFragmentState} dengan objek {@code TextFragment} yang ditentukan. Inisialisasi {@code TextFragmentState} ini tidak didukung. TextFragmentState hanya tersedia dengan properti {@code TextFragment.TextState}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Menerapkan pengaturan dari textState lain </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Menerapkan pengaturan dari textState lain |
| [getBackgroundColor](#getBackgroundColor--) | Mengatur warna latar belakang teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [getCharacterSpacing](#getCharacterSpacing--) | Mendapatkan jarak karakter teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Mendapatkan flag apakah batas persegi panjang teks digambar. |
| [getFont](#getFont--) | Mendapatkan font teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [getFontSize](#getFontSize--) | Mendapatkan ukuran font teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [getFontStyle](#getFontStyle--) | Mengatur gaya font teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [getForegroundColor](#getForegroundColor--) | Mendapatkan warna latar depan teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [getFormattingOptions](#getFormattingOptions--) | Mendapatkan atau mengatur opsi pemformatan. Pengaturan opsi hanya berlaku dalam skenario generator. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Mendapatkan perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Perhatikan bahwa properti TextFragmentState.VerticalAlignment hanya berfungsi dalam skenario pembuatan dokumen baru. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Mendapatkan skala horizontal teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [getLineSpacing](#getLineSpacing--) | <p> Mendapatkan spasi baris teks. </p> |
| [getRenderingMode](#getRenderingMode--) | Mendapatkan atau mengatur mode rendering teks. |
| [getRotation](#getRotation--) | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| [getStrokingColor](#getStrokingColor--) | Mendapatkan atau mengatur operasi pewarnaan garis pada rendering {@code TextFragment} (teks bergaris, batas persegi panjang) |
| [getTabStops](#getTabStops--) | <p> Mendapatkan tabstop untuk teks. </p> <hr> <p> Perhatikan bahwa properti Tabstops hanya berfungsi dalam skenario pembuatan dokumen baru. Tabstops dapat ditambahkan selama inisialisasi {@code TextFragment}. Tabstops harus dibangun sebelum teks. </p> |
| [getTextHeight](#getTextHeight--) | Mendapatkan tinggi teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [getWordSpacing](#getWordSpacing--) | Mendapatkan spasi kata teks. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Memeriksa apakah string input dapat ditempatkan di dalam persegi panjang yang didefinisikan. |
| [isInvisible](#isInvisible--) | Mendapatkan ketidakterlihatan teks. |
| [isStrikeOut](#isStrikeOut--) | Mendapatkan atau mengatur garis coret pada teks, yang direpresentasikan oleh objek {@link TextFragment} |
| [isSubscript](#isSubscript--) | Mendapatkan atau mengatur subskrip teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [isSuperscript](#isSuperscript--) | Mendapatkan atau mengatur superskrip teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [isUnderline](#isUnderline--) | Mendapatkan atau mengatur garis bawah pada teks, yang direpresentasikan oleh objek {@link TextFragment} |
| [measureHeight](#measureHeight-char-) | Mengukur tinggi karakter. |
| [measureString](#measureString-java.lang.String-) | Mengukur string. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mengatur warna latar belakang teks, yang direpresentasikan oleh objek TextFragment |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Mengatur jarak karakter teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Mengatur flag apakah batas persegi panjang teks digambar. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Mengatur font teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setFontSize](#setFontSize-float-) | Mengatur ukuran font teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setFontStyle](#setFontStyle-int-) | Mengatur gaya font teks, yang direpresentasikan oleh objek {@link TextFragment} |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Mengatur warna latar depan teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Mendapatkan atau mengatur opsi pemformatan. Pengaturan opsi hanya berlaku dalam skenario generator. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Mengatur perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Perhatikan bahwa properti TextFragmentState.VerticalAlignment hanya berfungsi dalam skenario pembuatan dokumen baru. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Mengatur skala horizontal teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [setInvisible](#setInvisible-boolean-) | Mengatur ketidakterlihatan teks. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Mengatur jarak baris teks. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Mendapatkan atau mengatur mode rendering teks. |
| [setRotation](#setRotation-double-) | Mendapatkan atau mengatur sudut rotasi dalam derajat. |
| [setStrikeOut](#setStrikeOut-boolean-) | Mengatur garis coret pada teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur operasi pewarnaan garis pada rendering {@code TextFragment} (teks bergaris, batas persegi panjang) |
| [setSubscript](#setSubscript-boolean-) | Mendapatkan atau mengatur subskrip teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [setSuperscript](#setSuperscript-boolean-) | Mendapatkan atau mengatur superskrip teks, yang direpresentasikan oleh objek {@code TextFragment}. |
| [setUnderline](#setUnderline-boolean-) | Mengatur garis bawah pada teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Mengatur spasi kata pada teks. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Menginisialisasi instance baru dari objek {@code TextFragmentState} dengan objek {@code TextFragment} yang ditentukan. Inisialisasi {@code TextFragmentState} ini tidak didukung. TextFragmentState hanya tersedia dengan properti {@code TextFragment.TextState}.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Menerapkan pengaturan dari textState lain </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Menerapkan pengaturan dari textState lain

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Mengatur warna latar belakang teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
nilai objek Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Mendapatkan jarak karakter teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Returns:**
nilai float

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik.

**Returns:**
elemen CoordinateOrigin

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Mendapatkan flag apakah batas persegi panjang teks digambar.

**Returns:**
nilai boolean

### getFont {#getFont--}
```
public Font getFont()
```

Mendapatkan font teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
Nilai font

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Mendapatkan ukuran font teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
nilai float

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Mengatur gaya font teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
elemen FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Mendapatkan warna latar depan teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
objek Color

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Mendapatkan atau mengatur opsi pemformatan. Pengaturan opsi hanya berlaku dalam skenario generator.

**Returns:**
instansi TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Mendapatkan perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Perhatikan bahwa properti TextFragmentState.VerticalAlignment hanya berfungsi dalam skenario pembuatan dokumen baru. </p>

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Mendapatkan skala horizontal teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Returns:**
nilai float

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Mendapatkan spasi baris teks. </p>

**Returns:**
nilai float <hr> <p> Perhatikan bahwa nilai tidak dipertahankan sebagai karakteristik teks dalam dokumen. Getter properti LineSpacing berfungsi untuk sebuah objek jika nilai tersebut secara eksplisit telah diatur sebelumnya dengan setter LineSpacing untuk objek tersebut. Properti ini digunakan oleh runtime dalam konteks proses pembuatan/perubahan saat ini. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Mendapatkan atau mengatur mode rendering teks.

**Returns:**
elemen TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

Mendapatkan atau mengatur sudut rotasi dalam derajat.

**Returns:**
nilai double

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Mendapatkan atau mengatur operasi pewarnaan garis pada rendering {@code TextFragment} (teks bergaris, batas persegi panjang)

**Returns:**
Instansi Color

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Mendapatkan tabstop untuk teks. </p> <hr> <p> Perhatikan bahwa properti Tabstops hanya berfungsi dalam skenario pembuatan dokumen baru. Tabstops dapat ditambahkan selama inisialisasi {@code TextFragment}. Tabstops harus dibangun sebelum teks. </p>

**Returns:**
objek TabStops

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Mendapatkan tinggi teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
nilai float

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Mendapatkan spasi kata teks.

**Returns:**
nilai float

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Memeriksa apakah string input dapat ditempatkan di dalam persegi panjang yang didefinisikan.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Mendapatkan ketidakterlihatan teks.

**Returns:**
nilai boolean

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Mendapatkan atau mengatur garis coret pada teks, yang direpresentasikan oleh objek {@link TextFragment}

**Returns:**
nilai boolean

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Mendapatkan atau mengatur subskrip teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Returns:**
nilai boolean

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Mendapatkan atau mengatur superskrip teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Returns:**
nilai boolean

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Mendapatkan atau mengatur garis bawah pada teks, yang direpresentasikan oleh objek {@link TextFragment}

**Returns:**
nilai boolean

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
```

Mengukur tinggi karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| karakter |  | Karakter untuk diukur. |

**Returns:**
Tinggi karakter jika dapat diambil dari font; jika tidak, 0.

### measureString {#measureString-java.lang.String-}
Mengukur string.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mengatur warna latar belakang teks, yang direpresentasikan oleh objek TextFragment

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Mengatur jarak karakter teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Mengatur flag apakah batas persegi panjang teks digambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFont {#setFont-com.aspose.pdf.Font-}
Mengatur font teks, yang direpresentasikan oleh objek {@code TextFragment}

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Mengatur ukuran font teks, yang direpresentasikan oleh objek {@code TextFragment}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Mengatur gaya font teks, yang direpresentasikan oleh objek {@link TextFragment}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Mengatur warna latar depan teks, yang direpresentasikan oleh objek {@code TextFragment}

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Mendapatkan atau mengatur opsi pemformatan. Pengaturan opsi hanya berlaku dalam skenario generator.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Mengatur perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Perhatikan bahwa properti TextFragmentState.VerticalAlignment hanya berfungsi dalam skenario pembuatan dokumen baru. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Mengatur skala horizontal teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Mengatur ketidakterlihatan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Mengatur jarak baris teks. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float <hr> <p> Perhatikan bahwa nilai tidak dipertahankan sebagai karakteristik teks dalam dokumen. Getter properti LineSpacing berfungsi untuk sebuah objek jika nilai tersebut secara eksplisit telah diatur sebelumnya dengan setter LineSpacing untuk objek tersebut. Properti ini digunakan oleh runtime dalam konteks proses pembuatan/perubahan saat ini. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Mendapatkan atau mengatur mode rendering teks.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Mendapatkan atau mengatur sudut rotasi dalam derajat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Mengatur garis coret pada teks, yang direpresentasikan oleh objek {@code TextFragment}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur operasi pewarnaan garis pada rendering {@code TextFragment} (teks bergaris, batas persegi panjang)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Mendapatkan atau mengatur subskrip teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Mendapatkan atau mengatur superskrip teks, yang direpresentasikan oleh objek {@code TextFragment}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Mengatur garis bawah pada teks, yang direpresentasikan oleh objek {@code TextFragment}

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Mengatur spasi kata pada teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |
