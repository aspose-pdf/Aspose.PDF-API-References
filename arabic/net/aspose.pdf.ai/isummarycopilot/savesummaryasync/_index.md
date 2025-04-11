---
title: ISummaryCopilot.SaveSummaryAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة ISummaryCopilot. تحفظ الملخص بشكل غير متزامن في ملف PDF
type: docs
weight: 30
url: /ar/net/aspose.pdf.ai/isummarycopilot/savesummaryasync/
---
## SaveSummaryAsync(string, CancellationToken?) {#savesummaryasync_1}

تحفظ الملخص بشكل غير متزامن في ملف PDF.

```csharp
public Task SaveSummaryAsync(string outputFileName, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | اسم ملف الإخراج لحفظ الملخص. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة.

### See Also

* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveSummaryAsync(string, SaveFormat, CancellationToken?) {#savesummaryasync}

تحفظ الملخص بشكل غير متزامن في ملف بالتنسيق المحدد.

```csharp
public Task SaveSummaryAsync(string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | اسم ملف الإخراج لحفظ الملخص. |
| saveFormat | SaveFormat | التنسيق الذي سيتم حفظ الملخص به. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)