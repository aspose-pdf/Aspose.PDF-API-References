---
title: Class CompromiseCheckResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.CompromiseCheckResult class. تمثل فئة للتحقق من التوقيعات الرقمية للمستندات من التلاعب
type: docs
weight: 10100
url: /ar/net/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult class

تمثل فئة للتحقق من التوقيعات الرقمية للمستندات من التلاعب.

```csharp
public sealed class CompromiseCheckResult
```

## Properties

| Name | Description |
| --- | --- |
| [HasCompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/hascompromisedsignatures/) { get; } | تشير إلى ما إذا كانت هناك أي توقيعات رقمية تم التلاعب بها في المستند. تعيد true إذا كانت هناك توقيع واحد على الأقل تم التلاعب به؛ وإلا، تعيد false. |
| [SignaturesCoverage](../../aspose.pdf.signatures/compromisecheckresult/signaturescoverage/) { get; } | تحصل على حالة تغطية التوقيعات الرقمية في المستند. إذا كانت تساوي Undefined، فإن أحد التوقيعات قد تم التلاعب به. |

## Fields

| Name | Description |
| --- | --- |
| readonly [CompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/compromisedsignatures/) | تحصل على مجموعة من التوقيعات الرقمية التي تم تحديدها على أنها تم التلاعب بها. تحتوي هذه الخاصية على قائمة بجميع التوقيعات الم compromised التي تم اكتشافها في المستند. |

### See Also

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)