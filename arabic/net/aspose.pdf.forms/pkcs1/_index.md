---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS1 class. يمثل كائن التوقيع وفقًا لمعيار PKCS1. يتم استخدام خوارزمية تشفير RSA وطريقة تجزئة SHA1 للتوقيع
type: docs
weight: 5170
url: /ar/net/aspose.pdf.forms/pkcs1/
---
## PKCS1 class

يمثل كائن التوقيع وفقًا لمعيار PKCS#1. يتم استخدام خوارزمية تشفير RSA وطريقة تجزئة SHA-1 للتوقيع.

```csharp
public sealed class PKCS1 : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `PKCS1`. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | يقوم بتهيئة مثيل جديد من فئة `PKCS1`. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | يقوم بتهيئة مثيل جديد من فئة `PKCS1`. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | يقوم بتهيئة مثيل جديد من فئة `PKCS1`. |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | اسم الشخص أو السلطة التي تقوم بتوقيع الوثيقة. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | يحصل على خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | مصفوفة من أزواج من الأعداد الصحيحة (إزاحة البايت الابتدائية، الطول بالبايت) التي تصف بالضبط نطاق البايت لحساب التجزئة. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع للتحقق من التوقيع، مثل رقم الهاتف. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | يحصل على/يحدد المظهر المخصص. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | المفوض لتوقيع تجزئة الوثيقة بشكل مخصص. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | وقت التوقيع. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | يحصل على أو يحدد الطول الافتراضي لبيانات التوقيع بالبايت. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | يحصل على/يحدد إعدادات ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | السبب وراء التوقيع، مثل (أنا أوافق، Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | يجبر على عرض/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، فإن حقل التوقيع له تنسيق مسبق التعريف للمظهر (سلاسل لتمثيل): ------------------------------------------- تم التوقيع رقميًا بواسطة {موضوع الشهادة} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو عنصر نائب لقيمة X. أيضًا، يمكن أن يحتوي التوقيع على صورة، في هذه الحالة يتم وضع السلاسل المدرجة فوق الصورة. ShowProperties صحيح بشكل افتراضي. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | يحصل على/يحدد إعدادات الطابع الزمني. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | يحصل على/يحدد علامة التحقق من ltv. |

## Methods

| Name | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | يسترجع معلومات حول خوارزمية التوقيع المستخدمة في التوقيع. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | يتحقق من الوثيقة بالنسبة لهذا التوقيع ويعيد صحيحًا إذا كانت الوثيقة صالحة أو خلاف ذلك خطأ. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | يتحقق من الوثيقة بالنسبة لهذا التوقيع ويعيد صحيحًا إذا كانت الوثيقة صالحة أو خلاف ذلك خطأ. |

### See Also

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)