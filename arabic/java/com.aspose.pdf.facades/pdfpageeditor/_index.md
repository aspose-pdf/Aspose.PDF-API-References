---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لتعديل صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، نقل الموضع وتغيير حجم الصفحة."
type: docs
weight: 570
url: /ar/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

يمثل فئة لتعديل صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، نقل الموضع وتغيير حجم الصفحة.

## الحقول

| حقل | الوصف |
| --- | --- |
| [BLINDH](#BLINDH) | ستائر عمودية |
| [BLINDV](#BLINDV) | ستائر عمودية |
| [BTWIPE](#BTWIPE) | مسح من الأسفل إلى الأعلى |
| [DGLITTER](#DGLITTER) | بريق قطري |
| [DISSOLVE](#DISSOLVE) | الصفحة القديمة تذوب |
| [INBOX](#INBOX) | صندوق داخلي |
| [LRGLITTER](#LRGLITTER) | بريق من اليسار إلى اليمين |
| [LRWIPE](#LRWIPE) | مسح من اليسار إلى اليمين |
| [OUTBOX](#OUTBOX) | صندوق خارجي |
| [RLWIPE](#RLWIPE) | مسح من اليمين إلى اليسار |
| [SPLITHIN](#SPLITHIN) | تقسيم أفقي داخلي |
| [SPLITHOUT](#SPLITHOUT) | تقسيم أفقي خارجي |
| [SPLITVIN](#SPLITVIN) | تقسيم عمودي داخلي |
| [SPLITVOUT](#SPLITVOUT) | تقسيم عمودي خارجي |
| [TBGLITTER](#TBGLITTER) | بريق من الأعلى إلى الأسفل |
| [TBWIPE](#TBWIPE) | مسح من الأعلى إلى الأسفل |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | منشئ لفئة PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | منشئ لفئة PdfPageEditor. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyChanges](#applyChanges--) | تطبيق التغييرات التي تم إجراؤها على صفحات المستند. |
| [getAlignment](#getAlignment--) | يحصل على محاذاة أفقية لمحتوى PDF الأصلي على صفحة النتيجة، الافتراضي هو AlignmentType.Left. استخدم getHorizontalAlignment بدلاً من ذلك |
| [getDisplayDuration](#getDisplayDuration--) | يحصل على مدة العرض للصفحات. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | يحصل على محاذاة أفقية لمحتوى PDF الأصلي على صفحة النتيجة، الافتراضي هو AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> يعيد حجم الصندوق المحدد في المستند. </p> <hr> <pre> المثال التالي يوضح كيفية الحصول على صندوق الوسائط للصفحة الأولى: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | إرجاع حجم الصفحة. |
| [getPageRotation](#getPageRotation-int-) | <p> يعيد دوران الصفحة المحددة. </p> <hr> <pre> المثال التالي يوضح كيفية الحصول على دوران الصفحة: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> يحصل على دوران الصفحات، يحتوي جدول التجزئة على رقم الصفحة ودرجة الدوران، المفتاح يمثل رقم الصفحة، قيمة المفتاح تمثل الدوران بالدرجات. </p> |
| [getPages](#getPages--) | <p> يعيد العدد الإجمالي للصفحات. </p> <hr> <pre> المثال التالي يوضح استخدام طريقة GetPages(): PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | يحصل على حجم صفحة ملف الإخراج. |
| [getPageSize](#getPageSize-int-) | <p> يعيد حجم الصفحة المحددة. </p> <hr> <pre> المثال التالي يوضح استخدام طريقة GetPageSize: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | يحصل على أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة. |
| [getRotation](#getRotation--) | يحصل على دوران الصفحات، يجب أن يكون الدوران 0 أو 90 أو 180 أو 270. القيمة الافتراضية هي 0. |
| [getTransitionDuration](#getTransitionDuration--) | يحصل على مدة تأثير الانتقال. |
| [getTransitionType](#getTransitionType--) | يحصل على نمط الانتقال لاستخدامه عند الانتقال إلى هذه الصفحة من أخرى أثناء العرض. |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل على المحاذاة العمودية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. استخدم getVerticalAlignmentType بدلاً من ذلك |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | يحصل على المحاذاة العمودية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | احصل على معامل التكبير. القيمة 1.0 تمثل 100٪. القيمة الافتراضية هي 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | تحقق مما إذا كان الصندوق معرفًا على الصفحة. |
| [movePosition](#movePosition-float-float-) | <p> ينقل الأصل من (0, 0) إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي النقطة (1 بوصة = 72 نقطة). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> يحفظ المستند المعدل إلى تدفق. </p> <hr> <pre> العينة التالية توضح كيفية حفظ مستند PDF المعدل إلى تدفق. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> يحفظ المستند المعدل إلى ملف. </p> <hr> <pre> العينة التالية توضح كيفية حفظ مستند PDF المعدل PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | يضبط المحاذاة الأفقية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي AlignmentType.Left. استخدم setHorizontalAlignment بدلاً من ذلك |
| [setDisplayDuration](#setDisplayDuration-int-) | يضبط مدة العرض للصفحات. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط المحاذاة الأفقية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | يضبط دوران الصفحات، يحتوي جدول التجزئة على رقم الصفحة ودرجة الدوران، المفتاح يمثل رقم الصفحة، قيمة المفتاح تمثل الدوران بالدرجات. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | يضبط حجم صفحة ملف الإخراج. |
| [setProcessPages](#setProcessPages-int:A-) | يضبط أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة. |
| [setRotation](#setRotation-int-) | يضبط دوران الصفحات، يجب أن يكون الدوران 0 أو 90 أو 180 أو 270. القيمة الافتراضية هي 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | يضبط مدة تأثير الانتقال. |
| [setTransitionType](#setTransitionType-int-) | يضبط نمط الانتقال لاستخدامه عند الانتقال إلى هذه الصفحة من أخرى أثناء العرض. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | يضبط المحاذاة العمودية للمحتوى الأصلي لملف PDF على صفحة النتيجة، الافتراضي هو VerticalAlignmentType.Bottom. استخدم setVerticalAlignmentType بدلاً من ذلك |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | يضبط المحاذاة العمودية للمحتوى الأصلي لملف PDF على صفحة النتيجة، الافتراضي هو VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> يضبط معامل التكبير. القيمة 1.0 تمثل 100٪. القيمة الافتراضية هي 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

ستائر عمودية

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

ستائر عمودية

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

مسح من الأسفل إلى الأعلى

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

بريق قطري

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

الصفحة القديمة تذوب

### INBOX {#INBOX}
```
public static final int INBOX
```

صندوق داخلي

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

بريق من اليسار إلى اليمين

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

مسح من اليسار إلى اليمين

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

صندوق خارجي

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

مسح من اليمين إلى اليسار

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

تقسيم أفقي داخلي

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

تقسيم أفقي خارجي

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

تقسيم عمودي داخلي

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

تقسيم عمودي خارجي

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

بريق من الأعلى إلى الأسفل

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

مسح من الأعلى إلى الأسفل

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

منشئ لفئة PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
منشئ لفئة PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

تطبيق التغييرات التي تم إجراؤها على صفحات المستند.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

يحصل على محاذاة أفقية لمحتوى PDF الأصلي على صفحة النتيجة، الافتراضي هو AlignmentType.Left. استخدم getHorizontalAlignment بدلاً من ذلك

**Returns:**
كائن AlignmentType @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

يحصل على مدة العرض للصفحات.

**Returns:**
قيمة int

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

يحصل على محاذاة أفقية لمحتوى PDF الأصلي على صفحة النتيجة، الافتراضي هو AlignmentType.Left.

**Returns:**
عنصر HorizontalAlignment @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> يعيد حجم الصندوق المحدد في المستند. </p> <hr> <pre> المثال التالي يوضح كيفية الحصول على صندوق الوسائط للصفحة الأولى: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
إرجاع حجم الصفحة.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> يعيد دوران الصفحة المحددة. </p> <hr> <pre> المثال التالي يوضح كيفية الحصول على دوران الصفحة: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صفحة |  | فهرس الصفحة. صفحات المستند مرقمة بدءًا من 1. |

**Returns:**
دوران الصفحة بالدرجات.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> يحصل على دوران الصفحات، يحتوي جدول التجزئة على رقم الصفحة ودرجة الدوران، المفتاح يمثل رقم الصفحة، قيمة المفتاح تمثل الدوران بالدرجات. </p>

**Returns:**
كائن {@code Map<Integer, Integer>}

### getPages {#getPages--}
```
public int getPages()
```

<p> يعيد العدد الإجمالي للصفحات. </p> <hr> <pre> المثال التالي يوضح استخدام طريقة GetPages(): PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
عدد الصفحات.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

يحصل على حجم صفحة ملف الإخراج.

**Returns:**
كائن PageSize

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> يعيد حجم الصفحة المحددة. </p> <hr> <pre> المثال التالي يوضح استخدام طريقة GetPageSize: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صفحة |  | فهرس الصفحة. صفحات المستند مرقمة بدءًا من 1. |

**Returns:**
النتيجة هي نسخة من PageSize. استخدم خصائص Width و Height للكائن المرتجع للحصول على عرض وارتفاع الصفحة.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

يحصل على أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة.

**Returns:**
مصفوفة من قيم int

### getRotation {#getRotation--}
```
public int getRotation()
```

يحصل على دوران الصفحات، يجب أن يكون الدوران 0 أو 90 أو 180 أو 270. القيمة الافتراضية هي 0.

**Returns:**
قيمة int

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

يحصل على مدة تأثير الانتقال.

**Returns:**
قيمة int

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

يحصل على نمط الانتقال لاستخدامه عند الانتقال إلى هذه الصفحة من أخرى أثناء العرض.

**Returns:**
قيمة int

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

يحصل على المحاذاة العمودية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. استخدم getVerticalAlignmentType بدلاً من ذلك

**Returns:**
كائن VerticalAlignmentType

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

يحصل على المحاذاة العمودية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom.

**Returns:**
عنصر VerticalAlignmentType @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

احصل على معامل التكبير. القيمة 1.0 تمثل 100٪. القيمة الافتراضية هي 1.0.

**Returns:**
قيمة عائمة

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
تحقق مما إذا كان الصندوق معرفًا على الصفحة.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> ينقل الأصل من (0, 0) إلى النقطة المحددة. الأصل هو أسفل اليسار والوحدة هي النقطة (1 بوصة = 72 نقطة). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| moveX |  | الإحداثي X. |
| moveY |  | الإحداثي Y. |

### save {#save-java.io.OutputStream-}
<p> يحفظ المستند المعدل إلى تدفق. </p> <hr> <pre> العينة التالية توضح كيفية حفظ مستند PDF المعدل إلى تدفق. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> يحفظ المستند المعدل إلى ملف. </p> <hr> <pre> العينة التالية توضح كيفية حفظ مستند PDF المعدل PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
يضبط المحاذاة الأفقية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي AlignmentType.Left. استخدم setHorizontalAlignment بدلاً من ذلك

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

يضبط مدة العرض للصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط المحاذاة الأفقية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
يضبط دوران الصفحات، يحتوي جدول التجزئة على رقم الصفحة ودرجة الدوران، المفتاح يمثل رقم الصفحة، قيمة المفتاح تمثل الدوران بالدرجات.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
يضبط حجم صفحة ملف الإخراج.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

يضبط أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة من قيم int |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

يضبط دوران الصفحات، يجب أن يكون الدوران 0 أو 90 أو 180 أو 270. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

يضبط مدة تأثير الانتقال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

يضبط نمط الانتقال لاستخدامه عند الانتقال إلى هذه الصفحة من أخرى أثناء العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
يضبط المحاذاة العمودية للمحتوى الأصلي لملف PDF على صفحة النتيجة، الافتراضي هو VerticalAlignmentType.Bottom. استخدم setVerticalAlignmentType بدلاً من ذلك

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
يضبط المحاذاة العمودية للمحتوى الأصلي لملف PDF على صفحة النتيجة، الافتراضي هو VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> يضبط معامل التكبير. القيمة 1.0 تمثل 100٪. القيمة الافتراضية هي 1.0. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة float <hr> <pre> المثال التالي يوضح كيفية تغيير تكبير صفحات المستند. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
