---
title: "نموذج"
linktitle: "نموذج"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل كائن النموذج."
type: docs
weight: 1740
url: /ar/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

فئة تمثل كائن النموذج.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | يضيف حقلًا إلى النموذج. |
| [add](#add-com.aspose.pdf.Field-int-) | يضيف حقلًا إلى النموذج. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | يضيف حقلًا جديدًا إلى النموذج؛ إذا كان هذا الحقل موجودًا بالفعل على نموذج آخر أو هذا النموذج، يتم إنشاء نسخة من الحقل. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | يضيف حقلًا إلى النموذج. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | يضيف مظهرًا إضافيًا للحقل إلى الصفحة المحددة من المستند في الموقع المحدد. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | يضيف مظهرًا إضافيًا للحقل إلى الصفحة المحددة من المستند. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | يضبط XFA للنموذج إلى القيمة المحددة. |
| [clear](#clear--) | يحذف جميع الحقول من النموذج. غير مدعوم. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | يحدد ما إذا كان الحقل موجودًا في النموذج.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | ينسخ الحقول الموجودة في النموذج إلى مصفوفة. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | ينسخ حقول النموذج إلى مصفوفة. |
| [delete](#delete-com.aspose.pdf.Field-) | احذف الحقل من النموذج. |
| [delete](#delete-java.lang.String-) | يحذف الحقل من النموذج وفقًا لاسمه. |
| [flatten](#flatten--) | يزيل جميع حقول النموذج الثابتة ويضع قيمها مباشرة على الصفحة. |
| [get_Item](#get_Item-int-) | يحصل على حقل النموذج وفقًا لمؤشر الحقل. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على حقل النموذج وفقًا لاسم الحقل. يرمي استثناءً إذا لم يتم العثور على الحقل. |
| [get_xfa](#get_xfa--) | للاستخدام الداخلي فقط |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | يبحث عن الحقل وفقًا لاسم الحقل. يرجع null إذا لم يتم العثور على الحقل. |
| [getAutoRecalculate](#getAutoRecalculate--) | إذا تم الضبط، سيتم إعادة حساب جميع حقول النموذج عندما يتغير أي حقل. القيمة الافتراضية هي true. اضبطها على false لزيادة الأداء عند ملء النموذج بكمية كبيرة من الحقول المحسوبة. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | إذا تم الضبط، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية. |
| [getDefaultAppearance](#getDefaultAppearance--) | يحصل على المظهر الافتراضي للنموذج (كائن يصف الخط الافتراضي، حجم النص واللون للحقول في النموذج). |
| [getDefaultResources](#getDefaultResources--) | يحصل على الموارد الافتراضية الموضوعة على هذا النموذج. |
| [getDocument](#getDocument--) | للاستخدام الداخلي فقط |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | إذا كانت هذه الخاصية true فسيتم رسم مستطيلات حدود حمراء إضافية لعناصر حاويات Xfa exclGroup المطلوبة. تم تقديم هذه الخاصية لأن عدم وجود تماثلات لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى المعيار. تكون false بشكل افتراضي. |
| [getFields](#getFields--) | يحصل على قائمة بجميع الحقول في أدنى مستوى من النموذج الهرمي. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | يرجع الحقول داخل المستطيل المحدد. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | إذا كانت هذه الخاصية true فسيتم تجاهل قيمة المفتاح NeedsRendering أثناء تحويل نموذج XFA إلى نموذج Standard. تكون false بشكل افتراضي. |
| [getNeedsRendering](#getNeedsRendering--) | يحصل على قيمة تشير إلى ما إذا كان المستند يتطلب إزالة نموذج XFA الديناميكي. تم تقديم هذه الخاصية لتحديد ما إذا كان يجب استخدام {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) لإزالة نموذج XFA في الحالات التي يكون فيها نموذج XFA موجودًا و {@code NeedsRendering}({@link #getNeedsRendering}) هو false. |
| [getRemovePermission](#getRemovePermission--) | إذا كانت هذه الخاصية true فسيتم إزالة القاموس "Perms" من مستند pdf بعد تحويل المستندات الديناميكية إلى معيار. قد يحتوي القاموس "Perms" على قواعد تعيق عرض اختيار الحقول الإلزامية في قارئ Adobe Acrobat. تكون false بشكل افتراضي. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | إذا تم التعيين، يحتوي المستند على توقيعات قد تُبطل إذا تم حفظ الملف (كتابة) بطريقة تغير محتوياته السابقة، بدلاً من تحديث تدريجي. |
| [getSignaturesExist](#getSignaturesExist--) | إذا تم التعيين، يحتوي المستند على حقل توقيع واحد على الأقل. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | يمكن للنماذج أن تحتوي على معلومات توقيع، أي يمكن أن تكون موقعة أو غير موقعة. وأحيانًا يجب أن تعتمد عرض النموذج على ما إذا كان النموذج موقعًا أم لا. تخبر هذه الخاصية محول النموذج (مثلاً أثناء تحويل نموذج XFA إلى نموذج Standard) ما إذا كان يجب عرض النموذج الناتج كموقع أو كغير موقع. |
| [getSyncRoot](#getSyncRoot--) | يرجع كائن المزامنة. |
| [getType](#getType--) | يحصل على نوع النموذج. القيم الممكنة هي: Standard، Static، Dynamic. |
| [getXFA](#getXFA--) | يحصل على بيانات XFA للنموذج (إذا كانت موجودة). |
| [hasField](#hasField-com.aspose.pdf.Field-) | تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد. |
| [hasField](#hasField-java.lang.String-) | يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج. |
| [hasField](#hasField-java.lang.String-boolean-) | يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج، مع القدرة على البحث في تسلسل هرمي للأطفال من الحقول. |
| [hasXfa](#hasXfa--) | يحصل على قيمة تشير إلى ما إذا كان المستند يحتوي على نموذج XFA. تم تقديم هذه الخاصية لتحديد ما إذا كان يجب استخدام {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) لإزالة نموذج XFA في الحالات التي يكون فيها نموذج XFA موجودًا و {@code NeedsRendering}({@link #getNeedsRendering}) هو false. |
| [isReadOnly](#isReadOnly--) | يحدد ما إذا كانت المجموعة للقراءة فقط. دائمًا يرجع false. |
| [isSynchronized](#isSynchronized--) | يرجع true إذا كان الكائن آمنًا للاستخدام متعدد الخيوط. |
| [iterator](#iterator--) | يحصل على تعداد حقول النموذج. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * يصدّر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الدفق المقدم. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | يحذف الحقل من النموذج. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | يزيل مظهر الحقل عند الفهرس المحدد. إذا بقي مظهر طفل واحد فقط، تقوم الطريقة بدمجه في الحقل. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | إذا تم الضبط، سيتم إعادة حساب جميع حقول النموذج عندما يتغير أي حقل. القيمة الافتراضية هي true. اضبطها على false لزيادة الأداء عند ملء النموذج بكمية كبيرة من الحقول المحسوبة. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | إذا تم الضبط، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | يسمح بتعيين ترتيب حساب الحقل. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | يضبط المظهر الافتراضي للنموذج (كائن يصف الخط الافتراضي وحجم النص واللون للحقول على النموذج). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | إذا كانت هذه الخاصية true فسيتم رسم مستطيلات حدود حمراء إضافية لعناصر حاويات Xfa exclGroup المطلوبة. تم تقديم هذه الخاصية لأن عدم وجود تماثلات لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى المعيار. تكون false بشكل افتراضي. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | إذا كانت هذه الخاصية true فسيتم تجاهل قيمة المفتاح NeedsRendering أثناء تحويل نموذج XFA إلى نموذج Standard. تكون false بشكل افتراضي. |
| [setRemovePermission](#setRemovePermission-boolean-) | إذا كانت هذه الخاصية true فسيتم إزالة القاموس "Perms" من مستند pdf بعد تحويل المستندات الديناميكية إلى معيار. قد يحتوي القاموس "Perms" على قواعد تعيق عرض اختيار الحقول الإلزامية في قارئ Adobe Acrobat. تكون false بشكل افتراضي. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | إذا تم التعيين، يحتوي المستند على توقيعات قد تُبطل إذا تم حفظ الملف (كتابة) بطريقة تغير محتوياته السابقة، بدلاً من تحديث تدريجي. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | إذا تم التعيين، يحتوي المستند على حقل توقيع واحد على الأقل. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | يمكن للنماذج أن تحتوي على معلومات توقيع، أي يمكن أن تكون موقعة أو غير موقعة. وأحيانًا يجب أن تعتمد عرض النموذج على ما إذا كان النموذج موقعًا أم لا. تخبر هذه الخاصية محول النموذج (مثلاً أثناء تحويل نموذج XFA إلى نموذج Standard) ما إذا كان يجب عرض النموذج الناتج كموقع أو كغير موقع. |
| [setType](#setType-com.aspose.pdf.FormType-) | يحصل على نوع النموذج. القيم الممكنة هي: Standard، Static، Dynamic. |
| [size](#size--) | يحصل على عدد الحقول في هذا النموذج. |

### Form {#Form-com.aspose.pdf.IDocument-}
منشئ

### add {#add-com.aspose.pdf.Field-}
يضيف حقلًا إلى النموذج.

### add {#add-com.aspose.pdf.Field-int-}
يضيف حقلًا إلى النموذج.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
يضيف حقلًا جديدًا إلى النموذج؛ إذا كان هذا الحقل موجودًا بالفعل على نموذج آخر أو هذا النموذج، يتم إنشاء نسخة من الحقل.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
يضيف حقلًا إلى النموذج.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
يضيف مظهرًا إضافيًا للحقل إلى الصفحة المحددة من المستند في الموقع المحدد.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
يضيف مظهرًا إضافيًا للحقل إلى الصفحة المحددة من المستند.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
يضبط XFA للنموذج إلى القيمة المحددة.

### clear {#clear--}
```
public void clear()
```

يحذف جميع الحقول من النموذج. غير مدعوم.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
يحدد ما إذا كان الحقل موجودًا في النموذج..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
ينسخ الحقول الموجودة في النموذج إلى مصفوفة.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
ينسخ حقول النموذج إلى مصفوفة.

### delete {#delete-com.aspose.pdf.Field-}
احذف الحقل من النموذج.

### delete {#delete-java.lang.String-}
يحذف الحقل من النموذج وفقًا لاسمه.

### flatten {#flatten--}
```
public void flatten()
```

يزيل جميع حقول النموذج الثابتة ويضع قيمها مباشرة على الصفحة.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

يحصل على حقل النموذج وفقًا لمؤشر الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الحقل. |

**Returns:**
الحقل المسترجع.

### get_Item {#get_Item-java.lang.String-}
يحصل على حقل النموذج وفقًا لاسم الحقل. يرمي استثناءً إذا لم يتم العثور على الحقل.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

للاستخدام الداخلي فقط

**Returns:**
كائن XFA

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
يبحث عن الحقل وفقًا لاسم الحقل. يرجع null إذا لم يتم العثور على الحقل.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

إذا تم الضبط، سيتم إعادة حساب جميع حقول النموذج عندما يتغير أي حقل. القيمة الافتراضية هي true. اضبطها على false لزيادة الأداء عند ملء النموذج بكمية كبيرة من الحقول المحسوبة.

**Returns:**
قيمة منطقية

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

إذا تم الضبط، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية.

**Returns:**
قيمة منطقية

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

يحصل على المظهر الافتراضي للنموذج (كائن يصف الخط الافتراضي، حجم النص واللون للحقول في النموذج).

**Returns:**
كائن DefaultAppearance

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

يحصل على الموارد الافتراضية الموضوعة على هذا النموذج.

**Returns:**
قيمة الموارد.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

للاستخدام الداخلي فقط

**Returns:**
كائن IDocument

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

إذا كانت هذه الخاصية true فسيتم رسم مستطيلات حدود حمراء إضافية لعناصر حاويات Xfa exclGroup المطلوبة. تم تقديم هذه الخاصية لأن عدم وجود تماثلات لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى المعيار. تكون false بشكل افتراضي.

**Returns:**
قيمة منطقية

### getFields {#getFields--}
```
public Field [] getFields()
```

يحصل على قائمة بجميع الحقول في أدنى مستوى من النموذج الهرمي.

**Returns:**
مصفوفة تحتوي على الحقول الموجودة.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
يرجع الحقول داخل المستطيل المحدد.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

إذا كانت هذه الخاصية true فسيتم تجاهل قيمة المفتاح NeedsRendering أثناء تحويل نموذج XFA إلى نموذج Standard. تكون false بشكل افتراضي.

**Returns:**
قيمة منطقية

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

يحصل على قيمة تشير إلى ما إذا كان المستند يتطلب إزالة نموذج XFA الديناميكي. تم تقديم هذه الخاصية لتحديد ما إذا كان يجب استخدام {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) لإزالة نموذج XFA في الحالات التي يكون فيها نموذج XFA موجودًا و {@code NeedsRendering}({@link #getNeedsRendering}) هو false.

**Returns:**
قيمة منطقية

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

إذا كانت هذه الخاصية true فسيتم إزالة القاموس "Perms" من مستند pdf بعد تحويل المستندات الديناميكية إلى معيار. قد يحتوي القاموس "Perms" على قواعد تعيق عرض اختيار الحقول الإلزامية في قارئ Adobe Acrobat. تكون false بشكل افتراضي.

**Returns:**
قيمة منطقية

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

إذا تم التعيين، يحتوي المستند على توقيعات قد تُبطل إذا تم حفظ الملف (كتابة) بطريقة تغير محتوياته السابقة، بدلاً من تحديث تدريجي.

**Returns:**
قيمة منطقية

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

إذا تم التعيين، يحتوي المستند على حقل توقيع واحد على الأقل.

**Returns:**
قيمة منطقية

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

يمكن للنماذج أن تحتوي على معلومات توقيع، أي يمكن أن تكون موقعة أو غير موقعة. وأحيانًا يجب أن تعتمد عرض النموذج على ما إذا كان النموذج موقعًا أم لا. تخبر هذه الخاصية محول النموذج (مثلاً أثناء تحويل نموذج XFA إلى نموذج Standard) ما إذا كان يجب عرض النموذج الناتج كموقع أو كغير موقع.

**Returns:**
عنصر SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يرجع كائن المزامنة.

**Returns:**
كائن للمزامنة

### getType {#getType--}
```
public FormType getType()
```

يحصل على نوع النموذج. القيم الممكنة هي: Standard، Static، Dynamic.

**Returns:**
قيمة FormType @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

يحصل على بيانات XFA للنموذج (إذا كانت موجودة).

**Returns:**
قيمة XFA

### hasField {#hasField-com.aspose.pdf.Field-}
تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد.

### hasField {#hasField-java.lang.String-}
يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج.

### hasField {#hasField-java.lang.String-boolean-}
يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج، مع القدرة على البحث في تسلسل هرمي للأطفال من الحقول.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

يحصل على قيمة تشير إلى ما إذا كان المستند يحتوي على نموذج XFA. تم تقديم هذه الخاصية لتحديد ما إذا كان يجب استخدام {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) لإزالة نموذج XFA في الحالات التي يكون فيها نموذج XFA موجودًا و {@code NeedsRendering}({@link #getNeedsRendering}) هو false.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحدد ما إذا كانت المجموعة للقراءة فقط. دائمًا يرجع false.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يرجع true إذا كان الكائن آمنًا للاستخدام متعدد الخيوط.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

يحصل على تعداد حقول النموذج.

**Returns:**
عداد الحقول.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * يصدّر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الدفق المقدم. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
يحذف الحقل من النموذج.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
يزيل مظهر الحقل عند الفهرس المحدد. إذا بقي مظهر طفل واحد فقط، تقوم الطريقة بدمجه في الحقل.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

إذا تم الضبط، سيتم إعادة حساب جميع حقول النموذج عندما يتغير أي حقل. القيمة الافتراضية هي true. اضبطها على false لزيادة الأداء عند ملء النموذج بكمية كبيرة من الحقول المحسوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

إذا تم الضبط، سيتم إنشاء حقول النموذج الغائبة تلقائيًا إذا كانت موجودة في التعليقات التوضيحية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
يسمح بتعيين ترتيب حساب الحقل.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
يضبط المظهر الافتراضي للنموذج (كائن يصف الخط الافتراضي وحجم النص واللون للحقول على النموذج).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

إذا كانت هذه الخاصية true فسيتم رسم مستطيلات حدود حمراء إضافية لعناصر حاويات Xfa exclGroup المطلوبة. تم تقديم هذه الخاصية لأن عدم وجود تماثلات لـ exclGroup أثناء تحويل تمثيل Xfa للنماذج إلى المعيار. تكون false بشكل افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

إذا كانت هذه الخاصية true فسيتم تجاهل قيمة المفتاح NeedsRendering أثناء تحويل نموذج XFA إلى نموذج Standard. تكون false بشكل افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

إذا كانت هذه الخاصية true فسيتم إزالة القاموس "Perms" من مستند pdf بعد تحويل المستندات الديناميكية إلى معيار. قد يحتوي القاموس "Perms" على قواعد تعيق عرض اختيار الحقول الإلزامية في قارئ Adobe Acrobat. تكون false بشكل افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

إذا تم التعيين، يحتوي المستند على توقيعات قد تُبطل إذا تم حفظ الملف (كتابة) بطريقة تغير محتوياته السابقة، بدلاً من تحديث تدريجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

إذا تم التعيين، يحتوي المستند على حقل توقيع واحد على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

يمكن للنماذج أن تحتوي على معلومات توقيع، أي يمكن أن تكون موقعة أو غير موقعة. وأحيانًا يجب أن تعتمد عرض النموذج على ما إذا كان النموذج موقعًا أم لا. تخبر هذه الخاصية محول النموذج (مثلاً أثناء تحويل نموذج XFA إلى نموذج Standard) ما إذا كان يجب عرض النموذج الناتج كموقع أو كغير موقع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | عنصر SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
يحصل على نوع النموذج. القيم الممكنة هي: Standard، Static، Dynamic.

### size {#size--}
```
public final int size()
```

يحصل على عدد الحقول في هذا النموذج.

**Returns:**
قيمة int
