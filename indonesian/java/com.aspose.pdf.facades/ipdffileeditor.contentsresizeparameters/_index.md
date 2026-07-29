---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk menentukan parameter pengubahan ukuran halaman. Memungkinkan mengatur parameter berikut: Ukuran halaman hasil (lebar, tinggi) dalam satuan ruang default atau dalam persentase halaman awal."
type: docs
weight: 300
url: /id/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Kelas untuk menentukan parameter pengubahan ukuran halaman. Memungkinkan pengaturan parameter berikut: Ukuran halaman hasil (lebar, tinggi) dalam satuan ruang default atau dalam persentase ukuran halaman awal; Margin Kiri, Atas, Bawah, dan Kanan dalam satuan ruang default atau dalam persentase ukuran halaman awal; Beberapa nilai dapat dibiarkan null untuk perhitungan otomatis. Nilai-nilai ini akan dihitung dari sisa ukuran halaman setelah perhitungan nilai yang ditentukan secara eksplisit. Misalnya: jika lebar halaman = 100 dan lebar halaman baru ditentukan 60 satuan maka margin kiri dan kanan dihitung otomatis: (100 - 60) / 2 = 15. Kelas ini digunakan dalam metode ResizeContents.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Membuat parameter pengubahan ukuran di mana semua nilai diatur ke \"auto\". Margin dan ukuran konten kemudian dapat ditentukan jika diperlukan. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Membuat parameter pengubahan ukuran di mana semua nilai diatur ke \"auto\". Margin dan ukuran konten kemudian dapat ditentukan jika diperlukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Membuat parameter pengubahan ukuran dengan ukuran konten yang ditentukan. |
| [contentSizePercent](#contentSizePercent-double-double-) | Membuat parameter pengubahan ukuran dengan ukuran konten yang ditentukan dalam persentase ukuran halaman awal. Margin dihitung secara otomatis. |
| [getBottomMargin](#getBottomMargin--) | Mendapatkan atau mengatur margin bawah pada halaman hasil. |
| [getContentsHeight](#getContentsHeight--) | Mendapatkan atau mengatur tinggi konten halaman sumber pada halaman hasil. |
| [getContentsWidth](#getContentsWidth--) | Mendapatkan atau mengatur lebar konten halaman sumber pada halaman hasil. |
| [getLeftMargin](#getLeftMargin--) | Mendapatkan atau mengatur margin kiri pada halaman hasil. |
| [getRightMargin](#getRightMargin--) | Mendapatkan atau mengatur margin kanan pada halaman hasil. |
| [getTopMargin](#getTopMargin--) | Mendapatkan atau mengatur margin atas pada halaman hasil. |
| [isChangeMediaBox](#isChangeMediaBox--) | Mendapatkan apakah akan menyesuaikan MediaBox halaman PDF selama operasi pengubahan ukuran. Nilai default adalah {@code false}. Mengatur parameter ini memungkinkan menyesuaikan MediaBox ke nilai CropBox selama pengubahan ukuran. |
| [margins](#margins-double-double-double-double-) | Membuat parameter pengubahan ukuran dengan nilai margin yang ditentukan. Ukuran konten dihitung secara otomatis. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Membuat parameter ubah ukuran. Margin ditentukan dalam persentase ukuran halaman awal. |
| [pageResize](#pageResize-double-double-) | Membuat parameter ubah ukuran untuk mengubah ukuran halaman. |
| [pageResizePct](#pageResizePct-double-double-) | Membuat parameter ubah ukuran untuk mengubah ukuran halaman. Ukuran baru ditentukan dalam persen. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Mendapatkan atau mengatur margin bawah pada halaman hasil. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Mengatur apakah menyesuaikan MediaBox halaman PDF selama operasi pengubahan ukuran. Nilai default adalah {@code false} Mengatur parameter ini memungkinkan menyesuaikan MediaBox ke nilai CropBox selama pengubahan ukuran. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Mendapatkan atau mengatur tinggi konten halaman sumber pada halaman hasil. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Mendapatkan atau mengatur lebar konten halaman sumber pada halaman hasil. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Mendapatkan atau mengatur margin kiri pada halaman hasil. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Mendapatkan atau mengatur margin kanan pada halaman hasil. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Mendapatkan atau mengatur margin atas pada halaman hasil. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Membuat parameter pengubahan ukuran di mana semua nilai diatur ke \"auto\". Margin dan ukuran konten kemudian dapat ditentukan jika diperlukan.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Membuat parameter pengubahan ukuran di mana semua nilai diatur ke \"auto\". Margin dan ukuran konten kemudian dapat ditentukan jika diperlukan.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Membuat parameter pengubahan ukuran dengan ukuran konten yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar baru konten. |
| tinggi |  | Tinggi baru konten. |

**Returns:**
Mengembalikan parameter ubah ukuran baru.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Membuat parameter pengubahan ukuran dengan ukuran konten yang ditentukan dalam persentase ukuran halaman awal. Margin dihitung secara otomatis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar konten baru dalam persen. |
| tinggi |  | Tinggi konten baru dalam persen. |

**Returns:**
Parameter ubah ukuran baru.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Mendapatkan atau mengatur margin bawah pada halaman hasil.

**Returns:**
Objek ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Mendapatkan atau mengatur tinggi konten halaman sumber pada halaman hasil.

**Returns:**
Objek ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Mendapatkan atau mengatur lebar konten halaman sumber pada halaman hasil.

**Returns:**
Objek ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Mendapatkan atau mengatur margin kiri pada halaman hasil.

**Returns:**
Objek ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Mendapatkan atau mengatur margin kanan pada halaman hasil.

**Returns:**
Objek ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Mendapatkan atau mengatur margin atas pada halaman hasil.

**Returns:**
Objek ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Mendapatkan apakah akan menyesuaikan MediaBox halaman PDF selama operasi pengubahan ukuran. Nilai default adalah {@code false}. Mengatur parameter ini memungkinkan menyesuaikan MediaBox ke nilai CropBox selama pengubahan ukuran.

**Returns:**
apakah menyesuaikan MediaBox halaman PDF selama operasi pengubahan ukuran.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Membuat parameter pengubahan ukuran dengan nilai margin yang ditentukan. Ukuran konten dihitung secara otomatis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri |  | Margin kiri. |
| kanan |  | Margin kanan. |
| atas |  | Margin atas. |
| bawah |  | Margin bawah. |

**Returns:**
Parameter ubah ukuran yang dibuat.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Membuat parameter ubah ukuran. Margin ditentukan dalam persentase ukuran halaman awal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri |  | Margin kiri (dalam persentase lebar halaman). |
| kanan |  | Margin kanan (dalam persentase tinggi halaman). |
| atas |  | Margin atas (dalam persentase tinggi halaman). |
| bawah |  | Margin bawah (dalam persentase tinggi halaman). |

**Returns:**
Mengembalikan parameter ubah ukuran baru.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Membuat parameter ubah ukuran untuk mengubah ukuran halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar halaman baru dalam satuan. |
| tinggi |  | Tinggi halaman baru dalam satuan. |

**Returns:**
Parameter ubah ukuran baru.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Membuat parameter ubah ukuran untuk mengubah ukuran halaman. Ukuran baru ditentukan dalam persen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| widthPct |  | Lebar halaman baru dalam persen. |
| heightPct |  | Tinggi halaman baru dalam persen. |

**Returns:**
Parameter ubah ukuran baru.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Mendapatkan atau mengatur margin bawah pada halaman hasil.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Mengatur apakah menyesuaikan MediaBox halaman PDF selama operasi pengubahan ukuran. Nilai default adalah {@code false} Mengatur parameter ini memungkinkan menyesuaikan MediaBox ke nilai CropBox selama pengubahan ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | apakah menyesuaikan MediaBox halaman PDF selama operasi pengubahan ukuran. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Mendapatkan atau mengatur tinggi konten halaman sumber pada halaman hasil.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Mendapatkan atau mengatur lebar konten halaman sumber pada halaman hasil.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Mendapatkan atau mengatur margin kiri pada halaman hasil.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Mendapatkan atau mengatur margin kanan pada halaman hasil.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Mendapatkan atau mengatur margin atas pada halaman hasil.
