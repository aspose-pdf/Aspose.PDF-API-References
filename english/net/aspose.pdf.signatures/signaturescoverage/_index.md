---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage enum. Represents enum for the level of coverage provided by digital signatures in a document
type: docs
weight: 10290
url: /net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

Represents enum for the level of coverage provided by digital signatures in a document.

```csharp
public enum SignaturesCoverage
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Undefined | `0` | Indicates that the state of digital signatures' coverage in the document is undefined. This value is typically used when one or more signatures in the document are compromised or cannot be verified, preventing a definitive assessment of the document's signature coverage. |
| EntirelySigned | `1` | Indicates that the document is entirely covered by digital signatures. This value signifies that all required portions of the document have been signed and no signatures are compromised. |
| PartiallySigned | `2` | Indicates that the document is partially signed, meaning that some, but not all, of its content is covered by digital signatures. This value is used when certain parts of the document remain unsigned or are excluded from the signature coverage. |

### See Also

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


