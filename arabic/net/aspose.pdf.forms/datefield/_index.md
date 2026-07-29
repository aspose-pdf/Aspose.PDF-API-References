---
title: "الفئة DateField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Forms.DateField. حقل تاريخ مع عرض تقويم"
type: docs
weight: 5130
url: /ar/net/aspose.pdf.forms/datefield/
---
## DateField class

حقل تاريخ مع عرض تقويم.

```csharp
public class DateField : TextBoxField
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DateField](datefield/#constructor)() | يُهيئ نسخة جديدة من `DateField` |
| [DateField](datefield/#constructor_1)(Document) | المنشئ الذي يجب استخدامه مع Generator. |
| [DateField](datefield/#constructor_2)(Document, Rectangle) | يُهيئ نسخة جديدة من `DateField` |
| [DateField](datefield/#constructor_3)(Page, Rectangle) | يُهيئ نسخة جديدة من `DateField` |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | يحصل على إجراءات التعليق. (خاصيتان) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | يحصل أو يعيّن الاسم البديل للحقل (اسم حقل بديل يُستخدم بدلاً من الاسم الفعلي للحقل في أي مكان يتم فيه التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقل في Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | الحصول على أو تعيين فهرس هذه التعليقة على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | الحصول على أو تعيين خصائص حدود التعليقة. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | الحصول على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار). |
| [DateFormat](../../aspose.pdf.forms/datefield/dateformat/) { get; set; } | الحصول أو التعيين لتنسيق التاريخ. |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | الحصول على أو تعيين المظهر الافتراضي للحقول. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | الحصول على أو تعيين علامة القابلية للتصدير للحقول. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليقة. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | يحصل أو يضبط العلامة التي تشير إلى ما إذا كان الحقل مقسَّمًا إلى مواضع متباعدة. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | الحصول على الاسم المؤهل بالكامل للتعليقة. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | الحصول على أو تعيين ارتفاع التعليقة. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | وضع تمييز التعليقة. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كان هذا الحقل غير نهائي أي مجموعة من الحقول. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | خاصية لدعم المُولد. تُستخدم عندما يُضاف الحقل إلى الرأس أو التذييل. إذا كانت true، سيتم إنشاء هذا الحقل مرة واحدة وسيكون مظهره مرئياً في جميع صفحات المستند. إذا كانت false، سيتم إنشاء حقل منفصل لكل صفحة من المستند. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | إرجاع true إذا كان القاموس متزامناً. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | الحصول على الحقل الفرعي الموجود في هذا الحقل باسم الحقل الفرعي. (مؤشرين) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | الحصول على أو تعيين اسم التخطيط للحقول الذي سيُستخدم عند تصدير بيانات نماذج الحقول التفاعلية من المستند. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | يحصل أو يضبط الحد الأقصى لطول النص في الحقل. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعيّن التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | يحصل أو يضبط علامة متعددة الأسطر للحقل. إذا كانت Multiline صحيحة، يمكن للحقل أن يحتوي على عدة أسطر من النص. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء يُنفّذ عندما يتم تنشيط التعليق. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على هذا الحقل. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الأصل للتعليق. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل أو يعيّن الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل أو يعيّن حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل أو يعيّن مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل أو يعيّن حالة الإلزامية للحقل. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | يحصل أو يضبط علامة القابلية للتمرير للحقل. إذا كانت true، يمكن تمرير الحقل. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | يحصل أو يعيّن علامة التدقيق الإملائي للحقل. إذا كان true فسيتم تدقيق الحقل إملائيًا. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن المزامنة. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل أو يعيّن ترتيب التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص العمودية للتعليقة. |
| [Value](../../aspose.pdf.forms/datefield/value/) { get; set; } | الحصول أو التعيين للتاريخ. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | يحصل أو يعيّن قيمة الحقل. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | يضيف باركود 128 إلى الحقل. ستُستبدل قيمة الحقل بالرمز ويصبح الحقل للقراءة فقط. |
| [AddImage](../../aspose.pdf.forms/datefield/addimage/#addimage)(Image) | تم رفض إضافة الصورة لهذا الحقل. (طريقتان) |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | ينسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | ينفّذ إجراء JavaScript محدد للحقل. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | يصدّر حقل نموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى الدفق المقدم. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | يصدّر حقل نموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | يصدّر محتوى الحقل المحدد إلى دفق JSON. لا يتم تصدير قيم حقول الأزرار. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | يزيل هذا الحقل ويضع قيمته مباشرةً على الصفحة. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | يعيد اسم الحالة "محدد" وفقًا لأسماء الحالات الموجودة. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | يعيد عداد الحقول المحتواة. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع مراعاة دوران الصفحة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | يستورد البيانات إلى الحقول المحددة من دفق JSON، بناءً على مطابقة دقيقة لأسماء الحقول الكاملة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | يستورد البيانات إلى الحقل المحدد من دفق JSON، باستخدام الاسم الكامل المحدد في المتغيّر 'fieldFullNameInJSON' للمطابقة. |
| [Init](../../aspose.pdf.forms/datefield/init/)(Page) | يُهيئ إجراء JS. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | حدد موضع الحقل. |

## أمثلة

DateField dateField = new DateField(page, rect); doc.Form.Add(dateField); dateField.Init(page);

### انظر أيضًا

* class [TextBoxField](../textboxfield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


