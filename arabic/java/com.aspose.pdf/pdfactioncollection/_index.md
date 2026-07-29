---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تصف قائمة الإجراءات."
type: docs
weight: 3680
url: /ar/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

الفئة تصف قائمة الإجراءات.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | أضف الإجراء إلى قائمة الإجراءات. |
| [delete](#delete-int-) | إزالة الإجراء حسب الفهرس. |
| [get_Item](#get_Item-int-) | يحصل على الإجراء حسب فهرسه. |
| [getCount](#getCount--) | يحصل على عدد الإجراءات. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | طريقة داخلية |
| [iterator](#iterator--) | يحصل على المُعدِّد. |

### add {#add-com.aspose.pdf.PdfAction-}
أضف الإجراء إلى قائمة الإجراءات.

### delete {#delete-int-}
```
public void delete(int index)
```

إزالة الإجراء حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الإجراء للإزالة. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

يحصل على الإجراء حسب فهرسه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة فهرس الإجراء. |

**Returns:**
فهرس PdfAction إذا تم العثور عليه؛ وإلا، يرمي @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

يحصل على عدد الإجراءات.

**Returns:**
قيمة int

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

طريقة داخلية

**Returns:**
كائن داخلي.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

يحصل على المُعدِّد.

**Returns:**
مُعدِّد PDfAction.
