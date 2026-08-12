---
title: "Aspose::Pdf::Text::TextFragment::IsolateTextSegments метод"
linktitle: "IsolateTextSegments"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextFragment::IsolateTextSegments метод. Получает TextSegment(ы), представляющие указанную часть текста TextFragment в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment::IsolateTextSegments method


Получает [TextSegment](../../textsegment/)(ы), представляющие указанную часть текста [TextFragment](../).

```cpp
System::SharedPtr<TextSegmentCollection> Aspose::Pdf::Text::TextFragment::IsolateTextSegments(int32_t startIndex, int32_t length)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int32_t | [Position](../../position/) в тексте, с которой начнётся новый [TextSegment](../../textsegment/)(ы). |
| length | int32_t | Длина текста, который будет изолирован в [TextSegment](../../textsegment/)(ы). |

### ReturnValue

[TextSegmentCollection](../../textsegmentcollection/) containing text segments representing text substring starting at a specified position and having a specified length.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSegmentCollection](../../textsegmentcollection/)
* Class [TextFragment](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
