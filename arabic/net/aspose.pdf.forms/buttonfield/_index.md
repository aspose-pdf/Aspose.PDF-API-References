---
title: Class ButtonField
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.ButtonField. تمثل الفئة حقل زر دفع
type: docs
weight: 4970
url: /ar/net/aspose.pdf.forms/buttonfield/
---
## فئة ButtonField

تمثل الفئة حقل زر دفع.

```csharp
public class ButtonField : Field
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ButtonField](buttonfield/#constructor)() | منشئ حقل الزر للمولد. |
| [ButtonField](buttonfield/#constructor_1)(Document, Rectangle) | منشئ ButtonField. |
| [ButtonField](buttonfield/#constructor_2)(Page, Rectangle) | منشئ ButtonField. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | يحصل على إجراءات التعليق. (2 خاصيات) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يحدد حالة مظهر التعليق الحالي. |
| [AlternateCaption](../../aspose.pdf.forms/buttonfield/alternatecaption/) { get; set; } | يحصل أو يحدد التسمية البديلة للزر التي ستظهر عند الضغط على زر الماوس داخل منطقة النشاط الخاصة به. |
| [AlternateIcon](../../aspose.pdf.forms/buttonfield/alternateicon/) { get; set; } | يحصل أو يحدد الرمز البديل الذي سيظهر عند الضغط على زر الماوس داخل منطقة النشاط الخاصة به. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | يحصل أو يحدد الاسم البديل للحقل (اسم حقل بديل سيتم استخدامه بدلاً من الاسم الفعلي للحقل حيثما يتم التعرف على الحقل في واجهة المستخدم). يتم استخدام الاسم البديل كأداة تلميح للحقل في Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | يحصل أو يحدد فهرس هذا التعليق على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس المظهر للتعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يحدد خصائص حدود التعليق. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يحدد لون التعليق. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يحدد نص التعليق. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | يحصل على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الراديو). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | يحصل أو يحدد المظهر الافتراضي للحقل. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | يحصل أو يحدد علامة تصدير الحقل. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل بالكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يحدد ارتفاع التعليق. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | وضع تمييز التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (للمولد PDF). |
| [IconFit](../../aspose.pdf.forms/buttonfield/iconfit/) { get; } | يحصل على كائن ملاءمة الرمز الذي يحدد كيفية عرض رمز التعليق داخل مستطيل التعليق الخاص به. |
| [ICPosition](../../aspose.pdf.forms/buttonfield/icposition/) { get; set; } | يحصل أو يحدد موضع تسمية الرمز. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كان هذا الحقل حقل غير نهائي أي مجموعة من الحقول. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | خاصية لدعم المولد. تستخدم عند إضافة الحقل إلى الرأس أو التذييل. إذا كانت القيمة true، سيتم إنشاء هذا الحقل مرة واحدة وسيكون مظهره مرئيًا في جميع صفحات المستند. إذا كانت القيمة false، سيتم إنشاء حقل منفصل لكل صفحة من صفحات المستند. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | تعيد true إذا كان القاموس متزامنًا. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | يحصل على الحقل الفرعي المحتوى في هذا الحقل حسب اسم الحقل الفرعي. (2 فهارس) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | يحصل أو يحدد اسم التعيين للحقل الذي سيتم استخدامه عند تصدير بيانات حقل النموذج التفاعلي من المستند. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يحدد التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يحدد اسم التعليق على الصفحة. |
| [NormalCaption](../../aspose.pdf.forms/buttonfield/normalcaption/) { get; set; } | يحصل أو يحدد التسمية العادية. |
| [NormalIcon](../../aspose.pdf.forms/buttonfield/normalicon/) { get; set; } | يحصل أو يحدد الرمز العادي للزر الذي سيظهر عندما لا يتفاعل مع المستخدم. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء سيتم تنفيذه عند تنشيط التعليق. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على هذا الحقل. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الوالد للتعليق. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل أو يحدد الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل أو يحدد حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل أو يحدد مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل أو يحدد حالة المتطلبات للحقل. |
| [RolloverCaption](../../aspose.pdf.forms/buttonfield/rollovercaption/) { get; set; } | يحصل أو يحدد التسمية المتدحرجة للزر التي ستظهر عندما يقوم المستخدم بتحريك المؤشر إلى منطقة النشاط الخاصة به دون الضغط على زر الماوس. |
| [RolloverIcon](../../aspose.pdf.forms/buttonfield/rollovericon/) { get; set; } | يحصل أو يحدد الرمز المتدحرج للزر الذي سيظهر عندما يقوم المستخدم بتحريك المؤشر إلى منطقة النشاط الخاصة به دون الضغط على زر الماوس. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس المظهر للتعليق. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن التزامن. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل أو يحدد ترتيب التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة النص للتعليق. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | يحصل أو يحدد قيمة الحقل. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة int تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| [AddImage](../../aspose.pdf.forms/buttonfield/addimage/)(Image) | يضيف صورة إلى موارد الحقل ويرسمها. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. تعيد دائمًا null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | ينسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | ينفذ إجراء JavaScript المحدد للحقل. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | يصدر حقل PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى التدفق المقدم. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | يصدر حقل PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | يصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيمة حقل الزر. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | يزيل هذا الحقل ويضع قيمته مباشرة على الصفحة. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | يعيد اسم حالة "محدد" وفقًا لأسماء الحالات الموجودة. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | يعيد عداد الحقول المحتواة. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | يستورد البيانات إلى الحقول المحددة من تدفق JSON، بناءً على مطابقة دقيقة لأسماء الحقول الكاملة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | يستورد البيانات إلى الحقل المحدد من تدفق JSON، باستخدام الاسم الكامل المحدد في متغير 'fieldFullNameInJSON' للمطابقة. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة على النموذج. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | يحدد موضع الحقل. |

### انظر أيضًا

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)