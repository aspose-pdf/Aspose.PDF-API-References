---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas opsi untuk mengekstrak grafik vektor dari halaman dokumen PDF."
type: docs
weight: 30
url: /id/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Mewakili kelas opsi untuk mengekstrak grafik vektor dari halaman dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Membuat instansi kelas SvgExtractionOptions. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Mendapatkan dan mengatur opsi untuk secara otomatis mengelompokkan subpath menjadi gambar. Opsi ini mengecualikan opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Mendapatkan dan mengatur opsi untuk mengekstrak setiap subpath dari dokumen PDF menjadi gambar SVG terpisah. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Mendapatkan dan mengatur persegi panjang pembatas yang menentukan area ekstraksi untuk ekstraksi SVG. |
| [getGroupStrength](#getGroupStrength--) | Mendapatkan dan mengatur opsi Kekuatan pengelompokan subpath menjadi gambar. Memungkinkan Anda mengkonfigurasi tingkat pengelompokan subpath. Nilai berkisar dari 0 hingga 1. Nilai 0 berarti opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) diaktifkan. Nilai 1 akan membuat satu gambar untuk semua jalur vektor pada halaman. Opsi ini berpengaruh ketika {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) bernilai false. Nilai default adalah {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Mendapatkan atau mengatur lebar goresan minimum yang akan digunakan dalam SVG yang dihasilkan. Jika PDF menggunakan lebar goresan yang lebih tipis, lebar tersebut akan diganti dengan lebar ini. Nilai default adalah 0,5. Nilai ini dinyatakan dalam satuan ruang pengguna yang telah ditransformasi dari halaman PDF yang dikonversi. Secara default 1 satuan ruang pengguna adalah 1/72 inci (0,35 mm), tetapi dapat ditimpa oleh dokumen PDF. Transformasi dapat memengaruhi lebar minimum sebenarnya dalam SVG yang dihasilkan. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Mendapatkan dan mengatur opsi untuk secara ketat memeriksa apakah subpath berada dalam persegi panjang yang ditentukan di {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Jika diatur ke false, maka subpath yang tidak sepenuhnya termasuk dalam {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) akan diekstrak. Nilai default adalah {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Mendapatkan dan mengatur flag yang menentukan apakah XFrom yang ditemukan pada halaman harus dibongkar atau tidak. Elemen XFrom dapat berakhir di file SVG yang berbeda. Hanya XForms yang dirender oleh pernyataan Do dari konten halaman yang dibongkar. XForms bersarang tidak dibongkar. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Mendapatkan dan mengatur opsi untuk membongkar hanya XForm yang sesuai dengan predikat yang ditentukan. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Mendapatkan dan mengatur opsi untuk secara otomatis mengelompokkan subpath menjadi gambar. Opsi ini mengecualikan opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}). |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Mendapatkan dan mengatur opsi untuk mengekstrak setiap subpath dari dokumen PDF menjadi gambar SVG terpisah. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Mendapatkan dan mengatur persegi panjang pembatas yang menentukan area ekstraksi untuk ekstraksi SVG. |
| [setGroupStrength](#setGroupStrength-double-) | Mendapatkan dan mengatur opsi Kekuatan pengelompokan subpath menjadi gambar. Memungkinkan Anda mengkonfigurasi tingkat pengelompokan subpath. Nilai berkisar dari 0 hingga 1. Nilai 0 berarti opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) diaktifkan. Nilai 1 akan membuat satu gambar untuk semua jalur vektor pada halaman. Opsi ini berpengaruh ketika {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) bernilai false. Nilai default adalah {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Mendapatkan atau mengatur lebar goresan minimum yang akan digunakan dalam SVG yang dihasilkan. Jika PDF menggunakan lebar goresan yang lebih tipis, lebar tersebut akan diganti dengan lebar ini. Nilai default adalah 0,5. Nilai ini dinyatakan dalam satuan ruang pengguna yang telah ditransformasi dari halaman PDF yang dikonversi. Secara default 1 satuan ruang pengguna adalah 1/72 inci (0,35 mm), tetapi dapat ditimpa oleh dokumen PDF. Transformasi dapat memengaruhi lebar minimum sebenarnya dalam SVG yang dihasilkan. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Mendapatkan dan mengatur opsi untuk secara ketat memeriksa apakah subpath berada dalam persegi panjang yang ditentukan di {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Jika diatur ke false, maka subpath yang tidak sepenuhnya termasuk dalam {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) akan diekstrak. Nilai default adalah {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Mendapatkan dan mengatur flag yang menentukan apakah XFrom yang ditemukan pada halaman harus dibongkar atau tidak. Elemen XFrom dapat berakhir di file SVG yang berbeda. Hanya XForms yang dirender oleh pernyataan Do dari konten halaman yang dibongkar. XForms bersarang tidak dibongkar. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Mendapatkan dan mengatur opsi untuk membongkar hanya XForm yang sesuai dengan predikat yang ditentukan. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Membuat instansi kelas SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Mendapatkan dan mengatur opsi untuk secara otomatis mengelompokkan subpath menjadi gambar. Opsi ini mengecualikan opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Returns:**
nilai boolean

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Mendapatkan dan mengatur opsi untuk mengekstrak setiap subpath dari dokumen PDF menjadi gambar SVG terpisah.

**Returns:**
nilai boolean

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Mendapatkan dan mengatur persegi panjang pembatas yang menentukan area ekstraksi untuk ekstraksi SVG.

**Returns:**
Instansi Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Mendapatkan dan mengatur opsi Kekuatan pengelompokan subpath menjadi gambar. Memungkinkan Anda mengkonfigurasi tingkat pengelompokan subpath. Nilai berkisar dari 0 hingga 1. Nilai 0 berarti opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) diaktifkan. Nilai 1 akan membuat satu gambar untuk semua jalur vektor pada halaman. Opsi ini berpengaruh ketika {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) bernilai false. Nilai default adalah {@code 0.8}.

**Returns:**
nilai double

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Mendapatkan atau mengatur lebar goresan minimum yang akan digunakan dalam SVG yang dihasilkan. Jika PDF menggunakan lebar goresan yang lebih tipis, lebar tersebut akan diganti dengan lebar ini. Nilai default adalah 0,5. Nilai ini dinyatakan dalam satuan ruang pengguna yang telah ditransformasi dari halaman PDF yang dikonversi. Secara default 1 satuan ruang pengguna adalah 1/72 inci (0,35 mm), tetapi dapat ditimpa oleh dokumen PDF. Transformasi dapat memengaruhi lebar minimum sebenarnya dalam SVG yang dihasilkan.

**Returns:**
nilai double

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Mendapatkan dan mengatur opsi untuk secara ketat memeriksa apakah subpath berada dalam persegi panjang yang ditentukan di {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Jika diatur ke false, maka subpath yang tidak sepenuhnya termasuk dalam {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) akan diekstrak. Nilai default adalah {@code True}.

**Returns:**
nilai boolean

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Mendapatkan dan mengatur flag yang menentukan apakah XFrom yang ditemukan pada halaman harus dibongkar atau tidak. Elemen XFrom dapat berakhir di file SVG yang berbeda. Hanya XForms yang dirender oleh pernyataan Do dari konten halaman yang dibongkar. XForms bersarang tidak dibongkar.

**Returns:**
nilai boolean

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Mendapatkan dan mengatur opsi untuk membongkar hanya XForm yang sesuai dengan predikat yang ditentukan.

**Returns:**
instansi Predicate internal dari instansi XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Mendapatkan dan mengatur opsi untuk secara otomatis mengelompokkan subpath menjadi gambar. Opsi ini mengecualikan opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Mendapatkan dan mengatur opsi untuk mengekstrak setiap subpath dari dokumen PDF menjadi gambar SVG terpisah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Mendapatkan dan mengatur persegi panjang pembatas yang menentukan area ekstraksi untuk ekstraksi SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Mendapatkan dan mengatur opsi Kekuatan pengelompokan subpath menjadi gambar. Memungkinkan Anda mengkonfigurasi tingkat pengelompokan subpath. Nilai berkisar dari 0 hingga 1. Nilai 0 berarti opsi {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) diaktifkan. Nilai 1 akan membuat satu gambar untuk semua jalur vektor pada halaman. Opsi ini berpengaruh ketika {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) bernilai false. Nilai default adalah {@code 0.8}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Mendapatkan atau mengatur lebar goresan minimum yang akan digunakan dalam SVG yang dihasilkan. Jika PDF menggunakan lebar goresan yang lebih tipis, lebar tersebut akan diganti dengan lebar ini. Nilai default adalah 0,5. Nilai ini dinyatakan dalam satuan ruang pengguna yang telah ditransformasi dari halaman PDF yang dikonversi. Secara default 1 satuan ruang pengguna adalah 1/72 inci (0,35 mm), tetapi dapat ditimpa oleh dokumen PDF. Transformasi dapat memengaruhi lebar minimum sebenarnya dalam SVG yang dihasilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Mendapatkan dan mengatur opsi untuk secara ketat memeriksa apakah subpath berada dalam persegi panjang yang ditentukan di {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). Jika diatur ke false, maka subpath yang tidak sepenuhnya termasuk dalam {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) akan diekstrak. Nilai default adalah {@code True}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Mendapatkan dan mengatur flag yang menentukan apakah XFrom yang ditemukan pada halaman harus dibongkar atau tidak. Elemen XFrom dapat berakhir di file SVG yang berbeda. Hanya XForms yang dirender oleh pernyataan Do dari konten halaman yang dibongkar. XForms bersarang tidak dibongkar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Mendapatkan dan mengatur opsi untuk membongkar hanya XForm yang sesuai dengan predikat yang ditentukan.
