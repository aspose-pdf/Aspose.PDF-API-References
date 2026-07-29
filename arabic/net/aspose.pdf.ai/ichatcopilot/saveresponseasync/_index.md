---
title: "IChatCopilot.SaveResponseAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IChatCopilot. تقوم بحفظ الاستجابة للرسالة المحددة بشكل غير متزامن إلى ملف PDF."
type: docs
weight: 40
url: /ar/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

يحفظ الاستجابة للرسالة المعطاة بشكل غير متزامن إلى ملف PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| رسالة | String | رسالة الإدخال التي تم حفظ الاستجابة لها. |
| outputFileName | String | اسم ملف PDF الناتج لحفظ الاستجابة. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة.

### انظر أيضًا

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

يحفظ الاستجابة للرسالة المعطاة بشكل غير متزامن إلى ملف بالتنسيق المحدد.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| رسالة | String | رسالة الإدخال التي تم حفظ الاستجابة لها. |
| outputFileName | String | اسم الملف الناتج لحفظ الاستجابة. |
| saveFormat | SaveFormat | الصيغة التي سيتم حفظ الاستجابة بها (PDF إذا لم يتم تحديدها). |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة.

### انظر أيضًا

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

يحفظ الاستجابات للقائمة المعطاة من الرسائل بشكل غير متزامن إلى ملف PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| رسائل | List`1 | قائمة رسائل الإدخال التي تم حفظ الاستجابات لها. |
| outputFileName | String | اسم ملف PDF الناتج لحفظ الاستجابات. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة.

### انظر أيضًا

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

يحفظ الاستجابات للقائمة المعطاة من الرسائل بشكل غير متزامن إلى ملف بالتنسيق المحدد.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| رسائل | List`1 | قائمة رسائل الإدخال التي تم حفظ الاستجابات لها. |
| outputFileName | String | اسم الملف الناتج لحفظ الاستجابات. |
| saveFormat | SaveFormat | الصيغة التي سيتم حفظ الاستجابات بها (PDF إذا لم يتم تحديدها). |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة.

### انظر أيضًا

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


