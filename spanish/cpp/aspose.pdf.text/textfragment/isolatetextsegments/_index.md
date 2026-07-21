---
title: "Método Aspose::Pdf::Text::TextFragment::IsolateTextSegments"
linktitle: "IsolateTextSegments"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Text::TextFragment::IsolateTextSegments. Obtiene TextSegment(s) que representan la parte especificada del texto del TextFragment en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment::IsolateTextSegments method


Obtiene [TextSegment](../../textsegment/)(s) que representan la parte especificada del texto del [TextFragment](../).

```cpp
System::SharedPtr<TextSegmentCollection> Aspose::Pdf::Text::TextFragment::IsolateTextSegments(int32_t startIndex, int32_t length)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int32_t | [Position](../../position/) en el texto desde donde comenzarán los nuevos [TextSegment](../../textsegment/)(s). |
| length | int32_t | Longitud del texto que se aislará en [TextSegment](../../textsegment/)(s). |

### ReturnValue

[TextSegmentCollection](../../textsegmentcollection/) containing text segments representing text substring starting at a specified position and having a specified length.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextSegmentCollection](../../textsegmentcollection/)
* Class [TextFragment](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
