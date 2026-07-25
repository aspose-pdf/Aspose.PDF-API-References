---
title: "طابع"
linktitle: "طابع"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل الطابع."
type: docs
weight: 700
url: /ar/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

فئة تمثل الطابع.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Stamp](#Stamp--) | منشئ لكائن Stamp. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | يضبط الصورة التي سيتم استخدامها كختم. |
| [bindImage](#bindImage-java.lang.String-) | <p> يضبط الصورة كختم. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | يضبط النص كختم. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> يضبط ملف PDF ورقم الصفحة التي ستُستخدم كختم. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream(\"stamp.pdf\"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> يضبط ملف PDF ورقم الصفحة التي ستُستخدم كختم. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf(\"stamp.pdf\", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | يضبط حالة نص الختم. |
| [close](#close--) | يغلق هذا المثيل |
| [getBlendingSpace](#getBlendingSpace--) | يحصل على قيمة BlendingColorSpace التي تحدد مساحة اللون المستخدمة لإجراء عمليات الشفافية والدمج على الصفحة. |
| [getOpacity](#getOpacity--) | يحصل على شفافية الختم. |
| [getPageNumber](#getPageNumber--) | يحصل على رقم الصفحة. |
| [getPages](#getPages--) | يحصل على مصفوفة بأرقام الصفحات التي سيتأثر بها الختم. |
| [getQuality](#getQuality--) | يحصل على جودة ختم الصورة بالنسبة المئوية. القيم المتاحة 0..100%. |
| [getRotation](#getRotation--) | يحصل على دوران الختم بالدرجات. |
| [getStampId](#getStampId--) | يحصل على معرف الختم. |
| [isBackground](#isBackground--) | يحصل على حالة الخلفية. إذا كانت true سيُوضع الختم كخلفية للصفحة المُختومة. القيمة الافتراضية هي false. |
| [setBackground](#setBackground-boolean-) | يضبط حالة الخلفية. إذا كانت true سيُوضع الختم كخلفية للصفحة المُختومة. القيمة الافتراضية هي false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | يضبط قيمة BlendingColorSpace التي تحدد مساحة اللون المستخدمة لإجراء عمليات الشفافية والدمج على الصفحة. |
| [setImageSize](#setImageSize-float-float-) | يضبط حجم ختم الصورة. سيتم تحجيم الصورة وفق القيم المحددة. |
| [setOpacity](#setOpacity-float-) | يضبط شفافية الختم. |
| [setOrigin](#setOrigin-float-float-) | يضبط الموضع على الصفحة حيث سيُوضع الختم. |
| [setPageNumber](#setPageNumber-int-) | يضبط رقم الصفحة. |
| [setPages](#setPages-int:A-) | <p> يضبط مصفوفة بأرقام الصفحات التي سيتأثر بها الختم. إذا كان Pages = null فإن جميع صفحات المستند تتأثر. </p> |
| [setQuality](#setQuality-int-) | يضبط جودة ختم الصورة بالنسبة المئوية. القيم المتاحة 0..100%. |
| [setRotation](#setRotation-float-) | <p> يحصل على أو يضبط دوران الختم بالدرجات. </p> |
| [setStampId](#setStampId-int-) | يضبط معرف الختم. |

### Stamp {#Stamp--}
```
public Stamp()
```

منشئ لكائن Stamp.

### bindImage {#bindImage-java.io.InputStream-}
يضبط الصورة التي سيتم استخدامها كختم.

### bindImage {#bindImage-java.lang.String-}
<p> يضبط الصورة كختم. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
يضبط النص كختم.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> يضبط ملف PDF ورقم الصفحة التي ستُستخدم كختم. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream(\"stamp.pdf\"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> يضبط ملف PDF ورقم الصفحة التي ستُستخدم كختم. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf(\"stamp.pdf\", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
يضبط حالة نص الختم.

### close {#close--}
```
public void close()
```

يغلق هذا المثيل

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

يحصل على قيمة BlendingColorSpace التي تحدد مساحة اللون المستخدمة لإجراء عمليات الشفافية والدمج على الصفحة.

**Returns:**
قيمة int @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

يحصل على شفافية الختم.

**Returns:**
قيمة عائمة

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

يحصل على رقم الصفحة.

**Returns:**
قيمة int

### getPages {#getPages--}
```
public int[] getPages()
```

يحصل على مصفوفة بأرقام الصفحات التي سيتأثر بها الختم.

**Returns:**
مصفوفة int

### getQuality {#getQuality--}
```
public int getQuality()
```

يحصل على جودة ختم الصورة بالنسبة المئوية. القيم المتاحة 0..100%.

**Returns:**
قيمة int

### getRotation {#getRotation--}
```
public float getRotation()
```

يحصل على دوران الختم بالدرجات.

**Returns:**
قيمة عائمة

### getStampId {#getStampId--}
```
public int getStampId()
```

يحصل على معرف الختم.

**Returns:**
قيمة int

### isBackground {#isBackground--}
```
public boolean isBackground()
```

يحصل على حالة الخلفية. إذا كانت true سيُوضع الختم كخلفية للصفحة المُختومة. القيمة الافتراضية هي false.

**Returns:**
قيمة منطقية

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

يضبط حالة الخلفية. إذا كانت true سيُوضع الختم كخلفية للصفحة المُختومة. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
يضبط قيمة BlendingColorSpace التي تحدد مساحة اللون المستخدمة لإجراء عمليات الشفافية والدمج على الصفحة.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

يضبط حجم ختم الصورة. سيتم تحجيم الصورة وفق القيم المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض الصورة. |
| الارتفاع |  | ارتفاع الصورة. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

يضبط شفافية الختم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

يضبط الموضع على الصفحة حيث سيُوضع الختم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| originX |  | إحداثي X للطابع. |
| originY |  | إحداثي Y للطابع. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

يضبط رقم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> يضبط مصفوفة بأرقام الصفحات التي سيتأثر بها الختم. إذا كان Pages = null فإن جميع صفحات المستند تتأثر. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

يضبط جودة ختم الصورة بالنسبة المئوية. القيم المتاحة 0..100%.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> يحصل على أو يضبط دوران الختم بالدرجات. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

يضبط معرف الختم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
