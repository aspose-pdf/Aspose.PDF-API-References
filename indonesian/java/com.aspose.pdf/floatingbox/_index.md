---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili FloatingBox dalam dokumen PDF. FloatingBox diposisikan secara khusus."
type: docs
weight: 1610
url: /id/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Mewakili FloatingBox dalam dokumen PDF. FloatingBox diposisikan secara khusus.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Menginisialisasi sebuah instance baru dari kelas {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | Menginisialisasi sebuah instance baru dari kelas {@code FloatingBox} dengan lebar dan tinggi yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Mengkloning objek {@code FloatingBox} baru. Paragraf dalam kotak mengambang tidak dikloning. |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan objek yang menunjukkan warna latar belakang kotak mengambang. |
| [getBackgroundImage](#getBackgroundImage--) | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [getBorder](#getBorder--) | Mendapatkan objek yang menunjukkan informasi batas kotak mengambang. |
| [getColumnInfo](#getColumnInfo--) | Mendapatkan informasi kolom |
| [getHeight](#getHeight--) | Mendapatkan nilai float yang menunjukkan tinggi kotak mengambang. |
| [getLeft](#getLeft--) | Mendapatkan koordinat kiri tabel. |
| [getPadding](#getPadding--) | Mendapatkan objek yang menunjukkan padding kotak mengambang. |
| [getParagraphs](#getParagraphs--) | Mendapatkan koleksi yang menunjukkan semua paragraf dalam sel. |
| [getPositioningMode](#getPositioningMode--) | Menentukan varian untuk menentukan lokasi FloatingBox pada halaman. |
| [getTop](#getTop--) | Mendapatkan koordinat atas tabel. |
| [getWidth](#getWidth--) | Mendapatkan nilai float yang menunjukkan lebar kotak mengambang. |
| [isNeedRepeating](#isNeedRepeating--) | Mendapatkan nilai boolean yang menunjukkan apakah paragraf perlu diulang pada halaman berikutnya. Nilai default adalah true.Atribut ini hanya berlaku ketika paragraf itu sendiri dan objek yang dirujuk oleh ReferenceParagraphID keduanya termasuk dalam RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mengatur objek yang menunjukkan warna latar belakang kotak mengambang. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Mengatur objek yang menunjukkan informasi batas kotak mengambang. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Mengatur informasi kolom |
| [setHeight](#setHeight-double-) | Mengatur nilai float yang menunjukkan tinggi kotak mengambang. |
| [setLeft](#setLeft-double-) | Mengatur koordinat kiri tabel. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Mengatur nilai boolean yang menunjukkan apakah paragraf perlu diulang pada halaman berikutnya. Nilai default adalah true.Atribut ini hanya berlaku ketika paragraf itu sendiri dan objek yang dirujuk oleh ReferenceParagraphID keduanya termasuk dalam RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Mengatur objek yang menunjukkan padding kotak mengambang. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Mengatur koleksi yang menunjukkan semua paragraf dalam sel. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Menentukan varian untuk menentukan lokasi FloatingBox pada halaman. |
| [setTop](#setTop-double-) | Mengatur koordinat atas tabel. |
| [setWidth](#setWidth-double-) | Mengatur nilai float yang menunjukkan lebar kotak mengambang. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Menginisialisasi sebuah instance baru dari kelas {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Menginisialisasi sebuah instance baru dari kelas {@code FloatingBox} dengan lebar dan tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar kotak. |
| tinggi |  | Tinggi kotak. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Mengkloning objek {@code FloatingBox} baru. Paragraf dalam kotak mengambang tidak dikloning.

**Returns:**
Objek {@code FloatingBox} baru.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Mendapatkan objek yang menunjukkan warna latar belakang kotak mengambang.

**Returns:**
objek yang menunjukkan warna latar belakang.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen).

**Returns:**
Instansi gambar

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Mendapatkan objek yang menunjukkan informasi batas kotak mengambang.

**Returns:**
objek yang menunjukkan informasi batas.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Mendapatkan informasi kolom

**Returns:**
objek ColumnInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Mendapatkan nilai float yang menunjukkan tinggi kotak mengambang.

**Returns:**
nilai yang menunjukkan tinggi.

### getLeft {#getLeft--}
```
public double getLeft()
```

Mendapatkan koordinat kiri tabel.

**Returns:**
koordinat kiri tabel.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Mendapatkan objek yang menunjukkan padding kotak mengambang.

**Returns:**
objek yang menunjukkan padding.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Mendapatkan koleksi yang menunjukkan semua paragraf dalam sel.

**Returns:**
koleksi yang menunjukkan semua paragraf.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Menentukan varian untuk menentukan lokasi FloatingBox pada halaman.

**Returns:**
elemen ParagraphPositioningMode

### getTop {#getTop--}
```
public double getTop()
```

Mendapatkan koordinat atas tabel.

**Returns:**
koordinat atas tabel.

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan nilai float yang menunjukkan lebar kotak mengambang.

**Returns:**
nilai double

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Mendapatkan nilai boolean yang menunjukkan apakah paragraf perlu diulang pada halaman berikutnya. Nilai default adalah true.Atribut ini hanya berlaku ketika paragraf itu sendiri dan objek yang dirujuk oleh ReferenceParagraphID keduanya termasuk dalam RepeatingRows.

**Returns:**
nilai boolean

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mengatur objek yang menunjukkan warna latar belakang kotak mengambang.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Mendapatkan atau mengatur gambar latar belakang untuk halaman (hanya untuk generator, tidak diisi saat membaca dokumen).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Mengatur objek yang menunjukkan informasi batas kotak mengambang.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Mengatur informasi kolom

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Mengatur nilai float yang menunjukkan tinggi kotak mengambang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang menunjukkan tinggi. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Mengatur koordinat kiri tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | koordinat kiri tabel. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Mengatur nilai boolean yang menunjukkan apakah paragraf perlu diulang pada halaman berikutnya. Nilai default adalah true.Atribut ini hanya berlaku ketika paragraf itu sendiri dan objek yang dirujuk oleh ReferenceParagraphID keduanya termasuk dalam RepeatingRows.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Mengatur objek yang menunjukkan padding kotak mengambang.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Mengatur koleksi yang menunjukkan semua paragraf dalam sel.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Menentukan varian untuk menentukan lokasi FloatingBox pada halaman.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Mengatur koordinat atas tabel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | koordinat atas tabel. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Mengatur nilai float yang menunjukkan lebar kotak mengambang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |
