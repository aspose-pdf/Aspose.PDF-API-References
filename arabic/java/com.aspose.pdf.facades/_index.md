---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الحزمة com.aspose.pdf.facades توفر فئات جاءت أصلاً من Aspose.Pdf.Kit."
type: docs
weight: 180
url: /ar/java/com.aspose.pdf.facades/
---
الحزمة com.aspose.pdf.facades توفر فئات جاءت أصلاً من Aspose.Pdf.Kit.

## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IFacade](./ifacade/) | واجهة واجهة أمامية عامة تُعرّف طرق الواجهات الأمامية المشتركة. |
| [IForm](./iform/) | فئة تمثل كائن نموذج Acro. |
| [IFormEditor](./iformeditor/) | فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك). |
| [IPdfFileEditor](./ipdffileeditor/) | تنفّذ عمليات على ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيّب، إلخ. |
| [IPdfFileStamp](./ipdffilestamp/) | واجهة لإضافة الختم (علامة مائية أو خلفية) إلى ملفات PDF. |
| [ISaveableFacade](./isaveablefacade/) | واجهة واجهة أمامية تُعرّف الطرق المشتركة لجميع الواجهات القابلة للحفظ. |
## الفئات

| فئة | الوصف |
| --- | --- |
| [AlignmentType](./alignmenttype/) | الفئة تحتوي على أنواع محاذاة محتملة. استخدم HorizontalAlignment بدلاً من ذلك. |
| [AutoRotateMode](./autorotatemode/) | اتجاه الدوران عند طباعة المستند. |
| [BDCProperties](./bdcproperties/) | خصائص المشغل BDC. |
| [Bookmark](./bookmark/) | يمثل إشارة مرجعية. |
| [Bookmarks](./bookmarks/) | يمثل مجموعة من كائنات {@code Bookmark}. |
| [CgmPdfProducer](./cgmpdfproducer/) | يمثل فئة لإنتاج PDF من تنسيق ملف الرسومات الحاسوبية (CGM). |
| [DataType](./datatype/) | يسرد تعريفات أنواع الحقول. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | تعداد خصائص XMP القياسية. |
| [DocumentPrivilege](./documentprivilege/) | يمثل الامتيازات للوصول إلى ملف Pdf. ارجع إلى{@code PdfFileSecurity}. هناك 4 طرق لاستخدام هذه الفئة: 1. استخدام الامتياز المحدد مسبقًا مباشرةً. 2. بناءً على امتياز محدد مسبقًا وتغيير بعض الأذونات المحددة. 3. بناءً على امتياز محدد مسبقًا وتغيير بعض تركيبة أذونات Adobe Professional المحددة. 4. دمج الطريقة 2 والطريقة 3. //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | يسرد أنواع الترميز المستخدمة للنص. |
| [Facade](./facade/) | فئة الواجهة الأساسية. |
| [FontColor](./fontcolor/) | فئة تمثل لون النص. |
| [Form](./form/) | فئة تمثل كائن نموذج Acro. |
| [Form.ImportStatus](./form.importstatus/) | حالة الحقل المستورد |
| [FormattedText](./formattedtext/) | فئة تمثل النص المنسق. تحتوي على معلومات حول النص ولونه وحجمه ونمطه. |
| [FormEditor](./formeditor/) | فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك). |
| [FormEditorWeb](./formeditorweb/) | فئة لتعديل النماذج (إضافة/حذف الحقول إلخ) |
| [FormFieldFacade](./formfieldfacade/) | فئة لتمثيل خصائص الحقل. |
| [FormWeb](./formweb/) | تمثيل واجهة نموذج Acro. |
| [InternalHelper](./internalhelper/) | فئة المساعدة |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | فئة لتحديد معلمات تغيير حجم الصفحة. تسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات الفضاء الافتراضية أو كنسبة مئوية من حجم الصفحات الأصلية؛ الهوامش اليسرى، العليا، السفلية واليمنى بوحدات الفضاء الافتراضية أو كنسبة مئوية من حجم الصفحة الأصلية؛ يمكن ترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من باقي حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض صفحة جديد 60 وحدة فإن الهوامش اليسرى واليمنى تُحسب تلقائيًا: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | قيمة الهامش أو حجم المحتوى المحددة كنسبة مئوية من وحدات الفضاء الافتراضية. تُستخدم هذه الفئة في ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | يمثل معلومات السطر. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | يمثل فئة للعمل مع تعليقات مستند PDF (التعليقات). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | يمثل فئة للعمل مع إشارات PDF بما في ذلك الإنشاء، التعديل، التصدير، الاستيراد والحذف. |
| [PdfContentEditor](./pdfcontenteditor/) | يمثل فئة لتعديل محتوى ملف PDF. |
| [PdfConverter](./pdfconverter/) | يمثل فئة لتحويل كل صفحة من ملف PDF إلى صور، يدعم الآن BMP و JPEG و PNG و TIFF. المحتوى المدعوم في ملفات PDF: الصور، النماذج، التعليقات. |
| [PdfExtractor](./pdfextractor/) | فئة لاستخراج الصور والنص من مستند PDF. |
| [PdfFileEditor](./pdffileeditor/) | تنفّذ عمليات على ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيّب، إلخ. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | الإجراء المتخذ عندما يتم مواجهة ملف تالف في عملية الدمج. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | يمثل فئة تحتوي على طريقة مجردة عادةً ما يتم توفيرها من قبل الطرف المستدعي وتتعامل مع أحداث التقدم التي تأتي من عملية الدمج. عادةً ما يمكن استخدام معالج العميل المقدم لعرض التقدم الكلي للدمج على وحدة التحكم أو في شريط التقدم. يمثل معلومات حول حدث التقدم الذي حدث. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | فئة توفر معلومات حول الملفات التالفة أثناء عملية الدمج. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | بيانات موضع فاصل الصفحة. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | هذه الفئة تمثل معلومات حول تقدم الدمج التي يمكن استخدامها في تطبيق خارجي. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | هذا التعداد يصف أنواع أحداث التقدم الممكنة التي يمكن أن تحدث أثناء الدمج |
| [PdfFileEditorWeb](./pdffileeditorweb/) | يمثل فئة PdfFileEditorWeb التي تنفذ عمليات مع ملف PDF: الدمج، التقسيم، استخراج الصفحات، إنشاء كتيب، إلخ. |
| [PdfFileInfo](./pdffileinfo/) | يمثل فئة للوصول إلى المعلومات الوصفية لوثيقة PDF. |
| [PdfFileMend](./pdffilemend/) | يمثل فئة لإضافة النصوص والصور على صفحات وثيقة PDF الموجودة. |
| [PdfFileSanitization](./pdffilesanitization/) | يمثل واجهة برمجة تطبيقات التطهير والاستعادة. استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى. |
| [PdfFileSecurity](./pdffilesecurity/) | يمثل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم، وتغيير إعدادات الأمان وكلمة المرور. |
| [PdfFileSignature](./pdffilesignature/) | يمثل فئة لتوقيع ملف pdf باستخدام شهادة. |
| [PdfFileStamp](./pdffilestamp/) | فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF. |
| [PdfFileStampWeb](./pdffilestampweb/) | فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF. تمكين العمل مع HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | فئة لإزالة جميع شفرة Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | يمثل فئة لتعديل صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، نقل الموضع وتغيير حجم الصفحة. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | يمثل كائن يحتوي على معلومات صفحة الطباعة الحالية. |
| [PdfProducer](./pdfproducer/) | <p> يمثل فئة لإنتاج PDF من صيغ أخرى. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | يمثل الطريقة التي تتعامل مع حدث QueryPageSettings في PrintDocument. |
| [PdfViewer](./pdfviewer/) | يمثل فئة لعرض أو طباعة ملف pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | فئة للتعامل مع بيانات XMP الوصفية. |
| [PositioningMode](./positioningmode/) | يحدد وضع التموضع. القيم الممكنة تشمل Legacy (التوافق مع الإصدارات السابقة) وCurrent (طريقة حساب موضع النص المحدثة). |
| [PropertyFlag](./propertyflag/) | تعداد لعلامات الحقول الممكنة. |
| [ReplaceTextStrategy](./replacetextstrategy/) | هذه الفئة تحتوي على معلمات تحدد سلوك PdfContentEditor عند تنفيذ عملية ReplaceText. |
| [SaveableFacade](./saveablefacade/) | <p> الفئة الأساسية لجميع الواجهات القابلة للحفظ.</p> |
| [SignatureName](./signaturename/) | يمثل فئة لاسم التوقيع. يمثل اسم توقيع أكثر دقة. يستخدم بدلاً من أسماء السلاسل. يسمح لك بعرض التوقيعات بنفس أسماء السلاسل. |
| [Stamp](./stamp/) | فئة تمثل الطابع. |
| [StampInfo](./stampinfo/) | فئة تمثل معلومات الطابع. |
| [TextProperties](./textproperties/) | يمثل خصائص النص مثل: حجم النص، اللون، النمط، إلخ. |
| [VerticalAlignmentType](./verticalalignmenttype/) | فئة تمثل قيم المحاذاة العمودية الممكنة. استخدم VerticalAlignment بدلاً من ذلك |
| [ViewerPreference](./viewerpreference/) | يصف تفضيلات المشاهد (وضع الصفحة، وضع الصفحة غير ملء الشاشة، تخطيط الصفحة). |
| [WordWrapMode](./wordwrapmode/) | يحدد استراتيجيات التفاف الكلمات |
## Enums

| تعداد | الوصف |
| --- | --- |
| [Algorithm](./algorithm/) | يمثل الخوارزميات التي يمكن استخدامها لتشفير مستند PDF. |
| [BlendingColorSpace](./blendingcolorspace/) | الفئة تمثل مساحة لون الدمج. |
| [FieldType](./fieldtype/) | تعداد لأنواع الحقول الممكنة. |
| [FontStyle](./fontstyle/) | يعدّ 14 نوعًا من الخطوط. |
| [ImageMergeMode](./imagemergemode/) | يمثل أوضاع دمج الصور. |
| [KeySize](./keysize/) | يحدد أحجام المفاتيح المختلفة التي يمكن استخدامها لتشفير مستندات PDF. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | الإجراء الذي يجب اتخاذه إذا لم يحتوي الخط على الحرف المطلوب |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | النطاق الذي يتم فيه تطبيق عملية استبدال النص REPLACE_FIRST بشكل افتراضي. |
| [StampType](./stamptype/) | يصف أنواع الطوابع. |
| [SubmitFormFlag](./submitformflag/) | تعداد لأعلام نموذج الإرسال الممكنة. |
