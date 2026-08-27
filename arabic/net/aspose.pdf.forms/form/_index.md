---
title: "الفئة Form"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Forms.Form class. فئة تمثل كائن النموذج"
type: docs
weight: 5190
url: /ar/net/aspose.pdf.forms/form/
---
## Form class

الفئة تمثل كائن النموذج.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | إذا تم الضبط، سيتم إعادة حساب جميع حقول النموذج عند تغيير أي حقل. القيمة الافتراضية هي true. اضبطها إلى false لزيادة الأداء عند ملء النموذج بعدد كبير من الحقول المحسوبة. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | إذا تم الضبط، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | يسمح بتعيين ترتيب حساب الحقول. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | يحصل على عدد الحقول في هذا النموذج. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | يحصل أو يعيّن المظهر الافتراضي للنموذج (كائن يصف الخط الافتراضي وحجم النص واللون للحقول في النموذج). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | يحصل على الموارد الافتراضية الموجودة في هذا النموذج. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | إذا كانت هذه الخاصية true، فسيتم رسم مستطيلات حدود حمراء إضافية لحاويات عناصر Xfa exclGroup المطلوبة. تم تقديم هذه الخاصية بسبب عدم وجود نظائر لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى المعيار. القيمة الافتراضية هي false. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | يحصل على قائمة بجميع الحقول في أدنى مستوى من النموذج الهرمي. |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | يحصل على قيمة تشير إلى ما إذا كان المستند يحتوي على نموذج XFA. تم تقديم هذه الخاصية لتحديد ما إذا كان يجب استخدام [`IgnoreNeedsRendering`](./ignoreneedsrendering/) لإزالة نموذج XFA في الحالات التي يكون فيها نموذج XFA موجودًا و[`NeedsRendering`](./needsrendering/) هو false. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | إذا كانت هذه الخاصية true، سيتم تجاهل قيمة المفتاح NeedsRendering أثناء تحويل نموذج XFA إلى النموذج القياسي. القيمة الافتراضية هي false. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | يرجع true إذا كان الكائن thread-safe. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | يحصل على حقل النموذج بواسطة اسم الحقل. يرمي استثناء إذا لم يتم العثور على الحقل. (2 indexers) |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | يحصل على قيمة تشير إلى ما إذا كان المستند يتطلب إزالة نموذج XFA الديناميكي. تم تقديم هذه الخاصية لتحديد ما إذا كان يجب استخدام [`IgnoreNeedsRendering`](./ignoreneedsrendering/) لإزالة نموذج XFA في الحالات التي يكون فيها نموذج XFA موجودًا و[`NeedsRendering`](./needsrendering/) غير صحيح. |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | إذا كانت هذه الخاصية صحيحة، سيتم إزالة القاموس "Perms" من مستند pdf بعد تحويل المستندات الديناميكية إلى قياسية. قد يحتوي القاموس "Perms" على قواعد تعيق عرض اختيار الحقول الإلزامية في قارئ Adobe Acrobat. القيمة الافتراضية هي false. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | إذا تم تعيينها، يحتوي المستند على توقيعات قد تصبح غير صالحة إذا تم حفظ (كتابة) الملف بطريقة تغير محتوياته السابقة، بدلاً من تحديث تدريجي. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | إذا تم تعيينها، يحتوي المستند على حقل توقيع واحد على الأقل. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | يعيد كائن المزامنة. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | يحصل على نوع النموذج. القيم الممكنة هي: Standard، Static، Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | يحصل على بيانات XFA للنموذج (إذا كانت موجودة). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | يضيف حقلًا إلى النموذج. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | يضيف حقلًا إلى النموذج. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | يضيف حقلًا جديدًا إلى النموذج؛ إذا كان هذا الحقل موجودًا بالفعل على نموذج آخر أو هذا النموذج، يتم إنشاء نسخة من الحقل. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | يضيف مظهرًا إضافيًا للحقل إلى الصفحة المحددة من المستند في الموقع المحدد. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | يضبط XFA للنموذج إلى القيمة المحددة. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | ينسخ الحقول الموجودة على النموذج إلى مصفوفة. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | احذف الحقل من النموذج. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | يحذف الحقل من النموذج بناءً على اسمه. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | يصدّر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الدفق المقدم. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | يصدّر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | يزيل جميع حقول النموذج ويضع قيمها مباشرة على الصفحة. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | يحصل على تعداد حقول النموذج. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | يعيد الحقول داخل المستطيل المحدد. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج، مع القدرة على النظر في تسلسل هرمي للأطفال من الحقول. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | يستورد حقول نموذج PDF من تنسيق JSON المقدم في الدفق. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | يستورد حقول نموذج PDF من تنسيق JSON المقدم في الملف المحدد. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | يجعل تعليقات حقول النموذج مستقلة. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | يزيل مظهر الحقل عند الفهرس المحدد. إذا تبقى مظهر طفل واحد فقط، تقوم الطريقة بدمجه في الحقل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | يمكن للنماذج أن تحتوي على معلومات توقيع، أي يمكن أن تكون موقعة أو غير موقعة. وأحيانًا يجب أن يعتمد عرض النموذج على ما إذا كان النموذج موقّعًا أم لا. هذه الخاصية تخبر محول النموذج (مثلاً أثناء تحويل نموذج XFA إلى نموذج قياسي) ما إذا كان يجب عرض النموذج الناتج كملّـم أو غير موقّع. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | الفئة التي تصف إعدادات إجراء تسطيح النموذج. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | يمكن للنماذج أن تحتوي على معلومات توقيع ويمكن أن تكون موقعة أو غير موقعة. أحيانًا يجب أن يعتمد عرض النماذج في العارض على ما إذا كان النموذج موقّعًا أم لا. هذا التعداد يحدد أوضاع العرض الممكنة أثناء تحويل نوع النموذج بالنسبة للتوقيع. |

### انظر أيضًا

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


