---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili lokasi dalam dokumen PDF di mana kesalahan ekstraksi teks telah muncul."
type: docs
weight: 5050
url: /id/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Mewakili lokasi dalam dokumen PDF di mana kesalahan ekstraksi teks telah muncul.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Kunci (nama) dari objek Font PDF yang digunakan untuk menampilkan operator yang menyebabkan kesalahan ekstraksi teks. |
| [getFormKey](#getFormKey--) | Kunci (nama) dari XObject Form PDF di mana kesalahan ekstraksi teks aliran konten berada. Tidak kosong jika ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Jenis objek PDF (Page atau xForm) di mana kesalahan ekstraksi teks aliran konten berada. |
| [getOperatorIndex](#getOperatorIndex--) | Indeks operator penampilan teks dalam aliran konten (koleksi operator) yang menyebabkan kesalahan ekstraksi teks. |
| [getOperatorString](#getOperatorString--) | Operator penampilan teks yang menyebabkan kesalahan ekstraksi teks. |
| [getPageNumber](#getPageNumber--) | Nomor halaman dokumen tempat kesalahan ekstraksi teks berada. |
| [getPath](#getPath--) | Lokasi dokumen PDF tempat kesalahan ekstraksi teks muncul. |
| [getTextStartPoint](#getTextStartPoint--) | Kunci (nama) dari objek Font PDF yang digunakan untuk menampilkan operator yang menyebabkan kesalahan ekstraksi teks. |
| [toString](#toString--) | Mengembalikan representasi string. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Kunci (nama) dari objek Font PDF yang digunakan untuk menampilkan operator yang menyebabkan kesalahan ekstraksi teks.

**Returns:**
nilai String

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Kunci (nama) dari XObject Form PDF di mana kesalahan ekstraksi teks aliran konten berada. Tidak kosong jika ObjectType == 'xForm'.

**Returns:**
nilai String

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Jenis objek PDF (Page atau xForm) di mana kesalahan ekstraksi teks aliran konten berada.

**Returns:**
nilai String

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Indeks operator penampilan teks dalam aliran konten (koleksi operator) yang menyebabkan kesalahan ekstraksi teks.

**Returns:**
nilai int

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Operator penampilan teks yang menyebabkan kesalahan ekstraksi teks.

**Returns:**
nilai String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Nomor halaman dokumen tempat kesalahan ekstraksi teks berada.

**Returns:**
nilai int

### getPath {#getPath--}
```
public String getPath()
```

Lokasi dokumen PDF tempat kesalahan ekstraksi teks muncul.

**Returns:**
nilai String

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Kunci (nama) dari objek Font PDF yang digunakan untuk menampilkan operator yang menyebabkan kesalahan ekstraksi teks.

**Returns:**
Instansi Point

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi string.

**Returns:**
Representasi string.
