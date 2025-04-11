---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IChatCopilot. تحصل بشكل غير متزامن على استجابة للرسالة المعطاة
type: docs
weight: 20
url: /ar/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

تحصل بشكل غير متزامن على استجابة للرسالة المعطاة.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | الرسالة المدخلة التي يتم طلب استجابة لها. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة مع سلسلة الاستجابة.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

تحصل بشكل غير متزامن على استجابة لقائمة الرسائل المعطاة.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | قائمة الرسائل المدخلة التي يتم طلب استجابات لها. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة مع سلسلة الاستجابة.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)