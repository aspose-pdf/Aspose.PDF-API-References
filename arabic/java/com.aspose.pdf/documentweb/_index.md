---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة DocumentWeb"
type: docs
weight: 1170
url: /ar/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

يمثل فئة DocumentWeb

## الحقول

| حقل | الوصف |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | يحدث عندما يستبدل الخط خطًا آخر في المستند. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | يقوم بتهيئة DocumentWeb فارغ. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | يقوم بتهيئة DocumentWeb فارغ. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | يقوم بتهيئة DocumentWeb فارغ. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | يقوم بتهيئة DocumentWeb فارغ. |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | يقوم بتهيئة DocumentWeb فارغ. |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | يقوم بتهيئة DocumentWeb فارغ. |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | يقوم بتهيئة DocumentWeb فارغ. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [afterImport](#afterImport--) | تعداد جميع التعليقات التوضيحية المسجلة واستدعاء AfterImport لكل منها. |
| [bindXml](#bindXml-java.io.InputStream-) | ربط xml بالمستند |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | ربط xml/xsl بالمستند |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | ربط xml/xsl بالمستند |
| [bindXml](#bindXml-java.lang.String-) | ربط xml بالمستند |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | ربط xml/xsl بالمستند |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | يغيّر كلمات مرور المستند. |
| [check](#check-boolean-) | يتحقق من صحة المستند. |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | تحويل المستند إلى مستند قابل للبحث. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | تحويل المستند بتطبيق Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | تحويل المستند بتطبيق Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | تحويل المستند بتطبيق Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | تحويل المستند بتطبيق Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | يحوّل الدفق من الصيغة المصدر إلى الدفق بالصِيغة الوجهة. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | يحوّل الدفق من الصيغة المصدر إلى ملف الوجهة بالصِيغة الوجهة. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | تحويل المستند وحفظ الأخطاء في الدفق المحدد. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | تحويل المستند باستخدام خيارات التحويل المحددة. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | يحوّل ملف المصدر من الصيغة المصدر إلى الدفق بالصِيغة الوجهة. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | يحوّل ملف المصدر من الصيغة المصدر إلى ملف الوجهة بالصِيغة الوجهة. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | تحويل المستند وحفظ الأخطاء في الملف المحدد. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | تحويل المستند وحفظ الأخطاء في الدفق المحدد. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | تحويل الصفحة إلى PNG لتدفق صورة DSR، OMR، OCR. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها. |
| [decrypt](#decrypt--) | يفك تشفير المستند. |
| [dispose](#dispose--) | مهمل. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | يشفر المستند. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | يشفر المستند. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | تصدير جميع تعليقات المستند إلى الدفق. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | يصدّر جميع تعليقات المستند إلى ملف XFDF |
| [flatten](#flatten--) | يزيل جميع الحقول (والتعليقات) من المستند ويضع قيمها بدلاً من ذلك. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | يزيل جميع الحقول من المستند ويضع قيمها بدلاً من ذلك. |
| [flattenTransparency](#flattenTransparency--) | يستبدل المحتوى الشفاف برسومات نقطية ومتجهة غير شفافة. |
| [freeMemory](#freeMemory--) | يمسح الذاكرة |
| [getAbsentFontHandler](#getAbsentFontHandler--) | إشعار حول الخطوط المفقودة أثناء معالجة المستندات. |
| [getActions](#getActions--) | يحصل على إجراءات المستند. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | يسمح بدمج محتويات الصفحة لتحسين حجم المستند. |
| [getBackground](#getBackground--) | يحصل على لون خلفية المستند. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | يعيد قيمة العنصر من قاموس الفهرس. |
| [getCollection](#getCollection--) | يحصل على مجموعة المستند. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | يحصل على إعدادات الأمان إذا كان المستند مشفّراً. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | يحصل على معالج أمان مخصص. |
| [getDefaultCopier](#getDefaultCopier--) | يعيد النسّاخ المستخدم لنسخ الصفحات إلى هذا المستند. |
| [getDestinations](#getDestinations--) | مهمل. |
| [getDirection](#getDirection--) | يحصل على ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
| [getDuplex](#getDuplex--) | يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | يحصل على مجموعة الملفات المدمجة في المستند. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع. |
| [getEngineDoc](#getEngineDoc--) | مثيل من IPdfDocument يُستخدم للوصول إلى بنية المستند الداخلية. |
| [getFileName](#getFileName--) | اسم ملف PDF الذي تسبب في هذا المستند |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | احصل على حد حجم الملف أو عيّنه لتحميل ملف كامل في الذاكرة. |
| [getForm](#getForm--) | يحصل على نموذج Acro Form للمستند. |
| [getId](#getId--) | يحصل على المعرف. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر. |
| [getInfo](#getInfo--) | يحصل على معلومات المستند. |
| [getJavaScript](#getJavaScript--) | مجموعة من JavaScript على مستوى المستند. |
| [getLogicalStructure](#getLogicalStructure--) | يحصل على البنية المنطقية للمستند. |
| [getMetadata](#getMetadata--) | بيانات تعريف المستند. |
| [getMetadataStream](#getMetadataStream--) | للاستخدام الداخلي فقط! |
| [getNamedDestinations](#getNamedDestinations--) | مجموعة من الوجهات المسماة في المستند. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
| [getObjectById](#getObjectById-java.lang.String-) | يحصل على كائن بالمعرف المحدد في المستند. |
| [getOpenAction](#getOpenAction--) | يحصل على الإجراء الذي يتم عند فتح المستند. |
| [getOptimizeSize](#getOptimizeSize--) | يحصل على علامة التحسين. |
| [getOutlines](#getOutlines--) | يحصل على مخططات المستند. |
| [getOutputIntents](#getOutputIntents--) | يحصل على مجموعة نوايا الإخراج في المستند. |
| [getPageInfo](#getPageInfo--) | يحصل على معلومات الصفحة. (للمولد فقط، لا يتم ملؤها عند قراءة المستند) |
| [getPageLabels](#getPageLabels--) | يحصل على تسميات الصفحات في المستند. |
| [getPageLayout](#getPageLayout--) | يحصل على تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
| [getPageMode](#getPageMode--) | يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند فتحه. |
| [getPages](#getPages--) | يحصل على مجموعة صفحات المستند. |
| [getPdfFormat](#getPdfFormat--) | يحصل على تنسيق PDF. |
| [getPermissions](#getPermissions--) | يحصل على أذونات المستند. |
| [getPrintScaling](#getPrintScaling--) | يحصل على خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [getTaggedContent](#getTaggedContent--) | يحصل على الوصول إلى محتوى TaggedPdf. |
| [getVersion](#getVersion--) | يحصل على نسخة من PDF من رأس ملف PDF. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | احصل على بيانات XMP الوصفية من المستند. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | يتحقق مما إذا تم حفظ مستند PDF الحالي مع تحديثات متدرجة. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | يستورد التعليقات التوضيحية من الدفق إلى المستند. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | يستورد التعليقات التوضيحية من ملف XFDF إلى المستند. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | العلم الذي يُشير إلى استبدال الخط المفقود. |
| [isCenterWindow](#isCenterWindow--) | يحصل على العلامة التي تحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | يحصل على علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تمكين تسجيل الإشعارات. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | يحصل أو يعيّن العلم الذي يتيح تفريغ جزء من المستند من الذاكرة. |
| [isEncrypted](#isEncrypted--) | يحصل على حالة التشفير للمستند. |
| [isFitWindow](#isFitWindow--) | يحصل على علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة الأولى المعروضة. |
| [isHandleSignatureChange](#isHandleSignatureChange--) | إلقاء استثناء إذا تم حفظ المستند مع تغييرات وكان يحتوي على توقيع |
| [isHideMenubar](#isHideMenubar--) | يحصل على العلامة التي تحدد ما إذا كان شريط القوائم يجب إخفاؤه عندما يكون المستند نشطًا. |
| [isHideToolBar](#isHideToolBar--) | يحصل على العلامة التي تحدد ما إذا كان شريط الأدوات يجب إخفاؤه عندما يكون المستند نشطًا. |
| [isHideWindowUI](#isHideWindowUI--) | يحصل أو يضبط العلامة التي تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
| [isLicensed](#isLicensed--) | يحصل على حالة الترخيص للنظام. |
| [isLinearized](#isLinearized--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة. |
| [isPdfaCompliant](#isPdfaCompliant--) | يتحقق مما إذا كان المستند متوافقًا مع PDF/A. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | يحصل على ما إذا كان المستند متوافقًا مع PDF/UA. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | يحصل على العلامة التي تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | يفحص ما إذا كان المستند يحتاج إلى استدعاء طريقة Repair. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | بشكل افتراضي، عملية التحقق من PDF/A ضرورية لتحديث أو إزالة البيانات المتوافقة مع PDF/A إذا تم خرق بعض القواعد. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | يقوم بتحميل ملف وتحويله إلى PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | يدمج المستندات. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | يدمج المستندات. |
| [merge](#merge-com.aspose.pdf.Document...-) | يدمج المستندات. |
| [merge](#merge-java.lang.String...-) | يدمج ملفات PDF. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | يدمج المستندات. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | يدمج المستندات. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | يدمج المستندات. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | يدمج ملفات PDF. |
| [optimize](#optimize--) | قم بترتيب المستند لتتمكن من - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال عبر رابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة تدريجيًا مع وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة (عرض أهم البيانات أولاً)؛ - السماح بالتفاعل مع المستخدم، مثل اتباع رابط، أن يتم حتى قبل استلام الصفحة بالكامل وعرضها. |
| [optimizeResources](#optimizeResources--) | تحسين الموارد في المستند: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | تحسين الموارد في المستند وفقًا لاستراتيجية التحسين المحددة. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | طريقة داخلية |
| [processParagraphs](#processParagraphs--) | يخزن المستند في المُولِّد. |
| [removeMetadata](#removeMetadata--) | يزيل البيانات الوصفية من المستند. |
| [removePdfaCompliance](#removePdfaCompliance--) | إزالة توافق PDF/A من المستند |
| [removePdfUaCompliance](#removePdfUaCompliance--) | إزالة توافق PDF/UA من المستند |
| [repair](#repair--) | يصلح المستند التالف. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | يصلح المستند التالف. |
| [resumeUpdate](#resumeUpdate--) | يستأنف تحديث المستند |
| [save](#save--) | احفظ المستند بشكل تدريجي (مثلاً |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | يحفظ المستند إلى تدفق الاستجابة مع خيارات الحفظ. |
| [save](#save-java.io.OutputStream-) | يخزن المستند في تدفق. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | يحفظ المستند باسم جديد مع تنسيق الملف. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به. |
| [save](#save-com.aspose.pdf.SaveOptions-) | يحفظ المستند باستخدام خيارات الحفظ. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | للاستخدام الداخلي فقط |
| [save](#save-java.lang.String-) | يحفظ المستند في الملف المحدد. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | يحفظ المستند باسم جديد مع تنسيق الملف. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | يحفظ مستند PDF بشكل تدريجي إلى التدفق المحدد. |
| [saveXml](#saveXml-java.lang.String-) | احفظ المستند إلى XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | يرسل الصفحات المحددة من المستند إلى جهاز المستند للمعالجة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | يرسل المستند بالكامل إلى جهاز المستند للمعالجة. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | إشعار حول الخطوط المفقودة أثناء معالجة المستندات. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | تعيين العلامة لاستبدال الخط المفقود. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | يسمح بدمج محتويات الصفحة لتحسين حجم المستند. |
| [setBackground](#setBackground-java.awt.Color-) | يضبط لون خلفية المستند. |
| [setCenterWindow](#setCenterWindow-boolean-) | يضبط العلم الذي يحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | يضبط مجموعة المستند. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | يحصل على معامل التحويل لمحول pdf/ua (تحويل البيانات الوصفية وفهرس المستند فقط إذا تم ضبطه على true). |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | يضبط حد حجم الملف لتحميل الملف بالكامل في الذاكرة إلى القيمة الافتراضية التي تساوي 210 ميغابايت. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | يضبط علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند. |
| [setDuplex](#setDuplex-int-) | يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تمكين تسجيل الإشعارات. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | يحصل أو يعيّن العلم الذي يتيح تفريغ جزء من المستند من الذاكرة. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | احصل على حد حجم الملف أو عيّنه لتحميل ملف كامل في الذاكرة. |
| [setFitWindow](#setFitWindow-boolean-) | يضبط علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | إلقاء استثناء إذا تم حفظ المستند مع تغييرات وكان يحتوي على توقيع |
| [setHideMenubar](#setHideMenubar-boolean-) | يضبط علامة تحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا. |
| [setHideToolBar](#setHideToolBar-boolean-) | يضبط علامة تحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | يضبط علامة تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر. |
| [setLinearized](#setLinearized-boolean-) | يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | يضبط الإجراء الذي يتم عند فتح المستند. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | يضبط علامة التحسين. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | يضبط معلومات الصفحة. (للمولد فقط، لا تُملأ عند قراءة المستند) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | يضبط تخطيط الصفحة الذي سيُستخدم عند فتح المستند. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | يضبط وضع الصفحة، محددًا كيفية عرض المستند عند فتحه. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | يضبط علامة تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة. |
| [setPrintScaling](#setPrintScaling-int-) | يضبط خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | بشكل افتراضي، عملية التحقق من PDF/A ضرورية لتحديث أو إزالة PDF/A إذا تم خرق بعض القواعد. |
| [setTitle](#setTitle-java.lang.String-) | تعيين عنوان لمستند PDF |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | تعيين بيانات XMP الوصفية للمستند. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A. |
| [suppressUpdate](#suppressUpdate--) | يقمع تحديث بيانات المحتوى لجميع الصفحات. لا يتم تحديث المحتوى حتى يتم استدعاء ResumeUpdate. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | تحقق من صحة المستند في الملف المحدد. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | تحقق من صحة المستند في الملف المحدد. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | تحقق من صحة المستند في الملف المحدد. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

يحدث عندما يستبدل الخط خطًا آخر في المستند.

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

يقوم بتهيئة DocumentWeb فارغ.

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
يقوم بتهيئة DocumentWeb فارغ.

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
يقوم بتهيئة DocumentWeb فارغ.

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
يقوم بتهيئة DocumentWeb فارغ.

### DocumentWeb {#DocumentWeb-java.lang.String-}
يقوم بتهيئة DocumentWeb فارغ.

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
يقوم بتهيئة DocumentWeb فارغ.

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
يقوم بتهيئة DocumentWeb فارغ.

### afterImport {#afterImport--}
```
public void afterImport()
```

تعداد جميع التعليقات التوضيحية المسجلة واستدعاء AfterImport لكل منها.

### bindXml {#bindXml-java.io.InputStream-}
ربط xml بالمستند

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
ربط xml/xsl بالمستند

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
ربط xml/xsl بالمستند

### bindXml {#bindXml-java.lang.String-}
ربط xml بالمستند

### bindXml {#bindXml-java.lang.String-java.lang.String-}
ربط xml/xsl بالمستند

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
يغيّر كلمات مرور المستند.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

يتحقق من صحة المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| doRepair |  | إذا كان صحيحًا، سيتم إصلاح المشكلات المكتشفة. |

**Returns:**
قيمة منطقية True - إذا تم إصلاح المستند؛ وإلا false.

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
تحويل المستند إلى مستند قابل للبحث.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
تحويل المستند بتطبيق Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
تحويل المستند بتطبيق Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
تحويل المستند بتطبيق Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
تحويل المستند بتطبيق Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
يحوّل الدفق من الصيغة المصدر إلى الدفق بالصِيغة الوجهة.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
يحوّل الدفق من الصيغة المصدر إلى ملف الوجهة بالصِيغة الوجهة.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
تحويل المستند وحفظ الأخطاء في الدفق المحدد.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
تحويل المستند باستخدام خيارات التحويل المحددة.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
يحوّل ملف المصدر من الصيغة المصدر إلى الدفق بالصِيغة الوجهة.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
يحوّل ملف المصدر من الصيغة المصدر إلى ملف الوجهة بالصِيغة الوجهة.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
تحويل المستند وحفظ الأخطاء في الملف المحدد.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
تحويل المستند وحفظ الأخطاء في الدفق المحدد.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
تحويل الصفحة إلى PNG لتدفق صورة DSR، OMR، OCR.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
تحويل المستند إلى مستند قابل للبحث وتجاوز أخطاء hochr التي لا يمكن تحويلها.

### decrypt {#decrypt--}
```
public void decrypt()
```

يفك تشفير المستند.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

مهمل.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
يشفر المستند.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
يشفر المستند.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
تصدير جميع تعليقات المستند إلى الدفق.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
يصدّر جميع تعليقات المستند إلى ملف XFDF

### flatten {#flatten--}
```
public void flatten()
```

يزيل جميع الحقول (والتعليقات) من المستند ويضع قيمها بدلاً من ذلك.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
يزيل جميع الحقول من المستند ويضع قيمها بدلاً من ذلك.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

يستبدل المحتوى الشفاف برسومات نقطية ومتجهة غير شفافة.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

يمسح الذاكرة

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

إشعار حول الخطوط المفقودة أثناء معالجة المستندات.

**Returns:**
مثيل ADocument.AbsentFontHandler

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

يحصل على إجراءات المستند.

**Returns:**
كائن DocumentActionCollection

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

يسمح بدمج محتويات الصفحة لتحسين حجم المستند.

**Returns:**
قيمة منطقية

### getBackground {#getBackground--}
```
public Color getBackground()
```

يحصل على لون خلفية المستند.

**Returns:**
كائن java.awt.Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
يعيد قيمة العنصر من قاموس الفهرس.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

يحصل على مجموعة المستند.

**Returns:**
كائن Collection

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

يحصل على إعدادات الأمان إذا كان المستند مشفّراً.

**Returns:**
عنصر CryptoAlgorithm أو null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

يحصل على معالج أمان مخصص.

**Returns:**
مثيل ICustomSecurityHandler

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

يعيد النسّاخ المستخدم لنسخ الصفحات إلى هذا المستند.

**Returns:**
كائن Copier

### getDestinations {#getDestinations--}
```
@Deprecated public DestinationCollection getDestinations()
```

مهمل.

**Returns:**
كائن DestinationCollection

### getDirection {#getDirection--}
```
public Direction getDirection()
```

يحصل على ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار).

**Returns:**
عنصر Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Returns:**
عنصر PrintDuplex

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

يحصل على مجموعة الملفات المدمجة في المستند.

**Returns:**
كائن EmbeddedFileCollection

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true.

**Returns:**
قيمة منطقية

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع.

**Returns:**
قيمة منطقية

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

مثيل من IPdfDocument يُستخدم للوصول إلى بنية المستند الداخلية.

**Returns:**
كائن IPdfDocument

### getFileName {#getFileName--}
```
public String getFileName()
```

اسم ملف PDF الذي تسبب في هذا المستند

**Returns:**
قيمة سلسلة

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

احصل على حد حجم الملف أو عيّنه لتحميل ملف كامل في الذاكرة.

**Returns:**
قيمة int

### getForm {#getForm--}
```
public Form getForm()
```

يحصل على نموذج Acro Form للمستند.

**Returns:**
كائن Form

### getId {#getId--}
```
public Id getId()
```

يحصل على المعرف.

**Returns:**
كائن Id

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر.

**Returns:**
قيم منطقية

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

يحصل على معلومات المستند.

**Returns:**
كائن DocumentInfo

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

مجموعة من JavaScript على مستوى المستند.

**Returns:**
كائن JavaScriptCollection

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

يحصل على البنية المنطقية للمستند.

**Returns:**
كائن RootElement

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

بيانات تعريف المستند.

**Returns:**
كائن Metadata

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

للاستخدام الداخلي فقط!

**Returns:**
كائن IPdfStreamAccessor

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

مجموعة من الوجهات المسماة في المستند.

**Returns:**
مثيل NamedDestinationCollection

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند الخروج من وضع ملء الشاشة.

**Returns:**
عنصر PageMode

### getObjectById {#getObjectById-java.lang.String-}
يحصل على كائن بالمعرف المحدد في المستند.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

يحصل على الإجراء الذي يتم عند فتح المستند.

**Returns:**
كائن IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

يحصل على علامة التحسين.

**Returns:**
قيمة منطقية

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

يحصل على مخططات المستند.

**Returns:**
كائن OutlineCollection

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

يحصل على مجموعة نوايا الإخراج في المستند.

**Returns:**
مثيل OutputIntents

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

يحصل على معلومات الصفحة. (للمولد فقط، لا يتم ملؤها عند قراءة المستند)

**Returns:**
معلومات الصفحة.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

يحصل على تسميات الصفحات في المستند.

**Returns:**
كائن PageLabelCollection

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

يحصل على تخطيط الصفحة الذي سيُستخدم عند فتح المستند.

**Returns:**
عنصر PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

يحصل على وضع الصفحة، محددًا كيفية عرض المستند عند فتحه.

**Returns:**
عنصر PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

يحصل على مجموعة صفحات المستند.

**Returns:**
قيمة منطقية

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

يحصل على تنسيق PDF.

**Returns:**
PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

يحصل على أذونات المستند.

**Returns:**
قيمة int

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

يحصل على خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Returns:**
عنصر PrintScaling

### getTaggedContent {#getTaggedContent--}
```
public ITaggedContent getTaggedContent()
```

يحصل على الوصول إلى محتوى TaggedPdf.

**Returns:**
مثيل ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

يحصل على نسخة من PDF من رأس ملف PDF.

**Returns:**
كائن String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
احصل على بيانات XMP الوصفية من المستند.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

يتحقق مما إذا تم حفظ مستند PDF الحالي مع تحديثات متدرجة.

**Returns:**
صحيح إذا كان مستند PDF يحتوي على تحديثات متزايدة؛ وإلا، خطأ.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
يستورد التعليقات التوضيحية من الدفق إلى المستند.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
يستورد التعليقات التوضيحية من ملف XFDF إلى المستند.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

العلم الذي يُشير إلى استبدال الخط المفقود.

**Returns:**
قيمة منطقية

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

يحصل على العلامة التي تحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة.

**Returns:**
قيمة منطقية

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط.

**Returns:**
قيمة منطقية افتراضيًا false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

يحصل على علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند.

**Returns:**
قيمة منطقية

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تمكين تسجيل الإشعارات.

**Returns:**
قيمة منطقية

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

يحصل أو يعيّن العلم الذي يتيح تفريغ جزء من المستند من الذاكرة.

**Returns:**
قيمة منطقية

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

يحصل على حالة التشفير للمستند.

**Returns:**
قيمة منطقية

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

يحصل على علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة الأولى المعروضة.

**Returns:**
قيمة منطقية

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

إلقاء استثناء إذا تم حفظ المستند مع تغييرات وكان يحتوي على توقيع

**Returns:**
قيمة منطقية

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

يحصل على العلامة التي تحدد ما إذا كان شريط القوائم يجب إخفاؤه عندما يكون المستند نشطًا.

**Returns:**
قيمة منطقية

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

يحصل على العلامة التي تحدد ما إذا كان شريط الأدوات يجب إخفاؤه عندما يكون المستند نشطًا.

**Returns:**
قيمة منطقية

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

يحصل أو يضبط العلامة التي تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا.

**Returns:**
قيمة منطقية

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

يحصل على حالة الترخيص للنظام.

**Returns:**
قيمة منطقية

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا.

**Returns:**
قيمة منطقية

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة.

**Returns:**
قيمة منطقية. (القيمة الافتراضية == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

يتحقق مما إذا كان المستند متوافقًا مع PDF/A.

**Returns:**
قيمة منطقية

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

يحصل على ما إذا كان المستند متوافقًا مع PDF/UA.

**Returns:**
قيمة منطقية

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

يحصل على العلامة التي تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة.

**Returns:**
قيمة منطقية

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
يفحص ما إذا كان المستند يحتاج إلى استدعاء طريقة Repair.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

بشكل افتراضي، عملية التحقق من PDF/A ضرورية لتحديث أو إزالة البيانات المتوافقة مع PDF/A إذا تم خرق بعض القواعد.

**Returns:**
قيمة منطقية

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A.

**Returns:**
قيمة منطقية

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
يقوم بتحميل ملف وتحويله إلى PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
يدمج المستندات.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
يدمج المستندات.

### merge {#merge-com.aspose.pdf.Document...-}
يدمج المستندات.

### merge {#merge-java.lang.String...-}
يدمج ملفات PDF.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
يدمج المستندات.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
يدمج المستندات.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
يدمج المستندات.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
يدمج ملفات PDF.

### optimize {#optimize--}
```
public void optimize()
```

قم بترتيب المستند لتتمكن من - فتح الصفحة الأولى بأسرع ما يمكن؛ - عرض الصفحة التالية أو الانتقال عبر رابط إلى الصفحة التالية بأسرع ما يمكن؛ - عرض الصفحة تدريجيًا مع وصولها عندما يتم تسليم بيانات الصفحة عبر قناة بطيئة (عرض أهم البيانات أولاً)؛ - السماح بالتفاعل مع المستخدم، مثل اتباع رابط، أن يتم حتى قبل استلام الصفحة بالكامل وعرضها.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

تحسين الموارد في المستند: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
تحسين الموارد في المستند وفقًا لاستراتيجية التحسين المحددة.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

ينظم عقد شجرة الصفحات في المستند في شجرة متوازنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodesNumInSubtrees |  | العدد المطلوب من العقد الفرعية. القيمة الافتراضية هي عشرة. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
طريقة داخلية

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

يخزن المستند في المُولِّد.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

يزيل البيانات الوصفية من المستند.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

إزالة توافق PDF/A من المستند

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

إزالة توافق PDF/UA من المستند

### repair {#repair--}
```
public void repair()
```

يصلح المستند التالف.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
يصلح المستند التالف.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

يستأنف تحديث المستند

### save {#save--}
```
public void save()
```

احفظ المستند بشكل تدريجي (مثلاً

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
يحفظ المستند إلى تدفق الاستجابة مع خيارات الحفظ.

### save {#save-java.io.OutputStream-}
يخزن المستند في تدفق.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
يحفظ المستند باسم جديد مع تنسيق الملف.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
يحفظ المستند باسم جديد مع ضبط خيارات الحفظ الخاصة به.

### save {#save-com.aspose.pdf.SaveOptions-}
يحفظ المستند باستخدام خيارات الحفظ.

### save {#save-com.aspose.ms.System.IO.Stream-}
للاستخدام الداخلي فقط

### save {#save-java.lang.String-}
يحفظ المستند في الملف المحدد.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
يحفظ المستند باسم جديد مع تنسيق الملف.

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

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
إشعار حول الخطوط المفقودة أثناء معالجة المستندات.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean substitute)
```

تعيين العلامة لاستبدال الخط المفقود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بديل |  | قيمة منطقية |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

يسمح بدمج محتويات الصفحة لتحسين حجم المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBackground {#setBackground-java.awt.Color-}
يضبط لون خلفية المستند.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

يضبط العلم الذي يحدد ما إذا كان موقع نافذة المستند سيُوسَّط على الشاشة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
يضبط مجموعة المستند.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

يحصل على معامل التحويل لمحول pdf/ua (تحويل البيانات الوصفية وفهرس المستند فقط إذا تم ضبطه على true).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

يضبط حد حجم الملف لتحميل الملف بالكامل في الذاكرة إلى القيمة الافتراضية التي تساوي 210 ميغابايت.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
يضبط ترتيب قراءة النص: L2R (من اليسار إلى اليمين) أو R2L (من اليمين إلى اليسار).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

لا يمكن تنفيذ العديد من العمليات على الخط إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية افتراضيًا false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

يضبط علامة تحدد ما إذا كان شريط عنوان نافذة المستند يجب أن يعرض عنوان المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

يحصل أو يعيّن خيار معالجة وضع الطباعة المزدوج لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PrintDuplex |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

خاصية تُعلن أن المستند يجب أن يدمج جميع خطوط Type1 القياسية التي تم تعيين علامة IsEmbedded لها إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تمكين تسجيل الإشعارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

يحصل أو يعيّن العلم الذي يتيح تفريغ جزء من المستند من الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

يحصل أو يعيّن العلامة لإدارة تنقية حقول التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

احصل على حد حجم الملف أو عيّنه لتحميل ملف كامل في الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب تغيير حجم نافذة المستند لتناسب الصفحة المعروضة أولاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

إلقاء استثناء إذا تم حفظ المستند مع تغييرات وكان يحتوي على توقيع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب إخفاء شريط القوائم عندما يكون المستند نشطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب إخفاء شريط الأدوات عندما يكون المستند نشطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب إخفاء عناصر واجهة المستخدم عندما يكون المستند نشطًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

يحصل أو يعيّن العلامة لتجاهل الأخطاء في ملفات المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيم منطقية |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

بشكل افتراضي، تقوم طريقة الحفظ بإغلاق التدفقات الداخلية وإطلاق موارد الذاكرة.

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
public void setOptimizeSize(boolean value)
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
public final void setPickTrayByPdfSize(boolean value)
```

يضبط علامة تحدد ما إذا كان يجب استخدام حجم صفحة PDF لاختيار صينية الورق المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

يضبط خيار معالجة مقياس الطباعة لاستخدامه عند طباعة الملف من مربع حوار الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PrintDuplex |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

بشكل افتراضي، عملية التحقق من PDF/A ضرورية لتحديث أو إزالة PDF/A إذا تم خرق بعض القواعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | قيمة منطقية |

### setTitle {#setTitle-java.lang.String-}
تعيين عنوان لمستند PDF

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
تعيين بيانات XMP الوصفية للمستند.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

يحصل أو يضبط ما إذا كان المستند متوافقًا مع PDF/A.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

يقمع تحديث بيانات المحتوى لجميع الصفحات. لا يتم تحديث المحتوى حتى يتم استدعاء ResumeUpdate.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
تحقق من صحة المستند في الملف المحدد.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
تحقق من صحة المستند في الملف المحدد.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
تحقق من صحة المستند في الملف المحدد.
