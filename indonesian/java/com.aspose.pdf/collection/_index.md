---
title: "Koleksi"
linktitle: "Koleksi"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk Collection(12.3.5 Collections)."
type: docs
weight: 610
url: /id/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Mewakili kelas untuk Collection(12.3.5 Collections).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Collection](#Collection--) | Menginisialisasi objek Collection baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Nama file tersemat default. |
| [getSchema](#getSchema--) | Mendapatkan "Schema" dari koleksi dokumen. |
| [getSortedCollection](#getSortedCollection--) | Mendapatkan koleksi file yang diurutkan sesuai spesifikasi. |

### Collection {#Collection--}
```
public Collection()
```

Menginisialisasi objek Collection baru.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Nama file tersemat default.

**Returns:**
Objek String

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Mendapatkan "Schema" dari koleksi dokumen.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Mendapatkan koleksi file yang diurutkan sesuai spesifikasi.

**Returns:**
Daftar file yang diurutkan.
