---
title: "الفئة TruncationStrategy"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.TruncationStrategy. تمثل استراتيجية القطع التي تتحكم في كيفية تقصير الخيط قبل التنفيذ."
type: docs
weight: 1330
url: /ar/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

يمثل استراتيجية القطع التي تتحكم في كيفية قطع السلسلة قبل التنفيذ.

```csharp
public class TruncationStrategy
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | يحصل أو يعيّن عدد أحدث الرسائل من الخيط عند إنشاء السياق للتنفيذ. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | يحصل أو يعيّن استراتيجية القطع التي تُستخدم للخيط. القيمة الافتراضية هي auto. إذا تم تعيينها إلى last_messages، سيُقطع الخيط إلى أحدث n رسائل في الخيط. عند تعيينها إلى auto، سيتم حذف الرسائل في وسط الخيط لتناسب طول السياق للنموذج، max_prompt_tokens. |

### انظر أيضًا

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


