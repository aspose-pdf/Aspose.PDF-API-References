---
title: "الموارد"
linktitle: "الموارد"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل موارد الصفحة."
type: docs
weight: 4220
url: /ar/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

فئة تمثل موارد الصفحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | يمسح البيانات المخزنة مؤقتًا، ويحرّر الذاكرة، إلخ. |
| [getExtGStates](#getExtGStates--) | يحصل على جميع حالات ExGStates من الموارد. |
| [getFonts](#getFonts--) | يحصل على مجموعة موارد {@code Fonts} |
| [getFonts](#getFonts-boolean-) | يعيد مجموعة الخطوط. إذا لم تحتوي الموارد على إدخال للخطوط فسيتم إنشاؤه اعتمادًا على علم CreateIfAbsent. |
| [getForms](#getForms--) | يحصل على مجموعة نماذج {@code Forms} |
| [getImages](#getImages--) | يحصل على مجموعة صور {@code Images} |
| [getResourceDictionary](#getResourceDictionary--) | حقل داخلي |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | يحصل على الموارد لـ |
| [isCommonResource](#isCommonResource--) | صحيح إذا كانت هذه الموارد مشتركة أي أنها مشتركة لعدة صفحات (موضوعة في قاموس الصفحات أو في كل صفحة كمرجع كائن) يجب التعامل مع الموارد المشتركة بحذر شديد، فمثلاً حذف كائن من الموارد المشتركة في صفحة واحدة قد يسبب أخطاءً في صفحات أخرى إذا كان الكائن المحذوف مستخدمًا في صفحات أخرى. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | للاستخدام الداخلي فقط! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

يمسح البيانات المخزنة مؤقتًا، ويحرّر الذاكرة، إلخ.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

يحصل على جميع حالات ExGStates من الموارد.

**Returns:**
يعيد القاموس مع مفاتيح أسماء ExGStates.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

يحصل على مجموعة موارد {@code Fonts}

**Returns:**
كائن FontCollection

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

يعيد مجموعة الخطوط. إذا لم تحتوي الموارد على إدخال للخطوط فسيتم إنشاؤه اعتمادًا على علم CreateIfAbsent.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createIfAbsent |  | إذا كانت هذه العلامة صحيحة فسيتم إنشاء الخطوط إذا كان هذا الإدخال غير موجود. |

**Returns:**
مجموعة الخطوط.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

يحصل على مجموعة نماذج {@code Forms}

**Returns:**
كائن XFormCollection

### getImages {#getImages--}
```
public XImageCollection getImages()
```

يحصل على مجموعة صور {@code Images}

**Returns:**
كائن XImageCollection

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

حقل داخلي

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
يحصل على الموارد لـ

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

صحيح إذا كانت هذه الموارد مشتركة أي أنها مشتركة لعدة صفحات (موضوعة في قاموس الصفحات أو في كل صفحة كمرجع كائن) يجب التعامل مع الموارد المشتركة بحذر شديد، فمثلاً حذف كائن من الموارد المشتركة في صفحة واحدة قد يسبب أخطاءً في صفحات أخرى إذا كان الكائن المحذوف مستخدمًا في صفحات أخرى.

**Returns:**
قيمة منطقية

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
للاستخدام الداخلي فقط!
