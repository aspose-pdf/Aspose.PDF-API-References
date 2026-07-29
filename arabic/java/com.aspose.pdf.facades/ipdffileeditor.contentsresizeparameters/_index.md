---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة لتحديد معلمات تغيير حجم الصفحة. تسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات المساحة الافتراضية أو بالنسبة المئوية للصفحات الأصلية."
type: docs
weight: 300
url: /ar/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

فئة لتحديد معلمات تغيير حجم الصفحة. تسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات الفضاء الافتراضية أو كنسبة مئوية من حجم الصفحات الأصلية؛ الهوامش اليسرى، العليا، السفلية واليمنى بوحدات الفضاء الافتراضية أو كنسبة مئوية من حجم الصفحة الأصلية؛ يمكن ترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من باقي حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض صفحة جديد 60 وحدة فإن الهوامش اليسرى واليمنى تُحسب تلقائيًا: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | ينشئ معلمات تغيير الحجم حيث يتم تعيين جميع القيم إلى "auto". يمكن تحديد الهوامش وحجم المحتوى لاحقًا إذا لزم الأمر. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | ينشئ معلمات تغيير الحجم حيث يتم تعيين جميع القيم إلى "auto". يمكن تحديد الهوامش وحجم المحتوى لاحقًا إذا لزم الأمر. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [contentSize](#contentSize-double-double-) | ينشئ معلمات تغيير الحجم بحجم محتوى محدد. |
| [contentSizePercent](#contentSizePercent-double-double-) | ينشئ معلمات تغيير الحجم بحجم محتوى محدد بالنسبة المئوية لحجم الصفحة الأصلية. يتم حساب الهوامش تلقائيًا. |
| [getBottomMargin](#getBottomMargin--) | يحصل أو يعيّن الهامش السفلي على الصفحة الناتجة. |
| [getContentsHeight](#getContentsHeight--) | يحصل أو يعيّن ارتفاع محتوى الصفحة المصدر على الصفحة الناتجة. |
| [getContentsWidth](#getContentsWidth--) | يحصل أو يعيّن عرض محتوى الصفحة المصدر على الصفحة الناتجة. |
| [getLeftMargin](#getLeftMargin--) | يحصل أو يعيّن الهامش الأيسر على الصفحة الناتجة. |
| [getRightMargin](#getRightMargin--) | يحصل أو يعيّن الهامش الأيمن على الصفحة الناتجة. |
| [getTopMargin](#getTopMargin--) | يحصل أو يعيّن الهامش العلوي على الصفحة الناتجة. |
| [isChangeMediaBox](#isChangeMediaBox--) | يحصل على ما إذا كان يجب تعديل MediaBox لصفحة PDF أثناء عملية تغيير الحجم. القيمة الافتراضية هي {@code false} ضبط هذا المعامل يتيح ملاءمة MediaBox مع قيمة CropBox أثناء تغيير الحجم. |
| [margins](#margins-double-double-double-double-) | ينشئ معلمات تغيير الحجم بقيمة هوامش محددة. يتم حساب حجم المحتوى تلقائيًا. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | ينشئ معلمات تغيير الحجم. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأصلي. |
| [pageResize](#pageResize-double-double-) | ينشئ معلمات تغيير الحجم لإعادة تحجيم الصفحة. |
| [pageResizePct](#pageResizePct-double-double-) | ينشئ معلمات تغيير الحجم لإعادة تحجيم الصفحة. يتم تحديد الأحجام الجديدة كنسبة مئوية. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | يحصل أو يعيّن الهامش السفلي على الصفحة الناتجة. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | يضبط ما إذا كان يجب تعديل MediaBox لصفحة PDF أثناء عملية تغيير الحجم. القيمة الافتراضية هي {@code false} ضبط هذا المعامل يتيح ملاءمة MediaBox لقيمة CropBox أثناء إعادة التحجيم. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | يحصل أو يعيّن ارتفاع محتوى الصفحة المصدر على الصفحة الناتجة. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | يحصل أو يعيّن عرض محتوى الصفحة المصدر على الصفحة الناتجة. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | يحصل أو يعيّن الهامش الأيسر على الصفحة الناتجة. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | يحصل أو يعيّن الهامش الأيمن على الصفحة الناتجة. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | يحصل أو يعيّن الهامش العلوي على الصفحة الناتجة. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

ينشئ معلمات تغيير الحجم حيث يتم تعيين جميع القيم إلى "auto". يمكن تحديد الهوامش وحجم المحتوى لاحقًا إذا لزم الأمر.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
ينشئ معلمات تغيير الحجم حيث يتم تعيين جميع القيم إلى "auto". يمكن تحديد الهوامش وحجم المحتوى لاحقًا إذا لزم الأمر.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

ينشئ معلمات تغيير الحجم بحجم محتوى محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | العرض الجديد للمحتويات. |
| الارتفاع |  | الارتفاع الجديد للمحتويات. |

**Returns:**
يعيد معلمات تغيير الحجم الجديدة.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

ينشئ معلمات تغيير الحجم بحجم محتوى محدد بالنسبة المئوية لحجم الصفحة الأصلية. يتم حساب الهوامش تلقائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | العرض الجديد للمحتوى بالنسب المئوية. |
| الارتفاع |  | الارتفاع الجديد للمحتويات بالنسب المئوية. |

**Returns:**
معلمات تغيير الحجم الجديدة.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

يحصل أو يعيّن الهامش السفلي على الصفحة الناتجة.

**Returns:**
كائن ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

يحصل أو يعيّن ارتفاع محتوى الصفحة المصدر على الصفحة الناتجة.

**Returns:**
كائن ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

يحصل أو يعيّن عرض محتوى الصفحة المصدر على الصفحة الناتجة.

**Returns:**
كائن ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

يحصل أو يعيّن الهامش الأيسر على الصفحة الناتجة.

**Returns:**
كائن ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

يحصل أو يعيّن الهامش الأيمن على الصفحة الناتجة.

**Returns:**
كائن ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

يحصل أو يعيّن الهامش العلوي على الصفحة الناتجة.

**Returns:**
كائن ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

يحصل على ما إذا كان يجب تعديل MediaBox لصفحة PDF أثناء عملية تغيير الحجم. القيمة الافتراضية هي {@code false} ضبط هذا المعامل يتيح ملاءمة MediaBox مع قيمة CropBox أثناء تغيير الحجم.

**Returns:**
ما إذا كان يجب تعديل MediaBox لصفحة PDF أثناء عملية تغيير الحجم.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

ينشئ معلمات تغيير الحجم بقيمة هوامش محددة. يتم حساب حجم المحتوى تلقائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اليسار |  | الهامش الأيسر. |
| يمين |  | الهامش الأيمن. |
| أعلى |  | الهامش العلوي. |
| الأسفل |  | الهامش السفلي. |

**Returns:**
تم إنشاء معلمات تغيير الحجم.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

ينشئ معلمات تغيير الحجم. يتم تحديد الهوامش كنسب مئوية من حجم الصفحة الأصلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اليسار |  | الهامش الأيسر (بنسب مئوية من عرض الصفحة). |
| يمين |  | الهامش الأيمن (بنسب مئوية من ارتفاع الصفحة). |
| أعلى |  | الهامش العلوي (بنسب مئوية من ارتفاع الصفحة). |
| الأسفل |  | الهامش السفلي (بنسب مئوية من ارتفاع الصفحة). |

**Returns:**
يعيد معلمات تغيير الحجم الجديدة.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

ينشئ معلمات تغيير الحجم لإعادة تحجيم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | العرض الجديد للصفحة بالوحدات. |
| الارتفاع |  | الارتفاع الجديد للصفحة بالوحدات. |

**Returns:**
معلمات تغيير الحجم الجديدة.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

ينشئ معلمات تغيير الحجم لإعادة تحجيم الصفحة. يتم تحديد الأحجام الجديدة كنسبة مئوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| widthPct |  | العرض الجديد للصفحة بالنسب المئوية. |
| heightPct |  | الارتفاع الجديد للصفحة بالنسب المئوية. |

**Returns:**
معلمات تغيير الحجم الجديدة.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
يحصل أو يعيّن الهامش السفلي على الصفحة الناتجة.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

يضبط ما إذا كان يجب تعديل MediaBox لصفحة PDF أثناء عملية تغيير الحجم. القيمة الافتراضية هي {@code false} ضبط هذا المعامل يتيح ملاءمة MediaBox لقيمة CropBox أثناء إعادة التحجيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | ما إذا كان يجب تعديل MediaBox لصفحة PDF أثناء عملية تغيير الحجم. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
يحصل أو يعيّن ارتفاع محتوى الصفحة المصدر على الصفحة الناتجة.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
يحصل أو يعيّن عرض محتوى الصفحة المصدر على الصفحة الناتجة.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
يحصل أو يعيّن الهامش الأيسر على الصفحة الناتجة.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
يحصل أو يعيّن الهامش الأيمن على الصفحة الناتجة.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
يحصل أو يعيّن الهامش العلوي على الصفحة الناتجة.
