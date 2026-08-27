---
title: "TextState"
linktitle: "TextState"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili keadaan teks dari sebuah teks"
type: docs
weight: 5340
url: /id/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Mewakili keadaan teks dari sebuah teks

## Fields

| Field | Deskripsi |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Nilai default tabulasi dalam lebar karakter spasi pada font default. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextState](#TextState--) | Membuat objek status teks. |
| [TextState](#TextState-java.awt.Color-) | Membuat objek status teks. |
| [TextState](#TextState-java.awt.Color-double-) | Membuat objek status teks. |
| [TextState](#TextState-double-) | Membuat objek status teks dengan spesifikasi ukuran font. |
| [TextState](#TextState-java.lang.String-) | Membuat objek status teks. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Membuat objek status teks. |
| [TextState](#TextState-java.lang.String-double-) | Membuat objek status teks. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Menerapkan pengaturan dari textState lain </p> <hr> <p> Hanya properti yang diubah secara eksplisit yang akan disalin. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Menghitung ukuran font untuk persegi panjang. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Mendapatkan warna latar belakang teks. </p> <hr> <p> Catatan bahwa nilai ini tidak dipertahankan sebagai karakteristik teks dalam dokumen. Getter properti BackgroundColor berfungsi untuk sebuah objek jika sebelumnya nilai tersebut secara eksplisit diatur dengan setter BackgroundColor untuk objek tersebut. Properti ini digunakan oleh runtime dalam konteks proses generasi/modifikasi saat ini. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Mendapatkan spasi karakter teks. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| [getFont](#getFont--) | Mendapatkan font teks. |
| [getfontSize](#getfontSize--) | Mewakili metode getfontSize |
| [getFontSize](#getFontSize--) | Mendapatkan ukuran font teks. |
| [getFontStyle](#getFontStyle--) | Mengatur gaya font teks. |
| [getForegroundColor](#getForegroundColor--) | Mendapatkan warna latar depan teks. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Mendapatkan perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Catatan bahwa properti TextState.HorizontalAlignment hanya berfungsi dalam skenario pembuatan dokumen baru. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Mendapatkan skala horizontal teks. |
| [getLineSpacing](#getLineSpacing--) | <p> Mendapatkan spasi baris teks. </p> |
| [getRenderingMode](#getRenderingMode--) | Mendapatkan atau mengatur mode render teks. |
| [getStrokingColor](#getStrokingColor--) | Mendapatkan atau mengatur warna latar depan teks. |
| [getTabTag](#getTabTag--) | <p> Anda dapat menempatkan tag ini dalam teks untuk mendeklarasikan tabulasi. </p> <hr> <p> Ini hanya berpengaruh bila dipasangkan dengan {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Mendapatkan tinggi teks. |
| [getWordSpacing](#getWordSpacing--) | Mendapatkan spasi kata teks. |
| [isInvisible](#isInvisible--) | Mendapatkan ketidakterlihatan teks. Ini pada dasarnya mencerminkan keadaan {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), kecuali untuk beberapa kasus khusus (seperti pemotongan). |
| [isStrikeOut](#isStrikeOut--) | Mendapatkan garis coret untuk teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [isSubscript](#isSubscript--) | Mendapatkan atau mengatur subskrip teks. |
| [isSuperscript](#isSuperscript--) | Mendapatkan superskrip teks. |
| [isUnderline](#isUnderline--) | Mendapatkan garis bawah untuk teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [measureHeight](#measureHeight-char-) | Mengukur tinggi karakter. |
| [measureString](#measureString-java.lang.String-) | Mengukur string. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Mengukur string. </p> <hr> <p> insideLine menunjukkan bahwa string belum berakhir. jika bagian dari keseluruhan string diukur - insideLine harus bernilai true. jika seluruh string diukur insideLine harus bernilai false. dengan kata lain: jika insideLine = true hanya lebar karakter yang dipertimbangkan. tidak ada transformasi tambahan yang dipertimbangkan jika insideLine = false akhir string ditangani dengan benar - transformasi miring dipertimbangkan. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mengatur warna latar belakang teks. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Mengatur spasi karakter teks. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Mendapatkan font teks. |
| [setFontSize](#setFontSize-float-) | Mengatur ukuran font teks. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Mengatur ukuran font teks dengan pembaruan teredam. |
| [setFontStyle](#setFontStyle-int-) | Mengatur gaya font teks. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Mendapatkan font teks dengan pembaruan teredam. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Mengatur warna latar depan teks. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Mengatur perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Perhatikan bahwa properti TextState.HorizontalAlignment berfungsi hanya dalam skenario pembuatan dokumen baru. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Mengatur skala horizontal teks. |
| [setInvisible](#setInvisible-boolean-) | Mengatur ketidakterlihatan teks. Ini pada dasarnya mencerminkan keadaan {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), kecuali untuk beberapa kasus khusus (seperti pemotongan). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Mengatur jarak baris teks. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Mendapatkan atau mengatur mode render teks. |
| [setStrikeOut](#setStrikeOut-boolean-) | Mengatur garis coret pada teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar depan teks. |
| [setSubscript](#setSubscript-boolean-) | Mendapatkan atau mengatur subskrip teks. |
| [setSuperscript](#setSuperscript-boolean-) | Mengatur superskrip teks. |
| [setUnderline](#setUnderline-boolean-) | Mengatur garis bawah pada teks, yang direpresentasikan oleh objek {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | Mengatur spasi kata pada teks. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Nilai default tabulasi dalam lebar karakter spasi pada font default.

### TextState {#TextState--}
```
public TextState()
```

Membuat objek status teks.

### TextState {#TextState-java.awt.Color-}
Membuat objek status teks.

### TextState {#TextState-java.awt.Color-double-}
Membuat objek status teks.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Membuat objek status teks dengan spesifikasi ukuran font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSize |  | Ukuran font. |

### TextState {#TextState-java.lang.String-}
Membuat objek status teks.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Membuat objek status teks.

### TextState {#TextState-java.lang.String-double-}
Membuat objek status teks.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Menerapkan pengaturan dari textState lain </p> <hr> <p> Hanya properti yang diubah secara eksplisit yang akan disalin. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Menghitung ukuran font untuk persegi panjang.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Mendapatkan warna latar belakang teks. </p> <hr> <p> Catatan bahwa nilai ini tidak dipertahankan sebagai karakteristik teks dalam dokumen. Getter properti BackgroundColor berfungsi untuk sebuah objek jika sebelumnya nilai tersebut secara eksplisit diatur dengan setter BackgroundColor untuk objek tersebut. Properti ini digunakan oleh runtime dalam konteks proses generasi/modifikasi saat ini. </p>

**Returns:**
Nilai warna

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Mendapatkan spasi karakter teks.

**Returns:**
nilai float

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik.

**Returns:**
elemen CoordinateOrigin

### getFont {#getFont--}
```
public Font getFont()
```

Mendapatkan font teks.

**Returns:**
objek Font

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Mewakili metode getfontSize

**Returns:**
nilai float

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Mendapatkan ukuran font teks.

**Returns:**
nilai float

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Mengatur gaya font teks.

**Returns:**
elemen FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Mendapatkan warna latar depan teks.

**Returns:**
Nilai warna

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Mendapatkan perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Catatan bahwa properti TextState.HorizontalAlignment hanya berfungsi dalam skenario pembuatan dokumen baru. </p>

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Mendapatkan skala horizontal teks.

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

Mendapatkan atau mengatur mode render teks.

**Returns:**
elemen TextRenderingMode @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Mendapatkan atau mengatur warna latar depan teks.

**Returns:**
Instansi Color

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Anda dapat menempatkan tag ini dalam teks untuk mendeklarasikan tabulasi. </p> <hr> <p> Ini hanya berpengaruh bila dipasangkan dengan {@code TabStops}. </p>

**Returns:**
nilai String "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Mendapatkan tinggi teks.

**Returns:**
nilai float

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Mendapatkan spasi kata teks.

**Returns:**
nilai float

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Mendapatkan ketidakterlihatan teks. Ini pada dasarnya mencerminkan keadaan {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), kecuali untuk beberapa kasus khusus (seperti pemotongan).

**Returns:**
nilai boolean

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Mendapatkan garis coret untuk teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
nilai boolean

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Mendapatkan atau mengatur subskrip teks.

**Returns:**
nilai boolean

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Mendapatkan superskrip teks.

**Returns:**
nilai boolean

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Mendapatkan garis bawah untuk teks, yang direpresentasikan oleh objek {@code TextFragment}

**Returns:**
nilai boolean

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
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

### measureString {#measureString-java.lang.String-boolean-}
<p> Mengukur string. </p> <hr> <p> insideLine menunjukkan bahwa string belum berakhir. jika bagian dari keseluruhan string diukur - insideLine harus bernilai true. jika seluruh string diukur insideLine harus bernilai false. dengan kata lain: jika insideLine = true hanya lebar karakter yang dipertimbangkan. tidak ada transformasi tambahan yang dipertimbangkan jika insideLine = false akhir string ditangani dengan benar - transformasi miring dipertimbangkan. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mengatur warna latar belakang teks.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Mengatur spasi karakter teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Mendapatkan atau mengatur CoordinateOrigin teks. Jika CoordinateOrigin adalah Descender, koordinat Y teks sesuai dengan titik terendah font. Jika CoordinateOrigin adalah BaseLine, koordinat Y teks sesuai dengan garis dasar font. Nilai defaultnya adalah Descender. Jika nilai Descent font terlalu besar, teks dapat dirender lebih tinggi dibandingkan font lain. Dalam kasus ini, CoordinateOrigin BaseLine dapat dipilih untuk rendering teks yang lebih baik.

### setFont {#setFont-com.aspose.pdf.Font-}
Mendapatkan font teks.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Mengatur ukuran font teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Mengatur ukuran font teks dengan pembaruan teredam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Mengatur gaya font teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai FontStyles @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Mendapatkan font teks dengan pembaruan teredam.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Mengatur warna latar depan teks.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Mengatur perataan horizontal untuk teks. </p> <hr> <p> HorizontalAlignment.None sama dengan HorizontalAlignment.Left. Perhatikan bahwa properti TextState.HorizontalAlignment berfungsi hanya dalam skenario pembuatan dokumen baru. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Mengatur skala horizontal teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Mengatur ketidakterlihatan teks. Ini pada dasarnya mencerminkan keadaan {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)}), kecuali untuk beberapa kasus khusus (seperti pemotongan).

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
Mendapatkan atau mengatur mode render teks.

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
Mendapatkan atau mengatur warna latar depan teks.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Mendapatkan atau mengatur subskrip teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Mengatur superskrip teks.

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
