---
title: "com.aspose.pdf"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الحزمة com.aspose.pdf هي حزمة جذر لجميع فئات مكتبة Aspose.PDF لـ Java والتي تكون إما مباشرةً فيها مثل Document أو غير مباشرةً عبر عدة حزم فرعية."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf/
---
الحزمة com.aspose.pdf هي حزمة جذر لجميع فئات مكتبة Aspose.PDF لـ Java والتي تكون إما مباشرةً فيها مثل Document أو غير مباشرةً عبر عدة حزم فرعية.

## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | إجراء الاستدعاء العكسي للتعرف على hocr. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | إجراء الاستدعاء العكسي للتعرف على hocr. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | إجراء الاستدعاء العكسي للتعرف على hocr. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | يحتوي على وظائف لضبط الخطوط |
| [IAnnotationVisitor](./iannotationvisitor/) | يحدد Visitor لزيارة تعليقات المستند المختلفة. |
| [IAppointment](./iappointment/) | يمثل واجهة عامة للإجراءات والوجهات. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | واجهة لاستراتيجيات تحويل مساحة الألوان. |
| [IDocument](./idocument/) | واجهة تمثل مستند PDF |
| [IFontOptions](./ifontoptions/) | خصائص مفيدة لضبط سلوك الخط |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | تم إعلان هذه الواجهة لتخصيص خوارزميات التكميم. يمكن للمستخدمين تنفيذ تحقيقهم الخاص لهذه الخوارزميات (على سبيل المثال خوارزميات تعتمد على كود غير مُدار). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | تم إعلان هذه الواجهة لتخصيص خوارزميات التكميم. يمكن للمستخدمين تنفيذ تحقيقهم الخاص لهذه الخوارزميات (على سبيل المثال خوارزميات تعتمد على كود غير مُدار). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | يحدد Visitor لزيارة عوامل pdf المختلفة. |
| [IPageSetOptions](./ipagesetoptions/) | يحدد خيارات التحويل المتعلقة بمجموعة من الصفحات للتحويل. |
| [IPipelineOptions](./ipipelineoptions/) | يحدد خيارات التحويل المتعلقة بتكوين خط الأنابيب. |
| [ITableElement](./itableelement/) | تمثل هذه الواجهة عنصرًا من جدول موجود مستخرج بواسطة TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | في بعض الأحيان يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة، ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال أثناء استخدام Aspose.PDf في السحابة لا يمكن الوصول مباشرة إلى الملفات المشار إليها، ويجب استخدام بعض الشيفرة المخصصة الموضوعة في طريقة خاصة. هذا المفوض يحدد توقيع تلك الطريقة المخصصة. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * تعيين العلامة ما إذا كان سيتم استخدام المجلد المؤقت لاستضافة بيانات الخط المؤقت. / * صحيح بشكل افتراضي. / * يستخدم ذاكرة الكومة إذا كانت القيمة = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | إلى خاصية من هذا النوع يمكنك تعيين مفوض تم إنشاؤه من طريقة مخصصة تنفّذ معالجة حفظ الصورة الخارجية التي تم استخراجها من SVG تم إنشاؤه من PDF ويجب حفظها كموارد خارجية أثناء تحويل PDF إلى HTML. في هذه الحالة يمكن إجراء المعالجة (مثل الحفظ اليدوي إلى تدفق أو إلى قرص) في تلك الشيفرة المخصصة ويجب على تلك الشيفرة المخصصة إرجاع مسار (أو أي سلسلة أخرى بدون علامات اقتباس) سيتم دمجه لاحقًا في SVG المُولَّد بدلاً من المسار الأصلي المفترض لتلك الصورة. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ الصورة في كود الطريقة المقدَّمة، لأن حفظ النتيجة في كود المحول لن يُستخدم. إذا كان يجب معالجة هذا أو ذاك الملف لسبب ما بواسطة كود المحول نفسه، وليس في الشيفرة المخصصة، يرجى تعيين في الشيفرة المخصصة العلامة 'CustomProcessingCancelled' لمتغيّر معلمة 'imageSavingInfo'. هذا يُشير إلى المحول بأن جميع الخطوات الضرورية لمعالجة ذلك المورد يجب أن تُنفَّذ في المحول نفسه كما لو لم يكن هناك أي شيفرة مخصصة خارجية. |
## الفئات

