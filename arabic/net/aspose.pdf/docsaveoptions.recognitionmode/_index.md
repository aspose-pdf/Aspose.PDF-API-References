---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode enum. يسمح بالتحكم في كيفية تحويل مستند PDF إلى مستند معالجة نصوص
type: docs
weight: 3770
url: /ar/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

يسمح بالتحكم في كيفية تحويل مستند PDF إلى مستند معالجة نصوص.

```csharp
public enum RecognitionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Textbox | `0` | هذه الوضعية سريعة وجيدة للحفاظ على المظهر الأصلي لملف PDF، ولكن قابلية تعديل المستند الناتج قد تكون محدودة. |
| Flow | `1` | وضعية التعرف الكاملة، حيث يقوم المحرك بأداء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج مستند قابل للتعديل بشكل كبير. الجانب السلبي هو أن المستند الناتج قد يبدو مختلفًا عن ملف PDF الأصلي. |
| EnhancedFlow | `2` | وضعية تدفق بديلة تدعم التعرف على الجداول. |

## Remarks

استخدم وضعية Textbox عندما لا يُتوقع أن يتم تعديل المستند الناتج بشكل كبير لاحقًا. صناديق النص سهلة التعديل عندما لا يكون هناك الكثير للقيام به.

استخدم وضعية Flow عندما يحتاج المستند الناتج إلى مزيد من التعديل. الفقرات وخطوط النص في وضعية التدفق تسمح بتعديل النص بسهولة، ولكن الكائنات ذات التنسيق غير المدعوم ستبدو أسوأ من وضعية Textbox.

### See Also

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)