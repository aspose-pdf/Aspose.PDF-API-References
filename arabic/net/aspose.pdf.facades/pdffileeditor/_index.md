---
title: "الفئة PdfFileEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfFileEditor. تنفّذ عمليات دمج ملفات PDF وتقسيمها واستخراج الصفحات وإنشاء كتيب وغيرها."
type: docs
weight: 4580
url: /ar/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

ينفذ عمليات مع ملف PDF: الجمع، التقسيم، استخراج الصفحات، إنشاء كتيب، إلخ.

```csharp
public sealed class PdfFileEditor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | إذا تم تعيينه إلى true، تُغلق التدفقات بعد العملية. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | عدد Document المدمجة قبل إجراء تحديث تدريجي جديد أثناء الدمج عندما يتم تعيين UseDiskBuffer إلى true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | يحصل على سجل عملية التحويل. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بتنسيق PDF الافتراضي دون تحويل. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | إذا كان صحيحًا فسيتم نسخ الهيكل المنطقي للملف عند إجراء الدمج. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | إذا كان صحيحًا فسيتم نسخ الخطوط العريضة. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | تحدد هذه الخاصية السلوك عند مواجهة ملف تالف أثناء عملية الدمج. القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | مصفوفة بالمشكلات التي تم مواجهتها عند تنفيذ الدمج. لكل مستند تالف تم تمريره إلى دالة Concatenate() يتم إنشاء إدخال CorruptedItem جديد. يمكن استخدام هذه الخاصية فقط عندما تكون قيمة CorruptedFileAction هي ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | إذا كان صحيحًا، يتم إجراء تحديثات متدرجة أثناء الدمج. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | إذا كان صحيحًا فسيتم نسخ الإجراءات من المستندات المصدر. القيمة الافتراضية: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | إذا كان صحيحًا فستصبح أسماء الحقول فريدة عند دمج النماذج. ستُضاف لاحقات إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في الخاصية UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | يحصل على آخر استثناء حدث. يمكن استخدامه للتحقق من سبب الفشل. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية صحيحة. وإلا، سيتم حفظ الطبقات ذات الأسماء المتساوية كطبقات مختلفة في المستند الناتج. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | إذا كان صحيحًا، يتم دمج المخططات المكررة. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | يحصل أو يعيّن علامة التحسين. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. يسمح ذلك بتقليل حجم الملف الناتج لكنه قد يسبب تنفيذًا أبطأ ومتطلبات ذاكرة أكبر. القيمة الافتراضية: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | يضبط كلمة مرور المالك إذا كان ملف PDF المصدر مشفرًا. هذه الخاصية لم تُنفَّذ بعد. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | إذا كان صحيحًا، تُطبق حقوق المستخدم للمستند الأول على المستند المدمج. تُهمل حقوق المستخدم لجميع المستندات الأخرى. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | إذا كان صحيحًا، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول موجودة)؛ وإلا، قد تحصل على توقيعات غير صالحة. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. يجب أن يحتوي هذا النص على الجزء %NUM% الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1، fieldNameABC2، fieldNameABC3، إلخ. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | إذا تم استخدام هذا الخيار، سيتم حفظ المستند الوجهة على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متدرجة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بوحدات المسافة الافتراضية. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بوحدات المسافة الافتراضية. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بالنسبة المئوية لحجم الصفحة الأولي. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | يعيد تحجيم محتويات الصفحة ويضيف هوامش محددة. تُحدد الهوامش بالنسبة المئوية لحجم الصفحة الأولي. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | يضيف فواصل صفحات إلى صفحات المستند. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | يضيف فواصل صفحات إلى صفحات المستند. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | يضيف فواصل صفحات إلى صفحات المستند. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | يضيف الصفحات المختارة من portStream ضمن النطاق من startPage إلى endPage، في portStream في نهاية firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | يضيف الصفحات المختارة من مصفوفة المستندات في portStreams. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portStreams في النطاق من startPage إلى endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | يضيف الصفحات المختارة من portFile ضمن النطاق من startPage إلى endPage، في portFile في نهاية firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | يضيف الصفحات المختارة من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles في النطاق من startPage إلى endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | يدمج المستندات. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | يدمج الملفات. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | يقوم بدمج الملفات في ملف واحد. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | يقوم بدمج ملفين. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | يقوم بدمج ملفين. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | يستخرج الصفحات من ملف الإدخال، يحفظها كملف Pdf جديد. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | يستخرج الصفحات من ملف الإدخال، يحفظها كملف Pdf جديد. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | يدرج الصفحات من ملف آخر إلى ملف Pdf في موضع معين. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | ينشئ كتيبًا من InputStream إلى outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | ينشئ كتيبًا من inputFile إلى outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | ينشئ كتيبًا من firstInputStream إلى outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | ينشئ مستند N-Up من تدفقَي PDF الإدخال إلى outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال ذات رقم الصفحة نفسه. يتم ترتيب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | ينشئ مستند N-Up من ملفي PDF الإدخال إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، إحداهما من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. تُرتب الصفحتان أفقياً. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال ذات رقم الصفحة نفسه. تُرتب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | ينشئ مستند N-Up من firstInputFile إلى outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | ينشئ مستند N-Up من ملف الإدخال إلى outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | يعيد تحجيم صفحات المستند. تُضاف هوامش فارغة حول الصفحة المصغرة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | يعيد تحجيم صفحات المستند. تُضاف هوامش فارغة حول الصفحة المصغرة. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | يعيد تحجيم محتويات صفحات المستند. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | يعيد تحجيم محتويات الصفحات في المستند. إذا تم تقليص الصفحة تُضاف هوامش فارغة حولها. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد حجم المحتويات الجديد بالنسبة المئوية. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد حجم المحتويات الجديد بالنسبة المئوية. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | يقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | يقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | يقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream جديد. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | يقسم ملف Pdf إلى مستندات صفحة واحدة. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | يقسم ملف Pdf إلى مستندات صفحة واحدة ويحفظه في المسار المحدد. يتم تحديد المسار بواسطة اسم الحقل temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | يقسم ملف Pdf إلى مستندات صفحة واحدة ويحفظه في المسار المحدد. يتم تحديد المسار بواسطة اسم الحقل temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | يضيف الصفحات المختارة من مصفوفة المستندات في portStreams. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portStreams في النطاق من startPage إلى endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | يضيف الصفحات المختارة من مستندات portFiles. يتضمن المستند الناتج firstInputFile وجميع صفحات مستندات portFiles في النطاق من startPage إلى endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | يدمج المستندات. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | يدمج الملفات. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | يقوم بدمج الملفات في ملف واحد. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | يقوم بدمج ملفين. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | يقوم بدمج مستندين Pdf مع ترتيب الصفحات بشكل متناوب وملء الأماكن الفارغة بصفحات فارغة. مثال: document1 يحتوي على 5 صفحات: p1, p2, p3, p4, p5. document2 يحتوي على 3 صفحات: p1', p2', p3'. دمج المستندين Pdf سيُنتج المستند الناتج بالصفحات: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | يستخرج الصفحات من ملف الإدخال، يحفظها كملف Pdf جديد. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | ينشئ كتيبًا من InputStream إلى outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | ينشئ كتيبًا من inputFile إلى outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | ينشئ كتيبًا من firstInputStream إلى outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | ينشئ مستند N-Up من تدفقَي PDF الإدخال إلى outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | ينشئ مستند N-Up من تدفقات PDF المتعددة إلى outputStream. كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في تدفقات الإدخال ذات رقم الصفحة نفسه. يتم ترتيب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | ينشئ مستند N-Up من ملفي PDF الإدخال إلى outputFile. كل صفحة من outputFile ستحتوي على صفحتين، إحداهما من ملف الإدخال الأول والأخرى من ملف الإدخال الثاني. تُرتب الصفحتان أفقياً. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | ينشئ مستند N-Up من ملفات PDF المتعددة إلى outputFile. كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات في ملفات الإدخال ذات رقم الصفحة نفسه. تُرتب الصفحات المتعددة أفقياً إذا كان isSidewise صحيحًا وتُرتب عمودياً إذا كان isSidewise خاطئًا. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | ينشئ مستند N-Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | ينشئ مستند N-Up من firstInputFile إلى outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | ينشئ مستند N-Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | ينشئ مستند N-Up من ملف الإدخال إلى outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | يعيد تحجيم محتويات صفحات المستند. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | يعيد تحجيم محتويات الصفحات في المستند. إذا تم تقليص الصفحة تُضاف هوامش فارغة حولها. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | يعيد تحجيم محتويات صفحات المستند. يقلص محتويات الصفحة ويضيف هوامش. يُحدد الحجم الجديد للمحتويات بوحدات الفضاء الافتراضية. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | يقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كـ Stream جديد. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | الإجراء الذي يتم عندما يُصادف ملف تالف أثناء عملية الدمج. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | فئة لتحديد معلمات تغيير حجم الصفحة. تسمح بتعيين المعلمات التالية: حجم الصفحة الناتجة (العرض، الارتفاع) بوحدات المساحة الافتراضية أو كنسبة مئوية من حجم الصفحات الأصلية؛ الهوامش اليسرى، العليا، السفلية واليمنى بوحدات المساحة الافتراضية أو كنسبة مئوية من حجم الصفحة الأصلية؛ قد تُترك بعض القيم فارغة للحساب التلقائي. سيتم حساب هذه القيم من باقي حجم الصفحة بعد حساب القيم المحددة صراحة. على سبيل المثال: إذا كان عرض الصفحة = 100 وتم تحديد عرض صفحة جديد 60 وحدة، فإن الهوامش اليسرى واليمنى تُحسب تلقائياً: (100 - 60) / 2 = 15. تُستخدم هذه الفئة في طريقة ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | قيمة الهامش أو حجم المحتوى المحددة بالنسبة المئوية لوحدات المساحة الافتراضية. تُستخدم هذه الفئة في ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | الفئة التي توفر معلومات حول الملفات الفاسدة أثناء الجمع. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | بيانات موضع فاصل الصفحة. |

### انظر أيضًا

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


