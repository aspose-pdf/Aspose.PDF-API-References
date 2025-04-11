---
title: BoundsCheckableList1.Insert
second_title: Aspose.PDF for .NET API Reference
description: طريقة BoundsCheckableList. تُدرج عنصرًا في System.Collections.Generic.List عند الفهرس المحدد
type: docs
weight: 110
url: /ar/net/aspose.pdf.generator/boundscheckablelist-1/insert/
---
## BoundsCheckableList&lt;T&gt;.Insert method

تُدرج عنصرًا في System.Collections.Generic.List عند الفهرس المحدد.

```csharp
public void Insert(int index, T item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | الفهرس الذي يبدأ من الصفر والذي يجب إدراج العنصر فيه. |
| item | T | الكائن الذي سيتم إدراجه. يمكن أن تكون القيمة null لأنواع المرجع. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *index* أقل من 0. -أو- *index* أكبر من Count. |

### See Also

* class [BoundsCheckableList&lt;T&gt;](../)
* namespace [Aspose.Pdf.Generator](../../../aspose.pdf.generator/)
* assembly [Aspose.PDF](../../../)