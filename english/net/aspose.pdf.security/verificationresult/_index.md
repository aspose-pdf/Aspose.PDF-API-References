---
title: Class VerificationResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.VerificationResult class. Represents the result of verifying a digital signature in a PDF file
type: docs
weight: 10480
url: /net/aspose.pdf.security/verificationresult/
---
## VerificationResult class

Represents the result of verifying a digital signature in a PDF file.

```csharp
public sealed class VerificationResult
```

## Properties

| Name | Description |
| --- | --- |
| [IsCompromised](../../aspose.pdf.security/verificationresult/iscompromised/) { get; } | Indicates whether the digital signature structure is likely compromised. This means a change to bypass signature checking by PDF tools. See [`Message`](./message/) for more details. |
| [Message](../../aspose.pdf.security/verificationresult/message/) { get; } | Gets the message associated with the verification result. The property value provides additional details about the verification outcome, such as error descriptions or success messages. |
| [State](../../aspose.pdf.security/verificationresult/state/) { get; } | Represents the verification state of a digital signature in a PDF file. Indicates whether the signature is valid, invalid, or undefined. |
| [VerificationException](../../aspose.pdf.security/verificationresult/verificationexception/) { get; } | Gets the exception associated with the verification process if presents. This property provides details about errors or issues encountered during the verification of a digital signature in a PDF file. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


