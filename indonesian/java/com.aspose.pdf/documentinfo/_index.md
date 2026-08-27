---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili metadata dokumen PDF."
type: docs
weight: 1160
url: /id/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Mewakili metadata dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Inisialisasi instance DocumentInfo. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Menambahkan elemen dengan kunci dan nilai yang ditentukan ke dalam koleksi. |
| [clear](#clear--) | Menghapus informasi dokumen. |
| [clearCustomData](#clearCustomData--) | Hanya menghapus data khusus, meninggalkan semua nilai bawaan lainnya (Title, Author, dll.). |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan nilai yang terkait dengan kunci yang ditentukan. |
| [getAuthor](#getAuthor--) | Mendapatkan penulis dokumen. |
| [getCreationDate](#getCreationDate--) | Mendapatkan tanggal pembuatan dokumen. |
| [getCreationTimeZone](#getCreationTimeZone--) | Zona waktu tanggal pembuatan dalam milidetik. |
| [getCreator](#getCreator--) | Mendapatkan pembuat dokumen. |
| [getKeywords](#getKeywords--) | Mendapatkan kata kunci dokumen. |
| [getModDate](#getModDate--) | Mendapatkan tanggal modifikasi dokumen. |
| [getModTimeZone](#getModTimeZone--) | Zona waktu tanggal modifikasi. |
| [getProducer](#getProducer--) | Mendapatkan produsen dokumen. |
| [getSubject](#getSubject--) | Mendapatkan subjek dokumen. |
| [getTitle](#getTitle--) | Mendapatkan judul dokumen. |
| [getTrapped](#getTrapped--) | Mendapatkan flag trapped. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Menentukan apakah kunci sudah ditentukan sebelumnya (Title, Author, dll.), bukan khusus. |
| [remove](#remove-java.lang.String-) | Menghapus elemen dengan kunci yang ditentukan dari koleksi. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Mengatur nilai yang terkait dengan kunci yang ditentukan. |
| [setAuthor](#setAuthor-java.lang.String-) | Mengatur penulis dokumen. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Mengatur tanggal pembuatan dokumen. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Zona waktu tanggal pembuatan dalam milidetik. |
| [setCreator](#setCreator-java.lang.String-) | Mengatur pembuat dokumen. |
| [setKeywords](#setKeywords-java.lang.String-) | Atur kata kunci dokumen. |
| [setModDate](#setModDate-java.util.Date-) | Mengatur tanggal modifikasi dokumen. |
| [setModTimeZone](#setModTimeZone-double-) | Zona waktu tanggal modifikasi. |
| [setProducer](#setProducer-java.lang.String-) | Mengatur produsen dokumen. |
| [setSubject](#setSubject-java.lang.String-) | Mengatur subjek dokumen. |
| [setTitle](#setTitle-java.lang.String-) | Mengatur judul dokumen. |
| [setTrapped](#setTrapped-java.lang.String-) | Mengatur flag terperangkap. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Inisialisasi instance DocumentInfo.

### addItem {#addItem-java.lang.String-java.lang.String-}
Menambahkan elemen dengan kunci dan nilai yang ditentukan ke dalam koleksi.

### clear {#clear--}
```
public void clear()
```

Menghapus informasi dokumen.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Hanya menghapus data khusus, meninggalkan semua nilai bawaan lainnya (Title, Author, dll.).

### get_Item {#get_Item-java.lang.String-}
Mendapatkan nilai yang terkait dengan kunci yang ditentukan.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Mendapatkan penulis dokumen.

**Returns:**
nilai String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Mendapatkan tanggal pembuatan dokumen.

**Returns:**
Objek Date

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Zona waktu tanggal pembuatan dalam milidetik.

**Returns:**
nilai double

### getCreator {#getCreator--}
```
public String getCreator()
```

Mendapatkan pembuat dokumen.

**Returns:**
nilai String

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Mendapatkan kata kunci dokumen.

**Returns:**
nilai String

### getModDate {#getModDate--}
```
public Date getModDate()
```

Mendapatkan tanggal modifikasi dokumen.

**Returns:**
Objek Date

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Zona waktu tanggal modifikasi.

**Returns:**
nilai double

### getProducer {#getProducer--}
```
public String getProducer()
```

Mendapatkan produsen dokumen.

**Returns:**
nilai String

### getSubject {#getSubject--}
```
public String getSubject()
```

Mendapatkan subjek dokumen.

**Returns:**
nilai String

### getTitle {#getTitle--}
```
public String getTitle()
```

Mendapatkan judul dokumen.

**Returns:**
nilai String

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Mendapatkan flag trapped.

**Returns:**
nilai String

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Menentukan apakah kunci sudah ditentukan sebelumnya (Title, Author, dll.), bukan khusus.

### remove {#remove-java.lang.String-}
Menghapus elemen dengan kunci yang ditentukan dari koleksi.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Mengatur nilai yang terkait dengan kunci yang ditentukan.

### setAuthor {#setAuthor-java.lang.String-}
Mengatur penulis dokumen.

### setCreationDate {#setCreationDate-java.util.Date-}
Mengatur tanggal pembuatan dokumen.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Zona waktu tanggal pembuatan dalam milidetik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | dalam milidetik |

### setCreator {#setCreator-java.lang.String-}
Mengatur pembuat dokumen.

### setKeywords {#setKeywords-java.lang.String-}
Atur kata kunci dokumen.

### setModDate {#setModDate-java.util.Date-}
Mengatur tanggal modifikasi dokumen.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Zona waktu tanggal modifikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setProducer {#setProducer-java.lang.String-}
Mengatur produsen dokumen.

### setSubject {#setSubject-java.lang.String-}
Mengatur subjek dokumen.

### setTitle {#setTitle-java.lang.String-}
Mengatur judul dokumen.

### setTrapped {#setTrapped-java.lang.String-}
Mengatur flag terperangkap.
