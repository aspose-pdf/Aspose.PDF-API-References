---
title: "التعداد ValidationMethod"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.Security.ValidationMethod. يمثل تعدادًا يحدد الطريقة المستخدمة للتحقق من صحة الشهادة"
type: docs
weight: 10230
url: /ar/net/aspose.pdf.security/validationmethod/
---
## ValidationMethod enumeration

يمثل enum يحدد الطريقة المستخدمة للتحقق من صحة الشهادة.

```csharp
public enum ValidationMethod
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | يحدد تلقائيًا الطريقة المثلى للتحقق من صحة الشهادة. |
| Ocsp | `1` | يستخدم بروتوكول حالة الشهادة عبر الإنترنت (OCSP) للتحقق من صحة الشهادة. OCSP هو بروتوكول يوفر حالة التحقق من الشهادة عن طريق الاستعلام مباشرةً إلى سلطة الشهادة (CA) المصدرة. |
| Crl | `2` | يُصادق على الشهادات باستخدام طريقة قائمة إبطال الشهادات (CRL). |
| All | `3` | يستخدم جميع الطرق المتاحة (OCSP و CRL) للتحقق من صحة الشهادة. |

### انظر أيضًا

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


