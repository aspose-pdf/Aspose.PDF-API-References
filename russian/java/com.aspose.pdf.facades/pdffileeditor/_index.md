---
title: PdfFileEditor
second_title: Aspose.PDF для справки по Java API
description: Реализует операции с конкатенацией файлов PDF, разделением, извлечением страниц, созданием буклетов и т. д.
type: docs
weight: 39
url: /ru/java/com.aspose.pdf.facades/pdffileeditor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, com.aspose.pdf.facades.APdfFileEditor

**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IPdfFileEditor](../../com.aspose.pdf.facades/ipdffileeditor)
```
public final class PdfFileEditor extends APdfFileEditor implements IPdfFileEditor
```

Реализует операции с файлом PDF: объединение, разбиение, извлечение страниц, создание буклета и др.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileEditor()](#PdfFileEditor--) | Конструктор PdfFileEditor. |
## Методы

| Метод | Описание |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | Изменяет размер содержимого страницы и добавляет указанные поля. |
| [addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
| [addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Добавляет разрывы страниц на страницы документа. |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Извлекает страницы из входного файла, сохраняет как новый файл Pdf. |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf. |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | Извлекает страницы из входного файла, сохраняет как новый файл Pdf. |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF. |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | Если установлено значение true, при возникновении ошибки генерируются исключения. |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение. |
| [getClass()](#getClass--) |  |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | Если установлено значение true, потоки закрываются после операции. |
| [getConcatenationPacketSize()](#getConcatenationPacketSize--) | Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true. |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpServletResponse. |
| [getConversionLog()](#getConversionLog--) | Получает журнал процесса преобразования. |
| [getCopyLogicalStructure()](#getCopyLogicalStructure--) | Если true, то логическая структура файла копируется при выполнении конкатенации. |
| [getCopyOutlines()](#getCopyOutlines--) | Если true, контуры будут скопированы. |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. |
| [getCorruptedItems()](#getCorruptedItems--) | Массив проблем, возникших при выполнении конкатенации. |
| [getCustomProgressConcatenationHandler()](#getCustomProgressConcatenationHandler--) | Представление внутреннего обработчика событий прогресса, который работает во время конкатенации и транслирует события конкатенации внутренних стадий конкатенации во внешний код заказчика. |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | Если true, во время конкатенации выполняются добавочные обновления. |
| [getKeepActions()](#getKeepActions--) | Если правда действия будут скопированы из исходных документов. |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | Если true, то имена полей будут уникальными при объединении форм. |
| [getLastException()](#getLastException--) | Получает последнее произошедшее исключение. |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | Необязательное содержимое объединенных документов с одинаковыми именами будет объединено в один слой результирующего документа, если это свойство истинно. |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | Если true, повторяющиеся контуры объединяются. |
| [getOptimizeSize()](#getOptimizeSize--) | Получает или устанавливает флаг оптимизации. |
| [getOwnerPassword()](#getOwnerPassword--) | Получает пароль владельца, если исходный входной файл Pdf зашифрован. |
| [getPreserveUserRights()](#getPreserveUserRights--) | Если true, права пользователя первого документа применяются к объединенному документу. |
| [getRemoveSignatures()](#getRemoveSignatures--) | Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [getSaveOptions()](#getSaveOptions--) | Получает или задает параметры сохранения, когда результат сохраняется как HttpServletResponse. |
| [getUniqueSuffix()](#getUniqueSuffix--) | Получить формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. |
| [hashCode()](#hashCode--) |  |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Вставляет страницы из другого файла в файл Pdf в позицию. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | Вставляет страницы из другого файла во входной файл Pdf. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [isUseDiskBuffer()](#isUseDiskBuffer--) | Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений. |
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
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размер содержимого страниц документа. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размер содержимого страниц в документе. |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | Изменяет размер содержимого страниц документа. |
| [resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Изменяет размеры страниц документа. |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | Если установлено значение true, при возникновении ошибки генерируются исключения. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение. |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | Если установлено значение true, потоки закрываются после операции. |
| [setConcatenationPacketSize(int value)](#setConcatenationPacketSize-int-) | Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpServletResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setCopyLogicalStructure(boolean value)](#setCopyLogicalStructure-boolean-) | Если true, то логическая структура файла копируется при выполнении конкатенации. |
| [setCopyOutlines(boolean value)](#setCopyOutlines-boolean-) | Если true, контуры будут скопированы. |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. |
| [setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Представление внутреннего обработчика событий прогресса, который работает во время конкатенации и транслирует события конкатенации внутренних стадий конкатенации во внешний код заказчика. |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | Если true, во время конкатенации выполняются добавочные обновления. |
| [setKeepActions(boolean value)](#setKeepActions-boolean-) | Если правда действия будут скопированы из исходных документов. |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | Если true, то имена полей будут уникальными при объединении форм. |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) |  |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | Если true, повторяющиеся контуры объединяются. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Получает или устанавливает флаг оптимизации. |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Устанавливает пароль владельца, если исходный входной файл Pdf зашифрован. |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | Если true, права пользователя первого документа применяются к объединенному документу. |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | Если true, все подписи будут удалены с полей (поля останутся); в противном случае вы можете получить недействительные подписи. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Иногда PDF-файлы содержат фоновые изображения (страниц или ячеек таблицы), составленные из нескольких одинаковых мозаичных фоновых изображений, расположенных рядом друг с другом. |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | Установите формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. |
| [setUseDiskBuffer(boolean value)](#setUseDiskBuffer-boolean-) | Если используется этот параметр, то целевой документ будет периодически сохраняться на диске, и к нему будет применяться дальнейшая конкатенация в виде добавочных обновлений. |
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
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileEditor() {#PdfFileEditor--}
```
public PdfFileEditor()
```


Конструктор PdfFileEditor.

### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InmputStream src = new FileInputStream("input.pdf");
  OutputStream dest = new FileInputStream("output.pdf");
  fileEditor.addMargins(src, dest, 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 10 units
      10, 
      //right margin is 5 units
      5, 
      //top margin is 5 units
      5, 
      //bottom margin is 5 units
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
public boolean addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указаны в пространственных единицах по умолчанию.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMargins("input.pdf", "output.pdf", 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 10 units
      10, 
      //right margin is 5 units
      5, 
      //top margin is 5 units
      5, 
      //bottom margin is 5 units
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
public boolean addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в процентах от исходного размера страницы.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InmputStream src = new FileInputStream("input.pdf");
  OutputStream dest = new FileInputStream("output.pdf");
  fileEditor.addMarginsPct(src, dest, 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 15% of page width 
      15, 
      //right margin is 10% of page width
      10, 
      //top margin is 20% of page width
      20, 
      //bottom margin is 5% of page width
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
boolean - логическое значение
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Изменяет размер содержимого страницы и добавляет указанные поля. Поля указываются в процентах от исходного размера страницы.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMarginsPct("input.pdf", "output.pdf", 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 15% of page width 
      15, 
      //right margin is 10% of page width
      10, 
      //top margin is 20% of page width
      20, 
      //bottom margin is 5% of page width
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
### addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [Document](../../com.aspose.pdf/document) | Исходный документ. |
| dest | [Document](../../com.aspose.pdf/document) | Документ назначения. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объектов PageBreak, описывающих места разрывов страниц. |

### addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [IDocument](../../com.aspose.pdf/idocument) | Исходный документ. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Документ назначения. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объектов PageBreak, описывающих места разрывов страниц. |

### addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.io.InputStream | Источник, который содержит исходный документ. |
| dest | java.io.OutputStream | Источник, в котором будет сохранен целевой документ. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объекта PageBreak, описывающего страницы и места, где будет добавлен разрыв страницы. |

### addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Добавляет разрывы страниц на страницы документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.lang.String | Путь к исходному документу. |
| dest | java.lang.String | Путь к целевому документу. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Массив объекта PageBreak, описывающего страницы и места, где будет добавлен разрыв страницы. |

### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Добавляет страницы, выбранные из portStream в диапазоне от startPage до endPage, в portStream в конце firstInputStream.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1,  3, 5, outstream);
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
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


Добавляет страницы, выбранные из массива документов в portStreams. Результирующий документ включает страницы firstInputFile и всех документов portStreams в диапазоне от startPage до endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OtputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream);
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
public boolean append(String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


Добавляет страницы, выбранные из portFile в диапазоне от startPage до endPage, в portFile в конце firstInputFile.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
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
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


Добавляет страницы, выбранные из документов portFiles. Результирующий документ включает firstInputFile и все страницы документов portFiles в диапазоне от startPage до endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
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
public boolean concatenate(IDocument[] src, IDocument dest)
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
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)
```


Объединяет два документа Pdf в новый документ Pdf со страницами по-разному и заполняет пустые места пустыми страницами. например: document1 имеет 5 страниц: p1, p2, p3, p4, p5. document2 имеет 3 страницы: p1', p2', p3'. Объединение двух документов Pdf создаст результирующий документ со страницами: p1, p1', p2, p2', p3, p3', p4, пустая страница, p5, пустая страница.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 InputStream blank = new FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream);
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
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
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
public boolean concatenate(InputStream[] inputStream, OutputStream outputStream)
```


Объединяет файлы

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream);
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
public boolean concatenate(String firstInputFile, String secInputFile, String outputFile)
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
public boolean concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)
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
public boolean concatenate(String[] inputFiles, String outputFile)
```


Объединяет файлы в один файл.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate(new String[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
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
public boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
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
public boolean delete(String inputFile, int[] pageNumber, String outputFile)
```


Удаляет страницы, заданные числовым массивом, из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Путь к входному файлу. |
| pageNumber | int[] | Индекс страницы из входного файла. |
| outputFile | java.lang.String | Путь к выходному файлу. |

**Возвращает:**
boolean - Истинно, если операция прошла успешно.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
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
public boolean extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Извлекает страницы, указанные числовым массивом, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
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
public boolean extract(String inputFile, int startPage, int endPage, String outputFile)
```


Извлекает страницы из входного файла, сохраняет как новый файл Pdf.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.Extract("input.pdf", 3, 7, "output.pdf");
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
public boolean extract(String inputFile, int[] pageNumber, String outputFile)
```


Извлекает страницы, указанные числовым массивом, сохраняет как новый файл PDF.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
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
public boolean getAllowConcatenateExceptions()
```


Если установлено значение true, при возникновении ошибки генерируются исключения. В противном случае исключение не генерируется, а методы возвращают false в случае сбоя.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException (true);
```

**Возвращает:**
boolean - логическое значение
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpServletResponse как вложение.

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```


Если установлено значение true, потоки закрываются после операции.

**Возвращает:**
boolean - логическое значение
### getConcatenationPacketSize() {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```


Количество документов, объединенных до того, как во время объединения было выполнено новое добавочное обновление, если для параметра UseDiskBuffer установлено значение true.

**Возвращает:**
интервал - целочисленное значение
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


Получает способ хранения содержимого при сохранении результата операции в объекте HttpServletResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
int — элемент ContentDisposition
### getConversionLog() {#getConversionLog--}
```
public String getConversionLog()
```


Получает журнал процесса преобразования.

**Возвращает:**
java.lang.String
### getCopyLogicalStructure() {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```


Если true, то логическая структура файла копируется при выполнении конкатенации.

**Возвращает:**
boolean - логическое значение
### getCopyOutlines() {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```


Если true, контуры будут скопированы.

**Возвращает:**
boolean - логическое значение
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```


Это свойство определяет поведение, когда процесс объединения встречает поврежденный файл. Возможные значения: StopWithError и ConcatenateIgnoringCorrupted.

**Возвращает:**
int — элемент ConcatenateCorruptedFileAction
### getCorruptedItems() {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem[] getCorruptedItems()
```


Массив проблем, возникших при выполнении конкатенации. Для каждого поврежденного документа, переданного в функцию Concatenate(), создается новая запись CorruptedItem. Это свойство можно использовать, только если CorruptedFileAction имеет значение ConcatenateIgnoringCorrupted.

--------------------

```
//concatenate documents and show information about corrupted documents
	      PdfFileEditor pfe = new PdfFileEditor();
	      pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted);
	      ```
if (pfe.getCorruptedItems().length >0)
```
	      {
	        for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems())
	        {
	           System.out.println(item.getIndex()+ " reason: " + item.getException());
	        }
	      }
```

**Returns:**
com.aspose.pdf.facades.PdfFileEditor.CorruptedItem[] - array of PdfFileEditor.CorruptedItem
### getCustomProgressConcatenationHandler() {#getCustomProgressConcatenationHandler--}
```
общедоступный PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```


Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. This field uses different types of events.

Simple concatenation has 8 events :
1)AllPagesCopied
2)DocumentEmbeddedFiles
3)DocumentForms
4)DocumentOutlines
5)DocumentJavaScript
6)DocumentLogicalStructure
7)DocumentConcated.
8)TotalPercentage.

Parallel concatenation informs about every page concatenation and has 3 events:
1)PageConcatenated
2)BlankPage
3)TotalPercentage

**Returns:**
[ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) - ConcatenationProgressHandler instance
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
публичное логическое значение getIncrementalUpdates()
```


If true, incremental updates are made during concatenation.

**Returns:**
boolean - boolean value
### getKeepActions() {#getKeepActions--}
```
публичный окончательный логический метод getKeepActions()
```


If true actions will be copied from source documents. Defaulkt value : true.

**Returns:**
boolean - boolean value
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
публичное логическое значение getKeepFieldsUnique()
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Returns:**
boolean - boolean value
### getLastException() {#getLastException--}
```
публичный окончательный RuntimeException getLastException()
```


Gets last occurred exception. May be used to check the reason of failure.

```
PdfFileEditor pfe = новый PdfFileEditor();
  если (!pfe.tryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
  {
     System.out.println("Произошла ошибка:");
     если (pfe.getLastException() != ноль)
     {
         System.out.println((pfe.getLastException().getMessage());
         если (pfe.getLastException().getInnerException() != ноль)
             System.out.println((pfe.getLastException().getInnerException().getMessage());
     }
  }
```

**Returns:**
java.lang.RuntimeException
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
публичное логическое значение getMergeDuplicateLayers()
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Returns:**
boolean
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
публичное логическое значение getMergeDuplicateOutlines()
```


If true, duplicate outlines are merged.

**Returns:**
boolean - boolean value
### getOptimizeSize() {#getOptimizeSize--}
```
общественное логическое значение getOptimizeSize()
```


Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean - boolean value
### getOwnerPassword() {#getOwnerPassword--}
```
публичная строка getOwnerPassword()
```


Gets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Returns:**
java.lang.String - String value
### getPreserveUserRights() {#getPreserveUserRights--}
```
публичное логическое значение getPreserveUserRights()
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Returns:**
boolean - boolean value
### getRemoveSignatures() {#getRemoveSignatures--}
```
публичный окончательный логический метод getRemoveSignatures()
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Returns:**
boolean - boolean value
### getSaveOptions() {#getSaveOptions--}
```
публичные SaveOptions getSaveOptions()
```


Gets or sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getUniqueSuffix() {#getUniqueSuffix--}
```
публичная строка getUniqueSuffix()
```


Get format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
общедоступный собственный int hashCode()
```




**Returns:**
int
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
общедоступная логическая вставка (InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 исходящий поток sourceStream = новый FileInputStream ("file1.pdf");
 outstream вставленный поток = новый FileInputStream ("file2.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.insert (исходный поток, 1, вставленный поток, 2, 6, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| startPage | int | From which page to start. |
| endPage | int | To which page to end. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True for success, or false.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
общедоступная логическая вставка (InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 исходящий поток sourceStream = новый FileInputStream ("file1.pdf");
 outstream вставленный поток = новый FileInputStream ("file2.pdf");
 OutputStream outStream = новый FileoutputStream("out.pdf");
 pfe.Insert (исходный поток, 1, вставленный поток, новый интервал[] { 3, 4, 5}, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True if operation was succeeded.
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
общедоступная логическая вставка (String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


Inserts pages from an other file into the Pdf file at a position.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Position in input file. |
| portFile | java.lang.String | The porting Pdf file. |
| startPage | int | Start position in portFile. |
| endPage | int | End position in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
публичная логическая вставка (String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 исходящий поток sourceStream = новый FileInputStream ("file1.pdf");
 outstream вставленный поток = новый FileInputStream ("file2.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.insert (исходный поток, 1, вставленный поток, 2, 6, исходящий поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Insert position in input file. |
| portFile | java.lang.String | Pages from the Pdf file. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
общественное логическое значение isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### isUseDiskBuffer() {#isUseDiskBuffer--}
```
публичный окончательный логический isUseDiskBuffer()
```


If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Returns:**
boolean - boolean value
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeBooklet (InputStream inputStream, OutputStream outputStream)
```


Makes booklet from the InputStream to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeBooklet (входной поток, выходной поток);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | output pdf stream. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet (InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


Makes booklet from the input stream and save result into output stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet (InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] левые страницы, интервал[] правые страницы)
```


Makes booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeBooklet (inputStream, outputStream, PageSize.A4, новый int[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
public boolean makeBooklet (InputStream inputStream, OutputStream outputStream, int[] левые страницы, интервал[] правые страницы)
```


Makes customized booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeBooklet (входной поток, выходной поток, новый интервал[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
public boolean makeBooklet (String inputFile, String outputFile)
```


Makes booklet from the input file to output file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet (String inputFile, String outputFile, PageSize pageSize)
```


Makes booklet from the inputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation is succeeded.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet (String inputFile, String outputFile, PageSize pageSize, int[] левые страницы, интервал[] правые страницы)
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, новый int[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
public boolean makeBooklet (String inputFile, String outputFile, int[] левые страницы, интервал[] правые страницы)
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", новый интервал[] { 2, 4, 6 }, новый интервал[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| leftPages | int[] | The left pages of the booklet. |
| rightPages | int[] | The right pages of the booklet. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeNUp (InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
```


Makes N-Up document from the two input PDF streams to outputStream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream input1 = новый FileInputStream("input1.pdf");
 InputStream input2 = новый FileInputStream("input2.pdf");
 OutputStream output = новый FileOutputStream("output.pdf");
 pfe.makeNUp (вход1, ввод2, вывод);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | first input stream. |
| secondInputStream | java.io.InputStream | second input stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
public boolean makeNUp (InputStream inputStream, OutputStream outputStream, int x, int y)
```


Makes N-Up document from the input stream and saves result into output stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.makeNUp (входной поток, выходной поток, 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp (InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


Makes N-Up document from the first input stream to output stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream inputStream = новый FileInputStream ("input.pdf");
 OutputStream outputStream = новый FileOutputStream("output.pdf");
 pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
общественное логическое значение makeNUp (InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream stream1 = новый FileInputStream("input1.pdf");
 InputStream stream2 = новый FileInputStream("input2.pdf");
 InputStream stream3 = новый FileInputStream("input3.pdf");
 OutputStream output = новый FileOutputStream("output.pdf");
 pfe.makeNUp (новый поток ввода[] {поток1, поток2, поток3}, вывод, ложь);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | Input Pdf streams. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public boolean makeNUp (String inputFile, String outputFile, int x, int y)
```


Makes N-Up document from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp (String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


Makes N-Up document from the input file to outputFile.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean makeNUp (строка firstInputFile, String secondInputFile, String outputFile)
```


Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | first input file. |
| secondInputFile | java.lang.String | second input file. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
общественное логическое значение makeNUp (строка[] inputFiles, String outputFile, boolean isSidewise)
```


Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.makeNUp (новая строка[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Input Pdf files. |
| outputFile | java.lang.String | Output pdf file path and name. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically. |

**Returns:**
boolean - boolean - True for success, or false.
### notify() {#notify--}
```
публичный окончательный родной void notify()
```




### notifyAll() {#notifyAll--}
```
public final родной void notifyAll()
```




### resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents (источник документа, параметры IPdfFileEditor.ContentsResizeParameters)
```


Resizes pages of document. Blank margins are added around of shrinked page.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 Источник документа = новый документ ("input.pdf");
 Адресат документа = новый документ();
 Параметры APdfFileEditor.ContentsResizeParameters = новый PdfFileEditor.ContentsResizeParameters(
     //левое поле = 10% ширины страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
     нулевой,
     //правое поле 10% страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     //верхнее поле = 10% от высоты
     PdfFileEditor.ContentsResizeValue.percents(10),
     // высота нового содержимого рассчитывается автоматически (аналогично ширине)
     нулевой,
     //нижнее поле 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, параметры);
 dest.save("output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Source document. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

### resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents (источник IDocument, int[] страницы, параметры IPdfFileEditor.ContentsResizeParameters)
```


Resizes pages of document. Blank margins are added around of shrinked page.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 Документ doc = новый документ ("input.pdf");
 Параметры PdfFileEditor.ContentsResizeParameters = новые параметры PdfFileEditor.ContentsResizeParameters(
     //левое поле = 10% ширины страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
     нулевой,
     //правое поле 10% страницы 
     PdfFileEditor.ContentsResizeValue.percents(10),
     //верхнее поле = 10% от высоты
     PdfFileEditor.ContentsResizeValue.percents(10),
     // высота нового содержимого рассчитывается автоматически (аналогично ширине)
     нулевой,
     //нижнее поле 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, новый интервал[] { 1, 2, 3}, параметры);
 doc.save("output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Source document. |
| pages | int[] | List of page indexes. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

### resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents (источник InputStream, назначение OutputStream, int[] страницы, параметры IPdfFileEditor.ContentsResizeParameters)
```


Resizes contents of pages of the document.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
	      InputStream src = новый FileInputStream("input.pdf");
	      OutputStream dest = new FileOutputStream("output.pdf");
	      Параметры PdfFileEditor.ContentsResizeParameters = новые параметры PdfFileEditor.ContentsResizeParameters(
	          //левое поле = 10% ширины страницы
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
	          нулевой,
	          //правое поле 10% страницы 
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //верхнее поле = 10% от высоты
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          // высота нового содержимого рассчитывается автоматически (аналогично ширине)
	          нулевой,
	          //нижнее поле 10%
	          PdfFileEditor.ContentsResizeValue.percents(10)
	             );
	      fileEditor.resizeContents (источник, пункт назначения, новый интервал[] { 1, 2, 3}, параметры);
	      назначение.закрыть();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream with source document. |
| destination | java.io.OutputStream | Stream with the destination document. |
| pages | int[] | Array of page indexes. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

**Returns:**
boolean - Returns true if success.
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContents (источник InputStream, назначение OutputStream, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream src = новый FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents (источник, пункт назначения, 
 //изменить размер всех страниц документа
 нулевой, 
 //ширина нового содержимого = 200
 200, 
 // высота нового содержимого = 300
 300);
 // остальная часть страницы будет пустой
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents (источник строки, назначение строки, int[] страницы, параметры IPdfFileEditor.ContentsResizeParameters)
```


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 Параметры PdfFileEditor.ContentsResizeParameters = новые параметры PdfFileEditor.ContentsResizeParameters(
     //левое поле = 10% ширины страницы
     PdfFileEditor.ContentsResizeValue.percents(10),
     // ширина нового содержимого рассчитывается автоматически как ширина - левое поле - правое поле (100% - 10% - 10% = 80%)
     нулевой,
     //правое поле 10% страницы 
     PdfFileEditor.ContentsResizeValue.percents(10),
     //верхнее поле = 10% от высоты
     PdfFileEditor.ContentsResizeValue.percents(10),
     // высота нового содержимого рассчитывается автоматически (аналогично ширине)
     нулевой,
     //нижнее поле 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents("input.pdf", "output.pdf", новый интервал[] { 1, 2,.3}, параметры);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Source document path. |
| destination | java.lang.String | Destination document path. |
| pages | int[] | Array of page indexes (page index starts from 1). |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Parameters of page resize. |

**Returns:**
boolean - trure if resize was successful.
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContents (источник строки, назначение строки, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf", 
 //изменить размер всех страниц документа
 нулевой, 
 //ширина нового содержимого = 200
 200, 
 // высота нового содержимого = 300
 300);
 // остальная часть страницы будет пустой
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContentsPct (источник InputStream, место назначения OutputStream, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 InputStream src = новый FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct (источник, пункт назначения, 
 //изменить размер всех страниц документа
 нулевой, 
 //ширина нового содержимого = 60% от исходного размера
 60, 
 //высота нового содержимого = 60% от исходного размера
 60);
 // Остальная часть страницы будет пустой (поля страницы). Размер левого и правого полей (100% - 60%) / 2 = 20%
 // То же самое для верхнего и нижнего полей.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - boolean value
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContentsPct (источник строки, пункт назначения строки, int[] страницы, двойная новая ширина, двойная новая высота)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = новый PdfFileEditor();
 fileEditor.resizePct("вход.pdf", "выход.pdf",
 //изменить размер всех страниц документа
 нулевой, 
 //ширина нового содержимого = 60% от исходного размера
 60, 
 //высота нового содержимого = 60% от исходного размера
 60);
 // Остальная часть страницы будет пустой (поля страницы). Размер левого и правого полей (100% - 60%) / 2 = 20%
 // То же самое для верхнего и нижнего полей.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - true if resize was successful.
### resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization (источник документа, параметры IPdfFileEditor.ContentsResizeParameters)
```


Resizes pages of document. Blank margins are added around of shrinked page. Normalization helps to avoid not grouped saved content state unexpected behavior.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Document instance |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters instance |

### resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization (источник IDocument, int[] страницы, параметры IPdfFileEditor.ContentsResizeParameters)
```


Resizes pages of document. Blank margins are added around of shrinked page. Normalization helps to avoid not grouped saved content state unexpected behavior.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Document instance |
| pages | int[] | array of int values |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters instance |

### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public void setAllowConcatenateExceptions (логическое значение)
```


If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
  pfe.setAllowConcatenateException (истина);
``` |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName (строковое значение)
```


Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams (логическое значение)
```


If set to true, streams are closed after operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
  pfe.setCloseConcatenatedStreams (истина);
``` |

### setConcatenationPacketSize(int value) {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize (целое значение)
```


Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition (целое значение)
```


Sets how content will be stored when result of operation is stored into HttpServletResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo (значение PdfFormat)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | int value |

### setCopyLogicalStructure(boolean value) {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure (логическое значение)
```


If true then logical structure of the file is copied when concatenation is performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCopyOutlines(boolean value) {#setCopyOutlines-boolean-}
```
public void setCopyOutlines (логическое значение)
```


If true then outlines will be copied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction (целое значение)
```


This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler) {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
```
public void setCustomProgressConcatenationHandler (PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)
```


Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. This field uses different types of events.

Simple concatenation has 8 events :
1)AllPagesCopied
2)DocumentEmbeddedFiles
3)DocumentForms
4)DocumentOutlines
5)DocumentJavaScript
6)DocumentLogicalStructure
7)DocumentConcated.
8)TotalPercentage.

Parallel concatenation informs about every page concatenation and has 3 events:
1)PageConcatenated
2)BlankPage
3)TotalPercentage

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProgressConcatenationHandler | [ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) | ConcatenationProgressHandler instance |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates (логическое значение)
```


If true, incremental updates are made during concatenation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepActions(boolean value) {#setKeepActions-boolean-}
```
public final void setKeepActions (логическое значение)
```


If true actions will be copied from source documents. Defaulkt value : true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique (логическое значение)
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers (логическое значение)
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines (логическое значение)
```


If true, duplicate outlines are merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize (логическое значение)
```


Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword (строковое значение)
```


Sets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights (логическое значение)
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public final void setRemoveSignatures (логическое значение)
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions (значение SaveOptions)
```


Sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions object |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages (логическое значение tryMergeAdjacentSameBackgroundImages)
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public void setUniqueSuffix (строковое значение)
```


Set format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

--------------------

```
PdfFileEditor ed = новый PdfFileEditor();
   ed.setUniqueSuffix ("_%ЧИСЛО%");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setUseDiskBuffer(boolean value) {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer (логическое значение)
```


If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitFromFirst (InputStream inputStream, int location, OutputStream outputStream)
```


Splits from start to specified location,and saves the front part in output Stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 OutputStream outStream = новый FileOutputStream("out.pdf");
 pfe.splitFromFirst (исходный поток, 5, исходящий поток);
```

--------------------

The streams are NOT closed after this operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting point. |
| outputStream | java.io.OutputStream | Output file Stream. |

**Returns:**
boolean - True for success, or false.
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public boolean splitFromFirst (String inputFile, int location, String outputFile)
```


Splits Pdf file from first page to specified location,and saves the front part as a new file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.splitFromFirst("input.pdf", 5, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting point. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
общедоступный ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] количество страниц)
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| numberOfPage | int[][] | The start page and the end page of each document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
общедоступный ByteArrayInputStream[] splitToBulks(String inputFile, int[][] количество страниц)
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file. |
| numberOfPage | int[][] | Array which contains array of double elements, which is start and end pages of document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitToEnd (InputStream inputStream, int location, OutputStream outputStream)
```


Splits from specified location, and saves the rear part as a new file Stream.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 InputStream sourceStream = новый FileInputStream("file1.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.splitToEnd (исходный поток, 5, исходящий поток);
```

--------------------

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting position. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True if splitting was successful.
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public boolean splitToEnd (String inputFile, int location, String outputFile)
```


Splits from location, and saves the rear part as a new file.

--------------------

```
PdfFileEditor pfe = новый PdfFileEditor();
 pfe.splitToEnd("input.pdf", 5, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting position. |
| outputFile | java.lang.String | Output Pdf file path. |

**Returns:**
boolean - True for success, or false.
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
общедоступный ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


Splits the Pdf file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf stream. |

**Returns:**
java.io.ByteArrayInputStream[] - ByteArrayInputStream[] array
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public void splitToPages (InputStream inputStream, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of the soruce document. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number . For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
общедоступный ByteArrayInputStream[splitToPages (строка inputFile)
```


Splits the PDF file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file name. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a single-page PDF document.
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public void splitToPages (String inputFile, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file name. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number . For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### toString() {#toString--}
```
публичная строка toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
публичный окончательный недействительный ожидание ()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
