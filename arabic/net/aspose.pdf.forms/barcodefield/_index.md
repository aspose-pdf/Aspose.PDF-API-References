---
title: Class BarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.BarcodeField class. الفئة تمثل حقل الباركود
type: docs
weight: 4950
url: /ar/net/aspose.pdf.forms/barcodefield/
---
## فئة BarcodeField

الفئة تمثل حقل الباركود.

```csharp
public sealed class BarcodeField : TextBoxField
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [BarcodeField](barcodefield/#constructor)(Document, Rectangle) | يُهيئ مثيلاً جديداً من فئة `BarcodeField`. |
| [BarcodeField](barcodefield/#constructor_1)(Page, Rectangle) | يُهيئ مثيلاً جديداً من فئة `BarcodeField`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | يحصل على إجراءات التعليق التوضيحي. (2 خصائص) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعين الحالة الحالية لمظهر التعليق التوضيحي. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | يحصل أو يعين الاسم البديل للحقل (اسم حقل بديل يجب استخدامه بدلاً من الاسم الفعلي للحقل عند تحديد الحقل في واجهة المستخدم). يُستخدم الاسم البديل كتلميح للحقل في Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | يحصل أو يعين فهرس هذا التعليق على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | يحصل على نوع التعليق التوضيحي. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التعليق التوضيحي. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يعين خصائص حدود التعليق التوضيحي. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Caption](../../aspose.pdf.forms/barcodefield/caption/) { get; } | يحصل على عنوان كائن الباركود. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق التوضيحي. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يعين لون التعليق التوضيحي. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يعين نص التعليق التوضيحي. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | يحصل على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الراديو). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | يحصل أو يعين المظهر الافتراضي للحقل. |
| [ECC](../../aspose.pdf.forms/barcodefield/ecc/) { get; } | يحصل على قيمة عددية تمثل معامل تصحيح الخطأ. بالنسبة لـ PDF417، يجب أن تكون من 0 إلى 8. بالنسبة لـ QRCode، يجب أن تكون من 0 إلى 3 (0 لـ 'L'، 1 لـ 'M'، 2 لـ 'Q'، و3 لـ 'H'). |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | يحصل أو يعين علم إمكانية التصدير للحقل. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | أعلام التعليق التوضيحي. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | يحصل أو يعين العلم الذي يشير إلى ما إذا كان الحقل مقسمًا إلى مواضع متباعدة. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم الكامل المؤهل للتعليق التوضيحي. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يعين ارتفاع التعليق التوضيحي. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | وضع تسليط الضوء للتعليق التوضيحي. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يعين رابط الارتباط التشعبي للجزء (للمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يعين قيمة منطقية تدل على ما إذا كانت هذه الفقرة ستكون في العمود التالي. الافتراضي هو false. (لإنشاء PDF) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | يحصل أو يعين قيمة منطقية تدل على ما إذا كان هذا الحقل غير نهائي، أي مجموعة من الحقول. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يعين ما إذا كانت الفقرة مضمنة. الافتراضي هو false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يعين قيمة منطقية تجبر إنشاء هذه الفقرة في صفحة جديدة. الافتراضي هو false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يعين قيمة منطقية تدل على ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. الافتراضي هو false. (لإنشاء PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | خاصية لدعم المولد. تُستخدم عند إضافة الحقل إلى الرأس أو التذييل. إذا كانت true، سيتم إنشاء هذا الحقل مرة واحدة وسيظهر مظهره على جميع صفحات المستند. إذا كانت false، سيتم إنشاء حقل منفصل لكل صفحة من صفحات المستند. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | ترجع true إذا كان القاموس متزامنًا. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | يحصل على الحقل الفرعي الموجود في هذا الحقل حسب اسم الحقل الفرعي. (2 مفهرس) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | يحصل أو يعين اسم التعيين للحقل الذي يجب استخدامه عند تصدير بيانات الحقول التفاعلية من المستند. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعين هامش خارجي للفقرة (لإنشاء PDF) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | يحصل أو يعين الطول الأقصى للنص في الحقل. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعين التاريخ والوقت الذي تم فيه تعديل التعليق التوضيحي مؤخرًا. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | يحصل أو يعين علم تعدد الأسطر للحقل. إذا كانت Multiline true، يمكن أن يحتوي الحقل على عدة خطوط من النص. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعين اسم التعليق التوضيحي على الصفحة. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء سيتم تنفيذه عند تفعيل التعليق التوضيحي. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على هذا الحقل. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الوالد للتعليق التوضيحي. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل أو يعين الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل أو يعين حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل أو يعين مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل أو يعين حالة الإلزام للحقل. |
| [Resolution](../../aspose.pdf.forms/barcodefield/resolution/) { get; } | يحصل على الدقة، بوحدة النقاط لكل بوصة (dpi)، التي يتم عندها عرض كائن الباركود. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | يحصل أو يعين علم القابلية للتمرير للحقل. إذا كانت true، يمكن تمرير الحقل. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | يحصل أو يعين علم التدقيق الإملائي للحقل. إذا كانت true، يجب تدقيق الحقل إملائيًا. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس المظاهر للتعليق التوضيحي. |
| [Symbology](../../aspose.pdf.forms/barcodefield/symbology/) { get; } | يحدد أي تقنية باركود أو glyph تُستخدم في هذا التعليق التوضيحي، انظر [`Symbology`](./symbology/) للتفاصيل. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن التزامن. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل أو يعين ترتيب التبويبات للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعين محاذاة النص للتعليق التوضيحي. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | يحصل أو يعين محاذاة النص العمودية للتعليق التوضيحي. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | يحصل أو يعين قيمة الحقل. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعين المحاذاة العمودية للفقرة. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعين عرض التعليق التوضيحي. |
| [XSymHeight](../../aspose.pdf.forms/barcodefield/xsymheight/) { get; } | يحصل على المسافة الرأسية بين وحدتين من الباركود، مقاسة بالبكسل. يجب أن تكون نسبة XSymHeight/XSymWidth قيمة صحيحة. بالنسبة لـ PDF417، نطاق النسبة المقبول هو من 1 إلى 4. بالنسبة لـ QRCode و DataMatrix، يجب أن تكون هذه النسبة دائمًا 1. |
| [XSymWidth](../../aspose.pdf.forms/barcodefield/xsymwidth/) { get; } | يحصل على المسافة الأفقية، بالبكسل، بين وحدتين من الباركود. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعين قيمة صحيحة تدل على ترتيب Z للرسمة. يتم وضع الرسمة ذات ZIndex الأكبر فوق الرسمة ذات ZIndex الأصغر. يمكن أن يكون ZIndex سالبًا. الرسمة ذات ZIndex السالب توضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | يضيف باركود 128 إلى الحقل. ستتغير قيمة الحقل إلى الرمز ويصبح الحقل للقراءة فقط. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | يضيف صورة إلى موارد الحقل ويرسمها. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | يحدث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | يستنسخ هذا المثال. طريقة افتراضية. دائماً تُرجع null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | ينسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | ينفذ إجراء JavaScript محدد للحقل. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | يصدر حقل نموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى التدفق المقدم. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | يصدر حقل نموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | يصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيم الحقول الزر. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | يزيل هذا الحقل ويوضع قيمته مباشرة على الصفحة. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | يرجع اسم الحالة "checked" وفقاً لأسماء الحالات القائمة. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | يرجع معد النسخ للحقول الموجودة. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يرجع مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | يستورد البيانات إلى الحقول المحددة من تدفق JSON، بناءً على تطابق دقيق للأسماء الكاملة للحقول. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | يستورد البيانات إلى الحقل المحدد من تدفق JSON، باستخدام الاسم الكامل المحدد في المتغير 'fieldFullNameInJSON' للمطابقة. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | يحدد موقع الحقل. |

### راجع أيضاً

* فئة [TextBoxField](../textboxfield/)
* مساحة الاسم [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* التجميع [Aspose.PDF](../../)