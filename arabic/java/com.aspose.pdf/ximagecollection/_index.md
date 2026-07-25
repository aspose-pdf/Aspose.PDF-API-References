---
title: "XImageCollection"
linktitle: "XImageCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تمثل مجموعة XImage."
type: docs
weight: 5630
url: /ar/java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImageCollection

**All Implemented Interfaces:**
Iterable < XImage >

```
public final class XImageCollection extends Object implements Iterable < XImage >
```

الفئة التي تمثل مجموعة XImage.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.BitmapInfo-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-java.awt.image.BufferedImage-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-java.io.InputStream-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-java.io.InputStream-int-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [add](#add-com.aspose.pdf.XImage-) | يضيف صورة جديدة إلى قائمة الصور. هذه الطريقة تضيف الصورة كمرجع إلى نفس كائن PdfObject (مما يسمح بتقليل حجم الملف) |
| [add](#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-) |  |
| [addWithImageFilterType](#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير. |
| [clear](#clear--) | يمسح جميع العناصر من المجموعة. |
| [contains](#contains-com.aspose.pdf.XImage-) | يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [copyTo](#copyTo-com.aspose.pdf.XImage:A-int-) | ينسخ مصفوفة الصور إلى المجموعة. |
| [delete](#delete--) | يحذف الصور من المجموعة. |
| [delete](#delete-int-) | يزيل الفهرس من المجموعة حسب الفهرس. |
| [delete](#delete-int-int-) | يزيل الفهرس من المجموعة حسب الفهرس مع تنفيذ الإجراء المحدد بواسطة معامل action. |
| [delete](#delete-java.lang.String-) | يحذف الصور من المجموعة. |
| [delete](#delete-java.lang.String-int-) | يحذف الصور من المجموعة. |
| [get_Item](#get_Item-int-) | يحصل على الصورة من المجموعة حسب فهرسها. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على الصورة من المجموعة حسب اسمها. |
| [getImageName](#getImageName-com.aspose.pdf.XImage-) | يرجع الاسم في قائمة الصور والذي هو المفتاح للصورة المعطاة. |
| [getNames](#getNames--) | يحصل على مصفوفة أسماء الصور. |
| [getSyncRoot](#getSyncRoot--) | يرجع كائن المزامنة. |
| [hasImage](#hasImage-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يُعيد true إذا كان الكائن متزامنًا. |
| [iterator](#iterator--) | يعيد عداد المجموعة. |
| [remove](#remove-com.aspose.pdf.XImage-) | غير مدعوم بعد، يرمي استثناءً. دائمًا يرمي NotImplementedException |
| [replace](#replace-int-java.io.InputStream-) | استبدال الصورة في المجموعة بصورة أخرى. |
| [replace](#replace-int-java.io.InputStream-int-) | استبدال الصورة في المجموعة بصورة أخرى. |
| [replace](#replace-int-java.io.InputStream-int-boolean-) | استبدال الصورة في المجموعة بصورة أخرى. |
| [saveJpxWithQuality](#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-) |  |
| [size](#size--) | عدد الصور في المجموعة. |

### add {#add-com.aspose.pdf.BitmapInfo-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-java.awt.image.BufferedImage-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-java.io.InputStream-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-java.io.InputStream-int-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### add {#add-com.aspose.pdf.XImage-}
يضيف صورة جديدة إلى قائمة الصور. هذه الطريقة تضيف الصورة كمرجع إلى نفس كائن PdfObject (مما يسمح بتقليل حجم الملف)

### add {#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-}


### addWithImageFilterType {#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
يضيف الكيان إلى نهاية المجموعة، بحيث يمكن الوصول إلى الكيان عبر الفهرس الأخير.

### clear {#clear--}
```
public void clear()
```

يمسح جميع العناصر من المجموعة.

### contains {#contains-com.aspose.pdf.XImage-}
يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة.

### copyTo {#copyTo-com.aspose.pdf.XImage:A-int-}
ينسخ مصفوفة الصور إلى المجموعة.

### delete {#delete--}
```
public void delete()
```

يحذف الصور من المجموعة.

### delete {#delete-int-}
```
public void delete(int index)
```

يزيل الفهرس من المجموعة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الصورة. |

### delete {#delete-int-int-}
```
public final void delete(int index, int action)
```

يزيل الفهرس من المجموعة حسب الفهرس مع تنفيذ الإجراء المحدد بواسطة معامل action.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الصورة التي سيتم إزالتها. |
| الإجراء |  | عنصر ImageDeleteAction. الإجراء الذي يتم بعد حذف الصورة. |

### delete {#delete-java.lang.String-}
يحذف الصور من المجموعة.

### delete {#delete-java.lang.String-int-}
يحذف الصور من المجموعة.

### get_Item {#get_Item-int-}
```
public XImage get_Item(int index)
```

يحصل على الصورة من المجموعة حسب فهرسها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الصورة |

**Returns:**
الصورة المسترجعة.

### get_Item {#get_Item-java.lang.String-}
يحصل على الصورة من المجموعة حسب اسمها.

### getImageName {#getImageName-com.aspose.pdf.XImage-}
يرجع الاسم في قائمة الصور والذي هو المفتاح للصورة المعطاة.

### getNames {#getNames--}
```
public String [] getNames()
```

يحصل على مصفوفة أسماء الصور.

**Returns:**
String[] array

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يرجع كائن المزامنة.

**Returns:**
عنصر Object

### hasImage {#hasImage-java.lang.String-}


### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يُعيد true إذا كان الكائن متزامنًا.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public Iterator < XImage > iterator()
```

يعيد عداد المجموعة.

**Returns:**
عداد المجموعة

### remove {#remove-com.aspose.pdf.XImage-}
غير مدعوم بعد، يرمي استثناءً. دائمًا يرمي NotImplementedException

### replace {#replace-int-java.io.InputStream-}
استبدال الصورة في المجموعة بصورة أخرى.

### replace {#replace-int-java.io.InputStream-int-}
استبدال الصورة في المجموعة بصورة أخرى.

### replace {#replace-int-java.io.InputStream-int-boolean-}
استبدال الصورة في المجموعة بصورة أخرى.

### saveJpxWithQuality {#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-}


### size {#size--}
```
public int size()
```

عدد الصور في المجموعة.

**Returns:**
قيمة int
