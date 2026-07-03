---
title: UnsignedContentAbsorber.Result
second_title: Aspose.PDF for Java API Reference
description: Encapsulates the result of an operation attempting to extract unsigned content from a PDF document. This class provides information about the success of the operation, details of.
type: docs
weight: 40
url: /java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Encapsulates the result of an operation attempting to extract unsigned content from a PDF document. This class provides information about the success of the operation, details of the unsigned content, a message describing the outcome, and the coverage status of the document's signatures.

## Methods

| Method | Description |
| --- | --- |
| [getCoverage](#getCoverage--) | Gets a value indicating the extent to which the document is covered by valid digital signatures. |
| [getMessage](#getMessage--) | Gets a message describing the outcome of the operation. |
| [getSuccess](#getSuccess--) | Gets a value indicating whether the operation to retrieve unsigned content from the document was successful. |
| [getUnsignedContent](#getUnsignedContent--) | Gets an unsigned content. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Gets a value indicating the extent to which the document is covered by valid digital signatures.

**Returns:**
a value indicating the extent to which the document is covered by valid digital signatures.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Gets a message describing the outcome of the operation.

**Returns:**
a message describing the outcome of the operation.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Gets a value indicating whether the operation to retrieve unsigned content from the document was successful.

**Returns:**
a value indicating whether the operation to retrieve unsigned content from the document was successful.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Gets an unsigned content.

**Returns:**
an unsigned content.
