---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Security.TimestampAlgorithmInfo. Mewakili kelas untuk informasi tentang algoritma tanda tangan timestamp
type: docs
weight: 10030
url: /id/net/aspose.pdf.security/timestampalgorithminfo/
---
## Kelas TimestampAlgorithmInfo

Mewakili kelas untuk informasi tentang algoritma tanda tangan timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Mendapatkan nama dari bidang tanda tangan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Mengonversi objek informasi saat ini ke representasi string-nya. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Mendapatkan jenis algoritma tanda tangan yang digunakan untuk menandatangani dokumen PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Mendapatkan algoritma hash yang meng-hash konten dokumen dan kemudian menandatanganinya menggunakan [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Mendapatkan standar kriptografi yang digunakan untuk menandatangani dokumen PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Mendapatkan algoritma hash digest yang digunakan untuk tanda tangan. Untuk timestamp, ini adalah algoritma hash digest dengan mana hash dari konten dokumen ditandatangani. |

### Lihat Juga

* kelas [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)