---
title: Aspose::Pdf::AutoTaggingSettings class
linktitle: AutoTaggingSettings
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::AutoTaggingSettings class. Provides settings for the auto-tagging functionality in PDF documents in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/autotaggingsettings/
---
## AutoTaggingSettings class


Provides settings for the auto-tagging functionality in PDF documents.

```cpp
class AutoTaggingSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AutoTaggingSettings](./autotaggingsettings/)() |  |
| static [get_Default](./get_default/)() | Gets the default settings for auto-tagging functionality in PDF documents. |
| [get_EnableAutoTagging](./get_enableautotagging/)() const | Gets a value indicating whether the auto-tagging functionality is enabled. |
| [get_HeadingLevels](./get_headinglevels/)() const | Gets the heading levels used for determining the structure of headings in a PDF document. |
| [get_HeadingRecognitionStrategy](./get_headingrecognitionstrategy/)() const | Gets the strategy used for recognizing headings in the document during auto-tagging. |
| [set_EnableAutoTagging](./set_enableautotagging/)(bool) | Sets a value indicating whether the auto-tagging functionality is enabled. |
| [set_HeadingLevels](./set_headinglevels/)(System::SharedPtr\<Aspose::Pdf::HeadingLevels\>) | Sets the heading levels used for determining the structure of headings in a PDF document. |
| [set_HeadingRecognitionStrategy](./set_headingrecognitionstrategy/)(Aspose::Pdf::HeadingRecognitionStrategy) | Sets the strategy used for recognizing headings in the document during auto-tagging. |
## Remarks


The [AutoTaggingSettings](./) class allows configuring options for automatic tagging of PDF content. It includes properties to enable or disable auto-tagging, specify a strategy for heading recognition, and define heading levels based on font sizes. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
