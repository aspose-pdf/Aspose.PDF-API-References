---
title: "الفئة CheckboxField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Forms.CheckboxField. فئة تمثل حقل خانة الاختيار"
type: docs
weight: 5100
url: /ar/net/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class

الفئة تمثل حقل خانة الاختيار

```csharp
public class CheckboxField : Field
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CheckboxField](checkboxfield/#constructor_1)(Document) | المنشئ للاستخدام مع Generator. |
| [CheckboxField](checkboxfield/#constructor_2)(Document, Rectangle) | المنشئ لفئة CheckboxField. |
| [CheckboxField](checkboxfield/#constructor_3)(Page, Rectangle) | المنشئ لفئة CheckboxField. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | يحصل على إجراءات التعليق. (خاصيتان) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates/) { get; } | يرجع قائمة الحالات المسموح بها. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | يحصل أو يعيّن الاسم البديل للحقل (اسم حقل بديل يُستخدم بدلاً من الاسم الفعلي للحقل في أي مكان يتم فيه التعرف على الحقل في واجهة المستخدم). يُستخدم الاسم البديل كأداة تلميح للحقل في Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | الحصول على أو تعيين فهرس هذه التعليقة على الصفحة. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | الحصول على أو تعيين خصائص حدود التعليقة. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked/) { get; set; } | يحصل أو يحدد حالة خانة الاختيار. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | الحصول على عدد الحقول الفرعية في هذا الحقل. (على سبيل المثال عدد العناصر في حقل زر الاختيار). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | الحصول على أو تعيين المظهر الافتراضي للحقول. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | الحصول على أو تعيين علامة القابلية للتصدير للحقول. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue/) { get; set; } | يحصل أو يحدد قيمة التصدير لحقل CheckBox. |
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
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | إجراء يُنفّذ عندما يتم تنشيط التعليق. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على هذا الحقل. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | يحصل على الأصل للتعليق. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | يحصل أو يعيّن الاسم الجزئي للحقل. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | يحصل أو يعيّن حالة القراءة فقط للحقل. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | يحصل أو يعيّن مستطيل الحقل. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | يحصل أو يعيّن حالة الإلزامية للحقل. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Style](../../aspose.pdf.forms/checkboxfield/style/) { get; set; } | يحصل أو يعيّن نمط مربع الاختيار. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | كائن المزامنة. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | يحصل أو يعيّن ترتيب التبويب للحقل. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value/) { get; set; } | يحصل أو يحدد قيمة حقل خانة الاختيار. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | يقبل الزائر. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption)(string) | يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة على الأكثر في أي وقت. يتم إضافة خانة الاختيار الجديدة إلى أسفل المجموعة. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_1)(string, Rectangle) | يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة على الأكثر في أي وقت. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_2)(string, int, Rectangle) | يضيف خانة اختيار جديدة إلى مجموعة خانات الاختيار، حيث يمكن اختيار خانة واحدة على الأكثر في أي وقت. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone/)() | استنساخ خانة الاختيار. |
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
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | يعيد حساب جميع الحقول المحسوبة في النموذج. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | حدد موضع الحقل. |

## أمثلة

يوضح المثال كيفية إنشاء حقل خانة اختيار متعدد القيم.

```csharp
using (var document = new Document())
{
var page = document.Pages.Add();

var checkbox = new CheckboxField(page, new Rectangle(50, 50, 70, 70));

// تعيين قيمة خيار مجموعة خانات الاختيار الأولى
checkbox.ExportValue = "option 1";

// أضف خيارًا جديدًا مباشرةً تحت الخيارات الحالية
checkbox.AddOption("option 2");

// أضف خيارًا جديدًا في المستطيل المحدد
checkbox.AddOption("option 3", new Rectangle(100, 100, 120, 120));

document.Form.Add(checkbox);

// حدد خانة الاختيار المضافة
checkbox.Value = "option 2";
document.Save("checkbox_group.pdf");
}
```

### انظر أيضًا

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


