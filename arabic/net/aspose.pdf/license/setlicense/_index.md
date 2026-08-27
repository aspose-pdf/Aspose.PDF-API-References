---
title: "License.SetLicense"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة License. تقوم بترخيص المكوّن"
type: docs
weight: 40
url: /ar/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licenseName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| licenseName | String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

## ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن Aspose.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (بدء التشغيل).

5. مورد مضمّن في تجميع استدعاء العميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مضمّن في تجميع استدعاء العميل.

[Java]

2. المجلد الذي يحتوي على ملف JAR لمكوّن Aspose.

3. المجلد الذي يحتوي على ملف JAR لاستدعاء العميل.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق يحتوي على الترخيص. |

## ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من تدفق.

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


