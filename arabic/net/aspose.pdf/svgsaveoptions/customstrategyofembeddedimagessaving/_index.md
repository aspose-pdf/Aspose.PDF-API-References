---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: حقل SvgSaveOptions. يمكن أن يحتوي هذا الحقل على استراتيجية الحفظ التي يجب استخدامها إذا كانت موجودة أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها مثل BMP المضمنة أو JPEG المضمنة في SVG المحفوظ. يجب أن تعالج تلك الاستراتيجية الموارد وتعيد سلسلة تمثل URI المرغوب فيه للموارد المحفوظة في SVG الناتج. إذا كان يجب أن يتم المعالجة لهذا الملف أو ذاك لسبب ما بواسطة كود المحول نفسه وليس في الكود المخصص، يرجى تعيين في الكود المخصص علامة 'CustomProcessingCancelled' لمتغير معلمة 'imageSavingInfo'. إنها تشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة تلك المورد يجب أن تتم في المحول نفسه كما لو لم يكن هناك أي كود مخصص خارجي.
type: docs
weight: 30
url: /ar/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## حقل SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving

يمكن أن يحتوي هذا الحقل على استراتيجية الحفظ التي يجب استخدامها (إذا كانت موجودة) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP المضمنة أو JPEG) المضمنة في SVG المحفوظ. يجب أن تعالج تلك الاستراتيجية الموارد وتعيد سلسلة تمثل URI المرغوب فيه للموارد المحفوظة في SVG الناتج. إذا كان يجب أن تتم المعالجة لهذا الملف أو ذاك لسبب ما بواسطة كود المحول نفسه، وليس في الكود المخصص، يرجى تعيين في الكود المخصص علامة 'CustomProcessingCancelled' لمتغير معلمة 'imageSavingInfo'. إنها تشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة تلك المورد يجب أن تتم في المحول نفسه كما لو لم يكن هناك أي كود مخصص خارجي.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### انظر أيضًا

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)