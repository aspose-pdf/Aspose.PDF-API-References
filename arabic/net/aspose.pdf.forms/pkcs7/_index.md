---
title: Class PKCS7
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.PKCS7. تمثل كائن PKCS7 الذي يتوافق مع مواصفة PKCS7 في RFC 2315 على الإنترنت PKCS 7 صيغة الرسالة التشفيرية الإصدار 1.5. يتم تضمين تجزئة SHA1 لنطاق بايت الوثائق في حقل PKCS7 SignedData
type: docs
weight: 5180
url: /ar/net/aspose.pdf.forms/pkcs7/
---
## فئة PKCS7

تمثل كائن PKCS#7 الذي يتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغة الرسالة التشفيرية، الإصدار 1.5. يتم تضمين `SHA1 digest` لنطاق بايت الوثيقة في حقل PKCS#7 SignedData.

```csharp
public sealed class PKCS7 : Signature
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PKCS7](pkcs7/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `PKCS7`. |
| [PKCS7](pkcs7/#constructor_1)(Stream, string) | يقوم بتهيئة مثيل جديد من فئة `PKCS7`. |
| [PKCS7](pkcs7/#constructor_2)(string, string) | يقوم بتهيئة مثيل جديد من فئة `PKCS7`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | اسم الشخص أو السلطة التي تقوم بتوقيع الوثيقة. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | يحصل على خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت الابتدائية، الطول بالبايت) التي يجب أن تصف نطاق البايت الدقيق لحساب التجزئة. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | معلومات يقدمها الموقع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع، مثل رقم الهاتف. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | يحصل على/يحدد المظهر المخصص. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | المفوض لتوقيع تجزئة الوثيقة بشكل مخصص. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | وقت التوقيع. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | يحصل على أو يحدد الطول الافتراضي لبيانات التوقيع بالبايت. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | يحصل على/يحدد إعدادات ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | سبب التوقيع، مثل (أنا أوافق، Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | يجبر على عرض/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، فإن حقل التوقيع له تنسيق مسبق التعريف للمظهر (سلاسل لتمثيل): ------------------------------------------- تم التوقيع رقميًا بواسطة {موضوع الشهادة} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو عنصر نائب لقيمة X. أيضًا، يمكن أن يحتوي التوقيع على صورة، في هذه الحالة يتم وضع السلاسل المدرجة فوق الصورة. ShowProperties صحيح بشكل افتراضي. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | يحصل على/يحدد إعدادات الطابع الزمني. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | يحصل على/يحدد علامة التحقق من صحة ltv. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | يسترجع معلومات حول خوارزمية التوقيع المستخدمة في التوقيع. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | يتحقق من الوثيقة بالنسبة لهذا التوقيع ويعيد صحيحًا إذا كانت الوثيقة صالحة أو خلاف ذلك خطأ. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | يتحقق من الوثيقة بالنسبة لهذا التوقيع ويعيد صحيحًا إذا كانت الوثيقة صالحة أو خلاف ذلك خطأ. |

### انظر أيضًا

* فئة [Signature](../signature/)
* مساحة الأسماء [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* التجميع [Aspose.PDF](../../)