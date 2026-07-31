---
title: "Enum ValidationMethod"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Security.ValidationMethod. Mewakili enum yang mendefinisikan metode yang digunakan untuk validasi sertifikat"
type: docs
weight: 10230
url: /id/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

Mewakili enum yang mendefinisikan metode yang digunakan untuk validasi sertifikat.

```csharp
public enum ValidationMethod
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Secara otomatis menentukan metode terbaik untuk validasi sertifikat. |
| Ocsp | `1` | Menggunakan Online Certificate Status Protocol (OCSP) untuk validasi sertifikat. OCSP adalah protokol yang menyediakan status validasi sebuah sertifikat dengan langsung menanyakan Otoritas Sertifikat (CA) yang mengeluarkannya. |
| Crl | `2` | Memvalidasi sertifikat menggunakan metode Certificate Revocation List (CRL). |
| All | `3` | Menggunakan semua metode yang tersedia (OCSP dan CRL) untuk validasi sertifikat. |

### Lihat Juga

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


