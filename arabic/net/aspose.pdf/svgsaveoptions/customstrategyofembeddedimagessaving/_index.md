---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "حقل SvgSaveOptions. يمكن لهذا الحقل أن يحتوي على استراتيجية حفظ يجب استخدامها إذا كانت موجودة أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المشار إليها مثل BMP أو JPEG المضمنة في SVG المحفوظ. يجب أن تقوم تلك الاستراتيجية بمعالجة الموارد وإرجاع سلسلة تمثل URI المرغوب للموارد المحفوظة في SVG المُولد. إذا كان يجب معالجة هذا أو ذاك الملف لسبب ما بواسطة شفرة المحول نفسها وليس في الشفرة المخصصة، يرجى ضبط علامة CustomProcessingCancelled في متغير معلمات imageSavingInfo في الشفرة المخصصة. هذه العلامة تُشير إلى المحول أن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفذ في المحول نفسه كما لو لم يكن هناك أي شفرة مخصصة خارجية"
type: docs
weight: 30
url: /ar/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

يمكن لهذا الحقل أن يحتوي على استراتيجية حفظ يجب استخدامها (إن وجدت) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المضمّن) المضمّنة في SVG المحفوظ. يجب أن تقوم هذه الاستراتيجية بمعالجة الموارد وإرجاع سلسلة تمثل URI المطلوب للموارد المحفوظة في SVG المُولَّد. إذا كان من الضروري معالجة هذا الملف أو ذاك الملف لسبب ما بواسطة كود المحول نفسه، وليس عبر كود مخصص، يرجى تعيين علامة 'CustomProcessingCancelled' في المتغيّر الخاص بمعامل 'imageSavingInfo' في الكود المخصص. هذا يُشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفّذ داخل المحول كما لو لم يكن هناك أي كود مخصص خارجي.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### انظر أيضًا

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


