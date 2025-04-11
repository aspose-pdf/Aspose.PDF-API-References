---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: طريقة DocumentDevice. يمثل كل جهاز عملية معينة على المستند، على سبيل المثال، يمكننا تحويل مستند PDF إلى تنسيق آخر
type: docs
weight: 10
url: /ar/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

يمثل كل جهاز عملية معينة على المستند، على سبيل المثال، يمكننا تحويل مستند PDF إلى تنسيق آخر.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | المستند الذي سيتم معالجته. |
| fromPage | Int32 | يحدد الصفحة التي سيتم بدء المعالجة منها. |
| toPage | Int32 | يحدد آخر صفحة سيتم معالجتها. |
| output | Stream | يحدد التدفق الذي يتم تخزين نتائج المعالجة فيه. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

يعالج المستند بالكامل ويخزن النتائج في التدفق.

```csharp
public void Process(Document document, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | المستند الذي سيتم معالجته. |
| output | Stream | يحدد التدفق الذي يتم تخزين نتائج المعالجة فيه. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

يعالج المستند بالكامل ويخزن النتائج في ملف.

```csharp
public void Process(Document document, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | المستند الذي سيتم معالجته. |
| outputFileName | String | يحدد الملف الذي يتم تخزين نتائج المعالجة فيه. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

يعالج صفحات معينة من المستند ويخزن النتائج في ملف.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Document | المستند الذي سيتم معالجته. |
| fromPage | Int32 | الصفحة الأولى لبدء المعالجة. |
| toPage | Int32 | آخر صفحة من المعالجة. |
| outputFileName | String | يحدد الملف الذي يتم تخزين نتائج المعالجة فيه. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)