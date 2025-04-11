---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Forms.Form. فئة تمثل كائن النموذج
type: docs
weight: 5070
url: /ar/net/aspose.pdf.forms/form/
---
## فئة النموذج

فئة تمثل كائن النموذج.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | إذا تم تعيينه، سيتم إعادة حساب جميع حقول النموذج عند تغيير أي حقل. القيمة الافتراضية هي true. تعيينها إلى false لزيادة الأداء عند ملء النموذج بكمية كبيرة من الحقول المحسوبة. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | إذا تم تعيينه، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | يسمح بتعيين ترتيب حساب الحقول. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | يحصل على عدد الحقول في هذا النموذج. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | يحصل على أو يحدد المظهر الافتراضي للنموذج (كائن يصف الخط الافتراضي، حجم النص ولونه للحقول في النموذج). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | يحصل على الموارد الافتراضية الموضوعة على هذا النموذج. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | إذا كانت هذه الخاصية true، فسيتم رسم مستطيلات حدود حمراء إضافية لعناصر exclGroup المطلوبة. تم تقديم هذه الخاصية بسبب عدم وجود نظائر لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى معيار. القيمة الافتراضية هي false. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | يحصل على قائمة بجميع الحقول في أدنى مستوى من النموذج الهيكلي. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | إذا كانت هذه الخاصية true، فسيتم تجاهل قيمة مفتاح NeedsRendering أثناء تحويل نموذج XFA إلى نموذج قياسي. القيمة الافتراضية هي false. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | يرجع true إذا كان الكائن آمنًا للخيوط. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | يحصل على حقل النموذج بواسطة اسم الحقل. يثير استثناء إذا لم يتم العثور على الحقل. (2 فهارس) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | إذا كانت هذه الخاصية true، فسيتم إزالة قاموس "Perms" من مستند PDF بعد تحويل المستندات الديناميكية إلى معيار. يمكن أن يحتوي قاموس "Perms" على قواعد تعيق عرض اختيار الحقول الإلزامية في قارئ Adobe Acrobat. القيمة الافتراضية هي false. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | إذا تم تعيينه، يحتوي المستند على توقيعات قد يتم إبطالها إذا تم حفظ (كتابة) الملف بطريقة تغير محتوياته السابقة، على عكس التحديث التزايدي. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | إذا تم تعيينه، يحتوي المستند على حقل توقيع واحد على الأقل. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | يرجع كائن المزامنة. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | يحصل على نوع النموذج. القيم الممكنة هي: قياسي، ثابت، ديناميكي. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | يحصل على بيانات XFA للنموذج (إذا كانت موجودة). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | يضيف حقلًا إلى النموذج. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | يضيف حقلًا إلى النموذج. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | يضيف حقلًا جديدًا إلى النموذج؛ إذا كان هذا الحقل موجودًا بالفعل في نموذج آخر أو هذا النموذج، يتم إنشاء نسخة من الحقل. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | يضيف مظهرًا إضافيًا للحقل إلى الصفحة المحددة من المستند في الموقع المحدد. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | يحدد XFA للنموذج إلى القيمة المحددة. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | ينسخ الحقول الموضوعة على النموذج إلى مصفوفة. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | يحذف حقلًا من النموذج. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | يحذف حقلًا من النموذج بواسطة اسمه. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | يصدر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى التدفق المقدم. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | يصدر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | يزيل جميع حقول النموذج ويضع قيمها مباشرة على الصفحة. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | يحصل على تعداد لحقول النموذج. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | يرجع الحقول داخل المستطيل المحدد. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | يتحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | يحدد ما إذا كان الحقل بالاسم المحدد قد أضيف بالفعل إلى النموذج. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | يحدد ما إذا كان الحقل بالاسم المحدد قد أضيف بالفعل إلى النموذج، مع القدرة على النظر في تسلسل الحقول الفرعية. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | يستورد حقول نموذج PDF من تنسيق JSON المقدم في التدفق. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | يستورد حقول نموذج PDF من تنسيق JSON المقدم في الملف المحدد. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | يجعل تعليقات حقول النموذج مستقلة. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | يزيل مظهر الحقل في الفهرس المحدد. إذا تبقى مظهر واحد فقط، يقوم الأسلوب بإدماجه في الحقل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | يمكن أن تحتوي النماذج على معلومات توقيع، أي يمكن أن تكون موقعة أو غير موقعة. وأحيانًا يجب أن يعتمد عرض النموذج على ما إذا كان النموذج موقّعًا أم لا. تخبر هذه الخاصية محول النموذج (على سبيل المثال، أثناء تحويل نموذج XFA إلى نموذج قياسي) ما إذا كان يجب عرض النموذج الناتج كموقع أو غير موقع. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | فئة تصف الإعدادات لإجراء تسطيح النموذج. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | يمكن أن تحتوي النماذج على معلومات توقيع ويمكن أن تكون موقعة أو غير موقعة. أحيانًا يجب أن يعتمد عرض النماذج في العارض على ما إذا كان النموذج موقّعًا أم لا. يقوم هذا التعداد بإدراج أوضاع العرض الممكنة أثناء تحويل نوع النموذج فيما يتعلق بالتوقيع. |

### انظر أيضًا

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)