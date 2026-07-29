---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يقوم بتعديلات المحتوى في وضع APPEND فقط. يتيح هذا الوضع تجنب التحليل غير الضروري والثقيل للمحتوى قبل إجراء أي تغيير على المحتوى. إنه يضيف الجديد فقط."
type: docs
weight: 800
url: /ar/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

يُجري تعديلات على المحتوى في وضع APPEND فقط. يسمح هذا الوضع بتجنب تحليل المحتوى غير الضروري والثقيل قبل إجراء أي تغيير على المحتوى. يضيف فقط عوامل تشغيل جديدة إلى نهاية أو بداية المحتوى.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | إنشاء نسخة جديدة من مُضيف المحتوى مع إرفاق الصفحة. |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | يُنشئ نسخة جديدة من مُضيف المحتوى مع Form XObject. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | يضيف المشغلات إلى نهاية المحتوى |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | يضيف المشغل إلى نهاية المحتوى |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | يضيف المشغلات إلى نهاية المحتوى |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | يضيف المشغلات إلى بداية المحتوى |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | يضيف المشغل إلى بداية المحتوى |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | يضيف المشغلات إلى بداية المحتوى |
| [getBeginCode](#getBeginCode--) | سلسلة تحتوي على المشغلات لإدراجها في بداية الصفحة. |
| [getBeginOperators](#getBeginOperators--) | <p> يعيد مشغلات البداية </p> |
| [getEndCode](#getEndCode--) | سلسلة تحتوي على المشغلات لإلحاقها بنهاية الصفحة. |
| [getEndOperators](#getEndOperators--) | <p> يعيد مشغلات النهاية </p> |
| [resumeUpdate](#resumeUpdate--) | يستأنف تحديث المستند |
| [setBeginCode](#setBeginCode-java.lang.String-) | سلسلة تحتوي على المشغلات لإدراجها في بداية الصفحة. |
| [setEndCode](#setEndCode-java.lang.String-) | سلسلة تحتوي على المشغلات لإدراجها في بداية الصفحة. |
| [suppressUpdate](#suppressUpdate--) | يقمع تحديث بيانات المحتوى. لا يتم تحديث المحتوى حتى يتم استدعاء ResumeUpdate. |
| [updateData](#updateData--) | هذه نسخة جديدة من UpdateData، التي تتجنب فك ترميز المحتوى الحالي. |
| [updateDataOld](#updateDataOld--) | يجب استدعاؤه لتطبيق التغييرات |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
إنشاء نسخة جديدة من مُضيف المحتوى مع إرفاق الصفحة.

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
يُنشئ نسخة جديدة من مُضيف المحتوى مع Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
يضيف المشغلات إلى نهاية المحتوى

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
يضيف المشغل إلى نهاية المحتوى

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
يضيف المشغلات إلى نهاية المحتوى

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
يضيف المشغلات إلى بداية المحتوى

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
يضيف المشغل إلى بداية المحتوى

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
يضيف المشغلات إلى بداية المحتوى

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

سلسلة تحتوي على المشغلات لإدراجها في بداية الصفحة.

**Returns:**
كائن String

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> يعيد مشغلات البداية </p>

**Returns:**
{@code List<Operator>} كائن

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

سلسلة تحتوي على المشغلات لإلحاقها بنهاية الصفحة.

**Returns:**
كائن String

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> يعيد مشغلات النهاية </p>

**Returns:**
{@code List<Operator>} كائن

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

يستأنف تحديث المستند

### setBeginCode {#setBeginCode-java.lang.String-}
سلسلة تحتوي على المشغلات لإدراجها في بداية الصفحة.

### setEndCode {#setEndCode-java.lang.String-}
سلسلة تحتوي على المشغلات لإدراجها في بداية الصفحة.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

يقمع تحديث بيانات المحتوى. لا يتم تحديث المحتوى حتى يتم استدعاء ResumeUpdate.

### updateData {#updateData--}
```
public void updateData()
```

هذه نسخة جديدة من UpdateData، التي تتجنب فك ترميز المحتوى الحالي.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

يجب استدعاؤه لتطبيق التغييرات
