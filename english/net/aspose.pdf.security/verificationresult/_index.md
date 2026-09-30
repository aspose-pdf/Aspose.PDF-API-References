---
title: "VerificationResult Class"
linktitle: "VerificationResult"
articleTitle: "VerificationResult"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Security.VerificationResult class. Represents the result of verifying a digital signature in a PDF file."
type: docs
weight: 230
url: "/net/aspose.pdf.security/verificationresult/"
keywords: "VerificationResult, Aspose.Pdf.Security, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## VerificationResult class

Represents the result of verifying a digital signature in a PDF file.

```csharp
public sealed class VerificationResult
```

## Properties

| Name | Description |
| --- | --- |
| [IsCompromised](./iscompromised/) { get; } | Indicates whether the digital signature structure is likely compromised. This means a change to bypass signature checking by PDF tools. See `Message` for more details. |
| [Message](./message/) { get; } | Gets the message associated with the verification result. The property value provides additional details about the verification outcome, such as error descriptions or success messages. |
| [State](./state/) { get; } | Represents the verification state of a digital signature in a PDF file. Indicates whether the signature is valid, invalid, or undefined. |
| [VerificationException](./verificationexception/) { get; } | Gets the exception associated with the verification process if presents. This property provides details about errors or issues encountered during the verification of a digital signature in a PDF file. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)

