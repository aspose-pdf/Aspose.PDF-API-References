---
title: "SignatureAlgorithmInfo Class"
linktitle: "SignatureAlgorithmInfo"
articleTitle: "SignatureAlgorithmInfo"
second_title: "Aspose.PDF for .NET"
description: "Represents a class for information about a signature algorithm, including its type, cryptographic standard, and digest hash algorithm."
type: docs
weight: 100
url: "/net/aspose.pdf.security/signaturealgorithminfo/"
keywords: "SignatureAlgorithmInfo, Aspose.Pdf.Security, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SignatureAlgorithmInfo class

Represents a class for information about a signature algorithm, including its type,
 cryptographic standard, and digest hash algorithm.

```csharp
public abstract class SignatureAlgorithmInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/#constructor)(*[CryptographicStandard](../../aspose.pdf.security/cryptographicstandard/), [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/), [SignatureAlgorithmType](../../aspose.pdf.security/signaturealgorithmtype/)*) | Creates an instance of [`SignatureAlgorithmInfo`](../../aspose.pdf.security/signaturealgorithminfo/). |

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](./signaturename/) { get; } | Gets the name of the signature field. |

## Methods

| Name | Description |
| --- | --- |
| [FillText](./filltext/) | Fills string builder instance. |
| [ToString](./tostring/) | Converts the current information object to its string representation. |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](./algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. |
| readonly [CryptographicStandard](./cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. |
| readonly [DigestHashAlgorithm](./digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)

