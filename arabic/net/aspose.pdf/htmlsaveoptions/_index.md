---
title: "الفئة HtmlSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.HtmlSaveOptions. خيارات الحفظ لتصدير إلى تنسيق Html"
type: docs
weight: 5690
url: /ar/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق Html.

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | يُهيئ نسخة جديدة من الفئة `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | يُهيئ نسخة جديدة من الفئة `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | يُهيئ نسخة جديدة من الفئة `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | يُهيئ نسخة جديدة من الفئة `HtmlSaveOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | يحصل أو يعيّن العلامة التي تشير إلى ما إذا كانت رسومات SVG المكتشفة (إن وجدت) سيتم ضغطها (تضغط) إلى تنسيق SVGZ أثناء الحفظ. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | إذا تم تعيين السمة ConvertMarkedContentToLayers إلى true فسيتم وضع جميع العناصر داخل محتوى PDF المعلَّم (الطبقة) داخل عنصر div في HTML مع السمة "data-pdflayer" التي تحدد اسم الطبقة. سيتم استخراج اسم هذه الطبقة من الخصائص الاختيارية لمحتوى PDF المعلَّم. إذا كانت هذه السمة false (افتراضيًا) فلن يتم إنشاء أي طبقات من محتوى PDF المعلَّم. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | يحدد اسم الخط المثبت الذي يُستخدم لاستبدال أي خط مستند غير مضمّن وغير مثبت في النظام. إذا كان null فسيتم استخدام خط الاستبدال الافتراضي. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | يحصل أو يعيّن الـ [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | باستخدام هذه الخاصية يمكنك تحديد صراحةً الصفحات التي يجب تحويلها في المستند. يجب أن تكون أرقام الصفحات في هذه القائمة أرقامًا تبدأ من 1. أي أن أرقام الصفحات الصالحة يجب أن تُؤخذ من النطاق (1...[NumberOfPagesInConvertedDocument]). ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحات HTML الناتجة - في الصفحات الناتجة ستظهر دائمًا بالترتيب الذي هي موجودة به في PDF المصدر. إذا كانت هذه القائمة null (كما هو افتراضي) فسيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة خارج نطاق الصفحات الموجودة (1-[amountOfPagesInDocument]) سيتم رمي استثناء. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان HTML يُنشأ كتنسيق ثابت. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | هذه السمة تحدد نص الفقرة بعرض كامل لوضع التدفق، FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | مصادر الخطوط للخطوط المحفوظة مسبقًا. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | النص بالحجم المحدد أو أصغر سيتم تجاهله أثناء التحويل. نحن لا نزيل هذا النص، بل نتجاهله ولا ننقله إلى ملف الإخراج. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | يحصل أو يضبط إشارة إلى أن الأخطاء المتعلقة بغياب الخط سيتم تجاهلها. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false بشكل افتراضي |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | يحصل أو يضبط الدقة لتصيير الصورة. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | هذه الخاصية تحدد الحد الأدنى لعرض خط مسار الرسم. إذا كان سمك الخط أقل من 1 بكسل، يقوم Adobe Acrobat بتقريبه إلى هذه القيمة. لذا يمكن استخدام هذه الخاصية لمحاكاة هذا السلوك في متصفحات HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | هذه الخاصية تُفعّل الوضع الذي لا تُجمّع فيه رموز النص إلى كلمات وسلاسل. يسمح هذا الوضع بالحفاظ على أقصى دقة أثناء تموضع الرموز على الصفحة ويمكن استخدامه لتحويل المستندات التي تحتوي على نوتات موسيقية أو رموز يجب وضعها بشكل منفصل عن بعضها. سيتم تطبيق هذا المعامل على المستند فقط عندما تكون قيمة الخاصية FixedLayout هي true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | إذا تم تعيين الخاصية **RenderTextAsImage** إلى true، يصبح النص من المصدر صورة في HTML. قد يكون ذلك مفيدًا لجعل النص غير قابل للتحديد أو عندما لا يتم عرض نص HTML بشكل صحيح. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | يشير إلى أنه سيتم حفظ الخط الكامل، يدعم فقط خطوط True Type. بشكل افتراضي SaveFullFont = false ويقوم المحول بحفظ مجموعة فرعية من الخط الأصلي اللازمة لعرض نص المستند. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | هذه الخاصية تحدد تجميعًا تسلسليًا للرموز والكلمات في سلاسل. على سبيل المثال، تكون العلامات والكلمات بترتيب مختلف في HTML المحول وتريد أن تتطابق. سيتم تطبيق هذا المعامل على المستند فقط عندما تكون قيمة الخاصية FixedLayout هي true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | عند اختيار وضع متعدد الصفحات (أي أن **SplitIntoPages** هو true)، تحدد هذه الخاصية ما إذا كان يجب إنشاء ملف CSS منفصل لكل صفحة HTML ناتجة. بشكل افتراضي هذه الخاصية false، لذا يتم إنشاء ملف CSS كبير مشترك لجميع الصفحات التي تم إنشاؤها. الحجم الإجمالي لجميع ملفات CSS التي تُولد في هذا الوضع (CSS واحد لكل صفحة) عادةً ما يكون أكبر بكثير من حجم ملف CSS واحد كبير، لأن في الحالة الأولى تتكرر فئات CSS في عدة ملفات لكل صفحة. لذلك، يُفضَّل عدم استخدام هذا الإعداد إلا عندما تكون مهتمًا بمعالجة كل صفحة HTML على حدة في المستقبل، وبالتالي يكون حجم CSS لكل صفحة منفصلة هو الأمر الأكثر حرجًا. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | يحصل أو يضبط العلامة التي تشير إلى ما إذا كانت كل صفحة من المستند المصدر ستحول إلى مستند HTML هدف خاص بها، أي ما إذا كان HTML الناتج سيتجزأ إلى عدة صفحات HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | يحصل أو يضبط عنوان صفحة HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | العلم لتجميع قطع الصورة في صورة واحدة. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | إذا تم تعيين الخاصية **UseZORder** إلى true، تُضاف الرسومات والنص إلى مستند HTML الناتج وفقًا لترتيب Z في مستند PDF الأصلي. إذا كانت هذه الخاصية false، تُوضع جميع الرسومات كطبقة واحدة مما قد يسبب بعض التأثيرات غير الضرورية للكائنات المتداخلة. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | هذا المعامل يحدد إجراءات مضادة للتعرج المطلوبة أثناء تحويل صور الخلفية المركبة من PDF إلى HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | عند توليد محول PDFtoHTML ملفات CSS نتيجة، يتم إنشاء أسماء فئات CSS (مثل \".stl_01 {}\" ... \".stl_NN {}\") واستخدامها في CSS الناتج. تسمح هذه الخاصية بتعيين بادئة اسم الفئة إجباريًا. على سبيل المثال، إذا أردت أن تبدأ جميع أسماء الفئات بـ 'my_prefix_' (أي تكون مثل 'my_prefix_1' ... 'my_prefix_NNN')، فقط عيّن 'my_prefix_' لهذه الخاصية قبل التحويل. إذا تُركت هذه الخاصية دون تعديل (أي null سيُترك كقيمة)، سيولد المحول أسماء الفئات بنفسه (ستكون مثل \".stl_01 {}\" ... \".stl_NN {}\"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | يمكن أن يحتوي هذا الحقل على استراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء تحويل Pdf إلى Html للتعامل مع حفظ ملفات CSS المتعلقة بالمستند HTML ككل أو لصفحاته (إذا تم إنشاء عدة صفحات HTML). إذا أردت معالجة ملف CSS بطريقة معينة، فقط أنشئ الطريقة المناسبة وعين التفويض المُنشأ منها إلى هذه الخاصية. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | نتيجة التحويل يمكن أن تحتوي على صفحة HTML واحدة أو عدة صفحات HTML. يمكنك تعيين لهذا الخاصية مفوضًا تم إنشاؤه من طريقة مخصصة تنفّذ معالجة صفحة HTML واحدة (بدقة - HTML للترميز، بدون ملفات مرتبطة خارجية إذا وجدت) التي تم إنشاؤها أثناء التحويل. في هذه الحالة يمكن تنفيذ المعالجة (مثل حفظ HTML للصفحة في تدفق أو على القرص) في ذلك الكود المخصص. في هذه الحالة يجب تنفيذ جميع الإجراءات اللازمة لحفظ صفحة HTML في كود الطريقة المقدمة، لأن حفظ النتيجة في كود المحول لن يكون مستخدمًا. إذا كان يجب تنفيذ المعالجة لهذه الحالة أو تلك الحالة لسبب ما بواسطة كود المحول نفسه، وليس في الكود المخصص، يرجى ضبط في الكود المخصص علامة 'CustomProcessingCancelled' للمتغيّر 'htmlSavingInfo' الخاص بالمعامل: سيتّبع ذلك إشارة إلى المحول بأن جميع الخطوات اللازمة لمعالجة هذا المورد يجب أن تُنفّذ في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي كود مخصص خارجي للمعالجة. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | يمكن استخدام هذا المعالج لمعالجة أحداث تقدم التحويل، على سبيل المثال يمكن استخدامه لعرض شريط تقدم أو رسائل حول عدد الصفحات المعالجة حاليًا، مثال على كود المعالج الذي يعرض التقدم في وحدة التحكم هو: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | يمكن لهذا الحقل أن يحتوي على استراتيجية حفظ يجب استخدامها (إن وجدت) أثناء التحويل للتعامل المخصص مع ملفات الموارد المشار إليها التي تم إنشاؤها (مثل الصور والخطوط) المرتبطة بعقد HTML المحفوظة. يجب على تلك الاستراتيجية معالجة الموارد وإرجاع سلسلة تمثل عنوان URL المرغوب للموارد المحفوظة في HTML المُولَّد. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | يمكن لهذا الحقل أن يحتوي على طريقة مخصصة تُعيد عنوان URL (أو قالب URL إذا كان توليد متعدد الصفحات مفعَّلًا - راجع التفاصيل أدناه) لملف CSS المستهدف كما يجب وضعه في HTML الناتج المُولَّد. على سبيل المثال، إذا كنت تريد أن يضع المحول عنوان URL محدد بدلاً من اسم ملف CSS القياسي في CSS المُولَّد، فيجب عليك إنشاء ووضع في هذا الخاصية طريقة تُولِّد عنوان URL المرغوب. إذا تم تعيين العلامة 'SplitCssIntoPages'، يجب على هذه الاستراتيجية المخصصة (إن وجدت) أن تُعيد ليس عنوان URL دقيق للـ CSS بل قالب سلسلة يُستبدل فيه العنصر النائب برقم الصفحة باستخدام دالة string.Format() داخل المحول، بحيث يمكن تحويله إلى عنوان URL لملف CSS الخاص بهذه الصفحة أو تلك الصفحة. أمثلة على سلسلة الإرجاع المتوقعة في هذه الحالة هي: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | قائمة بأسماء الخطوط المدمجة في PDF التي لا يجب تضمينها في HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | يحدد قاعدة ترميز خاصة لضبط فك ترميز PDF للمستند الحالي |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | يحدد وضع حفظ الخط الذي سيُستخدم أثناء حفظ PDF إلى الصيغة المطلوبة |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | أحيانًا تكون هناك متطلبات محددة لتوليد ترميز HTML. يحدد هذا المعامل أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لتلبية هذه المتطلبات المحددة. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | يضبط وضعية تموضع الحروف في الكلمات في HTML الناتج |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | هذه السمة تمثل مجموعة من الإعدادات المستخدمة لرسم الحدود (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF الأصلية. في جوهرها تتعلق بعرض حواف ورق الصفحة، وليس حدود الصفحة المشار إليها في صفحة PDF نفسها. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | هذه السمة تمثل مجموعة من الهوامش الإضافية للصفحة (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF الأصلية. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | إذا كان السمة 'SplitOnPages=false'، فسيتم وضع كامل HTML الذي يمثل جميع صفحات PDF المدخلة في ملف HTML ناتج واحد كبير. تحدد هذه العلامة ما إذا كان سيتم توليد HTML الناتج بطريقة تجعل تدفق المناطق التي تمثل صفحات PDF في HTML الناتج يعتمد على دقة شاشة المشاهد. افترض أن عرض الشاشة لدى المشاهد كبير بما يكفي لوضع صفحتين أو أكثر بجوار بعضهما في الاتجاه الأفقي. إذا تم تعيين هذه العلامة إلى true، فستُستغل هذه الإمكانية (حيث تُعرض عدة صفحات في الاتجاه الأفقي بجوار بعضها قدر الإمكان، ثم تُعرض المجموعة الأفقية التالية تحت الأولى). وإلا فإن الصفحات ستتدفق بهذه الطريقة: الصفحة التالية تُوضع دائمًا تحت السابقة. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically |

## أمثلة

The following example shows how to convert PDF file to HTML file

```csharp
[C#]
	// المسار إلى دليل المستندات.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions \t
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


