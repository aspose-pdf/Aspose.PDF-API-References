---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.OptimizedMemoryStream. تعرف على MemoryStream التي يمكن أن تحتوي على سعة قياسية أكبر
type: docs
weight: 7990
url: /ar/net/aspose.pdf/optimizedmemorystream/
---
## فئة OptimizedMemoryStream

تعرف على MemoryStream التي يمكن أن تحتوي على سعة قياسية أكبر

```csharp
public class OptimizedMemoryStream : Stream
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | يقوم بتهيئة مثيل جديد من فئة `OptimizedMemoryStream` استنادًا إلى مصفوفة البايت المحددة. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | يقوم بتهيئة مثيل جديد من فئة `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | يقوم بتهيئة مثيل جديد من فئة `OptimizedMemoryStream` استنادًا إلى مصفوفة البايت المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | يحصل أو يحدد حجم المخازن الأساسية. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كانت الدفق الحالي يدعم القراءة. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كانت الدفق الحالي يدعم البحث. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كانت الدفق الحالي يدعم الكتابة. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان يجب تحرير المخازن الأساسية عند التخلص. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على الطول بالبايت للدفق. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | عند تجاوزها في فئة مشتقة، يحصل أو يحدد الموضع داخل الدفق الحالي. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | الوظيفة التي تم تجاوزها. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | عند تجاوزها في فئة مشتقة، تقرأ تسلسل من البايتات من الدفق الحالي وتقدم الموضع داخل الدفق بعدد البايتات المقروءة. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | يقرأ بايتًا من الدفق ويقدم الموضع داخل الدفق ببايت واحد، أو يرجع -1 إذا كان في نهاية الدفق. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | عند تجاوزها في فئة مشتقة، تحدد الموضع داخل الدفق الحالي. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | عند تجاوزها في فئة مشتقة، تحدد طول الدفق الحالي. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | يحول الدفق الحالي إلى مصفوفة بايت. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | عند تجاوزها في فئة مشتقة، تكتب تسلسل من البايتات إلى الدفق الحالي وتقدم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق ببايت واحد. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | يكتب إلى الدفق المحدد. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | قيمة حجم المخزن الافتراضي بالبايت. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)