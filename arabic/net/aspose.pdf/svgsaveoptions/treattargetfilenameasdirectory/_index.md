---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "حقل SvgSaveOptions. يحدد هذا الخيار ما إذا كان سيتم إنشاء دليل هدف إذا لم يكن موجودًا بعد بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي سيحتوي الدليل على جميع SVGimages للصفحات كما هو موضح أدناه. إذا لم يتم إنشاء ملفات إخراج للصفحات بخلاف الأولى، فستُنشأ في الدليل المطلوب كملف الإخراج الرئيسي ولكن سيحتوي اسم الملف على اللاحقة _2...n التي تُحددها رقم الصفحة، على سبيل المثال إذا قمت بتعريف ملف الإخراج CAsposeTestsoutput.svg وسيحتوي الإخراج على عدة svgfiles للصفحات، فستُنشأ ملفات الصفحات أيضًا في الدليل CAsposeTests وتكون أسماؤها output.svg output_2.svg output_3.svg إلخ"
type: docs
weight: 50
url: /ar/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

تحدد هذه الخيار ما إذا كان سيتم إنشاء دليل هدف (إن لم يكن موجوداً) يحمل نفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي سيحتوي الدليل على جميع صور SVG للصفحات (كما هو موضح أدناه). إذا كان الجواب لا، فسيتم إنشاء ملفات الصفحات الأخرى غير الأولى في الدليل المطلوب نفسه كملف الإخراج الرئيسي، ولكن سيُضاف إلى اسم الملف اللاحقة _[2...n] التي تُحدَّد برقم الصفحة، على سبيل المثال إذا حددت ملف الإخراج "C:\AsposeTests\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم إنشاء ملفات الصفحات أيضاً في الدليل "C:\AsposeTests\" وستكون أسماؤها 'output.svg', 'output_2.svg', 'output_3.svg' إلخ.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### انظر أيضًا

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


