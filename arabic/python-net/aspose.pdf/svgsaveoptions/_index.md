---
title: "SvgSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "خيارات الحفظ للتصدير إلى تنسيق SVG"
type: docs
weight: 1460
url: /ar/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق SVG

يعرض نوع SvgSaveOptions الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| SvgSaveOptions() | ينشئ مثيلاً جديداً من فئة SvgSaveOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| warning_handler | استدعاء رد نداء للتعامل مع أي تحذيرات تم إنشاؤها. <br/>            يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. <br/>            Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم أيضًا Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |
| save_format | تنسيق حفظ البيانات. |
| close_response | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان كائن Response سيُغلق بعد حفظ المستند في الاستجابة. |
| extract_ocr_sublayer_only | لا شيء |
| try_merge_adjacent_same_background_images | لا شيء |
| treat_target_file_name_as_directory | هذا الخيار يحدد ما إذا كان سيتم إنشاء دليل الهدف<br/>             (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب <br/>             بدلاً من ملف الإخراج نفسه.<br/>             وبالتالي، سيحتوي الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه).<br/>               إذا كان لا، سيتم إنشاء ملفات إخراج الصفحات غير الأولى بالضبط في الدليل المطلوب<br/>            كملف الإخراج الرئيسي، ولكن سيحتوي اسم الملف على اللاحقة _[2...n]، التي<br/>             تُحدد برقم الصفحة، على سبيل المثال إذا قمت بتحديد ملف الإخراج "C:\\AsposeTests\\output.svg"<br/>             وكان الإخراج سيحتوي على عدة ملفات svg للصفحات،<br/>             فسيتم إنشاء ملفات الصفحات أيضًا في الدليل "C:\\AsposeTests\\" وتكون أسماؤها 'output.svg', 'output_2.svg', 'output_3.svg' إلخ. |
| compress_output_to_zip_archive | يحدد ما إذا كان سيتم إنشاء الإخراج كأرشيف zip واحد.<br/>             يرجى الرجوع إلى التعليق على خيار 'TreatTargetFileNameAsDirectory' لرؤية قواعد تسمية<br/>             ملفات svg للصفحات لمستند المصدر متعدد الصفحات، والتي تُطبق أيضًا على مجموعة الملفات المضغوطة. |
| scale_to_pixels | يحدد ما إذا كان سيتم تحويل مقياس مستند الإخراج من النقاط الطباعية إلى البكسلات. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

