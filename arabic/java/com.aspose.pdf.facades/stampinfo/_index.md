---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل معلومات الطابع."
type: docs
weight: 710
url: /ar/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

فئة تمثل معلومات الطابع.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getForm](#getForm--) | يحصل على XForm للطابع. |
| [getImage](#getImage--) | يحصل على صورة الطابع. قد تكون فارغة إذا لم يحتوي الطابع على صور (مثلاً للطابع النصي). |
| [getImageInternal](#getImageInternal--) | يحصل على صورة الطابع. قد تكون فارغة إذا لم يحتوي الطابع على صور (مثلاً للطابع النصي). |
| [getIndexOnPage](#getIndexOnPage--) | يحصل على فهرس الطابع في الصفحة. |
| [getRectangle](#getRectangle--) | يحصل على المستطيل حيث تم وضع الطابع. |
| [getStampId](#getStampId--) | يحصل على معرف الطابع. |
| [getStampType](#getStampType--) | يحصل على نوع الطابع (صورة / نموذج). |
| [getText](#getText--) | يحصل على النص في الطابع. |
| [getVisible](#getVisible--) | يحصل على رؤية الطابع. إذا كان false فإن الطابع مخفي (باستخدام HideStampById). يمكن استعادة الطابع المخفي بواسطة ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

يحصل على XForm للطابع.

**Returns:**
كائن XForm

### getImage {#getImage--}
```
public BufferedImage getImage()
```

يحصل على صورة الطابع. قد تكون فارغة إذا لم يحتوي الطابع على صور (مثلاً للطابع النصي).

**Returns:**
كائن BufferedImage

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

يحصل على صورة الطابع. قد تكون فارغة إذا لم يحتوي الطابع على صور (مثلاً للطابع النصي).

**Returns:**
كائن الصورة

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

يحصل على فهرس الطابع في الصفحة.

**Returns:**
قيمة int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على المستطيل حيث تم وضع الطابع.

**Returns:**
عنصر المستطيل

### getStampId {#getStampId--}
```
public int getStampId()
```

يحصل على معرف الطابع.

**Returns:**
قيمة int

### getStampType {#getStampType--}
```
public StampType getStampType()
```

يحصل على نوع الطابع (صورة / نموذج).

**Returns:**
عنصر StampType @see StampType

### getText {#getText--}
```
public String getText()
```

يحصل على النص في الطابع.

**Returns:**
قيمة سلسلة

### getVisible {#getVisible--}
```
public boolean getVisible()
```

يحصل على رؤية الطابع. إذا كان false فإن الطابع مخفي (باستخدام HideStampById). يمكن استعادة الطابع المخفي بواسطة ShowStampById.

**Returns:**
قيمة منطقية