| فئة | الوصف |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | يمثل خلية جدول موجودة في الصفحة |
| [AbsorbedRow](./absorbedrow/) | يمثل صف جدول موجود في الصفحة |
| [AbsorbedTable](./absorbedtable/) | يمثل جدول موجود في الصفحة |
| [ActionCollection](./actioncollection/) | مجموعة من الإجراءات |
| [Annotation](./annotation/) | فئة تمثّل كائن التعليق التوضيحي. |
| [AnnotationActionCollection](./annotationactioncollection/) | يمثل مجموعة إجراءات التعليق التوضيحي. |
| [AnnotationCollection](./annotationcollection/) | فئة تمثّل مجموعة التعليقات التوضيحية. |
| [AnnotationFlags](./annotationflags/) | العلامات مجموعة من العلامات الثنائية التي تحدد خصائص مختلفة للتعليق التوضيحي. |
| [AnnotationSelector](./annotationselector/) | تُستخدم هذه الفئة لاختيار التعليقات التوضيحية باستخدام فكرة قالب الزائر. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | فئة لتصيير النص العادي والنص الغني. |
| [AppearanceDictionary](./appearancedictionary/) | قاموس مظهر التعليق التوضيحي يحدد كيف يجب عرض التعليق بصريًا على الصفحة. |
| [ApsLoadOptions](./apsloadoptions/) | فئة تصف خيارات تحميل APS. خيار للاستيراد من تنسيق APS XML. |
| [ApsSaveOptions](./apssaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق APS XML. |
| [ApsToFlowConverter](./apstoflowconverter/) | تحويل APS إلى تدفق |
| [Artifact](./artifact/) | فئة تمثّل كائن قطعة PDF. |
| [ArtifactCollection](./artifactcollection/) | فئة تمثّل مجموعة القطع. |
| [AutoTaggingSettings](./autotaggingsettings/) | توفر إعدادات لوظيفة الوسم التلقائي في مستندات PDF. تسمح فئة {@link AutoTaggingSettings} بتكوين الخيارات للوسم التلقائي لمحتوى PDF. تشمل الخصائص لتمكين أو تعطيل الوسم التلقائي، وتحديد استراتيجية للتعرف على العناوين، وتعريف مستويات العناوين بناءً على أحجام الخط. |
| [BackgroundArtifact](./backgroundartifact/) | فئة تصف قطعة الخلفية. تسمح هذه القطعة بتعيين خلفية الصفحة. |
| [BarcodeField](./barcodefield/) | فئة تمثّل حقل الباركود. |
| [BaseActionCollection](./baseactioncollection/) | فئة تُغلف الإجراءات الأساسية مع إجراءات تفاعلية للصفحة/التعليق التوضيحي/الحقل. |
| [BaseOperatorCollection](./baseoperatorcollection/) | يمثل الفئة الأساسية لمجموعة المشغلين. |
| [BaseParagraph](./baseparagraph/) | يمثل كائنًا أساسيًا مجردًا يمكن إضافته إلى الصفحة (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | الفئة تصف قطعة Bates Numbering. |
| [BitmapInfo](./bitmapinfo/) | كائن يحتوي على مصفوفة من البكسلات ومعلومات bitmap. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | تنسيق بكسل bitmap. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | يمثل توضيح علامة Bleed Mark. تُوضع علامات Bleed Mark في زوايا الصفحة المطبوعة لتحديد مكان قص الصفحة ومدى السماح بالانحراف عن علامات القص. |
| [Border](./border/) | الفئة التي تمثل خصائص حد التوضيح. |
| [BorderInfo](./borderinfo/) | هذه الفئة تمثل الحد لعناصر الرسوميات. |
| [BorderSide](./borderside/) | العلامات تُعدد الجوانب الثنائية للحد. |
| [BorderStyleConverter](./borderstyleconverter/) | يمثل الفئة BorderStyleConverter. |
| [Brush](./brush/) | هذه الفئة تمثل فرشاة مجردة. |
| [BuildVersionInfo](./buildversioninfo/) | هذه الفئة توفر معلومات حول بناء المنتج الحالي. |
| [ButtonField](./buttonfield/) | الفئة تمثل حقل زر الضغط. |
| [CaretAnnotation](./caretannotation/) | الفئة التي تمثل توضيح Caret. |
| [CaretSymbolConverter](./caretsymbolconverter/) | يمثل الفئة CaretSymbolConverter. |
| [CdrLoadOptions](./cdrloadoptions/) | الفئة تصف خيارات تحميل CDR. |
| [Cell](./cell/) | يمثل خلية من صف الجدول. |
| [Cells](./cells/) | يمثل مجموعة خلايا للصف. |
| [CgmImportOptions](./cgmimportoptions/) | خيار استيراد لاستيراد من تنسيق Computer Graphics Metafile (CGM). |
| [CgmLoadOptions](./cgmloadoptions/) | يحتوي على خيارات لتحميل/استيراد ملف CGM إلى مستند pdf. |
| [Characteristics](./characteristics/) | يمثل خصائص التوضيح |
| [CharInfo](./charinfo/) | يمثل كائن معلومات الحرف. يوفر معلومات تموضع الحرف. |
| [CharInfoCollection](./charinfocollection/) | <p> يمثل مجموعة كائنات CharInfo. </p> <hr> <pre> يوضح المثال كيفية التكرار عبر جميع الأحرف واستخراج الحرف //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> يوفر الوصول إلى معلومات تموضع أحرف مقطع النص. </p> |
| [CheckboxField](./checkboxfield/) | الفئة التي تمثل حقل خانة الاختيار. |
| [ChoiceField](./choicefield/) | يمثل الفئة الأساسية لحقول الاختيار. |
| [CircleAnnotation](./circleannotation/) | الفئة التي تمثل توضيح دائرة. |
| [Collection](./collection/) | يمثل الفئة Collection (12.3.5 Collections). |
| [CollectionField](./collectionfield/) | يمثل فئة حقل مخطط مجموعة المستندات. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | يمثل معامل النوع الفرعي لحقل في مجموعة المخطط. |
| [CollectionItem](./collectionitem/) | يمثل فئة عنصر مجموعة. يحتوي عنصر المجموعة على البيانات الموصوفة في مخطط المجموعة. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | يمثل فئة لقيمة عنصر المجموعة. |
| [CollectionSchema](./collectionschema/) | يمثل فئة تصف "المخطط" لمجموعة المستندات. |
| [Color](./color/) | يمثل فئة لقيمة اللون التي يمكن التعبير عنها في فضاءات ألوان مختلفة. |
| [ColorBarAnnotation](./colorbarannotation/) | فئة تمثل تعليقة ColorBarAnnotation. يتم تجاهل الخاصية Color، ويتم استخدام لون ColorsOfCMYK بدلاً منها. عند الإنشاء، يحدد نسبة العرض إلى الارتفاع اتجاه التعليقة - أفقي أو عمودي. بعد ذلك، يتم التحقق من أن مستطيل التعليقة خارج TrimBox، وإذا لم يكن كذلك، يتم إزاحته إلى أقرب موقع خارج TrimBox مع مراعاة اتجاه التعليقة. يمكن تقليل العرض (الارتفاع) بحيث تتناسب التعليقة خارج TrimBox. إذا لم يتوفر مساحة للتخطيط، يمكن ضبط العرض/الارتفاع على الصفر (في هذه الحالة، تكون التعليقة موجودة على الصفحة ولكنها غير معروضة). |
| [ColumnInfo](./columninfo/) | تمثل هذه الفئة معلومات العمود. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | فئة تمثل الأحداث. |
| [ComboBoxField](./comboboxfield/) | فئة تمثل حقل صندوق القوائم في النموذج. |
| [ComHelper](./comhelper/) | <p> يوفر طرقًا لعملاء COM لتحميل مستند إلى Aspose.PDF. </p> <hr> <p> استخدم فئة ComHelper لتحميل مستند من ملف أو تدفق إلى كائن Document في تطبيق COM. توفر فئة Document مُنشئًا افتراضيًا لإنشاء مستند جديد وتوفر أيضًا مُنشئات محملة لتحميل مستند من ملف أو تدفق. إذا كنت تستخدم Aspose.Words من تطبيق .NET، يمكنك استخدام جميع مُنشئات Document مباشرة، ولكن إذا كنت تستخدم Aspose.PDF من تطبيق COM، فإن مُنشئ Document الافتراضي هو المتاح فقط. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | فئة مجردة تمثل تعليقة الشكل الشائعة. |
| [CompositingParameters](./compositingparameters/) | يمثل كائنًا يحتوي على معلمات تركيبة الرسومات لحالة الرسومات الحالية. |
| [ContentsAppender](./contentsappender/) | يُجري تعديلات على المحتوى في وضع APPEND فقط. يسمح هذا الوضع بتجنب تحليل المحتوى غير الضروري والثقيل قبل إجراء أي تغيير على المحتوى. يضيف فقط عوامل تشغيل جديدة إلى نهاية أو بداية المحتوى. |
| [Copier](./copier/) | فئة لنسخ الكائن. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | يمثل أنواع التعليقات التي تُوضع في زوايا الصفحة المطبوعة. |
| [CustomExplicitDestination](./customexplicitdestination/) | يمثل وجهة صريحة مخصصة. |
| [CustomSign](./customsign/) | مُفوض لتوقيع المستند مخصصًا (نسخة تجريبية). |
| [Dash](./dash/) | فئة تمثل نمط الخط المتقطع. |
| [DateField](./datefield/) | حقل تاريخ مع عرض تقويمي. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | يصف المظهر الافتراضي للحقل (الخط، حجم النص واللون). |
| [DefaultDirectory](./defaultdirectory/) | يحدد المسار الافتراضي لغرض ما. |
| [DestinationCollection](./destinationcollection/) | فئة تمثل مجموعة جميع الوجهات (شجرة أسماء تربط سلاسل الأسماء بالوجهات (انظر 12.3.2.3، "الوجهات المسماة") و(انظر 7.7.4، "قاموس الأسماء")) في مستند PDF. |
| [DestinationFactory](./destinationfactory/) | يمثل فئة DestinationFactory. |
| [DjvuLoadOptions](./djvuloadoptions/) | فئة تصف خيارات تحميل DJVU. |
| [DocMDPSignature](./docmdpsignature/) | يمثل فئة نوع توقيع مستند MDP (كشف التعديل ومنعه). |
| [DocSaveOptions](./docsaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق Doc |
| [Document](./document/) | فئة تمثل مستند PDF. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | فئة تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources(). @deprecated هذه الفئة مهجورة. يرجى استخدام com.aspose.pdf.optimization.OptimizationOptions بدلاً من ذلك. |
| [Document.RepairOptions](./document.repairoptions/) | يمثل خيارات إصلاح مستند PDF. توفر هذه الفئة طريقة لتخصيص عملية إصلاح مستند PDF. |
| [DocumentActionCollection](./documentactioncollection/) | فئة تصف الإجراءات التي تُجرى على بعض العمليات مع المستند |
| [DocumentExtensions](./documentextensions/) | توفر قدرات إضافية لفئة Document. |
| [DocumentFactory](./documentfactory/) | فئة تسمح بإنشاء/تحميل مستندات بأنواع مختلفة. |
| [DocumentInfo](./documentinfo/) | يمثل المعلومات الوصفية لمستند PDF. |
| [DocumentWeb](./documentweb/) | يمثل فئة DocumentWeb |
| [Element](./element/) | فئة تمثل العنصر الأساسي للهيكل المنطقي. |
| [ElementCollection](./elementcollection/) | مجموعة من عناصر الهيكل المنطقي الأساسية. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | فئة تمثل مجموعة الملفات المضمنة. |
| [EncryptedPayload](./encryptedpayload/) | يمثل الحمولة المشفرة في مواصفات الملف. |
| [EpubLoadOptions](./epubloadoptions/) | يحتوي على خيارات تحميل/استيراد ملف EPUB إلى مستند PDF. |
| [EpubSaveOptions](./epubsaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق EPUB |
| [ExcelSaveOptions](./excelsaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق Excel |
| [ExplicitDestination](./explicitdestination/) | يمثل الفئة الأساسية للوجهات الصريحة في مستند PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | يمثل فئة ExplicitDestinationTypeConverter |
| [ExportFieldsOptions](./exportfieldsoptions/) | يمثل الفئة الأساسية للخيارات الخاصة بتصدير حقول النموذج. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | يمثل خيارات تصدير حقول النموذج إلى تنسيق Json. يرث من {@link ExportFieldsOptions} ويضيف خيارات محددة لتصدير Json. |
| [ExportImportMessages](./exportimportmessages/) | يحتوي على رسائل خطأ مختلفة لعمليات تصدير واستيراد حقول النموذج. |
| [ExternalSignature](./externalsignature/) | ينشئ توقيع PKCS#7Detached منفصل باستخدام X509Certificate2. يدعم بطاقات ذكية USB، والرموز دون مفاتيح خاصة قابلة للتصدير. |
| [FdfReader](./fdfreader/) | فئة تقوم بقراءة تنسيق FDF. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf"); |
| [Field](./field/) | الفئة الأساسية لحقول النموذج Acro. |
| [FieldSerializationResult](./fieldserializationresult/) | يمثل نتيجة عملية تسلسل حقل النموذج. |
| [FieldSerializationStatus](./fieldserializationstatus/) | يمثل حالة تسلسل حقل النموذج. |
| [FieldValueType](./fieldvaluetype/) | يمثل نوع قيمة الحقل في مجموعة المخطط. |
| [FigureElement](./figureelement/) | فئة تمثل شكل البنية المنطقية. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | فئة تصف ملاحظة مرفق الملف. |
| [FileFontSource](./filefontsource/) | يمثل مصدر ملف خط واحد. |
| [FileHyperlink](./filehyperlink/) | يمثل كائن ارتباط تشعبي للملف. |
| [FileIconConverter](./fileiconconverter/) | يمثل فئة FileIconConverter |
| [FileParams](./fileparams/) | يحدد قاموس معلمات الملف المضمّن الذي يجب أن يحتوي على معلومات إضافية خاصة بالملف. |
| [FileSelectBoxField](./fileselectboxfield/) | حقل لعنصر صندوق اختيار الملف. |
| [FileSpecification](./filespecification/) | فئة تمثل ملفًا مضمّنًا. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع تكبير محتواها بما يكفي لتناسب صندوق الحدود بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع توسيط صندوق الحدود داخل النافذة في البعد الآخر. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي العمودي العلوي عند حافة النافذة العليا وتكبير محتوى الصفحة بما يكفي لتناسب العرض الكامل لصندوق الحدود داخل النافذة. قيمة null للعلوي تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي الأفقي الأيسر عند حافة النافذة اليسرى وتكبير محتوى الصفحة بما يكفي لتناسب الارتفاع الكامل لصندوق الحدود داخل النافذة. قيمة null للأيسر تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير. |
| [FitExplicitDestination](./fitexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع تكبير محتواها بما يكفي لتناسب الصفحة بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع توسيط الصفحة داخل النافذة في البعد الآخر. |
| [FitHExplicitDestination](./fithexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي العمودي العلوي عند حافة النافذة العليا وتكبير محتوى الصفحة بما يكفي لتناسب العرض الكامل للصفحة داخل النافذة. قيمة null للعلوي تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع تكبير محتواها بما يكفي لتناسب المستطيل المحدد بالإحداثيات اليسار، الأسفل، اليمين، والعلوي بالكامل داخل النافذة أفقياً وعمودياً. إذا كانت عوامل التكبير الأفقية والعمودية المطلوبة مختلفة، استخدم الأصغر منهما، مع توسيط المستطيل داخل النافذة في البعد الآخر. قد يؤدي قيمة null لأي من المعاملات إلى سلوك غير متوقع. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | يمثل وجهة صريحة تعرض الصفحة مع وضع إحداثي الأفقي الأيسر عند حافة النافذة اليسرى وتكبير محتوى الصفحة بما يكفي لتناسب الارتفاع الكامل للصفحة داخل النافذة. قيمة null للأيسر تشير إلى أنه يجب الاحتفاظ بالقيمة الحالية لهذا المعامل دون تغيير. |
| [FixedPrint](./fixedprint/) | يمثل بيانات طباعة ثابتة لتعليق العلامة المائية. |
| [FloatingBox](./floatingbox/) | يمثل صندوقًا عائمًا في مستند PDF. الصندوق العائم يتم وضعه مخصصًا. |
| [FlowConverter](./flowconverter/) | تحويل مستند PDF إلى صيغ تدفق (XLSX، ODS، XMLSpreedSheet2003، CSV) DOCX في وضع EnchanedFlow، وTableAbsorber في وضع FlowEngine. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | تمرير البيانات من مكتبة Flow إلى TableAbsorber |
| [FolderFontSource](./folderfontsource/) | يمثل المجلد الذي يحتوي على ملفات الخطوط. |
| [Font](./font/) | <p> يمثل كائن الخط. </p> <hr> <pre> يوضح المثال كيفية البحث عن النص في الصفحة الأولى وتغيير خط أول ظهور للبحث. // Open document Document doc = new Document("input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | يمثل كائن ماص للخطوط. يقوم بالبحث عن الخطوط ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code FontAbsorber.Fonts}. |
| [FontCollection](./fontcollection/) | <p> يمثل مجموعة الخطوط. </p> <hr> <pre> يوضح المثال كيفية جعل جميع الخطوط المعلنة على الصفحة مضمّنة. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\\\Tests\\\\input.pdf"); </pre> <hr> <p> يتم استخدام مجموعات الخطوط التي تمثلها الفئة {@code FontCollection} في عدة سيناريوهات. على سبيل المثال، في الموارد التي تحتوي على الخاصية {@code Resources.Fonts}. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | يتطلب معيار PDF/A أن يتم تضمين جميع الخطوط في المستند. تتضمن هذه الفئة علامات للحالات التي لا يمكن فيها تضمين بعض الخطوط لأن هذا الخط غير موجود على جهاز الكمبيوتر الوجهة. |
| [FontRepository](./fontrepository/) | <p> ينفّذ بحثًا عن الخطوط. يبحث في الخطوط المثبتة على النظام وخطوط PDF القياسية. كما يوفر وظيفة لفتح الخطوط المخصصة. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط نص الصفحة الأولى. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | يمثل الفئة الأساسية لمصدر الخط. |
| [FontStyles](./fontstyles/) | Binary Flag <p> يحدد معلومات النمط المطبقة على النص. </p> <hr> <p> يحتوي هذا التعداد على سمة {@code FlagsAttribute} التي تسمح بدمج قيم أعضائه. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag يعدد الاستراتيجيات لتقسيم الخطوط. |
| [FooterArtifact](./footerartifact/) | يصف عنصر التذييل. يمكن استخدامه لتعيين تذييل الصفحة. |
| [Form](./form/) | فئة تمثل كائن النموذج. |
| [Form.FlattenSettings](./form.flattensettings/) | فئة تصف إعدادات إجراء تسطيح النموذج. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | يمكن للنماذج أن تحتوي على معلومات توقيع ويمكن أن تكون موقعة أو غير موقعة. أحيانًا يجب أن يعتمد عرض النماذج في العارض على ما إذا كان النموذج موقّعًا أم لا. يعدد هذا التعداد أوضاع العرض الممكنة أثناء تحويل نوع النموذج فيما يتعلق بالتوقيع. |
| [FormattedFragment](./formattedfragment/) | يمثل جزءًا منسقًا تجريديًا. |
| [FreeTextAnnotation](./freetextannotation/) | يمثل تعليقة نص حر تعرض النص مباشرة على الصفحة. على عكس تعليقة النص العادية، لا تمتلك تعليقة النص الحر حالة فتح أو إغلاق؛ بدلاً من عرضها في نافذة منبثقة، يكون النص دائمًا مرئيًا. |
| [GoToAction](./gotoaction/) | يمثل إجراء انتقل إلى الذي يغيّر العرض إلى وجهة محددة (صفحة، موقع، وعامل تكبير). |
| [GoToRemoteAction](./gotoremoteaction/) | يمثل إجراء انتقل إلى عن بُعد يشبه إجراء الانتقال إلى العادي لكنه يقفز إلى وجهة في ملف PDF آخر بدلاً من الملف الحالي. |
| [GoToURIAction](./gotouriaction/) | يمثل إجراء URI يتسبب في حل URI. |
| [GraphInfo](./graphinfo/) | يمثل معلومات الرسومات. |
| [Group](./group/) | فئة سمات المجموعة التي تحدد سمات مجموعة صفحات الصفحة للاستخدام في نموذج التصوير الشفاف. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | الفئة تصف قطعة Heaader. قد تُستخدم هذه artifacgt لتعيين عنوان الصفحة. |
| [HeaderFooter](./headerfooter/) | الفئة تمثل رأس أو تذييل صفحة PDF. |
| [Heading](./heading/) | يمثل العنوان. |
| [HideAction](./hideaction/) | يمثل إجراء إخفاء يقوم بإخفاء أو إظهار تعليق أو أكثر على الشاشة عن طريق ضبط أو مسح علامات Hidden الخاصة بها. |
| [HighlightAnnotation](./highlightannotation/) | يمثل تعليقة تمييز تُبرز نطاقًا من النص في المستند. |
| [HtmlFragment](./htmlfragment/) | يمثل جزءًا من HTML. |
| [HtmlLoadOptions](./htmlloadoptions/) | يمثل خيارات تحميل/استيراد ملف HTML إلى مستند PDF. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | العلم الثنائي يحدد العلامات التي مع خيارات أخرى تحدد أحجام وتخطيطات الصفحات. |
| [HtmlSaveOptions](./htmlsaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق HTML. |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | هذا التعداد يصف إجراءات مكافحة التعرجات الممكنة أثناء التحويل. |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | هذه الفئة تمثل مجموعة من البيانات المتعلقة بالحفظ المخصص لملفات CSS أثناء تحويل PDF إلى تنسيق HTML. |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | يمكنك تعيين لهذه الخاصية استراتيجية مخصصة تنفّذ معالجة أو/و حفظ جزء من CSS تم إنشاؤه أثناء تحويل PDF إلى HTML. في هذه الحالة يجب أن تُجرى المعالجة (مثل الحفظ إلى تدفق أو قرص) في ذلك الكود المخصص. |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | يمكنك تعيين لهذه الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفّذ إنشاء عنوان URL لملف CSS المشار إليه في مستند HTML المُولد. على سبيل المثال، إذا أردت جعل CSS مشارًا إليه في HTML مثل "otherPage.ASPX?CssID=zjjkklj" فيجب أن تُعيد هذه الاستراتيجية المخصصة "otherPage.ASPX?CssID=zjjkklj". |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | يمثل مجموعة من البيانات المتعلقة بطلب من المحول إلى الكود المخصص للحصول على عنوان URL (أو قالب URL) المطلوب لملف CSS المعني. |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | هذا التعداد يحدد القواعد التي تضبط منطق الترميز. |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | يعدّ الأنماط التي يمكن استخدامها لحفظ الخطوط المشار إليها في ملف PDF المحفوظ. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملف صورة المورد الخارجي أثناء تحويل PDF إلى HTML. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | يعدّ الأنواع الممكنة لملفات الصور التي يمكن حفظها كمورد خارجي أثناء تحويل PDF إلى HTML. |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | أحيانًا تكون هناك متطلبات محددة للـ HTML المُنشأ. هذا التعداد يحدد أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية هذه المتطلبات المحددة. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | إذا كان خاصية SplitToPages في HtmlSaveOptions مفعلة، فسيتم إنشاء عدة ملفات HTML (ملف HTML واحد لكل صفحة محوّلة) أثناء تحويل PDF إلى HTML. هذه الفئة تمثل مجموعة من البيانات المتعلقة بالحفظ المخصص لعلامات صفحة HTML واحدة أثناء تحويل PDF إلى HTML. |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | قد يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML (التي قد تشير أيضًا إلى ملفات خارجية مثل الصور أو الخطوط). يمكنك تعيين لهذه الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفّذ معالجة صفحة HTML التي تم إنشاؤها أثناء التحويل (HTML نفسه). في هذه الحالة يمكن إجراء المعالجة (مثل الحفظ إلى تدفق أو قرص) في ذلك الكود المخصص. يجب تنفيذ جميع الإجراءات اللازمة لحفظ علامات صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يُستخدم. إذا كان يجب، لسبب ما، أن تُجرى المعالجة في كود المحول نفسه وليس في الكود المخصص، يرجى ضبط علامة 'CustomProcessingCancelled' في متغيّر معلمة 'htmlSavingInfo' داخل الكود المخصص: فهي تُشير إلى المحول بأن جميع الخطوات الضرورية لمعالجة هذا المورد يجب أن تُنفّذ في المحول نفسه كما لو لم يكن هناك أي كود حفظ مخصص خارجي. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | يعدّ الأنواع الممكنة لأولياء صور الصورة التي يمكن أن تنتمي إلى صفحة HTML أو إلى صورة أصلية SVG. |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | هذا التعداد يعدد أوضاع الإدماج الممكنة للملفات المشار إليها في HTML. يسمح بالتحكم فيما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، CSS) ستُدمج في ملف HTML الرئيسي أم ستُنشأ ككيانات ثنائية منفصلة. |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | قد يحتوي ملف PDF المحوّل على صور نقطية (.png، *.jpeg وغيرها). هذا التعداد يحدد طرق معالجة الصور النقطية أثناء تحويل PDF إلى HTML. |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | يمكنك إسناد إلى هذه الخاصية مفوض تم إنشاؤه من طريقة مخصصة تنفّذ معالجة المورد الخارجي (خط أو صورة) الذي تم استخراجها من PDF ويجب حفظه كمورد خارجي أثناء تحويل PDF إلى HTML. في هذه الحالة يمكن تنفيذ المعالجة (مثل الحفظ في تدفق أو على القرص) في ذلك الكود المخصص ويجب على هذا الكود المخصص إرجاع المسار (أو أي سلسلة أخرى بدون علامات اقتباس) التي سيتم دمجها لاحقًا في HTML المُولَّد بدلاً من المسار الأصلي المفترض لتلك الصورة. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ الصورة في شفرة الطريقة المقدَّمة، لأن حفظ النتيجة في شفرة المحول لن يُستَخدم. إذا كان من الضروري لسبب ما أن تتم معالجة هذا الملف أو ذاك الملف بواسطة شفرة المحول نفسها، وليس في الكود المخصص، يرجى تعيين في الكود المخصص العلامة 'CustomProcessingCancelled' لمتغيّر معلمة 'resourceSavingInfo'. هذا يُشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفّذ في المحول نفسه كما لو لم يكن هناك أي كود مخصص خارجي. |
| [Hyperlink](./hyperlink/) | يمثل ارتباطًا تشعبيًا مجردًا. |
| [IconFit](./iconfit/) | يصف كيفية عرض أيقونة ملاحظة الودجت داخل مستطيل الملاحظة الخاص بها. |
| [Id](./id/) | <p> يمثل بنية معرف الملف. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | يمثل صورة. |
| [ImageDeleteAction](./imagedeleteaction/) | الإجراء الذي يُنفّذ مع كائن الصورة عندما تُزال الصورة من المجموعة. إذا تم إزالة كائن الصورة |
| [ImagePlacement](./imageplacement/) | <p> يمثل خصائص الصورة الموضوعة في صفحة مستند PDF. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> عند وضع صورة في صفحة قد تكون أبعادها مختلفة عن الأبعاد الفيزيائية المعرفة في {@code Resources}. الهدف من الكائن {@code ImagePlacement} هو توفير مثل هذه المعلومات مثل الأبعاد، الدقة، وما إلى ذلك. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> يمثل كائن ماص لكائنات وضع الصورة. يقوم بالبحث عن استخدامات الصورة ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> يوضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على خصائص وضع الصورة. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> كائن {@code ImagePlacementAbsorber} يُستخدم أساسًا في سيناريو البحث عن الصور. عندما يكتمل البحث يتم تمثيل النتائج بكائنات {@code ImagePlacement} التي تحتويها مجموعة {@code ImagePlacementAbsorber.ImagePlacements}. يوفر كائن {@code ImagePlacement} الوصول إلى خصائص وضع الصورة: الأبعاد، الدقة، إلخ. </p> دوران الصورة الإيجابي يكون عكس اتجاه عقارب الساعة، بالنسبة للصفحة يكون مع اتجاه عقارب الساعة. هنا، نحتاج إلى تمثيل زاوية دوران الصورة، لذا نطرح زاوية الصفحة من زاوية الصورة. |
| [ImagePlacementCollection](./imageplacementcollection/) | يمثل مجموعة مواضع الصور |
| [ImageStamp](./imagestamp/) | يمثل ختمًا رسوميًا. |
| [ImageType](./imagetype/) | يمثل أنواع صيغ الصور. |
| [ImportDataAction](./importdataaction/) | عند استدعاء إجراء استيراد البيانات، سيتم استيراد بيانات تنسيق نماذج البيانات (FDF) إلى النموذج التفاعلي للمستند من ملف محدد. |
| [ImportFieldsOptions](./importfieldsoptions/) | يمثل الفئة الأساسية للخيارات الخاصة باستيراد حقول النموذج. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | يمثل خيارات استيراد حقول النموذج إلى تنسيق Json. يرث من {@code ImportFieldsOptions} ويضيف خيارات محددة لاستيراد Json. |
| [ImportOptions](./importoptions/) | نوع ImportOptions يحتفظ بمستوى التجريد للخيارات الفردية للاستيراد. |
| [InkAnnotation](./inkannotation/) | يمثل \"خربشة\" يدوية تتكون من مسار واحد أو أكثر غير متصل. |
| [InternalHelper](./internalhelper/) | فئة داخلية |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | الاستثناء الذي يُرمى عندما تكون عملية مع نوع النموذج غير صالحة. |
| [JavascriptAction](./javascriptaction/) | فئة تمثل إجراء جافاسكريبت. |
| [JavaScriptCollection](./javascriptcollection/) | هذه الفئة تمثل مجموعة من جافاسكريبت. |
| [LatexFragment](./latexfragment/) | يمثل جزء TeX. @deprecated يرجى استخدام TeXFragment بدلاً من ذلك |
| [LatexLoadOptions](./latexloadoptions/) | يمثل خيارات تحميل/استيراد ملف TeX إلى مستند PDF. @deprecated استخدم TeXLoadOptions بدلاً من ذلك. |
| [LaTeXSaveOptions](./latexsaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق TeX. @deprecated استخدم TeXSaveOptions بدلاً من ذلك |
| [LaunchAction](./launchaction/) | يمثل إجراء إطلاق يقوم بتشغيل تطبيق أو فتح أو طباعة مستند. |
| [Layer](./layer/) | يمثل طبقة داخل صفحة PDF. |
| [LevelFormat](./levelformat/) | يمثل تنسيق جدول المحتويات. |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. في هذا المثال، سيتم محاولة العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | يمثل معلومات الترخيص. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | مجموعة مشغّلات خفيفة الوزن. يُقصد استخدامها في السيناريوهات التي لا يكون فيها تدفق المحتوى الأساسي مرفقًا، حيث يُطلب فقط مجموعة المشغّلات كنتيجة. |
| [LineAnnotation](./lineannotation/) | فئة تمثل تعليقات الخط. |
| [LineEndingConverter](./lineendingconverter/) | يمثل فئة LineEndingConverter |
| [LineEndingsDrawer](./lineendingsdrawer/) | يرسم نهايات الخط للتعليقات. فئة داخلية للاستخدام الداخلي فقط. |
| [LinkAnnotation](./linkannotation/) | يمثل إما رابطًا تشعبيًا إلى وجهة أخرى في المستند أو إجراءً يجب تنفيذه. |
| [ListBoxField](./listboxfield/) | الفئة تمثل حقل ListBox. |
| [LoadOptions](./loadoptions/) | نوع LoadOptions يحمل مستوى التجريد على خيارات التحميل الفردية |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | يمثل وضع استخدام مساحة الهوامش أثناء التحويل (مثل HTML، EPUB إلخ)، يحدد معالجة تعليمات التنسيق المستورد المتعلقة باستخدام الهوامش. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | تنبيه! تم تنفيذ الميزة ولكن لم تُضمّن بعد في واجهة برمجة التطبيقات العامة بسبب وجود مشكلة عائق في طبقة OSHARED تم اكتشافها في المستند النموذجي. يمثل وضع استخدام حجم الصفحة أثناء التحويل. الصيغ (مثل HTML، EPUB إلخ) عادةً ما تكون ذات تصميم عائم، لذا يسمح بتلائم حجم الصفحة المطلوب. لكن أحيانًا يحدد المحتوى مواضع أفقية أو حجم لا يسمح بوضع المحتوى في حجم الصفحة المطلوب. في هذه الحالة يمكننا تحديد ما يجب القيام به (أي عندما لا يتناسب حجم المحتوى مع حجم الصفحة الأولي المطلوب في مستند PDF الناتج). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | نتيجة التحميل المخصص للمورد |
| [LocaleOptions](./localeoptions/) | نوع LocaleOptions يحدد تكوين اللغة لـ Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | يمثل كائن الارتباط التشعبي المحلي. |
| [MarginInfo](./margininfo/) | هذه الفئة تمثل هامشًا لكائنات مختلفة. |
| [MarkupAnnotation](./markupannotation/) | فئة مجردة تمثل توضيح العلامة. |
| [MarkupParagraph](./markupparagraph/) | يمثل فقرة. |
| [MarkupSection](./markupsection/) | يمثل قسم العلامة - المنطقة المستطيلة في صفحة تحتوي على نص ويمكن فصلها بصريًا عن كتل النص الأخرى. |
| [Matrix](./matrix/) | الفئة تمثل مصفوفة التحويل. |
| [Matrix3D](./matrix3d/) | الفئة تمثل مصفوفة التحويل. |
| [MdLoadOptions](./mdloadoptions/) | خيارات التحميل لتحويل صيغة Markdown. |
| [Measure](./measure/) | الفئة التي تصف نظام إحداثيات Measure. |
| [Measure.NumberFormat](./measure.numberformat/) | تنسيق الرقم للقياس. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | يمثل قائمة تنسيقات الأرقام. |
| [MediaClip](./mediaclip/) | الفئة تصف كائن مقطع الوسائط في العرض. |
| [MediaClipData](./mediaclipdata/) | الفئة تصف بيانات مقطع الوسائط. |
| [MediaClipSection](./mediaclipsection/) | هذه الفئة تصف قسم مقطع الوسائط. |
| [MediaRendition](./mediarendition/) | الفئة تصف عرض الوسائط. |
| [MemoryCleaner](./memorycleaner/) | يمثل فئة MemoryCleaner |
| [MemoryExtender](./memoryextender/) | يمثل فئة MemoryExtender. باستخدام ملفات كبيرة على نظام بذاكرة كومة محدودة، يمكن تمكينه لاستخدام مساحة القرص كذاكرة تبديل مؤقتة. |
| [MemoryFontSource](./memoryfontsource/) | يمثل مصدر ملف خط واحد. |
| [Metadata](./metadata/) | يوفر الوصول إلى تدفق بيانات XMP الوصفية. |
| [Metered](./metered/) | <p> يوفر طرقًا لتعيين المفتاح المقيس. </p> <hr> في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص المقيس <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey(\"PublicKey\", \"PrivateKey\"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | يمثل خيارات تحميل/استيراد ملف .mht إلى مستند pdf. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | خيارات الحفظ لتصدير إلى تنسيق Xml |
| [MovieAnnotation](./movieannotation/) | يمثل توضيح فيلم يحتوي على رسومات متحركة وصوت يتم عرضه على شاشة الكمبيوتر ومن خلال السماعات. عند تفعيل التوضيح، يتم تشغيل الفيلم. |
| [NamedAction](./namedaction/) | يمثل الإجراءات المسماة التي من المتوقع أن تدعمها تطبيقات عارض PDF. |
| [NamedDestination](./nameddestination/) | بدلاً من تعريفه مباشرةً باستخدام الصياغة الصريحة، يمكن الإشارة إلى الوجهة بصورة غير مباشرة عبر كائن اسم أو سلسلة بايت. |
| [Note](./note/) | هذه الفئة تمثل ملاحظة فقرة المولد. |
| [NumberField](./numberfield/) | حقل نص مع أحرف صالحة محددة @see TextBoxField |
| [NumberTree](./numbertree/) | فئة تمثل بنية شجرة الأرقام لملف PDF. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | يمثل إعدادات ocsp المستخدمة أثناء عملية التوقيع. |
| [OfdLoadOptions](./ofdloadoptions/) | خيارات التحميل لتنسيق OFD. |
| [Operator](./operator/) | فئة مجردة تمثل المشغل. |
| [OperatorCollection](./operatorcollection/) | الفئة تمثل مجموعة من المشغلات |
| [OperatorSelector](./operatorselector/) | تُستخدم هذه الفئة لاختيار المشغلات باستخدام فكرة قالب Visitor. |
| [Opi](./opi/) | يمثل Open Prepress Interface (OPI) آلية لإنشاء نواقل منخفضة الدقة أو وكلاء لتلك الصور عالية الدقة. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | يحدد MemoryStream يمكنه احتواء سعة قياسية أكبر |
| [Option](./option/) | الفئة تمثل خيار حقل الاختيار. |
| [OptionCollection](./optioncollection/) | فئة تمثل مجموعة خيارات حقل الاختيار. |
| [OutlineCollection](./outlinecollection/) | يمثل تسلسل هيكل مخطط المستند. |
| [OutlineItemCollection](./outlineitemcollection/) | يمثل مدخل المخطط في تسلسل هيكل المخطط لوثيقة PDF. |
| [Outlines](./outlines/) | الفئة تصف مجموعة المخططات. |
| [OutputIntent](./outputintent/) | يمثل نية الإخراج التي تتطابق مع خصائص اللون لوثيقة PDF مع خصائص جهاز الإخراج المستهدف أو بيئة الإنتاج التي سيُطبع فيها المستند. |
| [OutputIntents](./outputintents/) | يمثل مجموعة {@link OutputIntent}. |
| [Page](./page/) | فئة تمثل صفحة من وثيقة PDF. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | إجراء لتخصيص الرأس والتذييل. |
| [PageActionCollection](./pageactioncollection/) | هذه الفئة تصف إجراءات الصفحة |
| [PageCollection](./pagecollection/) | مجموعة صفحات وثيقة PDF. |
| [PageExtensions](./pageextensions/) | يوفر إمكانيات إضافية لفئة Page. |
| [PageInfo](./pageinfo/) | يمثل معلومات الصفحة لمولد pdf. |
| [PageInformationAnnotation](./pageinformationannotation/) | يمثل توضيح Page Information في مستند PDF. يحتوي هذا التوضيح على اسم الملف ورقم الصفحة وتاريخ ووقت إنشاء التوضيح. تُستخدم هذه الفئة أساسًا لإضافة بيانات وصفية إلى صفحة محددة في مستند PDF، مما يمكن أن يكون مفيدًا لأغراض التتبع والإشارة. على سبيل المثال، يمكن استخدامها لتعليم الصفحات أثناء عملية الطباعة أو لتوفير معلومات إضافية عن الصفحة عند عرض المستند. |
| [PageLabel](./pagelabel/) | فئة تمثل نطاق Page Label. |
| [PageLabelCollection](./pagelabelcollection/) | فئة تمثل مجموعة تسميات الصفحة. |
| [PageMarkup](./pagemarkup/) | تمثيل تنسيق الصفحة بواسطة مجموعات من {@code MarkupSection} و {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | يمثل ختم رقم الصفحة ويُستخدم لترقيم الصفحات. |
| [PageSize](./pagesize/) | فئة تمثل حجم الصفحة في مستند PDF. |
| [PaginationArtifact](./paginationartifact/) | يمثل فئة أساسية مجردة لقطع الترقيم في مستند. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> يمثل كائن ماص لهيكل الصفحة مثل الأقسام والفقرات. يقوم بالبحث عن الأقسام والفقرات النصية ويوفر الوصول إلى المستطيلات والمتعددات التي تصفه في مساحة إحداثيات النص. كما يقوم بالبحث عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر مجموعات {@code TextFragments} المجمعة حسب عناصر الهيكل. </p> يوضح المثال كيفية العثور على أول مقطع نصي لكل فقرة في الصفحة الأولى من مستند PDF وتظليله. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> عند إكمال البحث ستحتوي مجموعة {@code ParagraphAbsorber.PageMarkups} على كائنات {@code PageMarkup} التي تمثل هيكل الصفحة بواسطة مجموعات {@code MarkupSection} و {@code MarkupParagraph}. يوفر كائن {@code TextFragment} الوصول إلى نص نتيجة البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | يمثل خيارات لـ {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | هذه الفئة تمثل مجموعة الفقرات. |
| [PasswordBoxField](./passwordboxfield/) | فئة تصف حقل النص لإدخال كلمة المرور. |
| [PclLoadOptions](./pclloadoptions/) | يمثل خيارات لتحميل (استيراد) ملف PCL إلى مستند pdf. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | يسرد محركات التحويل التي يمكن استخدامها في التحويل. |
| [PDF3DAnnotation](./pdf3dannotation/) | فئة PDF3DAnnotation. لا يمكن وراثة هذه الفئة. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | فئة PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | فئة PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | فئة PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | فئة PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | فئة PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | فئة PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | فئة PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | فئة PDF3DStream. |
| [PDF3DView](./pdf3dview/) | فئة PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | الفئة PDF3DViewArray. |
| [PdfAction](./pdfaction/) | يمثل الإجراء في مستند PDF |
| [PdfActionCollection](./pdfactioncollection/) | الفئة تصف قائمة الإجراءات. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | هذه الفئة تصف القواعد التي يمكن استخدامها لضبط عملية نسخ بيانات الترميز للحالات التي يكون فيها خط TrueType الرمزي يحتوي على أكثر من ترميز واحد. بعض مستندات PDF بعد التحويل إلى تنسيق PDF/A قد تُظهر خطأ \"More than one encoding in symbolic TrueType font's cmap\". ما هو سبب هذا الخطأ؟ جميع خطوط TrueType الرمزية لديها جدول خاص \"cmap\" في بياناتها الداخلية. هذا الجدول يطابق رموز الأحرف مع مؤشرات الحروف. ويمكن لهذا الجدول أن يحتوي على جداول فرعية للترميز مختلفة تصف الترميزات المستخدمة. راجع معلومات متقدمة حول جداول cmap على https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. عادةً ما يحتوي جدول cmap على عدة جداول فرعية للترميز، لكن معيار PDF/A يتطلب إما ترك جدول فرعي ترميز واحد فقط لهذا الخط في مستند PDF/A أو وجود جدول فرعي ترميز (3,0) بين جداول هذا الخط. والسؤال الرئيسي هنا - ما البيانات التي يجب أخذها من الجداول الفرعية الأخرى لنسخها إلى جدول الترميز الوجهة (3,0)؟ أغلب الخطوط لديها جداول cmap 'مصممة جيدًا' حيث كل جدول فرعي للترميز متسق بالكامل مع جدول فرعي آخر. لكن بعض الخطوط لديها جداول cmap مع تصادمات - حيث على سبيل المثال يحتوي جدول فرعي على مؤشر حرف 100 للـ Unicode 100، بينما يحتوي جدول فرعي آخر على مؤشر حرف 200 لنفس الـ Unicode 100. لحل هذه المشكلات تحتاج استراتيجية خاصة. بشكل افتراضي تُستخدم الاستراتيجية التالية: يتم البحث عن جدول فرعي mac(1,0). إذا تم العثور على هذا الجدول، تُستخدم بياناته فقط لملء جدول الوجهة (3,0). إذا لم يُعثر على جدول فرعي mac فسيتم تكرار جميع الجداول الفرعية باستثناء (3,0) واستخدامها لنسخ البيانات إلى جدول الوجهة (3,0). كما يتم نسخ التعيين لكل Unicode (Unicode، مؤشر الحرف) إلى جدول الوجهة فقط إذا لم يكن جدول الوجهة يحتوي على هذا الـ Unicode في الوقت الحالي. لذا، على سبيل المثال إذا كان للجدول الفرعي الأول مؤشر حرف 100 للـ Unicode 100، وكان للجدول الفرعي التالي مؤشر حرف 200 لنفس الـ Unicode 100، فسيتم نسخ البيانات فقط من الجدول الفرعي الأول (Unicode=100، مؤشر الحرف = 100). وبالتالي كل جدول فرعي سابق يأخذ الأسبقية على التالي. خصائص هذه الفئة { PdfASymbolicFontEncodingStrategy} تساعد على ضبط السلوك الافتراضي. إذا تم تعيين الخاصية {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) من النوع { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}، فسيتم استخدام الجدول الفرعي المناسب بأسبقية على جدول mac(1,0). القيمة 'MacTable' من تعداد {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} لا معنى لها في هذه الحالة، لأنها تشير إلى نفس جدول mac(1,0) الذي يُستخدم افتراضيًا. الخاصية {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) تتجاهل جميع الأولويات لأي جدول فرعي. إذا تم تعيين هذه الخاصية، فستُستخدم فقط الجداول الفرعية من القائمة المعلنة بالترتيب المحدد. إذا لم يتم العثور على الجداول الفرعية المحددة فسيتم استخدام التكرار الافتراضي لجميع الجداول الفرعية واستراتيجية النسخ الموضحة أعلاه. الكائن { PdfASymbolicFontEncodingStrategy.QueueItem} يحدد جدول الترميز الفرعي المستخدم. يمكن تعيين هذا الجدول عبر مجموعة من الأعضاء (PlatformID، PlatformSpecificId) أو عبر تعداد { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. في حالة عدم وجود جدول فرعي (3,0) في الخط، سيُستخدم جدول فرعي آخر للحفاظ على توافق PDF/A. يتم اختيار الجدول الفرعي للاستخدام وفق القواعد نفسها المذكورة سابقًا، بحيث تُستخدم خصائص {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) و{@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) لتحديد الجدول الفرعي الناتج، وإذا لم يكن للخط الجدول الفرعي المطلوب فسيُستخدم أي جدول فرعي موجود. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | يحدد جدول الترميز الفرعي. كل جدول ترميز فرعي له تركيبة فريدة من المعلمات (PlatformID، PlatformSpecificID). تم تنفيذ التعداد {@code CMapEncodingTableType} والخاصية {@code CMapEncodingTable} لتسهيل تحديد جدول الترميز الفرعي المطلوب. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | يعلن مجموعة من جداول الترميز الفرعية المعروفة. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | يمثل مجموعة من الخيارات لتحويل مستند PDF. |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | هذه الفئة تحتفظ بأعلام للتحكم في تحويل PDF/A للحالات التي لا يتطابق فيها مستند PDF المصدر مع مواصفات PDF. إذا تم استخدام أعلام هذه الفئة فإنها تقلل الأداء ولكنها ضرورية عندما لا يمكن تحويل مستند PDF المصدر إلى صيغة PDF/A بالطريقة المعتادة. بشكل افتراضي يتم تعيين جميع الأعلام إلى false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | بعض مستندات PDF تحتوي على رموز يونيكود خاصة، تنتمي إلى منطقة الاستخدام الخاص (PUA)، راجع الوصف على https://en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز تتسبب في أخطاء توافق مع PDF/A مثل "Text is mapped to Unicode Private Use Area but no ActualText entry is present". هذا التعداد يعلن استراتيجيات يمكن استخدامها لمعالجة رموز PUA. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | بعض المستندات تصبح ذات حجم كبير بعد التحويل إلى صيغة PDF/A. لتقليل حجم الملف لهذه المستندات، من الضروري تحديد استراتيجية لإزالة الخطوط. هذا التعداد يعلن استراتيجيات يمكن استخدامها لتحسين استخدام الخطوط. كل استراتيجية من هذا التعداد لها معنى فقط عندما يتم تعيين العلم {@code OptimizeFileSize}. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | يصف الاستراتيجيات المستخدمة لمحاذاة مقاطع نص المستند. حالياً يتم دعم استراتيجية واحدة فقط لإعادة المقاطع إلى حدودها الأصلية. قد تُضاف استراتيجيات أخرى في المستقبل. |
| [PdfPageStamp](./pdfpagestamp/) | الفئة تمثل ختمًا يستخدم صفحة PDF كختم. |
| [PdfSaveOptions](./pdfsaveoptions/) | خيارات الحفظ للتصدير إلى صيغة Pdf. |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | خيارات التحميل لصيغة PdfXml. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | خيارات الحفظ لصيغة PdfXml. |
| [Permissions](./permissions/) | علم ثنائي. هذا التعداد يمثل أذونات المستخدم لملف pdf. |
| [PKCS1](./pkcs1/) | يمثل كائن التوقيع وفقًا لمعيار PKCS#1. يتم استخدام خوارزمية تشفير RSA وطريقة التجزئة SHA-1 للتوقيع. |
| [PKCS7](./pkcs7/) | يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: بنية الرسائل التشفيرية، الإصدار 1.5. يتم تضمين تجزئة SHA1 لنطاق بايتات المستند في حقل PKCS#7 SignedData. |
| [PKCS7Detached](./pkcs7detached/) | يمثل كائن PKCS#7 المتوافق مع مواصفة PKCS#7 في RFC 2315 على الإنترنت، PKCS #7: بنية الرسائل التشفيرية، الإصدار 1.5. يتم دمج تجزئة الرسالة الموقعة الأصلية لنطاق بايتات المستند كحقل PKCS#7 SignedData العادي. لا يتم تضمين أي بيانات في حقل PKCS#7 SignedData. |
| [Point](./point/) | يمثل نقطة ذات إحداثيات كسرية. |
| [Point3D](./point3d/) | يمثل نقطة ذات إحداثيات كسرية. |
| [PolyAnnotation](./polyannotation/) | فئة أساسية مجردة للتعليقات المتعددة. |
| [PolygonAnnotation](./polygonannotation/) | فئة تمثل تعليق مضلع. |
| [PolylineAnnotation](./polylineannotation/) | يمثل تعليق خط متعدد مشابه للمضلع، باستثناء أن القمة الأولى والأخيرة غير متصلتين ضمنيًا. |
| [PopupAnnotation](./popupannotation/) | يمثل تعليق المنبثقة الذي يعرض النص في نافذة منبثقة للإدخال والتحرير. |
| [Position](./position/) | يمثل كائن موقع. |
| [PptxSaveOptions](./pptxsaveoptions/) | خيارات الحفظ للتصدير إلى صيغة SVG. |
| [PrintController](./printcontroller/) | يمثل وحدة تحكم الطباعة. |
| [PrintDuplex](./printduplex/) | خيار معالجة الورق لاستخدامه عند طباعة الملف من مربع حوار الطباعة.. |
| [PrinterMarkAnnotation](./printermarkannotation/) | فئة مجردة تمثل تعليق علامة الطابعة. |
| [PrinterMarksKind](./printermarkskind/) | يحدد أنواع علامات الطابعة التي ستُضاف إلى مستند. يحتوي هذا التعداد على سمة {@link FlagsAttribute} التي تسمح بدمج قيم أعضائه بطريقة بتية. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | يوفر طرق امتداد للتعداد {@link PrinterMarksKind}. |
| [PrintScaling](./printscaling/) | خيار تحجيم الصفحة الذي يجب اختياره عندما يتم عرض مربع حوار الطباعة لهذا المستند. |
| [ProgressEventType](./progresseventtype/) | يصف هذا التعداد أنواع أحداث التقدم الممكنة التي يمكن أن تحدث أثناء التحويل. |
| [PsLoadOptions](./psloadoptions/) | يمثل خيارات تحميل/استيراد ملف .mht إلى مستند pdf. |
| [PsSaveOptions](./pssaveoptions/) | خيارات الحفظ لتصدير إلى صيغة PS (PostScript) أو EPS. |
| [RadioButtonField](./radiobuttonfield/) | فئة تمثل حقل زر الاختيار. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | فئة تمثل عنصرًا من حقل RadioButton. |
| [Rectangle](./rectangle/) | فئة تمثل مستطيل. |
| [Redaction](./redaction/) | للاستخدام الداخلي فقط @author User |
| [RedactionAnnotation](./redactionannotation/) | يمثل تعليقة Redact. |
| [RegexManager](./regexmanager/) | يوفر غلافًا لعمليات التعبيرات النمطية مع إعدادات مهلة قابلة للتكوين. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | يمثل تعليقة علامة التسجيل. علامات التسجيل هي رموز تُضاف إلى ألواح الطباعة أو الشاشات لضمان محاذاة صحيحة للألوان أثناء عملية الطباعة. |
| [RenderingOptions](./renderingoptions/) | يمثل خيارات العرض. |
| [RenderModeType](./rendermodetype/) | تعداد RenderModeType: مجموعة من أنواع وضع العرض. |
| [Rendition](./rendition/) | فئة تصف كائن العرض لتعليقة RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | إجراء عرض يتحكم في تشغيل المحتوى المتعدد الوسائط. |
| [RenditionOperation](./renditionoperation/) | العملية التي يجب تنفيذها عند تشغيل الإجراء. |
| [RenditionType](./renditiontype/) | التعداد يصف الأنواع الممكنة للعرض. |
| [Resources](./resources/) | فئة تمثل موارد الصفحة. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | يمثل ExtGStates مع بعض القيم. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | يمثل استراتيجية تحويل مساحات الألوان من RGB إلى رمادي للجهاز. |
| [RichMediaAnnotation](./richmediaannotation/) | فئة تصف RichMediaAnnotation التي تسمح بتضمين بيانات الفيديو/الصوت في مستند PDF. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | حدث يفعّل التعليقة. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | نوع الوسائط المتعددة. |
| [RichTextBoxField](./richtextboxfield/) | فئة تصف مكوّن محرر النص الغني. |
| [RichTextFontStyles](./richtextfontstyles/) | خيارات تنسيق مقاطع النص في RichText. |
| [RootElement](./rootelement/) | عنصر بنية الجذر. |
| [Row](./row/) | يمثل صفًا في الجدول. |
| [Rows](./rows/) | يمثل مجموعة صفوف من الجدول. |
| [RtfLoadOptions](./rtfloadoptions/) | خيارات التحميل لتنسيق RTF. |
| [SaveOptions](./saveoptions/) | نوع SaveOptions يحتفظ بمستوى التجريد على خيارات الحفظ الفردية |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | مثيل هذه الفئة يمثل معلومات حول الحدود التي يمكن رسمها على بعض مستندات النتيجة. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | يمثل معلومات عن جزء واحد من الحدود (الأعلى، الأسفل، الجانب الأيسر أو الجانب الأيمن) |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | مثيل هذه الفئة يمثل معلومات حول هوامش الصفحة التي يمكن رسمها على بعض مستندات النتيجة. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | يمثل معلومات عن جزء واحد من الهوامش (الأعلى، الأسفل، الجانب الأيسر أو الجانب الأيمن) |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملف المورد الخارجي التي تحدث أثناء تحويل PDF إلى تنسيق آخر (مثلاً HTML). |
| [ScalingMode](./scalingmode/) | نوع التحجيم الذي سيُستخدم. |
| [ScalingReason](./scalingreason/) | الظروف التي يتم فيها تحجيم الأيقونة داخل مستطيل التعليق. |
| [ScreenAnnotation](./screenannotation/) | تعليق شاشة يحدد منطقة من الصفحة يمكن تشغيل مقاطع الوسائط فيها. |
| [SelectorRendition](./selectorrendition/) | الفئة تصف تمثيل المُحدد. |
| [Signature](./signature/) | فئة مجردة تمثل كائن التوقيع في مستند PDF. التوقيعات هي حقول ذات قيم كائنات التوقيع، وتحتوي الأخيرة على بيانات تُستخدم للتحقق من صحة المستند. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | فئة مجردة تمثل كائن مظهر مخصص للتوقيع. |
| [SignatureField](./signaturefield/) | يمثل حقل نموذج التوقيع. |
| [SignHash](./signhash/) | مفوّض لتوقيع تجزئة المستند مخصصًا (نسخة تجريبية). |
| [SoundAnnotation](./soundannotation/) | يمثل تعليق صوتي يحتوي على صوت مسجل من ميكروفون الحاسوب أو مستورد من ملف. |
| [SoundData](./sounddata/) | يمثل بيانات صوتية تحدد الصوت الذي سيُشغل عند تفعيل التعليق. |
| [SoundEncoding](./soundencoding/) | تنسيق الترميز للبيانات العينية. |
| [SoundIcon](./soundicon/) | يسرد الأيقونات التي ستُستخدم في عرض التعليق. |
| [SoundIconConverter](./soundiconconverter/) | يمثل فئة SoundIconConverter |
| [SoundSampleData](./soundsampledata/) | يمثل إدخالات إضافية خاصة بكائن صوت (القسم 9.2 PDF1-7) |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | تنسيق الترميز لبيانات عينة الصوت. |
| [SquareAnnotation](./squareannotation/) | فئة تمثل التعليق التوضيحي المربع. |
| [SquigglyAnnotation](./squigglyannotation/) | يمثل التعليق التوضيحي المتعرج الذي يظهر كخط سفلي متعرّج في نص المستند. |
| [Stamp](./stamp/) | فئة مجردة لأنواع مختلفة من الطوابع التي تأتي كفروع. |
| [StampAnnotation](./stampannotation/) | <p> يمثل التعليق التوضيحي للطابع المطاطي. هذا النوع من التعليقات يعرض نصًا أو رسومات تهدف إلى الظهور كما لو تم ختمها على الصفحة بطابع مطاطي. </p> <hr> <pre> المقتطف البرمجي التالي يوضح كيفية إضافة طابعين إلى الصفحة الأولى من مستند PDF. يأتي المستند الإدخالي من inFile ويتم حفظ التغييرات في outFile. الطابع الأول له أيقونة NotForPublicRelease والثاني يأتي بصورة من rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | يمثل فئة StampIconConverter |
| [StrikeOutAnnotation](./strikeoutannotation/) | يمثل تعليقًا توضيحيًا بخط شطب يظهر كخط شطب في نص المستند. |
| [StructElement](./structelement/) | عنصر بنية عام. |
| [SubjectNameElements](./subjectnameelements/) | التعداد يصف العناصر في سلسلة موضوع التوقيع. |
| [SubmitFormAction](./submitformaction/) | فئة تصف إجراء submit-form. |
| [SvgLoadOptions](./svgloadoptions/) | يمثل خيارات تحميل/استيراد ملف SVG إلى مستند PDF. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | يسرد محركات التحويل التي يمكن استخدامها في التحويل. |
| [SvgSaveOptions](./svgsaveoptions/) | خيارات الحفظ للتصدير إلى صيغة SVG. |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | هذه الفئة تمثل مجموعة من البيانات المتعلقة بحفظ ملف صورة المورد الخارجي أثناء تحويل PDF إلى HTML. |
| [Symbology](./symbology/) | الرموز (Barcode) تحدد التفاصيل التقنية لنوع معين من الباركود: عرض الخطوط، مجموعة الأحرف، طريقة الترميز، مواصفات المجموع الاختباري، إلخ. |
| [SystemFontSource](./systemfontsource/) | يمثل جميع الخطوط المثبتة على النظام. |
| [TabAlignmentType](./tabalignmenttype/) | يعدّ أنواع محاذاة التبويب. |
| [Table](./table/) | يمثل جدولًا يمكن إضافته إلى الصفحة. |
| [TableAbsorber](./tableabsorber/) | <p> يمثل كائن ماص لعناصر الجدول. يقوم بالبحث ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TableAbsorber.TableList} . </p> <hr> <pre> المثال يوضح كيفية العثور على جدول في الصفحة الأولى من مستند PDF واستبدال النص في خلية جدول. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | يعدّ أنواع القادة للتبويب. |
| [TableBroken](./tablebroken/) | يعدّ الجدول المكسور. |
| [TabOrder](./taborder/) | ترتيب التبويب على الصفحة |
| [TabStop](./tabstop/) | يمثل موضع توقف تبويب مخصص في فقرة. |
| [TabStops](./tabstops/) | يمثل مجموعة من كائنات {@code TabStop}. |
| [TeXFragment](./texfragment/) | يمثل جزء LaTeX. |
| [TeXLoadOptions](./texloadoptions/) | يمثل خيارات تحميل/استيراد ملف TeX إلى مستند PDF. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | ينفّذ جلب تدفق إخراج من الذاكرة. يمكنك استخدامه، على سبيل المثال، عندما لا ترغب في كتابة الإخراج المرافق (مثل ملف سجل) إلى القرص ولكنك تريد قراءته لاحقًا من الذاكرة. |
| [TeXSaveOptions](./texsaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق TeX |
| [TextAbsorber](./textabsorber/) | <p> يمثل كائن ماص للنص. يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن {@code TextAbsorber.Text}. </p> <hr> <pre> يوضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> يستخدم كائن {@code TextAbsorber} لاستخراج النص من مستند PDF أو صفحة المستند. </p> |
| [TextAnnotation](./textannotation/) | يمثل تعليقا نصيًا هو "ملاحظة لاصقة" مرفقة بنقطة في مستند PDF. |
| [TextBoxField](./textboxfield/) | فئة تمثل حقل صندوق النص. |
| [TextBuilder](./textbuilder/) | يضيف كائن النص إلى صفحة PDF. |
| [TextDefaults](./textdefaults/) | يحدد القيم الافتراضية لنظام النص الفرعي |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | يحدد نوع القيم الافتراضية لنظام النص الفرعي |
| [TextEditOptions](./texteditoptions/) | يصف خيارات عمليات تحرير النص. |
| [TextElement](./textelement/) | عنصر نص عام في بنية المستند المنطقية. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | يصف حدوث خطأ استخراج النص في مستند PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | يمثل الموقع في مستند PDF حيث ظهر خطأ استخراج النص. |
| [TextExtractionOptions](./textextractionoptions/) | يمثل خيارات استخراج النص |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. راجع فئة {@code TextDevice}. |
| [TextFormattingOptions](./textformattingoptions/) | يمثل خيارات تنسيق النص |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | يحدد تفاصيل تباعد الأسطر |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | يحدد استراتيجيات التفاف الكلمات |
| [TextFragment](./textfragment/) | <p> يمثل جزءًا من نص Pdf. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص وخطّه. // فتح المستند Document doc = new Document("input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير النص وخط أول مرة ظهور للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // حفظ المستند doc.save("output.pdf"); </pre> <hr> <pre> في بضع كلمات، يحتوي كائن {@code TextFragment} على قائمة من كائنات {@code TextSegment}. بالتفصيل: نص مستند pdf في {@code com.aspose.pdf} يُمثَّل بواسطة كائنين أساسيين: {@code TextFragment} و {@code TextSegment} الاختلافات بينهما تعتمد في الغالب على السياق. لننظر في السيناريو التالي. يقوم المستخدم بالبحث عن النص "hello world" للتعامل معه، وتغيير خصائصه، وما إلى ذلك. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> تمثيل النص pdf الفيزيائي معقد جدًا. قد يتكون النص "hello world" من عدة مقاطع نصية مستقلة فيزيائيًا. نموذج نص Aspose.Pdf يوضح أساسًا أن كائن {@code TextFragment} يوفر مجموعة عمليات منطقية واحدة فوق مجموعة {@code TextSegment} الفيزيائية التي تمثل استعلام المستخدم. في سيناريو البحث النصي، يمثل {@code TextFragment} تمثيل النص "hello world" المنطقي، وتجمع كائنات {@code TextSegment} يمثل جميع المقاطع الفيزيائية التي تُكوّن كائن النص "hello world". لذلك، فإن {@code TextFragment} قريب من تمثيل النص المنطقي. و {@code TextSegment} قريب من تمثيل النص الفيزيائي. من الواضح أن كل كائن {@code TextSegment} قد يمتلك خطه الخاص، وتلوينه، وخصائص التموقع. يوفر {@code TextFragment} طريقة بسيطة لتغيير النص بخصائصه: تعيين الخط، تعيين حجم الخط، تعيين لون الخط، إلخ. في الوقت نفسه، يمكن الوصول إلى كائنات {@code TextSegment} ويستطيع المستخدمون التعامل مع كائنات {@code TextSegment} بشكل مستقل. <p> لاحظ أن تغيير خصائص TextFragment قد يغيّر مجموعة {@code Segments} الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان متطلبك هو ترك مجموعة {@code Segments} دون تغيير، يرجى تغيير المقاطع الداخلية بشكل فردي. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> يمثل كائن ماص لشرائح النص. ينفّذ بحثًا في النص ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextFragmentAbsorber.TextFragments}.</p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> كائن {@code TextFragmentAbsorber} يُستخدم أساسًا في سيناريو بحث النص. عندما يكتمل البحث تُمثَّل الوقائع بواسطة كائنات {@code TextFragment} التي تحتويها مجموعة {@code TextFragmentAbsorber.TextFragments}. كائن {@code TextFragment} يوفر الوصول إلى نص الوقائع، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | يمثل مجموعة شظايا النص |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> يمثل حالة نصية لشظية النص. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: الخط ({@code TextFragmentState.Font} الخاصية) حجم الخط ({@code TextFragmentState.FontSize} الخاصية) نمط الخط ({@code TextFragmentState.FontStyle} الخاصية) لون المقدمة ({@code TextFragmentState.ForegroundColor} الخاصية) لون الخلفية ({@code TextFragmentState.BackgroundColor} الخاصية) <p> لاحظ أن تغيير خصائص {@code TextFragmentState} قد يغيّر مجموعة {@code TextFragment.Segments} الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان مطلبك هو ترك مجموعة {@code TextFragment.Segments} دون تغيير، يرجى تعديل المقاطع الداخلية بشكل فردي. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | يسرد الأيقونات التي ستُستخدم في عرض التعليق. |
| [TextIconConverter](./texticonconverter/) | يمثل فئة TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | فئة أساسية مجردة لتعليمات توضيح النص. |
| [TextOptions](./textoptions/) | يمثل خيارات معالجة النص |
| [TextParagraph](./textparagraph/) | <p> يمثل فقرات النص ككائن نص متعدد الأسطر. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن فقرة نصية وإلحاقه بصفحة PDF. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // إنشاء فقرة نصية TextParagraph paragraph = new TextParagraph(); // تعيين مستطيل الفقرة paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // تعيين خيارات التفاف الكلمات paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // إلحاق سطر النص paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // إلحاق الفقرة بصفحة PDF باستخدام TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // حفظ مستند PDF doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | وضع الخلفية لـ TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | يمثل كائن ماص لفقرات النص. ينفذ بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextParagraphAbsorber.TextParagraphs}. |
| [TextParagraphCollection](./textparagraphcollection/) | يمثل مجموعة فقرات النص |
| [TextReplaceOptions](./textreplaceoptions/) | يمثل خيارات استبدال النص |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | يحدد الإجراء الذي سيتم بعد استبدال جزء من النص بجزء أقصر. None - لا إجراء، قد يتداخل النص المستبدل مع باقي السطر؛ AdjustSpaceWidth - يحاول تعديل المسافات بين الكلمات للحفاظ على طول السطر؛ WholeWordsHyphenation - يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الأيمن للفقرة؛ ShiftRestOfLine - يحرك باقي السطر وفقًا لتغيير طول النص، قد يتغير طول السطر؛ القيمة الافتراضية هي ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | يمثل خيارات بحث النص |
| [TextSegment](./textsegment/) | <p> يمثل مقطعًا من نص PDF. </p> <hr> <pre> يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن {@code TextState} لكائن {@code TextSegment} object. // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع حالات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الماص للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير لون المقدمة للمقطع النصي الأول من أول ظهور للنص absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // تغيير حجم الخط للمقطع النصي الأول من أول ظهور النص absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> باختصار، كائنات {@code TextSegment} هي أبناء كائن {@code TextFragment}. بالتفصيل: نص مستند PDF في {@code Aspose.Pdf} يُمثَّل بواسطة كائنين أساسيين: {@code TextFragment} و {@code TextSegment} الاختلافات بينهما تعتمد في الغالب على السياق. دعنا نأخذ السيناريو التالي في الاعتبار. المستخدم يبحث عن النص "hello world" للتعامل معه، وتغيير خصائصه، وما إلى ذلك. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> تمثيل نص PDF فعليًا معقد جدًا. قد يتكون النص "hello world" من عدة مقاطع نصية مستقلة ماديًا. يحدد نموذج نص Aspose.PDF أساسًا أن كائن {@code TextFragment} يوفر مجموعة عمليات منطقية واحدة على مجموعة كائنات {@code TextSegment} الفيزيائية التي تمثل استعلام المستخدم. في سيناريو البحث عن النص، يُعد {@code TextFragment} تمثيلًا منطقيًا للنص "hello world"، وتجمع كائنات {@code TextSegment} يمثل جميع المقاطع الفيزيائية التي تُكوّن كائن النص "hello world". لذا، فإن {@code TextFragment} قريب من تمثيل النص المنطقي. و{@code TextSegment} قريب من تمثيل النص الفيزيائي. من الواضح أن كل كائن {@code TextSegment} قد يمتلك خطه، لونه، وخصائص التموضع الخاصة به. يوفر {@code TextFragment} طريقة بسيطة لتغيير النص بخصائصه: تعيين الخط، تعيين حجم الخط، تعيين لون الخط، إلخ. في الوقت نفسه، يمكن الوصول إلى كائنات {@code TextSegment} ويستطيع المستخدمون التعامل مع كائنات {@code TextSegment} بشكل مستقل.</p> |
| [TextSegmentCollection](./textsegmentcollection/) | يمثل مجموعة من مقاطع النص |
| [TextStamp](./textstamp/) | يمثل ختمًا نصيًا. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | الإجراء الذي يُنفَّذ إذا لم يحتوي الخط على الحرف المطلوب. |
| [TextState](./textstate/) | يمثل حالة نصية لنص |
| [TextStyle](./textstyle/) | الفئة التي تمثل حقل خانة الاختيار. |
| [TimestampSettings](./timestampsettings/) | يمثل إعدادات ocsp المستخدمة أثناء عملية التوقيع. |
| [TocInfo](./tocinfo/) | يمثل معلومات جدول المحتويات. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | هذه الفئة تصف القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight "لا يمكن تعيين النص إلى Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | يمثل توضيح علامة القص. توضع علامات القص في زوايا الصفحة المطبوعة لتحديد مكان قص الصفحة. |
| [TxtLoadOptions](./txtloadoptions/) | خيارات التحميل لتحويل TXT إلى PDF. |
| [UnderlineAnnotation](./underlineannotation/) | يمثل توضيحًا للخط السفلي الذي يظهر كخط سفلي في نص المستند. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | هذه الفئة تمثل خيارات الحفظ التي تستخدم طريقة تحويل موحدة (مع نموذج مستند داخلي موحد). |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | يمثل فئة تحتوي على طريقة مجردة عادةً ما يتم توفيرها من قبل الجهة المستدعية وتعالج أحداث التقدم التي تأتي من المحول. عادةً ما يمكن استخدام معالج العميل المقدم لعرض التقدم الكلي للتحويل على وحدة التحكم أو في شريط التقدم. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | هذه الفئة تمثل معلومات حول تقدم التحويل يمكن استخدامها في تطبيق خارجي لعرض تقدم التحويل للمستخدم النهائي. |
| [WarningCallback](./warningcallback/) | واجهة لدعم آلية رد الاتصال للمستخدم. |
| [WarningInfo](./warninginfo/) | كائن غير قابل للتغيير لتغليف معلومات التحذير. |
| [WarningType](./warningtype/) | / * نوع التحذير الممثَّل في التعداد. / * / |
| [Watermark](./watermark/) | يمثل علامة مائية للصفحة. |
| [WatermarkAnnotation](./watermarkannotation/) | الفئة تصف كائن توضيح العلامة المائية. |
| [WatermarkArtifact](./watermarkartifact/) | الفئة تصف قطعة العلامة المائية. قد يُستخدم هذا لـ |
| [WebHyperlink](./webhyperlink/) | يمثل كائن ارتباط ويب. |
| [WidgetAnnotation](./widgetannotation/) | الفئة التي تمثل توضيح الودجت. |
| [XFA](./xfa/) | يمثل نموذج XML فيما يتعلق بهندسة نماذج XML (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | فئة للتعامل مع تغليف البيانات ذات الصلة |
| [XfdfReader](./xfdfreader/) | <p> الفئة التي تقوم بقراءة تنسيق XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | يجمع طرق كتابة التعليقات والحقول إلى تنسيق ملف XFDF |
| [XForm](./xform/) | الفئة تمثل XForm |
| [XFormCollection](./xformcollection/) | الفئة تمثل مجموعة XFormCollection. |
| [XImage](./ximage/) | الفئة التي تمثل كائن الصورة X-Object. |
| [XImage.RawParameters](./ximage.rawparameters/) | الفئة التي تمثل معلمات XImage الخام للصورة. |
| [XImageCollection](./ximagecollection/) | الفئة التي تمثل مجموعة XImage. |
| [XmlLoadOptions](./xmlloadoptions/) | يمثل خيارات تحميل/استيراد ملف XML إلى مستند PDF. |
| [XmlSaveOptions](./xmlsaveoptions/) | خيارات الحفظ لتصدير إلى تنسيق Xml |
| [XmpField](./xmpfield/) | يمثل حقل XMP. |
| [XmpFieldType](./xmpfieldtype/) | هذا التعداد يمثل أنواع حقل XMP. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | فئة الخاصية: داخلية أو خارجية. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | هذا المخطط يصف حقلًا في نوع مُنظم. إنه مشابه جدًا لمخطط نوع قيمة خاصية PDF/A، لكنه يحدد حقلًا في بنية بدلاً من خاصية. عنوان مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/field# البادئة المطلوبة لمساحة اسم المخطط: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | يمثل الفئة الأساسية لنسخ الحقل، الخاصية، ونوع القيمة. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | يصف خاصية واحدة. عنوان مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/property# البادئة المطلوبة لمساحة اسم المخطط: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | يصف مخطط امتداد XMP الذي توفره PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | يمثل وصف مخطط امتداد XMP الذي توفره PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | مخطط PDF/A ValueType مطلوب لجميع أنواع قيم الخاصية التي لم يتم تعريفها في مواصفة XMP 2004، أي لأنواع القيم خارج القائمة التالية: - أنواع المصفوفة (هذه أنواع حاوية قد تحتوي على حقل أو أكثر): Alt, Bag, Seq - أنواع القيم الأساسية: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - أنواع قيم إدارة الوسائط: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - نوع قيمة الوظيفة/سير العمل الأساسي: Job - أنواع قيم مخطط EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational عنوان مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/type# البادئة المطلوبة لمساحة اسم المخطط: pdfaType |
| [XmpValue](./xmpvalue/) | يمثل قيمة XMP |
| [XpsLoadOptions](./xpsloadoptions/) | يمثل خيارات تحميل/استيراد ملف xps إلى مستند PDF. |
| [XpsSaveOptions](./xpssaveoptions/) | خيارات الحفظ للتصدير إلى تنسيق Xps |
| [XslFoLoadOptions](./xslfoloadoptions/) | يمثل خيارات تحميل/استيراد ملف XSL-FO إلى مستند PDF. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. هذا التعداد يسرد الاستراتيجيات الممكنة للتعامل مع مثل هذه الأخطاء. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> يمثل الوجهة الصريحة التي تعرض الصفحة بالإحداثيات (اليسار، الأعلى) الموضوعة في الزاوية العليا اليسرى للنافذة ومحتويات الصفحة مكبرة بمعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تشير إلى أن القيمة الحالية لهذا المعامل يجب الاحتفاظ بها دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة. </p> <hr> <p> Document doc = new Document("example.pdf"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| تعداد | الوصف |
| --- | --- |
| [AFRelationship](./afrelationship/) | يصف التعداد علاقة الملفات المرتبطة. |
| [AnnotationState](./annotationstate/) | تعداد الحالات التي يمكن تعيين التعليق الأصلي إليها. |
| [AnnotationStateModel](./annotationstatemodel/) | نموذج الحالة المقابل لحالة التعليق. |
| [AnnotationType](./annotationtype/) | تعداد أنواع التعليقات. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | تعداد الأنواع الفرعية المحتملة للآثار. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | تعداد الأنواع المحتملة للآثار. |
| [BlendMode](./blendmode/) | تعداد أوضاع الدمج. |
| [BorderCornerStyle](./bordercornerstyle/) | يعدّ أنماط زوايا الحدود. |
| [BorderEffect](./bordereffect/) | يصف التأثير الذي يجب تطبيقه على حدود التعليقات. |
| [BorderStyle](./borderstyle/) | يصف نمط حد التعليق. |
| [BoxStyle](./boxstyle/) | يمثل الأنماط لرسم علامة الاختيار في مربع الاختيار. |
| [CapStyle](./capstyle/) | نمط نهاية الخط لخط التعليق بالحبر. |
| [CaptionPosition](./captionposition/) | تعداد موضع تسمية التعليق. |
| [CaretSymbol](./caretsymbol/) | رمز يُرتبط بمؤشر الكتابة. |
| [ColorsOfCMYK](./colorsofcmyk/) | الألوان المشمولة في نموذج اللون CMYK. |
| [ColorSpace](./colorspace/) | تعداد مساحات الألوان. |
| [ColorType](./colortype/) | يحدد نوع اللون للعناصر على الصفحة. |
| [ColumnAdjustment](./columnadjustment/) | يعدّ أنواع تعديل الأعمدة. |
| [ContentDisposition](./contentdisposition/) | رأس Content-Disposition في بروتوكول MIME. |
| [ConvertErrorAction](./converterroraction/) | هذه الفئة تمثل الإجراء لأخطاء التحويل. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | هذا الإجراء يمثل عمليات تحويل الصور ذات القناع الناعم. |
| [ConvertTransparencyAction](./converttransparencyaction/) | هذه الفئة تمثل الإجراء لتحويل الشفافية. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | يمثل نوع الخوارزمية التشفيرية المستخدمة في روتينات التشفير/فك التشفير. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * مساحة الأسماء {@code Aspose.Pdf.Security } تحتوي على فئات تُستخدم للتشفير والتوقيع الرقمي. / * / |
| [DefaultState](./defaultstate/) | يمثل الحالة الافتراضية لطبقة PDF. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | يمثل نوع الخوارزمية التي تحول البيانات إلى "hash" |
| [Direction](./direction/) | اتجاه النص. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | أذونات الوصول الممنوحة لهذا المستند. القيم الصالحة هي: 1 - لا يُسمح بأي تغييرات على المستند؛ أي تعديل على المستند يبطل التوقيع. 2 - التغييرات المسموح بها هي ملء النماذج، إنشاء قوالب الصفحات، والتوقيع؛ التغييرات الأخرى تبطل التوقيع. 3 - التغييرات المسموح بها هي نفسها كما في 2، بالإضافة إلى إنشاء التعليقات التوضيحية، حذفها وتعديلها؛ التغييرات الأخرى تبطل التوقيع. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | يسمح بتحديد تنسيق ملف .doc أو .docx. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | يسمح بالتحكم في كيفية تحويل مستند PDF إلى مستند معالجة نصوص. استخدم وضع RecognitionMode.Textbox عندما لا يُنوي تعديل المستند الناتج بشكل كبير لاحقًا. الصناديق النصية سهلة التعديل عندما لا يكون هناك الكثير للقيام به. استخدم وضع RecognitionMode.Flow عندما يحتاج مستند الإخراج إلى تعديل إضافي. الفقرات وخطوط النص في وضع التدفق تسمح بتعديل النص بسهولة، ولكن كائنات التنسيق غير المدعومة ستظهر أسوأ مما هي عليه في وضع RecognitionMode.Textbox. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | عند تحويل ملف PDF (الذي عادةً ما يكون بتخطيط ثابت)، يحاول محرك التحويل إجراء التجميع والتحليل متعدد المستويات لاستعادة نية مؤلف المستند الأصلي وإنتاج نتيجة بتخطيط تدفقي. هذه الخاصية تضبط ذلك التحويل لهذه أو لتلك الطريقة المرغوبة للتعرف على المحتوى. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | يسرد أنواع الوجهات الصريحة. |
| [ExtendedBoolean](./extendedboolean/) | يمثل نوعًا منطقيًا يدعم القيمة غير المعرفة. |
| [ExtractImageMode](./extractimagemode/) | يحدد أوضاعًا مختلفة يمكن استخدامها أثناء استخراج الصور من المستندات. |
| [FileEncoding](./fileencoding/) | ترميز الملف المرفق. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط. |
| [FileIcon](./fileicon/) | أيقونة تُستخدم في عرض التعليق التوضيحي. |
| [Fixup](./fixup/) | يمثل هذا التعداد نوعًا من Fixup. |
| [FormType](./formtype/) | تعداد الأنواع الممكنة لنموذج Acro Form. |
| [FreeTextIntent](./freetextintent/) | يسرد نوايا التعليق التوضيحي للنص الحر. |
| [HighlightingMode](./highlightingmode/) | يسرد وضع تمييز التعليق التوضيحي، التأثير البصري الذي يُستخدم عندما يتم ضغط زر الفأرة أو الإبقاء عليه داخل المنطقة النشطة. |
| [HorizontalAlignment](./horizontalalignment/) | يصف المحاذاة الأفقية. |
| [HtmlDocumentType](./htmldocumenttype/) | يمثل تعداد أنواع مستندات Html. |
| [HtmlMediaType](./htmlmediatype/) | يحدد أنواع الوسائط الممكنة المستخدمة أثناء العرض. |
| [IconCaptionPosition](./iconcaptionposition/) | يصف موضع الأيقونة. |
| [ImageFileType](./imagefiletype/) | يسرد أنواع ملفات الصورة. |
| [ImageFilterType](./imagefiltertype/) | تعداد يمثل نوع مرشح الصورة. |
| [ImageFormat](./imageformat/) | يمثل هذا التعداد صيغ الصور. |
| [ImportFormat](./importformat/) | يحدد تنسيق الاستيراد. |
| [Justification](./justification/) | يسرد أشكال الضبط (المحاذاة) التي تُستخدم في عرض نص التعليق التوضيحي. |
| [LaunchActionOperation](./launchactionoperation/) | يسرد العمليات التي يجب تنفيذها مع المستند أثناء تنفيذ إجراء الإطلاق. |
| [LettersPositioningMethods](./letterspositioningmethods/) | يسرد أوضاع وضع الحروف في الكلمات في ملف HTML الناتج. |
| [LightingSchemeType](./lightingschemetype/) | تعداد LightingSchemeType: مجموعة من أنواع مخططات الإضاءة. |
| [LineEnding](./lineending/) | يسرد أنماط نهايات الخط التي ستُستخدم في رسم الخط. |
| [LineIntent](./lineintent/) | يسرد نوايا التعليق التوضيحي للخط. |
| [LoadFormat](./loadformat/) | يحدد تنسيق التحميل. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | القيمة التي تشير إلى الطريقة التي تُعرض بها قيم الكسور. |
| [NumberingStyle](./numberingstyle/) | تعداد أنماط ترقيم الصفحات المدعومة لفئة PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | يحدد الموضع في الدفق لاستخدامه في البحث. |
| [PageCoordinateType](./pagecoordinatetype/) | يصف نوع إحداثيات الصفحة. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | يصف تخطيط الصفحة. |
| [PageMode](./pagemode/) | الفئة تصف المكونات المستخدمة لصفحة المستند. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | يحدد المتغير لتحديد موقع العنصر على الصفحة. |
| [PasswordType](./passwordtype/) | هذا التعداد يمثل أنواع كلمات المرور المعروفة المستخدمة في مستندات PDF المحمية بكلمة مرور. |
| [PDF3DActivation](./pdf3dactivation/) | تعداد PDF3DActivation: مجموعة من أوضاع تفعيل التعليقات التوضيحية ثلاثية الأبعاد. |
| [PdfFormat](./pdfformat/) | هذه الفئة تمثل تنسيق PDF. |
| [PdfVersion](./pdfversion/) | هذا التعداد يمثل نسخة ملف PDF. |
| [PolyIntent](./polyintent/) | يسرد نوايا التعليق التوضيحي للمضلع أو الخط المتعدد. |
| [PredefinedAction](./predefinedaction/) | يحدد الإجراءات المختلفة التي يمكن تشغيلها من ملف PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | يمثل موضع علامة في زاوية الصفحة. |
| [PrinterMarkSidePosition](./printermarksideposition/) | يمثل موضع علامة تسجيل على الصفحة. |
| [ReplyType](./replytype/) | يسرد أنواع العلاقات (\"نوع الرد\") بين التعليق التوضيحي والواحد المحدد بواسطة InReplyTo. |
| [ReturnAction](./returnaction/) | التعداد يمثل إجراء سير عمل البرنامج في حالة استدعاء طريقة {@code IWarningCallback.Warning(WarningInfo)}. |
| [Rotation](./rotation/) | تعداد قيم الدوران الممكنة. |
| [SaveFormat](./saveformat/) | يحدد التنسيق |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | يمثل أنواع الخطوط التي يمكن استخدامها في مستند النتيجة لرسم الحدود أو خطوط أخرى |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | يسرد الأنواع الممكنة للموارد الخارجية المحفوظة |
| [StampIcon](./stampicon/) | يسرد الأيقونات التي ستُستخدم في عرض التعليق. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | يسرد الأنواع الممكنة لملفات الصور التي يمكن حفظها كموارد خارجية أثناء تحويل PDF إلى SVG |
| [TextAlignment](./textalignment/) | محاذاة النص في التعليق التوضيحي. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | أنماط معالجة مسار القص |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | سلوك استبدال الخط. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | أنماط تحويل اللغة |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | الإجراء الذي يجب اتخاذه إذا لم يحتوي الخط على الحرف المطلوب |
| [TextRenderingMode](./textrenderingmode/) | وضعية عرض النص، Tmode، تحدد ما إذا كان إظهار النص سيؤدي إلى رسم مخططات الحروف، تعبئتها، استخدامها كحدود قص، أو مزيج من الثلاثة. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | يحدد سياسة لكيفية تعديل حجم خط النص ليتناسب مع المنطقة المحتوية. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | النطاق الذي يتم تطبيق عملية استبدال النص فيه REPLACE_FIRST افتراضيًا. تم الاحتفاظ بهذا الخيار القديم للتوافق. يؤثر على PdfContentEditor ولا يؤثر على TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | تعداد القيم الممكنة لمحاذاة عمودية. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
