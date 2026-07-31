---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Signature. Mendapatkan dan mengatur opsi yang menentukan apakah menghindari perkiraan panjang tanda tangan"
type: docs
weight: 30
url: /id/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

Mendapatkan dan mengatur opsi yang berarti apakah menghindari perkiraan panjang tanda tangan.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Catatan

Menghindari perkiraan panjang tanda tangan sebelum dokumen ditandatangani. Digunakan untuk penandatanganan melalui [`CustomSignHash`](../customsignhash/) dan melalui [`ExternalSignature`](../../externalsignature/). Jika [`CustomSignHash`](../customsignhash/) mengembalikan tanda tangan yang lebih panjang daripada [`DefaultSignatureLength`](../defaultsignaturelength/), maka [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) akan dilempar. Nilai default adalah `false`.

### Lihat Juga

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


