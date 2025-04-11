---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Properti Signature. Mendapatkan dan mengatur opsi yang berarti apakah untuk menghindari memperkirakan panjang tanda tangan
type: docs
weight: 30
url: /id/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Properti Signature.AvoidEstimatingSignatureLength

Mendapatkan dan mengatur opsi yang berarti apakah untuk menghindari memperkirakan panjang tanda tangan.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Keterangan

Menghindari untuk memperkirakan panjang tanda tangan sebelum mendokumentasikan tanda tangan. Digunakan untuk menandatangani melalui [`CustomSignHash`](../customsignhash/) dan melalui [`ExternalSignature`](../../externalsignature/). Jika [`CustomSignHash`](../customsignhash/) mengembalikan tanda tangan yang lebih panjang dari [`DefaultSignatureLength`](../defaultsignaturelength/), maka [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) akan dilemparkan. Nilai default adalah `false`.

### Lihat Juga

* kelas [Signature](../)
* ruang nama [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)