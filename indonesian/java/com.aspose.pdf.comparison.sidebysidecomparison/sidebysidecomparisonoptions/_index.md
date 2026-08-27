---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas opsi untuk membandingkan dokumen dengan output berdampingan."
type: docs
weight: 60
url: /id/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Mewakili kelas opsi untuk membandingkan dokumen dengan output berdampingan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Membuat instance kelas {@link SideBySideComparisonOptions}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Mendapatkan dan mengatur properti yang menentukan apakah penanda perubahan tambahan ditampilkan. Jika diatur, menampilkan tanda perubahan yang tidak ada pada halaman saat ini tetapi ada pada halaman lain. Jika perubahan berada di antara kata, tanda tersebut mungkin tidak diposisikan secara tepat relatif terhadap karakter spasi. Nilai default adalah {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonArea2](#getComparisonArea2--) | Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonMode](#getComparisonMode--) | Mendapatkan dan mengatur mode perbandingan. Nilai default adalah {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Mendapatkan warna yang digunakan untuk menandai konten yang dihapus selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penghapusan dalam hasil perbandingan. |
| [getExcludeAreas1](#getExcludeAreas1--) | Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [getExcludeTables](#getExcludeTables--) | Dapatkan dan atur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) dan {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Nilai default adalah {@code false}. |
| [getInsertColor](#getInsertColor--) | Mendapatkan warna yang digunakan untuk menandai konten yang disisipkan selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penyisipan dalam hasil perbandingan. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Mendapatkan dan mengatur properti yang menentukan apakah penanda perubahan tambahan ditampilkan. Jika diatur, menampilkan tanda perubahan yang tidak ada pada halaman saat ini tetapi ada pada halaman lain. Jika perubahan berada di antara kata, tanda tersebut mungkin tidak diposisikan secara tepat relatif terhadap karakter spasi. Nilai default adalah {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonMode](#setComparisonMode-int-) | Mendapatkan dan mengatur mode perbandingan. Nilai default adalah {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Mengatur warna yang digunakan untuk menandai konten yang dihapus selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penghapusan dalam hasil perbandingan. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Dapatkan dan atur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) dan {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Nilai default adalah {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Mengatur warna yang digunakan untuk menandai konten yang disisipkan selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penyisipan dalam hasil perbandingan. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Membuat instance kelas {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Mendapatkan dan mengatur properti yang menentukan apakah penanda perubahan tambahan ditampilkan. Jika diatur, menampilkan tanda perubahan yang tidak ada pada halaman saat ini tetapi ada pada halaman lain. Jika perubahan berada di antara kata, tanda tersebut mungkin tidak diposisikan secara tepat relatif terhadap karakter spasi. Nilai default adalah {@code false}.

**Returns:**
nilai boolean

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instansi Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instansi Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Mendapatkan dan mengatur mode perbandingan. Nilai default adalah {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
Elemen ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Mendapatkan warna yang digunakan untuk menandai konten yang dihapus selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penghapusan dalam hasil perbandingan.

**Returns:**
warna yang digunakan untuk menandai konten yang dihapus selama perbandingan berdampingan.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

**Returns:**
array dari instance Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

**Returns:**
array dari instance Rectangle

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Dapatkan dan atur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) dan {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Nilai default adalah {@code false}.

**Returns:**
nilai boolean

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Mendapatkan warna yang digunakan untuk menandai konten yang disisipkan selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penyisipan dalam hasil perbandingan.

**Returns:**
warna yang digunakan untuk menandai konten yang disisipkan selama perbandingan berdampingan.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Mendapatkan dan mengatur properti yang menentukan apakah penanda perubahan tambahan ditampilkan. Jika diatur, menampilkan tanda perubahan yang tidak ada pada halaman saat ini tetapi ada pada halaman lain. Jika perubahan berada di antara kata, tanda tersebut mungkin tidak diposisikan secara tepat relatif terhadap karakter spasi. Nilai default adalah {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Mendapatkan dan mengatur area perbandingan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini tidak dapat diatur bersama dengan opsi {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) dan {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Mendapatkan dan mengatur mode perbandingan. Nilai default adalah {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Mengatur warna yang digunakan untuk menandai konten yang dihapus selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penghapusan dalam hasil perbandingan.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen pertama dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Dapatkan dan atur area yang dikecualikan. Digunakan untuk halaman atau dokumen kedua dalam metode perbandingan. Opsi ini dapat diatur bersama dengan {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersama dengan opsi {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Dapatkan dan atur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersama dengan {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) dan {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Nilai default adalah {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Mengatur warna yang digunakan untuk menandai konten yang disisipkan selama perbandingan berdampingan. Properti ini mendefinisikan representasi visual untuk penyisipan dalam hasil perbandingan.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
