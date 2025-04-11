---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: طريقة SignaturesCompromiseDetector. تحقق من التوقيعات الرقمية للمستند من أجل الكشف عن التلاعب
type: docs
weight: 20
url: /ar/net/aspose.pdf/signaturescompromisedetector/check/
---
## طريقة SignaturesCompromiseDetector.Check

تحقق من التوقيعات الرقمية للمستند من أجل الكشف عن التلاعب.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | نتيجة التحقق من المستند. |

### قيمة الإرجاع

صحيح، إذا لم يتم الكشف عن تلاعب في التوقيعات.

## ملاحظات

استخدام هذه الطريقة لمستند لا يحتوي على توقيعات رقمية سيعيد `True`.

### انظر أيضًا

* class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* class [SignaturesCompromiseDetector](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)