---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لإضافة النصوص والصور على صفحات وثيقة PDF الموجودة."
type: docs
weight: 500
url: /ar/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

يمثل فئة لإضافة النصوص والصور على صفحات وثيقة PDF الموجودة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | منشئ. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | منشئ. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | منشئ. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | منشئ. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | منشئ. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | منشئ. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | منشئ. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | غير مُنفّذ. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | غير مُنفّذ. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | غير مُنفّذ. |
| [close](#close--) | يغلق كائن PdfFileMend. |
| [dispose](#dispose--) | يغلق كائن PdfFileMend. هذه الطريقة قديمة، استخدم close() بدلاً من ذلك. |
| [getDocument](#getDocument--) | يحصل على المستند الذي يعمل عليه {@code PdfFileMend}. |
| [getInputFile](#getInputFile--) | يسترجع ملف الإدخال. |
| [getInputStream](#getInputStream--) | يسترجع تدفق الإدخال. |
| [getOutputFile](#getOutputFile--) | يحصل على ملف الإخراج. |
| [getOutputStream](#getOutputStream--) | يحصل على تدفق الإخراج. |
| [getTextPositioningMode](#getTextPositioningMode--) | يحصل على استراتيجية تموضع النص. {@code PositioningMode} الوضع الافتراضي هو Legacy. |
| [getWrapMode](#getWrapMode--) | يحصل على خوارزمية التفاف الكلمات. |
| [save](#save-java.io.OutputStream-) | يحفظ مستند PDF إلى الملف المحدد. |
| [save](#save-java.lang.String-) | يحفظ مستند PDF إلى الملف المحدد. |
| [setInputFile](#setInputFile-java.lang.String-) | مهمل. |
| [setInputStream](#setInputStream-java.io.InputStream-) | يضبط دفق الإدخال. |
| [setOutputFile](#setOutputFile-java.lang.String-) | يضبط ملف الإخراج. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | هذه الطريقة مُهملة. استخدم طريقة Save(outputStream) للحصول على نتائج الواجهة. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | يضبط استراتيجية تموضع النص. {@code PositioningMode} الوضع الافتراضي هو Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | يضبط قيمة منطقية تشير إلى التفاف الكلمات في طرق AddText. إذا كانت القيمة true، سيتفاف النص في FormattedText. بشكل افتراضي، القيمة هي false. |
| [setWrapMode](#setWrapMode-int-) | يضبط خوارزمية التفاف الكلمات. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

منشئ.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
منشئ.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
منشئ.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
منشئ.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
منشئ.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
منشئ.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
منشئ.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); InputStream stream = new FileInputStream(\"picture.jpg\")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> يضيف صورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> يضيف صورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
غير مُنفّذ.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
غير مُنفّذ.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
غير مُنفّذ.

### close {#close--}
```
public void close()
```

يغلق كائن PdfFileMend.

### dispose {#dispose--}
```
public void dispose()
```

يغلق كائن PdfFileMend. هذه الطريقة قديمة، استخدم close() بدلاً من ذلك.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

يحصل على المستند الذي يعمل عليه {@code PdfFileMend}.

**Returns:**
كائن IDocument

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

يسترجع ملف الإدخال.

**Returns:**
قيمة سلسلة

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

يسترجع تدفق الإدخال.

**Returns:**
تدفق الإدخال.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

يحصل على ملف الإخراج.

**Returns:**
قيمة سلسلة

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

يحصل على تدفق الإخراج.

**Returns:**
تدفق الإخراج.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

يحصل على استراتيجية تموضع النص. {@code PositioningMode} الوضع الافتراضي هو Legacy.

**Returns:**
عنصر PositioningMode @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

يحصل على خوارزمية التفاف الكلمات.

**Returns:**
قيمة WordWrapMode @see WordWrapMode

### save {#save-java.io.OutputStream-}
يحفظ مستند PDF إلى الملف المحدد.

### save {#save-java.lang.String-}
يحفظ مستند PDF إلى الملف المحدد.

### setInputFile {#setInputFile-java.lang.String-}
مهمل.

### setInputStream {#setInputStream-java.io.InputStream-}
يضبط دفق الإدخال.

### setOutputFile {#setOutputFile-java.lang.String-}
يضبط ملف الإخراج.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
هذه الطريقة مُهملة. استخدم طريقة Save(outputStream) للحصول على نتائج الواجهة.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

يضبط استراتيجية تموضع النص. {@code PositioningMode} الوضع الافتراضي هو Legacy.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PositioningMode @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

يضبط قيمة منطقية تشير إلى التفاف الكلمات في طرق AddText. إذا كانت القيمة true، سيتفاف النص في FormattedText. بشكل افتراضي، القيمة هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

يضبط خوارزمية التفاف الكلمات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر WordWrapMode @see WordWrapMode |
