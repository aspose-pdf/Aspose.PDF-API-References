---
title: HtmlSaveOptions
second_title: Aspose.PDF لمرجع .NET API
description: حفظ الخيارات للتصدير إلى تنسيق Html
type: docs
weight: 3430
url: /ar/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

حفظ الخيارات للتصدير إلى تنسيق Html

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions#constructor)() | يقوم بتهيئة مثيل جديد لملف[`HtmlSaveOptions`](../htmlsaveoptions) فئة . |
| [HtmlSaveOptions](htmlsaveoptions#constructor_3)(bool) | يقوم بتهيئة مثيل جديد لملف[`HtmlSaveOptions`](../htmlsaveoptions) فئة . |
| [HtmlSaveOptions](htmlsaveoptions#constructor_1)(HtmlDocumentType) | يقوم بتهيئة مثيل جديد لملف[`HtmlSaveOptions`](../htmlsaveoptions) فئة . |
| [HtmlSaveOptions](htmlsaveoptions#constructor_2)(HtmlDocumentType, bool) | يقوم بتهيئة مثيل جديد لملف[`HtmlSaveOptions`](../htmlsaveoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize) { get; set; } | يحدد حجم الدُفعة إذا كان التحويل المجمّع قابلاً للتطبيق زوج تنسيقات المصدر والوجهة . |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى أنه سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany) { get; set; } | الحصول على أو تعيين العلامة التي تشير إلى ما إذا كان سيتم ضغط رسومات SVG التي تم العثور عليها (إن وجدت) (مضغوط) في تنسيق SVGZ أثناء save |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers) { get; set; } | إذا تم تعيين السمة ConvertMarkedContentToLayers على true ، فسيتم وضع جميع العناصر داخل PDF بعلامة محتوى (طبقة) في HTML div مع تحديد سمة "data-pdflayer" اسم الطبقة. سيتم استخراج اسم الطبقة هذا من الخصائص الاختيارية لملف PDF محتوى مميز . إذا كانت هذه السمة خاطئة (افتراضيًا) فلن يتم إنشاء أي طبقات من المحتوى المميز بعلامة PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname) { get; set; } | يحدد اسم الخط المثبت والذي يتم استخدامه لاستبدال خط أي مستند غير مضمن وغير مثبت في النظام. إذا كان فارغًا ، فسيتم استخدام خط الاستبدال الافتراضي. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype) { get; set; } | يحصل أو يحدد ملف[`HtmlDocumentType`](../htmldocumenttype) . |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages) { get; set; } | باستخدام هذه الخاصية يمكنك تحديد بوضوح صفحات المستند التي يجب تحويلها . يجب أن تحتوي الصفحات في هذه القائمة على أرقام تستند إلى 1. أي يجب أخذ أرقام الصفحات الصالحة من النطاق (1 ... [NumberOfPagesInConvertedDocument]) ترتيب ظهور الصفحات في هذه القائمة لا يؤثر على ترتيبها في صفحة (صفحات) HTML الناتجة - في صفحات النتائج ستذهب دائمًا بالترتيب التي تكون فيها موجودة في ملف PDF المصدر. إذا كانت هذه القائمة فارغة (كما هي افتراضيًا) ، فسيتم تحويل جميع الصفحات. إذا كان أي رقم صفحة في هذه القائمة سيخرج عن نطاق الصفحات الحالية (1- [ سيتم طرح استثناء amountOfPagesInDocument]) . |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | هذا السمة شغّل وظيفة استخراج صورة أو نص لمستندات PDF ذات الطبقة الفرعية OCR . |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان قد تم إنشاء HTML كتخطيط ثابت. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth) { get; set; } | تحدد هذه السمة نص فقرة بالعرض الكامل لوضع التدفق ، FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources) { get; } | مصادر الخطوط للخطوط المحفوظة مسبقًا. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution) { get; set; } | الحصول على دقة عرض الصورة أو تعيينها . |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth) { get; set; } | تحدد هذه السمة الحد الأدنى لعرض خط مسار الرسم . إذا كانت سماكة الخط أقل من 1 بكسل ، فإن Adobe Acrobat يقربها إلى هذه القيمة. لذلك يمكن استخدام هذه السمة لمحاكاة هذا السلوك لمتصفحات HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping) { get; set; } | تعمل هذه السمة على تشغيل الوضع عندما لا يتم تجميع الحروف الرسومية النصية في كلمات وسلاسل يسمح هذا الوضع بالحفاظ على أقصى درجات الدقة أثناء وضع الحروف الرسومية على الصفحة ويمكن استخدام في تحويل المستندات مع الملاحظات الموسيقية أو الصور الرمزية التي يجب وضعها بشكل منفصل بعضها البعض. سيتم تطبيق هذه المعلمة على المستند فقط عندما تكون قيمة السمة FixedLayout صحيحة. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage) { get; set; } | إذا تم تعيين السمة RenderTextAsImage على true ، فإن النص من المصدر يصبح صورة بتنسيق HTML. قد يكون مفيدًا لجعل النص غير قابل للتحديد أو لا يتم تقديم نص HTML بشكل صحيح. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | تنسيق حفظ البيانات . |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping) { get; set; } | تحدد هذه السمة تجميعًا متسلسلًا للحروف الرسومية والكلمات في سلاسل على سبيل المثال العلامات والكلمات لها ترتيب مختلف في HTML المحول وتريد مطابقتها . سيتم تطبيق هذه المعلمة على المستند فقط عندما تكون قيمة السمة FixedLayout صحيحة. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages) { get; set; } | عند تحديد وضع متعدد الصفحات (مثل "SplitIntoPages" هو "صحيح") ، فإن هذه السمة تحدد ما إذا كان يجب إنشاء CSS-file منفصل لكل صفحة HTML نتيجة. CSS مشترك كبير لجميع الصفحات التي تم إنشاؤها. حجم ملخص all CSSes التي تم إنشاؤها في هذا الوضع (CSS واحد لكل صفحة) عادة أكبر بكثير من حجم ملف CSS كبير واحد ، لأنه في الحالة السابقة فئات CSS مكررة في مثل هذه الحالة في عدة ملفات CSS لكل صفحة. من الأسوأ استخدام الإعداد فقط عندما تكون مهتمًا في المعالجة المستقبلية لكل صفحة HTML بشكل مستقل ، وبالتالي فإن حجم من CSS لكل صفحة يتم فصلها هو المشكلة الأكثر أهمية. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages) { get; set; } | الحصول على أو تعيين العلامة التي تشير إلى ما إذا كان سيتم تحويل كل صفحة من مستند المصدر إلى مستند HTML مستهدف خاص بها ، أي ما إذا كان سيتم تقسيم HTML الناتج إلى عدة صفحات HTML. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder) { get; set; } | إذا تم تعيين السمة UseZORder على صحيح ، فستتم إضافة الرسومات والنص إلى مستند HTML الناتج عن المستند وفقًا لذلك ترتيب Z في مستند PDF الأصلي. إذا كانت هذه السمة خاطئة ، يتم وضع جميع الرسومات على أنها طبقة واحدة مما قد يتسبب في بعض التأثيرات غير الضرورية للكائنات المتداخلة. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | رد الاتصال للتعامل مع أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر التعداد ReturnAction الذي يحدد إما متابعة أو إحباط. متابعة هو الإجراء الافتراضي وتستمر عملية "حفظ" ، ومع ذلك قد يقوم المستخدم أيضًا بإرجاع "إحباط" وفي هذه الحالة يجب أن تتوقف عملية "حفظ". |

## مجالات

| اسم | وصف |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing) | تحدد هذه المعلمة إجراءات منع التشويش المطلوبة أثناء تحويل صور الخلفية المركبة من PDF إلى HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix) | عند قيام محول PDFtoHTML بإنشاء CSSs نتيجة ، يتم إنشاء أسماء فئة CSS (شيء مثل ".stl_01 {}" ... ".stl_NN {} ) واستخدامها في CSS الناتجة. تسمح هذه الخاصية بتعيين بادئة اسم الفئة بالقوة على سبيل المثال ، إذا كنت تريد أن تبدأ جميع أسماء الفئات بـ "my_prefix _' (أي كانت شيئًا مثل" my_prefix_1 "..." my_prefix_NNN ") ، ثم قم بتعيين" my_prefix_ "لهذه الخاصية قبل التحويل. سيتم تركها كقيمة) ، ثم سيقوم المحول بإنشاء أسماء فئة بنفسه (سيكون شيئًا مثل ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy) | يمكن أن يحتوي هذا الحقل على إستراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء التحويل من Pdf إلى Html للتعامل مع حفظ CSSes related لإنشاء مستند HTML بالكامل أو إلى صفحاته (إذا تم إنشاء العديد من صفحات HTML) إذا كنت تريد التعامل مع ملف CSS بطريقة معينة ، وهذا ما عليك سوى إنشاء طريقة ذات صلة و تعيين المفوض الذي تم إنشاؤه منه إلى هذه الخاصية. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy) | يمكن أن تحتوي نتيجة التحويل على صفحة HTML واحدة أو عدة صفحات يمكنك تعيين مفوض الخاصية هذا الذي تم إنشاؤه من طريقة مخصصة تنفذ معالجة لصفحة HTML واحدة (بدقة - ترميز HTML ، بدون ملفات مرتبطة خارجية إن وجدت) ذلك تم إنشاؤه أثناء التحويل . في مثل هذه الحالة ، يمكن إجراء المعالجة (مثل حفظ HTML للصفحة في الدفق أو القرص) في هذا الرمز المخصص. في مثل هذه الحالة ، يجب تنفيذ جميع الإجراءات اللازمة لحفظ صفحة HTML في رمز الطريقة المزودة ، لأن حفظ النتيجة في رمز المحول لن يكون قيد الاستخدام. إذا كانت المعالجة لهذه الحالة أو تلك لسبب ما يجب أن تتم عن طريق رمز المحول نفسه ، ليس في رمز مخصص ، فالرجاء تعيين علامة الرمز المخصص "CustomProcessingCancelled " من متغير معلمة" htmlSavingInfo ": سيشير إلى المحول أن جميع يجب أن تتم الخطوات اللازمة لمعالجة هذا المورد في المحول نفسه بنفس الطريقة كما لو لم يكن هناك أي رمز مخصص خارجي للمعالجة . |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler) | يمكن استخدام هذا المعالج لمعالجة تقدم التحويل events fe يمكن استخدامه لإظهار شريط التقدم أو الرسائل حول المقدار الحالي للصفحات المعالجة ، مثال على كود المعالج الذي يظهر التقدم على وحدة التحكم هو: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy) | يمكن أن يحتوي هذا الحقل على إستراتيجية الحفظ التي يجب استخدامها (إن وجدت) أثناء التحويل من أجل المعالجة المخصصة لملفات المورد المرجعية التي تم إنشاؤها (مثل الصور والخطوط) المتعلقة بعقد HTML المحفوظة. يمثل عنوان URL المرغوب فيه للمورد المحفوظ في HTML الذي تم إنشاؤه . |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation) | يمكن أن يحتوي هذا الحقل على طريقة مخصصة تقوم بإرجاع URL (أو قالب عنوان URL في حالة تشغيل إنشاء صفحات متعددة - انظر التفاصيل أدناه) للموضوع CSS حيث يجب وضعها في HTML الناتج الناتج. اسم ملف CSS في CSS الذي تم إنشاؤه ، إذًا يجب عليك فقط إنشاء وإدخال هذه الخاصية method التي تنشئ عنوان URL مرغوبًا . إذا تم تعيين علامة "SplitCssIntoPages" ، فإن هذه الإستراتيجية المخصصة (إن وجدت) يجب أن لا ترجع عنوان URL الدقيق لـ CSS ولكن بدلاً من القالب السلسلة that (بعد استبدال العنصر النائب برقم الصفحة بالسلسلة. يمكن حل التنسيق () دالة داخل المحول) في عنوان URL لعنوان URL الخاص بهذه الصفحة أو تلك الخاصة بـ CSS. أمثلة لسلسلة الإرجاع المتوقعة في مثل هذه الحالة: 'SomeTargetLocation-page_ {0} .css'، '.. / PartHandlers / GetCss.aspx؟ DocumentId = 45654 &amp; CssPage = {0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist) | قائمة بأسماء خطوط PDF المضمنة التي لا يتم تضمينها في HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy) | يحدد قاعدة خاصة للتشفير لضبط فك تشفير PDF للمستند الحالي |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode) | يحدد وضع حفظ الخط الذي سيتم استخدامه أثناء حفظ PDF بالتنسيق المرغوب |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode) | في بعض الأحيان توجد متطلبات محددة لإنشاء ترميز HTML . تحدد هذه المعلمة أوضاع إعداد HTML التي يمكن استخدامها أثناء تحويل PDF إلى HTML لمطابقة مثل هذه المتطلبات المحددة. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod) | يضبط وضع وضع الأحرف في الكلمات في النتيجة HTML |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany) | تمثل هذه السمة مجموعة من الإعدادات المستخدمة لرسم الحدود (إن وجدت) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر . في جوهرها يتعلق الأمر بإظهار حواف الورق للصفحة ، وليس حدود الصفحة المشار إليها في صفحة PDF نفسها. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany) | تمثل هذه السمة مجموعة من الهامش الإضافي للصفحة (إن وجد) في مستند HTML الناتج حول المنطقة التي تمثل صفحة PDF المصدر. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize) | إذا كانت السمة "SplitOnPages = false" ، فسيتم وضع في ملف HTML ذي النتيجة الكبيرة واحد من HTML بالكامل الذي يمثل جميع صفحات PDF المدخلة. تحدد هذه العلامة ما إذا كان سيتم إنشاء نتيجة HTML بهذه الطريقة سيعتمد تدفق المناطق التي تمثل صفحات PDF في النتيجة HTML على دقة شاشة العارض. لنفترض أن عرض الشاشة على جانب العارض كبير بما يكفي لوضع صفحتين أو أكثر واحدة بالقرب من أخرى في الاتجاه الأفقي. إذا تم تعيين هذه العلامة على "true" ، فسيتم استخدام هذه الفرصة (سيتم عرض العديد من الصفحات في اتجاه أفقي واحدة بالقرب من الأخرى قدر الإمكان ، ثم سيتم عرض المجموعة الأفقية التالية من الصفحات تحت الأولى) . وإلا فسوف تتدفق الصفحات في على هذا النحو: الصفحة التالية تذهب دائمًا أسفل الصفحة السابقة . |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode) | تحدد ما إذا كانت الملفات المرجعية (HTML ، الخطوط ، الصور ، CSSes) سيتم تضمينها في ملف HTML الرئيسي أو سيتم إنشاؤها ككيانات ثنائية منفصلة |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode) | يمكن أن تحتوي ملفات PDF المحولة على صور نقطية تحدد هذه المعلمة كيفية التعامل معها أثناء تحويل PDF إلى HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom) | يحدد ما إذا كان سيتم إزالة المنطقة الفارغة العلوية والسفلية بدون أي محتوى (إن وجد) بتنسيق HTML الذي تم إنشاؤه . |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont) | يشير إلى أنه سيتم حفظ الخط بالكامل ، ويدعم خطوط True Type فقط. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts) | يمكن أن يحتوي ملف PDF على نصوص مظللة بعناصر أخرى (fe بالصور) ولكن يمكن تحديد للحافظة في Acrobat Reader (يحدث عادةً عندما يحتوي المستند على صور ونصوص OCR مستخرجة منه). تحتاج إلى حفظ نصوص مثل transparent نصوص قابلة للتحديد في نتيجة HTML لتقليد سلوك Acrobat Reader (على سبيل المثال ، عادةً ما يتم حفظ هذه النصوص على أنها مخفية ، غير متاحة للنسخ إلى الحافظة) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts) | يمكن أن يحتوي ملف PDF على نصوص شفافة يمكن تحديدها في الحافظة (عادةً ما يحدث ذلك عندما يحتوي المستند على صور ونصوص OCR مستخرجة منه). |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages) | الحصول على أو تعيين المسار إلى الدليل الذي يجب حفظ أي صور فيه إذا تمت مصادفتها أثناء حفظ المستند بتنسيق HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات الصور (إن وجدت) مع الملفات الأخرى المرتبطة بـ HTML ولا يؤثر على أي شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة ذي الصلة. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages) | الحصول على أو تحديد المسار إلى الدليل الذي يجب حفظ صور SVG إليه فقط إذا تمت مصادفتهم أثناء حفظ المستند بتنسيق HTML. إذا كانت المعلمة فارغة أو null فسيتم حفظ ملفات SVG (إن وجدت) مع ملفات الصور الأخرى (بالقرب من ملف الإخراج) أو في مجلد خاص للصور (إذا كانت محددة في خيار SpecialImagesFolderIfAny) . لا تؤثر على أي شيء إذا تم استخدام خاصية CustomImageSavingStrategy بنجاح لمعالجة ملف الصورة ذي الصلة. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | في بعض الأحيان تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول) تم إنشاؤها من عدة صور خلفية متشابهة ، ضع واحدة بالقرب من الأخرى. في مثل هذه الحالة ، تنشئ عارضات التنسيقات المستهدفة (fe MsWord لتنسيق DOCS) أحيانًا حدودًا مرئية بين أجزاء من صور الخلفية ، لأن تقنيات تجانس حافة الصورة (الصقل) تختلف عن Acrobat Reader . إذا بدا أن المستند المُصدَّر يحتوي على حدود مرئية بين أجزاء من نفس صور الخلفية ، يرجى محاولة استخدام هذا الإعداد للتخلص من من ذلك تأثير غير مرغوب فيه. انتبه! عادةً ما يؤدي هذا التحسين للجودة إلى إبطاء عملية التحويل ، لذا ، من فضلك ، استخدم هذا الخيار فقط عندما يكون ضروريًا حقًا. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss) | لا يحتوي ملف PDF نفسه على علامات تسطير للنصوص. تمت محاكاته مع سطر يقع أسفل النص. هذا الخيار يسمح للمحول بتجربة تخمين أن هذا السطر أو ذاك هو تسطير النص ووضع هذه المعلومات في CSS بدلاً من الرسم للتسطير بيانياً |

### أنظر أيضا

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPageSetOptions](../ipagesetoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
