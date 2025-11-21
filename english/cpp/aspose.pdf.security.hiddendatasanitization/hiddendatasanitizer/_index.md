---
title: Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer class
linktitle: HiddenDataSanitizer
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizer class. Represents a class for sanitizing hidden data in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizer/
---
## HiddenDataSanitizer class


Represents a class for sanitizing hidden data.

```cpp
class HiddenDataSanitizer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [HiddenDataSanitizer](./hiddendatasanitizer/)(System::SharedPtr\<HiddenDataSanitizationOptions\>) | Provides functionality to sanitize hidden data from a PDF document, ensuring that sensitive or unnecessary information such as metadata, annotations, JavaScripts, or private content is removed or transformed. |
| [Sanitize](./sanitize/)(System::SharedPtr\<Document\>) | Sanitizes a given PDF document by removing or transforming hidden data. |
| static [SanitizeAllToImages](./sanitizealltoimages/)(System::SharedPtr\<Document\>, int32_t) | Replaces page content with images and removes other hidden data. Allows you to remove hidden text with a background color, as well as text hidden under images. Also completely removes all interactive elements. The document is converted to images as is, and then cleared of any remaining hidden data. If you need to clear first and then convert, use the main class method. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
