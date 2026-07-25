---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل ختمًا رسوميًا."
type: docs
weight: 2360
url: /ar/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

يمثل ختمًا رسوميًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | يُهيئ مثيلًا جديدًا من الفئة {@code ImageStamp}. |
| [ImageStamp](#ImageStamp-java.lang.String-) | ينشئ ختم صورة باستخدام صورة في الملف المحدد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | يغلق هذا المثيل |
| [getAlternativeText](#getAlternativeText--) | يحصل على النص البديل لختم الصورة. |
| [getHeight](#getHeight--) | يحصل على ارتفاع الصورة. يسمح ضبط هذه الصورة بتكبير الصورة عموديًا. |
| [getImage](#getImage--) | يحصل على تدفق الصورة المستخدم للختم. |
| [getQuality](#getQuality--) | يحصل على جودة ختم الصورة بالنسبة المئوية. القيم الصالحة هي 0..100%. |
| [getWidth](#getWidth--) | يحصل على عرض الصورة. يسمح ضبط هذه الخاصية بتوسيع الصورة أفقيًا. |
| [getXIndent](#getXIndent--) | يحصل ويضبط إحداثيات الختم الأفقية، بدءًا من اليسار. |
| [getYIndent](#getYIndent--) | يحصل ويضبط إحداثيات الختم العمودية، بدءًا من الأسفل. |
| [put](#put-com.aspose.pdf.Page-) | يضيف ختمًا رسوميًا على الصفحة. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | يضبط النص البديل لختم الصورة. |
| [setHeight](#setHeight-double-) | يضبط ارتفاع الصورة. يسمح ضبط هذه الصورة بتكبير الصورة عموديًا. |
| [setQuality](#setQuality-int-) | يضبط جودة ختم الصورة بالنسبة المئوية. القيم الصالحة هي 0..100%. |
| [setWidth](#setWidth-double-) | يضبط عرض الصورة. يسمح ضبط هذه الخاصية بتوسيع الصورة أفقيًا. |
| [setXIndent](#setXIndent-double-) | يحصل ويضبط إحداثيات الختم الأفقية، بدءًا من اليسار. |
| [setYIndent](#setYIndent-double-) | يحصل ويضبط إحداثيات الختم العمودية، بدءًا من الأسفل. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
يُهيئ مثيلًا جديدًا من الفئة {@code ImageStamp}.

### ImageStamp {#ImageStamp-java.lang.String-}
ينشئ ختم صورة باستخدام صورة في الملف المحدد.

### close {#close--}
```
public void close()
```

يغلق هذا المثيل

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

يحصل على النص البديل لختم الصورة.

**Returns:**
قيمة سلسلة

### getHeight {#getHeight--}
```
public double getHeight()
```

يحصل على ارتفاع الصورة. يسمح ضبط هذه الصورة بتكبير الصورة عموديًا.

**Returns:**
قيمة double

### getImage {#getImage--}
```
public InputStream getImage()
```

يحصل على تدفق الصورة المستخدم للختم.

**Returns:**
كائن InputStream

### getQuality {#getQuality--}
```
public int getQuality()
```

يحصل على جودة ختم الصورة بالنسبة المئوية. القيم الصالحة هي 0..100%.

**Returns:**
قيمة int

### getWidth {#getWidth--}
```
public double getWidth()
```

يحصل على عرض الصورة. يسمح ضبط هذه الخاصية بتوسيع الصورة أفقيًا.

**Returns:**
قيمة double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

يحصل ويضبط إحداثيات الختم الأفقية، بدءًا من اليسار.

**Returns:**
قيمة double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

يحصل ويضبط إحداثيات الختم العمودية، بدءًا من الأسفل.

**Returns:**
قيمة double

### put {#put-com.aspose.pdf.Page-}
يضيف ختمًا رسوميًا على الصفحة.

### setAlternativeText {#setAlternativeText-java.lang.String-}
يضبط النص البديل لختم الصورة.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

يضبط ارتفاع الصورة. يسمح ضبط هذه الصورة بتكبير الصورة عموديًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

يضبط جودة ختم الصورة بالنسبة المئوية. القيم الصالحة هي 0..100%.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

يضبط عرض الصورة. يسمح ضبط هذه الخاصية بتوسيع الصورة أفقيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

يحصل ويضبط إحداثيات الختم الأفقية، بدءًا من اليسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

يحصل ويضبط إحداثيات الختم العمودية، بدءًا من الأسفل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |
