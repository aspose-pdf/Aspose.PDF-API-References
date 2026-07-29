---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يُعدد هذا التعداد أوضاع تضمين الملفات المشار إليها في HTML. يسمح بالتحكم فيما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، ملفات CSS) سيتم تضمينها في الرئيسي."
type: docs
weight: 2130
url: /ar/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

هذا التعداد يعدد أوضاع الإدماج الممكنة للملفات المشار إليها في HTML. يسمح بالتحكم فيما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، CSS) ستُدمج في ملف HTML الرئيسي أم ستُنشأ ككيانات ثنائية منفصلة.

## الحقول

| حقل | الوصف |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | يفرض تضمين جميع الملفات المشار إليها (CSS، الصور، الخطوط) في ترميز HTML المُولد (أي داخل HTML نفسه). ينتج هذا النهج ملف HTML واحد، لكن يصبح حجم الإخراج الكلي أكبر (نظرًا لاستخدام ترميز Base64 للملفات الثنائية) ولا تعالج جميع المتصفحات (خاصة القديمة) الملفات الثنائية المضمَّنة في HTML بنجاح. لكنه يسمح بالحصول على HTML يحتوي على النتيجة بالكامل دون أي ملفات إضافية. |
| [EmbedCssOnly](#EmbedCssOnly) | يفرض فصل جميع الملفات المشار إليها باستثناء CSS (الصور والخطوط). أي أن CSS سيتم تضمينه في HTML الناتج، بينما ستُعالج باقي الملفات المشار إليها (الصور والخطوط) كأجزاء خارجية. ينتج هذا HTML مناسب لمجموعة واسعة من المتصفحات. |
| [NoEmbedding](#NoEmbedding) | يفرض فصل الملفات المشار إليها (CSS، الصور، الخطوط). ينتج هذا النهج مجموعة من الملفات، لكن يصبح حجم الإخراج الكلي أصغر (نظرًا لعدم استخدام ترميز Base64 للملفات الثنائية). كما أن هذا النهج يولد HTML مناسب لمجموعة واسعة من المتصفحات. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

يفرض تضمين جميع الملفات المشار إليها (CSS، الصور، الخطوط) في ترميز HTML المُولد (أي داخل HTML نفسه). ينتج هذا النهج ملف HTML واحد، لكن يصبح حجم الإخراج الكلي أكبر (نظرًا لاستخدام ترميز Base64 للملفات الثنائية) ولا تعالج جميع المتصفحات (خاصة القديمة) الملفات الثنائية المضمَّنة في HTML بنجاح. لكنه يسمح بالحصول على HTML يحتوي على النتيجة بالكامل دون أي ملفات إضافية.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

يفرض فصل جميع الملفات المشار إليها باستثناء CSS (الصور والخطوط). أي أن CSS سيتم تضمينه في HTML الناتج، بينما ستُعالج باقي الملفات المشار إليها (الصور والخطوط) كأجزاء خارجية. ينتج هذا HTML مناسب لمجموعة واسعة من المتصفحات.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

يفرض فصل الملفات المشار إليها (CSS، الصور، الخطوط). ينتج هذا النهج مجموعة من الملفات، لكن يصبح حجم الإخراج الكلي أصغر (نظرًا لعدم استخدام ترميز Base64 للملفات الثنائية). كما أن هذا النهج يولد HTML مناسب لمجموعة واسعة من المتصفحات.
