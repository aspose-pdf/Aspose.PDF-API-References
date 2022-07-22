---
title: Form
second_title: Aspose.PDF لمرجع .NET API
description: فئة تمثل كائن النموذج .
type: docs
weight: 3020
url: /ar/net/aspose.pdf.forms/form/
---
## Form class

فئة تمثل كائن النموذج .

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | في حالة التعيين ، ستتم إعادة حساب جميع حقول النموذج عند تغيير أي حقل. القيمة الافتراضية صحيحة. قم بالتعيين على خطأ من أجل زيادة الأداء عند ملء النموذج بكمية كبيرة من الحقول المحسوبة. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | في حالة التعيين ، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | يسمح بتعيين ترتيب حساب الحقل. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | الحصول على عدد الحقول في هذا النموذج . |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | الحصول على المظهر الافتراضي للنموذج أو تعيينه (الكائن الذي يصف الخط الافتراضي وحجم النص واللون للحقول الموجودة في النموذج). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | الحصول على الموارد الافتراضية الموضوعة في هذا النموذج . |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | إذا كانت هذه الخاصية صحيحة ، فسيتم رسم مستطيلات إضافية للحدود الحمراء لعناصر Xfa exclGroup المطلوبة حاويات تم تقديم هذه الخاصية بسبب غياب نظائرها لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى معيار . إنها خاطئة افتراضيًا . |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | الحصول على قائمة بجميع الحقول في أدنى مستوى من الشكل الهرمي. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | إذا كانت هذه الخاصية صحيحة ، فسيتم تجاهل قيمة مفتاح NeedsRendering أثناء تحويل نموذج XFA إلى نموذج قياسي. إنه خطأ افتراضيًا. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | إرجاع صحيح إذا كان الكائن آمنًا لمؤشر الترابط . |
| [Item](../../aspose.pdf.forms/form/item) { get; } | يحصل على حقل النموذج حسب اسم الحقل. يلقي استثناء إذا لم يتم العثور على الحقل . (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | إذا كانت هذه الخاصية صحيحة ، فستتم إزالة قاموس "Perms" من مستند pdf بعد تحويل المستندات الديناميكية إلى المعيار. يمكن أن يحتوي قاموس "Perms" على قواعد تزعج عرض اختيار الحقول الإلزامية في Adobe Acrobat reader . وهي خاطئة افتراضيًا. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | في حالة الضبط ، يحتوي المستند على توقيعات قد يتم إبطال مفعولها إذا تم حفظ الملف (مكتوبًا) بطريقة تغير محتوياته السابقة ، بدلاً من التحديث المتزايد. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | في حالة الضبط ، يحتوي المستند على حقل توقيع واحد على الأقل. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | إرجاع كائن المزامنة . |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | يحصل على نوع النموذج. القيم المحتملة هي: قياسي ، ثابت ، ديناميكي . |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | الحصول على بيانات XFA بالنموذج (إذا كان موجودًا) . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | يضيف حقل على النموذج . |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | يضيف حقل على النموذج . |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | إضافة حقل جديد إلى النموذج إذا تم وضع هذا الحقل بالفعل في نموذج آخر أو هذا النموذج ، فسيتم إنشاء نسخة الحقل. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | يضيف مظهرًا إضافيًا للحقل إلى صفحة محددة من المستند في الموقع المحدد. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | يعين XFA للنموذج على القيمة المحددة. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | نسخ الحقول الموضوعة على النموذج في المصفوفة. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | حذف الحقل من النموذج . |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | حذف الحقل من النموذج باسمه . |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | يزيل كل حقول النموذج ويضع قيمها مباشرة على الصفحة. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | الحصول على تعداد لحقول النموذج. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | إرجاع الحقول داخل المستطيل المحدد. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | تحقق مما إذا كان النموذج يحتوي بالفعل على حقل محدد. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | يحدد ما إذا كان الحقل الذي يحمل الاسم المحدد قد تمت إضافته بالفعل إلى النموذج. |

## مجالات

| اسم | وصف |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | يمكن أن تحتوي النماذج على معلومات توقيع ، أي يمكن توقيعها أو عدم توقيعها. ويجب أن يعتمد عرض النموذج أحيانًا على ما إذا كان النموذج موقّعًا أم لا. يجب تقديمها كموقع أو بدون توقيع. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | فئة تصف إعدادات إجراء تسوية النموذج. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | يمكن أن تحتوي النماذج على معلومات توقيع ويمكن توقيعها أو عدم توقيعها. في بعض الأحيان يجب أن يعتمد عرض النماذج في العارض على ما إذا كان النموذج موقّعًا أم لا. يعدد هذا التعداد أوضاع العرض الممكنة أثناء تحويل نوع النموذج فيما يتعلق بالتوقيع. |

### أنظر أيضا

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* مساحة الاسم [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
