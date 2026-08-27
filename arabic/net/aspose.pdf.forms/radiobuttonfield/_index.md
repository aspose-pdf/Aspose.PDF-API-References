---
title: "الفئة RadioButtonField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Forms.RadioButtonField. الفئة تمثّل حقل زر اختيار."
type: docs
weight: 5330
url: /ar/net/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class

فئة تمثل حقل زر الاختيار.

```csharp
public sealed class RadioButtonField : ChoiceField
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RadioButtonField](radiobuttonfield/#constructor)(Document) | منشئ لحقل RadioButtonField. |
| [RadioButtonField](radiobuttonfield/#constructor_1)(Page) | منشئ لحقل RadiouttonField |

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
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | يحصل أو يعيّن علامة الالتزام عند تغيير الاختيار. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | الحصول على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | الحصول على أو تعيين المظهر الافتراضي للحقول. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | الحصول على أو تعيين علامة القابلية للتصدير للحقول. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليقة. |
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
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعيّن التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | يحصل أو يعيّن علامة التحديد المتعدد. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| [NoToggleToOff](../../aspose.pdf.forms/radiobuttonfield/notoggletooff/) { get; set; } | احصل أو عيّن العلامة التي تسمح لزر الاختيار بأن لا يكون له قيمة محددة. إذا كان `true`، يجب أن يكون زر اختيار واحد فقط محددًا في جميع الأوقات؛ اختيار الزر المحدد حاليًا لا يؤثر. إذا كان `false`، فإن النقر على الزر المحدد يلغي تحديده، مما يترك لا زر محدد. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء يُنفّذ عندما يتم تنشيط التعليق. |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options/) { get; } | يحصل على مجموعة خيارات زر الاختيار. |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على حقل RadioButton هذا. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الأصل للتعليق. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل أو يعيّن الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل أو يعيّن حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل أو يعيّن مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل أو يعيّن حالة الإلزامية للحقل. |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected/) { get; set; } | يحصل أو يعيّن فهرس العنصر المحدد. يبدأ ترقيم العناصر من 1. |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | يحصل أو يعيّن مصفوفة العناصر المحددة. في قائمة متعددة الاختيارات تحتوي المصفوفة على أكثر من عنصر. في قائمة اختيار فردي تحتوي على عنصر واحد. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style/) { get; set; } | نمط صندوق الحقل. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن المزامنة. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل أو يعيّن ترتيب التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value/) { get; set; } | يحصل أو يعيّن قيمة الحقل. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add/)(RadioButtonOptionField) | يضيف حقل خيار جديد إلى حقل RadioButton |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption)(string) | أضف خيارًا إلى زر radion. |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption/#addoption_1)(string, Rectangle) | أضف إلى خيار زر الاختيار مع مستطيل محدد. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | يضيف خيارًا جديدًا بقيمة تصدير واسم محددين. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | ينسخ الحقول الفرعية لهذا الحقل إلى مصفوفة بدءًا من الفهرس المحدد. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | يحذف الخيار حسب اسمه. |
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
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition/)(Point) | انقل جميع العناصر الفرعية لزر الاختيار إلى المواضع المحددة على الصفحة. |

### انظر أيضًا

* class [ChoiceField](../choicefield/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


