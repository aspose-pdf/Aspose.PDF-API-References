---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas menjelaskan daftar tindakan."
type: docs
weight: 3680
url: /id/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Kelas menjelaskan daftar tindakan.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Tambahkan aksi ke daftar aksi. |
| [delete](#delete-int-) | Hapus aksi berdasarkan indeks. |
| [get_Item](#get_Item-int-) | Mendapatkan aksi berdasarkan indeksnya. |
| [getCount](#getCount--) | Mendapatkan jumlah aksi. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Metode internal |
| [iterator](#iterator--) | Mendapatkan enumerator. |

### add {#add-com.aspose.pdf.PdfAction-}
Tambahkan aksi ke daftar aksi.

### delete {#delete-int-}
```
public void delete(int index)
```

Hapus aksi berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks aksi yang akan dihapus. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Mendapatkan aksi berdasarkan indeksnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Nilai indeks aksi. |

**Returns:**
Indeks PdfAction jika ditemukan; jika tidak, melempar @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Mendapatkan jumlah aksi.

**Returns:**
nilai int

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Metode internal

**Returns:**
objek internal.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Mendapatkan enumerator.

**Returns:**
enumerator PDfAction.
