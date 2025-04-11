---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IChatCopilot. تحفظ الاستجابة للرسالة المعطاة في ملف PDF بشكل غير متزامن
type: docs
weight: 40
url: /ar/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

تحفظ الاستجابة للرسالة المعطاة في ملف PDF بشكل غير متزامن.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | الرسالة المدخلة التي يتم حفظ الاستجابة لها. |
| outputFileName | String | اسم ملف PDF الناتج لحفظ الاستجابة. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

تحفظ الاستجابة للرسالة المعطاة في ملف بالتنسيق المحدد بشكل غير متزامن.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | الرسالة المدخلة التي يتم حفظ الاستجابة لها. |
| outputFileName | String | اسم الملف الناتج لحفظ الاستجابة. |
| saveFormat | SaveFormat | التنسيق الذي سيتم حفظ الاستجابة به (PDF إذا لم يتم تحديده). |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

تحفظ الاستجابات لقائمة الرسائل المعطاة في ملف PDF بشكل غير متزامن.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | قائمة الرسائل المدخلة التي يتم حفظ الاستجابات لها. |
| outputFileName | String | اسم ملف PDF الناتج لحفظ الاستجابات. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

تحفظ الاستجابات لقائمة الرسائل المعطاة في ملف بالتنسيق المحدد بشكل غير متزامن.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | قائمة الرسائل المدخلة التي يتم حفظ الاستجابات لها. |
| outputFileName | String | اسم الملف الناتج لحفظ الاستجابات. |
| saveFormat | SaveFormat | التنسيق الذي سيتم حفظ الاستجابات به (PDF إذا لم يتم تحديده). |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### Return Value

مهمة تمثل العملية غير المتزامنة.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)