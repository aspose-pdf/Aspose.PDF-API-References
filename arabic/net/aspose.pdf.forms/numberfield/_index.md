---
title: NumberField
second_title: Aspose.PDF لمرجع .NET API
description: حقل نصي مع chars المحدد الصالح المحدد
type: docs
weight: 3090
url: /ar/net/aspose.pdf.forms/numberfield/
---
## NumberField class

حقل نصي مع chars المحدد الصالح المحدد

```csharp
public class NumberField : TextBoxField
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [NumberField](numberfield#constructor)() | يقوم بتهيئة مثيل جديد لملف[`NumberField`](../numberfield) فئة . |
| [NumberField](numberfield#constructor_1)(Document, Rectangle) | يقوم بتهيئة مثيل جديد لملف[`NumberField`](../numberfield) فئة . |
| [NumberField](numberfield#constructor_2)(Page, Rectangle) | يقوم بتهيئة مثيل جديد لملف[`NumberField`](../numberfield) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | يحصل على إجراءات التعليق التوضيحي . (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | الحصول على حالة مظهر التعليق التوضيحي الحالية أو تعيينها. |
| [AllowedChars](../../aspose.pdf.forms/numberfield/allowedchars) { get; set; } | الحصول على الأحرف المسموح بها أو تعيينها. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | الحصول على الاسم البديل للحقل أو تعيينه (حقل بديل الاسم الذي يجب استخدامه بدلاً من اسم الحقل الفعلي أينما يتم تحديد الحقل في واجهة المستخدم) . يتم استخدام الاسم البديل كتلميح أداة حقل في Adobe Acrobat . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | الحصول على فهرس هذه الشرح أو تعيينه على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | يحصل على نوع التعليق التوضيحي . |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | الحصول على أو تعيين خصائص حدود التعليق التوضيحي.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | الحصول على خصائص التعليقات التوضيحية . |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | الحصول على لون التعليق التوضيحي أو تعيينه. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | الحصول على نص التعليق التوضيحي أو تعيينه. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | الحصول على أو تعيين عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار) . |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | الحصول على المظهر الافتراضي للحقل أو تعيينه. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | الحصول على أو تعيين علامة الحقل القابلة للتصدير. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | إشارات التعليق التوضيحي . |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs) { get; set; } | الحصول على أو تعيين علامة تشير إلى أن الحقل مقسم إلى مواضع متباعدة. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | الحصول على الاسم الكامل للتعليق التوضيحي. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | الحصول على ارتفاع التعليق التوضيحي أو تعيينه. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | وضع تمييز التعليقات التوضيحية . |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | الحصول على أو تعيين الارتباط التشعبي للجزء (لمولد pdf) . |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | الحصول على أو تعيين القيمة المنطقية التي تشير إلى أن هذا الحقل ليس حقلًا طرفيًا ، أي مجموعة من الحقول. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | خاصية دعم المولد. يستخدم عند إضافة حقل إلى رأس أو تذييل الصفحة. إذا كان هذا صحيحًا ، فسيتم إنشاء هذا الحقل مرة واحدة وسيكون مظهره مرئيًا في جميع صفحات المستند. إذا كانت خاطئة ، فسيتم إنشاء حقل منفصل لكل صفحة من صفحات الوثيقة. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | يعود صحيحًا إذا تمت مزامنة القاموس. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | يحصل على الحقل الفرعي المضمن في هذا الحقل باسم الحقل الفرعي. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | الحصول على أو تعيين اسم التعيين للحقل الذي سيتم استخدامه عند تصدير بيانات حقل النموذج التفاعلي من المستند. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen) { get; set; } | الحصول على أو تعيين الحد الأقصى لطول النص في الحقل. |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | تحديد أو تحديد التاريخ والوقت اللذين تم فيهما تعديل التعليق التوضيحي مؤخرًا. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline) { get; set; } | الحصول على أو تعيين علم متعدد الأسطر للحقل. إذا كان متعدد الأسطر صحيحًا ، فيمكن أن يحتوي الحقل على عدة أسطر من النص. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | الحصول على أو تعيين اسم التعليق التوضيحي على الصفحة. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | إجراء يتم تنفيذه عند تنشيط التعليق التوضيحي. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | يحصل على فهرس الصفحة الذي يحتوي على هذا الحقل. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | الحصول على أصل التعليق التوضيحي. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | الحصول على الاسم الجزئي للحقل أو تعيينه. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | الحصول على حالة القراءة فقط للحقل أو تعيينها. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | الحصول على مستطيل الحقل أو تعيينه. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | الحصول على الحالة المطلوبة للحقل أو تعيينها. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable) { get; set; } | الحصول على علم الحقل القابل للتمرير أو تعيينه. إذا كان الحقل صحيحًا يمكن تمريره. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck) { get; set; } | الحصول على علامة التدقيق الإملائي للحقل أو تعيينها. إذا كان هذا الحقل صحيحًا ، فسيتم تدقيقه إملائيًا. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | كائن التزامن . |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | الحصول على أو تعيين ترتيب علامة التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | الحصول على محاذاة النص للتعليق التوضيحي أو تعيينها. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment) { get; set; } | الحصول على محاذاة رأسية للنص أو تعيينها للتعليق التوضيحي. |
| override [Value](../../aspose.pdf.forms/textboxfield/value) { get; set; } | الحصول على قيمة الحقل أو تعيينها. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | الحصول على محاذاة عمودية للفقرة أو تعيينها |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | الحصول على عرض التعليق التوضيحي أو تعيينه. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | الحصول على أو تحديد قيمة int التي تشير إلى ترتيب Z للرسم البياني. سيتم وضع رسم بياني به ZIndex أكبر فوق الرسم البياني باستخدام ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني بالسالب سيتم وضع مؤشر Z خلف النص في الصفحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | يقبل الزائر . |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode)(string) | يضيف الرمز الشريطي 128 في الحقل. سيتم تغيير قيمة الحقل إلى الرمز وسيصبح الحقل للقراءة فقط. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage)(Image) | يضيف صورة إلى موارد الحقل ويرسمها . |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | تحديث المعلمات والمظهر ، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | استنساخ هذا المثال. طريقة افتراضية. العودة دائما فارغة. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | ينسخ الحقول الفرعية لهذا الحقل في مصفوفة تبدأ من الفهرس المحدد. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | يزيل هذا الحقل ويضع قيمته مباشرة على الصفحة. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | إرجاع عداد الحقول المضمنة. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | إرجاع مستطيل التعليق التوضيحي مع مراعاة تدوير الصفحة. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | يعيد احتساب كافة الحقول المحسوبة في النموذج. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | تعيين موضع الحقل. |

### أنظر أيضا

* class [TextBoxField](../textboxfield)
* مساحة الاسم [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
