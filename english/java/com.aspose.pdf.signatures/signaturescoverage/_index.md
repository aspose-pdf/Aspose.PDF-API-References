---
title: SignaturesCoverage
linktitle: SignaturesCoverage
second_title: Aspose.PDF for Java API Reference
description: Represents enum for the level of coverage provided by digital signatures in a document.
type: docs
weight: 40
url: /java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Represents enum for the level of coverage provided by digital signatures in a document.

## Fields

| Field | Description |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Indicates that the document is entirely covered by digital signatures. This value signifies that all required portions of the document have been signed and no signatures are compromised. |
| [PartiallySigned](#PartiallySigned) | Indicates that the document is partially signed, meaning that some, but not all, of its content is covered by digital signatures. This value is used when certain parts of the document remain unsigned or are excluded from the signature coverage. |
| [Undefined](#Undefined) | Indicates that the state of digital signatures' coverage in the document is undefined. This value is typically used when one or more signatures in the document are compromised or cannot be verified, preventing a definitive assessment of the document's signature coverage. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Indicates that the document is entirely covered by digital signatures. This value signifies that all required portions of the document have been signed and no signatures are compromised.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Indicates that the document is partially signed, meaning that some, but not all, of its content is covered by digital signatures. This value is used when certain parts of the document remain unsigned or are excluded from the signature coverage.

### Undefined {#Undefined}
```
public static final int Undefined
```

Indicates that the state of digital signatures' coverage in the document is undefined. This value is typically used when one or more signatures in the document are compromised or cannot be verified, preventing a definitive assessment of the document's signature coverage.
