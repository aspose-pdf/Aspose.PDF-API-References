---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.HtmlSaveOptions. خيارات الحفظ للتصدير إلى تنسيق Html
type: docs
weight: 5560
url: /ar/net/aspose.pdf/htmlsaveoptions/
---
## فئة HtmlSaveOptions

خيارات الحفظ للتصدير إلى تنسيق Html

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | يقوم بتهيئة مثيل جديد من فئة `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | يقوم بتهيئة مثيل جديد من فئة `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | يقوم بتهيئة مثيل جديد من فئة `HtmlSaveOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلاً للتطبيق على زوج تنسيقات المصدر والوجهة. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كانت رموز الخطوط ستُخزن مؤقتًا أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | يحصل أو يحدد العلم الذي يشير إلى ما إذا كانت الرسوم البيانية SVG الموجودة (إن وجدت) ستُضغط (تُضغط) إلى تنسيق SVGZ أثناء الحفظ |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | إذا تم تعيين خاصية ConvertMarkedContentToLayers إلى true، فسيتم وضع جميع العناصر داخل محتوى PDF المميز (الطبقة) في div HTML مع خاصية "data-pdflayer" التي تحدد اسم الطبقة. سيتم استخراج اسم هذه الطبقة من الخصائص الاختيارية لمحتوى PDF المميز. إذا كانت هذه الخاصية false (بشكل افتراضي)، فلن يتم إنشاء أي طبقات من محتوى PDF المميز. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | يحدد اسم الخط المثبت الذي يُستخدم لاستبدال أي خط مستند غير مضمن وغير مثبت في النظام. إذا كان null، فسيتم استخدام خط الاستبدال الافتراضي. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | يحصل أو يحدد [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | مع هذه الخاصية يمكنك تحديد الصفحات التي يجب تحويلها بشكل صريح. يجب أن تحتوي الصفحات في هذه القائمة على أرقام تبدأ من 1. أي أن الأرقام الصحيحة للصفحات يجب أن تؤخذ من النطاق (1...[NumberOfPagesInConvertedDocument]) ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحة HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي تظهر به في PDF المصدر. إذا كانت هذه القائمة null (كما هو افتراضي)، فسيتم تحويل جميع الصفحات. إذا كانت أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الحالية (1-[amountOfPagesInDocument])، سيتم طرح استثناء. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه الخاصية تقوم بتفعيل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان سيتم إنشاء HTML كتنسيق ثابت. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | تحدد هذه الخاصية نص الفقرة بعرض كامل لوضع التدفق، FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | مصادر الخطوط للخطوط المحفوظة مسبقًا. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | سيتم تجاهل النص بالحجم المحدد أو أقل أثناء التحويل. نحن لا نزيل هذا النص، بل نتجاهله ولا ننقله إلى ملف الإخراج |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | يحصل أو يحدد الإشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها. true - تعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false بشكل افتراضي |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | يحصل أو يحدد دقة عرض الصورة. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | تحدد هذه الخاصية الحد الأدنى لعرض خط المسار الرسومي. إذا كان سمك الخط أقل من 1 بكسل، فإن Adobe Acrobat يقوم بتقريبه إلى هذه القيمة. لذا يمكن استخدام هذه الخاصية لمحاكاة هذا السلوك لمتصفحات HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | تقوم هذه الخاصية بتفعيل الوضع الذي لن يتم فيه تجميع رموز النص في كلمات وعبارات. يسمح هذا الوضع بالحفاظ على أقصى دقة أثناء تحديد مواقع الرموز على الصفحة ويمكن استخدامه لتحويل المستندات التي تحتوي على نوتات موسيقية أو رموز يجب وضعها بشكل منفصل عن بعضها. سيتم تطبيق هذه المعلمة على المستند فقط عندما تكون قيمة خاصية FixedLayout صحيحة. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | إذا تم تعيين خاصية RenderTextAsImage إلى true، فإن النص من المصدر يصبح صورة في HTML. قد يكون مفيدًا لجعل النص غير قابل للتحديد أو إذا لم يتم عرض نص HTML بشكل صحيح. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | تشير إلى أنه سيتم حفظ الخط بالكامل، يدعم فقط خطوط True Type. بشكل افتراضي SaveFullFont = false ويقوم المحول بحفظ مجموعة من الخط الأولي اللازمة لعرض نص المستند. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | تحدد هذه الخاصية تجميعًا متسلسلًا للرموز والكلمات في سلاسل. على سبيل المثال، تحتوي العلامات والكلمات على ترتيب مختلف في HTML المحول وتريد أن تتطابق. سيتم تطبيق هذه المعلمة على المستند فقط عندما تكون قيمة خاصية FixedLayout صحيحة. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | عند اختيار وضع الصفحات المتعددة (أي 'SplitIntoPages' هو 'true')، تحدد هذه الخاصية ما إذا كان يجب إنشاء ملف CSS منفصل لكل صفحة HTML الناتجة. بشكل افتراضي، تكون هذه الخاصية false، لذا سيتم إنشاء CSS واحد كبير مشترك لجميع الصفحات التي تم إنشاؤها. الحجم الإجمالي لجميع ملفات CSS التي تم إنشاؤها في هذا الوضع (واحد CSS لكل صفحة) عادة ما يكون أكبر بكثير من حجم ملف CSS الكبير الواحد، لأنه في الحالة السابقة تكون فئات CSS مكررة في عدة ملفات CSS لكل صفحة. لذا، يُفضل استخدام هذا الإعداد فقط عندما تكون مهتمًا بمعالجة كل صفحة HTML بشكل مستقل، وبالتالي فإن حجم CSS لكل صفحة على حدة هو القضية الأكثر أهمية. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | يحصل أو يحدد العلم الذي يشير إلى ما إذا كانت كل صفحة من المستند المصدر ستتحول إلى مستند HTML خاص بها، أي ما إذا كان سيتم تقسيم HTML الناتج إلى عدة صفحات HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | يحصل أو يحدد عنوان صفحة HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | العلم لدمج أجزاء الصور في صورة واحدة. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | إذا تم تعيين خاصية UseZOrder إلى true، تتم إضافة الرسوميات والنص إلى مستند HTML الناتج وفقًا لترتيب Z في مستند PDF الأصلي. إذا كانت هذه الخاصية false، يتم وضع جميع الرسوميات كطبقة واحدة، مما قد يتسبب في بعض التأثيرات غير المرغوب فيها للأشياء المتداخلة. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر من تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك، يمكن للمستخدم أيضًا إرجاع Abort، وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | تحدد هذه المعلمة التدابير المطلوبة لمكافحة التعرج أثناء تحويل الصور الخلفية المركبة من PDF إلى HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | عندما يقوم محول PDFtoHTML بإنشاء CSS الناتج، يتم إنشاء أسماء فئات CSS (شيء مثل ".stl_01 {}" ... ".stl_NN {}") وتستخدم في CSS الناتج. تتيح لك هذه الخاصية تعيين بادئة اسم الفئة بشكل قسري. على سبيل المثال، إذا كنت تريد أن تبدأ جميع أسماء الفئات بـ 'my_prefix_' (أي أن تكون شيئًا مثل 'my_prefix_1' ... 'my_prefix_NNN')، فما عليك سوى تعيين 'my_prefix_' لهذه الخاصية قبل التحويل. إذا تركت هذه الخاصية دون تغيير (أي تم ترك null كقيمة)، فسيقوم المحول بإنشاء أسماء الفئات بنفسه (ستكون شيئًا مثل ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | يمكن أن تحتوي هذه الخاصية على استراتيجية الحفظ التي يجب استخدامها (إذا كانت موجودة) أثناء تحويل PDF إلى HTML لمعالجة حفظ CSS المتعلقة بمستند HTML الذي تم إنشاؤه ككل أو لصفحاته (إذا تم إنشاء عدة صفحات HTML). إذا كنت تريد معالجة ملف CSS بطريقة معينة، فما عليك سوى إنشاء الطريقة ذات الصلة وتعيين المندوب الذي تم إنشاؤه منها لهذه الخاصية. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | يمكن أن تحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات. يمكنك تعيين هذه الخاصية لمندوب تم إنشاؤه من طريقة مخصصة تقوم بمعالجة صفحة HTML واحدة (لتكون دقيقة - HTML المميز، بدون ملفات مرتبطة خارجية إن وجدت) التي تم إنشاؤها أثناء التحويل. في هذه الحالة، يمكن تنفيذ المعالجة (مثل حفظ HTML للصفحة في دفق أو قرص) في هذا الرمز المخصص. في هذه الحالة، يجب اتخاذ جميع الإجراءات اللازمة لحفظ صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يكون قيد الاستخدام. إذا كانت المعالجة لهذه الحالة أو تلك لأي سبب يجب أن تتم بواسطة كود المحول نفسه، وليس في كود مخصص، يرجى تعيين في كود مخصص العلم 'CustomProcessingCancelled' لمتغير 'htmlSavingInfo': سيشير ذلك إلى المحول بأن جميع الخطوات اللازمة لمعالجة تلك المورد يجب أن تتم في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود خارجي مخصص للمعالجة. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | يمكن استخدام هذه المعالجة للتعامل مع أحداث تقدم التحويل، على سبيل المثال، يمكن استخدامها لعرض شريط تقدم أو رسائل حول الكمية الحالية من الصفحات المعالجة، مثال على كود المعالجة الذي يظهر التقدم على وحدة التحكم هو: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | يمكن أن تحتوي هذه الخاصية على استراتيجية الحفظ التي يجب استخدامها (إذا كانت موجودة) أثناء التحويل لمعالجة الموارد المرجعية التي تم إنشاؤها (مثل الصور والخطوط) المتعلقة بعقد HTML المحفوظ. يجب أن تعالج تلك الاستراتيجية الموارد وتعيد سلسلة تمثل عنوان URL المرغوب فيه للموارد المحفوظة في HTML الناتج. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | يمكن أن تحتوي هذه الخاصية على طريقة مخصصة تعيد عنوان URL (أو قالب عنوان URL إذا كان إنشاء صفحات متعددة قيد التشغيل - انظر التفاصيل أدناه) لملف CSS المعني كما يجب أن يتم وضعه في HTML الناتج. على سبيل المثال، إذا كنت تريد من المحول وضع عنوان URL محدد بدلاً من اسم ملف CSS القياسي في CSS الناتج، فما عليك سوى إنشاء ووضع هذه الخاصية في طريقة تولد عنوان URL المرغوب. إذا تم تعيين العلم 'SplitCssIntoPages'، فيجب أن تعيد هذه الاستراتيجية المخصصة (إن وجدت) ليس عنوان URL الدقيق لـ CSS ولكن بدلاً من ذلك سلسلة قالب يمكن أن تُحل إلى عنوان URL لـ CSS لهذه الصفحة أو تلك بعد استبدال العنصر النائب برقم الصفحة باستخدام دالة string.Format() داخل المحول. أمثلة على سلسلة الإرجاع المتوقعة في هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | قائمة بأسماء الخطوط المضمنة في PDF التي لن يتم تضمينها في HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | تحدد قاعدة الترميز الخاصة لضبط فك تشفير PDF للمستند الحالي |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | تحدد وضع حفظ الخط الذي سيتم استخدامه أثناء حفظ PDF إلى التنسيق المرغوب |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | أحيانًا تكون هناك متطلبات محددة لتوليد HTML المميز. تحدد هذه المعلمة أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية تلك المتطلبات المحددة. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | تعيين وضع تحديد مواقع الحروف في الكلمات في HTML الناتج |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | تمثل هذه الخاصية مجموعة من الإعدادات المستخدمة لرسم الحدود (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. في الأساس، يتعلق الأمر بعرض حواف ورقة الصفحة، وليس حدود الصفحة المشار إليها في صفحة PDF نفسها. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | تمثل هذه الخاصية مجموعة من الهوامش الإضافية للصفحة (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | إذا كانت الخاصية 'SplitOnPages=false'، فسيتم وضع HTML بالكامل الذي يمثل جميع صفحات PDF المدخلة في ملف HTML واحد كبير. تحدد هذه العلامة ما إذا كان سيتم إنشاء HTML الناتج بطريقة تعتمد على دقة شاشة المشاهد. افترض أن عرض الشاشة على جانب المشاهد كبير بما يكفي لوضع صفحتين أو أكثر بجانب بعضهما في الاتجاه الأفقي. إذا تم تعيين هذه العلامة إلى true، فسيتم استخدام هذه الفرصة (سيتم عرض أكبر عدد ممكن من الصفحات في الاتجاه الأفقي بجانب بعضها، ثم ستظهر المجموعة التالية من الصفحات تحت الأولى). خلاف ذلك، ستتدفق الصفحات بهذه الطريقة: الصفحة التالية دائمًا تحت السابقة. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | تحدد ما إذا كانت الملفات المرجعية (HTML، الخطوط، الصور، CSS) ستُدرج في ملف HTML الرئيسي أو سيتم إنشاؤها ككيانات ثنائية منفصلة |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | يمكن أن تحتوي PDF المحولة على صور نقطية. تحدد هذه المعلمة كيفية التعامل معها أثناء تحويل PDF إلى HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | تحدد ما إذا كان سيتم إزالة المناطق الفارغة العلوية والسفلية في HTML المنشأ بدون أي محتوى (إن وجدت). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | يمكن أن تحتوي PDF على نصوص مظللة بواسطة عناصر أخرى (مثل الصور) ولكن يمكن تحديدها في Acrobat Reader (عادة ما يحدث ذلك عندما يحتوي المستند على صور ونصوص تم استخراجها بواسطة OCR منه). تخبر هذه الإعدادات المحول ما إذا كنا بحاجة إلى حفظ مثل هذه النصوص كنصوص شفافة قابلة للتحديد في HTML الناتج لمحاكاة سلوك Acrobat Reader (بخلاف ذلك، يتم عادةً حفظ مثل هذه النصوص كخفية، غير متاحة للنسخ إلى الحافظة) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | يمكن أن تحتوي PDF على نصوص شفافة يمكن تحديدها في الحافظة (عادة ما يحدث ذلك عندما يحتوي المستند على صور ونصوص تم استخراجها بواسطة OCR منه). تخبر هذه الإعدادات المحول ما إذا كنا بحاجة إلى حفظ مثل هذه النصوص كنصوص شفافة قابلة للتحديد في HTML الناتج |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | يحصل أو يحدد المسار إلى الدليل الذي يجب حفظ أي صور فيه إذا تم العثور عليها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null، فسيتم حفظ ملفات الصور (إن وجدت) مع الملفات الأخرى المرتبطة بـ HTML. لا يؤثر ذلك على أي شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | يحصل أو يحدد المسار إلى الدليل الذي يجب حفظه فقط لصور SVG إذا تم العثور عليها أثناء حفظ المستند كـ HTML. إذا كانت المعلمة فارغة أو null، فسيتم حفظ ملفات SVG (إن وجدت) مع ملفات الصور الأخرى (بالقرب من ملف الإخراج) أو في مجلد خاص للصور (إذا تم تحديده في خيار SpecialImagesFolderIfAny). لا يؤثر ذلك على أي شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة المعني. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي PDF على صور خلفية (للصفحات أو خلايا الجدول) تتكون من عدة صور خلفية متطابقة موضوعة بجانب بعضها. في هذه الحالة، تقوم محولات التنسيقات المستهدفة (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مكافحة التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | لا تحتوي PDF نفسها على علامات التسطير للنصوص. يتم محاكاتها بخط يقع تحت النص. تتيح هذه الخاصية للمحول محاولة تخمين أن هذا الخط أو ذاك هو تسطير نص ووضع هذه المعلومات في CSS بدلاً من رسم التسطير بشكل رسومي |

## أمثلة

يوضح المثال التالي كيفية تحويل ملف PDF إلى ملف HTML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### انظر أيضًا

* فئة [UnifiedSaveOptions](../unifiedsaveoptions/)
* واجهة [IPageSetOptions](../ipagesetoptions/)
* واجهة [IPipelineOptions](../ipipelineoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)