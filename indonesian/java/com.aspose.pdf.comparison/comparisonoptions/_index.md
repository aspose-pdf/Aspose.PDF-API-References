---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas opsi perbandingan dokumen PDF."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Mewakili kelas opsi perbandingan dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Membuat sebuah instance kelas {@link ComparisonOptions}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Mendapatkan dan mengatur urutan operasi edit. |
| [getExcludeAreas1](#getExcludeAreas1--) | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman pertama atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . |
| [getExcludeAreas2](#getExcludeAreas2--) | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman kedua atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . |
| [getExtractionArea](#getExtractionArea--) | Mendapatkan dan mengatur area persegi panjang di mana teks halaman akan dibandingkan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) dan { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) . |
| [isExcludeTables](#isExcludeTables--) | Mendapatkan dan mengatur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . Nilai default adalah {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Mendapatkan dan mengatur urutan operasi edit. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman pertama atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman kedua atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . |
| [setExcludeTables](#setExcludeTables-boolean-) | Mendapatkan dan mengatur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . Nilai default adalah {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Mendapatkan dan mengatur area persegi panjang di mana teks halaman akan dibandingkan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) dan { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) . |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Membuat sebuah instance kelas {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Mendapatkan dan mengatur urutan operasi edit.

**Returns:**
Elemen EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman pertama atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) .

**Returns:**
array dari instance Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman kedua atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) .

**Returns:**
array dari instance Rectangle

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Mendapatkan dan mengatur area persegi panjang di mana teks halaman akan dibandingkan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) dan { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instansi Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Mendapatkan dan mengatur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . Nilai default adalah {@code false}.

**Returns:**
nilai boolean

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Mendapatkan dan mengatur urutan operasi edit.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman pertama atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) .

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Mendapatkan dan mengatur area yang dikecualikan. Digunakan untuk halaman kedua atau dokumen dalam metode perbandingan. Opsi ini dapat diatur bersamaan dengan {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) .

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Mendapatkan dan mengatur opsi yang menentukan apakah tabel dikecualikan dari perbandingan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}) . Nilai default adalah {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Mendapatkan dan mengatur area persegi panjang di mana teks halaman akan dibandingkan. Opsi ini tidak dapat diatur bersamaan dengan {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) dan { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) .
