---
title: "Класс PdfFileEditor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfFileEditor class. Реализует операции с объединением PDF‑файлов, их разбиением, извлечением страниц, созданием буклета и т.д."
type: docs
weight: 4580
url: /ru/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Реализует операции с PDF‑файлом: конкатенацию, разбиение, извлечение страниц, создание буклета и т.д.

```csharp
public sealed class PdfFileEditor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Если установлено значение true, потоки закрываются после операции. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Количество документов, объединённых до выполнения нового инкрементного обновления во время объединения, когда UseDiskBuffer установлено в true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Получает журнал процесса конвертации. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Устанавливает формат PDF‑файла. Результирующий файл будет сохранён в указанном формате. Если это свойство не указано, файл будет сохранён в формате PDF по умолчанию без конвертации. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Если true, то логическая структура файла копируется при выполнении конкатенации. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Если true, то контуры будут скопированы. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Это свойство определяет поведение, когда процесс конкатенации встречает повреждённый файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Массив возникших проблем при выполнении конкатенации. Для каждого повреждённого документа, переданного в функцию Concatenate(), создаётся новая запись CorruptedItem. Это свойство может использоваться только когда CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Если true, во время конкатенации выполняются инкрементные обновления. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Если true, действия будут скопированы из исходных документов. Значение по умолчанию: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Если true, имена полей будут сделаны уникальными при конкатенации форм. К именам полей будут добавлены суффиксы, шаблон суффикса можно указать в свойстве UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Получает последнее возникшее исключение. Может использоваться для проверки причины сбоя. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Если это свойство true, необязательное содержимое конкатенированных документов с одинаковыми именами будет объединено в один слой в результирующем документе. В противном случае слои с одинаковыми именами будут сохранены как отдельные слои в результирующем документе. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Если true, дублирующие контуры объединяются. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Получает или задает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может вызвать более медленное выполнение и большие требования к памяти. Значение по умолчанию: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Устанавливает пароль владельца, если исходный входной Pdf файл зашифрован. Это свойство ещё не реализовано. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Если true, пользовательские права первого документа применяются к конкатенированному документу. Права всех остальных документов игнорируются. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Если true, все подписи будут удалены из полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при конкатенации форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" имена будут: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Если эта опция используется, то документ назначения будет периодически сохраняться на диск, а дальнейшая конкатенация будет применяться к нему как инкрементные обновления. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в единицах пространства по умолчанию. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в процентах от исходного размера страницы. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Изменяет размер содержимого страниц и добавляет указанные поля. Поля задаются в процентах от исходного размера страницы. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Добавляет разрывы страниц в документ. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Добавляет разрывы страниц в документ. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Добавляет разрывы страниц в документ. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конец firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Добавляет страницы, выбранные из массива документов в portStreams. Итоговый документ включает firstInputFile и страницы всех документов portStreams в диапазоне от startPage до endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конец firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Добавляет страницы, выбранные из документов portFiles. Итоговый документ включает firstInputFile и страницы всех документов portFiles в диапазоне от startPage до endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Конкатенирует документы. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Конкатенирует файлы |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Объединяет файлы в один файл. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Объединяет два файла. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Объединяет два файла. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Объединяет два Pdf документа в новый Pdf документ, чередуя страницы и заполняя пустые места пустыми страницами. Например: document1 содержит 5 страниц: p1, p2, p3, p4, p5. document2 содержит 3 страницы: p1', p2', p3'. Слияние двух Pdf документов создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Объединяет два Pdf документа в новый Pdf документ, чередуя страницы и заполняя пустые места пустыми страницами. Например: document1 содержит 5 страниц: p1, p2, p3, p4, p5. document2 содержит 3 страницы: p1', p2', p3'. Слияние двух Pdf документов создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Извлекает страницы, указанные массивом номеров, и сохраняет как новый Pdf файл. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Извлекает страницы, указанные массивом номеров, и сохраняет как новый PDF файл. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Извлекает страницы из входного файла, сохраняет как новый Pdf файл. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Извлекает страницы из входного файла, сохраняет как новый Pdf файл. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Вставляет страницы из другого файла во входный Pdf файл. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Вставляет страницы из другого файла во входный Pdf файл. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Вставляет страницы из другого файла во входный Pdf файл. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Вставляет страницы из другого файла в Pdf файл в указанную позицию. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Создает буклет из InputStream в outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Создает буклет из входного файла в выходной файл. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Создает буклет из входного потока и сохраняет результат в выходной поток. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Создает буклет из inputFile в outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Создает пользовательский буклет из firstInputStream в outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Создает пользовательский буклет из firstInputFile в outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Создает буклет из firstInputStream в outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Создает пользовательский буклет из firstInputFile в outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Создает документ N-Up из двух входных PDF потоков в outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Создает документ N-Up из нескольких входных PDF потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц во входных потоках с одинаковыми номерами. Многостраничные страницы укладываются горизонтально, если isSidewise истинно, и вертикально, если isSidewise ложно. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Создает документ N-Up из двух входных PDF файлов в outputFile. Каждая страница outputFile будет содержать две страницы: одна из первого входного файла, другая из второго входного файла. Эти две страницы располагаются горизонтально. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Создает документ N-Up из нескольких входных PDF файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц во входных файлах с одинаковыми номерами. Многостраничные страницы укладываются горизонтально, если isSidewise истинно, и вертикально, если isSidewise ложно. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Создает документ N-Up из входного потока и сохраняет результат в выходной поток. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Создает документ N-Up из firstInputFile в outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Создает документ N-Up из первого входного потока в выходной поток. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Создает документ N-Up из входного файла в outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Изменяет размер страниц документа. Пустые поля добавляются вокруг уменьшенной страницы. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Изменяет размер содержимого страниц документа. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в единицах пространства по умолчанию. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в единицах пространства по умолчанию. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в процентах. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в процентах. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Разделяет от начала до указанного места и сохраняет переднюю часть в выходной поток. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Разделяет Pdf файл с первой страницы до указанного места и сохраняет переднюю часть как новый файл. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Разделяет Pdf‑файл на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Разделяет Pdf‑файл на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Разделяет от указанного места и сохраняет заднюю часть как новый поток файла. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Разделяет от места и сохраняет заднюю часть как новый файл. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Разделяет Pdf‑файл на одностраничные документы. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Разделяет PDF‑файл на одностраничные документы. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Разделяет Pdf‑файл на одностраничные документы и сохраняет его в указанный путь. Путь задаётся именем поля template. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Разделяет Pdf‑файл на одностраничные документы и сохраняет его в указанный путь. Путь задаётся именем поля template. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Добавляет страницы, выбранные из массива документов в portStreams. Итоговый документ включает firstInputFile и страницы всех документов portStreams в диапазоне от startPage до endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Добавляет страницы, выбранные из документов portFiles. Итоговый документ включает firstInputFile и страницы всех документов portFiles в диапазоне от startPage до endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Конкатенирует документы. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Конкатенирует файлы |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Объединяет файлы в один файл. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Объединяет два файла. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Объединяет два Pdf документа в новый Pdf документ, чередуя страницы и заполняя пустые места пустыми страницами. Например: document1 содержит 5 страниц: p1, p2, p3, p4, p5. document2 содержит 3 страницы: p1', p2', p3'. Слияние двух Pdf документов создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Объединяет два Pdf документа в новый Pdf документ, чередуя страницы и заполняя пустые места пустыми страницами. Например: document1 содержит 5 страниц: p1, p2, p3, p4, p5. document2 содержит 3 страницы: p1', p2', p3'. Слияние двух Pdf документов создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Удаляет страницы, указанные массивом номеров, из входного файла и сохраняет как новый Pdf файл. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Извлекает страницы, указанные массивом номеров, и сохраняет как новый Pdf файл. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Извлекает страницы, указанные массивом номеров, и сохраняет как новый PDF файл. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Извлекает страницы из входного файла, сохраняет как новый Pdf файл. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Вставляет страницы из другого файла во входный Pdf файл. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Вставляет страницы из другого файла во входный Pdf файл. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Создает буклет из InputStream в outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Создает буклет из входного файла в выходной файл. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Создает буклет из входного потока и сохраняет результат в выходной поток. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Создает буклет из inputFile в outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Создает пользовательский буклет из firstInputStream в outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Создает пользовательский буклет из firstInputFile в outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Создает буклет из firstInputStream в outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Создает пользовательский буклет из firstInputFile в outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Создает документ N-Up из двух входных PDF потоков в outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Создает документ N-Up из нескольких входных PDF потоков в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые являются комбинацией страниц во входных потоках с одинаковыми номерами. Многостраничные страницы укладываются горизонтально, если isSidewise истинно, и вертикально, если isSidewise ложно. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Создает документ N-Up из двух входных PDF файлов в outputFile. Каждая страница outputFile будет содержать две страницы: одна из первого входного файла, другая из второго входного файла. Эти две страницы располагаются горизонтально. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Создает документ N-Up из нескольких входных PDF файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией страниц во входных файлах с одинаковыми номерами. Многостраничные страницы укладываются горизонтально, если isSidewise истинно, и вертикально, если isSidewise ложно. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Создает документ N-Up из входного потока и сохраняет результат в выходной поток. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Создает документ N-Up из firstInputFile в outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Создает документ N-Up из первого входного потока в выходной поток. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Создает документ N-Up из входного файла в outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Изменяет размер содержимого страниц документа. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Изменяет размер содержимого страниц в документе. Если страница уменьшена, вокруг неё добавляются пустые поля. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в единицах пространства по умолчанию. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Разделяет от начала до указанного места и сохраняет переднюю часть в выходной поток. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Разделяет Pdf файл с первой страницы до указанного места и сохраняет переднюю часть как новый файл. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Разделяет от указанного места и сохраняет заднюю часть как новый поток файла. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Разделяет от места и сохраняет заднюю часть как новый файл. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Действие, выполняемое при встрече повреждённого файла в процессе конкатенации. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от исходного размера страниц; левое, верхнее, нижнее и правое поля в единицах пространства по умолчанию или в процентах от исходного размера страницы; некоторые значения могут быть оставлены null для автоматического вычисления. Эти значения будут рассчитаны из оставшегося размера страницы после вычисления явно указанных значений. Например: если ширина страницы = 100, а новая ширина страницы указана как 60 единиц, то левое и правое поля автоматически рассчитываются: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Значение отступа или размера содержимого, указанное в процентах от единиц пространства по умолчанию. Этот класс используется в ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Класс, предоставляющий информацию о повреждённых файлах во время конкатенации. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Данные о позиции разрыва страницы. |

### См. также

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


