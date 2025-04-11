---
title: Class KeyedSignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Security.KeyedSignatureAlgorithmInfo. Mewakili kelas untuk informasi tentang algoritma tanda tangan yang dikunci
type: docs
weight: 9980
url: /id/net/aspose.pdf.security/keyedsignaturealgorithminfo/
---
## Kelas KeyedSignatureAlgorithmInfo

Mewakili kelas untuk informasi tentang algoritma tanda tangan yang dikunci.

```csharp
public abstract class KeyedSignatureAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Mendapatkan ukuran kunci kriptografi yang digunakan oleh algoritma tanda tangan. |

### Lihat Juga

* kelas [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)