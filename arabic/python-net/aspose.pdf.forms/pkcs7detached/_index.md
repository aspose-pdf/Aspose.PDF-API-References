---
title: "PKCS7Detached"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، <br/>            PKCS #7: بنية الرسائل المشفرة، الإصدار 1.5.<br/>            يتم دمج تجزئة الرسالة الموقعة الأصلية لنطاق بايتات المستند كحقل PKCS#7 SignedData العادي. <br/>            لا يتم تضمين أي بيانات في حقل PKCS#7 SignedData."
type: docs
weight: 200
url: /ar/python-net/aspose.pdf.forms/pkcs7detached/
---

## PKCS7Detached class

يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، <br/>            PKCS #7: بنية الرسائل المشفرة، الإصدار 1.5.<br/>            يتم دمج تجزئة الرسالة الموقعة الأصلية لنطاق بايتات المستند كحقل PKCS#7 SignedData العادي. <br/>            لا يتم تضمين أي بيانات في حقل PKCS#7 SignedData.

يعرض نوع PKCS7Detached الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PKCS7Detached(image) | يُنشئ مثيلًا جديدًا من الفئة PKCS7Detached |
| PKCS7Detached() | يُنشئ مثيلًا جديدًا من الفئة [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/). |
| PKCS7Detached(pfx, password) | يُنشئ مثيلًا جديدًا من الفئة PKCS7Detached |
| PKCS7Detached(pfx, password) | يُنشئ مثيلًا جديدًا من الفئة PKCS7Detached |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| custom_appearance | يحصل/يضبط المظهر المخصص. |
| authority | اسم الشخص أو السلطة التي توقع المستند. |
| date | وقت التوقيع. |
| location | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| reason | سبب التوقيع، مثل (I agreeРІР‚В¦). |
| contact_info | المعلومات التي يقدمها الموقع لتمكين المستلم من الاتصال بالموقع <br/>            للتحقق من التوقيع، مثل رقم هاتف. |
| byte_range | مصفوفة من أزواج الأعداد الصحيحة (إزاحة البايت الابتدائية، الطول بالبايت) <br/>             التي تصف النطاق الدقيق للبايت لحساب التجزئة. |
| timestamp_settings | يحصل/يضبط إعدادات الطابع الزمني. |
| ocsp_settings | يحصل/يضبط إعدادات OCSP. |
| use_ltv | يحصل/يضبط علامة التحقق LTV. |
| show_properties | فرض إظهار/إخفاء خصائص التوقيع.<br/>            في حالة كون ShowProperties صحيحًا، يكون لحقل التوقيع تنسيق مظهر محدد مسبقًا (سلاسل تمثيلية):<br/>            -------------------------------------------<br/>            موقّع رقمياً بواسطة {certificate subject}<br/>            التاريخ: {signature.Date}<br/>            السبب: {signature.Reason}<br/>            الموقع: {signature.Location}<br/>            -------------------------------------------<br/>            حيث أن {X} هو عنصر نائب لقيمة X. يمكن أيضًا أن يحتوي التوقيع على صورة، وفي هذه الحالة توضع السلاسل المذكورة فوق الصورة.<br/>            ShowProperties صحيح بشكل افتراضي. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| verify() | تحقق من المستند بالنسبة لهذا التوقيع وأرجع true إذا كان المستند صالحًا <br/>            أو false إذا لم يكن كذلك. |

### انظر أيضًا

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

