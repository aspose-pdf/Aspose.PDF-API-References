---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: حقل SvgSaveOptions. تحدد هذه الخيارات ما إذا كان سيتم إنشاء دليل الهدف إذا لم يكن موجودًا بعد بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج المطلوب نفسه. بحيث يحتوي الدليل على جميع صور SVG الناتجة للصفحات كما هو موضح أدناه. إذا لم يتم إنشاء ملفات الإخراج للصفحات الأخرى غير الصفحة الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن ستحتوي على لاحقة اسم الملف _2...n التي تحددها رقم الصفحة، على سبيل المثال، إذا قمت بتعريف ملف الإخراج CAsposeTestsoutput.svg وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم أيضًا إنشاء ملفات الصفحات في الدليل CAsposeTests وستكون لها أسماء output.svg و output_2.svg و output_3.svg وما إلى ذلك.
type: docs
weight: 50
url: /ar/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## حقل SvgSaveOptions.TreatTargetFileNameAsDirectory

تحدد هذه الخيارات ما إذا كان سيتم إنشاء دليل الهدف (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج المطلوب نفسه. بحيث يحتوي الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه). إذا لم يكن كذلك، سيتم إنشاء ملفات الإخراج للصفحات الأخرى غير الصفحة الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن ستحتوي على لاحقة اسم الملف _[2...n]، التي تحددها رقم الصفحة، على سبيل المثال، إذا قمت بتعريف ملف الإخراج "C:\AsposeTests\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم أيضًا إنشاء ملفات الصفحات في الدليل "C:\AsposeTests\" وستكون لها أسماء 'output.svg' و 'output_2.svg' و 'output_3.svg' وما إلى ذلك.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### انظر أيضًا

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)