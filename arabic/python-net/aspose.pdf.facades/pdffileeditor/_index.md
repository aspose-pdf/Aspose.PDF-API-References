---
title: "PdfFileEditor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "ينفّذ عمليات دمج ملفات PDF، وتقسيمها، واستخراج الصفحات، وإنشاء كتيّب، إلخ."
type: docs
weight: 220
url: /ar/python-net/aspose.pdf.facades/pdffileeditor/
---

## PdfFileEditor class

تنفذ عمليات مع ملف PDF: الدمج، التقسيم، استخراج الصفحات، إنشاء كتيب، إلخ.

يعرض نوع PdfFileEditor الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFileEditor() | يُنشئ مثلاً جديداً من فئة PdfFileEditor |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| conversion_log | يحصل على سجل عملية التحويل. |
| merge_duplicate_layers | المحتويات الاختيارية للمستندات المدمجة ذات الأسماء المتساوية سيتم دمجها في طبقة واحدة في المستند الناتج إذا كانت هذه الخاصية صحيحة. <br/>            وإلا، سيتم حفظ الطبقات ذات الأسماء المتساوية كطبقات مختلفة في المستند الناتج. |
| copy_outlines | إذا كانت صحيحة، سيتم نسخ المخططات. |
| copy_logical_structure | إذا كانت صحيحة، سيتم نسخ البنية المنطقية للملف عند إجراء الدمج. |
| merge_duplicate_outlines | إذا كانت صحيحة، يتم دمج المخططات المتكررة. |
| preserve_user_rights | إذا كانت صحيحة، تُطبق حقوق المستخدم للمستند الأول على المستند المدمج. تُهمل حقوق المستخدم لجميع المستندات الأخرى. |
| incremental_updates | إذا كانت صحيحة، تُجرى تحديثات تدريجية أثناء الدمج. |
| optimize_size | يحصل أو يضبط علامة التحسين. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. <br/>            يتيح ذلك تقليل حجم الملف الناتج لكنه قد يسبب تنفيذًا أبطأ ومتطلبات ذاكرة أكبر.<br/>            القيمة الافتراضية: false. |
| corrupted_items | مصفوفة من المشكلات التي تم مواجهتها عند إجراء الدمج. لكل مستند تالف يتم تمريره إلى Concatenate() <br/>            يتم إنشاء إدخال CorruptedItem جديد.<br/>            يمكن استخدام هذه الخاصية فقط عندما تكون قيمة CorruptedFileAction هي ConcatenateIgnoringCorrupted. |
| corrupted_file_action | تحدد هذه الخاصية السلوك عندما تواجه عملية الدمج ملفًا تالفًا.<br/>            القيم الممكنة هي: StopWithError و ConcatenateIgnoringCorrupted. |
| owner_password | يضبط كلمة مرور المالك إذا كان ملف Pdf المصدر مشفرًا.<br/>            هذه الخاصية لم تُنفّذ بعد. |
| allow_concatenate_exceptions | إذا تم تعيينه إلى true، تُرمى الاستثناءات إذا حدث خطأ. وإلا لا تُرمى الاستثناءات وتُعيد الطرق false إذا فشل. |
| close_concatenated_streams | إذا تم تعيينه إلى true، تُغلق التدفقات بعد العملية. |
| unique_suffix | صيغة اللاحقة التي تُضاف إلى اسم الحقل لجعلها فريدة عند دمج النماذج.<br/>            يجب أن تحتوي هذه السلسلة على الجزء %NUM% الذي سيُستبدل بالأرقام.<br/>            على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فستكون أسماء الحقول "fieldName" كالتالي:<br/>            fieldNameABC1, fieldNameABC2, fieldNameABC3 إلخ. |
| keep_actions | إذا كان true، سيتم نسخ الإجراءات من المستندات المصدر. القيمة الافتراضية: true. |
| keep_fields_unique | إذا كان true، سيتم جعل أسماء الحقول فريدة عند دمج النماذج.<br/>            ستُضاف اللاحقات إلى أسماء الحقول، ويمكن تحديد قالب اللاحقة في خاصية UniqueSuffix. |
| remove_signatures | إذا كان true، سيتم إزالة جميع التوقيعات من الحقول (ستبقى الحقول موجودة)؛ وإلا قد تحصل على توقيعات غير صالحة. |
| use_disk_buffer | إذا تم استخدام هذا الخيار، سيتم حفظ المستند الوجهة على القرص بشكل دوري وستُطبق عمليات الدمج اللاحقة عليه كتحديثات متزايدة. |
| concatenation_packet_size | عدد المستندات التي تم دمجها قبل إنشاء تحديث متزايد جديد أثناء عملية الدمج عندما تكون UseDiskBuffer مضبوطة على true. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| try_concatenate(first_input_file, sec_input_file, output_file) | يدمج ملفين. |
| try_concatenate(src, dest) | يدمج المستندات. |
| try_concatenate(input_files, output_file) | يدمج الملفات في ملف واحد. |
| try_concatenate(input_stream, output_stream) | يدمج الملفات |
| try_concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | يدمج ملفين. |
| try_concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | يدمج الملفات |
| try_append(input_stream, port_streams, start_page, end_page, output_stream) | يضيف الصفحات التي يتم اختيارها من مصفوفة المستندات في portStreams.<br/>            يتضمن مستند النتيجة firstInputFile وجميع صفحات مستندات portStreams في النطاق startPage إلى endPage. |
| try_append(input_file, port_files, start_page, end_page, output_file) | يضيف الصفحات التي يتم اختيارها من مستندات portFiles. <br/>            يتضمن مستند النتيجة firstInputFile وجميع صفحات مستندات portFiles في النطاق startPage إلى endPage. |
| try_insert(input_file, insert_location, port_file, page_number, output_file) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| try_insert(input_stream, insert_location, port_stream, page_number, output_stream) | يدرج الصفحات من ملف آخر إلى ملف Pdf الإدخال. |
| try_delete(input_file, page_number, output_file) | يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| try_delete(input_stream, page_number, output_stream) | يحذف الصفحات المحددة بمصفوفة الأرقام من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| try_extract(input_file, start_page, end_page, output_file) | يستخرج الصفحات من ملف الإدخال، ويحفظها كملف Pdf جديد. |
| try_extract(input_file, page_number, output_file) | يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف PDF جديد. |
| try_extract(input_stream, page_number, output_stream) | يستخرج الصفحات المحددة بمصفوفة الأرقام، ويحفظها كملف Pdf جديد. |
| try_split_from_first(input_file, location, output_file) | يقسم ملف Pdf من الصفحة الأولى إلى الموقع المحدد، ويحفظ الجزء الأمامي كملف جديد. |
| try_split_from_first(input_stream, location, output_stream) | يقسم من البداية إلى الموقع المحدد، ويحفظ الجزء الأمامي في تدفق الإخراج. |
| try_split_to_end(input_file, location, output_file) | يقسم من الموقع، ويحفظ الجزء الخلفي كملف جديد. |
| try_split_to_end(input_stream, location, output_stream) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي كدفق ملف جديد. |
| try_make_booklet(input_file, output_file) | ينشئ كتيبًا من ملف الإدخال إلى ملف الإخراج. |
| try_make_booklet(input_stream, output_stream) | ينشئ كتيبًا من InputStream إلى outputStream. |
| try_make_booklet(input_file, output_file, page_size) | ينشئ كتيبًا من inputFile إلى outputFile. |
| try_make_booklet(input_stream, output_stream, page_size) | ينشئ كتيبًا من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| try_make_booklet(input_file, output_file, left_pages, right_pages) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| try_make_booklet(input_stream, output_stream, left_pages, right_pages) | ينشئ كتيبًا مخصصًا من firstInputStream إلى outputStream. |
| try_make_booklet(input_file, output_file, page_size, left_pages, right_pages) | ينشئ كتيبًا مخصصًا من firstInputFile إلى outputFile. |
| try_make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | ينشئ كتيبًا من firstInputStream إلى outputStream. |
| try_make_n_up(input_file, output_file, x, y) | ينشئ مستند N‑Up من firstInputFile إلى outputFile. |
| try_make_n_up(input_stream, output_stream, x, y) | ينشئ مستند N‑Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| try_make_n_up(input_stream, output_stream, x, y, page_size) | ينشئ مستند N‑Up من تدفق الإدخال الأول إلى تدفق الإخراج. |
| try_make_n_up(first_input_file, second_input_file, output_file) | ينشئ مستند N‑Up من firstInputFile إلى outputFile. |
| try_make_n_up(first_input_stream, second_input_stream, output_stream) | ينشئ مستند N‑Up من تدفق الإدخال ويحفظ النتيجة في تدفق الإخراج. |
| try_make_n_up(input_files, output_file, is_sidewise) | ينشئ مستند N-Up من ملفات PDF المتعددة المدخلة إلى outputFile. <br/>            كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات <br/>            في ملفات الإدخال ذات رقم الصفحة نفسه. يتم تجميع الصفحات المتعددة أفقياً <br/>            إذا كان isSidewise صحيحاً وتُجمع عمودياً إذا كان isSidewise خاطئاً. |
| try_make_n_up(input_streams, output_stream, is_sidewise) | ينشئ مستند N-Up من تدفقات PDF المتعددة المدخلة إلى outputStream.<br/>            كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات <br/>            في تدفقات الإدخال ذات رقم الصفحة نفسه. يتم تجميع الصفحات المتعددة أفقياً <br/>            إذا كان isSidewise صحيحاً وتُجمع عمودياً إذا كان isSidewise خاطئاً. |
| try_make_n_up(input_file, output_file, x, y, page_size) | ينشئ مستند N-Up من ملف الإدخال إلى outputFile. |
| try_resize_contents(source, destination, pages, parameters) | يعيد تحجيم محتويات صفحات المستند. |
| try_resize_contents(source, destination, pages, new_width, new_height) | يعيد تحجيم محتويات صفحات المستند. <br/>            يقلص محتويات الصفحة ويضيف هوامش.<br/>            يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. |
| try_resize_contents(source, destination, pages, parameters) | يعيد تحجيم محتويات صفحات المستند. إذا تم تقليل حجم الصفحة تُضاف هوامش فارغة حول الصفحة. |
| concatenate(first_input_file, sec_input_file, output_file) | يجمع الملفات ويحفظ النتيجة في كائن HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, output_stream) | يجمع الملفات ويخزن النتيجة في كائن HttpResponse. |
| concatenate(src, dest) | يدمج المستندات. |
| concatenate(input_files, output_file) | يجمع الملفات ويحفظ النتيجة في كائن HttpResposnse. |
| concatenate(input_stream, output_stream) | يجمع الملفات ويخزن النتيجة في كائن HttpResponse. |
| concatenate(first_input_file, sec_input_file, blank_page_file, output_file) | يجمع الملفات ويحفظ النتيجة في كائن HttpResposnse. |
| concatenate(first_input_stream, sec_input_stream, blank_page_stream, output_stream) | يجمع الملفات ويخزن النتيجة في كائن HttpResponse. |
| append(input_stream, port_streams, start_page, end_page, output_stream) | يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن الاستجابة. |
| append(input_file, port_files, start_page, end_page, output_file) | يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن HttpResponse. |
| append(input_file, port_file, start_page, end_page, output_file) | يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن HttpResponse. |
| append(input_stream, port_stream, start_page, end_page, output_stream) | يضيف المستندات إلى المستند المصدر ويحفظ النتيجة في كائن الاستجابة. |
| insert(input_file, insert_location, port_file, start_page, end_page, output_file) | يدرج محتويات الملف في الملف المصدر ويخزن النتيجة في كائن HttpResponse. |
| insert(input_stream, insert_location, port_stream, start_page, end_page, output_stream) | يدرج المستند في مستند آخر ويخزن النتيجة في كائن الاستجابة. |
| insert(input_file, insert_location, port_file, page_number, output_file) | يدرج محتويات الملف في الملف المصدر ويخزن النتيجة في كائن HttpResponse. |
| insert(input_stream, insert_location, port_stream, page_number, output_stream) | يدرج المستند في مستند آخر ويخزن النتيجة في كائن الاستجابة. |
| delete(input_file, page_number, output_file) | يحذف الصفحات المحددة من المستند ويخزن النتيجة في كائن HttpResponse. |
| delete(input_stream, page_number, output_stream) | يحذف الصفحات المحددة من المستند ويحفظ النتيجة في كائن HttpResponse. |
| extract(input_file, start_page, end_page, output_file) | يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpResponse. |
| extract(input_file, page_number, output_file) | يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpResponse. |
| extract(input_stream, start_page, end_page, output_stream) | يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpResponse. |
| extract(input_stream, page_number, output_stream) | يستخرج الصفحات المحددة من الملف المصدر ويخزن النتيجة في كائن HttpResponse. |
| split_from_first(input_file, location, output_file) | يقسم المستند من الصفحة الأولى إلى الموقع ويحفظ النتيجة في كائنات HttpResponse. |
| split_from_first(input_stream, location, output_stream) | يقسم المستند من البداية إلى الموقع المحدد ويخزن النتيجة في كائن HttpResponse. |
| split_to_end(input_file, location, output_file) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي في كائن HttpResponse. |
| split_to_end(input_stream, location, output_stream) | يقسم من الموقع المحدد، ويحفظ الجزء الخلفي في كائن HttpResponse. |
| make_booklet(input_file, output_file) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpResponse. |
| make_booklet(input_stream, output_stream) | إنشاء كتيب من ملف PDF وتخزينه في HttpResponse. |
| make_booklet(input_file, output_file, page_size) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpResponse. |
| make_booklet(input_stream, output_stream, page_size) | إنشاء كتيب من ملف PDF وتخزينه في HttpResponse. |
| make_booklet(input_file, output_file, left_pages, right_pages) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpResponse. |
| make_booklet(input_stream, output_stream, left_pages, right_pages) | إنشاء كتيب من ملف PDF وتخزينه في HttpResponse. |
| make_booklet(input_file, output_file, page_size, left_pages, right_pages) | ينشئ كتيبًا من الملف المصدر ويخزن النتيجة في كائنات HttpResponse. |
| make_booklet(input_stream, output_stream, page_size, left_pages, right_pages) | إنشاء كتيب من ملف PDF وتخزينه في HttpResponse. |
| make_n_up(input_file, output_file, x, y) | ينشئ مستند N-up ويخزن النتيجة في كائن HttpResponse. |
| make_n_up(input_stream, output_stream, x, y) | ينشئ مستند N-up ويخزن النتيجة في كائن HttpResponse. |
| make_n_up(input_stream, output_stream, x, y, page_size) | ينشئ مستند N-up ويخزن النتيجة في كائن HttpResponse. |
| make_n_up(first_input_file, second_input_file, output_file) | ينشئ مستند N-up ويخزن النتيجة في كائن HttpResponse. |
| make_n_up(first_input_stream, second_input_stream, output_stream) | ينشئ مستند N-up ويخزن النتيجة في كائن HttpResponse. |
| make_n_up(input_files, output_file, is_sidewise) | ينشئ مستند N-Up من ملفات PDF المتعددة المدخلة إلى outputFile. <br/>            كل صفحة من outputFile ستحتوي على صفحات متعددة، وهي مزيج من الصفحات <br/>            في ملفات الإدخال ذات رقم الصفحة نفسه. يتم تجميع الصفحات المتعددة أفقياً <br/>            إذا كان isSidewise صحيحاً وتُجمع عمودياً إذا كان isSidewise خاطئاً. |
| make_n_up(input_streams, output_stream, is_sidewise) | ينشئ مستند N-Up من تدفقات PDF المتعددة المدخلة إلى outputStream.<br/>            كل صفحة من outputStream ستحتوي على صفحات متعددة، وهي مزيج من الصفحات <br/>            في تدفقات الإدخال ذات رقم الصفحة نفسه. يتم تجميع الصفحات المتعددة أفقياً <br/>            إذا كان isSidewise صحيحاً وتُجمع عمودياً إذا كان isSidewise خاطئاً. |
| make_n_up(input_file, output_file, x, y, page_size) | ينشئ مستند N-up ويخزن النتيجة في كائن HttpResponse. |
| split_to_pages(input_file, file_name_template) | يقسم ملف PDF إلى مستندات صفحة واحدة. |
| split_to_pages(input_stream, file_name_template) | يقسم ملف Pdf إلى مستندات صفحة واحدة ويحفظه في المسار المحدد. يتم تحديد المسار بواسطة قالب اسم الحقل. |
| resize_contents(source, destination, pages, parameters) | يعيد تحجيم محتويات الصفحات في المستند. إذا تم تصغير الصفحة تُضاف هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse. |
| resize_contents(source, destination, pages, new_width, new_height) | يعيد تحجيم محتويات صفحات المستند. <br/>            يقلص محتويات الصفحة ويضيف هوامش.<br/>            يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. |
| resize_contents(source, destination, pages, new_width, new_height) | يعيد تحجيم محتويات صفحات المستند. <br/>            يقلص محتويات الصفحة ويضيف هوامش.<br/>            يتم تحديد الحجم الجديد للمحتويات بوحدات المسافة الافتراضية. |
| resize_contents(source, destination, pages, parameters) | يعيد تحجيم محتويات الصفحات في المستند. إذا تم تصغير الصفحة تُضاف هوامش فارغة حول الصفحة. يتم تخزين النتيجة في كائن HttpResponse. |
| resize_contents(source, pages, parameters) | يعيد تحجيم صفحات المستند. تُضاف هوامش فارغة حول الصفحة المصغرة. |
| resize_contents(source, parameters) | يعيد تحجيم صفحات المستند. تُضاف هوامش فارغة حول الصفحة المصغرة. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | يعيد تحجيم محتويات صفحات المستند.<br/>            يصغر محتويات الصفحة ويضيف هوامش.<br/>            يتم تحديد حجم المحتويات الجديد بالنسب المئوية. |
| resize_contents_pct(source, destination, pages, new_width, new_height) | يعيد تحجيم محتويات صفحات المستند.<br/>            يصغر محتويات الصفحة ويضيف هوامش.<br/>            يتم تحديد حجم المحتويات الجديد بالنسب المئوية. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | يعيد تحجيم محتويات الصفحة ويضيف الهوامش المحددة.<br/>            يتم تحديد الهوامش بوحدات المسافة الافتراضية. |
| add_margins(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | يعيد تحجيم محتويات الصفحة ويضيف الهوامش المحددة.<br/>            يتم تحديد الهوامش بوحدات المسافة الافتراضية. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | يعيد تحجيم محتويات الصفحة ويضيف الهوامش المحددة.<br/>            يتم تحديد الهوامش بالنسبة المئوية لحجم الصفحة الأصلي. |
| add_margins_pct(source, destination, pages, left_margin, right_margin, top_margin, bottom_margin) | يعيد تحجيم محتويات الصفحة ويضيف الهوامش المحددة.<br/>            يتم تحديد الهوامش بالنسبة المئوية لحجم الصفحة الأصلي. |
| add_page_break(src, dest, page_breaks) | يضيف فواصل صفحات إلى صفحات المستند. |
| add_page_break(src, dest, page_breaks) | يضيف فواصل صفحات إلى صفحات المستند. |
| add_page_break(src, dest, page_breaks) | يضيف فواصل صفحات إلى صفحات المستند. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

