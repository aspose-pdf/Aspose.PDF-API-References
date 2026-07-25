---
title: "PdfFileStampWeb"
linktitle: "PdfFileStampWeb"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF. تمكين العمل مع HttpServletResponse."
type: docs
weight: 550
url: /ar/java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF. تمكين العمل مع HttpServletResponse.

## الحقول

| حقل | الوصف |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | الموضع السفلي الأيسر. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | الموضع السفلي الأوسط. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | الموضع السفلي الأيمن. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | الموضع الأيسر. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | الموضع الأيمن. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | الموضع العلوي الأيسر. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | الموضع العلوي الأوسط. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | الموضع العلوي الأيمن. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> يضيف تذييلًا إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> يضيف تذييلًا إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> يضيف صورة كتذييل للصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> يضيف صورة كتذييل للصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> يضيف صورة كتذييل لصفحات المستند. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); fileStamp.addFooter(\"image.jpg\", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | يضيف صورة ك تذييل للصفحات. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> يضيف رأسًا إلى الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> يضيف رأسًا إلى صفحات الملف. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> يضيف صورة كعنوان للصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> يضيف صورة في أعلى الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> يضيف صورة كعنوان لصفحات الملف. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); fileStamp.addHeader(\"image.jpg\", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> يضيف صورة كعنوان للصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); fileStamp.addHeader(\"image.jpg\", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقياً. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> يضيف رقم الصفحة في الموضع المحدد على الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> يضيف رقم الصفحة إلى الصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> يضيف رقم الصفحة إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> يضيف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقياً. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> يضيف رقم الصفحة في الموضع المحدد على الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> يضيف رقم الصفحة إلى الصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> يضيف رقم الصفحة إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> يضيف ختمًا إلى الملف. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> يغلق الملفات المفتوحة ويحفظ التغييرات. تحذير. إذا تم تحديد تدفقات الإدخال أو الإخراج فإنها لا تُغلق بواسطة طريقة Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | مهمل. |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getContentDisposition](#getContentDisposition--) | يحصل على طريقة تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [getInputFile](#getInputFile--) | يحصل على اسم ومسار ملف الإدخال. |
| [getInputStream](#getInputStream--) | يحصل على تدفق الإدخال. |
| [getKeepSecurity](#getKeepSecurity--) | يحافظ على الأمان إذا كان true. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة). |
| [getNumberingStyle](#getNumberingStyle--) | يحصل أو يعيّن نمط ترقيم الصفحات. |
| [getOptimizeSize](#getOptimizeSize--) | يحصل أو يضبط علم التحسين. |
| [getOutputFile](#getOutputFile--) | يحصل على اسم ومسار ملف الإخراج. |
| [getOutputStream](#getOutputStream--) | يحصل على تدفق الإخراج. |
| [getPageHeight](#getPageHeight--) | <p> يحصل على ارتفاع الصفحة الأولى في ملف المصدر. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | يحصل على دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية هي 0. |
| [getPageWidth](#getPageWidth--) | <p> يحصل على عرض الصفحة الأولى في ملف الإدخال. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | يحصل على كائن Response حيث سيتم تخزين نتيجة العملية. |
| [getSaveOptions](#getSaveOptions--) | يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [getStampId](#getStampId--) | معرّف الختم للخمسة المضافة التالية (بما في ذلك رؤوس الصفحات/تذييلات الصفحات/أرقام الصفحات). |
| [getStartingNumber](#getStartingNumber--) | يحصل أو يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال. الصفحات التالية ستُرقَّم بدءًا من هذه القيمة. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل. |
| [setInputFile](#setInputFile-java.lang.String-) | يضبط اسم ومسار ملف الإدخال. |
| [setInputStream](#setInputStream-java.io.InputStream-) | يضبط تدفق الإدخال. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | يحافظ على الأمان إذا كان true. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | يحصل أو يعيّن نمط ترقيم الصفحات. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | يحصل أو يضبط علم التحسين. |
| [setOutputFile](#setOutputFile-java.lang.String-) | يضبط اسم ومسار ملف الإخراج. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | يضبط أو يضبط تدفق الإخراج. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | يضبط دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية هي 0. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | يضبط كائن Response حيث سيتم تخزين نتيجة العملية. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | معرّف الختم للخمسة المضافة التالية (بما في ذلك رؤوس الصفحات/تذييلات الصفحات/أرقام الصفحات). |
| [setStartingNumber](#setStartingNumber-int-) | <p> يحدد الرقم الابتدائي للصفحة الأولى في ملف الإدخال. الصفحات التالية سيتم ترقيمها بدءًا من هذه القيمة. على سبيل المثال إذا تم تعيين StartingNumber إلى 100، فإن صفحات المستند ستحصل على الأرقام 100، 101، 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

الموضع السفلي الأيسر.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

الموضع السفلي الأوسط.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

الموضع السفلي الأيمن.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

الموضع الأيسر.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

الموضع الأيمن.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

الموضع العلوي الأيسر.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

الموضع العلوي الأوسط.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

الموضع العلوي الأيمن.

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> منشئ PdfFileStamp. يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> يضيف تذييلًا إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> يضيف تذييلًا إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> يضيف صورة كتذييل للصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> يضيف صورة كتذييل للصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> يضيف صورة كتذييل لصفحات المستند. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); fileStamp.addFooter(\"image.jpg\", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
يضيف صورة ك تذييل للصفحات.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> يضيف رأسًا إلى الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> يضيف رأسًا إلى صفحات الملف. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> يضيف صورة كعنوان للصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> يضيف صورة في أعلى الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); InputStream input = new FileInputStream(\"test.jpg\"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> يضيف صورة كعنوان لصفحات الملف. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); fileStamp.addHeader(\"image.jpg\", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> يضيف صورة كعنوان للصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", output.pdf\"); fileStamp.addHeader(\"image.jpg\", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقياً. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> يضيف رقم الصفحة في الموضع المحدد على الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> يضيف رقم الصفحة إلى الصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> يضيف رقم الصفحة إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> يضيف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقياً. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> يضيف رقم الصفحة في الموضع المحدد على الصفحة. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> يضيف رقم الصفحة إلى الصفحات. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> يضيف رقم الصفحة إلى صفحات المستند. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> يضيف ختمًا إلى الملف. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> يغلق الملفات المفتوحة ويحفظ التغييرات. تحذير. إذا تم تحديد تدفقات الإدخال أو الإخراج فإنها لا تُغلق بواسطة طريقة Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

مهمل.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

**Returns:**
كائن سلسلة

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

يحصل على طريقة تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

**Returns:**
عنصر ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

يحصل على اسم ومسار ملف الإدخال.

**Returns:**
كائن String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

يحصل على تدفق الإدخال.

**Returns:**
كائن InputStream

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

يحافظ على الأمان إذا كان true. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة).

**Returns:**
قيمة منطقية

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

يحصل أو يعيّن نمط ترقيم الصفحات.

**Returns:**
عنصر NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

يحصل أو يضبط علم التحسين.

**Returns:**
قيمة منطقية

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

يحصل على اسم ومسار ملف الإخراج.

**Returns:**
كائن String

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

يحصل على تدفق الإخراج.

**Returns:**
كائن OutputStream

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> يحصل على ارتفاع الصفحة الأولى في ملف المصدر. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
قيمة عائمة

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

يحصل على دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية هي 0.

**Returns:**
قيمة عائمة

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> يحصل على عرض الصفحة الأولى في ملف الإدخال. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
قيمة عائمة

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

يحصل على كائن Response حيث سيتم تخزين نتيجة العملية.

**Returns:**
كائن HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions.

**Returns:**
كائن SaveOptions

### getStampId {#getStampId--}
```
public int getStampId()
```

معرّف الختم للخمسة المضافة التالية (بما في ذلك رؤوس الصفحات/تذييلات الصفحات/أرقام الصفحات).

**Returns:**
قيمة int

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

يحصل أو يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال. الصفحات التالية ستُرقَّم بدءًا من هذه القيمة.

**Returns:**
قيمة int

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل.

### setInputFile {#setInputFile-java.lang.String-}
يضبط اسم ومسار ملف الإدخال.

### setInputStream {#setInputStream-java.io.InputStream-}
يضبط تدفق الإدخال.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

يحافظ على الأمان إذا كان true. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
يحصل أو يعيّن نمط ترقيم الصفحات.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

يحصل أو يضبط علم التحسين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOutputFile {#setOutputFile-java.lang.String-}
يضبط اسم ومسار ملف الإخراج.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
يضبط أو يضبط تدفق الإخراج.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

يضبط دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
يضبط كائن Response حيث سيتم تخزين نتيجة العملية.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

معرّف الختم للخمسة المضافة التالية (بما في ذلك رؤوس الصفحات/تذييلات الصفحات/أرقام الصفحات).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> يحدد الرقم الابتدائي للصفحة الأولى في ملف الإدخال. الصفحات التالية سيتم ترقيمها بدءًا من هذه القيمة. على سبيل المثال إذا تم تعيين StartingNumber إلى 100، فإن صفحات المستند ستحصل على الأرقام 100، 101، 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
