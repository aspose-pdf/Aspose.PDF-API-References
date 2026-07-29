---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل مجموعة تسميات الصفحة."
type: docs
weight: 3400
url: /ar/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

فئة تمثل مجموعة تسميات الصفحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLabel](#getLabel-int-) | يحصل على تسمية الصفحة حسب فهرس الصفحة (فهرس الصفحة يبدأ من 0). |
| [getPages](#getPages--) | يحصل على فهارس الصفحات في المجموعة. |
| [removeLabel](#removeLabel-int-) | إزالة التسمية حسب فهرس الصفحة (فهرس الصفحة يبدأ من 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | تحديث التسمية للفهرس المحدد للصفحة (فهرس الصفحة يبدأ من 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

يحصل على تسمية الصفحة حسب فهرس الصفحة (فهرس الصفحة يبدأ من 0).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageIndex |  | فهرس الصفحة. |

**Returns:**
تسمية الصفحة للفهرس المحدد أو null إذا لم توجد تسمية للصفحة.

### getPages {#getPages--}
```
public int[] getPages()
```

يحصل على فهارس الصفحات في المجموعة.

**Returns:**
مصفوفة من الأعداد الصحيحة التي تحتوي على فهارس الصفحات.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

إزالة التسمية حسب فهرس الصفحة (فهرس الصفحة يبدأ من 0).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageIndex |  | فهرس الصفحة التي يجب حذف التسمية منها. |

**Returns:**
true إذا تم تنفيذ العملية بنجاح.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
تحديث التسمية للفهرس المحدد للصفحة (فهرس الصفحة يبدأ من 0).
