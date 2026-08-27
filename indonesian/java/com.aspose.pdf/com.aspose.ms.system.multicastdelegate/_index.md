---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang merepresentasikan peristiwa"
type: docs
weight: 740
url: /id/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Kelas yang merepresentasikan peristiwa

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-T-) | Tambahkan satu delegasi lagi. |
| [assign](#assign-T-) | Tambahkan hanya delegasi saat ini, menghapus yang lain. |
| [clear](#clear--) | Bersihkan daftar delegasi |
| [isEmpty](#isEmpty--) | Mengembalikan true jika daftar penangan kosong |
| [remove](#remove-T-) | Hapus delegasi dari daftar |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Tambahkan satu delegasi lagi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| delegasi |  | Objek Penangan |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Tambahkan hanya delegasi saat ini, menghapus yang lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| delegasi |  | Objek Penangan |

### clear {#clear--}
```
public final void clear()
```

Bersihkan daftar delegasi

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Mengembalikan true jika daftar penangan kosong

**Returns:**
nilai boolean

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Hapus delegasi dari daftar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| delegasi |  | Objek Penangan |
