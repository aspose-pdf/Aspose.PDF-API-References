---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. يمثل وضع استخدام منطقة الهوامش أثناء التحويل مثل HTML EPUB وما إلى ذلك، ويحدد معالجة التعليمات الخاصة بالتنسيق المستورد المتعلقة باستخدام الهوامش
type: docs
weight: 6130
url: /ar/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

يمثل وضع استخدام منطقة الهوامش أثناء التحويل (مثل HTML، EPUB وما إلى ذلك)، ويحدد معالجة التعليمات الخاصة بالتنسيق المستورد المتعلقة باستخدام الهوامش.

```csharp
public enum MarginsAreaUsageModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | في هذا الوضع، يطيع المحول تنسيق المستند المستورد (مثل CSS من HTML المستورد) في استخدام منطقة الهوامش. لذا، إذا كان تنسيق المستند المستورد يتطلب استخدام منطقة الهوامش للتقديم، سيسمح المحول بذلك |
| NeverPutContentOnMarginArea | `1` | هذا الوضع يمنع بشكل صارم استخدام منطقة الهوامش، لذا، لن يستخدم المحول منطقة الهوامش للتقديم، حتى إذا كان CSS أو تنسيق المستند المصدر يسمح أو يتطلب ذلك |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)