---
title: TextFragment.IsolateTextSegments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 메서드. TextFragment 텍스트의 지정된 부분을 나타내는 TextSegments를 가져옵니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment.IsolateTextSegments 메서드

지정된 부분을 나타내는 [`TextSegment`](../../textsegment/)를 가져옵니다.

```csharp
public TextSegmentCollection IsolateTextSegments(int startIndex, int length)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startIndex | Int32 | 새로운 [`TextSegment`](../../textsegment/)가 시작될 텍스트 내 위치입니다. |
| length | Int32 | [`TextSegment`](../../textsegment/)로 분리될 텍스트의 길이입니다. |

### 반환 값

지정된 위치에서 시작하고 지정된 길이를 가진 텍스트 하위 문자열을 나타내는 텍스트 세그먼트를 포함하는 [`TextSegmentCollection`](../../textsegmentcollection/)입니다.

### 참조

* 클래스 [TextSegmentCollection](../../textsegmentcollection/)
* 클래스 [TextFragment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)