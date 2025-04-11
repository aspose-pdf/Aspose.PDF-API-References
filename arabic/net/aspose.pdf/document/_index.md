---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Document. فئة تمثل وثيقة PDF
type: docs
weight: 3780
url: /ar/net/aspose.pdf/document/
---
## فئة الوثيقة

فئة تمثل وثيقة PDF.

```csharp
public sealed class Document : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Document](document/#constructor)() | يقوم بتهيئة وثيقة فارغة. |
| [Document](document/#constructor_1)(PdfVersion) | يقوم بتهيئة وثيقة فارغة حسب الإصدار. |
| [Document](document/#constructor_2)(Stream) | يقوم بتهيئة مثيل جديد من Document من *دفق* الإدخال. |
| [Document](document/#constructor_7)(string) | يقوم فقط بتهيئة Document باستخدام *اسم الملف*. نفس الشيء كما هو [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | يقوم بتهيئة مثيل جديد من Document من *دفق* الإدخال. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | يفتح وثيقة موجودة من دفق يوفر التحويل الضروري للحصول على وثيقة PDF. |
| [Document](document/#constructor_5)(Stream, string) | يقوم بتهيئة مثيل جديد من Document من *دفق* الإدخال. |
| [Document](document/#constructor_9)(string, bool) | يقوم فقط بتهيئة Document باستخدام *اسم الملف*. نفس الشيء كما هو [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | يفتح وثيقة موجودة من ملف يوفر خيارات التحويل الضرورية للحصول على وثيقة PDF. |
| [Document](document/#constructor_10)(string, string) | يقوم بتهيئة مثيل جديد من فئة `Document` للعمل مع وثيقة مشفرة. |
| [Document](document/#constructor_6)(Stream, string, bool) | يقوم بتهيئة مثيل جديد من Document من *دفق* الإدخال. |
| [Document](document/#constructor_11)(string, string, bool) | يقوم بتهيئة مثيل جديد من فئة `Document` للعمل مع وثيقة مشفرة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | يحصل على إجراءات الوثيقة. هذه الخاصية هي مثيل من فئة DocumentActions التي تسمح بالحصول على/تعيين إجراءات BeforClosing، BeforSaving، إلخ. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | يسمح بدمج محتويات الصفحات لتحسين حجم الوثيقة. إذا تم استخدامه، فقد تشير صفحات مختلفة ولكن مكررة إلى نفس كائن المحتوى. يرجى ملاحظة أن هذا الوضع قد يسبب آثار جانبية مثل تغيير محتوى الصفحة عند تغيير صفحة أخرى. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | يحصل على أو يحدد لون خلفية الوثيقة. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان سيتم توسيط موضع نافذة الوثيقة على الشاشة. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | يحصل على مجموعة الوثيقة. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | يحصل على إعدادات الأمان إذا كانت الوثيقة مشفرة. إذا لم تكن الوثيقة مشفرة، فسيتم رفع استثناء مطابق في .net 1.1 أو سيكون CryptoAlgorithm فارغًا للإصدارات الأخرى من .net. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | يحصل على مجموعة الوجهات. قديمة. يرجى استخدام NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | يحصل على أو يحدد ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | لا يمكن تنفيذ العديد من العمليات مع الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط. على سبيل المثال، لا يمكن تضمين بعض الخطوط في وثيقة PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. تُستخدم هذه العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في وثيقة PDF الحالية. كن حذرًا عند استخدام هذه العلامة. عندما يتم تعيينها، فهذا يعني أن الشخص الذي يحدد هذه العلامة يتحمل جميع المسؤوليات عن انتهاكات الترخيص/القانون المحتملة. لذا، يتحمل المخاطر بنفسه. يُوصى بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق الطبع والنشر. بشكل افتراضي، تكون القيمة خاطئة. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان يجب عرض شريط عنوان نافذة الوثيقة عنوان الوثيقة. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | يحصل على أو يحدد خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | يحصل على مجموعة من الملفات المضمنة في الوثيقة. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | خاصية تعلن أن الوثيقة يجب أن تتضمن جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded فيها إلى true. يمكن تضمين جميع خطوط PDF في الوثيقة ببساطة عن طريق تعيين علامة IsEmbedded إلى true، ولكن خطوط PDF القياسية Type1 هي استثناء من هذه القاعدة. يتطلب تضمين خطوط Type1 القياسية وقتًا طويلاً، لذا لتضمين هذه الخطوط، من الضروري ليس فقط تعيين علامة IsEmbedded إلى true للخط المحدد ولكن أيضًا تعيين علامة إضافية على مستوى الوثيقة - EmbedStandardFonts = true؛ يمكن تعيين هذه الخاصية مرة واحدة فقط لجميع الخطوط. بشكل افتراضي، تكون القيمة خاطئة. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | يحصل على أو يحدد علامة تمكّن الوثيقة من أن يتم تفريغها جزئيًا من الذاكرة. يسمح ذلك بتقليل استخدام الذاكرة ولكن قد يؤثر سلبًا على الأداء. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | يحصل على أو يحدد علامة لإدارة تطهير حقول التوقيع. مفعل بشكل افتراضي. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | اسم ملف PDF الذي تسبب في هذه الوثيقة |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان يجب تغيير حجم نافذة الوثيقة لتناسب الصفحة المعروضة الأولى. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | مثيل IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | يحصل على نموذج Acro للوثيقة. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | يثير استثناء إذا كانت الوثيقة ستُحفظ مع تغييرات وتحتوي على توقيع |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان يجب إخفاء شريط القائمة عند تنشيط الوثيقة. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان يجب إخفاء شريط الأدوات عند تنشيط الوثيقة. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان يجب إخفاء عناصر واجهة المستخدم عند تنشيط الوثيقة. |
| [Id](../../aspose.pdf/document/id/) { get; } | يحصل على المعرف. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | يحصل على أو يحدد علامة تجاهل الأخطاء في الملفات المصدر. عندما يتم نسخ الصفحات من الوثيقة المصدر إلى الوثيقة الوجهة، يتوقف عملية النسخ مع استثناء إذا كانت بعض الكائنات في الملفات المصدر تالفة عندما تكون هذه العلامة خاطئة. مثال: dest.Pages.Add(src.Pages); إذا تم تعيين هذه العلامة إلى true، فسيتم استبدال الكائنات التالفة بقيم فارغة. بشكل افتراضي: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | يحصل على معلومات الوثيقة. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | يحصل على حالة تشفير الوثيقة. صحيح إذا كانت الوثيقة مشفرة. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | يحصل على أو يحدد قيمة تشير إلى ما إذا كانت الوثيقة مُخططة. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | يحصل على ما إذا كانت الوثيقة متوافقة مع pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | يحصل على ما إذا كانت الوثيقة متوافقة مع pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | يحصل على أو يحدد ما إذا كانت الوثيقة متوافقة مع pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | مجموعة من JavaScript على مستوى الوثيقة. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | يحصل على الهيكل المنطقي للوثيقة. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | بيانات التعريف للوثيقة. (قد تتضمن وثيقة PDF معلومات عامة، مثل عنوان الوثيقة، المؤلف، وتواريخ الإنشاء والتعديل. تُسمى هذه المعلومات العالمية حول الوثيقة (على عكس محتواها أو هيكلها) بيانات التعريف وتهدف إلى المساعدة في الفهرسة والبحث عن الوثائق في قواعد البيانات الخارجية.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | مجموعة من الوجهات المسماة في الوثيقة. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | يحصل على أو يحدد وضع الصفحة، موضحًا كيفية عرض الوثيقة عند الخروج من وضع ملء الشاشة. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | يحصل على أو يحدد الإجراء الذي يتم تنفيذه عند فتح الوثيقة. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | يحصل على أو يحدد علامة تحسين. عندما تتم إضافة صفحات إلى الوثيقة، يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. يسمح ذلك بتقليل حجم الملف الناتج ولكن قد يتسبب في تنفيذ أبطأ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | يحصل على مخططات الوثيقة. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | يحصل على مجموعة من نوايا الإخراج في الوثيقة. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | يحصل على أو يحدد معلومات الصفحة. (للمولد فقط، لا يتم ملؤها عند قراءة الوثيقة) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | يحصل على تسميات الصفحات في الوثيقة. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | يحصل على أو يحدد تخطيط الصفحة الذي يجب استخدامه عند فتح الوثيقة. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | يحصل على أو يحدد وضع الصفحة، موضحًا كيفية عرض الوثيقة عند فتحها. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | يحصل على أو يحدد مجموعة صفحات الوثيقة. لاحظ أن الصفحات مرقمة من 1 في المجموعة. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | يحصل على تنسيق PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | يحصل على أذونات الوثيقة. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | يحصل على أو يحدد علامة توضح ما إذا كان يجب استخدام حجم صفحة PDF لاختيار درج الورق المدخل. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | يحصل على أو يحدد خيار تغيير حجم الصفحة الذي يجب اختياره عند عرض مربع حوار الطباعة لهذه الوثيقة. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | يحصل على الوصول إلى محتوى TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | يحصل على إصدار PDF من رأس ملف PDF. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | يحصل على ويحدد حد حجم الملف لتحميل ملف كامل في الذاكرة. يتم تعيين القيمة بالميغابايت. القيمة الافتراضية هي 210 ميغابايت. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | يحصل على حالة الترخيص للنظام. يرجع true إذا كان النظام يعمل في وضع مرخص وfalse خلاف ذلك. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | يدمج الوثائق. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | يدمج ملفات PDF. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | يدمج الوثائق. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | يدمج الوثائق. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | يربط XML بالوثيقة |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | يربط XML بالوثيقة |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | يربط XML/XSL بالوثيقة |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | يربط XML/XSL بالوثيقة |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | يربط XML/XSL بالوثيقة |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | يغير كلمات مرور الوثيقة. يمكن تنفيذ هذا الإجراء فقط باستخدام كلمة مرور المالك. |
| [Check](../../aspose.pdf/document/check/)(bool) | يتحقق من صحة الوثيقة. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | يحول الوثيقة باستخدام خيارات التحويل المحددة |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | يتعرف على الصور داخل الوثيقة ويضيف سلاسل hocr فوقها. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | يتعرف على الصور داخل الوثيقة ويضيف سلاسل hocr فوقها. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | يحول الوثيقة ويحفظ الأخطاء في الدفق المحدد. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | يحول الوثيقة ويحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | يحول الوثيقة عن طريق تطبيق الإصلاح. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | يحول الوثيقة عن طريق تطبيق الإصلاح. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | يحول الوثيقة ويحفظ الأخطاء في الملف المحدد. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | يحول الوثيقة ويحفظ الأخطاء في الملف المحدد. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | يحول الصفحة إلى PNG لدفق صورة DSR، OMR، OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | يفك تشفير الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المفككة من الوثيقة. |
| [Dispose](../../aspose.pdf/document/dispose/)() | يغلق جميع الموارد المستخدمة بواسطة هذه الوثيقة. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | يشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | يشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | يشفر الوثيقة. اتصل بعد ذلك بـ Save للحصول على النسخة المشفرة من الوثيقة. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | يصدر جميع تعليقات الوثيقة إلى الدفق. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | يصدر جميع تعليقات الوثيقة إلى ملف XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | يزيل جميع الحقول من الوثيقة ويضع قيمها بدلاً منها. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | يزيل جميع الحقول (والتعليقات) من الوثيقة ويضع قيمها بدلاً منها. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | يستبدل المحتوى الشفاف برسومات نقطية وبيانية غير شفافة. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Clears memory |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Returns item value from catalog dictionary. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | يحصل على كائن بالمعرف المحدد في الوثيقة. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | يحصل على بيانات التعريف XMP من الوثيقة. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | يتحقق مما إذا كانت وثيقة PDF الحالية قد تم حفظها مع تحديثات تدريجية. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | يستورد التعليقات من الدفق إلى الوثيقة. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | يستورد التعليقات من ملف XFDF إلى الوثيقة. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | يتحقق مما إذا كانت الوثيقة تتطلب استدعاء طريقة الإصلاح. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | يحمل ملفًا، محولًا إياه إلى PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | يدمج الوثائق. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | يدمج ملفات PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | يدمج الوثائق. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | يدمج الوثائق. |
| [Optimize](../../aspose.pdf/document/optimize/)() | يقوم بتخطيط الوثيقة من أجل - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال إلى الرابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة بشكل تدريجي عند وصول البيانات لصفحة ما عبر قناة بطيئة (عرض البيانات الأكثر فائدة أولاً)؛ - السماح بالتفاعل مع المستخدم، مثل اتباع رابط، ليتم تنفيذه حتى قبل أن يتم استلام الصفحة بالكامل وعرضها. استدعاء هذه الطريقة لا يحفظ الوثيقة فعليًا. على العكس، يتم إعداد الوثيقة فقط للحصول على هيكل محسن، اتصل بعد ذلك بـ Save للحصول على وثيقة محسنة. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | تحسين الموارد في الوثيقة: 1. يتم إزالة الموارد التي لا تستخدم في صفحات الوثيقة؛ 2. يتم دمج الموارد المتساوية في كائن واحد؛ 3. يتم حذف الكائنات غير المستخدمة. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | تحسين الموارد في الوثيقة وفقًا لاستراتيجية التحسين المحددة. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | ينظم عقد شجرة الصفحة في الوثيقة في شجرة متوازنة. فقط إذا كانت الوثيقة تحتوي على أكثر من nodesNumInSubtrees كائنات صفحة، وإلا فلا تفعل شيئًا. لا تستدعي هذه الطريقة أثناء التكرار على عناصر Pages، فقد تعطي نتائج غير متوقعة |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | معالجة الفقرات للمولد. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | يزيل بيانات التعريف من الوثيقة. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | يزيل التوافق مع pdfa من الوثيقة |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | يزيل التوافق مع pdfUa من الوثيقة |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | يقوم بإصلاح الوثيقة التالفة. |
| [Save](../../aspose.pdf/document/save/#save)() | يحفظ الوثيقة بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | يحفظ الوثيقة مع خيارات الحفظ. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | يخزن الوثيقة في الدفق. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | يحفظ الوثيقة في الملف المحدد. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | يحفظ الوثيقة باسم جديد مع تنسيق ملف. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | يحفظ الوثيقة إلى دفق مع خيارات الحفظ. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | يحفظ الوثيقة باسم جديد مع تنسيق ملف. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | يحفظ الوثيقة باسم جديد مع تعيين خيارات الحفظ الخاصة بها. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | يحفظ الوثيقة بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | يحفظ الوثيقة مع خيارات الحفظ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | يخزن الوثيقة في الدفق. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | يحفظ الوثيقة في الملف المحدد. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | يحفظ الوثيقة باسم جديد مع تنسيق ملف. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | يحفظ الوثيقة إلى دفق مع خيارات الحفظ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | يحفظ الوثيقة باسم جديد مع تنسيق ملف. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | يحفظ الوثيقة باسم جديد مع تعيين خيارات الحفظ الخاصة بها. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | يحفظ الوثيقة إلى XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | يرسل الوثيقة بالكامل إلى جهاز الوثيقة للمعالجة. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | يرسل الوثيقة بالكامل إلى جهاز الوثيقة للمعالجة. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | يرسل صفحات معينة من الوثيقة إلى جهاز الوثيقة للمعالجة. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | يرسل الوثيقة بالكامل إلى جهاز الوثيقة للمعالجة. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | تعيين العنوان لوثيقة PDF |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | تعيين بيانات التعريف XMP للوثيقة. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | تحقق من الوثيقة في الملف المحدد. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | تحقق من الوثيقة في الملف المحدد. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | تحقق من الوثيقة في الملف المحدد. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | يحول الدفق في التنسيق المصدر إلى دفق في التنسيق الوجهة. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | يحول الدفق في التنسيق المصدر إلى ملف الوجهة في التنسيق الوجهة. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | يحول الملف المصدر في التنسيق المصدر إلى دفق في التنسيق الوجهة. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | يحول الملف المصدر في التنسيق المصدر إلى ملف الوجهة في التنسيق الوجهة. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | يحدد حد حجم الملف لتحميل ملف كامل في الذاكرة إلى القيمة الافتراضية التي تساوي 210 ميغابايت. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | يحدث عندما يتم استبدال خط بخط آخر في الوثيقة. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | يمثل الطريقة التي ستتعامل مع حدث استبدال الخط. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | يحمل الوظائف لضبط الخطوط |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | يمثل الخيارات لطرق الدمج. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | يمثل الخيارات لإصلاح وثيقة PDF. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)