---
title: UnsignedContentAbsorber
linktitle: UnsignedContentAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents a class for extracting unsigned content from a PDF file managed by digital signatures.
type: docs
weight: 30
url: /java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Represents a class for extracting unsigned content from a PDF file managed by digital signatures.

## Constructors

| Constructor | Description |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Represents a class used for processing unsigned content. |

## Methods

| Method | Description |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Attempt to retrieve the unsigned content from the associated document. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Represents a class used for processing unsigned content.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Attempt to retrieve the unsigned content from the associated document.

**Returns:**
A {@link UnsignedContentAbsorber.Result} object containing details about the unsigned content, the coverage of digital signatures, the operation's success status, and an informational message.
