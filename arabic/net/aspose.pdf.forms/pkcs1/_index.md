---
title: "فئة PKCS1"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Forms.PKCS1. تمثل كائن التوقيع وفق معيار PKCS1. يتم استخدام خوارزمية تشفير RSA وطريقة تجزئة SHA1 للتوقيع."
type: docs
weight: 5290
url: /ar/net/aspose.pdf.forms/pkcs1/
---
## PKCS1 class

يمثل كائن التوقيع المتعلق بمعيار PKCS#1. يتم استخدام خوارزمية تشفير RSA وطريقة التجزئة SHA-1 للتوقيع.

```csharp
public sealed class PKCS1 : Signature
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `PKCS1`. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | يُنشئ مثيلًا جديدًا من الفئة `PKCS1`. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | يُنشئ مثيلًا جديدًا من الفئة `PKCS1`. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | يُنشئ مثيلًا جديدًا من الفئة `PKCS1`. |

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


