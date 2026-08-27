---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili cap teks."
type: docs
weight: 5320
url: /id/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Mewakili cap teks.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Menginisialisasi instance baru dari kelas {@code TextStamp} dengan objek formattedText |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Menginisialisasi instance baru dari kelas {@code TextStamp} dengan objek formattedText |
| [TextStamp](#TextStamp-java.lang.String-) | Menginisialisasi instance baru dari kelas {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Menginisialisasi instance baru dari kelas TextStamp. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Jika diaktifkan, ukuran font akan secara otomatis disesuaikan agar cocok dengan persegi panjang stempel berukuran: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) dan {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Lebar dan tinggi default diambil dari persegi panjang halaman. |
| [getDefaultFont](#getDefaultFont--) | Mengembalikan font default |
| [getDefaultFontSize](#getDefaultFontSize--) | Ukuran Font Default |
| [getDraw](#getDraw--) | Properti ini menentukan bagaimana stempel digambar pada halaman. Jika Draw = true, stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks. |
| [getFontSize](#getFontSize--) | Ukuran font aktual setelah stempel ditempatkan. (Mungkin berbeda dari ukuran font awal yang diberikan melalui konstruktor jika opsi 'AutoAdjustFontSizeToFitStampRectangle' diaktifkan.) |
| [getHeight](#getHeight--) | Tinggi yang diinginkan untuk stempel pada halaman. |
| [getMaxRowWidth](#getMaxRowWidth--) | Tinggi baris maksimum untuk opsi WordWrap. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Mendapatkan atau mengatur mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta. |
| [getReplacementFont](#getReplacementFont--) | Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan. |
| [getTextAlignment](#getTextAlignment--) | Perataan teks di dalam stempel. |
| [getTextState](#getTextState--) | Mendapatkan properti teks dari stempel. Lihat {@code TextState} untuk detail. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default ketika Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default ketika Draw = false) nilai YIndent akan diperlakukan sebagai bagian bawah (garis turun) teks. |
| [getValue](#getValue--) | Mendapatkan nilai string yang digunakan sebagai stempel pada halaman. |
| [getWidth](#getWidth--) | Lebar yang diinginkan untuk stempel pada halaman. |
| [getWordWrapMode](#getWordWrapMode--) | Mendapatkan atau mengatur mode word wrap untuk rendering teks. |
| [isJustify](#isJustify--) | Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua sisi kiri dan kanan teks akan diratakan. Nilai default: false. |
| [isScale](#isScale--) | Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan. |
| [isWordWrap](#isWordWrap--) | Mendefinisikan word wrap. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan dipisah menjadi beberapa baris agar sesuai dengan lebar yang ditentukan. Nilai default: false. |
| [put](#put-com.aspose.pdf.Page-) | Menambahkan stempel teks pada halaman. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Jika diaktifkan, ukuran font akan secara otomatis disesuaikan agar cocok dengan persegi panjang stempel berukuran: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) dan {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Lebar dan tinggi default diambil dari persegi panjang halaman. |
| [setDraw](#setDraw-boolean-) | Properti ini menentukan bagaimana stempel digambar pada halaman. Jika Draw = true, stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks. |
| [setHeight](#setHeight-double-) | Tinggi yang diinginkan untuk stempel pada halaman. |
| [setJustify](#setJustify-boolean-) | Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua sisi kiri dan kanan teks akan diratakan. Nilai default: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Tinggi baris maksimum untuk opsi WordWrap. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Mendapatkan atau mengatur mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan. |
| [setScale](#setScale-boolean-) | Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Perataan teks di dalam stempel. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default ketika Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default ketika Draw = false) nilai YIndent akan diperlakukan sebagai bagian bawah (garis turun) teks. |
| [setValue](#setValue-java.lang.String-) | Mengatur nilai string yang digunakan sebagai stempel pada halaman. |
| [setWidth](#setWidth-double-) | Lebar yang diinginkan untuk stempel pada halaman. |
| [setWordWrap](#setWordWrap-boolean-) | Mendefinisikan word wrap. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan dipisah menjadi beberapa baris agar sesuai dengan lebar yang ditentukan. Nilai default: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Mendapatkan atau mengatur mode word wrap untuk rendering teks. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Menginisialisasi instance baru dari kelas {@code TextStamp} dengan objek formattedText

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Menginisialisasi instance baru dari kelas {@code TextStamp} dengan objek formattedText

### TextStamp {#TextStamp-java.lang.String-}
Menginisialisasi instance baru dari kelas {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Menginisialisasi instance baru dari kelas TextStamp.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1;

**Returns:**
nilai float

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Jika diaktifkan, ukuran font akan secara otomatis disesuaikan agar cocok dengan persegi panjang stempel berukuran: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) dan {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Lebar dan tinggi default diambil dari persegi panjang halaman.

**Returns:**
nilai boolean

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Mengembalikan font default

**Returns:**
objek com.aspose.pdf.Font

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Ukuran Font Default

**Returns:**
nilai float

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Properti ini menentukan bagaimana stempel digambar pada halaman. Jika Draw = true, stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks.

**Returns:**
nilai boolean

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Ukuran font aktual setelah stempel ditempatkan. (Mungkin berbeda dari ukuran font awal yang diberikan melalui konstruktor jika opsi 'AutoAdjustFontSizeToFitStampRectangle' diaktifkan.)

**Returns:**
nilai float

### getHeight {#getHeight--}
```
public double getHeight()
```

Tinggi yang diinginkan untuk stempel pada halaman.

**Returns:**
nilai double

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Tinggi baris maksimum untuk opsi WordWrap.

**Returns:**
nilai double

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Mendapatkan atau mengatur mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta.

**Returns:**
elemen NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan.

**Returns:**
Instansi Font

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Perataan teks di dalam stempel.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Mendapatkan properti teks dari stempel. Lihat {@code TextState} untuk detail.

**Returns:**
elemen TextState

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default ketika Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default ketika Draw = false) nilai YIndent akan diperlakukan sebagai bagian bawah (garis turun) teks.

**Returns:**
nilai boolean

### getValue {#getValue--}
```
public String getValue()
```

Mendapatkan nilai string yang digunakan sebagai stempel pada halaman.

**Returns:**
nilai String

### getWidth {#getWidth--}
```
public double getWidth()
```

Lebar yang diinginkan untuk stempel pada halaman.

**Returns:**
nilai double

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Mendapatkan atau mengatur mode word wrap untuk rendering teks.

**Returns:**
elemen WordWrapMode

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua sisi kiri dan kanan teks akan diratakan. Nilai default: false.

**Returns:**
nilai boolean

### isScale {#isScale--}
```
public boolean isScale()
```

Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan.

**Returns:**
nilai boolean

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Mendefinisikan word wrap. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan dipisah menjadi beberapa baris agar sesuai dengan lebar yang ditentukan. Nilai default: false.

**Returns:**
nilai boolean @deprecated "Gunakan WordWrapMode sebagai gantinya."

### put {#put-com.aspose.pdf.Page-}
Menambahkan stempel teks pada halaman.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Secara otomatis menyesuaikan presisi ukuran font. Nilai default: 0.1;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Jika diaktifkan, ukuran font akan secara otomatis disesuaikan agar cocok dengan persegi panjang stempel berukuran: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) dan {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Lebar dan tinggi default diambil dari persegi panjang halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Properti ini menentukan bagaimana stempel digambar pada halaman. Jika Draw = true, stempel digambar sebagai operator grafis dan jika draw = false maka stempel digambar sebagai teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Tinggi yang diinginkan untuk stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Mendefinisikan perataan teks. Jika properti ini diatur ke true, kedua sisi kiri dan kanan teks akan diratakan. Nilai default: false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Tinggi baris maksimum untuk opsi WordWrap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Mendapatkan atau mengatur mode yang menentukan perilaku jika font tidak mengandung karakter yang diminta.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen NoCharacterAction |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Mendapatkan atau mengatur font yang digunakan untuk penggantian jika font pengguna tidak mengandung karakter yang diperlukan.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Mendefinisikan skala teks. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan diskalakan agar sesuai dengan lebar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Perataan teks di dalam stempel.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Mendefinisikan asal koordinat untuk menempatkan teks. Jika TreatYIndentAsBaseLine = true (default ketika Draw = true) nilai YIndent akan diperlakukan sebagai garis dasar teks. Jika TreatYIndentAsBaseLine = false (default ketika Draw = false) nilai YIndent akan diperlakukan sebagai bagian bawah (garis turun) teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setValue {#setValue-java.lang.String-}
Mengatur nilai string yang digunakan sebagai stempel pada halaman.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Lebar yang diinginkan untuk stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Mendefinisikan word wrap. Jika properti ini diatur ke true dan nilai Width ditentukan, teks akan dipisah menjadi beberapa baris agar sesuai dengan lebar yang ditentukan. Nilai default: false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated "Gunakan WordWrapMode sebagai gantinya." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Mendapatkan atau mengatur mode word wrap untuk rendering teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen WordWrapMode @see WordWrapMode |
