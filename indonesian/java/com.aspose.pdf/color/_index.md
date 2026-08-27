---
title: "Warna"
linktitle: "Warna"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk nilai warna yang dapat diekspresikan dalam ruang warna yang berbeda."
type: docs
weight: 670
url: /id/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Mewakili kelas untuk nilai warna yang dapat diekspresikan dalam ruang warna yang berbeda.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Default](#Default) | Mewakili warna Default. |
| [Empty](#Empty) | Mewakili warna kosong. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Color](#Color--) | Konstruktor default. |
| [Color](#Color-double:A-) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Mengkloning instance ini |
| [equals](#equals-java.lang.Object-) | Mengembalikan true jika dua Warna sama. |
| [fromArgb](#fromArgb-int-int-int-) | Mendapatkan objek Color pdf yang valid dari komponen warna RGB. |
| [fromArgb](#fromArgb-int-int-int-int-) | Mendapatkan objek Color pdf yang valid dari komponen warna RGB. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Mendapatkan objek Color pdf yang valid dari komponen warna CMYK. |
| [fromGray](#fromGray-double-) | Mendapatkan objek Color pdf yang valid dari komponen warna Gray. |
| [fromRgb](#fromRgb-java.awt.Color-) | Mendapatkan objek Color pdf yang valid dari nilai java.awt.Color. |
| [fromRgb](#fromRgb-double-double-double-) | Mendapatkan objek Color pdf yang valid dari komponen warna RGB. |
| [getA](#getA--) | Mendapatkan nilai komponen alfa |
| [getAliceBlue](#getAliceBlue--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFAEBD7. |
| [getAqua](#getAqua--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF7FFFD4. |
| [getAzure](#getAzure--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFF0FFFF. |
| [getBeige](#getBeige--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFF5F5DC. |
| [getBisque](#getBisque--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFFE4C4. |
| [getBlack](#getBlack--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFFEBCD. |
| [getBlue](#getBlue--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF8A2BE2. |
| [getBrown](#getBrown--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF7FFF00. |
| [getChocolate](#getChocolate--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFD2691E. |
| [getColorSpace](#getColorSpace--) | Mendapatkan ruang warna yang diwakili oleh warna tersebut. |
| [getCoral](#getCoral--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF6495ED. |
| [getCornsilk](#getCornsilk--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFFF8DC. |
| [getCrimson](#getCrimson--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFDC143C. |
| [getCyan](#getCyan--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFB8860B. |
| [getDarkGray](#getDarkGray--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF9932CC. |
| [getDarkRed](#getDarkRed--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF9400D3. |
| [getData](#getData--) | Nilai warna. |
| [getDeepPink](#getDeepPink--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF00BFFF. |
| [getDimGray](#getDimGray--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF228B22. |
| [getFuchsia](#getFuchsia--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFF8F8FF. |
| [getGold](#getGold--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDAA520. |
| [getGray](#getGray--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF808080. |
| [getGreen](#getGreen--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF008000. |
| [getGreenYellow](#getGreenYellow--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF0FFF0. |
| [getHotPink](#getHotPink--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFCD5C5C. |
| [getIndigo](#getIndigo--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF4B0082. |
| [getIvory](#getIvory--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFFF0. |
| [getKhaki](#getKhaki--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF0E68C. |
| [getLavender](#getLavender--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF08080. |
| [getLightCyan](#getLightCyan--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFAFAD2. |
| [getLightGray](#getLightGray--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF90EE90. |
| [getLightPink](#getLightPink--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFFE0. |
| [getLime](#getLime--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF32CD32. |
| [getLinen](#getLinen--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFAF0E6. |
| [getMagenta](#getMagenta--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF00FF. |
| [getMaroon](#getMaroon--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF191970. |
| [getMintCream](#getMintCream--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFDEAD. |
| [getNavy](#getNavy--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF000080. |
| [getOldLace](#getOldLace--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFDF5E6. |
| [getOlive](#getOlive--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF808000. |
| [getOliveDrab](#getOliveDrab--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF6B8E23. |
| [getOrange](#getOrange--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFF4500. |
| [getOrchid](#getOrchid--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | Mendapatkan objek yang menunjukkan ruang warna pola. Hanya untuk penggunaan internal. |
| [getPeachPuff](#getPeachPuff--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFDAB9. |
| [getPeru](#getPeru--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFCD853F. |
| [getPink](#getPink--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFC0CB. |
| [getPlum](#getPlum--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFB0E0E6. |
| [getPurple](#getPurple--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF800080. |
| [getRed](#getRed--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF8B4513. |
| [getSalmon](#getSalmon--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFF5EE. |
| [getSienna](#getSienna--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFA0522D. |
| [getSilver](#getSilver--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF708090. |
| [getSnow](#getSnow--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF4682B4. |
| [getTan](#getTan--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFD2B48C. |
| [getTeal](#getTeal--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF008080. |
| [getThistle](#getThistle--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFD8BFD8. |
| [getTomato](#getTomato--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFF6347. |
| [getTransparent](#getTransparent--) | Mendapatkan warna yang ditentukan sistem. |
| [getTurquoise](#getTurquoise--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF40E0D0. |
| [getViolet](#getViolet--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFEE82EE. |
| [getWheat](#getWheat--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF5DEB3. |
| [getWhite](#getWhite--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF5F5F5. |
| [getYellow](#getYellow--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF9ACD32. |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek tersebut harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek tersebut harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Mengembalikan true jika dua Warna sama. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Mengembalikan true jika dua Color tidak sama. |
| [parse](#parse-java.lang.String-) | Mengekstrak komponen warna dari string. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Mengatur objek yang menunjukkan ruang warna pola. Hanya untuk penggunaan internal |
| [toRgb](#toRgb--) | Mengonversi warna menjadi rgb. |
| [toString](#toString--) | Mengonversi menjadi string. |

### Default {#Default}
```
public static final Color Default
```

Mewakili warna Default.

### Empty {#Empty}
```
public static final Color Empty
```

Mewakili warna kosong.

### Color {#Color--}
```
public Color()
```

Konstruktor default.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Konstruktor

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vektor |  | array double[] |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Mengkloning instance ini

**Returns:**
objek Color

### equals {#equals-java.lang.Object-}
Mengembalikan true jika dua Warna sama.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Mendapatkan objek Color pdf yang valid dari komponen warna RGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r |  | Komponen warna Merah (nilai 0 - 255). |
| g |  | Komponen warna Hijau (nilai 0 - 255). |
| b |  | Komponen warna Biru (nilai 0 - 255). |

**Returns:**
Objek Warna dengan setiap nilai komponen dalam rentang [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Mendapatkan objek Color pdf yang valid dari komponen warna RGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a |  | Nilai komponen alfa (nilai 0 - 255). |
| r |  | Komponen warna Merah (nilai 0 - 255). |
| g |  | Komponen warna Hijau (nilai 0 - 255). |
| b |  | Komponen warna Biru (nilai 0 - 255). |

**Returns:**
Objek Warna dengan setiap nilai komponen dalam rentang [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Mendapatkan objek Color pdf yang valid dari komponen warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c |  | Komponen warna Cyan (nilai 0 - 1). |
| m |  | Komponen warna Magenta (nilai 0 - 1). |
| y |  | Komponen warna Kuning (nilai 0 - 1). |
| k |  | Komponen warna Key (nilai 0 - 1). |

**Returns:**
Objek Warna dengan setiap nilai komponen dalam rentang [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Mendapatkan objek Color pdf yang valid dari komponen warna Gray.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g |  | Komponen warna Abu-abu (nilai 0 - 1). |

**Returns:**
Objek Warna dengan setiap nilai komponen dalam rentang [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Mendapatkan objek Color pdf yang valid dari nilai java.awt.Color.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Mendapatkan objek Color pdf yang valid dari komponen warna RGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| r |  | Komponen warna Merah (nilai 0 - 1). |
| g |  | Komponen warna Hijau (nilai 0 - 1). |
| b |  | Komponen warna Biru (nilai 0 - 1). |

**Returns:**
Objek Warna dengan setiap nilai komponen dalam rentang [0..1].

### getA {#getA--}
```
public double getA()
```

Mendapatkan nilai komponen alfa

**Returns:**
nilai double

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFF0F8FF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFAEBD7.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF00FFFF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF7FFFD4.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFF0FFFF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFF5F5DC.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFFE4C4.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF000000.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFFEBCD.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF0000FF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF8A2BE2.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFA52A2A.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFDEB887.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF5F9EA0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF7FFF00.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFD2691E.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Mendapatkan ruang warna yang diwakili oleh warna tersebut.

**Returns:**
Objek ColorSpace

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFF7F50.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF6495ED.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFFFF8DC.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFDC143C.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF00FFFF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF00008B.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF008B8B.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFB8860B.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFA9A9A9.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF006400.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FFBDB76B.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF8B008B.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Mendapatkan warna yang didefinisikan sistem dengan nilai ARGB #FF556B2F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF8C00.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF9932CC.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF8B0000.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFE9967A.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF8FBC8F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF483D8B.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF2F4F4F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF00CED1.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF9400D3.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getData {#getData--}
```
public double[] getData()
```

Nilai warna.

**Returns:**
array nilai double

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF1493.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF00BFFF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF696969.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF1E90FF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFB22222.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFFAF0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF228B22.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF00FF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDCDCDC.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFF8F8FF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getGold {#getGold--}
```
public static Color getGold()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFD700.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDAA520.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getGray {#getGray--}
```
public static Color getGray()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF808080.

**Returns:**
Sebuah struktur yang mewakili warna yang didefinisikan sistem.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF008000.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFADFF2F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF0FFF0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFF69B4.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFCD5C5C.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF4B0082.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFFF0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF0E68C.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFE6E6FA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFF0F5.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF7CFC00.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFACD.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFADD8E6.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF08080.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFE0FFFF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFAFAD2.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFD3D3D3.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF90EE90.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFB6C1.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFA07A.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF20B2AA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF87CEFA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF778899.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFB0C4DE.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFFE0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLime {#getLime--}
```
public static Color getLime()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF00FF00.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF32CD32.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFAF0E6.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF00FF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF800000.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF66CDAA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF0000CD.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFBA55D3.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF9370DB.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF3CB371.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF7B68EE.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF00FA9A.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF48D1CC.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFC71585.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF191970.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFF5FFFA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFE4E1.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFE4B5.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFDEAD.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF000080.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFDF5E6.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF808000.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF6B8E23.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFFA500.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFFF4500.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFDA70D6.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FFEEE8AA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Mendapatkan warna yang didefinisikan oleh sistem dengan nilai ARGB #FF98FB98.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFAFEEEE.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDB7093.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFEFD5.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Mendapatkan objek yang menunjukkan ruang warna pola. Hanya untuk penggunaan internal.

**Returns:**
Objek PatternColorSpace

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFDAB9.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFCD853F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPink {#getPink--}
```
public static Color getPink()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFC0CB.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFDDA0DD.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFB0E0E6.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF800080.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getRed {#getRed--}
```
public static Color getRed()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFF0000.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFBC8F8F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF4169E1.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF8B4513.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFA8072.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFF4A460.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF2E8B57.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFF5EE.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFA0522D.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFC0C0C0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF87CEEB.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF6A5ACD.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF708090.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FFFFFAFA.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Mendapatkan warna yang didefinisikan sistem yang memiliki nilai ARGB #FF00FF7F.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF4682B4.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getTan {#getTan--}
```
public static Color getTan()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFD2B48C.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF008080.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFD8BFD8.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFF6347.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Mendapatkan warna yang ditentukan sistem.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF40E0D0.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFEE82EE.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF5DEB3.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFFFF.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFF5F5F5.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FFFFFF00.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Mendapatkan warna yang ditentukan sistem yang memiliki nilai ARGB #FF9ACD32.

**Returns:**
Sebuah yang mewakili warna yang didefinisikan sistem.

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek tersebut harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing dua objek tersebut harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Mengembalikan true jika dua Warna sama.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Mengembalikan true jika dua Color tidak sama.

### parse {#parse-java.lang.String-}
Mengekstrak komponen warna dari string.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Mengatur objek yang menunjukkan ruang warna pola. Hanya untuk penggunaan internal

### toRgb {#toRgb--}
```
public Color toRgb()
```

Mengonversi warna menjadi rgb.

**Returns:**
Nilai warna Rgb.

### toString {#toString--}
```
public String toString()
```

Mengonversi menjadi string.

**Returns:**
Representasi string dari objek Color.
