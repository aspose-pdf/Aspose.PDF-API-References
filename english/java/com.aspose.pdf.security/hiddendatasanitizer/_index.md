---
title: HiddenDataSanitizer
linktitle: HiddenDataSanitizer
second_title: Aspose.PDF for Java API Reference
description: Represents a class for sanitizing hidden data.
type: docs
weight: 20
url: /java/com.aspose.pdf.security/hiddendatasanitizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizer

```
public final class HiddenDataSanitizer extends Object
```

Represents a class for sanitizing hidden data.

## Constructors

| Constructor | Description |
| --- | --- |
| [HiddenDataSanitizer](#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-) | Provides functionality to sanitize hidden data from a PDF document, ensuring that sensitive or unnecessary information such as metadata, annotations, JavaScripts, or private content is removed or transformed. |

## Methods

| Method | Description |
| --- | --- |
| [sanitize](#sanitize-com.aspose.pdf.Document-) | Sanitizes a given PDF document by removing or transforming hidden data. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-) | Replaces page content with images and removes other hidden data. Allows you to remove hidden text with a background color, as well as text hidden under images. Also, completely removes all interactive elements. The document is converted to images as is, and then cleared of any remaining hidden data. If you need to clear first and then convert, use the main class method. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-int-) | Replaces page content with images and removes other hidden data. Allows you to remove hidden text with a background color, as well as text hidden under images. Also completely removes all interactive elements. The document is converted to images as is, and then cleared of any remaining hidden data. If you need to clear first and then convert, use the main class method. |

### HiddenDataSanitizer {#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-}
Provides functionality to sanitize hidden data from a PDF document, ensuring that sensitive or unnecessary information such as metadata, annotations, JavaScripts, or private content is removed or transformed.

### sanitize {#sanitize-com.aspose.pdf.Document-}
Sanitizes a given PDF document by removing or transforming hidden data.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-}
Replaces page content with images and removes other hidden data. Allows you to remove hidden text with a background color, as well as text hidden under images. Also, completely removes all interactive elements. The document is converted to images as is, and then cleared of any remaining hidden data. If you need to clear first and then convert, use the main class method.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-int-}
Replaces page content with images and removes other hidden data. Allows you to remove hidden text with a background color, as well as text hidden under images. Also completely removes all interactive elements. The document is converted to images as is, and then cleared of any remaining hidden data. If you need to clear first and then convert, use the main class method.
