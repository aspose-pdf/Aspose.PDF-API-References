---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: طريقة الترخيص. ترخص المكون
type: docs
weight: 20
url: /ar/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

ترخص المكون.

```csharp
public void SetLicense(string licenseName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| licenseName | String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. المسار الصريح.

2. المجلد الذي يحتوي على تجميع مكون Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الإدخال (بدء التشغيل).

5. مورد مضمن في تجميع استدعاء العميل.

**ملاحظة:** في إطار عمل .NET Compact، يحاول العثور على الترخيص فقط في هذه المواقع:

1. المسار الصريح.

2. مورد مضمن في تجميع استدعاء العميل.

[Java]

2. المجلد الذي يحتوي على ملف JAR لمكون Aspose.

3. المجلد الذي يحتوي على ملف JAR لاستدعاء العميل.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

ترخص المكون.

```csharp
public void SetLicense(Stream stream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من تدفق.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)