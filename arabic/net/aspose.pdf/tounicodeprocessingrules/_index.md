---
title: "فئة ToUnicodeProcessingRules"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.ToUnicodeProcessingRules. تصف هذه الفئة القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight: لا يمكن تعيين النص إلى Unicode"
type: docs
weight: 11300
url: /ar/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

هذه الفئة تصف القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight "لا يمكن تعيين النص إلى Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | تهيئ نسخة جديدة من الفئة `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | يُنشئ مثيلًا جديدًا من الفئة `ToUnicodeProcessingRules` مع الخيار المحدد لإزالة المسافات من أسماء CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | يُنشئ مثيلًا جديدًا من الفئة `ToUnicodeProcessingRules` مع خيارات محددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | بعض الخطوط لا توفر معلومات عن اليونيكود لبعض رموز النص. هذا النقص في المعلومات يسبب خطأ "Text cannot be mapped to Unicode". استخدم هذه العلامة لتعيين الرموز غير المرتبطة إلى "space" (الرمز 32) في اليونيكود. |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | بعض الخطوط لديها خرائط رموز ToUnicode تحتوي على مسافات في الأسماء. هذه المسافات قد تتسبب في أخطاء عند تعيين النص إلى اليونيكود. هذه العلامة تُصِر على إزالة المسافات من أسماء خرائط رموز ToUnicode. القيمة الافتراضية false. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


