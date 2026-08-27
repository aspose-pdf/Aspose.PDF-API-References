---
title: "OptimizedMemoryStream.Read"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OptimizedMemoryStream. عند تجاوزها في فئة مشتقة تقرأ تسلسل من البايتات من الدفق الحالي وتقدم الموضع داخل الدفق بعدد البايتات المقروءة"
type: docs
weight: 100
url: /ar/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

عند تجاوزها في فئة مشتقة، تقرأ تسلسلاً من البايتات من التيار الحالي وتقدّم الموضع داخل التيار بعدد البايتات المقروءة.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| buffer | Byte[] | مصفوفة من البايتات. عند إرجاع هذه الطريقة، يحتوي الـ buffer على مصفوفة البايتات المحددة بالقيم |
| الإزاحة | Int32 | الإزاحة الصفرية للبايت التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| عدد | Int32 | الحد الأقصى لعدد البايتات التي سيتم قراءتها من الدفق الحالي. |

### قيمة الإرجاع

إجمالي عدد البايتات المقروءة إلى الـ buffer. قد يكون أقل من عدد البايتات المطلوب إذا لم تتوفر تلك البايتات حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق.

### انظر أيضًا

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


