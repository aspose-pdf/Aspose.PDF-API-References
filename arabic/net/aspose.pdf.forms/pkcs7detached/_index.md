---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.PKCS7Detached. تمثل كائن PKCS7 الذي يتوافق مع مواصفات PKCS7 في RFC 2315 على الإنترنت PKCS 7 صيغة الرسالة التشفيرية الإصدار 1.5. يتم تضمين ملخص الرسالة الموقعة الأصلية على نطاق بايت الوثائق كحقل PKCS7 SignedData العادي. لا يجب أن يتم تضمين أي بيانات في حقل PKCS7 SignedData.
type: docs
weight: 5190
url: /ar/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

تمثل كائن PKCS#7 الذي يتوافق مع مواصفات PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغة الرسالة التشفيرية، الإصدار 1.5. يتم تضمين ملخص الرسالة الموقعة الأصلية على نطاق بايت الوثيقة كحقل PKCS#7 SignedData العادي. لا يجب أن يتم تضمين أي بيانات في حقل PKCS#7 SignedData.

```csharp
public sealed class PKCS7Detached : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | يقوم بتهيئة مثيل جديد من فئة `PKCS7Detached`. |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | اسم الشخص أو السلطة التي تقوم بتوقيع الوثيقة. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | يحصل ويحدد خيارًا يعني ما إذا كان يجب تجنب تقدير طول التوقيع. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت الابتدائية، الطول بالبايت) التي يجب أن تصف نطاق البايت الدقيق لحساب الملخص. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع للتحقق من التوقيع، مثل رقم الهاتف. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | يحصل/يحدد المظهر المخصص. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | المفوض لتوقيع تجريبي مخصص لملخص الوثيقة. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | وقت التوقيع. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | يحصل أو يحدد الطول الافتراضي لبيانات التوقيع بالبايت. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | يحصل/يحدد إعدادات ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | سبب التوقيع، مثل (أنا أوافق، Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | يجبر على عرض/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، فإن حقل التوقيع له تنسيق مظهر محدد مسبقًا (سلاسل لتمثيل): ------------------------------------------- تم التوقيع رقميًا بواسطة {موضوع الشهادة} التاريخ: {signature.Date} السبب: {signature.Reason} الموقع: {signature.Location} ------------------------------------------- حيث {X} هو عنصر نائب لقيمة X. يمكن أيضًا أن يحتوي التوقيع على صورة، في هذه الحالة يتم وضع السلاسل المدرجة فوق الصورة. ShowProperties صحيح بشكل افتراضي. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | يحصل/يحدد إعدادات الطابع الزمني. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | يحصل/يحدد علامة التحقق من صحة ltv. |

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