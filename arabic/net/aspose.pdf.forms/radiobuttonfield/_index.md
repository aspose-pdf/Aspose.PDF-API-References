---
title: Class RadioButtonField
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.RadioButtonField. فئة تمثل حقل زر الاختيار
type: docs
weight: 5210
url: /ar/net/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class

فئة تمثل حقل زر الاختيار.

```csharp
public sealed class RadioButtonField : ChoiceField
```

## Constructors

| Name | Description |
| --- | --- |
| [RadioButtonField](radiobuttonfield/#constructor)(Document) | مُنشئ لفئة RadioButtonField. |
| [RadioButtonField](radiobuttonfield/#constructor_1)(Page) | مُنشئ لفئة RadioButtonField |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | يحصل على إجراءات التعليق. (2 خصائص) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يحدد حالة مظهر التعليق الحالية. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | يحصل أو يحدد الاسم البديل للحقل (اسم حقل بديل يجب استخدامه بدلاً من الاسم الفعلي للحقل حيثما يتم التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقل في Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | يحصل أو يحدد فهرس هذا التعليق على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس المظهر للتعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يحدد خصائص حدود التعليق. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يحدد لون التعليق. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | يحصل أو يحدد علامة الالتزام عند تغيير الاختيار. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يحدد نص التعليق. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | يحصل على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | يحصل أو يحدد المظهر الافتراضي للحقل. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | يحصل أو يحدد علامة قابلية التصدير للحقل. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل بالكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يحدد ارتفاع التعليق. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | وضع تمييز التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (لإنشاء PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كان هذا الحقل حقل غير نهائي أي مجموعة من الحقول. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | خاصية لدعم المولد. تُستخدم عند إضافة الحقل إلى الرأس أو التذييل. إذا كانت القيمة true، سيتم إنشاء هذا الحقل مرة واحدة وسيكون مظهره مرئيًا في جميع صفحات المستند. إذا كانت القيمة false، سيتم إنشاء حقل منفصل لكل صفحة من صفحات المستند. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | يُرجع true إذا كان القاموس متزامنًا. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | يحصل على الحقل الفرعي الموجود في هذا الحقل حسب اسم الحقل الفرعي. (2 فهارس) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | يحصل أو يحدد اسم الربط للحقل الذي يجب استخدامه عند تصدير بيانات حقل النموذج التفاعلي من المستند. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يحدد التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | يحصل أو يحدد علامة التحديد المتعدد. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يحدد اسم التعليق على الصفحة. |
| [NoToggleToOff](../../aspose.pdf.forms/radiobuttonfield/notoggletooff/) { get; set; } | يحصل أو يحدد العلامة التي تسمح لزر الاختيار بعدم وجود قيمة محددة. إذا كانت القيمة `true`، يجب أن يكون هناك زر اختيار واحد محدد في جميع الأوقات؛ اختيار الزر المحدد حاليًا ليس له تأثير. إذا كانت القيمة `false`، فإن النقر على الزر المحدد يلغي تحديده، مما يترك دون زر محدد. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء سيتم تنفيذه عند تنشيط التعليق. |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options/) { get; } | يحصل على مجموعة من خيارات زر الاختيار. |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على حقل RadioButton هذا. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الوالد للتعليق. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل أو يحدد الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل أو يحدد حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل أو يحدد مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل أو يحدد حالة المتطلبات للحقل. |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected/) { get; set; } | يحصل أو يحدد فهرس العنصر المحدد. يبدأ ترقيم العناصر من 1. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | يحصل أو يحدد مصفوفة العناصر المحددة. لقائمة التحديد المتعدد تحتوي المصفوفة على أكثر من عنصر واحد. لقائمة التحديد الفردي تحتوي على عنصر واحد. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس المظهر للتعليق. |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style/) { get; set; } | نمط صندوق الحقل. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن المزامنة. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل أو يحدد ترتيب التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة النص للتعليق. |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value/) { get; set; } | يحصل أو يحدد قيمة الحقل. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add/)(RadioButtonOptionField) | يضيف حقل خيار جديد إلى حقل زر الاختيار |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption)(string) | يضيف خيارًا إلى زر الاختيار. |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption_1)(string, Rectangle) | يضيف إلى خيار زر الاختيار مع مستطيل محدد. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | يضيف خيارًا جديدًا مع قيمة تصدير واسم محددين. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | ينسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | يحذف الخيار حسب اسمه. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | ينفذ إجراء JavaScript محدد للحقل. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | يصدر حقل النموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى التدفق المقدم. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | يصدر حقل النموذج PDF المحدد إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | يصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيمة حقل الزر. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | يزيل هذا الحقل ويضع قيمته مباشرة على الصفحة. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | يُرجع اسم حالة "محدد" وفقًا لأسماء الحالات الموجودة. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | يُرجع عداد الحقول المحتواة. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يُرجع مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | يستورد البيانات إلى الحقول المحددة من تدفق JSON، بناءً على مطابقة دقيقة لأسماء الحقول الكاملة. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | يستورد البيانات إلى الحقل المحدد من تدفق JSON، باستخدام الاسم الكامل المحدد في متغير 'fieldFullNameInJSON' للمطابقة. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition/)(Point) | ينقل جميع العناصر الفرعية لزر الاختيار إلى المواقع المحددة على الصفحة. |

### See Also

* class [ChoiceField](../choicefield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)