---
title: "الفئة PKCS7Detached"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Forms.PKCS7Detached. تمثل كائن PKCS7 المتوافق مع مواصفة PKCS7 في RFC 2315 للإنترنت PKCS 7 Cryptographic Message Syntax الإصدار 1.5. يتم دمج ملخص الرسالة الموقعة الأصلي على نطاق بايتات المستند كحقل PKCS7 SignedData العادي. لا يتم تضمين أي بيانات في حقل PKCS7 SignedData."
type: docs
weight: 5310
url: /ar/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: صيغ الرسائل المشفرة، الإصدار 1.5. يتم دمج تجزئة الرسالة الموقعة الأصلية على نطاق بايتات المستند كحقل PKCS#7 SignedData العادي. لا يتم تضمين أي بيانات في حقل PKCS#7 SignedData.

```csharp
public sealed class PKCS7Detached : Signature
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | يُهيئ نسخة جديدة من الفئة `PKCS7Detached`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | اسم الشخص أو الجهة التي توقع المستند. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | يحصل أو يعيّن خيارًا يحدد ما إذا كان يجب تجنب تقدير طول التوقيع. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت البداية، الطول بالبايت) التي تصف النطاق البايت الدقيق لحساب التجزئة. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | معلومات يقدمها الموقع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع، مثل رقم هاتف. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | يحصل أو يعيّن المظهر المخصص. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | المندوب لتوقيع مخصص لتجزئة المستند. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | وقت التوقيع. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | يحصل أو يعيّن الطول الافتراضي لبيانات التوقيع بالبايت. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | يحصل/يعيّن إعدادات ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | سبب التوقيع، مثل (I agree, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، يكون لحقل التوقيع تنسيق مظهر محدد مسبقًا (سلاسل تمثيلية): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- حيث {X} هو عنصر نائبي لقيمة X. يمكن أيضًا أن يحتوي التوقيع على صورة، وفي هذه الحالة تُوضع السلاسل المذكورة فوق الصورة. ShowProperties صحيح بشكل افتراضي. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | يحصل/يعيّن إعدادات الطابع الزمني. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | يحصل/يعيّن علامة التحقق من ltv. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | يسترجع معلومات حول خوارزمية التوقيع المستخدمة في التوقيع. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية. |

### انظر أيضًا

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


