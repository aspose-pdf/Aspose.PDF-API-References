---
title: "XImage"
linktitle: "XImage"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تمثل كائن الصورة X-Object."
type: docs
weight: 5610
url: /ar/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

الفئة التي تمثل كائن الصورة X-Object.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | للاستخدام الداخلي فقط |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | يضيف قناع قوالب إلى XImage. |
| [containsTransparency](#containsTransparency--) | إذا كانت الصورة تحتوي على شفافية فترجع true؛ وإلا false. |
| [delete](#delete--) | يحذف الصورة من المجموعة الأصلية. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | يرجع نوع اللون للصورة. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | يرجع قائمة من السلاسل النصية التي تحتوي على النص البديل لـ XImage. |
| [getColorType](#getColorType--) | يرجع نوع اللون للصورة. |
| [getEngineImg](#getEngineImg--) | كائن IPPdfImage الذي يصف الصورة. داخلي فقط |
| [getFilterType](#getFilterType--) | يحصل على نوع مرشح الصورة. |
| [getGrayscaled](#getGrayscaled--) | يحصل على نسخة رمادية اللون من الصورة. |
| [getHeight](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getImage](#getImage--) | للاستخدام الداخلي فقط |
| [getMetadata](#getMetadata--) | بيانات تعريف الصورة. |
| [getName](#getName--) | يحصل على اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لديها مراجع في محتويات الصفحة، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة. |
| [getNameInCollection](#getNameInCollection--) | يرجع اسم الصورة في مجموعتها. |
| [getRawBytes](#getRawBytes--) | يعيد بايتات خام للصورة دون فك الترميز. |
| [getRawImageData](#getRawImageData--) | يسترجع بيانات الصورة الخام من الصورة المصدر. |
| [getRawParameters](#getRawParameters--) | يحصل على معلمات الصورة الخام |
| [getWidth](#getWidth--) | يحصل على عرض الصورة. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | يعيد true إذا كان الكائن الأساسي صورة. |
| [isImageMask](#isImageMask--) | يحصل على علم يحدد ما إذا كان يجب معالجة الصورة كقناع صورة (انظر 8.9.6، "Masked Images"). إذا كان هذا العلم true، يجب أن تكون قيمة BitsPerComponent مساوية لـ 1 ولا يجب تحديد Mask و ColorSpace؛ يجب طلاء المناطق غير المظللة باستخدام اللون غير المتصل الحالي. القيمة الافتراضية: false. القيمة: True إذا كانت الصورة قناع صورة. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | يعيد true إذا كان كلا الصورتين يشيران إلى نفس الكائن. |
| [rename](#rename-java.lang.String-) | يعيد تسمية الصورة ويستبدل جميع الإشارات إلى الصورة بالاسم الجديد |
| [replace](#replace-java.io.InputStream-) | يستبدل الصورة في الدفق المحدد في {@code image}. * |
| [save](#save-java.io.OutputStream-) | يحفظ بيانات الصورة في الدفق كصورة JPEG. |
| [save](#save-java.io.OutputStream-float-float-) | يحفظ الصورة في الدفق بالتنسيق المطلوب. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | يحفظ الصورة في الدفق بالتنسيق المطلوب. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | يحفظ الصورة في الدفق بالتنسيق المطلوب. |
| [save](#save-java.io.OutputStream-int-) | يحفظ الصورة في الدفق بالتنسيق المطلوب مع الدقة المحددة. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | يحفظ الصورة في الدفق بالتنسيق المطلوب. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | يحفظ بيانات الصورة في الدفق كصورة JPEG مع الدقة المحددة. |
| [setName](#setName-java.lang.String-) | يضبط اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لديها إشارات في محتويات الصفحة، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة. |
| [toStream](#toStream--) | يعيد دفق الصورة الأصلي. |
| [toString](#toString--) | يعيد تمثيلًا نصيًا لخصائص كائن XImage. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | يضبط النص البديل لـ XImage على الصفحة. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
للاستخدام الداخلي فقط

### addStencilMask {#addStencilMask-java.io.InputStream-}
يضيف قناع قوالب إلى XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

إذا كانت الصورة تحتوي على شفافية فترجع true؛ وإلا false.

**Returns:**
قيمة منطقية

### delete {#delete--}
```
public void delete()
```

يحذف الصورة من المجموعة الأصلية.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
يرجع نوع اللون للصورة.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
يرجع قائمة من السلاسل النصية التي تحتوي على النص البديل لـ XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

يرجع نوع اللون للصورة.

**Returns:**
قيمة نوع اللون.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

كائن IPPdfImage الذي يصف الصورة. داخلي فقط

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

يحصل على نوع مرشح الصورة.

**Returns:**
عنصر ImageFilterType

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

يحصل على نسخة رمادية اللون من الصورة.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

يحصل على ارتفاع الصورة.

**Returns:**
قيمة int

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

للاستخدام الداخلي فقط

**Returns:**
صورة

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

بيانات تعريف الصورة.

**Returns:**
مثيل Metadata

### getName {#getName--}
```
public String getName()
```

يحصل على اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لديها مراجع في محتويات الصفحة، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة.

**Returns:**
سلسلة

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

يرجع اسم الصورة في مجموعتها.

**Returns:**
مفتاح الصورة (الاسم).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

يعيد بايتات خام للصورة دون فك الترميز.

**Returns:**
مصفوفة بايت

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

يسترجع بيانات الصورة الخام من الصورة المصدر.

**Returns:**
مصفوفة {@link byte[]} تحتوي على بيانات الصورة الأصلية.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

يحصل على معلمات الصورة الخام

**Returns:**
RawParameters مثال

### getWidth {#getWidth--}
```
public int getWidth()
```

يحصل على عرض الصورة.

**Returns:**
قيمة int

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
يعيد true إذا كان الكائن الأساسي صورة.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

يحصل على علم يحدد ما إذا كان يجب معالجة الصورة كقناع صورة (انظر 8.9.6، "Masked Images"). إذا كان هذا العلم true، يجب أن تكون قيمة BitsPerComponent مساوية لـ 1 ولا يجب تحديد Mask و ColorSpace؛ يجب طلاء المناطق غير المظللة باستخدام اللون غير المتصل الحالي. القيمة الافتراضية: false. القيمة: True إذا كانت الصورة قناع صورة.

**Returns:**
قيمة منطقية

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
يعيد true إذا كان كلا الصورتين يشيران إلى نفس الكائن.

### rename {#rename-java.lang.String-}
يعيد تسمية الصورة ويستبدل جميع الإشارات إلى الصورة بالاسم الجديد

### replace {#replace-java.io.InputStream-}
يستبدل الصورة في الدفق المحدد في {@code image}. *

### save {#save-java.io.OutputStream-}
يحفظ بيانات الصورة في الدفق كصورة JPEG.

### save {#save-java.io.OutputStream-float-float-}
يحفظ الصورة في الدفق بالتنسيق المطلوب.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
يحفظ الصورة في الدفق بالتنسيق المطلوب.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
يحفظ الصورة في الدفق بالتنسيق المطلوب.

### save {#save-java.io.OutputStream-int-}
يحفظ الصورة في الدفق بالتنسيق المطلوب مع الدقة المحددة.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
يحفظ الصورة في الدفق بالتنسيق المطلوب.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
يحفظ بيانات الصورة في الدفق كصورة JPEG مع الدقة المحددة.

### setName {#setName-java.lang.String-}
يضبط اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لديها إشارات في محتويات الصفحة، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة.

### toStream {#toStream--}
```
public InputStream toStream()
```

يعيد دفق الصورة الأصلي.

**Returns:**
تدفق الصورة الأصلي.

### toString {#toString--}
```
public String toString()
```

يعيد تمثيلًا نصيًا لخصائص كائن XImage.

**Returns:**
String مثال

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
يضبط النص البديل لـ XImage على الصفحة.
