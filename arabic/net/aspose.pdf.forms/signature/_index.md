---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.Signature. فئة مجردة تمثل كائن التوقيع في مستند PDF. التوقيعات هي حقول تحتوي على قيم كائنات التوقيع، والأخيرة تحتوي على بيانات تُستخدم للتحقق من صحة المستند
type: docs
weight: 5270
url: /ar/net/aspose.pdf.forms/signature/
---
## فئة التوقيع

فئة مجردة تمثل كائن التوقيع في مستند PDF. التوقيعات هي حقول تحتوي على قيم كائنات التوقيع، والأخيرة تحتوي على بيانات تُستخدم للتحقق من صحة المستند.

```csharp
public abstract class Signature
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Signature](signature/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | يقوم بتهيئة مثيل جديد من فئة `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | يقوم بتهيئة مثيل جديد من فئة `Signature`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | اسم الشخص أو السلطة التي تقوم بتوقيع المستند. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | يحصل على خيار يعني ما إذا كان يجب تجنب تقدير طول التوقيع. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت الابتدائية، الطول بالبايت) التي تصف بالضبط نطاق البايت لحساب التجزئة. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | المعلومات المقدمة من الموقّع لتمكين المستلم من الاتصال بالموقّع للتحقق من التوقيع، مثل رقم الهاتف. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | يحصل على/يحدد المظهر المخصص. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | المفوض لتوقيع تجزئة المستند بشكل مخصص. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | وقت التوقيع. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | يحصل على أو يحدد الطول الافتراضي لبيانات التوقيع بالبايت. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | يحصل على/يحدد إعدادات OCSP. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | السبب وراء التوقيع، مثل (أنا أوافق، Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | يجبر على عرض/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، فإن حقل التوقيع له تنسيق مسبق التعريف للمظهر (سلاسل لتمثيل): ------------------------------------------- تم التوقيع رقميًا بواسطة {موضوع الشهادة} التاريخ: {التوقيع.Date} السبب: {التوقيع.Reason} الموقع: {التوقيع.Location} ------------------------------------------- حيث {X} هو عنصر نائب لقيمة X. أيضًا يمكن أن يحتوي التوقيع على صورة، في هذه الحالة يتم وضع السلاسل المدرجة فوق الصورة. ShowProperties صحيح بشكل افتراضي. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | يحصل على/يحدد إعدادات الطابع الزمني. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | يحصل على/يحدد علامة التحقق من صحة LTV. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | يسترجع معلومات حول خوارزمية التوقيع المستخدمة في التوقيع. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | يتحقق من المستند بالنسبة لهذا التوقيع ويعيد صحيحًا إذا كان المستند صالحًا أو خلاف ذلك خطأ. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | يتحقق من المستند بالنسبة لهذا التوقيع ويعيد صحيحًا إذا كان المستند صالحًا أو خلاف ذلك خطأ. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* التجميع [Aspose.PDF](../../)