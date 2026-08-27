---
title: "صورة"
linktitle: "صورة"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل صورة."
type: docs
weight: 2280
url: /ar/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

يمثل صورة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Image](#Image--) | المنشئ الافتراضي |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | حاول تحويل الصورة بصيغة bmp/png/gif/tiff إلى تدفق بصيغة JPG. |
| [deepClone](#deepClone--) | استنساخ الصورة. |
| [getBitmapInfo](#getBitmapInfo--) | يحصل أو يعيّن بايتات الصورة غير المضغوطة. |
| [getBitmapSize](#getBitmapSize--) | يحصل على حجم بت ماب الصورة. |
| [getBufferedImage](#getBufferedImage--) | يحصل على صورة java awt. |
| [getFile](#getFile--) | يحصل على ملف الصورة. |
| [getFileType](#getFileType--) | يحصل على نوع ملف الصورة. |
| [getFixHeight](#getFixHeight--) | يحصل على ارتفاع الصورة. |
| [getFixWidth](#getFixWidth--) | يحصل على عرض الصورة. |
| [getImageScale](#getImageScale--) | يحصل على مقياس الصورة. |
| [getImageStream](#getImageStream--) | يحصل على تدفق الصورة. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | يعيد نوع MIME للصورة. |
| [getTitle](#getTitle--) | يحصل على قيمة نصية تشير إلى عنوان الصورة. |
| [isApplyResolution](#isApplyResolution--) | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة تستخدم الدقة أثناء الإنشاء. |
| [isBlackWhite](#isBlackWhite--) | يحصل على قيمة منطقية تشير إلى ما إذا كانت الصورة مُجبرة على أن تكون بالأبيض والأسود. إذا تم استخدام صورة TIFF من تنسيق فرعي CCITT، يجب ضبط هذه الخاصية إلى true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | حاول اكتشاف واستخدام ترميز 1bpp للصور ذات التدرج الرمادي. القيمة الافتراضية == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة تستخدم الدقة أثناء الإنشاء. |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | يحصل أو يعيّن بايتات الصورة غير المضغوطة. |
| [setBlackWhite](#setBlackWhite-boolean-) | يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة مُجبرة على أن تكون بالأبيض والأسود. إذا تم استخدام صورة TIFF من تنسيق فرعي CCITT، يجب ضبط هذه الخاصية إلى true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | حاول اكتشاف واستخدام ترميز 1bpp للصور ذات التدرج الرمادي. القيمة الافتراضية == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | يضبط صورة java awt. |
| [setFile](#setFile-java.lang.String-) | يضبط ملف الصورة. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | يضبط نوع ملف الصورة. |
| [setFixHeight](#setFixHeight-double-) | يضبط ارتفاع الصورة. |
| [setFixWidth](#setFixWidth-double-) | يضبط عرض الصورة. |
| [setImageScale](#setImageScale-double-) | يضبط مقياس الصورة. |
| [setImageStream](#setImageStream-java.io.InputStream-) | يضبط تدفق الصورة. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | يضبط قيمة نصية تشير إلى عنوان الصورة. |

### Image {#Image--}
```
public Image()
```

المنشئ الافتراضي

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
حاول تحويل الصورة بصيغة bmp/png/gif/tiff إلى تدفق بصيغة JPG.

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ الصورة.

**Returns:**
الكائن المستنسخ

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

يحصل أو يعيّن بايتات الصورة غير المضغوطة.

**Returns:**
مثيل BitmapInfo

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

يحصل على حجم بت ماب الصورة.

**Returns:**
مثيل Rectangle

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

يحصل على صورة java awt.

**Returns:**
كائن BufferedImage

### getFile {#getFile--}
```
public String getFile()
```

يحصل على ملف الصورة.

**Returns:**
قيمة سلسلة

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

يحصل على نوع ملف الصورة.

**Returns:**
قيمة int @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

يحصل على ارتفاع الصورة.

**Returns:**
قيمة double

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

يحصل على عرض الصورة.

**Returns:**
قيمة double

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

يحصل على مقياس الصورة.

**Returns:**
قيمة double

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

يحصل على تدفق الصورة.

**Returns:**
كائن InputStream

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
يعيد نوع MIME للصورة.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

يحصل على قيمة نصية تشير إلى عنوان الصورة.

**Returns:**
قيمة TextFragment

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة تستخدم الدقة أثناء الإنشاء.

**Returns:**
قيمة منطقية

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

يحصل على قيمة منطقية تشير إلى ما إذا كانت الصورة مُجبرة على أن تكون بالأبيض والأسود. إذا تم استخدام صورة TIFF من تنسيق فرعي CCITT، يجب ضبط هذه الخاصية إلى true.

**Returns:**
قيمة منطقية

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

حاول اكتشاف واستخدام ترميز 1bpp للصور ذات التدرج الرمادي. القيمة الافتراضية == FALSE

**Returns:**
قيمة منطقية

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة تستخدم الدقة أثناء الإنشاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
يحصل أو يعيّن بايتات الصورة غير المضغوطة.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة مُجبرة على أن تكون بالأبيض والأسود. إذا تم استخدام صورة TIFF من تنسيق فرعي CCITT، يجب ضبط هذه الخاصية إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

حاول اكتشاف واستخدام ترميز 1bpp للصور ذات التدرج الرمادي. القيمة الافتراضية == FALSE

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| blackWhiteForGrayScale |  | قيمة منطقية |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
يضبط صورة java awt.

### setFile {#setFile-java.lang.String-}
يضبط ملف الصورة.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
يضبط نوع ملف الصورة.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

يضبط ارتفاع الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

يضبط عرض الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

يضبط مقياس الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setImageStream {#setImageStream-java.io.InputStream-}
يضبط تدفق الصورة.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
يضبط قيمة نصية تشير إلى عنوان الصورة.
