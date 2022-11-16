---
title: IPdfFileEditor
second_title: Aspose.PDF для справки по Java API
description: Реализует операции с конкатенацией файлов PDF, разделением, извлечением страниц, созданием буклетов и т. д.
type: docs
weight: 70
url: /ru/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Реализует операции с файлом PDF: объединение, разбиение, извлечение страниц, создание буклета и др.
## Методы

| Метод | Описание |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream. |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-) | Добавляет страницы, выбранные из массива документов в portStreams. |
| [append(String inputFile, String portFile, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile. |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String---int-int-java.lang.String-) | Добавляет страницы, выбранные из документов portFiles. |
| [concatenate(IDocument[] src, IDocument dest)](#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-) | Объединяет документы. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Объединяет два файла. |
| [concatenate(InputStream[] inputStream, OutputStream outputStream)](#concatenate-java.io.InputStream---java.io.OutputStream-) | Объединяет файлы |
| [concatenate(String firstInputFile, String secInputFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Объединяет два файла. |
| [concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. |
| [concatenate(String[] inputFiles, String outputFile)](#concatenate-java.lang.String---java.lang.String-) | Объединяет файлы в один файл. |
| [delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#delete-java.io.InputStream-int---java.io.OutputStream-) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [delete(String inputFile, int[] pageNumber, String outputFile)](#delete-java.lang.String-int---java.lang.String-) | Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf. |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Извлекает страницы из входного файла, сохраняет как новый файл Pdf. |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf. |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | Извлекает страницы из входного файла, сохраняет как новый файл Pdf. |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF. |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | Разрешить объединение исключений |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение. |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | Если установлено значение true, потоки закрываются после операции. |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpServletResponse. |
| [getConversionLog()](#getConversionLog--) | Получает журнал процесса преобразования. |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | Если true, во время конкатенации выполняются добавочные обновления. |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | Если true, то имена полей будут уникальными при объединении форм. |
| [getLastException()](#getLastException--) | Получает последнее произошедшее исключение. |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | Если true, повторяющиеся контуры объединяются. |
| [getOwnerPassword()](#getOwnerPassword--) | Получает пароль владельца, если исходный входной файл Pdf зашифрован. |
| [getPreserveUserRights()](#getPreserveUserRights--) | Если true, права пользователя первого документа применяются к объединенному документу. |
| [getRemoveSignatures()](#getRemoveSignatures--) | Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [getSaveOptions()](#getSaveOptions--) | Получает или задает параметры сохранения, когда результат сохраняется как HttpServletResponse. |
| [getUniqueSuffix()](#getUniqueSuffix--) | Получить формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Вставляет страницы из другого файла в файл Pdf в позицию. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream)](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Создает буклет из InputStream в outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Делает буклет из входного потока и сохраняет результат в выходной поток. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---) | Создает буклет из firstInputStream в outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---) | Создает настраиваемый буклет из firstInputStream в outputStream. |
| [makeBooklet(String inputFile, String outputFile)](#makeBooklet-java.lang.String-java.lang.String-) | Делает буклет из входного файла в выходной файл. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Делает буклет из inputFile в outputFile. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---) | Создает настраиваемый буклет из файла firstInputFile в файл outputFile. |
| [makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-int---int---) | Создает настраиваемый буклет из файла firstInputFile в файл outputFile. |
| [makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Создает документ N-Up из двух входных потоков PDF в outputStream. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Создает документ N-Up из входного потока и сохраняет результат в выходной поток. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Создает документ N-Up из первого входного потока в выходной поток. |
| [makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)](#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-) | Создает документ N-Up из нескольких входных потоков PDF в outputStream. |
| [makeNUp(String inputFile, String outputFile, int x, int y)](#makeNUp-java.lang.String-java.lang.String-int-int-) | Создает документ N-Up из firstInputFile в outputFile. |
| [makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Создает документ N-Up из входного файла в outputFile. |
| [makeNUp(String firstInputFile, String secondInputFile, String outputFile)](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Создает документ N-Up из двух входных PDF-файлов в outputFile. |
| [makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)](#makeNUp-java.lang.String---java.lang.String-boolean-) | Создает документ N-Up из нескольких входных PDF-файлов в outputFile. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | Если установлено значение true, при возникновении ошибки генерируются исключения. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение. |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | Если установлено значение true, потоки закрываются после операции. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpServletResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | Если true, во время конкатенации выполняются добавочные обновления. |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | Если true, то имена полей будут уникальными при объединении форм. |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) | Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | Если true, повторяющиеся контуры объединяются. |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Устанавливает пароль владельца, если исходный входной файл Pdf зашифрован. |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | Если true, права пользователя первого документа применяются к объединенному документу. |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpServletResponse. |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | Установите формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. |
| [splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Разбивается от начала до указанного места и сохраняет переднюю часть в выходном потоке. |
| [splitFromFirst(String inputFile, int location, String outputFile)](#splitFromFirst-java.lang.String-int-java.lang.String-) | Разбивает файл Pdf с первой страницы в указанное место и сохраняет переднюю часть как новый файл. |
| [splitToBulks(InputStream inputStream, int[][] numberOfPage)](#splitToBulks-java.io.InputStream-int-----) | Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [splitToBulks(String inputFile, int[][] numberOfPage)](#splitToBulks-java.lang.String-int-----) | Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными. |
| [splitToEnd(InputStream inputStream, int location, OutputStream outputStream)](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Разбивается из указанного места и сохраняет заднюю часть как новый файловый поток. |
| [splitToEnd(String inputFile, int location, String outputFile)](#splitToEnd-java.lang.String-int-java.lang.String-) | Отделяется от местоположения и сохраняет заднюю часть как новый файл. |
| [splitToPages(InputStream inputStream)](#splitToPages-java.io.InputStream-) | Разбивает файл Pdf на одностраничные документы. |
| [splitToPages(InputStream inputStream, String fileNameTemplate)](#splitToPages-java.io.InputStream-java.lang.String-) | Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. |
| [splitToPages(String inputFile)](#splitToPages-java.lang.String-) | Разбивает файл PDF на одностраничные документы. |
| [splitToPages(String inputFile, String fileNameTemplate)](#splitToPages-java.lang.String-java.lang.String-) | Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. |
### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public abstract boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.addMargins(src, dest,
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 10 units
 	10,
 	// right margin is 5 units
 	5,
 	// top margin is 5 units
 	5,
 	// bottom margin is 5 units
 	5);
 dest.Close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле. |
| rightMargin | double | Правая маржа. |
| topMargin | double | Верхнее поле. |
| bottomMargin | double | Нижний край. |

**Возвращает:**
boolean - логическое значение
### addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public abstract boolean addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.addMargins("input.pdf", "output.pdf",
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 10 units
 	10,
 	// right margin is 5 units
 	5,
 	// top margin is 5 units
 	5,
 	// bottom margin is 5 units
 	5);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле. |
| rightMargin | double | Правая маржа. |
| topMargin | double | Верхнее поле. |
| bottomMargin | double | Нижний край. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно.
### addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public abstract boolean addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в процентах от исходного размера страницы.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.addMarginsPct(src, dest,
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 15% of page width
 	15,
 	// right margin is 10% of page width
 	10,
 	// top margin is 20% of page width
 	20,
 	// bottom margin is 5% of page width
 	5);
 dest.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле в процентах от исходного размера страницы. |
| rightMargin | double | Правое поле в процентах от исходного размера страницы. |
| topMargin | double | Верхнее поле в процентах от исходного размера страницы. |
| bottomMargin | double | Нижнее поле в процентах от исходного размера страницы. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public abstract boolean addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в процентах от исходного размера страницы.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.addMarginsPct("input.pdf", "output.pdf",
 // process pages 1, 2, 3
 	new int[]
 	{ 1, 2, 3 },
 	// left margin is 15% of page width
 	15,
 	// right margin is 10% of page width
 	10,
 	// top margin is 20% of page width
 	20,
 	// bottom margin is 5% of page width
 	5);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| leftMargin | double | Левое поле в процентах от исходного размера страницы. |
| rightMargin | double | Правое поле в процентах от исходного размера страницы. |
| topMargin | double | Верхнее поле в процентах от исходного размера страницы. |
| bottomMargin | double | Нижнее поле в процентах от исходного размера страницы. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно
### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
public abstract boolean append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1, 3, 5, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| portStream | java.io.InputStream | Страницы из файла Pdf Stream. |
| startPage | int | Страница начинается в порту File Stream. |
| endPage | int | Страница заканчивается в portFile Stream. |
| outputStream | java.io.OutputStream | Выходной файл Pdf Stream. |

**Возвращает:**
boolean - True для успеха или false.
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-}
```
public abstract boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает страницы firstInputFile и всех документов portStreams в диапазоне от startPage до endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, new Stream[]
 { stream1, stream2 }, 3, 5, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| portStreams | java.io.InputStream[] | Документы, из которых нужно скопировать страницы. |
| startPage | int | Страница начинается в документах portStreams. |
| endPage | int | Страница заканчивается в документах portStreams. |
| outputStream | java.io.OutputStream | Выходной поток PDF. |

**Возвращает:**
boolean - True для успеха или false.
### append(String inputFile, String portFile, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
```
public abstract boolean append(String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| portFile | java.lang.String | Страницы из файла PDF. |
| startPage | int | Страница начинается в portFile. |
| endPage | int | Страница заканчивается в portFile. |
| outputFile | java.lang.String | Выходной PDF-документ. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String---int-int-java.lang.String-}
```
public abstract boolean append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


Добавляет страницы, выбранные из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", new string[]
 { "file1.pdf", "file2.pdf" }, 3, 5, "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| portFiles | java.lang.String[] | Документы, из которых нужно скопировать страницы. |
| startPage | int | Страница начинается в документах portFiles. |
| endPage | int | Страница заканчивается в документах portFiles. |
| outputFile | java.lang.String | Выходной PDF-документ. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(IDocument[] src, IDocument dest) {#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-}
```
public abstract boolean concatenate(IDocument[] src, IDocument dest)
```


Объединяет документы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [IDocument\[\]](../../com.aspose.pdf/idocument) | Массив исходных документов. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Документ назначения. |

**Возвращает:**
boolean — Истинно, если конкатенация прошла успешно.
### concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public abstract boolean concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)
```


Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 InputStream blank = new FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[]
 { stream1, stream2, blank }, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | Первый Pdf-поток. |
| secInputStream | java.io.InputStream | Второй поток PDF. |
| blankPageStream | java.io.InputStream | Поток Pdf с пустой страницей |
| outputStream | java.io.OutputStream | Выходной поток PDF. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public abstract boolean concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
```


Объединяет два файла.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(stream1, stream2, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | Поток первого файла. |
| secInputStream | java.io.InputStream | Поток второго файла. |
| outputStream | java.io.OutputStream | Поток, в котором будет храниться файл результатов. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(InputStream[] inputStream, OutputStream outputStream) {#concatenate-java.io.InputStream---java.io.OutputStream-}
```
public abstract boolean concatenate(InputStream[] inputStream, OutputStream outputStream)
```


Объединяет файлы

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[]
 { stream1, stream2 }, outstream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | Массив потоков для объединения. |
| outputStream | java.io.OutputStream | Поток, в котором будет храниться файл результатов. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(String firstInputFile, String secInputFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract boolean concatenate(String firstInputFile, String secInputFile, String outputFile)
```


Объединяет два файла.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | java.lang.String | Первый файл для объединения. |
| secInputFile | java.lang.String | Второй файл для объединения. |
| outputFile | java.lang.String | Выходной файл. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract boolean concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)
```


Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | java.lang.String | Первый файл. |
| secInputFile | java.lang.String | Второй файл. |
| blankPageFile | java.lang.String | PDF-файл с пустой страницей. |
| outputFile | java.lang.String | Файл результата. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### concatenate(String[] inputFiles, String outputFile) {#concatenate-java.lang.String---java.lang.String-}
```
public abstract boolean concatenate(String[] inputFiles, String outputFile)
```


Объединяет файлы в один файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.concatenate(new string[]
 { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Массив файлов для объединения. |
| outputFile | java.lang.String | Имя выходного файла. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#delete-java.io.InputStream-int---java.io.OutputStream-}
```
public abstract boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.Delete(inputStream, new int[]
 { 2, 3 }, outputStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputStream | java.io.OutputStream | Выходной файловый поток. |

**Возвращает:**
boolean - True для успеха или false.
### delete(String inputFile, int[] pageNumber, String outputFile) {#delete-java.lang.String-int---java.lang.String-}
```
public abstract boolean delete(String inputFile, int[] pageNumber, String outputFile)
```


Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.delete("input.pdf", new int[]
 { 2, 3 }, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к входному файлу. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputFile | java.lang.String | Путь к выходному файлу. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
public abstract boolean extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
```


Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, 1, 3, 6, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| startPage | int | Номер стартовой страницы. |
| endPage | int | Конечный номер страницы. |
| outputStream | java.io.OutputStream | Выходной файл Pdf Stream. |

**Возвращает:**
boolean - True для успеха или false.
### extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#extract-java.io.InputStream-int---java.io.OutputStream-}
```
public abstract boolean extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, new int[]
 { 3, 5, 8 }, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной файл Поток. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputStream | java.io.OutputStream | Выходной файловый поток. |

**Возвращает:**
boolean - True для успеха или false.
### extract(String inputFile, int startPage, int endPage, String outputFile) {#extract-java.lang.String-int-int-java.lang.String-}
```
public abstract boolean extract(String inputFile, int startPage, int endPage, String outputFile)
```


Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.extract("input.pdf", 3, 7, "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь к файлу PDF. |
| startPage | int | Номер стартовой страницы. |
| endPage | int | Конечный номер страницы. |
| outputFile | java.lang.String | Выходной путь к файлу Pdf. |

**Возвращает:**
boolean - True для успеха или false.
### extract(String inputFile, int[] pageNumber, String outputFile) {#extract-java.lang.String-int---java.lang.String-}
```
public abstract boolean extract(String inputFile, int[] pageNumber, String outputFile)
```


Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.extract("input.pdf", new int[]
 { 3, 5, 7 }, "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к входному файлу. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputFile | java.lang.String | Путь к выходному файлу. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### getAllowConcatenateExceptions() {#getAllowConcatenateExceptions--}
```
public abstract boolean getAllowConcatenateExceptions()
```


Разрешить объединение исключений

**Возвращает:**
boolean - логическое значение
### getAttachmentName() {#getAttachmentName--}
```
public abstract String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение.

**Возвращает:**
java.lang.String — строковое значение
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
public abstract boolean getCloseConcatenatedStreams()
```


Если установлено значение true, потоки закрываются после операции.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setCloseConcatenatedStreams(true);
```

**Возвращает:**
boolean - логическое значение
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


Получает способ хранения содержимого при сохранении результата операции в объекте HttpServletResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
int — элемент ContentDisposition
### getConversionLog() {#getConversionLog--}
```
public abstract String getConversionLog()
```


Получает журнал процесса преобразования.

**Возвращает:**
java.lang.String — строковое значение
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
public abstract int getCorruptedFileAction()
```


Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted.

**Возвращает:**
int — элемент ConcatenateCorruptedFileAction
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
public abstract boolean getIncrementalUpdates()
```


Если true, во время конкатенации выполняются добавочные обновления.

**Возвращает:**
boolean - логическое значение
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
public abstract boolean getKeepFieldsUnique()
```


Если true, то имена полей будут уникальными при объединении форм. К именам полей будут добавлены суффиксы, шаблон суффикса можно указать в свойстве UniqueSuffix.

**Возвращает:**
boolean - логическое значение
### getLastException() {#getLastException--}
```
public abstract Exception getLastException()
```


Получает последнее произошедшее исключение. Может использоваться для проверки причины сбоя, когда AllowconcatenateExceptions = false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setAllowConcatenateExceptions(false);
 if (!pfe.concatenate("", "", ""))
 {
     System.out.println("");
     if (pfe.getLastException() != null)
     {
 	System.out.println(pfe.getLastException().getMessage());
 	if (pfe.getLastException().getCause() != null)
 	    System.out.println(pfe.getLastException().getCause().getMessage());
     }
 }
```

**Возвращает:**
java.lang.Exception — объект java.lang.Exception
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
public abstract boolean getMergeDuplicateLayers()
```


Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. В противном случае слои с одинаковыми именами будут сохранены в результирующем документе как разные слои.

**Возвращает:**
boolean - логическое значение
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
public abstract boolean getMergeDuplicateOutlines()
```


Если true, повторяющиеся контуры объединяются.

**Возвращает:**
boolean - логическое значение
### getOwnerPassword() {#getOwnerPassword--}
```
public abstract String getOwnerPassword()
```


Получает пароль владельца, если исходный входной файл Pdf зашифрован. Это свойство еще не реализовано.

**Возвращает:**
java.lang.String — строковое значение
### getPreserveUserRights() {#getPreserveUserRights--}
```
public abstract boolean getPreserveUserRights()
```


Если true, права пользователя первого документа применяются к объединенному документу. Права пользователя на все остальные документы игнорируются.

**Возвращает:**
boolean - логическое значение
### getRemoveSignatures() {#getRemoveSignatures--}
```
public abstract boolean getRemoveSignatures()
```


Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи.

**Возвращает:**
boolean - логическое значение
### getSaveOptions() {#getSaveOptions--}
```
public abstract SaveOptions getSaveOptions()
```


Получает или задает параметры сохранения, когда результат сохраняется как HttpServletResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - Объект SaveOptions
### getUniqueSuffix() {#getUniqueSuffix--}
```
public abstract String getUniqueSuffix()
```


Получить формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" будут имена: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.

**Возвращает:**
java.lang.String — строковое значение
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
public abstract boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Вставляет страницы из другого файла во входной файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток файла PDF. |
| insertLocation | int | Вставить позицию во входной файл. |
| portStream | java.io.InputStream | Поток файла Pdf для страниц. |
| startPage | int | С какой страницы начать. |
| endPage | int | На какой странице закончить. |
| outputStream | java.io.OutputStream | Выходной поток. |

**Возвращает:**
boolean - True для успеха или false.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
public abstract boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


Вставляет страницы из другого файла во входной файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 InputStream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, new int[]
 { 3, 4, 5 }, outStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток файла PDF. |
| insertLocation | int | Вставить позицию во входной файл. |
| portStream | java.io.InputStream | Поток файла Pdf для страниц. |
| pageNumber | int[] | Номер страницы портированного файла portFile. |
| outputStream | java.io.OutputStream | Выходной поток. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
public abstract boolean insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


Вставляет страницы из другого файла в файл Pdf в позицию.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| insertLocation | int | Позиция во входном файле. |
| portFile | java.lang.String | Файл переноса в формате PDF. |
| startPage | int | Начальная позиция в portFile. |
| endPage | int | Конечная позиция в portFile. |
| outputFile | java.lang.String | Выходной PDF-файл. |

**Возвращает:**
boolean - True для успеха или false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
public abstract boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


Вставляет страницы из другого файла во входной файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "out.pdf", 2, 6, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл PDF. |
| insertLocation | int | Вставить позицию во входной файл. |
| portFile | java.lang.String | Страницы из файла PDF. |
| pageNumber | int[] | Номер страницы портированного файла portFile. |
| outputFile | java.lang.String | Выходной PDF-файл. |

**Возвращает:**
boolean - True для успеха или false.
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream)
```


Создает буклет из InputStream в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной pdf-поток. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


Делает буклет из входного потока и сохраняет результат в выходной поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)
```


Создает буклет из firstInputStream в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |
| leftPages | int[] | Левые страницы. |
| rightPages | int[] | Правильные страницы. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
public abstract boolean makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)
```


Создает настраиваемый буклет из firstInputStream в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| outputStream | java.io.OutputStream | выходной pdf-поток. |
| leftPages | int[] | Левые страницы. |
| rightPages | int[] | Правильные страницы. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
public abstract boolean makeBooklet(String inputFile, String outputFile)
```


Делает буклет из входного файла в выходной файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
public abstract boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize)
```


Делает буклет из inputFile в outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean — Истинно, если операция прошла успешно.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
public abstract boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)
```


Создает настраиваемый буклет из файла firstInputFile в файл outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |
| leftPages | int[] | Левые страницы. |
| rightPages | int[] | Правильные страницы. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
public abstract boolean makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)
```


Создает настраиваемый буклет из файла firstInputFile в файл outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Входной файл. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| leftPages | int[] | Левые страницы буклета. |
| rightPages | int[] | Правые страницы буклета. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public abstract boolean makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
```


Создает документ N-Up из двух входных потоков PDF в outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream input1 = new FileInputStream("input1.pdf");
 InputStream input2 = new FileInputStream("input2.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(input1, input2, output);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | первый входной поток. |
| secondInputStream | java.io.InputStream | второй входной поток. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
public abstract boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)
```


Создает документ N-Up из входного потока и сохраняет результат в выходной поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной pdf-поток. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
public abstract boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


Создает документ N-Up из первого входного потока в выходной поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной pdf-поток. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
public abstract boolean makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


Создает документ N-Up из нескольких входных потоков PDF в outputStream. Каждая страница outputStream будет содержать несколько страниц, которые объединяются со страницами во входных потоках с тем же номером страницы. Многостраничные страницы складываются горизонтально, если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("input1.pdf");
 InputStream stream2 = new FileInputStream("input2.pdf");
 InputStream stream3 = new FileInputStream("input3.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(new Stream[]
 { stream1, stream2, stream3 }, output, false);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | Входные потоки Pdf. |
| outputStream | java.io.OutputStream | Выходной pdf-поток. |
| isSidewise | boolean | Нагроможденный путь, верный для горизонтального и плоский для вертикального |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public abstract boolean makeNUp(String inputFile, String outputFile, int x, int y)
```


Создает документ N-Up из firstInputFile в outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
public abstract boolean makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


Создает документ N-Up из входного файла в outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите путь и имя файла PDF. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| x | int | Число столбцов. |
| y | int | Количество рядов. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы выходного pdf-файла. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
public abstract boolean makeNUp(String firstInputFile, String secondInputFile, String outputFile)
```


Создает документ N-Up из двух входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать две страницы, одна страница из первого входного файла, а другая из второго входного файла. Две страницы сложены горизонтально.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstInputFile | java.lang.String | первый входной файл. |
| secondInputFile | java.lang.String | второй входной файл. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
public abstract boolean makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)
```


Создает документ N-Up из нескольких входных PDF-файлов в outputFile. Каждая страница outputFile будет содержать несколько страниц, которые объединяются со страницами во входных файлах с тем же номером страницы. Несколько страниц складываются горизонтально, если isSidewise имеет значение true, и складываются вертикально, если isSidewise имеет значение false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp(new string[]
 { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Входные PDF-файлы. |
| outputFile | java.lang.String | Выходной путь и имя файла PDF. |
| isSidewise | boolean | Сложенный образ, верный для горизонтали и флаш для вертикали. |

**Возвращает:**
boolean - boolean - True для успеха или false.
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public abstract boolean resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents(src, dest,
 // resize all pages of document
 	null,
 	// new contents width = 200
 	200,
 	// new contents height = 300
 	300);
 // rest area of page will be empty
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

**Возвращает:**
boolean - True, если изменение размера прошло успешно.
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public abstract boolean resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Новый размер содержимого указывается в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf",
 // resize all pages of document
 	null,
 	// new contents width = 200
 	200,
 	// new contents height = 300
 	300);
 // rest area of page will be empty
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в пространственных единицах по умолчанию. |
| newHeight | double | Новая высота содержимого страницы в пространственных единицах по умолчанию. |

**Возвращает:**
boolean - True, если изменение размера прошло успешно.
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public abstract boolean resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Размер нового содержимого указывается в процентах.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct(src, dest,
 // resize all pages of document
 	null,
 	// new contents width = 60% of initial size
 	60,
 	// new contents height = 60% of initial size
 	60);
 // Rest area of page will be empty (page margins). Size of left and right
 // margins is (100% - 60%) / 2 = 20%
 // The same for top and bottom margins.
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.io.InputStream | Поток, содержащий исходный документ. |
| destination | java.io.OutputStream | Поток, где результирующий документ будет сохранен. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в процентах. |
| newHeight | double | Новая высота содержимого страницы в процентах. |

**Возвращает:**
boolean - True, если изменение размера прошло успешно.
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
public abstract boolean resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)
```


Изменяет размер содержимого страниц документа. Уменьшает содержимое страницы и добавляет поля. Размер нового содержимого указывается в процентах.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContentsPct("input.pdf", "output.pdf",
 // resize all pages of document
 	null,
 	// new contents width = 60% of initial size
 	60,
 	// new contents height = 60% of initial size
 	60);
 // Rest area of page will be empty (page margins). Size of left and right
 // margins is (100% - 60%) / 2 = 20%
 // The same for top and bottom margins.
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | java.lang.String | Путь к исходному документу. |
| destination | java.lang.String | Путь, по которому будет сохранен результирующий документ. |
| pages | int[] | Массив индексов страниц. Если null, то будут обработаны все страницы документа. |
| newWidth | double | Новая ширина содержимого страницы в процентах. |
| newHeight | double | Новая высота содержимого страницы в процентах. |

**Возвращает:**
boolean - true, если изменение размера прошло успешно.
### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public abstract void setAllowConcatenateExceptions(boolean value)
```


Если установлено значение true, при возникновении ошибки генерируются исключения. В противном случае исключение не генерируется, а методы возвращают false в случае сбоя.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setAllowConcatenatedException(true);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName(String value)
```


Задает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | строковое значение |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public abstract void setCloseConcatenatedStreams(boolean value)
```


Если установлено значение true, потоки закрываются после операции.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.setCloseConcatenatedStreams(true);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition(int value)
```


Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpServletResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ContentDisposition |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public abstract void setConvertTo(PdfFormat value)
```


Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | Элемент PdfFormat |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public abstract void setCorruptedFileAction(int value)
```


Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ConcatenateCorruptedFileAction |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public abstract void setIncrementalUpdates(boolean value)
```


Если true, во время конкатенации выполняются добавочные обновления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public abstract void setKeepFieldsUnique(boolean value)
```


Если true, то имена полей будут уникальными при объединении форм. К именам полей будут добавлены суффиксы, шаблон суффикса можно указать в свойстве UniqueSuffix.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public abstract void setMergeDuplicateLayers(boolean value)
```


Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. В противном случае слои с одинаковыми именами будут сохранены в результирующем документе как разные слои.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public abstract void setMergeDuplicateOutlines(boolean value)
```


Если true, повторяющиеся контуры объединяются.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public abstract void setOwnerPassword(String value)
```


Устанавливает пароль владельца, если исходный входной файл Pdf зашифрован. Это свойство еще не реализовано.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | строковое значение |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public abstract void setPreserveUserRights(boolean value)
```


Если true, права пользователя первого документа применяются к объединенному документу. Права пользователя на все остальные документы игнорируются.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public abstract void setRemoveSignatures(boolean value)
```


Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


Задает параметры сохранения, когда результат сохраняется как HttpServletResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | Объект SaveOptions |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public abstract void setUniqueSuffix(String value)
```


Установите формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" будут имена: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.

--------------------

```
PdfFileEditor ed = new PdfFileEditor();
 ed.setUniqueSuffix("_%NUM%");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | строковое значение |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public abstract boolean splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)
```


Разбивается от начала до указанного места и сохраняет переднюю часть в выходном потоке.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitFromFirst(sourceStream, 5, outStream);
```

--------------------

Потоки НЕ закрываются после этой операции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Исходный файл Pdf Stream. |
| location | int | Точка разделения. |
| outputStream | java.io.OutputStream | Выходной файл Поток. |

**Возвращает:**
boolean - True для успеха или false.
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public abstract boolean splitFromFirst(String inputFile, int location, String outputFile)
```


Разбивает файл Pdf с первой страницы в указанное место и сохраняет переднюю часть как новый файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitFromFirst("input.pdf", 5, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Исходный PDF-файл. |
| location | int | Точка разделения. |
| outputFile | java.lang.String | Выходной PDF-файл. |

**Возвращает:**
boolean - True для успеха или false.
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
public abstract ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] numberOfPage)
```


Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| numberOfPage | int[][] | Начальная страница и конечная страница каждого документа. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Выходные потоки PDF, каждый поток буферизует документ PDF.
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
public abstract ByteArrayInputStream[] splitToBulks(String inputFile, int[][] numberOfPage)
```


Разбивает файл Pdf на несколько документов. Документы могут быть одностраничными или многостраничными.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите PDF-файл. |
| numberOfPage | int[][] | Массив, содержащий массив двойных элементов, являющийся начальной и конечной страницами документа. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Выходные потоки PDF, каждый поток буферизует документ PDF.
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
public abstract boolean splitToEnd(InputStream inputStream, int location, OutputStream outputStream)
```


Разбивается из указанного места и сохраняет заднюю часть как новый файловый поток.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitToEnd(sourceStream, 5, outStream);
```

--------------------

Потоки НЕ закрываются после этой операции, если не указано значение CloseConcatedStreams.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Исходный файл Pdf Stream. |
| location | int | Позиция разделения. |
| outputStream | java.io.OutputStream | Выходной файл Pdf Stream. |

**Возвращает:**
boolean - True для успеха или false.
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public abstract boolean splitToEnd(String inputFile, int location, String outputFile)
```


Отделяется от местоположения и сохраняет заднюю часть как новый файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitToEnd("input.pdf", 5, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Исходный PDF-файл. |
| location | int | Позиция разделения. |
| outputFile | java.lang.String | Выходной путь к файлу Pdf. |

**Возвращает:**
boolean - True для успеха или false.
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
public abstract ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


Разбивает файл Pdf на одностраничные документы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |

**Возвращает:**
java.io.ByteArrayInputStream[] - ByteArrayInputStream[] множество
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public abstract void splitToPages(InputStream inputStream, String fileNameTemplate)
```


Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. Путь задается полем имени поля шаблона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток исходного документа. |
| fileNameTemplate | java.lang.String | Шаблон результирующего имени файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указано c:/dir/page%NUM%.pdf, результирующие файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т. д. |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
public abstract ByteArrayInputStream[] splitToPages(String inputFile)
```


Разбивает файл PDF на одностраничные документы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите имя файла PDF. |

**Возвращает:**
java.io.ByteArrayInputStream[] - Выходные потоки PDF, каждый поток буферизует одностраничный документ PDF.
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public abstract void splitToPages(String inputFile, String fileNameTemplate)
```


Разделите файл Pdf на одностраничные документы и сохраните его по указанному пути. Путь задается полем имени поля шаблона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите имя файла. |
| fileNameTemplate | java.lang.String | Шаблон результирующего имени файла. Должен содержать %NUM%, который заменяется номером страницы. Например, если указано c:/dir/page%NUM%.pdf, результирующие файлы будут иметь следующие имена: c:/dir/page1.pdf, c:/dir/page2.pdf и т. д. |
