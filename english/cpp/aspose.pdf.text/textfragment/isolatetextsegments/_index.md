---
title: Aspose::Pdf::Text::TextFragment::IsolateTextSegments method
linktitle: IsolateTextSegments
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragment::IsolateTextSegments method. Gets TextSegment(s) representing specified part of the TextFragment text in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment::IsolateTextSegments method


Gets [TextSegment](../../textsegment/)(s) representing specified part of the [TextFragment](../) text.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<TextSegmentCollection> Aspose::Pdf::Text::TextFragment::IsolateTextSegments(int32_t startIndex, int32_t length)
```


| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int32_t | [Position](../../position/) in text from which new [TextSegment](../../textsegment/)(s) will start. |
| length | int32_t | Length of the text that will isolated into [TextSegment](../../textsegment/)(s). |

### ReturnValue

[TextSegmentCollection](../../textsegmentcollection/) containing text segments represeting text substring starting at a specifing position and having a specified length.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>startIndex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_position" kindref="compound">Position</ref> in text from which new <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_segment" kindref="compound">TextSegment</ref>(s) will start.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>length</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Length of the text that will isolated into <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_text_segment" kindref="compound">TextSegment</ref>(s).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextSegmentCollection](../../textsegmentcollection/)
* Class [TextFragment](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
