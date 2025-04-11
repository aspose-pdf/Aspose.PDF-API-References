---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF for .NET API Reference
description: يوفر مساحة أسماء Aspose.Pdf.Facades فئات جاءت أصلاً من Aspose.Pdf.Kit. تُستخدم هذه الفئات للتلاعب بالمستندات وأداء عمليات مثل الدمج، والختم، والتوقيع، والتعليق، وما إلى ذلك، ولكن على مستوى عالٍ دون الوصول إلى الهيكل الداخلي للمستندات.
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/
---
تقدم مساحة أسماء **Aspose.Pdf.Facades** فئات جاءت أصلاً من Aspose.Pdf.Kit. تُستخدم هذه الفئات للتلاعب بالمستندات وأداء عمليات مثل الدمج، والختم، والتوقيع، والتعليق، وما إلى ذلك، ولكن على مستوى عالٍ دون الوصول إلى الهيكل الداخلي للمستند.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [AutoFiller](./autofiller/) | تمثل فئة لاستقبال البيانات من قاعدة البيانات أو مصدر بيانات آخر، وتملأها في الحقول المصممة من قالب PDF وأخيرًا تولد ملف PDF جديد أو تدفق. لديها وضعان لإدخال ملف القالب: الإدخال كتيار أو ملف PDF. لديها أربعة أنواع من أوضاع الإخراج: تدفق مدمج واحد، ملف مدمج واحد، العديد من التدفقات الصغيرة، العديد من الملفات الصغيرة. يمكنها استقبال البيانات الحرفية الموجودة في System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | خصائص مشغل BDC. |
| [Bookmark](./bookmark/) | تمثل إشارة مرجعية. |
| [Bookmarks](./bookmarks/) | تمثل مجموعة من كائنات [`Bookmark`](../aspose.pdf.facades/bookmark/). |
| [DocumentPrivilege](./documentprivilege/) | تمثل الامتيازات للوصول إلى ملف PDF. راجع [`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتياز المحدد مسبقًا مباشرة. 2. بناءً على امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز محدد مسبقًا وتغيير بعض تركيبات أذونات Adobe Professional المحددة. 4. مزج الطريقة 2 والطريقة 3. |
| [Facade](./facade/) | فئة الواجهة الأساسية. |
| [FontColor](./fontcolor/) | فئة تمثل لون النص. |
| [Form](./form/) | فئة تمثل كائن نموذج Acro. |
| [FormattedText](./formattedtext/) | فئة تمثل النص المنسق. تحتوي على معلومات حول النص ولونه وحجمه وأسلوبه. |
| [FormDataConverter](./formdataconverter/) | تمثل فئة لتحويل البيانات من تنسيق إلى آخر. يمكنها تحويل البيانات في fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB. يمكنها أيضًا تحويل البيانات في OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf. يمكنها تحويل fdf إلى xml مع علامة "مسمّاة بشكل صارم". |
| [FormEditor](./formeditor/) | فئة لتحرير النماذج (إضافة/حذف الحقول، إلخ) |
| [FormFieldFacade](./formfieldfacade/) | فئة لتمثيل خصائص الحقل. |
| [LineInfo](./lineinfo/) | تمثل معلومات الخط. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | تمثل فئة للعمل مع تعليقات مستندات PDF (التعليقات). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | تمثل فئة للعمل مع إشارات مرجعية لملف PDF بما في ذلك الإنشاء، والتعديل، والتصدير، والاستيراد، والحذف. |
| [PdfContentEditor](./pdfcontenteditor/) | تمثل فئة لتحرير محتوى ملف PDF. |
| [PdfConverter](./pdfconverter/) | تمثل فئة لتحويل كل صفحة من ملف PDF إلى صور، تدعم BMP وJPEG وPNG وTIFF الآن. المحتوى المدعوم في ملفات PDF: الصور، النموذج، التعليق. |
| [PdfExtractor](./pdfextractor/) | فئة لاستخراج الصور والنصوص من مستند PDF. |
| [PdfFileEditor](./pdffileeditor/) | تنفذ عمليات مع ملف PDF: الدمج، والتقسيم، واستخراج الصفحات، وصنع كتيب، إلخ. |
| [PdfFileInfo](./pdffileinfo/) | تمثل فئة للوصول إلى المعلومات الوصفية لمستند PDF. |
| [PdfFileMend](./pdffilemend/) | تمثل فئة لإضافة نصوص وصور على صفحات مستند PDF موجود. |
| [PdfFileSanitization](./pdffilesanitization/) | تمثل واجهة برمجة التطبيقات للتعقيم والاسترداد. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى. |
| [PdfFileSecurity](./pdffilesecurity/) | تمثل تشفير أو فك تشفير ملف PDF باستخدام كلمة مرور المالك أو المستخدم، وتغيير إعدادات الأمان وكلمة المرور. |
| [PdfFileSignature](./pdffilesignature/) | تمثل فئة لتوقيع ملف PDF باستخدام شهادة. |
| [PdfFileStamp](./pdffilestamp/) | فئة لإضافة أختام (علامة مائية أو خلفية) إلى ملفات PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | فئة لإزالة جميع أكواد Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | تمثل فئة لتحرير صفحة ملف PDF، بما في ذلك تدوير الصفحة، وتكبير الصفحة، وتحريك الموضع، وتغيير حجم الصفحة. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | تمثل كائنًا يحتوي على معلومات الصفحة الحالية للطباعة. |
| [PdfProducer](./pdfproducer/) | تمثل فئة لإنتاج PDF من تنسيقات أخرى. يوضح هذا المثال كيفية إنتاج ملف PDF من ملف CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | تمثل الطريقة التي تتعامل مع حدث [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) من [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |
| [PdfViewer](./pdfviewer/) | تمثل فئة لعرض أو طباعة ملف PDF. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | فئة للتلاعب ببيانات التعريف XMP. |
| [ReplaceTextStrategy](./replacetextstrategy/) | تحتوي هذه الفئة على معلمات تحدد سلوك PdfContentEditor عند تنفيذ عملية ReplaceText. |
| [SaveableFacade](./saveablefacade/) | فئة أساسية لجميع الواجهات القابلة للحفظ. |
| [SignatureName](./signaturename/) | تمثل فئة لاسم التوقيع. |
| [Stamp](./stamp/) | فئة تمثل الختم. |
| [StampInfo](./stampinfo/) | فئة تمثل معلومات الختم. |
| [TextProperties](./textproperties/) | تمثل خصائص النص مثل: حجم النص، اللون، الأسلوب، إلخ. |
| [ViewerPreference](./viewerpreference/) | تصف تفضيلات المشاهد (وضع الصفحة، وضع الصفحة غير كامل الشاشة، تخطيط الصفحة). |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IFacade](./ifacade/) | واجهة الواجهة العامة التي تحدد طرق الواجهات الشائعة. |
| [ISaveableFacade](./isaveablefacade/) | واجهة الواجهة التي تحدد الطرق الشائعة لجميع الواجهات القابلة للحفظ. |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [Algorithm](./algorithm/) | تمثل الخوارزميات التي يمكن استخدامها لتشفير مستند PDF. |
| [AutoRotateMode](./autorotatemode/) | اتجاه التدوير عند طباعة المستند. |
| [BlendingColorSpace](./blendingcolorspace/) | تمثل الفئة مساحة اللون الممزوجة. |
| [DataType](./datatype/) | تعدد تعريفات أنواع الحقول. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | تعداد الخصائص القياسية XMP. |
| [EncodingType](./encodingtype/) | تعدد أنواع تشفير النص المستخدم. |
| [FieldType](./fieldtype/) | تعداد أنواع الحقول الممكنة. |
| [FontStyle](./fontstyle/) | تعدد 14 نوعًا من الخطوط. |
| [ImageMergeMode](./imagemergemode/) | تمثل الأوضاع لدمج الصور. |
| [KeySize](./keysize/) | تحدد أحجام المفاتيح المختلفة التي يمكن استخدامها لتشفير مستندات PDF. |
| [PositioningMode](./positioningmode/) | تحدد وضع التمركز. تشمل القيم الممكنة Legacy (التوافق العكسي) وCurrent (طريقة حساب موضع النص المحدثة) |
| [PropertyFlag](./propertyflag/) | تعداد الأعلام الممكنة للحقول. |
| [StampType](./stamptype/) | تصف أنواع الأختام. |
| [SubmitFormFlag](./submitformflag/) | تعداد الأعلام الممكنة لنموذج الإرسال. |
| [WordWrapMode](./wordwrapmode/) | تحدد استراتيجيات لف لف الكلمات |