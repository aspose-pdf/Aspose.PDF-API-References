---
title: "SignHash Delegate"
linktitle: "SignHash"
articleTitle: "SignHash"
second_title: "Aspose.PDF for .NET API Reference"
description: "Delegate for custom sign the document hash."
type: docs
weight: 330
url: "/net/aspose.pdf.forms/signhash/"
product_version: "26.9.0"
---
## SignHash delegate

Delegate for custom sign the document hash.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Type | Description |
| --- | --- | --- |
| hash | Byte[] | Input hash of the document. |
| digestHashAlgorithm | DigestHashAlgorithm | The digest algorithm used to create the hash. The value will never be equal to <see cref="F:Aspose.Pdf.DigestHashAlgorithm.Auto" />. |

### Return Value

Output signature.

### See Also

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

