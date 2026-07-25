---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تنسيق رقم الصفحة الذي يتضمن فهرسًا وإجمالي عدد الصفحات وفاصلًا."
type: docs
weight: 150
url: /ar/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

يمثل تنسيق رقم الصفحة الذي يتضمن فهرسًا وإجمالي عدد الصفحات وفاصلًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDelimiter](#getDelimiter--) | يحصل أو يضبط الفاصل المستخدم في تنسيق رقم الصفحة. سيتم تحديث السلسلة المنسقة بناءً على الفاصل المحدد. |
| [getIndex](#getIndex--) | يحصل أو يضبط مكوّن فهرس الصفحة في تنسيق رقم الصفحة. ستتضمن السلسلة المنسقة عنصرًا نائبًا لفهرس الصفحة. |
| [getOffset](#getOffset--) | يحصل أو يضبط الإزاحة التي ستُضاف إلى فهرس الصفحة. |
| [getPageNumberString](#getPageNumberString-int-int-) | يرجع سلسلة منسقة تمثل رقم الصفحة بناءً على الإعدادات الحالية. |
| [getTotalNum](#getTotalNum--) | يحصل أو يضبط مكوّن إجمالي عدد الصفحات في تنسيق رقم الصفحة. ستتضمن السلسلة المنسقة عنصرًا نائبًا لإجمالي عدد الصفحات. |
| [setDelimiter](#setDelimiter-java.lang.String-) | يحصل أو يضبط الفاصل المستخدم في تنسيق رقم الصفحة. سيتم تحديث السلسلة المنسقة بناءً على الفاصل المحدد. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | يحصل أو يضبط مكوّن فهرس الصفحة في تنسيق رقم الصفحة. |
| [setOffset](#setOffset-int-) | يحصل أو يضبط الإزاحة التي ستُضاف إلى فهرس الصفحة. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | يحصل أو يضبط مكوّن إجمالي عدد الصفحات في تنسيق رقم الصفحة. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

يحصل أو يضبط الفاصل المستخدم في تنسيق رقم الصفحة. سيتم تحديث السلسلة المنسقة بناءً على الفاصل المحدد.

**Returns:**
قيمة سلسلة

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

يحصل أو يضبط مكوّن فهرس الصفحة في تنسيق رقم الصفحة. ستتضمن السلسلة المنسقة عنصرًا نائبًا لفهرس الصفحة.

**Returns:**
مثيل PageIndex

### getOffset {#getOffset--}
```
public final int getOffset()
```

يحصل أو يضبط الإزاحة التي ستُضاف إلى فهرس الصفحة.

**Returns:**
قيمة int

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

يرجع سلسلة منسقة تمثل رقم الصفحة بناءً على الإعدادات الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة الحالي. |
| عدد |  | إجمالي عدد الصفحات. |

**Returns:**
سلسلة رقم صفحة منسقة.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

يحصل أو يضبط مكوّن إجمالي عدد الصفحات في تنسيق رقم الصفحة. ستتضمن السلسلة المنسقة عنصرًا نائبًا لإجمالي عدد الصفحات.

**Returns:**
مثيل PageTotalNum

### setDelimiter {#setDelimiter-java.lang.String-}
يحصل أو يضبط الفاصل المستخدم في تنسيق رقم الصفحة. سيتم تحديث السلسلة المنسقة بناءً على الفاصل المحدد.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
يحصل أو يضبط مكوّن فهرس الصفحة في تنسيق رقم الصفحة.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

يحصل أو يضبط الإزاحة التي ستُضاف إلى فهرس الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
يحصل أو يضبط مكوّن إجمالي عدد الصفحات في تنسيق رقم الصفحة.
