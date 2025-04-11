---
title: Class RadioButtonOptionField
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.RadioButtonOptionField. تمثل الفئة عنصرًا من حقل RadioButton
type: docs
weight: 5220
url: /ar/net/aspose.pdf.forms/radiobuttonoptionfield/
---
## RadioButtonOptionField class

تمثل الفئة عنصرًا من حقل RadioButton.

```csharp
public sealed class RadioButtonOptionField : Field
```

## Constructors

| Name | Description |
| --- | --- |
| [RadioButtonOptionField](radiobuttonoptionfield/#constructor)() | إنشاء مثيل جديد من RadioButtonOptionField. |
| [RadioButtonOptionField](radiobuttonoptionfield/#constructor_1)(Page, Rectangle) | ينشئ زر اختيار في المستطيل المحدد على الصفحة المحددة. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | يحصل على إجراءات التعليق. (2 خصائص) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل على أو يحدد حالة مظهر التعليق الحالي. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | يحصل على أو يحدد الاسم البديل للحقل (اسم حقل بديل يجب استخدامه بدلاً من الاسم الفعلي للحقل حيثما يتم التعرف على الحقل في واجهة المستخدم). يتم استخدام الاسم البديل كأداة تلميح للحقل في Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | يحصل على أو يحدد فهرس هذا التعليق على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس المظهر للتعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل على أو يحدد خصائص حدود التعليق. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Caption](../../aspose.pdf.forms/radiobuttonoptionfield/caption/) { get; set; } | يحصل على أو يحدد التسمية. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل على أو يحدد لون التعليق. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل على أو يحدد نص التعليق. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | يحصل على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | يحصل على أو يحدد المظهر الافتراضي للحقل. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | يحصل على أو يحدد علامة تصدير الحقل. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل بالكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل على أو يحدد ارتفاع التعليق. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | وضع تمييز التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل على أو يحدد رابط الجزء (لإنشاء PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل على أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | يحصل على أو يحدد قيمة بوليانية تشير إلى ما إذا كان هذا الحقل حقل غير نهائي أي مجموعة من الحقول. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل على أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل على أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل على أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | خاصية لدعم المولد. تستخدم عندما يتم إضافة الحقل إلى الرأس أو التذييل. إذا كانت القيمة true، سيتم إنشاء هذا الحقل مرة واحدة وسيكون مظهره مرئيًا في جميع صفحات الوثيقة. إذا كانت القيمة false، سيتم إنشاء حقل منفصل لكل صفحة من صفحات الوثيقة. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | تعيد true إذا كان القاموس متزامنًا. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | يحصل على الحقل الفرعي المحتوى في هذا الحقل حسب اسم الحقل الفرعي. (2 فهارس) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | يحصل على أو يحدد اسم التعيين للحقل الذي يجب استخدامه عند تصدير بيانات حقل النموذج التفاعلي من الوثيقة. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل على أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل على أو يحدد التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل على أو يحدد اسم التعليق على الصفحة. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء يجب تنفيذه عند تنشيط التعليق. |
| [OptionName](../../aspose.pdf.forms/radiobuttonoptionfield/optionname/) { get; set; } | يحصل على أو يحدد اسم الخيار. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على هذا الحقل. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الوالد للتعليق. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل على أو يحدد الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل على أو يحدد حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل على أو يحدد مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل على أو يحدد حالة المتطلبات للحقل. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس المظهر للتعليق. |
| [Style](../../aspose.pdf.forms/radiobuttonoptionfield/style/) { get; set; } | يحصل على أو يحدد نمط مربع الاختيار. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن التزامن. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل على أو يحدد ترتيب التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل على أو يحدد محاذاة النص للتعليق. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | يحصل على أو يحدد قيمة الحقل. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل على أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل على أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل على أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا تعيد null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | ينسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | ينفذ إجراء JavaScript المحدد للحقل. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | يصدر حقل نموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى التدفق المقدم. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | يصدر حقل نموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | يصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيمة حقل الزر. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | يزيل هذا الحقل ويضع قيمته مباشرة على الصفحة. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | يعيد اسم حالة "محدد" وفقًا لأسماء الحالات الموجودة. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | يعيد عداد الحقول المحتواة. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | يستورد البيانات إلى الحقول المحددة من تدفق JSON، بناءً على مطابقة دقيقة لأسماء الحقول الكاملة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | يستورد البيانات إلى الحقل المحدد من تدفق JSON، باستخدام الاسم الكامل المحدد في متغير 'fieldFullNameInJSON' للمطابقة. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | تعيين موضع الحقل. |

### See Also

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)