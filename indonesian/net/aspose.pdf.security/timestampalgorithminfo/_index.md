---
title: "Kelas TimestampAlgorithmInfo"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Security.TimestampAlgorithmInfo. Mewakili kelas untuk informasi tentang algoritma tanda tangan timestamp"
type: docs
weight: 10210
url: /id/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

Mewakili kelas untuk informasi tentang algoritma tanda tangan timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Mendapatkan nama bidang tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Mengonversi objek informasi saat ini ke representasi string-nya. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Mendapatkan tipe algoritma tanda tangan yang digunakan untuk menandatangani dokumen PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Mengambil algoritma hash yang meng-hash konten dokumen dan kemudian menandatanganinya menggunakan [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Mendapatkan standar kriptografi yang digunakan untuk menandatangani dokumen PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Mendapatkan algoritma hash digest yang digunakan untuk tanda tangan. Untuk timestamp, ini adalah algoritma hash digest yang digunakan untuk menandatangani hash konten dokumen. |

### Lihat Juga

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


