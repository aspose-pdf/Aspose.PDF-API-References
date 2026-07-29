---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili hasil proses validasi untuk sebuah sertifikat. Kelas ValidationResult menyediakan informasi tentang hasil memvalidasi sebuah sertifikat, termasuk informasinya."
type: docs
weight: 40
url: /id/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Mewakili hasil proses validasi untuk sebuah sertifikat. Kelas ValidationResult menyediakan informasi tentang hasil validasi sertifikat, termasuk statusnya dan pesan yang menjelaskan masalah apa pun yang ditemui selama validasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Membuat instance dari kelas {@link ValidationResult}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMessage](#getMessage--) | Mewakili pesan yang terkait dengan hasil validasi. Properti Message menyediakan konteks tambahan atau informasi tentang keadaan hasil validasi. |
| [getStatus](#getStatus--) | Mendapatkan status proses validasi untuk sebuah sertifikat. Properti Status menunjukkan hasil dari validasi sertifikat. Nilai yang mungkin didefinisikan dalam enumerasi {@link ValidationStatus}, seperti Valid, Invalid, atau Undefined. Ini memberikan wawasan apakah sertifikat telah melewati pemeriksaan validasi atau tidak. |
| [setMessage](#setMessage-java.lang.String-) | Mewakili pesan yang terkait dengan hasil validasi. Properti Message menyediakan konteks tambahan atau informasi tentang keadaan hasil validasi. |
| [setStatus](#setStatus-int-) | Mendapatkan status proses validasi untuk sebuah sertifikat. Properti Status menunjukkan hasil dari validasi sertifikat. Nilai yang mungkin didefinisikan dalam enumerasi {@link ValidationStatus}, seperti Valid, Invalid, atau Undefined. Ini memberikan wawasan apakah sertifikat telah melewati pemeriksaan validasi atau tidak. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Membuat instance dari kelas {@link ValidationResult}.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Mewakili pesan yang terkait dengan hasil validasi. Properti Message menyediakan konteks tambahan atau informasi tentang keadaan hasil validasi.

**Returns:**
nilai String

### getStatus {#getStatus--}
```
public final int getStatus()
```

Mendapatkan status proses validasi untuk sebuah sertifikat. Properti Status menunjukkan hasil dari validasi sertifikat. Nilai yang mungkin didefinisikan dalam enumerasi {@link ValidationStatus}, seperti Valid, Invalid, atau Undefined. Ini memberikan wawasan apakah sertifikat telah melewati pemeriksaan validasi atau tidak.

**Returns:**
Elemen ValidationStatus

### setMessage {#setMessage-java.lang.String-}
Mewakili pesan yang terkait dengan hasil validasi. Properti Message menyediakan konteks tambahan atau informasi tentang keadaan hasil validasi.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Mendapatkan status proses validasi untuk sebuah sertifikat. Properti Status menunjukkan hasil dari validasi sertifikat. Nilai yang mungkin didefinisikan dalam enumerasi {@link ValidationStatus}, seperti Valid, Invalid, atau Undefined. Ini memberikan wawasan apakah sertifikat telah melewati pemeriksaan validasi atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ValidationStatus |
