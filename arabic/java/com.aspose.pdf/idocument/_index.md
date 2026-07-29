---
title: "IDocument"
linktitle: "IDocument"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "واجهة تمثل مستند PDF"
type: docs
weight: 2230
url: /ar/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

واجهة تمثل مستند PDF

## الطرق

| طريقة | الوصف |
| --- | --- |
| [afterImport](#afterImport--) | تعداد جميع التعليقات التوضيحية المسجلة واستدعاء AfterImport لكل منها. |
| [bindXml](#bindXml-java.io.InputStream-) | ربط xml بالمستند |
| [bindXml](#bindXml-java.lang.String-) | ربط xml بالمستند |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | ربط xml/xsl بالمستند |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | يغيّر كلمات مرور المستند. |
| [check](#check-boolean-) | يتحقق من صحة المستند. |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | تحويل المستند إلى مستند قابل للبحث. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. <p> هذا يسمح بإظهار/إخفاء النص القابل للبحث على الصفحة. القيمة الافتراضية هي FALSE. هذا يسمح بالحصول على الصورة الأصلية من pdf. القيمة الافتراضية هي FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. <p> هذا يسمح بإظهار/إخفاء النص القابل للبحث على الصفحة. القيمة الافتراضية هي FALSE. هذا يسمح بالحصول على الصورة الأصلية من pdf. القيمة الافتراضية هي FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | تحويل المستند باستخدام خيارات التحويل المحددة. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | طريقة داخلية |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها. |
| [decrypt](#decrypt--) | يفك تشفير المستند. |
| [dispose](#dispose--) | مهمل. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | يشفر المستند. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | يصدّر جميع تعليقات المستند إلى ملف XFDF |
| [flatten](#flatten--) | يزيل جميع الحقول (والتعليقات) من المستند ويضع قيمها بدلاً من ذلك. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | يزيل جميع الحقول من المستند ويضع قيمها بدلاً من ذلك. |
| [flattenTransparency](#flattenTransparency--) | يستبدل المحتوى الشفاف برسومات نقطية ومتجهة غير شفافة. |
| [freeMemory](#freeMemory--) | يمسح الذاكرة |
| [getActions](#getActions--) | يحصل على إجراءات المستند. |
| [getBackground](#getBackground--) | يحصل على لون خلفية المستند. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | يعيد قيمة العنصر من قاموس الفهرس. |
| [getCollection](#getCollection--) | يحصل على مجموعة المستند. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | يحصل على إعدادات الأمان إذا كان المستند مشفّراً. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | يحصل على معالج أمان مخصص. |
| [getDefaultCopier](#getDefaultCopier--) | يعيد النسّاخ المستخدم لنسخ الصفحات إلى هذا المستند. |
| [getDestinations](#getDestinations--) | يحصل على مجموعة الوجهات. |
| [getDirection](#getDirection--) | يحصل على ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
| [getDuplex](#getDuplex--) | يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | يحصل على مجموعة الملفات المدمجة في المستند. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع. |
| [getEngineDoc](#getEngineDoc--) | مثيل من IPdfDocument يُستخدم للوصول إلى بنية المستند الداخلية. |
| [getFileName](#getFileName--) | اسم ملف PDF الذي تسبب في هذا المستند |
| [getForm](#getForm--) | يحصل على نموذج Acro Form للمستند. |
| [getId](#getId--) | يحصل على المعرف. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر. |
| [getInfo](#getInfo--) | يحصل على معلومات المستند. |
| [getLogicalStructure](#getLogicalStructure--) | يحصل على البنية المنطقية للمستند. |
| [getMetadata](#getMetadata--) | بيانات تعريف المستند. |
| [getMetadataStream](#getMetadataStream--) | يرجع تدفق البيانات الوصفية الخام |
| [getNamedDestinations](#getNamedDestinations--) | مجموعة من الوجهات المسماة في المستند. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
| [getObjectById](#getObjectById-java.lang.String-) | يحصل على كائن بالمعرف المحدد في المستند. |
| [getOpenAction](#getOpenAction--) | يحصل على الإجراء الذي يتم عند فتح المستند. |
| [getOptimizeSize](#getOptimizeSize--) | يحصل على علامة التحسين. |
| [getOutlines](#getOutlines--) | يحصل على مخططات المستند. |
| [getPageInfo](#getPageInfo--) | يحصل على معلومات الصفحة. (للمولد فقط، لا يتم ملؤها عند قراءة المستند) |
| [getPageLabels](#getPageLabels--) | يحصل على تسميات الصفحات في المستند. |
| [getPageLayout](#getPageLayout--) | يحصل على تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
| [getPageMode](#getPageMode--) | يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند فتحه. |
| [getPages](#getPages--) | يحصل على مجموعة صفحات المستند. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | يحصل على أذونات المستند. |
| [getPrintScaling](#getPrintScaling--) | يحصل على خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [getTaggedContent](#getTaggedContent--) | يحصل على الوصول إلى محتوى TaggedPdf. |
| [getVersion](#getVersion--) | يحصل على نسخة من PDF من رأس ملف PDF. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | احصل على بيانات XMP الوصفية من المستند. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | يستورد التعليقات التوضيحية من ملف XFDF إلى المستند. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | إشعار حول الخطوط المفقودة عند معالجة المستندات |
| [isCenterWindow](#isCenterWindow--) | يحصل على علامة تحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | يحصل على علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
| [isEncrypted](#isEncrypted--) | يحصل على حالة التشفير للمستند. |
| [isFitWindow](#isFitWindow--) | يحصل على علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة الأولى المعروضة. |
| [isHideMenubar](#isHideMenubar--) | يحصل على العلامة التي تحدد ما إذا كان شريط القوائم يجب إخفاؤه عندما يكون المستند نشطًا. |
| [isHideToolBar](#isHideToolBar--) | يحصل على العلامة التي تحدد ما إذا كان شريط الأدوات يجب إخفاؤه عندما يكون المستند نشطًا. |
| [isHideWindowUI](#isHideWindowUI--) | يحصل أو يضبط العلامة التي تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
| [isLinearized](#isLinearized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة. يمكننا إجراء بعض العمليات ومواصلة العمل مع المستند بعد طريقة الحفظ إذا تم تمكين معلمة ManualDispose هذه. |
| [isPdfaCompliant](#isPdfaCompliant--) | يحصل على ما إذا كان المستند متوافقًا مع PDF/A. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | يحصل على ما إذا كان المستند متوافقًا مع PDF/UA. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | يحصل على العلامة التي تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A. |
| [optimize](#optimize--) | خطّ المستند بهدف - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال عبر رابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة تدريجيًا مع وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة (عرض أكثر البيانات فائدة أولاً)؛ - السماح بالتفاعل مع المستخدم، مثل اتباع رابط، أن يتم حتى قبل استلام الصفحة بالكامل وعرضها. |
| [optimizeResources](#optimizeResources--) | تحسين الموارد في المستند: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | تحسين الموارد في المستند وفقًا لاستراتيجية التحسين المحددة. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة. |
| [processParagraphs](#processParagraphs--) | يخزن المستند في تدفق. |
| [removeMetadata](#removeMetadata--) | يزيل البيانات الوصفية من المستند. |
| [removePdfaCompliance](#removePdfaCompliance--) | إزالة توافق PDF/A من المستند |
| [removePdfUaCompliance](#removePdfUaCompliance--) | إزالة توافق PDF/UA من المستند |
| [repair](#repair--) | يصلح المستند التالف. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | احفظ المستند بشكل تدريجي (مثلاً |
| [save](#save-java.io.OutputStream-) | يخزن المستند في تدفق. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | احفظ المستند |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به. |
| [save](#save-java.lang.String-) | يحفظ المستند في الملف المحدد. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد. |
| [saveXml](#saveXml-java.lang.String-) | احفظ المستند إلى XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | يرسل الصفحات المحددة من المستند إلى جهاز المستند للمعالجة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | تعيين علامة لتحديد الخط الذي يحدده البرنامج في حالة عدم وجود الخط. |
| [setBackground](#setBackground-java.awt.Color-) | يضبط لون خلفية المستند. |
| [setCenterWindow](#setCenterWindow-boolean-) | يضبط علامة تحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | يضبط مجموعة المستند. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | يحصل على معامل التحويل لمحول pdf/ua (تحويل البيانات الوصفية وفهرس المستند فقط إذا تم ضبطه على true). |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | يضبط علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
| [setDuplex](#setDuplex-int-) | يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع. |
| [setFitWindow](#setFitWindow-boolean-) | يضبط علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً. |
| [setHideMenubar](#setHideMenubar-boolean-) | يضبط علامة تحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. |
| [setHideToolBar](#setHideToolBar-boolean-) | يضبط علامة تحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | يضبط علامة تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة. يمكننا إجراء بعض العمليات ومتابعة العمل مع المستند بعد استدعاء طريقة الحفظ إذا تم تمكين معامل ManualDispose هذا. ولكن يُنصح بشدة باستدعاء طريقة التخلص (dispose) عندما لا يعود هناك حاجة إلى كائن Document. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | يضبط الإجراء الذي يتم عند فتح المستند. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | يضبط علامة التحسين. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | يضبط معلومات الصفحة. (للمولد فقط، لا تُملأ عند قراءة المستند) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند فتحه. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | يضبط علامة تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة. |
| [setPrintScaling](#setPrintScaling-int-) | يضبط خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [setTitle](#setTitle-java.lang.String-) | تعيين عنوان لمستند PDF |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | تعيين بيانات XMP الوصفية للمستند. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | تحقق من صحة المستند في الملف المحدد. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | تحقق من صحة المستند في الملف المحدد. |

### afterImport {#afterImport--}
```
void afterImport()
```

تعداد جميع التعليقات التوضيحية المسجلة واستدعاء AfterImport لكل منها.

### bindXml {#bindXml-java.io.InputStream-}
ربط xml بالمستند

### bindXml {#bindXml-java.lang.String-}
ربط xml بالمستند

### bindXml {#bindXml-java.lang.String-java.lang.String-}
ربط xml/xsl بالمستند

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
يغيّر كلمات مرور المستند.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

يتحقق من صحة المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| doRepair |  | إذا كان صحيحًا، سيتم إصلاح المشكلات المكتشفة. |

**Returns:**
قيمة منطقية

### close {#close--}
```
void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
تحويل المستند إلى مستند قابل للبحث.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد. <p> هذا يسمح بإظهار/إخفاء النص القابل للبحث على الصفحة. القيمة الافتراضية هي FALSE. هذا يسمح بالحصول على الصورة الأصلية من pdf. القيمة الافتراضية هي FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد. <p> هذا يسمح بإظهار/إخفاء النص القابل للبحث على الصفحة. القيمة الافتراضية هي FALSE. هذا يسمح بالحصول على الصورة الأصلية من pdf. القيمة الافتراضية هي FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
تحويل المستند باستخدام خيارات التحويل المحددة.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
طريقة داخلية

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها.

### decrypt {#decrypt--}
```
void decrypt()
```

يفك تشفير المستند.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

مهمل.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
يشفر المستند.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
يصدّر جميع تعليقات المستند إلى ملف XFDF

### flatten {#flatten--}
```
void flatten()
```

يزيل جميع الحقول (والتعليقات) من المستند ويضع قيمها بدلاً من ذلك.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
يزيل جميع الحقول من المستند ويضع قيمها بدلاً من ذلك.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

يستبدل المحتوى الشفاف برسومات نقطية ومتجهة غير شفافة.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

يمسح الذاكرة

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

يحصل على إجراءات المستند.

**Returns:**
كائن DocumentActionCollection

### getBackground {#getBackground--}
```
Color getBackground()
```

يحصل على لون خلفية المستند.

**Returns:**
كائن java.awt.Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
يعيد قيمة العنصر من قاموس الفهرس.

### getCollection {#getCollection--}
```
Collection getCollection()
```

يحصل على مجموعة المستند.

**Returns:**
كائن Collection

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

يحصل على إعدادات الأمان إذا كان المستند مشفّراً.

**Returns:**
عنصر CryptoAlgorithm أو null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

يحصل على معالج أمان مخصص.

**Returns:**
مثيل ICustomSecurityHandler

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

يعيد النسّاخ المستخدم لنسخ الصفحات إلى هذا المستند.

**Returns:**
كائن Copier

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

يحصل على مجموعة الوجهات.

**Returns:**
كائن DestinationCollection

### getDirection {#getDirection--}
```
Direction getDirection()
```

يحصل على ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار).

**Returns:**
عنصر Direction

### getDuplex {#getDuplex--}
```
int getDuplex()
```

يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Returns:**
عنصر PrintDuplex

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

يحصل على مجموعة الملفات المدمجة في المستند.

**Returns:**
كائن EmbeddedFileCollection

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true.

**Returns:**
قيمة منطقية

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع.

**Returns:**
قيمة منطقية

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

مثيل من IPdfDocument يُستخدم للوصول إلى بنية المستند الداخلية.

**Returns:**
كائن IPdfDocument

### getFileName {#getFileName--}
```
String getFileName()
```

اسم ملف PDF الذي تسبب في هذا المستند

**Returns:**
كائن String

### getForm {#getForm--}
```
Form getForm()
```

يحصل على نموذج Acro Form للمستند.

**Returns:**
كائن Form

### getId {#getId--}
```
Id getId()
```

يحصل على المعرف.

**Returns:**
كائن Id

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر.

**Returns:**
قيمة منطقية

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

يحصل على معلومات المستند.

**Returns:**
كائن DocumentInfo

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

يحصل على البنية المنطقية للمستند.

**Returns:**
كائن RootElement

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

بيانات تعريف المستند.

**Returns:**
كائن Metadata

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

يرجع تدفق البيانات الوصفية الخام

**Returns:**
كائن IPdfStreamAccessor

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

مجموعة من الوجهات المسماة في المستند.

**Returns:**
مثيل NamedDestinationCollection

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة.

**Returns:**
عنصر PageMode

### getObjectById {#getObjectById-java.lang.String-}
يحصل على كائن بالمعرف المحدد في المستند.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

يحصل على الإجراء الذي يتم عند فتح المستند.

**Returns:**
كائن IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

يحصل على علامة التحسين.

**Returns:**
قيمة منطقية

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

يحصل على مخططات المستند.

**Returns:**
كائن OutlineCollection

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

يحصل على معلومات الصفحة. (للمولد فقط، لا يتم ملؤها عند قراءة المستند)

**Returns:**
معلومات الصفحة.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

يحصل على تسميات الصفحات في المستند.

**Returns:**
كائن PageLabelCollection

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

يحصل على تخطيط الصفحة الذي سيُستخدم عند فتح المستند.

**Returns:**
عنصر PageLayout

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند فتحه.

**Returns:**
عنصر PageMode

### getPages {#getPages--}
```
PageCollection getPages()
```

يحصل على مجموعة صفحات المستند.

**Returns:**
قيمة منطقية

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
عنصر PdfFormat

### getPermissions {#getPermissions--}
```
int getPermissions()
```

يحصل على أذونات المستند.

**Returns:**
قيمة int

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

يحصل على خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Returns:**
عنصر PrintScaling

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

يحصل على الوصول إلى محتوى TaggedPdf.

**Returns:**
مثيل ITaggedContent

### getVersion {#getVersion--}
```
String getVersion()
```

يحصل على نسخة من PDF من رأس ملف PDF.

**Returns:**
كائن String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
احصل على بيانات XMP الوصفية من المستند.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
يستورد التعليقات التوضيحية من ملف XFDF إلى المستند.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

إشعار حول الخطوط المفقودة عند معالجة المستندات

**Returns:**
قيمة منطقية

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

يحصل على علامة تحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة.

**Returns:**
قيمة منطقية

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط.

**Returns:**
قيمة منطقية افتراضيًا false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

يحصل على علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند.

**Returns:**
قيمة منطقية

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

يحصل على حالة التشفير للمستند.

**Returns:**
قيمة منطقية

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

يحصل على علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة الأولى المعروضة.

**Returns:**
قيمة منطقية

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

يحصل على العلامة التي تحدد ما إذا كان شريط القوائم يجب إخفاؤه عندما يكون المستند نشطًا.

**Returns:**
قيمة منطقية

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

يحصل على العلامة التي تحدد ما إذا كان شريط الأدوات يجب إخفاؤه عندما يكون المستند نشطًا.

**Returns:**
قيمة منطقية

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

يحصل أو يضبط العلامة التي تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا.

**Returns:**
قيمة منطقية

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا.

**Returns:**
قيمة منطقية

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة. يمكننا إجراء بعض العمليات ومواصلة العمل مع المستند بعد طريقة الحفظ إذا تم تمكين معلمة ManualDispose هذه.

**Returns:**
قيمة منطقية. (القيمة الافتراضية == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

يحصل على ما إذا كان المستند متوافقًا مع PDF/A.

**Returns:**
قيمة منطقية

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

يحصل على ما إذا كان المستند متوافقًا مع PDF/UA.

**Returns:**
قيمة منطقية

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

يحصل على العلامة التي تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة.

**Returns:**
قيمة منطقية

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A.

**Returns:**
قيمة منطقية

### optimize {#optimize--}
```
void optimize()
```

خطّ المستند بهدف - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال عبر رابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة تدريجيًا مع وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة (عرض أكثر البيانات فائدة أولاً)؛ - السماح بالتفاعل مع المستخدم، مثل اتباع رابط، أن يتم حتى قبل استلام الصفحة بالكامل وعرضها.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

تحسين الموارد في المستند: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
تحسين الموارد في المستند وفقًا لاستراتيجية التحسين المحددة.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodesNumInSubtrees |  | العدد المطلوب من العقد الفرعية. القيمة الافتراضية هي عشرة. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

يخزن المستند في تدفق.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

يزيل البيانات الوصفية من المستند.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

إزالة توافق PDF/A من المستند

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

إزالة توافق PDF/UA من المستند

### repair {#repair--}
```
void repair()
```

يصلح المستند التالف.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

احفظ المستند بشكل تدريجي (مثلاً

### save {#save-java.io.OutputStream-}
يخزن المستند في تدفق.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
احفظ المستند

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به.

### save {#save-java.lang.String-}
يحفظ المستند في الملف المحدد.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد.

### saveIncrementally {#saveIncrementally-java.lang.String-}
يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد.

### saveXml {#saveXml-java.lang.String-}
احفظ المستند إلى XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
يرسل الصفحات المحددة من المستند إلى جهاز المستند للمعالجة.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
يرسل المستند بالكامل إلى جهاز المستند للمعالجة.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
يرسل المستند بالكامل إلى جهاز المستند للمعالجة.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
يرسل المستند بالكامل إلى جهاز المستند للمعالجة.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

تعيين علامة لتحديد الخط الذي يحدده البرنامج في حالة عدم وجود الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | قيمة منطقية |

### setBackground {#setBackground-java.awt.Color-}
يضبط لون خلفية المستند.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

يضبط علامة تحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
يضبط مجموعة المستند.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

يحصل على معامل التحويل لمحول pdf/ua (تحويل البيانات الوصفية وفهرس المستند فقط إذا تم ضبطه على true).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية افتراضيًا false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

يضبط علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PrintDuplex |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة. يمكننا إجراء بعض العمليات ومتابعة العمل مع المستند بعد استدعاء طريقة الحفظ إذا تم تمكين معامل ManualDispose هذا. ولكن يُنصح بشدة باستدعاء طريقة التخلص (dispose) عندما لا يعود هناك حاجة إلى كائن Document.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| manualDisposeEnabled |  | قيمة منطقية. (القيمة الافتراضية == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
يضبط الإجراء الذي يتم عند فتح المستند.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

يضبط علامة التحسين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
يضبط معلومات الصفحة. (للمولد فقط، لا تُملأ عند قراءة المستند)

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
يضبط وضع الصفحة، محددًا كيفية عرض المستند عند فتحه.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
void setPickTrayByPdfSize(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

يضبط خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PrintDuplex |

### setTitle {#setTitle-java.lang.String-}
تعيين عنوان لمستند PDF

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
تعيين بيانات XMP الوصفية للمستند.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
تحقق من صحة المستند في الملف المحدد.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
تحقق من صحة المستند في الملف المحدد.
