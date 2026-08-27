---
title: "الفئة Document"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Document. فئة تمثل مستند PDF"
type: docs
weight: 3900
url: /ar/net/aspose.pdf/document/
---
## Document class

فئة تمثل مستند PDF.

```csharp
public sealed class Document : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Document](document/#constructor)() | يُهيئ مستندًا فارغًا. |
| [Document](document/#constructor_1)(PdfVersion) | يُهيئ مستندًا فارغًا حسب الإصدار. |
| [Document](document/#constructor_2)(Stream) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_11)(string) | فقط ابدأ Document باستخدام *filename*. نفس ما هو في [`Document`](./document/). |
| [Document](document/#constructor_6)(Stream, bool) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | يفتح مستندًا موجودًا من تدفق مع توفير التحويل الضروري للحصول على مستند pdf. |
| [Document](document/#constructor_7)(Stream, string) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_15)(string, bool) | فقط ابدأ Document باستخدام *filename*. نفس ما هو في [`Document`](./document/). |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | يُهيئ نسخة جديدة من الفئة `Document` للعمل مع مستند مشفر. |
| [Document](document/#constructor_12)(string, LoadOptions) | يفتح مستندًا موجودًا من ملف مع توفير خيارات التحويل الضرورية للحصول على مستند pdf. |
| [Document](document/#constructor_16)(string, string) | يُهيئ نسخة جديدة من الفئة `Document` للعمل مع مستند مشفر. |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_9)(Stream, string, bool) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | يُهيئ نسخة جديدة من الفئة `Document` للعمل مع مستند مشفر. |
| [Document](document/#constructor_18)(string, string, bool) | يُهيئ نسخة جديدة من الفئة `Document` للعمل مع مستند مشفر. |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | يُهيئ نسخة جديدة من الفئة `Document` للعمل مع مستند مشفر. |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | تهيئة نسخة جديدة من Document من تدفق *input*. |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | يُهيئ نسخة جديدة من الفئة `Document` للعمل مع مستند مشفر. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | يحصل على إجراءات المستند. هذه الخاصية هي نسخة من الفئة DocumentActions التي تسمح بالحصول/تعيين إجراءات BeforClosing، BeforSaving، إلخ. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | يسمح بدمج محتويات الصفحات لتحسين حجم المستند. إذا تم الاستخدام، قد تشير الصفحات المختلفة ولكن المكررة إلى نفس كائن المحتوى. يرجى ملاحظة أن هذا الوضع قد يسبب آثارًا جانبية مثل تغيير محتوى صفحة عندما يتم تغيير صفحة أخرى. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | يحصل أو يعيّن لون الخلفية للمستند. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | يحصل أو يعيّن علمًا يحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | يحصل على مجموعة من المستند. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | يحصل على إعدادات الأمان إذا كان المستند مشفرًا. إذا لم يكن المستند مشفرًا فسيتم رفع الاستثناء المقابل في .net 1.1 أو سيكون CryptoAlgorithm فارغًا للإصدارات الأخرى من .net. |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | يحصل على معالج أمان مخصص. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | يحصل على مجموعة الوجهات. مهملة. يرجى استخدام NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | يحصل أو يعيّن ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | العديد من العمليات مع الخط لا يمكن تنفيذها إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط. على سبيل المثال لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تعطل التضمين لهذا الخط. تُستخدم هذه العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في مستند PDF الحالي. كن حذرًا عند استخدام هذه العلامة. عندما يتم تعيينها يعني أن الشخص الذي يضع هذه العلامة يتحمل جميع المسؤولية عن أي انتهاكات ترخيص/قانونية على نفسه. لذا يتحمل ذلك على مسؤوليته الخاصة. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر. القيمة الافتراضية false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | يحصل أو يعيّن العلامة التي تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | يحصل على مجموعة الملفات المضمّنة في المستند. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | خاصية تُعلن أن المستند يجب أن يضمّن جميع خطوط Type1 القياسية التي لديها العلامة IsEmbedded مُعيّنة إلى true. يمكن تضمين جميع خطوط PDF في المستند ببساطة عبر تعيين العلامة IsEmbedded إلى true، لكن خطوط Type1 القياسية في PDF استثناء من هذه القاعدة. يتطلب تضمين خطوط Type1 القياسية وقتًا طويلاً، لذا لتضمين هذه الخطوط ليس من الضروري فقط تعيين العلامة IsEmbedded إلى true للخط المحدد ولكن أيضًا تعيين علامة إضافية على مستوى المستند - EmbedStandardFonts = true؛ يمكن تعيين هذه الخاصية مرة واحدة فقط لجميع الخطوط. القيمة الافتراضية false. |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تمكين تسجيل الإشعارات. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | يحصل أو يعيّن العلامة التي تمكّن من إلغاء تحميل المستند جزئيًا من الذاكرة. هذا يسمح بتقليل استهلاك الذاكرة لكنه قد يؤثر سلبًا على الأداء. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع. مفعّلة افتراضيًا. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | اسم ملف PDF الذي تسبب في هذا المستند |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | يحصل أو يعيّن العلامة التي تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة الأولى المعروضة. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | مثيل IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | يحصل على نموذج Acro Form للمستند. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | ارمِ استثناءً إذا كان المستند سيُحفظ مع تغييرات ويحتوي على توقيع |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | يحصل أو يعيّن العلامة التي تحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | يحصل أو يعيّن العلامة التي تحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | يحصل أو يعيّن العلامة التي تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
| [Id](../../aspose.pdf/document/id/) { get; } | يحصل على المعرف. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر. عندما تُنسخ الصفحات من المستند المصدر إلى المستند الوجهة، تتوقف عملية النسخ باستثناء إذا كانت بعض الكائنات في ملفات المصدر تالفة عندما تكون هذه العلامة false. مثال: dest.Pages.Add(src.Pages); إذا تم تعيين هذه العلامة إلى true فستُستبدل الكائنات التالفة بقيم فارغة. القيمة الافتراضية: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | يحصل على معلومات المستند. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | يحصل على حالة التشفير للمستند. True إذا كان المستند مشفرًا. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | يحصل على ما إذا كان المستند متوافقًا مع pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | يحصل على ما إذا كان المستند متوافقًا مع pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | يحصل أو يعيّن ما إذا كان المستند متوافقًا مع pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | مجموعة JavaScript على مستوى المستند. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | يحصل على البنية المنطقية للمستند. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | بيانات تعريف المستند. (قد يتضمن مستند PDF معلومات عامة، مثل عنوان المستند، المؤلف، وتواريخ الإنشاء والتعديل. تُسمى هذه المعلومات العامة عن المستند (على عكس محتواه أو هيكله) بالبيانات الوصفية وتهدف إلى المساعدة في فهرسة والبحث عن المستندات في قواعد البيانات الخارجية.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | مجموعة من الوجهات المسماة في المستند. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | يحصل أو يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | يحصل أو يضبط الإجراء الذي يُنفّذ عند فتح المستند. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | يحصل أو يضبط علامة التحسين. عندما تُضاف صفحات إلى المستند، يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. يتيح ذلك تقليل حجم الملف الناتج لكنه قد يسبب تنفيذًا أبطأ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | يحصل على مخططات المستند. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | يحصل على مجموعة نوايا الإخراج في المستند. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | يحصل أو يضبط معلومات الصفحة. (للمولد فقط، لا تُملأ عند قراءة المستند) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | يحصل على تسميات الصفحات في المستند. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | يحصل أو يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | يحصل أو يضبط وضع الصفحة، محددًا كيفية عرض المستند عند فتحه. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | يحصل أو يضبط مجموعة صفحات المستند. لاحظ أن الصفحات مُرقَّمة بدءًا من 1 في المجموعة. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | يحصل على تنسيق PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | يحصل على أذونات المستند. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | يحصل أو يضبط علامة تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخل. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | يحصل أو يضبط خيار مقياس الصفحة الذي سيُختار عند عرض حوار الطباعة لهذا المستند. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | يحصل على الوصول إلى محتوى TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | يحصل على نسخة من Pdf من رأس ملف Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | احصل واضبط الحد الأقصى لحجم الملف لتحميل الملف بالكامل في الذاكرة. تُحدد القيمة بالميغابايت. القيمة الافتراضية هي 210 ميغابايت. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | يحصل على حالة الترخيص للنظام. يُعيد true إذا كان النظام يعمل في وضع الترخيص وfalse غير ذلك. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | يدمج المستندات. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | يدمج ملفات pdf. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | يدمج المستندات. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | يدمج المستندات. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | ربط xml بالمستند |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | ربط xml بالمستند |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | ربط xml/xsl بالمستند |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | ربط xml/xsl بالمستند |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | ربط xml/xsl بالمستند |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | يغيّر كلمات مرور المستند. يمكن تنفيذ هذا الإجراء فقط باستخدام كلمة مرور المالك. |
| [Check](../../aspose.pdf/document/check/)(bool) | يتحقق من صحة المستند. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | تحويل المستند باستخدام خيارات التحويل المحددة |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | التعرف على الصور داخل المستند وإضافة سلاسل hocr فوقها. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | التعرف على الصور داخل المستند وإضافة سلاسل hocr فوقها. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | تحويل المستند وحفظ الأخطاء في الدفق المحدد. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | تحويل المستند بتطبيق الـ Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | تحويل المستند بتطبيق الـ Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | تحويل الصفحة إلى PNG لتدفق صورة DSR، OMR، OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | يفك تشفير المستند. استدعِ ثم احفظ للحصول على نسخة غير مشفرة من المستند. |
| [Dispose](../../aspose.pdf/document/dispose/)() | يغلق جميع الموارد المستخدمة من قبل هذا المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | يشفر المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | يشفر المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | يشفر المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | يشفر المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | يشفر المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | يشفر المستند. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | تصدير جميع تعليقات المستند إلى الدفق. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | تصدير جميع تعليقات المستند إلى ملف XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | إزالة جميع الحقول من المستند ووضع قيمها بدلاً منها. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | إزالة جميع الحقول (والتعليقات) من المستند ووضع قيمها بدلاً منها. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | استبدال المحتوى الشفاف برسومات نقطية ومتجهة غير شفافة. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | مسح الذاكرة |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | إرجاع قيمة العنصر من قاموس الفهرس. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | الحصول على كائن بمعرف محدد في المستند. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | الحصول على بيانات XMP الوصفية من المستند. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | التحقق مما إذا كان مستند PDF الحالي قد تم حفظه بتحديثات متزايدة. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | استيراد التعليقات من الدفق إلى المستند. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | استيراد التعليقات من ملف XFDF إلى المستند. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | التحقق مما إذا كان المستند يتطلب استدعاء طريقة Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | تحميل ملف وتحويله إلى PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | يدمج المستندات. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | يدمج ملفات pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | يدمج المستندات. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | يدمج المستندات. |
| [Optimize](../../aspose.pdf/document/optimize/)() | قم بترتيب المستند لتتمكن من - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال عبر رابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة بشكل تدريجي عند وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة (عرض أكثر البيانات فائدة أولاً)؛ - السماح بتفاعل المستخدم، مثل اتباع رابط، أن يتم حتى قبل استلام وعرض الصفحة بالكامل. استدعاء هذه الطريقة لا يحفظ المستند فعليًا. على العكس، يتم إعداد المستند فقط للحصول على بنية محسّنة، ثم استدعِ Save للحصول على المستند المحسّن. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | تحسين الموارد في المستند: 1. تُزال الموارد التي لا تُستخدم في صفحات المستند؛ 2. تُدمج الموارد المتساوية في كائن واحد؛ 3. تُحذف الكائنات غير المستخدمة. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | تحسين الموارد في المستند وفقًا لاستراتيجية التحسين المحددة. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة. فقط إذا كان المستند يحتوي على أكثر من nodesNumInSubtrees كائنات صفحة، وإلا لا يفعل شيئًا. لا تستدعِ هذه الطريقة أثناء التكرار على عناصر Pages، فقد تُعطي نتائج غير متوقعة. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | معالجة الفقرات للمولد. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | يزيل البيانات الوصفية من المستند. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | إزالة توافق pdfa من المستند |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | إزالة توافق pdfUa من المستند |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | إصلاح المستند المكسور. |
| [Save](../../aspose.pdf/document/save/#save)() | حفظ المستند بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | يحفظ المستند باستخدام خيارات الحفظ. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | يخزن المستند في تدفق. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | يحفظ المستند في الملف المحدد. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | يحفظ المستند باسم جديد مع تنسيق الملف. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | يحفظ المستند إلى تدفق مع خيارات الحفظ. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | يحفظ المستند باسم جديد مع تنسيق الملف. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | يحفظ المستند باسم جديد مع تعيين خيارات الحفظ الخاصة به. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | حفظ المستند بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | يحفظ المستند باستخدام خيارات الحفظ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | يخزن المستند في تدفق. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | يحفظ المستند في الملف المحدد. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | يحفظ المستند باسم جديد مع تنسيق الملف. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | يحفظ المستند إلى تدفق مع خيارات الحفظ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | يحفظ المستند باسم جديد مع تنسيق الملف. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | يحفظ المستند باسم جديد مع تعيين خيارات الحفظ الخاصة به. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | حفظ المستند إلى XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | يرسل صفحات معينة من المستند إلى جهاز المستند للمعالجة. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | تعيين العنوان لمستند Pdf |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | تعيين بيانات XMP الوصفية للمستند. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | تحقق من صحة المستند في الملف المحدد. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | تحقق من صحة المستند في الملف المحدد. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | تحقق من صحة المستند في الملف المحدد. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | يحوّل التدفق من الصيغة المصدر إلى تدفق بالصِيغة الوجهة. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | يحوّل التدفق من الصيغة المصدر إلى ملف الوجهة بالصِيغة الوجهة. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | يحوّل الملف المصدر من الصيغة المصدر إلى تدفق بالصِيغة الوجهة. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | يقوم بتحويل ملف المصدر بصيغته المصدر إلى ملف الوجهة بصيغته الوجهة. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | يضبط حد حجم الملف لتحميل ملف كامل إلى الذاكرة إلى القيمة الافتراضية التي تساوي 210 ميغابايت. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | يحدث عندما يستبدل الخط خطًا آخر في المستند. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | يمثل الطريقة التي ستتعامل مع حدث FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | يحتوي على وظائف لضبط الخطوط |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | يمثل الخيارات لطرق الدمج. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | تمثل خيارات إصلاح Document PDF. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


