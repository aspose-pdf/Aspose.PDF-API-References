---
title: Document
second_title: Aspose.PDF لمرجع .NET API
description: فئة تمثل مستند PDF
type: docs
weight: 1870
url: /ar/net/aspose.pdf/document/
---
## Document class

فئة تمثل مستند PDF

```csharp
public sealed class Document : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Document](document#constructor)() | تهيئة مستند فارغ . |
| [Document](document#constructor_1)(Stream) | تهيئة مثيل المستند الجديد من ملف*input* تيار . |
| [Document](document#constructor_6)(string) | فقط الحرف الأول باستخدام المستند*filename* . كمثل[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | تهيئة مثيل المستند الجديد من ملف*input* تيار . |
| [Document](document#constructor_2)(Stream, LoadOptions) | يفتح مستندًا موجودًا من دفق يوفر التحويل اللازم للحصول على مستند pdf. |
| [Document](document#constructor_4)(Stream, string) | تهيئة مثيل المستند الجديد من ملف*input* تيار . |
| [Document](document#constructor_7)(string, LoadOptions) | يفتح مستندًا موجودًا من ملف يوفر خيارات التحويل الضرورية للحصول على مستند pdf. |
| [Document](document#constructor_8)(string, string) | تهيئة مثيل جديد لملف[`Document`](../document) فئة للعمل مع المستند المشفر. |
| [Document](document#constructor_5)(Stream, string, bool) | تهيئة مثيل المستند الجديد من ملف*input* تيار . |
| [Document](document#constructor_9)(string, string, bool) | تهيئة مثيل جديد لملف[`Document`](../document) فئة للعمل مع المستند المشفر. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | يحصل على إجراءات المستند. هذه الخاصية هي مثيل لفئة DocumentActions التي تسمح بالحصول على / تعيين إجراءات BeforClosing و BeforSaving وما إلى ذلك. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | يسمح بدمج محتويات الصفحة لتحسين حجم المستند. إذا تم استخدامها ثم تختلف ولكن الصفحات المكررة قد تشير إلى نفس كائن المحتوى. يرجى ملاحظة أن هذا الوضع قد يتسبب في آثار جانبية مثل تغيير محتوى الصفحة عند تغيير صفحة أخرى. |
| [Background](../../aspose.pdf/document/background) { get; set; } | الحصول على أو تحديد لون خلفية المستند. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | الحصول على أو تعيين علامة تحدد ما إذا كان موضع نافذة المستند سيكون في المنتصف على الشاشة. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | الحصول على مجموعة من المستندات. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | يحصل على إعدادات التأمين إذا تم تشفير الوثيقة. إذا لم يتم تشفير المستند ، فسيتم رفع الاستثناء المقابل في .net 1.1 أو ستكون خوارزمية CryptoAlgorithm فارغة لإصدارات .net الأخرى. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | يحصل على مجموعة الوجهات . مهمل. الرجاء استخدام NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | الحصول على أو تعيين ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار) . |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | لا يمكن تنفيذ العديد من العمليات باستخدام الخط إذا تم حظر هذه العمليات بموجب ترخيص لهذا الخط. على سبيل المثال ، لا يمكن تضمين بعض الخطوط في مستند PDF إذا عطلت قواعد الترخيص التضمين لهذا الخط. يتم استخدام هذه العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في مستند PDF الحالي. توخ الحذر عند استخدام هذه العلامة. عندما يتم تعيينه ، فهذا يعني أن الشخص الذي يضع هذا العلم ، يتحمل كل مسؤولية انتهاكات الترخيص / القانون المحتملة على نفسه. لذا فهو يأخذ الأمر على مسؤوليته الخاصة. يوصى بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر. خطأ افتراضيًا. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | الحصول على علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند أم لا. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | الحصول على أو تعيين خيار معالجة وضع الطباعة على الوجهين لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | الحصول على مجموعة من الملفات المضمنة في المستند. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | الخاصية التي تعلن أن المستند يجب أن يضمّن جميع خطوط Type1 القياسية التي تحتوي على علامة IsEmbedded مضبوطة على true. يمكن دمج جميع خطوط PDF في المستند ببساطة عن طريق إعداد العلامة IsEmbedded in true ، ولكن خطوط PDF القياسية Type1 هي استثناء من هذه القاعدة. مضمنة في true للخط المحدد ولكن أيضًا قم بتعيين علامة إضافية على مستوى المستند - EmbedStandardFonts = true يمكن تعيين هذه الخاصية مرة واحدة فقط لجميع الخطوط . افتراضيًا false . |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | الحصول على أو تعيين علامة تتيح إلغاء تحميل المستند جزئيًا من الذاكرة. هذا يسمح بتقليل استخدام الذاكرة ولكن قد يكون له تأثير سلبي على الأداء. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | الحصول على علامة أو تعيينها لإدارة تعقيم حقول التوقيع. ممكّن افتراضيًا. |
| [FileName](../../aspose.pdf/document/filename) { get; } | اسم ملف PDF الذي تسبب في هذا المستند |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | الحصول على أو تعيين علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتلائم الصفحة الأولى المعروضة. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | مثيل IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form) { get; } | يحصل على نموذج Acro للوثيقة. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | استثناء رمي إذا كان المستند سيُحفظ بالتغييرات وله توقيع |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | الحصول على أو تعيين علامة تحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | الحصول على أو تعيين علامة تحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | الحصول على أو تعيين علامة تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
| [Id](../../aspose.pdf/document/id) { get; } | يحصل على المعرف . |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | الحصول على علامة تجاهل الأخطاء في الملفات المصدر أو تعيينها. عند نسخ صفحات من المستند المصدر إلى المستند الوجهة ، يتم إيقاف عملية النسخ باستثناء في حالة تلف بعض الكائنات في الملفات المصدر عندما تكون هذه العلامة خاطئة. مثال: dest.Pages.Add (src.Pages) إذا تم تعيين هذه العلامة على "true" ، فسيتم استبدال الكائنات التالفة بقيم فارغة. افتراضيًا: true . |
| [Info](../../aspose.pdf/document/info) { get; } | الحصول على معلومات المستند . |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | يحصل على حالة مشفرة للمستند. صحيح إذا تم تشفير المستند. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان المستند خطيًا. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | يحصل على المستند المتوافق مع pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | يحصل على وثيقة متوافقة مع pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | الحصول على المستند المتوافق مع pdfa أو تعيينه. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | مجموعة JavaScript لمستوى المستند. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | يحصل على البنية المنطقية للوثيقة. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | بيانات تعريف المستند. (قد يتضمن مستند PDF معلومات عامة ، مثل عنوان المستند ومؤلفه وتواريخ الإنشاء والتعديل. تسمى هذه المعلومات العامة حول المستند (على عكس محتواها أو هيكلها) metadata وهي تهدف إلى المساعدة في فهرسة المستندات والبحث عنها في قواعد البيانات الخارجية.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | مجموعة الوجهة المحددة في المستند. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | الحصول على وضع الصفحة أو تعيينه ، وتحديد كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | الحصول على أو تعيين الإجراء الذي يتم تنفيذه عند فتح المستند. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | الحصول على علامة التحسين أو تعيينها. عند إضافة الصفحات إلى المستند ، يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. هذا يسمح بتقليل حجم الملف الناتج ولكن قد يتسبب في إبطاء التنفيذ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false . |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | يحصل على مخططات الوثيقة . |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | الحصول على معلومات الصفحة أو تعيينها. (للمولد فقط) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | الحصول على تسميات الصفحة في المستند. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | الحصول على تخطيط الصفحة الذي سيتم استخدامه عند فتح المستند أو تعيينه. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | الحصول على وضع الصفحة أو تعيينه ، مع تحديد كيفية عرض المستند عند فتحه. |
| [Pages](../../aspose.pdf/document/pages) { get; } | الحصول على مجموعة من صفحات المستند أو تعيينها. لاحظ أن الصفحات مرقمة من 1 في المجموعة. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | يحصل على تنسيق PDF |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | يحصل على أذونات المستند . |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | يحصل على حق الوصول إلى محتوى TaggedPdf. |
| [Version](../../aspose.pdf/document/version) { get; } | الحصول على نسخة من Pdf من رأس ملف Pdf. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | الحصول على الحالة المرخصة للنظام. إرجاع صحيح هو أن النظام يعمل في الوضع المرخص وخطأ في الحالات الأخرى. |

## طُرق

| اسم | وصف |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | ربط xml بـ document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | ربط xml بـ document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | ربط xml / xsl بالمستند |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | ربط xml / xsl بالمستند |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | ربط xml / xsl بالمستند |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | يغير كلمات مرور المستند. يمكن القيام بهذا الإجراء فقط باستخدام كلمة مرور المالك. |
| [Check](../../aspose.pdf/document/check)(bool) | التحقق من صحة الوثيقة . |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | قم بتحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | تحويل المستند باستخدام خيارات التحويل المحددة |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | قم بتحويل المستند وحفظ الأخطاء في الدفق المحدد. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | قم بتحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | تحويل المستند عن طريق تطبيق Fixup . |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | تحويل المستند عن طريق تطبيق Fixup . |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | قم بتحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | قم بتحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | قم بتحويل الصفحة إلى PNG لدفق صور DSR و OMR و OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | يفك تشفير المستند. اتصل ثم حفظ للحصول على نسخة مشفرة من المستند. |
| [Dispose](../../aspose.pdf/document/dispose)() | يتم إغلاق كافة الموارد المستخدمة بواسطة هذا المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | لتشفير المستند. اتصل ثم حفظ للحصول على نسخة مشفرة من المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | لتشفير المستند. اتصل ثم حفظ للحصول على نسخة مشفرة من المستند. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | لتشفير المستند. اتصل ثم حفظ للحصول على نسخة مشفرة من المستند. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | قم بتصدير كافة التعليقات التوضيحية للمستند إلى تدفق . |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | تصدير كافة التعليقات التوضيحية للمستند إلى ملف XFDF file |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | يزيل كل الحقول من المستند ويضع قيمها بدلاً من ذلك. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | يزيل كل الحقول من المستند ويضع قيمها بدلاً من ذلك. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | مسح الذاكرة |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | إرجاع قيمة العنصر من قاموس الكتالوج. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | الحصول على كائن بمعرف محدد في المستند. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | احصل على بيانات تعريف XMP من المستند . |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | يتم استيراد التعليقات التوضيحية من التدفق إلى المستند . |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | يتم استيراد التعليقات التوضيحية من ملف XFDF إلى المستند. |
| [Optimize](../../aspose.pdf/document/optimize)() | جعل المستند خطيًا من أجل - افتح الصفحة الأولى في أسرع وقت ممكن - اعرض الصفحة التالية أو اتبع الرابط للصفحة التالية بأسرع ما يمكن - اعرض الصفحة بشكل متزايد فور وصولها عند تسليم بيانات الصفحة عبر قناة بطيئة (اعرض البيانات الأكثر فائدة أولاً) - السماح بتفاعل المستخدم ، مثل اتباع ارتباط ، ليتم تنفيذه حتى قبل استلام الصفحة بالكامل وعرضها. لا يؤدي استدعاء هذه الطريقة إلى حفظ المستند فعليًا . على العكس من ذلك ، يتم إعداد المستند فقط للحصول على بنية محسّنة ، استدعاء ثم حفظ للحصول على مستند محسن . |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | تحسين الموارد في المستند: 1. تتم إزالة الموارد غير المستخدمة في صفحات المستند 2. يتم ربط الموارد المتساوية في كائن واحد 3. يتم حذف الكائنات غير المستخدمة. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | تحسين الموارد في المستند وفقًا لإستراتيجية التحسين المحددة. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | معالجة الفقرات للمولد. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | يزيل البيانات الأولية من المستند. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | إزالة الامتثال pdfa من المستند |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | إزالة التوافق مع pdfUa من المستند |
| [Repair](../../aspose.pdf/document/repair)() | إصلاح المستند التالف. |
| [Save](../../aspose.pdf/document/save#save)() | احفظ المستند بشكل متزايد (أي باستخدام تقنية التحديث المتزايد) . |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | يحفظ المستند مع خيارات الحفظ . |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | يخزن المستند في التدفق . |
| [Save](../../aspose.pdf/document/save#save_5)(string) | يحفظ المستند في الملف المحدد. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | يحفظ المستند باسم جديد مع تنسيق ملف. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | يحفظ المستند في دفق مع خيارات الحفظ . |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | يحفظ المستند باسم جديد مع تنسيق ملف. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | يحفظ المستند باسم جديد ويضبط خيارات الحفظ الخاصة به. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | يحفظ المستند في تدفق استجابة مع خيارات الحفظ. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | احفظ المستند بتنسيق XML . |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | يرسل المستند بأكمله إلى جهاز المستند للمعالجة . |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | يرسل المستند بأكمله إلى جهاز المستند للمعالجة . |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | يرسل صفحات معينة من المستند إلى جهاز المستند للمعالجة . |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | يرسل المستند بأكمله إلى جهاز المستند للمعالجة . |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | تعيين عنوان لـ Pdf Document |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | تعيين البيانات الوصفية للمستند XMP . |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | تحقق من صحة الوثيقة في الملف المحدد. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | تحقق من صحة الوثيقة في الملف المحدد. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | تحقق من صحة الوثيقة في الملف المحدد. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | يحول الدفق بتنسيق المصدر إلى دفق بتنسيق الوجهة. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | يحول الدفق بتنسيق المصدر إلى ملف الوجهة بتنسيق الوجهة. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | يحول الملف المصدر بتنسيق المصدر إلى دفق بتنسيق الوجهة. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | يحول الملف المصدر بتنسيق المصدر إلى ملف الوجهة بتنسيق الوجهة. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | إجراء معاودة الاتصال للتعرف على hocr . |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | يمثل الطريقة التي ستتعامل مع حدث FontSubstitution. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | يحتوي على وظائف لضبط الخطوط |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
