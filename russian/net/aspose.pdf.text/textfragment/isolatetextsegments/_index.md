---
title: TextFragment.IsolateTextSegments
second_title: Aspose.PDF for .NET API Reference
description: Метод TextFragment. Получает TextSegments, представляющие указанную часть текста TextFragment
type: docs
weight: 200
url: /ru/net/aspose.pdf.text/textfragment/isolatetextsegments/
---
## Метод TextFragment.IsolateTextSegments

Получает [`TextSegment`](../../textsegment/)(ы), представляющие указанную часть текста [`TextFragment`](../).

```csharp
public TextSegmentCollection IsolateTextSegments(int startIndex, int length)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | Int32 | Позиция в тексте, с которой начнутся новые [`TextSegment`](../../textsegment/)(ы). |
| length | Int32 | Длина текста, который будет изолирован в [`TextSegment`](../../textsegment/)(ы). |

### Возвращаемое значение

[`TextSegmentCollection`](../../textsegmentcollection/) содержащая текстовые сегменты, представляющие подстроку текста, начинающуюся с указанной позиции и имеющую заданную длину.

### См. также

* класс [TextSegmentCollection](../../textsegmentcollection/)
* класс [TextFragment](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)