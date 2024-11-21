---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delegate for custom sign the document hash
type: docs
weight: 3890
url: /net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Delegate for custom sign the document hash.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Type | Description |
| --- | --- | --- |
| hash | Byte[] | Input hash of the document. |
| digestHashAlgorithm | DigestHashAlgorithm | The digest algorithm used to create the hash. The value will never be equal to Auto. |

### Return Value

Output signature.

## Remarks

Note that whether the digital signature is detached or not, the hash argument will always be the final hash to be signed.

### See Also

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


