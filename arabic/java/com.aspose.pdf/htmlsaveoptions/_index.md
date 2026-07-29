---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى تنسيق HTML."
type: docs
weight: 1990
url: /ar/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

خيارات الحفظ للتصدير إلى تنسيق HTML.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | ينشئ مثيلاً جديداً لفئة HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | ينشئ مثيلاً جديداً لفئة {@code HtmlSaveOptions}. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | ينشئ مثيلاً جديداً لفئة HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | ينشئ مثيلاً جديداً لفئة HtmlSaveOptions. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | إذا كان السمة 'SplitOnPages=false'، فإن HTML الكامل الذي يمثل جميع صفحات PDF المدخلة لن يتم تقسيمه إلى صفحات HTML مختلفة، بل سيُوضع في ملف HTML نتيجي كبير واحد. ولكن كل صفحة PDF مصدر ستُمثَّل بمنطقة مستطيلة خاصة بها في HTML (إذا لزم الأمر يمكن تأطير تلك المناطق لإظهار حواف ورق الصفحة باستخدام السمة الخاصة 'PageBorderIfAny'). تُعرّف هذه المعلمة عرض الهامش الذي سيُترك إجباريًا حول مناطق HTML الناتجة التي تمثل صفحات مستند PDF المصدر. في الأساس، تُحدد هذه المعلمة الفاصل المضمون بين تمثيلات HTML لصفحات PDF \"paper\" في مثل هذا الوضع من التحويل. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | تحدد هذه المعلمة إجراءات التنعيم المطلوبة أثناء تحويل الصور الخلفية المركبة من PDF إلى HTML. |
| [getBatchSize](#getBatchSize--) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | عند توليد محول PDFtoHTML ملفات CSS الناتجة، يتم إنشاء أسماء فئات CSS (مثل \".stl_01 {}\" ... \".stl_NN {}\") وتُستخدم في CSS الناتج. تسمح هذه الخاصية بتعيين بادئة اسم الفئة قسرًا. على سبيل المثال، إذا كنت تريد أن تبدأ جميع أسماء الفئات بـ 'my_prefix_' (أي أن تكون شيئًا مثل 'my_prefix_1' ... 'my_prefix_NNN')، فما عليك سوى تعيين 'my_prefix_' لهذه الخاصية قبل التحويل. إذا تُركت هذه الخاصية دون تعديل (أي أن تكون القيمة null)، فسيقوم المحول بإنشاء أسماء الفئات بنفسه (ستكون شيئًا مثل \".stl_01 {}\" ... \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء تحويل Pdf إلى Html للتعامل مع حفظ ملفات CSS المتعلقة بالمستند HTML المُنشأ ككل أو بصفحاته (إذا تم إنشاء عدة صفحات HTML). إذا رغبت في معالجة ملف CSS بطريقة معينة، يرجى إنشاء الطريقة المناسبة وتعيين المفوض (delegate) المُنشأ منها إلى هذه الخاصية. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | يمكن أن يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML. يمكنك تعيين لهذا الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفّذ معالجة صفحة HTML واحدة (لتكون دقيقة - markup-HTML، بدون ملفات مرتبطة خارجية إذا وجدت) التي تم إنشاؤها أثناء التحويل. في مثل هذه الحالة يمكن إجراء المعالجة (مثل حفظ HTML للصفحة في تدفق أو قرص) في ذلك الكود المخصص. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يكون مستخدمًا. إذا كان يجب تنفيذ المعالجة لهذا أو ذاك الحالة لسبب ما بواسطة كود المحول نفسه، وليس في الكود المخصص، يرجى ضبط علامة 'CustomProcessingCancelled' في متغيّر 'htmlSavingInfo' الخاص بالمعامل: سيتسبب ذلك في إشارة إلى المحول بأن جميع الخطوات اللازمة لمعالجة هذا المورد يجب أن تُنفّذ في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود مخصص خارجي للمعالجة. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لإظهار شريط تقدم أو رسائل حول عدد الصفحات المعالجة حاليًا، مثال على كود المعالج الذي يعرض التقدم في وحدة التحكم هو : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء التحويل للتعامل المخصص مع ملفات الموارد المرجعية التي تم إنشاؤها (مثل الصور والخطوط) المرتبطة بعقد HTML المحفوظة. يجب على هذه الاستراتيجية معالجة الموارد وإرجاع سلسلة تمثل عنوان URL المرغوب للموارد المحفوظة في HTML المُولَّد. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | يمكن لهذا الحقل أن يحتوي على طريقة مخصصة تُعيد عنوان URL (أو قالب URL إذا كان توليد الصفحات المتعددة مفعَّلًا - راجع التفاصيل أدناه) لملف CSS المستهدف كما يجب وضعه في HTML الناتج المُولَّد. على سبيل المثال، إذا كنت تريد أن يضع المحول عنوان URL محدد بدلاً من اسم ملف CSS القياسي في CSS المُولَّد، فيجب عليك إنشاء وإدراج في هذا الخاصية طريقة تُولِّد عنوان URL المرغوب. إذا تم تعيين العلامة 'SplitCssIntoPages'، فيجب على هذه الاستراتيجية المخصصة (إن وجدت) أن تُعيد ليس عنوان URL دقيق للـ CSS بل قالب سلسلة يُستبدل فيه العنصر النائب برقم الصفحة باستخدام دالة String.Format() داخل المحول، بحيث يمكن تحويله إلى عنوان URL لملف CSS الخاص بهذه الصفحة أو تلك الصفحة. أمثلة على السلسلة المرجعة المتوقعة في مثل هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | يحدد اسم الخط المثبت الذي يُستخدم لاستبدال أي خط في المستند غير مضمن وغير مثبت في النظام. إذا كان القيمة null فسيتم استخدام خط الاستبدال الافتراضي. |
| [getDocumentType](#getDocumentType--) | يحصل على {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | قائمة بأسماء خطوط PDF المضمنة التي لا يتم تضمينها في HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي يجب أخذ أرقام الصفحات الصالحة من النطاق (1...[NumberOfPagesInConvertedDocument]). لا يؤثر ترتيب ظهور الصفحات في هذه القائمة على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في ملف PDF الأصلي. إذا كانت هذه القائمة فارغة (null) كما هو الافتراضي، سيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (1-[amountOfPagesInDocument]) سيتم رمي استثناء. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | هذه الخاصية تحدد نص الفقرة بعرض كامل لوضع التدفق، FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | يحدد قاعدة ترميز خاصة لضبط فك تشفير PDF للمستند الحالي |
| [getFontSavingMode](#getFontSavingMode--) | يحدد وضع حفظ الخط الذي سيُستخدم أثناء حفظ PDF إلى الصيغة المطلوبة |
| [getFontSources](#getFontSources--) | <p> مصادر الخطوط للخطوط المحفوظة مسبقًا. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | أحيانًا تكون هناك متطلبات محددة لتوليد ترميز HTML. هذه المعلمة تحدد أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية هذه المتطلبات المحددة. |
| [getImageResolution](#getImageResolution--) | يحصل أو يضبط الدقة لتصيير الصورة. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | يضبط وضعية تموضع الحروف في الكلمات في HTML الناتج |
| [getMinimalLineWidth](#getMinimalLineWidth--) | هذه الخاصية تحدد الحد الأدنى لعرض خط المسار الرسومي. إذا كان سمك الخط أقل من 1 بكسل، فإن Adobe Acrobat يقوم بتقريبه إلى هذه القيمة. لذا يمكن استخدام هذه الخاصية لمحاكاة هذا السلوك في متصفحات HTML. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | هذه الخاصية تمثل مجموعة من الإعدادات المستخدمة لرسم الحدود (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. في الأساس تتعلق بإظهار حواف ورق الصفحة، وليس حدود الصفحة المشار إليها في صفحة PDF نفسها. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | هذه الخاصية تمثل مجموعة من الهوامش الإضافية للصفحة (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | تحدد ما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، ملفات CSS) سيتم تضمينها في ملف HTML الرئيسي أم سيتم إنشاؤها ككيانات ثنائية منفصلة |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | يمكن أن يحتوي PDF المحول على صور نقطية. هذه المعلمة تحدد كيفية التعامل معها أثناء تحويل PDF إلى HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ أي صور فيه إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات الصور (إن وجدت) مع الملفات الأخرى المرتبطة بـ HTML. لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ صور SVG فيه فقط إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات SVG (إن وجدت) مع ملفات الصور الأخرى (قرب ملف الإخراج) أو في مجلد خاص للصور (إذا تم تحديده في خيار SpecialImagesFolderIfAny). لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني. |
| [getTitle](#getTitle--) | يحصل أو يضبط عنوان صفحة HTML. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | يحصل على العلامة التي تشير إلى ما إذا كانت رسومات SVG المكتشفة (إن وجدت) سيتم ضغطها (مضغوطة) إلى صيغة SVGZ أثناء الحفظ. القيمة: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | إذا تم تعيين الخاصية ConvertMarkedContentToLayers إلى true فسيتم وضع جميع العناصر داخل محتوى PDF المميز (الطبقة) في عنصر div في HTML مع الخاصية "data-pdflayer" التي تحدد اسم الطبقة. سيتم استخراج اسم الطبقة من الخصائص الاختيارية لمحتوى PDF المميز. إذا كانت هذه الخاصية false (افتراضيًا) فلن يتم إنشاء أي طبقات من محتوى PDF المميز. |
| [isFixedLayout](#isFixedLayout--) | يحصل على قيمة تشير إلى ما إذا كان HTML تم إنشاؤه كتنسيق ثابت. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | If attribute 'SplitOnPages=false'، فسيتم وضع كل HTML الذي يمثل جميع صفحات PDF المدخلة في ملف HTML نتيجة واحد كبير. تحدد هذه العلامة ما إذا كان سيتم إنشاء HTML النتيجة بهذه الطريقة بحيث يعتمد تدفق المناطق التي تمثل صفحات PDF في HTML النتيجة على دقة شاشة المشاهد. افترض أن عرض الشاشة على جانب المشاهد كبير بما يكفي لوضع صفحتين أو أكثر بجانب بعضهما في الاتجاه الأفقي. إذا تم تعيين هذه العلامة إلى true، فستُستَخدم هذه الإمكانية (سيتم عرض العديد من الصفحات في الاتجاه الأفقي بجانب بعضها قدر الإمكان، ثم ستُعرض مجموعة الصفحات الأفقية التالية تحت الأولى). وإلا فإن الصفحات ستتدفق بهذه الطريقة: الصفحة التالية تُوضع دائمًا تحت السابقة. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | هذه السمة تُشغِّل الوضع الذي لا تُجمَّع فيه رموز النص إلى كلمات وسلاسل. يتيح هذا الوضع الحفاظ على أقصى دقة أثناء تموضع الرموز على الصفحة ويمكن استخدامه لتحويل المستندات التي تحتوي على نوتات موسيقية أو رموز يجب وضعها بشكل منفصل عن بعضها. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | يحدد ما إذا كان سيتم إزالة المنطقة الفارغة العلوية والسفلية دون أي محتوى (إن وجدت) في HTML المُنشأ. |
| [isRenderTextAsImage](#isRenderTextAsImage--) | إذا تم تعيين السمة RenderTextAsImage إلى true، يصبح النص من المصدر صورة في HTML. قد يكون ذلك مفيدًا لجعل النص غير قابل للتحديد أو عندما لا يتم عرض نص HTML بشكل صحيح. |
| [isSaveFullFont](#isSaveFullFont--) | يشير إلى أنه سيتم حفظ الخط الكامل، يدعم فقط خطوط True Type. بشكل افتراضي SaveFullFont = false ويقوم المحول بحفظ مجموعة فرعية من الخط الأصلي اللازمة لعرض نص المستند. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | يمكن أن يحتوي PDF على نصوص محجوبة بواسط عناصر أخرى (مثلاً بالصور) ولكن يمكن تحديدها إلى الحافظة في Acrobat Reader (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة لتقليد سلوك Acrobat Reader (وإلا فإن هذه النصوص عادةً تُحفظ مخفية، غير متاحة للنسخ إلى الحافظة). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | يمكن أن يحتوي PDF على نصوص شفافة يمكن تحديدها إلى الحافظة (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | هذه السمة تحدد تجميعًا تسلسليًا للرموز والكلمات إلى سلاسل. على سبيل المثال، العلامات والكلمات قد يكون لها ترتيب مختلف في HTML المحول وتريد أن تتطابق. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | عند اختيار وضع متعدد الصفحات (أي أن 'SplitIntoPages' هو 'true')، تحدد هذه السمة ما إذا يجب إنشاء ملف CSS منفصل لكل صفحة HTML نتيجة. بشكل افتراضي تكون هذه السمة false، وبالتالي يُنشأ ملف CSS كبير مشترك لجميع الصفحات المُنشأة. عادةً ما يكون الحجم الإجمالي لجميع ملفات CSS التي تُولد في هذا الوضع (CSS واحد لكل صفحة) أكبر بكثير من حجم ملف CSS واحد كبير، لأن في الحالة الأولى تتكرر فئات CSS في عدة ملفات لكل صفحة. لذلك، يُفضَّل عدم استخدام هذا الإعداد إلا عندما تكون مهتمًا بمعالجة كل صفحة HTML بشكل مستقل في المستقبل، وبالتالي يكون حجم CSS لكل صفحة منفصلة هو الأمر الأكثر حرجًا. |
| [isSplitIntoPages](#isSplitIntoPages--) | يحصل على العلامة التي تشير إلى ما إذا كانت كل صفحة من المستند المصدر ستُحول إلى مستند HTML هدف خاص بها، أي ما إذا كان HTML النتيجة سيتقسم إلى عدة صفحات HTML. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | لا يحتوي PDF نفسه على علامات تسطير للنصوص. يتم محاكاة ذلك بخط موضع تحت النص. يتيح هذا الخيار للمحول محاولة تخمين أن هذا الخط أو ذاك هو تسطير النص ووضع هذه المعلومة في CSS بدلاً من رسم التسطير رسوميًا. |
| [isUseZOrder](#isUseZOrder--) | إذا تم تعيين السمة UseZORder إلى true، تُضاف الرسومات والنص إلى مستند HTML الناتج وفقًا لترتيب Z في مستند PDF الأصلي. إذا كانت هذه السمة false، تُوضع جميع الرسومات كطبقة واحدة مما قد يسبب بعض التأثيرات غير الضرورية للكائنات المتراكبة. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | إذا كان السمة 'SplitOnPages=false'، فإن HTML الكامل الذي يمثل جميع صفحات PDF المدخلة لن يتم تقسيمه إلى صفحات HTML مختلفة، بل سيُوضع في ملف HTML نتيجي كبير واحد. ولكن كل صفحة PDF مصدر ستُمثَّل بمنطقة مستطيلة خاصة بها في HTML (إذا لزم الأمر يمكن تأطير تلك المناطق لإظهار حواف ورق الصفحة باستخدام السمة الخاصة 'PageBorderIfAny'). تُعرّف هذه المعلمة عرض الهامش الذي سيُترك إجباريًا حول مناطق HTML الناتجة التي تمثل صفحات مستند PDF المصدر. في الأساس، تُحدد هذه المعلمة الفاصل المضمون بين تمثيلات HTML لصفحات PDF \"paper\" في مثل هذا الوضع من التحويل. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | تحدد هذه المعلمة إجراءات التنعيم المطلوبة أثناء تحويل الصور الخلفية المركبة من PDF إلى HTML. |
| [setBatchSize](#setBatchSize-int-) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | يضبط العلامة التي تشير إلى ما إذا كانت رسومات SVG المكتشفة (إن وجدت) سيتم ضغطها (تضغط) إلى تنسيق SVGZ أثناء الحفظ. القيمة: الـ {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | إذا تم تعيين الخاصية ConvertMarkedContentToLayers إلى true فسيتم وضع جميع العناصر داخل محتوى PDF المميز (الطبقة) في عنصر div في HTML مع الخاصية "data-pdflayer" التي تحدد اسم الطبقة. سيتم استخراج اسم الطبقة من الخصائص الاختيارية لمحتوى PDF المميز. إذا كانت هذه الخاصية false (افتراضيًا) فلن يتم إنشاء أي طبقات من محتوى PDF المميز. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | عند توليد محول PDFtoHTML ملفات CSS الناتجة، يتم إنشاء أسماء فئات CSS (مثل \".stl_01 {}\" ... \".stl_NN {}\") وتُستخدم في CSS الناتج. تسمح هذه الخاصية بتعيين بادئة اسم الفئة قسرًا. على سبيل المثال، إذا كنت تريد أن تبدأ جميع أسماء الفئات بـ 'my_prefix_' (أي أن تكون شيئًا مثل 'my_prefix_1' ... 'my_prefix_NNN')، فما عليك سوى تعيين 'my_prefix_' لهذه الخاصية قبل التحويل. إذا تُركت هذه الخاصية دون تعديل (أي أن تكون القيمة null)، فسيقوم المحول بإنشاء أسماء الفئات بنفسه (ستكون شيئًا مثل \".stl_01 {}\" ... \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء تحويل Pdf إلى Html للتعامل مع حفظ ملفات CSS المتعلقة بالمستند HTML المُنشأ ككل أو بصفحاته (إذا تم إنشاء عدة صفحات HTML). إذا رغبت في معالجة ملف CSS بطريقة معينة، يرجى إنشاء الطريقة المناسبة وتعيين المفوض (delegate) المُنشأ منها إلى هذه الخاصية. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | يمكن أن يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML. يمكنك تعيين إلى هذه الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفذ معالجة صفحة HTML واحدة (لتكون دقيقة - HTML ترميز، بدون ملفات مرتبطة خارجية إن وجدت) التي تم إنشاؤها أثناء التحويل. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل على سبيل المثال. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | يمكن أن يحتوي هذا الحقل على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء التحويل لمعالجة مخصصة للملفات المرجعية التي تم إنشاؤها (مثل الصور والخطوط) المتعلقة بعقد HTML المحفوظة). |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | يمكن أن يحتوي هذا الحقل على طريقة مخصصة تُعيد عنوان URL (أو قالب URL إذا كان توليد متعدد الصفحات مفعلاً - انظر التفاصيل أدناه) لملف CSS المستهدف كما يجب وضعه في HTML الناتج المُولد. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | يحدد اسم الخط المثبت الذي يُستخدم لاستبدال أي خط في المستند غير مضمن وغير مثبت في النظام. إذا كان القيمة null فسيتم استخدام خط الاستبدال الافتراضي. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | يضبط الـ {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | قائمة بأسماء خطوط PDF المضمنة التي لا يتم تضمينها في HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي يجب أخذ أرقام الصفحات الصالحة من النطاق (1...[NumberOfPagesInConvertedDocument]). لا يؤثر ترتيب ظهور الصفحات في هذه القائمة على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في ملف PDF الأصلي. إذا كانت هذه القائمة فارغة (null) كما هو الافتراضي، سيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (1-[amountOfPagesInDocument]) سيتم رمي استثناء. |
| [setFixedLayout](#setFixedLayout-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا الـ HTML يُنشأ كتنسيق ثابت. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | هذه الخاصية تحدد نص الفقرة بعرض كامل لوضع التدفق، FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | يحدد قاعدة ترميز خاصة لضبط فك تشفير PDF للمستند الحالي |
| [setFontSavingMode](#setFontSavingMode-int-) | يحدد وضع حفظ الخط الذي سيُستخدم أثناء حفظ PDF إلى الصيغة المطلوبة |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | أحيانًا تكون هناك متطلبات محددة لتوليد ترميز HTML. هذه المعلمة تحدد أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية هذه المتطلبات المحددة. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا |
| [setImageResolution](#setImageResolution-int-) | يحصل أو يضبط الدقة لتصيير الصورة. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | يضبط وضعية تموضع الحروف في الكلمات في HTML الناتج |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | هذه الخاصية تحدد الحد الأدنى لعرض خط المسار الرسومي. إذا كان سمك الخط أقل من 1 بكسل، فإن Adobe Acrobat يقوم بتقريبه إلى هذه القيمة. لذا يمكن استخدام هذه الخاصية لمحاكاة هذا السلوك في متصفحات HTML. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | هذه السمة تمثل مجموعة من الإعدادات المستخدمة لرسم حد (إن وجد) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | هذه الخاصية تمثل مجموعة من الهوامش الإضافية للصفحة (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | If attribute 'SplitOnPages=false'، فسيتم وضع كل HTML الذي يمثل جميع صفحات PDF المدخلة في ملف HTML نتيجة واحد كبير. تحدد هذه العلامة ما إذا كان سيتم إنشاء HTML النتيجة بهذه الطريقة بحيث يعتمد تدفق المناطق التي تمثل صفحات PDF في HTML النتيجة على دقة شاشة المشاهد. افترض أن عرض الشاشة على جانب المشاهد كبير بما يكفي لوضع صفحتين أو أكثر بجانب بعضهما في الاتجاه الأفقي. إذا تم تعيين هذه العلامة إلى true، فستُستَخدم هذه الإمكانية (سيتم عرض العديد من الصفحات في الاتجاه الأفقي بجانب بعضها قدر الإمكان، ثم ستُعرض مجموعة الصفحات الأفقية التالية تحت الأولى). وإلا فإن الصفحات ستتدفق بهذه الطريقة: الصفحة التالية تُوضع دائمًا تحت السابقة. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | تحدد ما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، ملفات CSS) سيتم تضمينها في ملف HTML الرئيسي أم سيتم إنشاؤها ككيانات ثنائية منفصلة |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | هذه السمة تُشغِّل الوضع الذي لا تُجمَّع فيه رموز النص إلى كلمات وسلاسل. يتيح هذا الوضع الحفاظ على أقصى دقة أثناء تموضع الرموز على الصفحة ويمكن استخدامه لتحويل المستندات التي تحتوي على نوتات موسيقية أو رموز يجب وضعها بشكل منفصل عن بعضها. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | يمكن أن يحتوي PDF المحول على صور نقطية. هذه المعلمة تحدد كيفية التعامل معها أثناء تحويل PDF إلى HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | يحدد ما إذا كان سيتم إزالة المنطقة الفارغة العلوية والسفلية دون أي محتوى (إن وجدت) في HTML المُنشأ. |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | إذا تم تعيين السمة RenderTextAsImage إلى true، يصبح النص من المصدر صورة في HTML. قد يكون ذلك مفيدًا لجعل النص غير قابل للتحديد أو عندما لا يتم عرض نص HTML بشكل صحيح. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | يشير إلى أنه سيتم حفظ الخط الكامل، يدعم فقط خطوط True Type. بشكل افتراضي SaveFullFont = false ويقوم المحول بحفظ مجموعة فرعية من الخط الأصلي اللازمة لعرض نص المستند. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | يمكن أن يحتوي PDF على نصوص محجوبة بواسط عناصر أخرى (مثلاً بالصور) ولكن يمكن تحديدها إلى الحافظة في Acrobat Reader (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة لتقليد سلوك Acrobat Reader (وإلا فإن هذه النصوص عادةً تُحفظ مخفية، غير متاحة للنسخ إلى الحافظة). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | يمكن أن يحتوي PDF على نصوص شفافة يمكن تحديدها إلى الحافظة (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | هذه السمة تحدد تجميعًا تسلسليًا للرموز والكلمات إلى سلاسل. على سبيل المثال، العلامات والكلمات قد يكون لها ترتيب مختلف في HTML المحول وتريد أن تتطابق. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ أي صور فيه إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات الصور (إن وجدت) مع الملفات الأخرى المرتبطة بـ HTML. لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ صور SVG فيه فقط إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات SVG (إن وجدت) مع ملفات الصور الأخرى (قرب ملف الإخراج) أو في مجلد خاص للصور (إذا تم تحديده في خيار SpecialImagesFolderIfAny). لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | عند اختيار وضع متعدد الصفحات (أي أن 'SplitIntoPages' هو 'true')، تحدد هذه السمة ما إذا يجب إنشاء ملف CSS منفصل لكل صفحة HTML نتيجة. بشكل افتراضي تكون هذه السمة false، وبالتالي يُنشأ ملف CSS كبير مشترك لجميع الصفحات المُنشأة. عادةً ما يكون الحجم الإجمالي لجميع ملفات CSS التي تُولد في هذا الوضع (CSS واحد لكل صفحة) أكبر بكثير من حجم ملف CSS واحد كبير، لأن في الحالة الأولى تتكرر فئات CSS في عدة ملفات لكل صفحة. لذلك، يُفضَّل عدم استخدام هذا الإعداد إلا عندما تكون مهتمًا بمعالجة كل صفحة HTML بشكل مستقل في المستقبل، وبالتالي يكون حجم CSS لكل صفحة منفصلة هو الأمر الأكثر حرجًا. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | يضبط العلامة التي تشير إلى ما إذا كانت كل صفحة من المستند المصدر سيتم تحويلها إلى مستند HTML هدف خاص بها، أي ما إذا كان HTML الناتج سيتقسم إلى عدة صفحات HTML. |
| [setTitle](#setTitle-java.lang.String-) | يحصل أو يضبط عنوان صفحة HTML. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | لا يحتوي PDF نفسه على علامات تسطير للنصوص. يتم محاكاة ذلك بخط موضع تحت النص. يتيح هذا الخيار للمحول محاولة تخمين أن هذا الخط أو ذاك هو تسطير النص ووضع هذه المعلومة في CSS بدلاً من رسم التسطير رسوميًا. |
| [setUseZOrder](#setUseZOrder-boolean-) | إذا تم تعيين السمة UseZORder إلى true، تُضاف الرسومات والنص إلى مستند HTML الناتج وفقًا لترتيب Z في مستند PDF الأصلي. إذا كانت هذه السمة false، تُوضع جميع الرسومات كطبقة واحدة مما قد يسبب بعض التأثيرات غير الضرورية للكائنات المتراكبة. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

ينشئ مثيلاً جديداً لفئة HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

ينشئ مثيلاً جديداً لفئة {@code HtmlSaveOptions}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fixedLayout |  | قيمة منطقية |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
ينشئ مثيلاً جديداً لفئة HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
ينشئ مثيلاً جديداً لفئة HtmlSaveOptions.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

إذا كان السمة 'SplitOnPages=false'، فإن HTML الكامل الذي يمثل جميع صفحات PDF المدخلة لن يتم تقسيمه إلى صفحات HTML مختلفة، بل سيُوضع في ملف HTML نتيجي كبير واحد. ولكن كل صفحة PDF مصدر ستُمثَّل بمنطقة مستطيلة خاصة بها في HTML (إذا لزم الأمر يمكن تأطير تلك المناطق لإظهار حواف ورق الصفحة باستخدام السمة الخاصة 'PageBorderIfAny'). تُعرّف هذه المعلمة عرض الهامش الذي سيُترك إجباريًا حول مناطق HTML الناتجة التي تمثل صفحات مستند PDF المصدر. في الأساس، تُحدد هذه المعلمة الفاصل المضمون بين تمثيلات HTML لصفحات PDF \"paper\" في مثل هذا الوضع من التحويل.

**Returns:**
قيمة int @deprecated تم إهمال AdditionalMarginWidthInPoints، يرجى استخدام PageMarginIfAny بدلاً من ذلك.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

تحدد هذه المعلمة إجراءات التنعيم المطلوبة أثناء تحويل الصور الخلفية المركبة من PDF إلى HTML.

**Returns:**
عنصر AntialiasingProcessingType @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Returns:**
قيمة int

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

عند توليد محول PDFtoHTML ملفات CSS الناتجة، يتم إنشاء أسماء فئات CSS (مثل \".stl_01 {}\" ... \".stl_NN {}\") وتُستخدم في CSS الناتج. تسمح هذه الخاصية بتعيين بادئة اسم الفئة قسرًا. على سبيل المثال، إذا كنت تريد أن تبدأ جميع أسماء الفئات بـ 'my_prefix_' (أي أن تكون شيئًا مثل 'my_prefix_1' ... 'my_prefix_NNN')، فما عليك سوى تعيين 'my_prefix_' لهذه الخاصية قبل التحويل. إذا تُركت هذه الخاصية دون تعديل (أي أن تكون القيمة null)، فسيقوم المحول بإنشاء أسماء الفئات بنفسه (ستكون شيئًا مثل \".stl_01 {}\" ... \".stl_NN {}\").

**Returns:**
قيمة سلسلة

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء تحويل Pdf إلى Html للتعامل مع حفظ ملفات CSS المتعلقة بالمستند HTML المُنشأ ككل أو بصفحاته (إذا تم إنشاء عدة صفحات HTML). إذا رغبت في معالجة ملف CSS بطريقة معينة، يرجى إنشاء الطريقة المناسبة وتعيين المفوض (delegate) المُنشأ منها إلى هذه الخاصية.

**Returns:**
مثيل CssSavingStrategy

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

يمكن أن يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML. يمكنك تعيين لهذا الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفّذ معالجة صفحة HTML واحدة (لتكون دقيقة - markup-HTML، بدون ملفات مرتبطة خارجية إذا وجدت) التي تم إنشاؤها أثناء التحويل. في مثل هذه الحالة يمكن إجراء المعالجة (مثل حفظ HTML للصفحة في تدفق أو قرص) في ذلك الكود المخصص. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يكون مستخدمًا. إذا كان يجب تنفيذ المعالجة لهذا أو ذاك الحالة لسبب ما بواسطة كود المحول نفسه، وليس في الكود المخصص، يرجى ضبط علامة 'CustomProcessingCancelled' في متغيّر 'htmlSavingInfo' الخاص بالمعامل: سيتسبب ذلك في إشارة إلى المحول بأن جميع الخطوات اللازمة لمعالجة هذا المورد يجب أن تُنفّذ في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود مخصص خارجي للمعالجة.

**Returns:**
مثيل HtmlPageMarkupSavingStrategy

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> يمكن استخدام هذا المعالج للتعامل مع أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لإظهار شريط تقدم أو رسائل حول عدد الصفحات المعالجة حاليًا، مثال على كود المعالج الذي يعرض التقدم في وحدة التحكم هو : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
مثيل ConversionProgressEventHandler

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء التحويل للتعامل المخصص مع ملفات الموارد المرجعية التي تم إنشاؤها (مثل الصور والخطوط) المرتبطة بعقد HTML المحفوظة. يجب على هذه الاستراتيجية معالجة الموارد وإرجاع سلسلة تمثل عنوان URL المرغوب للموارد المحفوظة في HTML المُولَّد.

**Returns:**
مثيل ResourceSavingStrategy

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

يمكن لهذا الحقل أن يحتوي على طريقة مخصصة تُعيد عنوان URL (أو قالب URL إذا كان توليد الصفحات المتعددة مفعَّلًا - راجع التفاصيل أدناه) لملف CSS المستهدف كما يجب وضعه في HTML الناتج المُولَّد. على سبيل المثال، إذا كنت تريد أن يضع المحول عنوان URL محدد بدلاً من اسم ملف CSS القياسي في CSS المُولَّد، فيجب عليك إنشاء وإدراج في هذا الخاصية طريقة تُولِّد عنوان URL المرغوب. إذا تم تعيين العلامة 'SplitCssIntoPages'، فيجب على هذه الاستراتيجية المخصصة (إن وجدت) أن تُعيد ليس عنوان URL دقيق للـ CSS بل قالب سلسلة يُستبدل فيه العنصر النائب برقم الصفحة باستخدام دالة String.Format() داخل المحول، بحيث يمكن تحويله إلى عنوان URL لملف CSS الخاص بهذه الصفحة أو تلك الصفحة. أمثلة على السلسلة المرجعة المتوقعة في مثل هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
مثيل CssUrlMakingStrategy

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

يحدد اسم الخط المثبت الذي يُستخدم لاستبدال أي خط في المستند غير مضمن وغير مثبت في النظام. إذا كان القيمة null فسيتم استخدام خط الاستبدال الافتراضي.

**Returns:**
قيمة String: اسم الخط

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

يحصل على {@code HtmlDocumentTypeInternal}.

**Returns:**
الـ {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

قائمة بأسماء خطوط PDF المضمنة التي لا يتم تضمينها في HTML.

**Returns:**
مصفوفة من عناصر String

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي يجب أخذ أرقام الصفحات الصالحة من النطاق (1...[NumberOfPagesInConvertedDocument]). لا يؤثر ترتيب ظهور الصفحات في هذه القائمة على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في ملف PDF الأصلي. إذا كانت هذه القائمة فارغة (null) كما هو الافتراضي، سيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (1-[amountOfPagesInDocument]) سيتم رمي استثناء.

**Returns:**
مصفوفة int

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

هذه الخاصية تحدد نص الفقرة بعرض كامل لوضع التدفق، FixedLayout = false

**Returns:**
قيمة منطقية

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

يحدد قاعدة ترميز خاصة لضبط فك تشفير PDF للمستند الحالي

**Returns:**
عنصر FontEncodingRules @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

يحدد وضع حفظ الخط الذي سيُستخدم أثناء حفظ PDF إلى الصيغة المطلوبة

**Returns:**
عنصر FontSavingModes @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> مصادر الخطوط للخطوط المحفوظة مسبقًا. </p>

**Returns:**
كائن FontSourceCollection <hr> <p> قد يتم حفظ الخطوط مبدئيًا لأغراض التخزين المؤقت ثم تمريرها إلى عملية تحويل Html. على سبيل المثال قد يكون ذلك مفيدًا في سيناريو تقسيم المستند ومعالجة صفحات المستند في عدة خيوط باستخدام مجموعة واحدة من الخطوط. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

أحيانًا تكون هناك متطلبات محددة لتوليد ترميز HTML. هذه المعلمة تحدد أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية هذه المتطلبات المحددة.

**Returns:**
عنصر HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

يحصل أو يضبط الدقة لتصيير الصورة.

**Returns:**
القيمة: الدقة

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

يضبط وضعية تموضع الحروف في الكلمات في HTML الناتج

**Returns:**
العنصر LettersPositioningMethods @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

هذه الخاصية تحدد الحد الأدنى لعرض خط المسار الرسومي. إذا كان سمك الخط أقل من 1 بكسل، فإن Adobe Acrobat يقوم بتقريبه إلى هذه القيمة. لذا يمكن استخدام هذه الخاصية لمحاكاة هذا السلوك في متصفحات HTML.

**Returns:**
قيمة عائمة

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

هذه الخاصية تمثل مجموعة من الإعدادات المستخدمة لرسم الحدود (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. في الأساس تتعلق بإظهار حواف ورق الصفحة، وليس حدود الصفحة المشار إليها في صفحة PDF نفسها.

**Returns:**
مثيل BorderInfo

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

هذه الخاصية تمثل مجموعة من الهوامش الإضافية للصفحة (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر.

**Returns:**
مثيل MarginInfo

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

تحدد ما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، ملفات CSS) سيتم تضمينها في ملف HTML الرئيسي أم سيتم إنشاؤها ككيانات ثنائية منفصلة

**Returns:**
العنصر PartsEmbeddingModes @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

يمكن أن يحتوي PDF المحول على صور نقطية. هذه المعلمة تحدد كيفية التعامل معها أثناء تحويل PDF إلى HTML

**Returns:**
العنصر RasterImagesSavingModes @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ أي صور فيه إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات الصور (إن وجدت) مع الملفات الأخرى المرتبطة بـ HTML. لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني.

**Returns:**
قيمة سلسلة

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ صور SVG فيه فقط إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات SVG (إن وجدت) مع ملفات الصور الأخرى (قرب ملف الإخراج) أو في مجلد خاص للصور (إذا تم تحديده في خيار SpecialImagesFolderIfAny). لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني.

**Returns:**
قيمة سلسلة

### getTitle {#getTitle--}
```
public final String getTitle()
```

يحصل أو يضبط عنوان صفحة HTML.

**Returns:**
قيمة سلسلة

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

يحصل على العلامة التي تشير إلى ما إذا كانت رسومات SVG المكتشفة (إن وجدت) سيتم ضغطها (مضغوطة) إلى صيغة SVGZ أثناء الحفظ. القيمة: {@code HtmlDocumentType}.

**Returns:**
قيمة منطقية

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

إذا تم تعيين الخاصية ConvertMarkedContentToLayers إلى true فسيتم وضع جميع العناصر داخل محتوى PDF المميز (الطبقة) في عنصر div في HTML مع الخاصية "data-pdflayer" التي تحدد اسم الطبقة. سيتم استخراج اسم الطبقة من الخصائص الاختيارية لمحتوى PDF المميز. إذا كانت هذه الخاصية false (افتراضيًا) فلن يتم إنشاء أي طبقات من محتوى PDF المميز.

**Returns:**
قيمة منطقية

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

يحصل على قيمة تشير إلى ما إذا كان HTML تم إنشاؤه كتنسيق ثابت.

**Returns:**
القيمة: {@code true} إذا [fixed layout]; وإلا, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا

**Returns:**
قيمة منطقية

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

If attribute 'SplitOnPages=false'، فسيتم وضع كل HTML الذي يمثل جميع صفحات PDF المدخلة في ملف HTML نتيجة واحد كبير. تحدد هذه العلامة ما إذا كان سيتم إنشاء HTML النتيجة بهذه الطريقة بحيث يعتمد تدفق المناطق التي تمثل صفحات PDF في HTML النتيجة على دقة شاشة المشاهد. افترض أن عرض الشاشة على جانب المشاهد كبير بما يكفي لوضع صفحتين أو أكثر بجانب بعضهما في الاتجاه الأفقي. إذا تم تعيين هذه العلامة إلى true، فستُستَخدم هذه الإمكانية (سيتم عرض العديد من الصفحات في الاتجاه الأفقي بجانب بعضها قدر الإمكان، ثم ستُعرض مجموعة الصفحات الأفقية التالية تحت الأولى). وإلا فإن الصفحات ستتدفق بهذه الطريقة: الصفحة التالية تُوضع دائمًا تحت السابقة.

**Returns:**
قيمة منطقية

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

هذه السمة تُشغِّل الوضع الذي لا تُجمَّع فيه رموز النص إلى كلمات وسلاسل. يتيح هذا الوضع الحفاظ على أقصى دقة أثناء تموضع الرموز على الصفحة ويمكن استخدامه لتحويل المستندات التي تحتوي على نوتات موسيقية أو رموز يجب وضعها بشكل منفصل عن بعضها. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true.

**Returns:**
قيمة منطقية

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

يحدد ما إذا كان سيتم إزالة المنطقة الفارغة العلوية والسفلية دون أي محتوى (إن وجدت) في HTML المُنشأ.

**Returns:**
قيمة منطقية

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

إذا تم تعيين السمة RenderTextAsImage إلى true، يصبح النص من المصدر صورة في HTML. قد يكون ذلك مفيدًا لجعل النص غير قابل للتحديد أو عندما لا يتم عرض نص HTML بشكل صحيح.

**Returns:**
قيمة منطقية

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

يشير إلى أنه سيتم حفظ الخط الكامل، يدعم فقط خطوط True Type. بشكل افتراضي SaveFullFont = false ويقوم المحول بحفظ مجموعة فرعية من الخط الأصلي اللازمة لعرض نص المستند.

**Returns:**
قيمة منطقية

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

يمكن أن يحتوي PDF على نصوص محجوبة بواسط عناصر أخرى (مثلاً بالصور) ولكن يمكن تحديدها إلى الحافظة في Acrobat Reader (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة لتقليد سلوك Acrobat Reader (وإلا فإن هذه النصوص عادةً تُحفظ مخفية، غير متاحة للنسخ إلى الحافظة).

**Returns:**
قيمة منطقية

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

يمكن أن يحتوي PDF على نصوص شفافة يمكن تحديدها إلى الحافظة (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة.

**Returns:**
قيمة منطقية

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

هذه السمة تحدد تجميعًا تسلسليًا للرموز والكلمات إلى سلاسل. على سبيل المثال، العلامات والكلمات قد يكون لها ترتيب مختلف في HTML المحول وتريد أن تتطابق. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true.

**Returns:**
قيمة منطقية

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

عند اختيار وضع متعدد الصفحات (أي أن 'SplitIntoPages' هو 'true')، تحدد هذه السمة ما إذا يجب إنشاء ملف CSS منفصل لكل صفحة HTML نتيجة. بشكل افتراضي تكون هذه السمة false، وبالتالي يُنشأ ملف CSS كبير مشترك لجميع الصفحات المُنشأة. عادةً ما يكون الحجم الإجمالي لجميع ملفات CSS التي تُولد في هذا الوضع (CSS واحد لكل صفحة) أكبر بكثير من حجم ملف CSS واحد كبير، لأن في الحالة الأولى تتكرر فئات CSS في عدة ملفات لكل صفحة. لذلك، يُفضَّل عدم استخدام هذا الإعداد إلا عندما تكون مهتمًا بمعالجة كل صفحة HTML بشكل مستقل في المستقبل، وبالتالي يكون حجم CSS لكل صفحة منفصلة هو الأمر الأكثر حرجًا.

**Returns:**
قيمة منطقية

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

يحصل على العلامة التي تشير إلى ما إذا كانت كل صفحة من المستند المصدر ستُحول إلى مستند HTML هدف خاص بها، أي ما إذا كان HTML النتيجة سيتقسم إلى عدة صفحات HTML.

**Returns:**
قيمة منطقية

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

لا يحتوي PDF نفسه على علامات تسطير للنصوص. يتم محاكاة ذلك بخط موضع تحت النص. يتيح هذا الخيار للمحول محاولة تخمين أن هذا الخط أو ذاك هو تسطير النص ووضع هذه المعلومة في CSS بدلاً من رسم التسطير رسوميًا.

**Returns:**
قيمة منطقية

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

إذا تم تعيين السمة UseZORder إلى true، تُضاف الرسومات والنص إلى مستند HTML الناتج وفقًا لترتيب Z في مستند PDF الأصلي. إذا كانت هذه السمة false، تُوضع جميع الرسومات كطبقة واحدة مما قد يسبب بعض التأثيرات غير الضرورية للكائنات المتراكبة.

**Returns:**
قيمة منطقية

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

إذا كان السمة 'SplitOnPages=false'، فإن HTML الكامل الذي يمثل جميع صفحات PDF المدخلة لن يتم تقسيمه إلى صفحات HTML مختلفة، بل سيُوضع في ملف HTML نتيجي كبير واحد. ولكن كل صفحة PDF مصدر ستُمثَّل بمنطقة مستطيلة خاصة بها في HTML (إذا لزم الأمر يمكن تأطير تلك المناطق لإظهار حواف ورق الصفحة باستخدام السمة الخاصة 'PageBorderIfAny'). تُعرّف هذه المعلمة عرض الهامش الذي سيُترك إجباريًا حول مناطق HTML الناتجة التي تمثل صفحات مستند PDF المصدر. في الأساس، تُحدد هذه المعلمة الفاصل المضمون بين تمثيلات HTML لصفحات PDF \"paper\" في مثل هذا الوضع من التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @deprecated تم إهمال AdditionalMarginWidthInPoints، يرجى استخدام PageMarginIfAny بدلاً من ذلك. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

تحدد هذه المعلمة إجراءات التنعيم المطلوبة أثناء تحويل الصور الخلفية المركبة من PDF إلى HTML.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| معالجة مضادة للتنعيم |  | عنصر AntialiasingProcessingType @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

يضبط العلامة التي تشير إلى ما إذا كانت رسومات SVG المكتشفة (إن وجدت) سيتم ضغطها (تضغط) إلى تنسيق SVGZ أثناء الحفظ. القيمة: الـ {@code HtmlDocumentType}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

إذا تم تعيين الخاصية ConvertMarkedContentToLayers إلى true فسيتم وضع جميع العناصر داخل محتوى PDF المميز (الطبقة) في عنصر div في HTML مع الخاصية "data-pdflayer" التي تحدد اسم الطبقة. سيتم استخراج اسم الطبقة من الخصائص الاختيارية لمحتوى PDF المميز. إذا كانت هذه الخاصية false (افتراضيًا) فلن يتم إنشاء أي طبقات من محتوى PDF المميز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
عند توليد محول PDFtoHTML ملفات CSS الناتجة، يتم إنشاء أسماء فئات CSS (مثل \".stl_01 {}\" ... \".stl_NN {}\") وتُستخدم في CSS الناتج. تسمح هذه الخاصية بتعيين بادئة اسم الفئة قسرًا. على سبيل المثال، إذا كنت تريد أن تبدأ جميع أسماء الفئات بـ 'my_prefix_' (أي أن تكون شيئًا مثل 'my_prefix_1' ... 'my_prefix_NNN')، فما عليك سوى تعيين 'my_prefix_' لهذه الخاصية قبل التحويل. إذا تُركت هذه الخاصية دون تعديل (أي أن تكون القيمة null)، فسيقوم المحول بإنشاء أسماء الفئات بنفسه (ستكون شيئًا مثل \".stl_01 {}\" ... \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء تحويل Pdf إلى Html للتعامل مع حفظ ملفات CSS المتعلقة بالمستند HTML المُنشأ ككل أو بصفحاته (إذا تم إنشاء عدة صفحات HTML). إذا رغبت في معالجة ملف CSS بطريقة معينة، يرجى إنشاء الطريقة المناسبة وتعيين المفوض (delegate) المُنشأ منها إلى هذه الخاصية.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
يمكن أن يحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات HTML. يمكنك تعيين إلى هذه الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفذ معالجة صفحة HTML واحدة (لتكون دقيقة - HTML ترميز، بدون ملفات مرتبطة خارجية إن وجدت) التي تم إنشاؤها أثناء التحويل.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل على سبيل المثال.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
يمكن أن يحتوي هذا الحقل على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء التحويل لمعالجة مخصصة للملفات المرجعية التي تم إنشاؤها (مثل الصور والخطوط) المتعلقة بعقد HTML المحفوظة).

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
يمكن أن يحتوي هذا الحقل على طريقة مخصصة تُعيد عنوان URL (أو قالب URL إذا كان توليد متعدد الصفحات مفعلاً - انظر التفاصيل أدناه) لملف CSS المستهدف كما يجب وضعه في HTML الناتج المُولد.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
يحدد اسم الخط المثبت الذي يُستخدم لاستبدال أي خط في المستند غير مضمن وغير مثبت في النظام. إذا كان القيمة null فسيتم استخدام خط الاستبدال الافتراضي.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
يضبط الـ {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
قائمة بأسماء خطوط PDF المضمنة التي لا يتم تضمينها في HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي يجب أخذ أرقام الصفحات الصالحة من النطاق (1...[NumberOfPagesInConvertedDocument]). لا يؤثر ترتيب ظهور الصفحات في هذه القائمة على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي توجد به في ملف PDF الأصلي. إذا كانت هذه القائمة فارغة (null) كما هو الافتراضي، سيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (1-[amountOfPagesInDocument]) سيتم رمي استثناء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان هذا الـ HTML يُنشأ كتنسيق ثابت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | : {@code true} إذا [fixed layout]; وإلا, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

هذه الخاصية تحدد نص الفقرة بعرض كامل لوضع التدفق، FixedLayout = false

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

يحدد قاعدة ترميز خاصة لضبط فك تشفير PDF للمستند الحالي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| استراتيجية ترميز الخط |  | عنصر FontEncodingRules @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

يحدد وضع حفظ الخط الذي سيُستخدم أثناء حفظ PDF إلى الصيغة المطلوبة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| وضع حفظ الخط |  | عنصر FontSavingModes @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

أحيانًا تكون هناك متطلبات محددة لتوليد ترميز HTML. هذه المعلمة تحدد أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية هذه المتطلبات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| وضع توليد ترميز HTML |  | عنصر HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

يحصل أو يضبط الدقة لتصيير الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | القيمة: الدقة |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
يضبط وضعية تموضع الحروف في الكلمات في HTML الناتج

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

هذه الخاصية تحدد الحد الأدنى لعرض خط المسار الرسومي. إذا كان سمك الخط أقل من 1 بكسل، فإن Adobe Acrobat يقوم بتقريبه إلى هذه القيمة. لذا يمكن استخدام هذه الخاصية لمحاكاة هذا السلوك في متصفحات HTML.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
هذه السمة تمثل مجموعة من الإعدادات المستخدمة لرسم حد (إن وجد) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
هذه الخاصية تمثل مجموعة من الهوامش الإضافية للصفحة (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

If attribute 'SplitOnPages=false'، فسيتم وضع كل HTML الذي يمثل جميع صفحات PDF المدخلة في ملف HTML نتيجة واحد كبير. تحدد هذه العلامة ما إذا كان سيتم إنشاء HTML النتيجة بهذه الطريقة بحيث يعتمد تدفق المناطق التي تمثل صفحات PDF في HTML النتيجة على دقة شاشة المشاهد. افترض أن عرض الشاشة على جانب المشاهد كبير بما يكفي لوضع صفحتين أو أكثر بجانب بعضهما في الاتجاه الأفقي. إذا تم تعيين هذه العلامة إلى true، فستُستَخدم هذه الإمكانية (سيتم عرض العديد من الصفحات في الاتجاه الأفقي بجانب بعضها قدر الإمكان، ثم ستُعرض مجموعة الصفحات الأفقية التالية تحت الأولى). وإلا فإن الصفحات ستتدفق بهذه الطريقة: الصفحة التالية تُوضع دائمًا تحت السابقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع تدفق الصفحات يعتمد على حجم شاشة المشاهد |  | قيمة منطقية |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

تحدد ما إذا كانت الملفات المشار إليها (HTML، الخطوط، الصور، ملفات CSS) سيتم تضمينها في ملف HTML الرئيسي أم سيتم إنشاؤها ككيانات ثنائية منفصلة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| وضع تضمين الأجزاء |  | العنصر PartsEmbeddingModes @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

هذه السمة تُشغِّل الوضع الذي لا تُجمَّع فيه رموز النص إلى كلمات وسلاسل. يتيح هذا الوضع الحفاظ على أقصى دقة أثناء تموضع الرموز على الصفحة ويمكن استخدامه لتحويل المستندات التي تحتوي على نوتات موسيقية أو رموز يجب وضعها بشكل منفصل عن بعضها. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

يمكن أن يحتوي PDF المحول على صور نقطية. هذه المعلمة تحدد كيفية التعامل معها أثناء تحويل PDF إلى HTML

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| وضع حفظ الصور النقطية |  | العنصر RasterImagesSavingModes @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

يحدد ما إذا كان سيتم إزالة المنطقة الفارغة العلوية والسفلية دون أي محتوى (إن وجدت) في HTML المُنشأ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| إزالة المناطق الفارغة في الأعلى والأسفل |  | قيمة منطقية |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

إذا تم تعيين السمة RenderTextAsImage إلى true، يصبح النص من المصدر صورة في HTML. قد يكون ذلك مفيدًا لجعل النص غير قابل للتحديد أو عندما لا يتم عرض نص HTML بشكل صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

يشير إلى أنه سيتم حفظ الخط الكامل، يدعم فقط خطوط True Type. بشكل افتراضي SaveFullFont = false ويقوم المحول بحفظ مجموعة فرعية من الخط الأصلي اللازمة لعرض نص المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

يمكن أن يحتوي PDF على نصوص محجوبة بواسط عناصر أخرى (مثلاً بالصور) ولكن يمكن تحديدها إلى الحافظة في Acrobat Reader (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة لتقليد سلوك Acrobat Reader (وإلا فإن هذه النصوص عادةً تُحفظ مخفية، غير متاحة للنسخ إلى الحافظة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| حفظ النصوص المظللة كنصوص شفافة |  | قيمة منطقية |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

يمكن أن يحتوي PDF على نصوص شفافة يمكن تحديدها إلى الحافظة (عادةً يحدث عندما يحتوي المستند على صور ونصوص مُستخرجة عبر OCR). هذه الإعدادات تخبر المحول ما إذا كنا بحاجة إلى حفظ هذه النصوص كنصوص شفافة قابلة للتحديد في HTML النتيجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| حفظ النصوص الشفافة |  | قيمة منطقية |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

هذه السمة تحدد تجميعًا تسلسليًا للرموز والكلمات إلى سلاسل. على سبيل المثال، العلامات والكلمات قد يكون لها ترتيب مختلف في HTML المحول وتريد أن تتطابق. سيُطبق هذا المعامل على المستند فقط عندما تكون قيمة السمة FixedLayout هي true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ أي صور فيه إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات الصور (إن وجدت) مع الملفات الأخرى المرتبطة بـ HTML. لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
يحصل أو يضبط المسار إلى الدليل الذي يجب حفظ صور SVG فيه فقط إذا تم مواجهتها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات SVG (إن وجدت) مع ملفات الصور الأخرى (قرب ملف الإخراج) أو في مجلد خاص للصور (إذا تم تحديده في خيار SpecialImagesFolderIfAny). لا يؤثر ذلك على شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

عند اختيار وضع متعدد الصفحات (أي أن 'SplitIntoPages' هو 'true')، تحدد هذه السمة ما إذا يجب إنشاء ملف CSS منفصل لكل صفحة HTML نتيجة. بشكل افتراضي تكون هذه السمة false، وبالتالي يُنشأ ملف CSS كبير مشترك لجميع الصفحات المُنشأة. عادةً ما يكون الحجم الإجمالي لجميع ملفات CSS التي تُولد في هذا الوضع (CSS واحد لكل صفحة) أكبر بكثير من حجم ملف CSS واحد كبير، لأن في الحالة الأولى تتكرر فئات CSS في عدة ملفات لكل صفحة. لذلك، يُفضَّل عدم استخدام هذا الإعداد إلا عندما تكون مهتمًا بمعالجة كل صفحة HTML بشكل مستقل في المستقبل، وبالتالي يكون حجم CSS لكل صفحة منفصلة هو الأمر الأكثر حرجًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

يضبط العلامة التي تشير إلى ما إذا كانت كل صفحة من المستند المصدر سيتم تحويلها إلى مستند HTML هدف خاص بها، أي ما إذا كان HTML الناتج سيتقسم إلى عدة صفحات HTML.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTitle {#setTitle-java.lang.String-}
يحصل أو يضبط عنوان صفحة HTML.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

لا يحتوي PDF نفسه على علامات تسطير للنصوص. يتم محاكاة ذلك بخط موضع تحت النص. يتيح هذا الخيار للمحول محاولة تخمين أن هذا الخط أو ذاك هو تسطير النص ووضع هذه المعلومة في CSS بدلاً من رسم التسطير رسوميًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| محاولة حفظ تسطير النص وشطب النص في CSS |  | قيمة منطقية |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

إذا تم تعيين السمة UseZORder إلى true، تُضاف الرسومات والنص إلى مستند HTML الناتج وفقًا لترتيب Z في مستند PDF الأصلي. إذا كانت هذه السمة false، تُوضع جميع الرسومات كطبقة واحدة مما قد يسبب بعض التأثيرات غير الضرورية للكائنات المتراكبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
