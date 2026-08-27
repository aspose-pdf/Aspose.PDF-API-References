---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة عنصر مجموعة. يحتوي عنصر المجموعة على البيانات الموصوفة في مخطط المجموعة."
type: docs
weight: 640
url: /ar/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

يمثل فئة عنصر مجموعة. يحتوي عنصر المجموعة على البيانات الموصوفة في مخطط المجموعة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAllNames](#getAllNames--) | يحصل على مجموعة من جميع أسماء قيم عنصر التجميع. |
| [hasName](#hasName-java.lang.String-) | يتحقق مما إذا كان الاسم المحدد موجودًا في عنصر التجميع. |
| [isEmpty](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان عنصر التجميع فارغًا. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | يحاول الحصول على القيمة من نوع DateTime من عنصر التجميع بالاسم المحدد. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | يحاول الحصول على القيمة المزدوجة للاسم المحدد من عنصر التجميع. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | يحاول الحصول على القيمة الصحيحة لاسم محدد من عنصر التجميع. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | يحاول الحصول على القيمة النصية بالاسم المحدد من عنصر التجميع. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

يحصل على مجموعة من جميع أسماء قيم عنصر التجميع.

**Returns:**
قائمة من String

### hasName {#hasName-java.lang.String-}
يتحقق مما إذا كان الاسم المحدد موجودًا في عنصر التجميع.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

يحصل على قيمة تشير إلى ما إذا كان عنصر التجميع فارغًا.

**Returns:**
صحيح إذا كان عنصر التجميع فارغًا؛ وإلا، خطأ. تُعيد هذه الخاصية true إذا لم يحتوي عنصر التجميع على أي قيم، بما في ذلك قيم السلاسل النصية، والقيم المزدوجة، والقيم الصحيحة، وقيم التاريخ. إذا كان أي من هذه الأنواع من القيم موجودًا في عنصر التجميع، تُعيد هذه الخاصية false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
يحاول الحصول على القيمة من نوع DateTime من عنصر التجميع بالاسم المحدد.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
يحاول الحصول على القيمة المزدوجة للاسم المحدد من عنصر التجميع.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
يحاول الحصول على القيمة الصحيحة لاسم محدد من عنصر التجميع.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
يحاول الحصول على القيمة النصية بالاسم المحدد من عنصر التجميع.
