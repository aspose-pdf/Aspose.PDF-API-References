---
title: TextFragment.IsolateTextSegments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment メソッド。指定された部分の TextFragment テキストを表す TextSegments を取得します
type: docs
weight: 200
url: /ja/net/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment.IsolateTextSegments メソッド

指定された部分の [`TextFragment`](../) テキストを表す [`TextSegment`](../../textsegment/) を取得します。

```csharp
public TextSegmentCollection IsolateTextSegments(int startIndex, int length)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startIndex | Int32 | 新しい [`TextSegment`](../../textsegment/) が開始するテキスト内の位置。 |
| length | Int32 | [`TextSegment`](../../textsegment/) に分離されるテキストの長さ。 |

### 戻り値

指定された位置から始まり、指定された長さを持つテキストの部分文字列を表すテキストセグメントを含む [`TextSegmentCollection`](../../textsegmentcollection/) 。

### 参照

* クラス [TextSegmentCollection](../../textsegmentcollection/)
* クラス [TextFragment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)