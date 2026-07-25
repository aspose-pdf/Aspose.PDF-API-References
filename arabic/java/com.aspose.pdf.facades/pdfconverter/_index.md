---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لتحويل كل صفحة من ملف pdf إلى صور، يدعم الآن BMP و JPEG و PNG و TIFF. المحتوى المدعوم في ملفات pdf: صور، نماذج، تعليقات."
type: docs
weight: 390
url: /ar/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

يمثل فئة لتحويل كل صفحة من ملف PDF إلى صور، يدعم الآن BMP و JPEG و PNG و TIFF. المحتوى المدعوم في ملفات PDF: الصور، النماذج، التعليقات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfConverter](#PdfConverter--) | يُنشئ كائن {@code PdfConverter} جديد. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | يُنشئ كائن {@code PdfConverter} جديد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | يربط مستند PDF بـ {@link PdfConverter} للمعالجة اللاحقة. |
| [bindPdf](#bindPdf-java.io.InputStream-) | يربط تدفق Pdf للتحويل. |
| [bindPdf](#bindPdf-java.lang.String-) | يربط ملف Pdf للتحويل. |
| [close](#close--) | أغلق نسخة PdfConverter وحرّر الموارد. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | للاستخدام الداخلي فقط |
| [dispose](#dispose--) | أغلق نسخة PdfConverter وحرّر الموارد. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [doConvert](#doConvert--) | <p> قم ببعض الأعمال الأولية لتحويل مستند pdf إلى صور. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [getEndPage](#getEndPage--) | يحصل على موضع النهاية الذي تريد تحويله. |
| [getFormPresentationMode](#getFormPresentationMode--) | يحصل على وضع عرض النموذج. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة الافتراضي - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد، الحجم والجودة. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد والجودة. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد، الحجم والجودة. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد، الأبعاد والجودة. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| [getNextImage](#getNextImage-java.lang.String-) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة الافتراضي - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> يحفظ الصورة إلى ملف بالتنسيق المحدد للصورة، وحجم الصورة، والجودة. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | يحفظ الصورة إلى ملف بالتنسيق المحدد للصورة والجودة. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> يحفظ الصورة إلى ملف بالتنسيق المحدد للصورة والأبعاد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> يحفظ الصورة إلى ملف بالتنسيق المحدد للصورة، والأبعاد، والجودة. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | يحفظ الصورة إلى ملف بحجم الصفحة المحدد وصيغة الصورة الافتراضية - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | يحفظ الصورة إلى ملف بحجم الصفحة المحدد وصيغة الصورة. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | يحفظ الصورة إلى ملف بحجم الصفحة المحدد، وصيغة الصورة، والجودة. |
| [getPageCount](#getPageCount--) | يحصل على عدد الصفحات. |
| [getPassword](#getPassword--) | يحصل على كلمة مرور المالك للوثيقة. |
| [getRenderingOptions](#getRenderingOptions--) | يحصل على خيارات العرض. |
| [getResolution](#getResolution--) | يحصل على الدقة أثناء التحويل. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 150. |
| [getStartPage](#getStartPage--) | يحصل على موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1. |
| [getUserPassword](#getUserPassword--) | يحصل على كلمة مرور المستخدم للوثيقة. |
| [hasNextImage](#hasNextImage--) | يشير إلى ما إذا كان ملف PDF يحتوي على صور إضافية أم لا. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | يحصل على العلامة التي تتحكم في إظهار المناطق المخفية على الصفحة. الطريقة مهجورة. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | يدمج قائمة تدفقات الصور ك تدفق صورة واحد. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | يدمج قائمة تدفقات TIFF ك تدفق TIFF متعدد الإطارات. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> يحول كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> يحول كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | يحوّل كل صفحة من مستند PDF إلى صور مع ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يحوّل كل صفحة من مستند PDF إلى صور مع ويحفظ الصور في ملف TIFF واحد. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF من الفئة ClassF واحد. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF من الفئة ClassF واحد. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF من الفئة ClassF واحد. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> يقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> يقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | يقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [setEndPage](#setEndPage-int-) | يضبط موضع النهاية الذي تريد تحويله. استخدم setEndPage(int) قبل setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | يضبط وضع عرض النموذج. |
| [setPassword](#setPassword-java.lang.String-) | يضبط OwnerPassword للوثيقة. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | يضبط نطاق الصفحات التي تريد تحويلها. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | يضبط خيارات العرض. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | يضبط الدقة أثناء التحويل. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | مهمل. |
| [setStartPage](#setStartPage-int-) | يضبط موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1. استخدم setEndPage(int) قبل setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | يضبط UserPassword للوثيقة. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

يُنشئ كائن {@code PdfConverter} جديد.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
يُنشئ كائن {@code PdfConverter} جديد.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
يربط مستند PDF بـ {@link PdfConverter} للمعالجة اللاحقة.

### bindPdf {#bindPdf-java.io.InputStream-}
يربط تدفق Pdf للتحويل.

### bindPdf {#bindPdf-java.lang.String-}
يربط ملف Pdf للتحويل.

### close {#close--}
```
public void close()
```

أغلق نسخة PdfConverter وحرّر الموارد.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
للاستخدام الداخلي فقط

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

أغلق نسخة PdfConverter وحرّر الموارد. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> قم ببعض الأعمال الأولية لتحويل مستند PDF إلى صور. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

**Returns:**
عنصر PageCoordinateType @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

يحصل على موضع النهاية الذي تريد تحويله.

**Returns:**
قيمة int

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

يحصل على وضع عرض النموذج.

**Returns:**
وضع عرض النموذج. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة الافتراضي - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد، الحجم والجودة.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد والجودة.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد، الحجم والجودة.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
يحفظ الصورة إلى تدفق باستخدام تنسيق الصورة المحدد، الأبعاد والجودة.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
يحفظ الصورة إلى تدفق باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة.

### getNextImage {#getNextImage-java.lang.String-}
يحفظ الصورة إلى ملف باستخدام تنسيق الصورة الافتراضي - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> يحفظ الصورة إلى ملف بالتنسيق المحدد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> يحفظ الصورة إلى ملف بالتنسيق المحدد، وحجم الصورة، والجودة. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
يحفظ الصورة إلى ملف بالتنسيق المحدد للصورة والجودة.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> يحفظ الصورة إلى ملف بالتنسيق المحدد والأبعاد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> يحفظ الصورة إلى ملف بالتنسيق المحدد، والأبعاد، والجودة. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
يحفظ الصورة إلى ملف بحجم الصفحة المحدد وصيغة الصورة الافتراضية - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
يحفظ الصورة إلى ملف بحجم الصفحة المحدد وصيغة الصورة.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
يحفظ الصورة إلى ملف بحجم الصفحة المحدد، وصيغة الصورة، والجودة.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

يحصل على عدد الصفحات.

**Returns:**
قيمة int

### getPassword {#getPassword--}
```
public String getPassword()
```

يحصل على كلمة مرور المالك للوثيقة.

**Returns:**
قيمة سلسلة

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

يحصل على خيارات العرض.

**Returns:**
خيارات العرض.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

يحصل على الدقة أثناء التحويل. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 150.

**Returns:**
عنصر الدقة

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

يحصل على موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1.

**Returns:**
قيمة int

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

يحصل على كلمة مرور المستخدم للوثيقة.

**Returns:**
قيمة سلسلة

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

يشير إلى ما إذا كان ملف PDF يحتوي على صور إضافية أم لا.

**Returns:**
يمكن الحصول على مزيد من الصور أم لا، true إذا كان ممكنًا، أو false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

يحصل على العلامة التي تتحكم في إظهار المناطق المخفية على الصفحة. الطريقة مهجورة.

**Returns:**
قيمة منطقية

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
يدمج قائمة تدفقات الصور ك تدفق صورة واحد.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
يدمج قائمة تدفقات TIFF ك تدفق TIFF متعدد الإطارات.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يحوّل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
يحوّل كل صفحة من مستند PDF إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
يحوّل كل صفحة من مستند PDF إلى صور مع ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يحوّل كل صفحة من مستند PDF إلى صور مع ويحفظ الصور في ملف TIFF واحد.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF من الفئة ClassF واحد.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF من الفئة ClassF واحد.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
يحوّل كل صفحة من مستند PDF إلى صور ويحفظ الصور في تدفق TIFF من الفئة ClassF واحد.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> يقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> يقوم بتحويل كل صفحات مستند PDF إلى صور ويحفظ الصور في ملف TIFF من نوع ClassF واحد. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
يقوم بتحويل كل صفحات مستند PDF إلى صور وحفظ الصور في ملف TIFF ClassF واحد.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

يضبط موضع النهاية الذي تريد تحويله. استخدم setEndPage(int) قبل setStartPage(int)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

يضبط وضع عرض النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | وضع عرض النموذج. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
يضبط OwnerPassword للوثيقة.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

يضبط نطاق الصفحات التي تريد تحويلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPage |  | قيمة int |
| EndPage |  | قيمة int |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
يضبط خيارات العرض.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
يضبط الدقة أثناء التحويل. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

مهمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

يضبط موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1. استخدم setEndPage(int) قبل setStartPage(int)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setUserPassword {#setUserPassword-java.lang.String-}
يضبط UserPassword للوثيقة.
