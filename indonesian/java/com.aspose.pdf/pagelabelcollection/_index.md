---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili koleksi label halaman."
type: docs
weight: 3400
url: /id/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Kelas yang mewakili koleksi label halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLabel](#getLabel-int-) | Mendapatkan label halaman berdasarkan indeks halaman (indeks halaman dimulai dari 0). |
| [getPages](#getPages--) | Mendapatkan indeks halaman dalam koleksi. |
| [removeLabel](#removeLabel-int-) | Menghapus label berdasarkan indeks halaman (indeks halaman dimulai dari 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Memperbarui label untuk indeks halaman yang diberikan (indeks halaman dimulai dari 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Mendapatkan label halaman berdasarkan indeks halaman (indeks halaman dimulai dari 0).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageIndex |  | Indeks halaman. |

**Returns:**
Label halaman untuk indeks halaman yang ditentukan atau null jika label halaman tidak ada.

### getPages {#getPages--}
```
public int[] getPages()
```

Mendapatkan indeks halaman dalam koleksi.

**Returns:**
Array integer yang berisi indeks-indeks halaman.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Menghapus label berdasarkan indeks halaman (indeks halaman dimulai dari 0).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageIndex |  | Indeks halaman dimana label harus dihapus. |

**Returns:**
true jika operasi berhasil dijalankan.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Memperbarui label untuk indeks halaman yang diberikan (indeks halaman dimulai dari 0).
