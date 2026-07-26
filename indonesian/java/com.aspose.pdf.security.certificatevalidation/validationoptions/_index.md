---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memvalidasi tanda tangan digital dalam dokumen PDF."
type: docs
weight: 30
url: /id/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

Mewakili opsi untuk memvalidasi tanda tangan digital dalam dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | Membuat instance dari kelas {@link ValidationOptions}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah rantai sertifikat harus diperiksa selama proses validasi. Ketika properti ini diatur, keberadaan rantai sertifikat akan diperiksa; jika tidak ada, maka hasil verifikasi akan menjadi {@link ValidationStatus#Undefined}, yang sesuai dengan perilaku Adobe Acrobat. Jika Anda hanya ingin memeriksa status pencabutan secara daring, maka atur bidang menjadi {@code false}. Nilai default adalah {@code false}. |
| [getRequestTimeout](#getRequestTimeout--) | Mendapatkan atau mengatur durasi batas waktu, dalam milidetik, untuk operasi terkait jaringan selama proses validasi. Properti RequestTimeout menentukan waktu maksimum yang harus ditunggu sistem untuk respons jaringan saat mengakses sumber daya daring, seperti status pencabutan atau server OCSP. |
| [getValidationMethod](#getValidationMethod--) | Mendapatkan atau mengatur metode yang digunakan untuk memvalidasi sebuah sertifikat. |
| [getValidationMode](#getValidationMode--) | Mendapatkan atau mengatur mode validasi untuk tanda tangan digital dalam dokumen PDF. Properti ValidationMode menentukan tingkat keketatan proses validasi. |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah rantai sertifikat harus diperiksa selama proses validasi. Ketika properti ini diatur, keberadaan rantai sertifikat akan diperiksa; jika tidak ada, maka hasil verifikasi akan menjadi {@link ValidationStatus#Undefined}, yang sesuai dengan perilaku Adobe Acrobat. Jika Anda hanya ingin memeriksa status pencabutan secara daring, maka atur bidang menjadi {@code false}. Nilai default adalah {@code false}. |
| [setRequestTimeout](#setRequestTimeout-int-) | Mendapatkan atau mengatur durasi batas waktu, dalam milidetik, untuk operasi terkait jaringan selama proses validasi. Properti RequestTimeout menentukan waktu maksimum yang harus ditunggu sistem untuk respons jaringan saat mengakses sumber daya daring, seperti status pencabutan atau server OCSP. |
| [setValidationMethod](#setValidationMethod-int-) | Mendapatkan atau mengatur metode yang digunakan untuk memvalidasi sebuah sertifikat. |
| [setValidationMode](#setValidationMode-int-) | Mendapatkan atau mengatur mode validasi untuk tanda tangan digital dalam dokumen PDF. Properti ValidationMode menentukan tingkat keketatan proses validasi. |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

Membuat instance dari kelas {@link ValidationOptions}.

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah rantai sertifikat harus diperiksa selama proses validasi. Ketika properti ini diatur, keberadaan rantai sertifikat akan diperiksa; jika tidak ada, maka hasil verifikasi akan menjadi {@link ValidationStatus#Undefined}, yang sesuai dengan perilaku Adobe Acrobat. Jika Anda hanya ingin memeriksa status pencabutan secara daring, maka atur bidang menjadi {@code false}. Nilai default adalah {@code false}.

**Returns:**
nilai boolean

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

Mendapatkan atau mengatur durasi batas waktu, dalam milidetik, untuk operasi terkait jaringan selama proses validasi. Properti RequestTimeout menentukan waktu maksimum yang harus ditunggu sistem untuk respons jaringan saat mengakses sumber daya daring, seperti status pencabutan atau server OCSP.

**Returns:**
nilai int

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

Mendapatkan atau mengatur metode yang digunakan untuk memvalidasi sebuah sertifikat.

**Returns:**
Elemen ValidationMethod

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

Mendapatkan atau mengatur mode validasi untuk tanda tangan digital dalam dokumen PDF. Properti ValidationMode menentukan tingkat keketatan proses validasi.

**Returns:**
Elemen ValidationMode

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah rantai sertifikat harus diperiksa selama proses validasi. Ketika properti ini diatur, keberadaan rantai sertifikat akan diperiksa; jika tidak ada, maka hasil verifikasi akan menjadi {@link ValidationStatus#Undefined}, yang sesuai dengan perilaku Adobe Acrobat. Jika Anda hanya ingin memeriksa status pencabutan secara daring, maka atur bidang menjadi {@code false}. Nilai default adalah {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

Mendapatkan atau mengatur durasi batas waktu, dalam milidetik, untuk operasi terkait jaringan selama proses validasi. Properti RequestTimeout menentukan waktu maksimum yang harus ditunggu sistem untuk respons jaringan saat mengakses sumber daya daring, seperti status pencabutan atau server OCSP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

Mendapatkan atau mengatur metode yang digunakan untuk memvalidasi sebuah sertifikat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ValidationMethod |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

Mendapatkan atau mengatur mode validasi untuk tanda tangan digital dalam dokumen PDF. Properti ValidationMode menentukan tingkat keketatan proses validasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ValidationMode |
