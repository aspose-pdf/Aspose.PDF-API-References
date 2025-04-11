---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMethod enum. يمثل تعدادًا محددًا للطريقة المستخدمة للتحقق من الشهادة
type: docs
weight: 10050
url: /ar/net/aspose.pdf.security/validationmethod/
---
## تعداد ValidationMethod

يمثل تعدادًا محددًا للطريقة المستخدمة للتحقق من الشهادة.

```csharp
public enum ValidationMethod
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | يحدد تلقائيًا أفضل طريقة للتحقق من الشهادة. |
| Ocsp | `1` | يستخدم بروتوكول حالة الشهادة عبر الإنترنت (OCSP) للتحقق من الشهادة. OCSP هو بروتوكول يوفر حالة التحقق من الشهادة من خلال الاستعلام مباشرةً من هيئة الشهادات المصدرة (CA). |
| Crl | `2` | يتحقق من الشهادات باستخدام طريقة قائمة إلغاء الشهادات (CRL). |
| All | `3` | يستخدم جميع الطرق المتاحة (OCSP و CRL) للتحقق من الشهادة. |

### انظر أيضًا

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)