---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas bidang skema koleksi dokumen."
type: docs
weight: 620
url: /id/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Mewakili kelas bidang skema koleksi dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getE](#getE--) | Mendapatkan flag yang menunjukkan apakah pemroses PDF interaktif harus menyediakan dukungan untuk mengedit nilai bidang. Nilai default: false |
| [getFiledType](#getFiledType--) | Mendapatkan tipe nilai bidang dalam koleksi skema. Field ini menjelaskan tipe nilai yang sesuai dengan {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Mendapatkan nama bidang tekstual yang akan ditampilkan kepada pengguna oleh pemroses PDF interaktif |
| [getO](#getO--) | Mendapatkan urutan relatif nama bidang dalam antarmuka pengguna. Bidang-bidang akan diurutkan oleh pemroses PDF interaktif secara naik. |
| [getSubtype](#getSubtype--) | Mendapatkan subtipe nilai bidang dalam koleksi skema. Subtipe bidang koleksi atau bidang terkait file yang dijelaskan oleh kamus ini. Entri ini mengidentifikasi tipe data yang akan disimpan dalam bidang. |
| [getV](#getV--) | Mendapatkan visibilitas awal bidang dalam antarmuka pengguna. Nilai default: true. |

### getE {#getE--}
```
public final boolean getE()
```

Mendapatkan flag yang menunjukkan apakah pemroses PDF interaktif harus menyediakan dukungan untuk mengedit nilai bidang. Nilai default: false

**Returns:**
nilai boolean

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Mendapatkan tipe nilai bidang dalam koleksi skema. Field ini menjelaskan tipe nilai yang sesuai dengan {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
Elemen FieldValueType

### getN {#getN--}
```
public final String getN()
```

Mendapatkan nama bidang tekstual yang akan ditampilkan kepada pengguna oleh pemroses PDF interaktif

**Returns:**
nilai String

### getO {#getO--}
```
public final Integer [] getO()
```

Mendapatkan urutan relatif nama bidang dalam antarmuka pengguna. Bidang-bidang akan diurutkan oleh pemroses PDF interaktif secara naik.

**Returns:**
array of Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Mendapatkan subtipe nilai bidang dalam koleksi skema. Subtipe bidang koleksi atau bidang terkait file yang dijelaskan oleh kamus ini. Entri ini mengidentifikasi tipe data yang akan disimpan dalam bidang.

**Returns:**
Elemen CollectionFieldSubtype

### getV {#getV--}
```
public final boolean getV()
```

Mendapatkan visibilitas awal bidang dalam antarmuka pengguna. Nilai default: true.

**Returns:**
nilai boolean
