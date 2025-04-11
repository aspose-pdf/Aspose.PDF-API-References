---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin enum. يجب أن يحدد نمط انضمام الخط الشكل الذي سيتم استخدامه في زوايا المسارات التي يتم رسمها
type: docs
weight: 7450
url: /ar/net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

يجب أن يحدد نمط انضمام الخط الشكل الذي سيتم استخدامه في زوايا المسارات التي يتم رسمها.

```csharp
public enum LineJoin
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MiterJoin | `0` | انضمام ميتير. يجب تمديد الحواف الخارجية للخطوط للجزئين حتى تلتقي عند زاوية، كما في إطار الصورة. إذا التقى الجزئين عند زاوية حادة جدًا كما هو محدد بواسطة معلمة حد الميتير (انظر 8.4.3.5، "حد الميتير")، يجب استخدام انضمام مائل بدلاً من ذلك. |
| RoundJoin | `1` | انضمام دائري. سيتم رسم قوس دائرة بقطر يساوي عرض الخط حول النقطة التي يلتقي فيها الجزئين، موصلًا الحواف الخارجية للخطوط للجزئين. يجب ملء هذه الشكل على شكل شريحة فطيرة، مما ينتج زاوية مدورة. |
| BevelJoin | `2` | انضمام مائل. يجب إنهاء الجزئين بغطاء مستقيم (انظر 8.4.3.3، "نمط غطاء الخط") ويجب ملء الشق الناتج خارج نهايات الجزئين مثلثًا. |

### See Also

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)