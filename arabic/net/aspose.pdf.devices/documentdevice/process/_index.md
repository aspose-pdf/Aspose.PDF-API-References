---
title: "DocumentDevice.Process"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة DocumentDevice. كل جهاز يمثل عملية ما على المستند، على سبيل المثال يمكننا تحويل مستند pdf إلى تنسيق آخر"
type: docs
weight: 10
url: /ar/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

كل جهاز يمثل عملية معينة على المستند، مثل تحويل مستند pdf إلى تنسيق آخر.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | المستند المراد معالجته. |
| fromPage | Int32 | يحدد الصفحة التي يبدأ منها المعالجة. |
| toPage | Int32 | يحدد آخر صفحة للمعالجة. |
| الإخراج | Stream | يحدد الدفق حيث تُخزن نتائج المعالجة. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

يعالج المستند بالكامل ويحفظ النتائج في تدفق.

```csharp
public void Process(Document document, Stream output)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | المستند المراد معالجته. |
| الإخراج | Stream | يحدد الدفق حيث تُخزن نتائج المعالجة. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

يعالج المستند بالكامل ويحفظ النتائج في ملف.

```csharp
public void Process(Document document, string outputFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | المستند المراد معالجته. |
| outputFileName | String | يحدد الملف حيث تُخزن نتائج المعالجة. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

يعالج صفحات معينة من المستند ويحفظ النتائج في الملف.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| document | Document | المستند المراد معالجته. |
| fromPage | Int32 | الصفحة الأولى لبدء المعالجة. |
| toPage | Int32 | الصفحة الأخيرة للمعالجة. |
| outputFileName | String | يحدد الملف حيث تُخزن نتائج المعالجة. |

### انظر أيضًا

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


