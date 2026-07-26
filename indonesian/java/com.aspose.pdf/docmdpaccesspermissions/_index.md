---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Izin akses yang diberikan untuk dokumen ini. Nilai yang valid adalah: 1 - Tidak ada perubahan pada dokumen yang diizinkan; setiap perubahan pada dokumen akan membatalkan tanda tangan. 2 -."
type: docs
weight: 1010
url: /id/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Izin akses yang diberikan untuk dokumen ini. Nilai yang valid adalah: 1 - Tidak ada perubahan pada dokumen yang diizinkan; setiap perubahan pada dokumen akan membatalkan tanda tangan. 2 - Perubahan yang diizinkan meliputi mengisi formulir, menginstansiasi templat halaman, dan menandatangani; perubahan lain akan membatalkan tanda tangan. 3 - Perubahan yang diizinkan sama dengan nomor 2, serta pembuatan, penghapusan, dan modifikasi anotasi; perubahan lain akan membatalkan tanda tangan.

## Fields

| Field | Deskripsi |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Perubahan yang diizinkan sama seperti pada 2, serta pembuatan, penghapusan, dan modifikasi anotasi; perubahan lain membatalkan tanda tangan. |
| [FillingInForms](#FillingInForms) | 2 - Perubahan yang diizinkan meliputi mengisi formulir, menginstansiasi templat halaman, dan menandatangani; perubahan lain membatalkan tanda tangan. |
| [NoChanges](#NoChanges) | 1 - Tidak ada perubahan pada dokumen yang diizinkan; setiap perubahan pada dokumen membatalkan tanda tangan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Perubahan yang diizinkan sama seperti pada 2, serta pembuatan, penghapusan, dan modifikasi anotasi; perubahan lain membatalkan tanda tangan.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Perubahan yang diizinkan meliputi mengisi formulir, menginstansiasi templat halaman, dan menandatangani; perubahan lain membatalkan tanda tangan.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Tidak ada perubahan pada dokumen yang diizinkan; setiap perubahan pada dokumen membatalkan tanda tangan.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
