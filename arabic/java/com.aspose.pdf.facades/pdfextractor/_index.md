---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة لاستخراج الصور والنص من مستند PDF."
type: docs
weight: 400
url: /ar/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

فئة لاستخراج الصور والنص من مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * يربط مستند PDF للتحرير. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * يربط مستند PDF للتحرير. / * / * / * |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> يربط مستند PDF من تدفق. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> ربط ملف PDF الإدخال. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | يستخرج المرفقات من مستند PDF. |
| [extractAttachment](#extractAttachment-java.lang.String-) | يستخرج المرفقات من مستند PDF. |
| [extractImage](#extractImage--) | <p> استخراج الصور من ملف PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> يحصل على جميع حاويات المحتوى المميز كصور منفصلة. </p> <p> سيتم حفظ كل محتوى مميز كصورة بصيغة png مسماة بـ {@code MCID_<ID number of block for the page>.png}</p> |
| [extractText](#extractText--) | <p> استخراج النص من مستند PDF. </p> <hr> <pre> المثال الأول يوضح كيفية استخراج كل النص من ملف PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> المثال الثاني يوضح كيفية استخراج نص كل صفحة إلى ملف txt واحد. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> استخراج النص من مستند PDF. </p> <hr> <pre> المثال الأول يوضح كيفية استخراج كل النص من ملف PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> المثال الثاني يوضح كيفية استخراج نص كل صفحة إلى ملف txt واحد. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | للاستخدام الداخلي فقط |
| [getAttachment](#getAttachment--) | <p> حفظ جميع ملفات المرفقات إلى تدفقات. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> حفظ جميع ملفات المرفقات إلى تدفقات. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | يحصل على قائمة المرفقات. |
| [getAttachNames](#getAttachNames--) | <p> يعيد قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة. </p> <hr> <pre> المثال يوضح كيفية استخراج أسماء المرفقات من ملف PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> يحصل على الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> يضبط الوضع لعملية استخراج الصور. </p> <hr> القيمة الافتراضية هي ExtractImageMode.DefinedInResources التي تستخرج جميع الصور المعرفة في الموارد. لاستخراج الصور المعروضة فعليًا يجب استخدام الوضع ExtractImageMode.ActuallyUsed. |
| [getExtractTextMode](#getExtractTextMode--) | <p> يحصل على الوضع لنتيجة استخراج النص. </p> <hr> <pre> المثال يوضح استخدام خاصية {@code ExtractTextMode} في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> القيمة: 0 هو وضع النص النقي و 1 هو وضع الترتيب الخام. القيمة الافتراضية هي 0.</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | يسترجع الصورة التالية من ملف PDF ويخزنها في الدفق. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | يسترجع الصورة التالية من ملف PDF ويخزنها في الدفق بالتنسيق المحدد للصورة. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | يسترجع الصورة التالية من مستند PDF بالتنسيق المحدد للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> يحفظ نص صفحة واحدة إلى الدفق. </p> <hr> <pre> يوضح المثال كيفية استخدام طريقة {@code GetNextPageText} في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> يحفظ نص صفحة واحدة إلى ملف. </p> <hr> <pre> يوضح المثال كيفية استخدام طريقة GetNextPageText في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | يحصل على كلمة مرور ملف الإدخال. |
| [getResolution](#getResolution--) | يحصل على الدقة للصور المستخرجة. القيمة الافتراضية هي 150. الصور التي لديها قيمة دقة أعلى تكون أوضح. ومع ذلك فإن زيادة قيمة الدقة يؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور. عادةً للحصول على صورة واضحة يكفي ضبط الدقة إلى 150 أو 300. |
| [getStartPage](#getStartPage--) | كائن Pdf.Engine يمثل مستند PDF. |
| [getText](#getText-java.io.OutputStream-) | يحفظ النص إلى الدفق. راجع أيضًا:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | يحفظ النص إلى الدفق. راجع أيضًا:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | يحفظ النص إلى ملف. راجع أيضًا:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | يحصل على خيارات بحث النص. |
| [hasNextImage](#hasNextImage--) | <p> يتحقق مما إذا كانت هناك صور إضافية متاحة في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> يشير إلى ما إذا كان يمكن الحصول على نصوص إضافية أم لا. </p> <hr> <pre> يوضح المثال كيفية استخدام الخاصية {@code HasNextPageText} في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | يكون صحيحًا عندما يحتوي النص على رموز عبريّة أو عربية. يجب مراعاة هذه الحالة بشكل خاص لأن وظائف السلاسل تغير سلوكها وتبدأ معالجة النص من اليمين إلى اليسار (باستثناء الأرقام والحروف غير النصية الأخرى). |
| [setEndPage](#setEndPage-int-) | <p> يحدد الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> يضبط الوضع لعملية استخراج الصور. </p> <hr> القيمة الافتراضية هي ExtractImageMode.DefinedInResources التي تستخرج جميع الصور المعرفة في الموارد. لاستخراج الصور المعروضة فعليًا يجب استخدام الوضع ExtractImageMode.ActuallyUsed. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> يحدد الوضع لنتيجة استخراج النص. </p> <hr> <pre> يوضح المثال كيفية استخدام الخاصية {@code ExtractTextMode} في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> القيمة: 0 هو وضع النص النقي و1 هو وضع الترتيب الخام. القيمة الافتراضية هي 0. |
| [setPassword](#setPassword-java.lang.String-) | يحدد كلمة مرور ملف الإدخال. |
| [setResolution](#setResolution-int-) | قم بتعيين الدقة للصور المستخرجة. القيمة الافتراضية هي 150. الصور التي لديها قيمة دقة أعلى تكون أكثر وضوحًا. ومع ذلك فإن زيادة قيمة الدقة يؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور. عادةً للحصول على صورة واضحة يكفي تعيين الدقة إلى 150 أو 300. |
| [setStartPage](#setStartPage-int-) | <p> يحدد الصفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | يضبط خيارات البحث عن النص. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * يربط مستند PDF للتحرير. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * يربط مستند PDF للتحرير. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> يربط مستند PDF من تدفق. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> ربط ملف PDF الإدخال. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

يستخرج المرفقات من مستند PDF.

### extractAttachment {#extractAttachment-java.lang.String-}
يستخرج المرفقات من مستند PDF.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> استخراج الصور من ملف PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> يحصل على جميع حاويات المحتوى المميز كصور منفصلة. </p> <p> سيتم حفظ كل محتوى مميز كصورة بصيغة png مسماة بـ {@code MCID_<ID number of block for the page>.png}</p>

### extractText {#extractText--}
```
public void extractText()
```

<p> يستخرج النص من مستند PDF. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> يوضح المثال الثاني كيفية استخراج نص كل صفحة في ملف txt واحد. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> يستخرج النص من مستند PDF. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\Text\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\Text\\text.txt\"); </pre> <p> يوضح المثال الثاني كيفية استخراج نص كل صفحة في ملف txt واحد. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
للاستخدام الداخلي فقط

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> حفظ جميع ملفات المرفقات إلى تدفقات. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
مصفوفة الدفق لملف المرفق في مستند PDF.

### getAttachment {#getAttachment-java.lang.String-}
<p> حفظ جميع ملفات المرفقات إلى تدفقات. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
مصفوفة الدفق لملف المرفق في مستند PDF.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

يحصل على قائمة المرفقات.

**Returns:**
إرجاع List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> يعيد قائمة المرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة. </p> <hr> <pre> المثال يوضح كيفية استخراج أسماء المرفقات من ملف PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
قائمة المرفقات

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> يحصل على الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
صفحة النهاية.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> يضبط الوضع لعملية استخراج الصور. </p> <hr> القيمة الافتراضية هي ExtractImageMode.DefinedInResources التي تستخرج جميع الصور المعرفة في الموارد. لاستخراج الصور المعروضة فعليًا يجب استخدام الوضع ExtractImageMode.ActuallyUsed.

**Returns:**
قيمة ExtractImageMode @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> يحصل على الوضع لنتيجة استخراج النص. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> <p> القيمة: 0 هو وضع النص النقي و 1 هو وضع الترتيب الخام. القيمة الافتراضية هي 0.

**Returns:**
نتيجة استخراج النص.

### getNextImage {#getNextImage-java.io.OutputStream-}
يسترجع الصورة التالية من ملف PDF ويخزنها في الدفق.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
يسترجع الصورة التالية من ملف PDF ويخزنها في الدفق بالتنسيق المحدد للصورة.

### getNextImage {#getNextImage-java.lang.String-}
<p> يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
يسترجع الصورة التالية من مستند PDF بالتنسيق المحدد للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> يحفظ نص صفحة واحدة إلى الدفق. </p> <hr> <pre> يوضح المثال كيفية استخدام طريقة {@code GetNextPageText} في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> يحفظ نص صفحة واحدة إلى ملف. </p> <hr> <pre> يوضح المثال كيفية استخدام طريقة GetNextPageText في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

يحصل على كلمة مرور ملف الإدخال.

**Returns:**
قيمة سلسلة

### getResolution {#getResolution--}
```
public int getResolution()
```

يحصل على الدقة للصور المستخرجة. القيمة الافتراضية هي 150. الصور التي لديها قيمة دقة أعلى تكون أوضح. ومع ذلك فإن زيادة قيمة الدقة يؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور. عادةً للحصول على صورة واضحة يكفي ضبط الدقة إلى 150 أو 300.

**Returns:**
قيمة int

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

كائن Pdf.Engine يمثل مستند PDF.

**Returns:**
صفحة البداية في نطاق الصفحات.

### getText {#getText-java.io.OutputStream-}
يحفظ النص إلى الدفق. راجع أيضًا:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
يحفظ النص إلى الدفق. راجع أيضًا:{@code ExtractText}

### getText {#getText-java.lang.String-}
يحفظ النص إلى ملف. راجع أيضًا:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

يحصل على خيارات بحث النص.

**Returns:**
خيارات بحث النص.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> يتحقق مما إذا كانت هناك صور إضافية متاحة في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
صحيح إذا كانت المزيد من الصور متاحة

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> يشير إلى ما إذا كان يمكن الحصول على نصوص إضافية أم لا. </p> <hr> <pre> يوضح المثال كيفية استخدام الخاصية {@code HasNextPageText} في سيناريو استخراج النص. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
يمكن الحصول على المزيد من النصوص أم لا، صحيح يعني يمكن، أو خطأ.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

يكون صحيحًا عندما يحتوي النص على رموز عبريّة أو عربية. يجب مراعاة هذه الحالة بشكل خاص لأن وظائف السلاسل تغير سلوكها وتبدأ معالجة النص من اليمين إلى اليسار (باستثناء الأرقام والحروف غير النصية الأخرى).

**Returns:**
قيمة منطقية

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> يحدد الصفحة النهائية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | صفحة النهاية. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> يضبط الوضع لعملية استخراج الصور. </p> <hr> القيمة الافتراضية هي ExtractImageMode.DefinedInResources التي تستخرج جميع الصور المعرفة في الموارد. لاستخراج الصور المعروضة فعليًا يجب استخدام الوضع ExtractImageMode.ActuallyUsed.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> يحدد الوضع لنتيجة استخراج النص. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\Text\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\Text\\text.txt\"); </pre> القيمة: 0 هو وضع النص النقي و 1 هو وضع الترتيب الخام. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | نتيجة استخراج النص. |

### setPassword {#setPassword-java.lang.String-}
يحدد كلمة مرور ملف الإدخال.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

قم بتعيين الدقة للصور المستخرجة. القيمة الافتراضية هي 150. الصور التي لديها قيمة دقة أعلى تكون أكثر وضوحًا. ومع ذلك فإن زيادة قيمة الدقة يؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور. عادةً للحصول على صورة واضحة يكفي تعيين الدقة إلى 150 أو 300.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> يحدد الصفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | صفحة البداية في نطاق الصفحات. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
يضبط خيارات البحث عن النص.
