---
title: "الفئة OptimizedMemoryStream"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.OptimizedMemoryStream. تُعرّف MemoryStream يمكنه احتواء سعة قياسية أكبر"
type: docs
weight: 8130
url: /ar/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

يحدد MemoryStream يمكنه احتواء سعة قياسية أكبر.

```csharp
public class OptimizedMemoryStream : Stream
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | يُنشئ مثلاً جديداً من الفئة `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | يُنشئ مثلاً جديداً من الفئة `OptimizedMemoryStream` بناءً على مصفوفة البايت المحددة. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | يُنشئ مثلاً جديداً من الفئة `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | يُنشئ مثلاً جديداً من الفئة `OptimizedMemoryStream` بناءً على مصفوفة البايت المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | يحصل أو يعيّن حجم المخازن المؤقتة الأساسية. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التيار الحالي يدعم القراءة. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التيار الحالي يدعم التموقع. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التيار الحالي يدعم الكتابة. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحرير المخازن المؤقتة الأساسية عند التخلص. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | عند تجاوزها في فئة مشتقة، يحصل على الطول بالبايت للتيار. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | عند تجاوزها في فئة مشتقة، يحصل أو يعيّن الموضع داخل التيار الحالي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | الدالة المتجاوزة. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | عند تجاوزها في فئة مشتقة، تقرأ تسلسلاً من البايتات من التيار الحالي وتقدّم الموضع داخل التيار بعدد البايتات المقروءة. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | تقرا بايتاً من التيار وتقدّم الموضع داخل التيار بايت واحد، أو تُعيد -1 إذا كان عند نهاية التيار. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | عند تجاوزها في فئة مشتقة، تعيّن الموضع داخل التيار الحالي. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | عند تجاوزها في فئة مشتقة، تعيّن طول التيار الحالي. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | يقوم بتحويل الدفق الحالي إلى مصفوفة بايت. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | عند تجاوزها في فئة مشتقة، تقوم بكتابة تسلسل من البايتات إلى الدفق الحالي وتقدم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | تكتب بايتًا إلى الموضع الحالي في الدفق وتقدم الموضع داخل الدفق بايتًا واحدًا. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | تكتب إلى الدفق المحدد. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | قيمة حجم المخزن المؤقت الافتراضي بالبايت. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


