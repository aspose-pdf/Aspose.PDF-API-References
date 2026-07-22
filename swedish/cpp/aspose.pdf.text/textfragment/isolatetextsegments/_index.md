---
title: "Aspose::Pdf::Text::TextFragment::IsolateTextSegments metod"
linktitle: "IsolateTextSegments"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFragment::IsolateTextSegments metod. Hämtar TextSegment(s) som representerar angiven del av TextFragment‑texten i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment::IsolateTextSegments method


Hämtar [TextSegment](../../textsegment/)(s) som representerar angiven del av [TextFragment](../)-texten.

```cpp
System::SharedPtr<TextSegmentCollection> Aspose::Pdf::Text::TextFragment::IsolateTextSegments(int32_t startIndex, int32_t length)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int32_t | [Position](../../position/) i texten från vilken nya [TextSegment](../../textsegment/)(s) kommer att starta. |
| length | int32_t | Längden på den text som kommer att isoleras till [TextSegment](../../textsegment/)(s). |

### ReturnValue

[TextSegmentCollection](../../textsegmentcollection/) containing text segments representing text substring starting at a specified position and having a specified length.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSegmentCollection](../../textsegmentcollection/)
* Class [TextFragment](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
