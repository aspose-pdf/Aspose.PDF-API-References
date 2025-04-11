---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMode Aspose.Pdf.Security. Menentukan mode validasi untuk proses validasi tanda tangan PDF
type: docs
weight: 10060
url: /id/net/aspose.pdf.security/validationmode/
---
## Enumerasi ValidationMode

Menentukan mode validasi untuk proses validasi tanda tangan PDF.

```csharp
public enum ValidationMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Mewakili mode di mana validasi tidak dilakukan. |
| OnlyCheck | `1` | Mewakili mode di mana validasi dilakukan, tetapi hasilnya tidak mempengaruhi validasi tanda tangan digital. Anda dapat memeriksa hasil validasi sendiri. |
| Strict | `2` | Mewakili mode di mana validasi dilakukan dan hasilnya mempengaruhi validasi tanda tangan digital. Jika sertifikat tidak dapat diverifikasi, maka tanda tangan digital akan dianggap tidak valid. Anda dapat memeriksa hasil validasi sendiri. |

### Lihat Juga

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)