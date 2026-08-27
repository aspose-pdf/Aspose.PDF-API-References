---
title: "الأذونات"
linktitle: "الأذونات"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "علم ثنائي. هذا التعداد يمثل أذونات المستخدم لملف pdf."
type: docs
weight: 3830
url: /ar/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

علم ثنائي. هذا التعداد يمثل أذونات المستخدم لملف pdf.

## الحقول

| حقل | الوصف |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (معالجات الأمان للإصدار 3 أو أعلى) تجميع المستند (إدراج، تدوير، أو حذف الصفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان {@code ModifyContent} واضحًا. |
| [ExtractContent](#ExtractContent) | (معالجات الأمان للإصدار 2) نسخ أو استخراج النصوص والرسومات من المستند بأي طريقة، بما في ذلك استخراج النصوص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). (معالجات الأمان للإصدار 3 أو أعلى) نسخ أو استخراج النصوص والرسومات من المستند عبر عمليات غير تلك التي يتحكم فيها {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (معالجات الأمان للإصدار 3 أو أعلى) استخراج النصوص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). |
| [FillForm](#FillForm) | (معالجات الأمان للإصدار 3 أو أعلى) ملء حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كان {@code ModifyTextAnnotations} واضحًا. |
| [ModifyContent](#ModifyContent) | تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها {@code ModifyTextAnnotations}، {@code FillForm}، و 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | إضافة أو تعديل تعليقات النص، ملء حقول النماذج التفاعلية، وإذا كان {@code ModifyContent} مفعلاً أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| [PrintDocument](#PrintDocument) | (معالجات الأمان للإصدار 2) طباعة المستند. (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند (قد لا يكون بأعلى مستوى جودة، حسب ما إذا كان {@code PrintingQuality} مفعلاً أيضًا). |
| [PrintingQuality](#PrintingQuality) | (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما تكون هذه البتة غير مفعلة (والبتة 3 مفعلة)، يكون الطباعة محدودة إلى تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(معالجات الأمان للإصدار 3 أو أعلى) تجميع المستند (إدراج، تدوير، أو حذف الصفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان {@code ModifyContent} واضحًا.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(معالجات الأمان للإصدار 2) نسخ أو استخراج النصوص والرسومات من المستند بأي طريقة، بما في ذلك استخراج النصوص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). (معالجات الأمان للإصدار 3 أو أعلى) نسخ أو استخراج النصوص والرسومات من المستند عبر عمليات غير تلك التي يتحكم فيها {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(معالجات الأمان للإصدار 3 أو أعلى) استخراج النصوص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى).

### FillForm {#FillForm}
```
public static final int FillForm
```

(معالجات الأمان للإصدار 3 أو أعلى) ملء حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كان {@code ModifyTextAnnotations} واضحًا.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها {@code ModifyTextAnnotations}، {@code FillForm}، و 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

إضافة أو تعديل تعليقات النص، ملء حقول النماذج التفاعلية، وإذا كان {@code ModifyContent} مفعلاً أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(معالجات الأمان للإصدار 2) طباعة المستند. (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند (قد لا يكون بأعلى مستوى جودة، حسب ما إذا كان {@code PrintingQuality} مفعلاً أيضًا).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما تكون هذه البتة غير مفعلة (والبتة 3 مفعلة)، يكون الطباعة محدودة إلى تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة.
