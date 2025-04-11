---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delegasi untuk menandatangani hash dokumen secara kustom
type: docs
weight: 5260
url: /id/net/aspose.pdf.forms/signhash/
---
## Delegasi SignHash

Delegasi untuk menandatangani hash dokumen secara kustom.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hash | Byte[] | Hash input dari dokumen. |
| digestHashAlgorithm | DigestHashAlgorithm | Algoritma digest yang digunakan untuk membuat hash. Nilai ini tidak akan pernah sama dengan Auto. |

### Nilai Kembali

Tanda tangan output.

## Catatan

Perhatikan bahwa apakah tanda tangan digital terpisah atau tidak, argumen hash akan selalu menjadi hash akhir yang akan ditandatangani.

### Lihat Juga

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)