---
title: "CompromiseCheckResult Class"
linktitle: "CompromiseCheckResult"
articleTitle: "CompromiseCheckResult"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Signatures.CompromiseCheckResult class. Represents a class for checking document digital signatures for compromise."
type: docs
weight: 20
url: "/net/aspose.pdf.signatures/compromisecheckresult/"
keywords: "CompromiseCheckResult, Aspose.Pdf.Signatures, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CompromiseCheckResult class

Represents a class for checking document digital signatures for compromise.

```csharp
public sealed class CompromiseCheckResult
```

## Properties

| Name | Description |
| --- | --- |
| [HasCompromisedSignatures](./hascompromisedsignatures/) { get; } | Indicates whether there are any compromised digital signatures in the document. Returns true if at least one signature is compromised; otherwise, false. |
| [SignaturesCoverage](./signaturescoverage/) { get; } | Gets the coverage state of digital signatures in a document. If it is equal to `Undefined`, then one of the signatures is compromised. |

## Fields

| Name | Description |
| --- | --- |
| readonly [CompromisedSignatures](./compromisedsignatures/) | Gets a collection of digital signatures that have been identified as compromised. This property contains the list of all compromised signatures detected in the document. |

### See Also

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)

