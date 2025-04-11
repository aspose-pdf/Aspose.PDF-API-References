---
title: TextFragment.IsolateTextSegments
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextFragment. تحصل على TextSegments تمثل جزءًا محددًا من نص TextFragment
type: docs
weight: 200
url: /ar/net/aspose.pdf.text/textfragment/isolatetextsegments/
---
## طريقة TextFragment.IsolateTextSegments

تحصل على [`TextSegment`](../../textsegment/)(s) تمثل جزءًا محددًا من نص [`TextFragment`](../).

```csharp
public TextSegmentCollection IsolateTextSegments(int startIndex, int length)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | Int32 | الموضع في النص الذي ستبدأ منه [`TextSegment`](../../textsegment/)(s) الجديدة. |
| length | Int32 | طول النص الذي سيتم عزله في [`TextSegment`](../../textsegment/)(s). |

### قيمة الإرجاع

[`TextSegmentCollection`](../../textsegmentcollection/) تحتوي على مقاطع نصية تمثل جزء النص الذي يبدأ من موضع محدد وله طول محدد.

### انظر أيضًا

* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)