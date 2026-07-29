---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل الأحداث."
type: docs
weight: 740
url: /ar/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

فئة تمثل الأحداث.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-T-) | أضف مفوضًا آخر. |
| [assign](#assign-T-) | أضف المفوض الحالي فقط، مع مسح الآخرين. |
| [clear](#clear--) | مسح قائمة المفوضين |
| [isEmpty](#isEmpty--) | يرجع true إذا كانت قائمة المعالجات فارغة |
| [remove](#remove-T-) | حذف delegate من القائمة |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

أضف مفوضًا آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| delegate |  | كائن Handlers |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

أضف المفوض الحالي فقط، مع مسح الآخرين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| delegate |  | كائن Handlers |

### clear {#clear--}
```
public final void clear()
```

مسح قائمة المفوضين

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

يرجع true إذا كانت قائمة المعالجات فارغة

**Returns:**
قيمة منطقية

### remove {#remove-T-}
```
public final void remove( T delegate)
```

حذف delegate من القائمة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| delegate |  | كائن Handlers |
