---
title: Class TruncationStrategy
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.TruncationStrategy. تمثل استراتيجية الاقتطاع التي تتحكم في كيفية اقتطاع الخيط قبل التشغيل
type: docs
weight: 1240
url: /ar/net/aspose.pdf.ai/truncationstrategy/
---
## TruncationStrategy class

تمثل استراتيجية الاقتطاع التي تتحكم في كيفية اقتطاع الخيط قبل التشغيل.

```csharp
public class TruncationStrategy
```

## Constructors

| Name | Description |
| --- | --- |
| [TruncationStrategy](truncationstrategy/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [LastMessages](../../aspose.pdf.ai/truncationstrategy/lastmessages/) { get; set; } | يحصل أو يحدد عدد الرسائل الأحدث من الخيط عند بناء السياق للتشغيل. |
| [StrategyType](../../aspose.pdf.ai/truncationstrategy/strategytype/) { get; set; } | يحصل أو يحدد استراتيجية الاقتطاع لاستخدامها للخيط. الافتراضي هو auto. إذا تم تعيينه إلى last_messages، سيتم اقتطاع الخيط إلى n من أحدث الرسائل في الخيط. عند تعيينه إلى auto، سيتم إسقاط الرسائل في منتصف الخيط لتناسب طول سياق النموذج، max_prompt_tokens. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)