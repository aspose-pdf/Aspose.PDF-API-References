---
title: "الفئة Signature"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Forms.Signature. فئة تجريدية تمثل كائن التوقيع في مستند pdf. التوقيعات هي حقول ذات قيم كائنات توقيع تحتوي في النهاية على بيانات تُستخدم للتحقق من صحة المستند."
type: docs
weight: 5390
url: /ar/net/aspose.pdf.forms/signature/
---
## Signature class

فئة مجردة تمثل كائن التوقيع في مستند pdf. التوقيعات هي حقول ذات قيم كائنات توقيع، وتحتوي الأخيرة على بيانات تُستخدم للتحقق من صحة المستند.

```csharp
public abstract class Signature
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Signature](signature/#constructor)() | يُهيئ نسخة جديدة من الفئة `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | يُهيئ نسخة جديدة من الفئة `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | يُهيئ نسخة جديدة من الفئة `Signature`. |

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
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_2)(X509Certificate2, ValidationOptions, out ValidationResult) | تحقق من صحة المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا وإلا false. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية. |

### انظر أيضًا

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


