---
title: PdfFileEditor
second_title: Aspose.PDF для справочника API .NET
description: Реализует операции с файлом PDF объединение разбиение извлечение страниц создание буклета и т. д.
type: docs
weight: 2470
url: /ru/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Реализует операции с файлом PDF: объединение, разбиение, извлечение страниц, создание буклета и т. д.

```csharp
public sealed class PdfFileEditor
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | Получает или задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | Если установлено значение true, потоки закрываются после операции. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, когда для параметра UseDiskBuffer установлено значение true. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | Получает или задает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение: встроенный / вложение. По умолчанию: встроенный. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Получает журнал процесса преобразования. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, то файл будет сохранен в формате PDF по умолчанию без преобразования. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Если true, то логическая структура файла копируется при выполнении конкатенации. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Если true, контуры будут скопированы. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | Массив проблем, возникших при выполнении конкатенации. Для каждого поврежденного документа из переданного в функцию Concatenate() создается новая запись CorruptedItem. Это свойство может использоваться только в том случае, если CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | Если true, во время конкатенации выполняются добавочные обновления. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Если true действия будут скопированы из исходных документов. Значение по умолчанию: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | Если true, то имена полей будут уникальными при объединении форм. К именам полей будут добавлены суффиксы, шаблон суффикса может быть указан в свойстве UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | Получает последнее возникшее исключение. Может использоваться для проверки причины сбоя. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. В противном случае слои с одинаковыми именами будут сохранены как разные слои в результирующем документе. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Если true, повторяющиеся контуры объединяются. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Устанавливает пароль владельца, если исходный входной файл Pdf зашифрован. Это свойство еще не реализовано. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Если true, права пользователя первого документа применяются к объединенному документу. Права пользователя на все остальные документы игнорируются. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Если true, все подписи будут удалены из полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для имена полей "fieldName" будут следующими: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т. д. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Изменяет размер содержимого страницы и добавляет заданные поля. Поля указываются в процентах от исходного размера страницы. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Изменяет размер содержимого страницы и добавляет заданные поля. Поля указываются в процентах от исходного размера страницы. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Добавляет разрывы страниц на страницы документа. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Добавляет разрывы страниц на страницы документа. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Добавляет разрывы страниц на страницы документа. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Добавляет документы в исходный документ и сохраняет результат в объекте ответа. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Добавляет документы в исходный документ и сохраняет результат в объекте HttpResponse. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | Добавляет страницы, выбранные из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Объединяет документы. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Объединяет файлы и сохраняет результат в объекте HttpResponse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Объединяет файлы |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Объединяет файлы и сохраняет результат в объекте HttpResposnse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Объединяет файлы в один файл. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | Объединяет два файла. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | Объединяет два файла. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: документ1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf даст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: документ1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf даст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Удаляет указанные страницы из документа и сохраняет результат в объекте HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Извлекает страницы из входного файла, сохраняет как новый файл PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Извлекает страницы из входного файла, сохраняет как новый файл PDF. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Вставляет документ в другой документ и сохраняет результат в объекте ответа. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Вставляет страницы из другого файла во входной файл Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Вставляет содержимое файла в исходный файл и сохраняет результат в объекте HttpResponse. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Вставляет страницы из другого файла во входной файл Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Вставляет страницы из другого файла во входной файл Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Вставляет страницы из другого файла в файл Pdf в позицию. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | Делает буклет из InputStream в outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Делает буклет из входного файла в выходной файл. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Создает буклет из исходного файла и сохраняет результат в HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Делает буклет из входного потока и сохраняет результат в выходной поток. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | Делает буклет из inputFile в outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | Создает настраиваемый буклет из firstInputStream в outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | Создает настраиваемый буклет из firstInputFile в outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Сделать буклет из файла PDF и сохранить его в HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Создает буклет из firstInputStream в outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | Создает настраиваемый буклет из firstInputFile в outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | Создает документ N-Up из двух входных потоков PDF в outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Создает документ N-Up из нескольких входных потоков PDF в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые объединяются со страницами во входных потоках с тем же номером страницы. Многостраничные страницы складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | Создает документ N-Up из двух входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла , а другая из второго входного файла. Две страницы сложены горизонтально. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Создает документ N-Up из нескольких входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией со страницами во входных файлах с тем же номером страницы. Несколько страниц складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | Создает документ N-up и сохраняет результат в HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Создает документ N-Up из входного потока и сохраняет результат в выходной поток. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | Создает документ N-up и сохраняет результат в HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | Создает документ N-Up из firstInputFile в outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | Создает документ N-up и сохраняет результат в объекте HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | Создает документ N-Up из первого входного потока в выходной поток. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | Создает документ N-up и сохраняет результат в объекте HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Создает документ N-Up из входного файла в outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Изменяет размеры страниц документа. Вокруг сжатой страницы добавляются пустые поля. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Изменяет размеры содержимого страниц документа. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Размер нового содержимого указывается в процентах. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Размер нового содержимого указывается в процентах. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Разбивает документ от начала до указанного места и сохраняет результат в объекте HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Разбивается от начала до указанного места и сохраняет переднюю часть в выходном потоке. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Разделяет документ с первой страницы на место и сохраняет результат в объектах HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Разбивает файл Pdf с первой страницы в указанное место и сохраняет переднюю часть как новый файл. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Разделяется из указанного места и сохраняет заднюю часть в объекте HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Разделяет из указанного места и сохраняет заднюю часть как новый файл Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Разделяется из указанного места и сохраняет заднюю часть в объекте HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Разделяет локацию и сохраняет заднюю часть как новый файл. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Разбивает файл Pdf на одностраничные документы. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | Разбивает файл PDF на одностраничные документы. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. Путь задается полем имени поля temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. Путь задается полем имени поля temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Добавляет документы в исходный документ и сохраняет результат в объекте ответа. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает firstInputFile и все страницы документов portStreams в диапазоне от startPage до endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Добавляет документы в исходный документ и сохраняет результат в объекте HttpResponse. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | Добавляет страницы, выбранные из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Объединяет документы. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Объединяет файлы и сохраняет результат в объекте HttpResponse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Объединяет файлы |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Объединяет файлы и сохраняет результат в объекте HttpResposnse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Объединяет файлы в один файл. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | Объединяет два файла. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: документ1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf даст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: документ1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf даст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Удаляет указанные страницы из документа и сохраняет результат в объект HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Удаляет указанные страницы из документа и сохраняет результат в объекте HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Извлекает указанные страницы из исходного файла и сохраняет результат в объект HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Извлекает страницы из входного файла, сохраняет как новый файл PDF. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Вставляет документ в другой документ и сохраняет результат в объекте ответа. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Вставляет страницы из другого файла во входной файл Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Вставляет содержимое файла в исходный файл и сохраняет результат в объекте HttpResponse. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Вставляет страницы из другого файла во входной файл Pdf. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | Делает буклет из InputStream в outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Создает буклет из входного файла в выходной файл. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Создает буклет из исходного файла и сохраняет результат в HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Делает буклет из входного потока и сохраняет результат в выходной поток. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | Делает буклет из inputFile в outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | Создает настраиваемый буклет из firstInputStream в outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | Создает настраиваемый буклет из firstInputFile в outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Сделать буклет из файла PDF и сохранить его в HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Создает буклет из firstInputStream в outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Создает буклет из исходного файла и сохраняет результат в объектах HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | Создает настраиваемый буклет из firstInputFile в outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | Создает документ N-Up из двух входных потоков PDF в outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Создает документ N-Up из нескольких входных потоков PDF в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые объединяются со страницами во входных потоках с тем же номером страницы. Многостраничные страницы складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | Создает документ N-Up из двух входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла , а другая из второго входного файла. Две страницы сложены горизонтально. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Создает документ N-Up из нескольких входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые являются комбинацией со страницами во входных файлах с тем же номером страницы. Несколько страниц складываются горизонтально , если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | Создает документ N-up и сохраняет результат в HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Создает документ N-Up из входного потока и сохраняет результат в выходной поток. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | Создает документ N-up и сохраняет результат в HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | Создает документ N-Up из firstInputFile в outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | Создает документ N-up и сохраняет результат в объекте HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | Создает документ N-Up из первого входного потока в выходной поток. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | Создает документ N-up и сохраняет результат в объекте HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Создает документ N-Up из входного файла в outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Изменяет размеры содержимого страниц документа. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. Результат сохраняется в объекте HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Изменяет размер содержимого страниц в документе. Если страница сжата, вокруг страницы добавляются пустые поля. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Разбивает документ от начала до указанного места и сохраняет результат в объекте HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Разбивается от начала до указанного места и сохраняет переднюю часть в выходном потоке. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Разделяет документ с первой страницы на место и сохраняет результат в объектах HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Разбивает файл Pdf с первой страницы в указанное место и сохраняет переднюю часть как новый файл. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Разделяется из указанного места и сохраняет заднюю часть в объекте HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Разделяет из указанного места и сохраняет заднюю часть как новый файл Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Разделяется из указанного места и сохраняет заднюю часть в объекте HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Разделяет локацию и сохраняет заднюю часть как новый файл. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Действие, выполняемое при обнаружении поврежденного файла в процессе объединения. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Класс для задания параметров изменения размера страницы. Позволяет задавать следующие параметры: Размер результирующей страницы (ширина, высота) в пространственных единицах по умолчанию или в процентах от размера начальных страниц; Левое, верхнее, нижнее и правое поля в пространственных единицах по умолчанию или в процентах от исходного размера страницы; Некоторые значения могут быть оставлены нулевыми для автоматического расчета. Эти значения будут рассчитаны из остального размера страницы после вычисления явно указанных значений. Например: если ширина страницы = 100 и новая ширина страницы указана в 60 единицах, то автоматически вычисляются левое и правое поля: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Значение поля или размера содержимого, указанное в процентах от единиц пространства по умолчанию. Этот класс используется в ContentsResizeParameters. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Класс, предоставляющий информацию о поврежденных файлах во время объединения. |
| class [PageBreak](pdffileeditor.pagebreak) | Данные позиции разрыва страницы. |

### Смотрите также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
