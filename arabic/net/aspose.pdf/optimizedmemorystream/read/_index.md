---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: طريقة OptimizedMemoryStream. عند تجاوزها في فئة مشتقة، تقرأ سلسلة من البايتات من الدفق الحالي وتقدم الموضع داخل الدفق بعدد البايتات المقروءة
type: docs
weight: 100
url: /ar/net/aspose.pdf/optimizedmemorystream/read/
---
## طريقة OptimizedMemoryStream.Read

عند تجاوزها في فئة مشتقة، تقرأ سلسلة من البايتات من الدفق الحالي وتقدم الموضع داخل الدفق بعدد البايتات المقروءة.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | Byte[] | مصفوفة من البايتات. عند عودة هذه الطريقة، تحتوي المصفوفة على مصفوفة البايت المحددة بالقيم |
| offset | Int32 | الإزاحة البايتية المعتمدة على الصفر التي تبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| count | Int32 | الحد الأقصى لعدد البايتات التي سيتم قراءتها من الدفق الحالي. |

### قيمة الإرجاع

إجمالي عدد البايتات التي تم قراءتها في المصفوفة. قد يكون هذا أقل من عدد البايتات المطلوبة إذا لم تكن تلك البايتات متاحة حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق.

### انظر أيضًا

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)