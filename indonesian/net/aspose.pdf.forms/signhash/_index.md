---
title: "Delegasi SignHash"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Delegasi untuk menandatangani hash dokumen secara khusus."
type: docs
weight: 5380
url: /id/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Delegasi untuk menandatangani hash dokumen secara khusus.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hash | Byte[] | Hash masukan dari dokumen. |
| digestHashAlgorithm | DigestHashAlgorithm | Algoritma digest yang digunakan untuk membuat hash. Nilainya tidak akan pernah sama dengan Auto. |

### Nilai Kembalian

Tanda tangan keluaran.

## Catatan

Catatan bahwa apakah tanda tangan digital terpisah atau tidak, argumen hash akan selalu menjadi hash akhir yang akan ditandatangani.

### Lihat Juga

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


