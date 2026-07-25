---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الحزمة com.aspose.pdf.devices توفر فئات تُستخدم لتمثيل المستند كصورة (صور) أو نص عادي."
type: docs
weight: 140
url: /ar/java/com.aspose.pdf.devices/
---
الحزمة com.aspose.pdf.devices توفر فئات تُستخدم لتمثيل المستند كصورة (صور) أو نص عادي.

## الفئات

| فئة | الوصف |
| --- | --- |
| [BmpDevice](./bmpdevice/) | يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF كملفات BMP. |
| [Device](./device/) | فئة مجردة لجميع أنواع الأجهزة. يتم استخدام الجهاز لتمثيل مستند PDF بصيغة معينة. على سبيل المثال، يمكن تمثيل صفحة المستند كصورة أو نص. |
| [DicomDevice](./dicomdevice/) | يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة Dicom. |
| [DocumentDevice](./documentdevice/) | فئة مجردة لجميع الأجهزة التي تُستخدم لمعالجة مستند PDF بالكامل. |
| [EmfDevice](./emfdevice/) | يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة emf. |
| [FormPresentationMode](./formpresentationmode/) | يُستخدم لتحديد وضع عرض النموذج عند الطباعة أو التحويل إلى مستندات PDF صورة. |
| [GifDevice](./gifdevice/) | يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة gif. |
| [GraphicsDevice](./graphicsdevice/) | يمثل جهاز صورة يساعد على تحويل صفحات مستند PDF إلى رسومات. |
| [ImageDevice](./imagedevice/) | فئة مجردة لأجهزة الصورة. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة jpeg. |
| [Margins](./margins/) | تمثل هذه الفئة هوامش الصورة. |
| [PageDevice](./pagedevice/) | فئة مجردة لجميع الأجهزة التي تُستخدم لمعالجة صفحة معينة من مستند PDF. |
| [PngDevice](./pngdevice/) | يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة png. |
| [Resolution](./resolution/) | يمثل فئة لتخزين دقة الصورة. |
| [TextDevice](./textdevice/) | <p> تمثل فئة لتحويل صفحات مستند PDF إلى نص. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // إنشاء جهاز النص TextDevice device = new TextDevice(); // تحويل الصفحة وحفظ النص إلى الدفق device.process(doc.getPages().get_Item(1), ms); // استخدام النص المستخرج extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> كائن {@code TextDevice} يُستخدم أساسًا لاستخراج النص من صفحة PDF. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | يمثل جهاز صورة يحفظ صفحات مستند PDF كصورة مصغرة. |
| [TiffDevice](./tiffdevice/) | تساعد هذه الفئة على حفظ صفحات مستند PDF صفحةً بصفحة في صورة TIFF واحدة. |
| [TiffSettings](./tiffsettings/) | تمثل هذه الفئة إعدادات استيراد PDF إلى TIFF. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | فئة تمثل أنواع التحويل المفهرسة |
## Enums

| تعداد | الوصف |
| --- | --- |
| [ColorDepth](./colordepth/) | يُستخدم لتحديد قيمة المعامل الممررة إلى جهاز صورة TIFF. |
| [CompressionType](./compressiontype/) | يُستخدم لتحديد قيمة المعامل الممررة إلى جهاز صورة TIFF. |
| [ShapeType](./shapetype/) | يمثل هذا التعداد نوع الشكل للصور المستخرجة. |
