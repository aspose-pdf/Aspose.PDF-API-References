---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMethod Aspose.Pdf.Security. Mewakili enum yang mendefinisikan metode yang digunakan untuk validasi sertifikat
type: docs
weight: 10050
url: /id/net/aspose.pdf.security/validationmethod/
---
## Enumerasi ValidationMethod

Mewakili enum yang mendefinisikan metode yang digunakan untuk validasi sertifikat.

```csharp
public enum ValidationMethod
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Secara otomatis menentukan metode terbaik untuk validasi sertifikat. |
| Ocsp | `1` | Menggunakan Protokol Status Sertifikat Daring (OCSP) untuk validasi sertifikat. OCSP adalah protokol yang memberikan status validasi dari sebuah sertifikat dengan langsung menanyakan kepada Otoritas Sertifikat (CA) yang menerbitkannya. |
| Crl | `2` | Memvalidasi sertifikat menggunakan metode Daftar Pencabutan Sertifikat (CRL). |
| All | `3` | Menggunakan semua metode yang tersedia (OCSP dan CRL) untuk validasi sertifikat. |

### Lihat Juga

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)