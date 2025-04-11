---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.ExternalSignature. تنشئ توقيع PKCS7 مفصول باستخدام X509Certificate2. تدعم بطاقات USB الذكية بدون مفاتيح خاصة قابلة للتصدير
type: docs
weight: 5040
url: /ar/net/aspose.pdf.forms/externalsignature/
---
## فئة ExternalSignature

تنشئ توقيع PKCS#7 مفصول باستخدام X509Certificate2. تدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير.

```csharp
public class ExternalSignature : Signature
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | تنشئ توقيع PKCS#7 `(مفصول)` باستخدام X509Certificate2. تدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | تنشئ توقيع PKCS#7 باستخدام X509Certificate2 كسلسلة base64. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | تنشئ توقيع PKCS#7 `(مفصول)` باستخدام X509Certificate2 كسلسلة base64. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | تنشئ توقيع PKCS#7 مفصول باستخدام X509Certificate2. تدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | تنشئ توقيع PKCS#7 `(مفصول)` باستخدام X509Certificate2. تدعم بطاقات USB الذكية، الرموز بدون مفاتيح خاصة قابلة للتصدير. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | اسم الشخص أو السلطة التي توقع الوثيقة. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | يحصل على خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت الابتدائية، الطول بالبايت) التي يجب أن تصف النطاق الدقيق للبايت لحساب التجزئة. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع للتحقق من التوقيع، مثل رقم الهاتف. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | يحصل على/يحدد المظهر المخصص. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | المفوض لتوقيع تجزئة الوثيقة بشكل مخصص. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | وقت التوقيع. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | يحصل على أو يحدد الطول الافتراضي لبيانات التوقيع بالبايت. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | يحصل على/يحدد إعدادات ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | سبب التوقيع، مثل (أنا أوافق، Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | يجبر على عرض/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، فإن حقل التوقيع له تنسيق مسبق التعريف للمظهر (سلاسل لتمثيل): ------------------------------------------- تم التوقيع رقميًا بواسطة {موضوع الشهادة} التاريخ: {تاريخ التوقيع} السبب: {سبب التوقيع} الموقع: {موقع التوقيع} ------------------------------------------- حيث {X} هو عنصر نائب لقيمة X. أيضًا يمكن أن يحتوي التوقيع على صورة، في هذه الحالة يتم وضع السلاسل المدرجة فوق الصورة. ShowProperties صحيح بشكل افتراضي. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | يحصل على/يحدد إعدادات الطابع الزمني. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | يحصل على/يحدد علامة التحقق من ltv. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | يسترجع معلومات حول خوارزمية التوقيع المستخدمة في التوقيع. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | تحقق من الوثيقة بالنسبة لهذا التوقيع وأعد true إذا كانت الوثيقة صالحة أو false خلاف ذلك. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | تحقق من الوثيقة بالنسبة لهذا التوقيع وأعد true إذا كانت الوثيقة صالحة أو false خلاف ذلك. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | الشهادة مع المفتاح الخاص. |

### انظر أيضًا

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)