---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. هذا التعداد يعدد أوضاع الإدراج الممكنة للملفات المشار إليها في HTML. يسمح بالتحكم فيما إذا كانت الملفات المشار إليها  ستدرج في ملف HTML الرئيسي أو ستولد ككيانات ثنائية منفصلة.
type: docs
weight: 5710
url: /ar/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

هذا التعداد يعدد أوضاع الإدراج الممكنة للملفات المشار إليها في HTML. يسمح بالتحكم فيما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، CSS) ستدرج في ملف HTML الرئيسي أو ستولد ككيانات ثنائية منفصلة.

```csharp
public enum PartsEmbeddingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | يفرض إدراج جميع الملفات المشار إليها (CSS، الصور، الخطوط) في التعليمات البرمجية HTML الناتجة (أي في HTML نفسه). هذه الطريقة تولد ملف HTML واحد، لكن الحجم الإجمالي للإخراج يصبح أكبر (لأن ترميز Base64 للثنائيات قيد الاستخدام) وليس جميع المتصفحات (خاصة القديمة) تعالج الثنائيات المدمجة في HTML بنجاح. لكنها تسمح بالحصول على HTML يحتوي على النتيجة الكاملة، دون أي ملفات إضافية. |
| EmbedCssOnly | `1` | يفرض وضع جميع الملفات المشار إليها باستثناء CSS (الصور والخطوط) في أجزاء منفصلة. أي أن CSS سيتم إدراجه في HTML الناتج، وجميع الملفات المشار إليها الأخرى (الصور والخطوط) ستتم معالجتها كأجزاء خارجية. إنها تولد HTML مناسب لمجموعة واسعة من المتصفحات. |
| NoEmbedding | `2` | يفرض وضع الملفات المشار إليها (CSS، الصور، الخطوط) في أجزاء منفصلة. هذه الطريقة تولد مجموعة من الملفات، لكن الحجم الإجمالي للإخراج يصبح أصغر (لأنه لا يتم استخدام ترميز Base64 للثنائيات). كما أن هذه الطريقة تولد HTML مناسب لمجموعة واسعة من المتصفحات. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)