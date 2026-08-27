---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang menjelaskan aksi submit-form."
type: docs
weight: 4690
url: /id/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Kelas yang menjelaskan aksi submit-form.

## Fields

| Field | Deskripsi |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Jika diatur, semua nilai bidang yang dikirim yang mewakili tanggal akan dikonversi ke format standar. |
| [EMBED_FORM](#EMBED_FORM) | Jika diatur, entri F dari FDF yang dikirim harus berupa spesifikasi file yang berisi aliran file tersemat yang mewakili file PDF tempat FDF dikirim. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Jika diatur, FDF yang dikirim harus mengecualikan entri F. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Jika diatur, hanya anotasi markup yang entri T‑nya cocok dengan nama pengguna saat ini yang akan disertakan. |
| [EXCLUDE](#EXCLUDE) | Jika kosong, array Fields menentukan bidang mana yang akan disertakan dalam pengiriman. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Jika diatur, nama dan nilai bidang akan dikirim dalam format Formulir HTML. |
| [GET_METHOD](#GET_METHOD) | Jika diatur, nama dan nilai bidang akan dikirim menggunakan permintaan HTTP GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Jika diatur, file FDF yang dikirim harus menyertakan semua anotasi markup dalam dokumen PDF yang mendasarinya. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Jika diatur, file FDF yang dikirim harus menyertakan konten semua pembaruan inkremental. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Jika diatur, semua bidang yang ditentukan oleh array Fields dan flag Sertakan/Kecualikan harus dikirim. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Jika diatur, koordinat klik mouse yang menyebabkan aksi submit-form harus ditransmisikan sebagai bagian dari data formulir. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Jika diatur, dokumen harus dikirim sebagai PDF, menggunakan tipe konten MIME application/pdf. |
| [XFDF](#XFDF) | Jika diatur, nama dan nilai bidang harus dikirim sebagai XFDF. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Menginisialisasi objek SubmitFormAction. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFlags](#getFlags--) | Mendapatkan flagas dari aksi submit |
| [getUrl](#getUrl--) | URL Tujuan. |
| [setFlags](#setFlags-int-) | Mengatur flagas dari aksi submit |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | URL Tujuan. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Jika diatur, semua nilai bidang yang dikirim yang mewakili tanggal akan dikonversi ke format standar.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Jika diatur, entri F dari FDF yang dikirim harus berupa spesifikasi file yang berisi aliran file tersemat yang mewakili file PDF tempat FDF dikirim.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Jika diatur, FDF yang dikirim harus mengecualikan entri F.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Jika diatur, hanya anotasi markup yang entri T‑nya cocok dengan nama pengguna saat ini yang akan disertakan.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Jika kosong, array Fields menentukan bidang mana yang akan disertakan dalam pengiriman.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Jika diatur, nama dan nilai bidang akan dikirim dalam format Formulir HTML.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Jika diatur, nama dan nilai bidang akan dikirim menggunakan permintaan HTTP GET.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Jika diatur, file FDF yang dikirim harus menyertakan semua anotasi markup dalam dokumen PDF yang mendasarinya.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Jika diatur, file FDF yang dikirim harus menyertakan konten semua pembaruan inkremental.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Jika diatur, semua bidang yang ditentukan oleh array Fields dan flag Sertakan/Kecualikan harus dikirim.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Jika diatur, koordinat klik mouse yang menyebabkan aksi submit-form harus ditransmisikan sebagai bagian dari data formulir.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Jika diatur, dokumen harus dikirim sebagai PDF, menggunakan tipe konten MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

Jika diatur, nama dan nilai bidang harus dikirim sebagai XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Menginisialisasi objek SubmitFormAction.

### getFlags {#getFlags--}
```
public int getFlags()
```

Mendapatkan flagas dari aksi submit

**Returns:**
nilai int

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

URL Tujuan.

**Returns:**
Nilai FileSpecification

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Mengatur flagas dari aksi submit

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
URL Tujuan.
