---
title: "Page.IsBlank"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Page. تحصل على العلامة التي تشير ما إذا كانت الصفحة فارغة أم لا"
type: docs
weight: 490
url: /ar/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

يحصل على العلامة التي تشير ما إذا كانت الصفحة فارغة أم لا.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fillThresholdFactor | Double | قيمة عتبة التعبئة التي تدير حساسية الكشف. يجب أن تكون في النطاق [0..1). |

### قيمة الإرجاع

صحيح - إذا كانت الصفحة فارغة؛ وإلا، خطأ.

## ملاحظات

لتحديد ما إذا كانت الصفحة فارغة أم لا، يتم حساب نسبة المساحة المملوءة إلى إجمالي مساحة الصفحة. تُقارن هذه النسبة بمعامل fillThresholdFactor وإذا كانت أقل، تُعتبر الصفحة فارغة.

### انظر أيضًا

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


