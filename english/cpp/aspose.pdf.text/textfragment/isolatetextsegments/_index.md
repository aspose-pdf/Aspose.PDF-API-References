---
title: Aspose::Pdf::Text::TextFragment::IsolateTextSegments method
linktitle: IsolateTextSegments
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragment::IsolateTextSegments method. Gets TextSegment(s) representing specified part of the TextFragment text in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment::IsolateTextSegments method


Gets [TextSegment](../../textsegment/)(s) representing specified part of the [TextFragment](../) text.

```cpp
System::SharedPtr<TextSegmentCollection> Aspose::Pdf::Text::TextFragment::IsolateTextSegments(int32_t startIndex, int32_t length)
```


| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int32_t | [Position](../../position/) in text from which new [TextSegment](../../textsegment/)(s) will start. |
| length | int32_t | Length of the text that will isolated into [TextSegment](../../textsegment/)(s). |

### ReturnValue

[TextSegmentCollection](../../textsegmentcollection/) containing text segments representing text substring starting at a specified position and having a specified length.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSegmentCollection](../../textsegmentcollection/)
* Class [TextFragment](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
