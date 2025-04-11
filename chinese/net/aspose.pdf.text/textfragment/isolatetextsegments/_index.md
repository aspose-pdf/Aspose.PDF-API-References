---
title: TextFragment.IsolateTextSegments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 方法。获取表示 TextFragment 文本指定部分的 TextSegments
type: docs
weight: 200
url: /zh/net/aspose.pdf.text/textfragment/isolatetextsegments/
---
## TextFragment.IsolateTextSegments 方法

获取 [`TextSegment`](../../textsegment/)(s) 表示 [`TextFragment`](../) 文本的指定部分。

```csharp
public TextSegmentCollection IsolateTextSegments(int startIndex, int length)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | Int32 | 文本中新的 [`TextSegment`](../../textsegment/)(s) 将开始的位置。 |
| length | Int32 | 将被隔离为 [`TextSegment`](../../textsegment/)(s) 的文本长度。 |

### 返回值

[`TextSegmentCollection`](../../textsegmentcollection/) 包含表示从指定位置开始并具有指定长度的文本子字符串的文本段。

### 另请参阅

* 类 [TextSegmentCollection](../../textsegmentcollection/)
* 类 [TextFragment](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)