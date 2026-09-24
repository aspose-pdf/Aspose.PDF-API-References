---
title: "TimestampAlgorithmInfo Class"
linktitle: "TimestampAlgorithmInfo"
articleTitle: "TimestampAlgorithmInfo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Security.TimestampAlgorithmInfo class. Represents a class for the information about the timestamp signature algorithm."
type: docs
weight: 130
url: "/net/aspose.pdf.security/timestampalgorithminfo/"
keywords: "TimestampAlgorithmInfo, Aspose.Pdf.Security, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TimestampAlgorithmInfo class

Represents a class for the information about the timestamp signature algorithm.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Gets the name of the signature field. *(Inherited from SignatureAlgorithmInfo)* |

## Methods

| Name | Description |
| --- | --- |
| [FillText](./filltext/) |  |
| [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/) | Converts the current information object to its string representation. *(Inherited from SignatureAlgorithmInfo)* |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Gets the type of the signature algorithm used for signing the PDF document. *(Inherited from SignatureAlgorithmInfo)* |
| readonly [ContentHashAlgorithm](./contenthashalgorithm/) | Gets the hash algorithm that hashed the content of the document and then signed it using `DigestHashAlgorithm`. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Gets the cryptographic standard used for signing the PDF document. *(Inherited from SignatureAlgorithmInfo)* |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Gets the digest hash algorithm used for the signature. *(Inherited from SignatureAlgorithmInfo)* |

### See Also

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)

