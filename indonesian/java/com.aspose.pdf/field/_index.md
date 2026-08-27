---
title: "Field"
linktitle: "Field"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas dasar untuk bidang formulir acro."
type: docs
weight: 1380
url: /id/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Kelas dasar untuk bidang formulir acro.

## Fields

| Field | Deskripsi |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Membuat bidang untuk digunakan dalam Generator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Menjalankan aksi JavaScript yang ditentukan untuk bidang. |
| [flatten](#flatten--) | Menghapus bidang ini dan menempatkan nilainya langsung pada halaman. |
| [get_Item](#get_Item-int-) | Mendapatkan subbidang yang terdapat dalam bidang ini berdasarkan indeks. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan subbidang yang terdapat dalam bidang ini berdasarkan nama subbidang. |
| [getAlternateName](#getAlternateName--) | Mendapatkan nama alternatif bidang (Nama bidang alternatif yang akan digunakan menggantikan nama bidang sebenarnya di mana pun bidang tersebut diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip bidang di Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Mendapatkan indeks anotasi ini pada halaman. |
| [getMappingName](#getMappingName--) | Mendapatkan nama pemetaan bidang yang akan digunakan saat mengekspor data bidang formulir interaktif dari dokumen. |
| [getMaxFontSize](#getMaxFontSize--) | Ukuran font maksimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran. |
| [getMinFontSize](#getMinFontSize--) | Ukuran font minimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran. |
| [getPageIndex](#getPageIndex--) | Mendapatkan indeks halaman yang berisi bidang ini. |
| [getPartialName](#getPartialName--) | Mendapatkan nama parsial bidang. |
| [getRect](#getRect--) | Mendapatkan persegi panjang bidang. |
| [getSyncRoot](#getSyncRoot--) | Objek sinkronisasi. |
| [getTabOrder](#getTabOrder--) | Mendapatkan atau mengatur urutan tab bidang. |
| [getValue](#getValue--) | Mendapatkan nilai bidang. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Jika true maka ukuran font akan dikurangi agar teks sesuai dengan persegi panjang yang ditentukan. |
| [isGroup](#isGroup--) | Mendapatkan nilai boolean yang menunjukkan apakah bidang ini bukan bidang terminal, yaitu grup bidang. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Properti untuk dukungan Generator. Digunakan ketika bidang ditambahkan ke header atau footer. Jika true, bidang ini akan dibuat sekali dan tampilannya akan terlihat pada semua halaman dokumen. Jika false, bidang terpisah akan dibuat untuk setiap halaman dokumen. |
| [isSynchronized](#isSynchronized--) | Mengembalikan true jika kamus disinkronkan. |
| [iterator](#iterator--) | Mengembalikan enumerator dari bidang yang terkandung. |
| [recalculate](#recalculate--) | Menghitung ulang semua bidang terhitung pada formulir. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Mengatur nama alternatif bidang (Nama bidang alternatif yang akan digunakan menggantikan nama bidang sebenarnya di mana pun bidang tersebut diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip bidang di Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Mengatur indeks anotasi ini pada halaman. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Jika true maka ukuran font akan dikurangi agar teks sesuai dengan persegi panjang yang ditentukan. |
| [setMappingName](#setMappingName-java.lang.String-) | Mengatur nama pemetaan bidang yang akan digunakan saat mengekspor data bidang formulir interaktif dari dokumen. |
| [setMaxFontSize](#setMaxFontSize-double-) | Ukuran font maksimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran. |
| [setMinFontSize](#setMinFontSize-double-) | Ukuran font minimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran. |
| [setPartialName](#setPartialName-java.lang.String-) | Mengatur nama parsial bidang. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Atur posisi bidang. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Mengatur persegi panjang bidang. |
| [setSharedField](#setSharedField-boolean-) | Properti untuk dukungan Generator. Digunakan ketika bidang ditambahkan ke header atau footer. Jika true, bidang ini akan dibuat sekali dan tampilannya akan terlihat pada semua halaman dokumen. Jika false, bidang terpisah akan dibuat untuk setiap halaman dokumen. |
| [setTabOrder](#setTabOrder-int-) | Mendapatkan atau mengatur urutan tab bidang. |
| [setValue](#setValue-java.lang.String-) | Atur nilai. |
| [size](#size--) | Mendapatkan jumlah subbidang dalam bidang ini. (Misalnya jumlah item dalam bidang tombol radio). |
| [updateAppearances](#updateAppearances--) | Perbarui nilai tampilan. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Membuat bidang untuk digunakan dalam Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Menjalankan aksi JavaScript yang ditentukan untuk bidang.

### flatten {#flatten--}
```
public void flatten()
```

Menghapus bidang ini dan menempatkan nilainya langsung pada halaman.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Mendapatkan subbidang yang terdapat dalam bidang ini berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks subbidang yang diminta. |

**Returns:**
Instansi bidang.

### get_Item {#get_Item-java.lang.String-}
Mendapatkan subbidang yang terdapat dalam bidang ini berdasarkan nama subbidang.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Mendapatkan nama alternatif bidang (Nama bidang alternatif yang akan digunakan menggantikan nama bidang sebenarnya di mana pun bidang tersebut diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip bidang di Adobe Acrobat.

**Returns:**
nilai String

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Mendapatkan indeks anotasi ini pada halaman.

**Returns:**
nilai int

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Mendapatkan nama pemetaan bidang yang akan digunakan saat mengekspor data bidang formulir interaktif dari dokumen.

**Returns:**
nilai String

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Ukuran font maksimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran.

**Returns:**
nilai double

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Ukuran font minimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran.

**Returns:**
nilai double

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Mendapatkan indeks halaman yang berisi bidang ini.

**Returns:**
nilai int

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Mendapatkan nama parsial bidang.

**Returns:**
nilai String

### getRect {#getRect--}
```
public Rectangle getRect()
```

Mendapatkan persegi panjang bidang.

**Returns:**
persegi panjang bidang.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objek sinkronisasi.

**Returns:**
nilai objek

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Mendapatkan atau mengatur urutan tab bidang.

**Returns:**
nilai int

### getValue {#getValue--}
```
public String getValue()
```

Mendapatkan nilai bidang.

**Returns:**
nilai String

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Jika true maka ukuran font akan dikurangi agar teks sesuai dengan persegi panjang yang ditentukan.

**Returns:**
nilai boolean

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Mendapatkan nilai boolean yang menunjukkan apakah bidang ini bukan bidang terminal, yaitu grup bidang.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Properti untuk dukungan Generator. Digunakan ketika bidang ditambahkan ke header atau footer. Jika true, bidang ini akan dibuat sekali dan tampilannya akan terlihat pada semua halaman dokumen. Jika false, bidang terpisah akan dibuat untuk setiap halaman dokumen.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mengembalikan true jika kamus disinkronkan.

**Returns:**
nilai boolean

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Mengembalikan enumerator dari bidang yang terkandung.

**Returns:**
Objek Enumerator.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Menghitung ulang semua bidang terhitung pada formulir.

**Returns:**
benar jika nilai bidang diubah selama perhitungan ulang.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Mengatur nama alternatif bidang (Nama bidang alternatif yang akan digunakan menggantikan nama bidang sebenarnya di mana pun bidang tersebut diidentifikasi dalam antarmuka pengguna). Nama alternatif digunakan sebagai tooltip bidang di Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Mengatur indeks anotasi ini pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Jika true maka ukuran font akan dikurangi agar teks sesuai dengan persegi panjang yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMappingName {#setMappingName-java.lang.String-}
Mengatur nama pemetaan bidang yang akan digunakan saat mengekspor data bidang formulir interaktif dari dokumen.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Ukuran font maksimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Ukuran font minimal yang dapat digunakan untuk isi bidang. -1 untuk tidak memeriksa ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setPartialName {#setPartialName-java.lang.String-}
Mengatur nama parsial bidang.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Atur posisi bidang.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Mengatur persegi panjang bidang.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Properti untuk dukungan Generator. Digunakan ketika bidang ditambahkan ke header atau footer. Jika true, bidang ini akan dibuat sekali dan tampilannya akan terlihat pada semua halaman dokumen. Jika false, bidang terpisah akan dibuat untuk setiap halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Mendapatkan atau mengatur urutan tab bidang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setValue {#setValue-java.lang.String-}
Atur nilai.

### size {#size--}
```
public int size()
```

Mendapatkan jumlah subbidang dalam bidang ini. (Misalnya jumlah item dalam bidang tombol radio).

**Returns:**
nilai int

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Perbarui nilai tampilan.
