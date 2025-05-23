---
title: Class EcdsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Security.EcdsaAlgorithmInfo. Mewakili kelas untuk informasi tentang algoritma tanda tangan ECDSA
type: docs
weight: 9970
url: /id/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## Kelas EcdsaAlgorithmInfo

Mewakili kelas untuk informasi tentang algoritma tanda tangan ECDSA.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Mendapatkan standar kriptografi yang digunakan untuk menandatangani dokumen PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Mendapatkan algoritma hash digest yang digunakan untuk tanda tangan. Untuk cap waktu, ini adalah algoritma hash digest dengan mana hash dari konten dokumen ditandatangani. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Mendapatkan nama dari kurva eliptik yang digunakan oleh ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Mendapatkan ukuran kunci kriptografi yang digunakan oleh algoritma tanda tangan. |

### Lihat Juga

* kelas [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)