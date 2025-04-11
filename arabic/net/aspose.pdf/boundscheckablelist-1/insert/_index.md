---
title: BoundsCheckableList1.Insert
second_title: Aspose.PDF for .NET API Reference
description: طريقة BoundsCheckableList. تُدخل عنصرًا في System.Collections.Generic.List عند الفهرس المحدد
type: docs
weight: 110
url: /ar/net/aspose.pdf/boundscheckablelist-1/insert/
---
## BoundsCheckableList&lt;T&gt;.Insert method

تُدخل عنصرًا في System.Collections.Generic.List عند الفهرس المحدد.

```csharp
public void Insert(int index, T item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | الفهرس الذي يبدأ من الصفر والذي يجب إدخال العنصر فيه. |
| item | T | الكائن الذي سيتم إدخاله. يمكن أن تكون القيمة null لأنواع المرجع. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* أقل من 0. -أو- *index* أكبر من Count. |

### See Also

* class [BoundsCheckableList&lt;T&gt;](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)